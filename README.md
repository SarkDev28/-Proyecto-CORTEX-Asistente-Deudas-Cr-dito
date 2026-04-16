
# -Proyecto-CORTEX-Asistente-Deudas-crédito
## Integrantes
- Joseph Santiago Piña Torres
- Andres Camilo Gamarra Jaimes
- Jasbleiny Mariana Pedroza Redondo
<img width="975" height="903" alt="Captura de pantalla 2026-02-19 111511" src="https://github.com/user-attachments/assets/a526c84e-3671-44fb-a04d-8a452a5fc546" />

# -Proyecto-CORTEX-Asistente-Deudas-crédito-RADAR
<img width="626" height="596" alt="image" src="https://github.com/user-attachments/assets/0f5f59ab-05a2-4fb9-920f-402cef51638b" />

- Atención (9/10)
Requiere alta precisión para interpretar tasas, plazos, contratos y datos financieros. Un error mínimo puede afectar recomendaciones económicas, por lo que necesita fuerte control y verificación de información.

- Memoria (8/10)
Debe manejar conceptos financieros, normativas y modelos de cálculo, además de recordar el contexto del usuario (ingresos, deudas, objetivos) para mantener coherencia en sus recomendaciones.

- Lenguaje (9/10)
Necesita explicar términos técnicos de forma clara y rigurosa, estructurar argumentos financieros y comunicar riesgos sin ambigüedades.

- Emoción (6/10)
Aunque es un sistema técnico, debe mostrar empatía moderada ante el estrés financiero del usuario, manteniendo un tono profesional y no terapéutico.

# -Plan de Trabajo Fase 2: "Los Sentidos del Agente" (Inputs & Filtros)
- Semana 4
<img width="401" height="922" alt="image" src="https://github.com/user-attachments/assets/f605d297-25fa-4f4e-a771-6c623fe9b091" />

# -Diagrama de Flujo Perceptivo (Miro)
- Semana 5
<img width="1773" height="637" alt="Captura de pantalla 2026-03-19 103614" src="https://github.com/user-attachments/assets/597aa2f2-5e1f-4125-adf2-afa2a8b1359b" />

# -Diseñando el "Gatekeeper" (GitHub)
- Semana 6
<img width="687" height="658" alt="Captura de pantalla 2026-03-19 104055" src="https://github.com/user-attachments/assets/8578b8c8-e564-4837-8c7e-91fbf61a06b9" />
<img width="402" height="838" alt="Captura de pantalla 2026-03-19 104132" src="https://github.com/user-attachments/assets/ccf77597-80c5-4747-8cb7-637dff0cc867" />

# -El Disco Duro
- Semana 7
<img width="1857" height="943" alt="image" src="https://github.com/user-attachments/assets/e5e8e531-4c1f-447d-ab29-561ac248e5e0" />

# - La RAM Cognitiva
- Semana 8
<img width="1936" height="738" alt="image" src="https://github.com/user-attachments/assets/33686bdb-b83c-45b3-aca7-4ebc5e5c3821" />

# -El Bibliotecario
- Semana 9

[START]
   ↓
[Nueva Pregunta del Usuario]
   ↓
[Normalizar Input]
(Limpiar texto + detectar intención + keywords)
   ↓
{¿Está la respuesta en RAM?}
   ↓                ↓
  Sí               No
   ↓                ↓
[Responder]   [Buscar en LTM]
                   ↓
          [Convertir a embeddings / keywords]
                   ↓
          [Buscar en base de conocimiento]
                   ↓
          [Rankear resultados]
                   ↓
          [Seleccionar Top 3-5]
                   ↓
          [Construir contexto]
                   ↓
               ↓
        [Generar respuesta]
               ↓
        [Actualizar RAM]
               ↓
{¿RAM excede límite?}
   ↓                ↓
  Sí               No
   ↓                ↓
[Eliminar antiguo]   ↓
   ↓                ↓
        [Esperar siguiente input]
               ↓
{¿Timeout 10 min?}
   ↓                ↓
  Sí               No
   ↓                ↓
[Limpiar RAM]   [Mantener RAM]
   ↓
[END]


