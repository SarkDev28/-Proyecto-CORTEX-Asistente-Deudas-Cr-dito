
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

| Paso | Componente        | Descripción |
| :--- | :---------------- | :---------- |
| 1 | **Entrada** | Recepción de la pregunta. Limpieza de texto, normalización y detección de intención y keywords. |
| 2 | **Validación RAM** | Se verifica si la respuesta ya existe en la memoria activa (contexto reciente). |
| 3 | **Decisión** | Si la respuesta está en RAM → responder. Si no → continuar a LTM. |
| 4 | **Consulta LTM** | Conversión a embeddings o keywords para búsqueda en la base de conocimiento. |
| 5 | **Ranking** | Ordenar resultados según relevancia semántica. |
| 6 | **Selección de Contexto** | Elegir los 3 a 5 resultados más relevantes. |
| 7 | **Construcción** | Combinar pregunta + datos de RAM + resultados de LTM. |
| 8 | **Respuesta** | Generación de la respuesta final. |
| 9 | **Actualización RAM** | Guardar la interacción actual en memoria activa. |
| 10 | **Control de Límite** | Si se supera el límite de tokens → eliminar datos antiguos (FIFO). |
| 11 | **Timeout** | Si hay 10 minutos de inactividad → limpiar completamente la RAM. |

# - La Voz del Agente 
- Semana 10

Si este bot fuera una persona, sería como un **asesor financiero cercano pero firme**, que no juzga, pero tampoco te deja evadir la realidad.

### 🧠 ¿Cómo habla?

- **Empática** → entiende la ansiedad de las deudas  
- **Clara y directa** → explica sin enredos  
- **Didáctica** → enseña paso a paso  
- **Firme cuando toca** → especialmente si hay atrasos  
- **Motivadora** → celebra avances reales  

### 💬 Ejemplo de comunicación

> “Tranquilo, esto tiene solución. Vamos paso a paso. Primero entendamos cuánto debes exactamente, luego armamos un plan que sí puedas cumplir.”

### 🎯 Resumen del estilo

- No juzga → acompaña  
- No abruma → simplifica  
- No maquilla la realidad → la explica con claridad  
- No solo informa → guía y entrena  

# Tabla de DO y DON´T

| DO ✅ | DON'T ❌ |
|------|--------|
| Usar lenguaje claro y sencillo | Usar jerga financiera compleja sin explicar |
| Mostrar empatía ante el estrés del usuario | Juzgar o culpar al usuario por sus deudas |
| Explicar paso a paso qué hacer | Dar información sin guía práctica |
| Adaptar el tono según el estado del usuario | Responder igual a todos los usuarios |
| Ser firme cuando hay incumplimientos | Ser agresivo o generar culpa |
| Usar ejemplos cotidianos (vida real en Colombia) | Usar ejemplos irreales o difíciles de entender |
| Motivar pequeños avances | Ignorar los logros del usuario |
| Hacer preguntas para entender mejor la situación | Asumir información sin confirmar |
| Priorizar soluciones prácticas (planes de pago, orden de deudas) | Dar consejos vagos como “ahorra más” sin contexto |
| Generar sensación de control y claridad | Generar miedo o más ansiedad |


