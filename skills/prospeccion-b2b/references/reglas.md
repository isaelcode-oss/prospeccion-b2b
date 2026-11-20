# Correo en frío B2B: reglas completas

Actualizado el 2026-11-19. Texto propio. Algunas ideas generales de estilo (frases prohibidas,
secuencia de tres correos, motivos de respuesta) se inspiran en `skills/email_frameworks.md` de
ethanplusai/sellbird; no se copió texto ni ejemplos.

Reglas para escribir y enviar correo en frío a empresas en **Estados Unidos, Europa y República
Dominicana**. Nada se envía sin autorización explícita de quien firma la campaña, y el correo de
marketing va separado del transaccional (avisos, facturas, cuentas).

**Aviso:** esto es una guía práctica, no asesoría legal. Las normas cambian; revisa la fecha y las
fuentes de la sección 10 y consulta a un abogado antes de una campaña real.

Orden de importancia: **ley del país del destinatario > entregabilidad > calidad de la lista > texto**.
Un correo perfecto a un país donde está prohibido, o desde un dominio quemado, no sirve.

## 1. Primero el país: ¿se puede enviar?

Manda la ley del país **del destinatario**, no la nuestra. Si no se sabe el país o la persona es
un autónomo, se aplica la regla más estricta de la lista.

| Mercado | ¿Correo en frío B2B sin consentimiento previo? | Condición clave |
| --- | --- | --- |
| **EE. UU.** | Sí (opt-out) | CAN-SPAM entero (sección 2). No hay excepción B2B. |
| **Reino Unido** | Sí, a suscriptores corporativos (sociedades, LLP) | La regla de consentimiento de PECR reg. 22 se aplica a suscriptores individuales: autónomos y algunas sociedades personales necesitan consentimiento. |
| **Francia** | Sí, a profesionales | Interés legítimo solo si la oferta tiene que ver con su profesión. Identidad del remitente y forma sencilla de rechazar en cada envío (CNIL). |
| **Alemania** | **No** | UWG § 7.2.2 exige consentimiento previo y expreso del destinatario, sin distinguir empresas. Excepción: cliente propio con productos similares (§ 7.3). |
| **Austria** | **No** | TKG 2021 § 174.3: consentimiento previo. Excepción de cliente propio (§ 174.4), que no vale si el destinatario está en la lista ECG. |
| **España** | **No** | LSSI art. 21.1 prohíbe el correo promocional no solicitado ni autorizado. Excepción: relación contractual previa y productos similares (art. 21.2). |
| **Italia** | **No** | Codice privacy art. 130, apartados 1 y 2: consentimiento para marketing por correo. Excepción de cliente propio (art. 130.4). |
| **Otros países de la UE** | **Tratar como No** | No verificados todavía. Leer la norma nacional antes de enviar. |
| **República Dominicana** | Sí, con condiciones | Ley 172-13 art. 71: solo datos de documentos accesibles al público, dados por el titular o con su consentimiento. Retiro o bloqueo cuando lo pida. |

Para toda la UE, además de la regla del país, se aplica el RGPD: base de **interés legítimo**
documentada (por qué esta persona y por qué ahora), decir de dónde salió su dato y ofrecer la
oposición en el primer correo.

Si un país está en "No", no se manda correo en frío. La alternativa es otro canal permitido por
ese país o un contenido al que la persona se suscriba sola.

## 2. Lo que lleva todo correo (piso común)

Este piso cumple los tres mercados a la vez. Se aplica siempre, aunque el país sea permisivo.

- **Identidad real.** Nombre, empresa y firma verdaderos. Nunca hacerse pasar por cliente,
  conocido o persona particular. Cabeceras y remitente sin falsear.
- **Asunto honesto.** Nada de "re:" o "fwd:" en un hilo que no existe, ni insinuar una relación
  previa.
- **Que se entienda que es comercial.** No hace falta poner "publicidad", pero el correo no se
  disfraza de otra cosa.
- **Dirección postal física válida** del remitente en la firma (EE. UU. la exige: calle, apartado
  postal registrado o buzón privado autorizado).
- **Baja sencilla.** Una línea del estilo "Si no quieres más correos, responde «baja»". Debe
  funcionar al menos 30 días tras el envío. La ley de EE. UU. da 10 días hábiles para cumplirla;
  nosotros la aplicamos **en el momento** y para siempre.
- **Cualquier forma de "no" es baja.** "No me escribas", "quítame", "no interesa" o lo mismo en
  inglés: se trata como baja aunque esté a mitad de conversación.
- **Lista de no contactar única** por remitente, revisada antes de cada envío. En RD, el titular
  puede pedir en cualquier momento que se retire o bloquee su nombre.
- **Origen del dato** (UE y RD). Una línea del tipo "Vi tu correo en la web de {{empresa}}". En RD
  solo se usan datos de documentos accesibles al público o dados por el propio titular.
- **Oposición visible** (UE). La línea de baja vale como aviso del derecho a oponerse, pero tiene
  que aparecer desde el primer correo.
- **Sin píxeles de apertura ni seguimiento de clics.** Perjudican la entregabilidad y, según
  resúmenes de terceros, los reguladores de Francia e Italia piden consentimiento para medir
  aperturas individuales.
