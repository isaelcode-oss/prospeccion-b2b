# prospeccion-b2b

Skill para agentes de IA (formato Agent Skills: Claude Code, Codex y compatibles) que escribe,
revisa y prepara **correo en frío a empresas** dirigido a **Estados Unidos, Europa y República
Dominicana**, en español o inglés.

Antes de redactar, decide si el país del destinatario permite el envío. Después aplica un pie
legal común, buenas prácticas de entregabilidad y un estilo que no suena a plantilla ni a IA.

> **No es asesoría legal.** Es una guía práctica con fuentes y fecha de verificación
> (`skills/prospeccion-b2b/references/reglas.md`, sección 10). Las normas cambian. Consulta a un
> abogado antes de una campaña real.

## Qué cubre

- Tabla por país:
  - EE. UU. (CAN-SPAM).
  - Reino Unido (PECR).
  - Francia (CNIL).
  - Alemania (UWG § 7).
  - Austria (TKG 2021 § 174).
  - España (LSSI art. 21).
  - Italia (Codice privacy art. 130).
  - República Dominicana (Ley 172-13).
  - RGPD para toda la UE (arts. 14 y 21).
- Pie común que cumple los tres mercados: identidad, dirección postal, origen del dato y baja.
- Entregabilidad: dominio secundario, SPF, DKIM y DMARC, verificación de direcciones, texto plano
  y nada de píxeles de seguimiento.
- Estilo: frases prohibidas en español e inglés, secuencia de tres correos, asuntos y cómo
  responder.
- Lista de revisión antes de enviar.

## Instalación

Claude Code:

```bash
git clone https://github.com/isaelcode-oss/prospeccion-b2b.git
mkdir -p ~/.claude/skills
cp -r prospeccion-b2b/skills/prospeccion-b2b ~/.claude/skills/
```

Se activa sola con pedidos como «escribe un correo en frío para empresas de España» o «¿puedo
mandar correo de prospección a Alemania?».

## Origen

Algunas ideas generales de estilo, como las frases a evitar, la secuencia de tres correos y los
motivos por los que alguien responde, se inspiran en `skills/email_frameworks.md` de
[ethanplusai/sellbird](https://github.com/ethanplusai/sellbird). El texto, los ejemplos y toda la
parte legal son propios.

## Licencia

[CC BY 4.0](LICENSE). Puedes usarla y adaptarla citando la fuente: isaelcode.Dev.
