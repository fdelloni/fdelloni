# Franco Delloni

Abogado y builder. Construyo software en la intersección de **legaltech, fintech y proptech**, con foco en el mercado argentino: sistemas que combinan derecho aplicado, automatización e IA en producción.

🌐 [francodelloni.com](https://francodelloni.com) · 📍 Sunchales, Santa Fe, Argentina

## Qué estoy construyendo

| Proyecto | Qué es | Stack |
|---|---|---|
| [**Sunchales Transparente**](https://github.com/fdelloni/sunchales-transparente) | Plataforma cívica de transparencia para la Municipalidad de Sunchales: datos abiertos, digesto normativo, contrataciones, remuneraciones y asistente ciudadano con RAG. Pipeline automatizada que scrapea, procesa e indexa fuentes oficiales todos los días. | Next.js · TypeScript · Supabase/Postgres (RLS, pgvector) · GitHub Actions · Gemini |
| [**alquil.app — bot de WhatsApp**](https://github.com/fdelloni/alquilapp-whatsapp-bot) | Asistente de gestión de alquileres por WhatsApp: consultas jurídico-operativas con RAG sobre normativa locativa argentina (CCyC, DNU 70/2023), recibos PDF, facturas, recordatorios. Con banco de QA automatizado de 105 preguntas que corre por cron y commitea sus reportes. | Node.js · Express · Twilio · Supabase · pgvector · Gemini/Groq/Cohere |
| [**SolidFin**](https://github.com/fdelloni/solidfin) | Plataforma de préstamos con garantía solidaria grupal (en desarrollo). | — |

## Cómo trabajo

- **Del expediente al deploy**: el conocimiento de dominio (derecho civil, locaciones, compliance) va embebido en la lógica del software, no en un PDF aparte.
- **Evaluación antes que intuición**: mis sistemas con LLMs tienen bancos de QA versionados; cada regla del prompt existe porque un caso de test falló.
- **Datos honestos**: si un dato no tiene fuente verificable, el sistema lo etiqueta como pendiente. No se inventa información.
