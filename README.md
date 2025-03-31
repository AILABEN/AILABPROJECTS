Flujo Automatizado con Make: AILAB Nodo Microsoft - Universidad EAFIT
Este documento describe el funcionamiento de un flujo automatizado diseñado por el AILAB del Nodo Microsoft en la Universidad EAFIT, en colaboración con el área de Atracción. El objetivo de este flujo es optimizar la generación y distribución de actualizaciones de formularios relacionados con el ejercicio 'Oportunidades y retos'.
¿De qué trata el flujo?
El flujo tiene como propósito automatizar el ciclo de creación, actualización y envío de formularios de satisfacción para el área de Atracción, asegurando que los involucrados reciban las últimas versiones sin intervención manual. Esta solución aprovecha herramientas integradas en Make (antes Integromat) y utiliza inteligencia artificial para generar textos, alimentar documentos y distribuir la información por correo electrónico.
Componentes del flujo
A continuación, se describen los módulos usados en el flujo automatizado:
- Microsoft 365 Excel: Monitorea nuevas filas en una tabla con respuestas o datos del formulario.
- OpenAI (x2): Genera texto o resúmenes a partir de los datos, usando modelos de lenguaje como GPT-4o.
- Google Docs: Inserta automáticamente el contenido generado en un documento de Google.
- HTTP: Recupera el archivo (PDF o DOCX) generado desde Google Docs para su distribución.
- Microsoft 365 Email (Outlook): Envía el documento como archivo adjunto a los destinatarios definidos.
Impacto en el área de Atracción
Este flujo permite al equipo de Atracción reducir significativamente el tiempo invertido en tareas operativas, al automatizar la consolidación de información, redacción de documentos y su distribución por correo electrónico. De esta manera, el equipo puede enfocarse en tareas estratégicas de análisis y toma de decisiones.
