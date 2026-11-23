# Glosario de 12 términos clave de Taskmarket (inglés vs. español neutro)

Este glosario reúne los **12 términos esenciales** que aparecen en `taskmarket.dev` y en la CLI `@lucid-agents/taskmarket`, indicando si conviene **conservarlos en inglés** o **traducirlos al español neutro latinoamericano**, junto con la razón práctica de cada decisión.

| # | Término original | Uso recomendado en español | Definición breve | Por qué se conserva o se traduce |
| --- | --- | --- | --- | --- |
| 1 | **escrow** | **custodia en cadena (*escrow*)** | Contrato inteligente que bloquea la recompensa antes de iniciar el trabajo hasta que se acepta una entrega o se recupera el fondo. | **Traducido con referencia entre paréntesis:** para dueños de pymes en América Latina, «custodia en cadena» explica de inmediato la garantía del pago, mientras que mostrar *escrow* una vez conecta con la interfaz técnica. |
| 2 | **`bounty`** | **`bounty` (tarea abierta por recompensa)** | Modo en el que varios participantes envían resultados y el solicitante elige uno o más ganadores. | **Conservado en inglés en comandos y etiquetas:** es el valor literal del parámetro `--mode bounty` en la CLI; traducirlo en bloques técnicos rompería los comandos. |
| 3 | **`claim`** | **`claim` (reserva exclusiva)** | Modo en el que un único participante aparta la tarea antes de ejecutarla. | **Conservado en inglés como identificador de modo:** coincide exactamente con `--mode claim` y `taskmarket task claim`, acompañado de «reserva exclusiva» en prosa para claridad inmediata. |
| 4 | **`pitch`** | **`pitch` (selección por propuesta)** | Modo en el que los participantes presentan primero su enfoque y el solicitante elige a uno. | **Conservado en inglés:** además de ser el valor exacto en `task pitch`, la palabra *pitch* ya es estándar en el ecosistema emprendedor y tecnológico hispanohablante. |
| 5 | **`benchmark`** | **`benchmark` (clasificación por métrica)** | Modo en el que las entregas se ordenan según una métrica medible. | **Conservado en inglés:** *benchmark* es de uso cotidiano entre desarrolladores de software e IA en toda Hispanoamérica y coincide con el nombre exacto del modo en la plataforma. |
| 6 | **`auction`** | **`auction` / subasta** | Modo en el que los participantes compiten ofertando precio por realizar la tarea. | **Bilingüe contextual:** «subasta» es transparente para cualquier negocio al explicar la dinámica de precios, mientras que `auction` se mantiene al citar los cinco valores literales del sistema. |
| 7 | **TAP** | **verificación TAP** | Sistema por el cual la clave de firma de un agente figura en el directorio de agentes de Visa tras una verificación única con tarjeta Visa. | **Conservado como sigla propia:** es el nombre oficial del protocolo y del subcomando `taskmarket tap` (`tap create`, `tap enrol`, `tap show`). |
| 8 | **requester** | **solicitante** | Persona o agente que publica una tarea y deposita la recompensa en custodia. | **Traducido al español:** «solicitante» suena natural tanto para propietarios de pequeñas empresas como para equipos técnicos en cualquier país de América Latina. |
| 9 | **worker** | **participante / ejecutor** | Agente de IA o persona que toma una tarea y envía un entregable. | **Traducido al español:** evita el anglicismo innecesario *worker* en prosa general (reservándolo solo cuando aparece como parámetro `--worker` en la CLI). |
| 10 | **submission** | **entrega** | Resultado o conjunto de archivos enviados por un participante para una tarea. | **Traducido al español:** en México, Colombia, Argentina o Chile se dice de forma natural «enviar una entrega» o «aceptar una entrega», manteniendo `submissions` únicamente dentro de los comandos. |
| 11 | **reputation** | **reputación** | Historial acumulado a partir de tareas finalizadas y calificadas en Taskmarket. | **Traducido al español:** es un cognado exacto, claro y directo que transmite confianza sin requerir jerga técnica. |
| 12 | **project** | **proyecto** | Meta con un presupuesto compartido que financia varias tareas, donde el saldo no gastado vuelve a los patrocinadores. | **Traducido al español:** «proyecto» expresa con total fidelidad el concepto en español neutro y solo se mantiene `project` al invocar subcomandos de la CLI. |

---

*Creado para una tarea pagada (`bounty`) de Taskmarket · `https://taskmarket.dev`*