- **España:** la baja debe ser una dirección de correo válida donde ejercerla (LSSI art. 21.2).
  Responder al mismo correo cumple si esa dirección se atiende.

Pie mínimo, ejemplo en español:

```
<Nombre> · <Empresa>
<dirección postal>
Vi tu correo en <fuente>. Si no quieres más correos, responde «baja» y no vuelvo a escribirte.
```

En inglés:

```
<Name> · <Company>
<postal address>
I found your email on <source>. If you'd rather not hear from me, reply "stop" and I won't write again.
```

## 3. Entregabilidad

- **Dominio secundario** para el frío (por ejemplo, una variante de la marca), nunca el dominio
  principal ni el de un cliente. Si se quema, no arrastra al correo real.
- SPF, DKIM y DMARC configurados y comprobados antes del primer envío. Calentar el dominio y el
  buzón semanas antes.
- **Verificar cada dirección** antes de mandar. Un rebote alto quema el dominio.
- **Lotes pequeños y segmentados.** Pocos destinatarios muy relevantes rinden más que un envío
  masivo.
- **Texto plano.** Sin imágenes, sin adjuntos y como mucho un enlace (ninguno en el primer
  correo). Sin mayúsculas sostenidas ni frases de spam ("gratis", "garantizado", "actúa ya").
- Una sola queja por spam cuesta más que cien envíos.

## 4. Cómo escribirlo

La regla de fondo: **que parezca escrito por una persona que se fijó en algo**, no por un
vendedor ni por una IA. Si al leerlo en voz alta suena a anuncio, se rehace.

- **Corto.** El primer correo, entre 25 y 50 palabras, y nunca más de 75. Los siguientes, más
  cortos. Tiene que caber en la pantalla de un móvil.
- **Una sola idea.** Una observación, una conexión con un problema y una pregunta.
- **Sobre la otra persona.** Su empresa o su situación aparecen antes que nosotros. En el primer
  correo, idealmente, el producto ni se nombra.
- **Pide una respuesta, no una venta.** El objetivo es abrir conversación. Una pregunta fácil de
  contestar ("¿lo tienen resuelto?") rinde más que pedir una reunión.
- **Tono.** De igual a igual y frases cortas. Con directivos, aún más breve. Con perfiles
  técnicos, concreto y sin adjetivos. Con dueños de pequeños negocios, cercano pero sin vender.
- **Idioma del destinatario.** Español en RD y España, inglés en EE. UU. y Reino Unido, el idioma
  local cuando sea viable. No se traduce una plantilla palabra por palabra.

### Prohibido

Estas frases delatan una plantilla o un texto de IA:

| En español | En inglés |
| --- | --- |
| "Espero que estés bien" | "I hope this finds you well" |
| "Te escribo porque…", "Quería contactarte" | "Reaching out because", "I wanted to" |
| "Solo para dar seguimiento" | "Just following up", "circling back" |
| "Imagina que…", "¿Y si te dijera…?" | "Picture this", "Imagine if", "What if I told you" |
| "En el mundo actual…" | "In today's…" |
| "Revolucionario", "disruptivo", "de vanguardia" | "Game-changer", "cutting-edge" |
| "¿Te interesa una llamada rápida?" | "Worth a quick call?" |
| "Sin compromiso", "sin presión" | "No pressure", "no obligation" |
| "¿Eres la persona indicada?" | "Are you the right person?" |

Tampoco se usa:
- Rayas o guiones entre ideas.
- Signos de exclamación.
- Negritas, viñetas, listas o títulos.
- Paréntesis de relleno.
- Varias preguntas en un mismo correo.
- Más de una ventaja del producto.
- Empezar con "Yo" o "Nosotros".
- Halagos vacíos ("se ve que han construido algo grande").

## 5. Secuencia de tres correos

Cada correo trae un ángulo nuevo con asunto nuevo y no menciona el anterior. Se espacian entre
dos y siete días, y se para tras el tercero o con cualquier respuesta negativa.

**1. La observación.** Algo concreto que se vio de su empresa, con qué problema conecta y una
pregunta.

```
Asunto: pedidos de noche

<Nombre>, vi que <empresa> recibe los pedidos solo por WhatsApp y el horario publicado termina a las 6 de la tarde.

¿Qué pasa hoy con los pedidos que llegan después?
```

```
Subject: late orders

<Name>, I saw that <company> takes orders only through WhatsApp, and your posted hours end at 6 p.m.

What happens today to the orders that come in later?
```

**2. El ángulo.** Un dolor concreto, cómo lo resolvemos en una frase y una pregunta directa.

```
Asunto: facturas a mano

<Nombre>, en muchas distribuidoras alguien pasa cada pedido del correo al sistema de facturación, uno por uno.

Nosotros conectamos los dos para que ocurra solo. ¿En <empresa> eso ya está resuelto?
```

**3. El cierre.** Entre 10 y 30 palabras, sin vender ni culpabilizar.

```
Asunto: cierro aquí

<Nombre>, cierro aquí para no llenarte el buzón. Si más adelante te sirve, me respondes y seguimos.
```

