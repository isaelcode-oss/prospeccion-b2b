---
name: prospeccion-b2b
description: Reglas para escribir, revisar y preparar correo en frío a empresas (B2B) dirigido a Estados Unidos, Europa o República Dominicana. Decide primero si el país del destinatario permite enviarlo (CAN-SPAM, RGPD y normas nacionales europeas como UWG, LSSI o PECR, y la Ley 172-13 de RD), después aplica el pie legal común, la entregabilidad, el estilo sin frases de plantilla ni de IA y una secuencia de tres correos en español o inglés. Úsala SIEMPRE que el usuario diga «escribe un correo en frío», «cold email», «prospección por correo», «secuencia de correos para captar clientes», «revisa este correo de venta», «¿puedo mandarle correo a empresas de <país>?», o cuando una automatización, un bot o un flujo n8n vaya a enviar correo comercial a gente que no se suscribió. No la uses para correo transaccional, boletines con suscripción ni respuestas a clientes existentes.
---

# Correo en frío B2B

Las reglas completas, los ejemplos y las fuentes legales están en `references/reglas.md`. Léelo
entero antes de escribir o revisar el primer correo de la tarea.

Esta skill no da permiso para enviar. Mandar correo a terceros es una acción sensible: se prepara
el borrador o la campaña y **el usuario autoriza el envío**. Tampoco es asesoría legal. Para campañas de
clientes, la responsabilidad del envío se acuerda antes de empezar.

## Flujo

1. **País del destinatario.** Con la tabla de la sección 1 de `reglas.md`, decide si se puede
   enviar. Si el país está en «No», dilo y propón otro canal. Si no se sabe el país o el
   destinatario es un autónomo, aplica la regla más estricta.
2. **Base y origen del dato.** Anota de dónde salió cada dirección y, en la UE, el interés
   legítimo. En RD, solo datos de fuentes públicas o dados por el titular.
3. **Redactar.** Sigue las secciones 4 a 7: corto, una idea y una pregunta, en el idioma del
   destinatario, sin frases prohibidas y con asunto honesto.
4. **Pie común** de la sección 2: identidad, dirección postal, origen del dato y baja.
5. **Revisar con la lista de la sección 9** y mostrar al usuario el resultado con la lista marcada.

## Salida

Para cada correo: país y base legal en una línea, asunto, cuerpo y pie. Al final, la lista de la
sección 9 con cada punto marcado como cumplido o pendiente y su motivo.

Si una afirmación legal de `reglas.md` figura como «fuente secundaria» o «sin verificar» y la
campaña va a ese país, avisa al usuario antes de prepararla.
