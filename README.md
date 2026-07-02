# Franco Delloni

Abogado y builder. Construyo software en la intersección de **legaltech, fintech y proptech**, con foco en el mercado argentino: sistemas que combinan derecho aplicado, automatización e IA en producción.

🌐 [francodelloni.com](https://francodelloni.com) · 📍 Sunchales, Santa Fe, Argentina

## En producción

| Proyecto | Qué es | Stack |
|---|---|---|
| **[Sunchales Transparente](https://ciudadan.com)** · [código](https://github.com/fdelloni/sunchales-transparente) | Plataforma cívica de transparencia para la Municipalidad de Sunchales: datos abiertos, digesto normativo, contrataciones, remuneraciones y asistente ciudadano con RAG. Pipeline automatizada que scrapea, procesa e indexa fuentes oficiales todos los días. | Next.js · TypeScript · Supabase/Postgres (RLS, pgvector) · GitHub Actions · Gemini |
| **[alquil.app](https://alquil.app)** · [bot (código)](https://github.com/fdelloni/alquilapp-whatsapp-bot) | Gestión de alquileres para Argentina: plataforma web + asistente de WhatsApp con RAG sobre normativa locativa (CCyC, DNU 70/2023), recibos PDF, facturas y recordatorios. Banco de QA automatizado de 105 preguntas que corre por cron. | Node.js · Express · Twilio · Supabase · pgvector · Gemini/Groq/Cohere |

## En desarrollo

| Proyecto | Qué es | Vertical |
|---|---|---|
| **[d.lex](https://dlex-orpin.vercel.app)** | Plataforma de arbitraje y resolución de disputas online. | Legaltech |
| **[SolidFin](https://github.com/fdelloni/solidfin)** | Préstamos con garantía solidaria grupal. | Fintech |
| **isolventia** | Motor de scoring crediticio para personas físicas y jurídicas en Argentina. | Fintech |

## También explorando

Prototipos e ideas en curso: **Artemisa Rastro** (informes de personas / due diligence), **Tambo-IA** (identificación de ganado con IA para el tambo), **Matcheo** e **Idearium** (comunidad y conexión por afinidad).

> Varios de estos productos son comerciales, así que su código es privado. Los links de arriba llevan al producto en vivo; donde el proyecto es abierto, sumo el link al código.

## Cómo trabajo

- **Del expediente al deploy**: el conocimiento de dominio (derecho civil, locaciones, compliance) va embebido en la lógica del software, no en un PDF aparte.
- **Evaluación antes que intuición**: mis sistemas con LLMs tienen bancos de QA versionados; cada regla del prompt existe porque un caso de test falló.
- **Datos honestos**: si un dato no tiene fuente verificable, el sistema lo etiqueta como pendiente. No se inventa información.