## 6. Asuntos

- En minúsculas y de dos a cinco palabras, como un correo interno.
- Sin el nombre de la persona y sin "pregunta rápida".
- Buenos: `<empresa> web`, `llamadas perdidas`, `una idea para <empresa>`, `lo dejo aquí`.
- Malos: `transforma tu negocio con IA`, `oferta exclusiva`, `3 formas de crecer`.

## 7. Por qué alguien contesta

Cada correo se construye sobre **uno** de estos cuatro motivos. Si no tiene ninguno, se
reescribe.

1. **Reconocimiento.** Se nombra un problema que vive, con sus palabras y con detalle. Es el más
   fuerte.
2. **Curiosidad real.** Sabemos algo que querría saber, y se lo damos si responde. Nunca se
   inventa.
3. **Sí fácil.** Una pregunta tan barata de contestar que responder cuesta menos que borrar.
4. **Prueba de un par.** Un caso real y público de alguien de su sector. Solo si es verdad y se
   puede comprobar.

Las cifras, los casos y los clientes que se citan son reales y tienen fuente. Sin testimonios
inventados.

## 8. Cuando responden

- **Escuchar y confirmar qué preocupa** antes de contestar. Una objeción se aclara, no se
  "vence".
- Si es presupuesto, autoridad, necesidad o momento, se pregunta cuál es y se responde solo a eso.
- **"No"** cierra la conversación con un agradecimiento y la baja aplicada.
- Si preguntan si el correo es automático o lo escribió una IA, **se dice la verdad**.
- Ofertas, precios y enlaces solo se mandan cuando hay interés real, nunca en el primer correo.

## 9. Antes de enviar

- [ ] País del destinatario identificado y permitido en la tabla de la sección 1.
- [ ] En la UE, interés legítimo anotado para esta lista y esta campaña.
- [ ] Dato de fuente pública o dado por el titular, y la fuente anotada.
- [ ] Dirección verificada y fuera de la lista de no contactar.
- [ ] Pie completo: identidad, dirección postal, origen del dato y baja.
- [ ] Asunto honesto, sin píxel y como mucho un enlace (ninguno en el primero).
- [ ] Una idea, una pregunta, menos de 75 palabras y ninguna frase prohibida.
- [ ] Todo lo que afirma es verdad y se puede comprobar.
- [ ] Quien firma la campaña autorizó el envío.

## 10. Fuentes y estado de verificación (2026-11-19)

**Verificado en la fuente primaria:**
- **CAN-SPAM:** guía de la FTC, https://www.ftc.gov/business-guidance/resources/can-spam-act-compliance-guide-business.
  No hay excepción B2B y la multa llega a 53.088 USD por correo.
- **Ley 172-13 de RD:** art. 27 (excepciones al consentimiento, entre ellas las fuentes de
  acceso público) y art. 71 (tratamiento con fines de publicidad y prospección comercial, y
  retiro o bloqueo a petición del titular). Texto leído en la compilación
  de un bufete (https://drlawyer.com/espanol/leyes/ley-172-13-sobre-proteccion-de-datos-de-caracter-personal/);
  la versión oficial en PDF está en https://www.sb.gob.do/regulacion/leyes/ley-no-172-13-proteccion-de-los-datos/.

- **RGPD** (texto oficial en EUR-Lex): art. 14.3.b (informar a más tardar en la primera
  comunicación si los datos se usan para comunicarse con el interesado) y art. 21.2-4 (oposición a
  la mercadotecnia directa, mencionada explícitamente a más tardar en la primera comunicación).
- **Alemania:** UWG § 7, https://www.gesetze-im-internet.de/uwg_2004/__7.html
- **Austria:** TKG 2021 § 174, https://www.ris.bka.gv.at/eli/bgbl/i/2021/190/P174/NOR40238632
- **España:** LSSI art. 21, https://www.boe.es/buscar/act.php?id=BOE-A-2002-13758
- **Reino Unido:** PECR reg. 22 (versión con las modificaciones del 5 de febrero de 2026),
  https://www.legislation.gov.uk/uksi/2003/2426/regulation/22
- **Francia:** página de la CNIL sobre prospección por correo,
  https://www.cnil.fr/fr/la-prospection-commerciale-par-courrier-electronique
- **Italia:** resolución del Garante del 15 de mayo de 2013 sobre el art. 130 del Codice privacy
  (docweb 2543820).

**Solo en fuente secundaria:**
- Consentimiento para píxeles de apertura en Francia e Italia.
- Reglas de Irlanda, Países Bajos, Bélgica, Polonia y Chequia. Por eso la tabla las trata como «No».

**Sin verificar:**
- Que la Ley 126-02 de RD no tenga reglas específicas de correo no solicitado. No se encontraron.
- En RD hay un proyecto de ley de protección de datos personales presentado el 17 de marzo de
  2026, que no es ley. Si se aprueba, esta guía se revisa.

Antes de la primera campaña real en un país nuevo, se lee la norma primaria de ese país y se
actualiza esta sección. Para clientes, la responsabilidad legal del envío y la revisión con un
abogado se acuerdan antes de empezar.
