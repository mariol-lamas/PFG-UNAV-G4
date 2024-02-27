# PFG-UNAV-G4
---
## Objetivos de PFG
Los objetivos principales del PFG consisten en:

•Identificar los objetivos del proyecto a partir de un reto de predicción por clasificación definido sobre una base de datos de campañas de marketing de una institución bancaria.

•Descargar, analizar y preparar el set de datos para el caso de uso

•Construir un modelo de Redes Neuronales (RN) que permita predecir una etiqueta de clase categórica.

•Desarrollar las estrategias necesarias que permitan solucionar con éxito el problema del caso de uso

•Gestionar el trabajo de equipo, cumpliendo el calendario de las sesiones de seguimiento y entregas

•Defender el proyecto en las sesiones y elaborar una memoria final

## Información de los datos iniciales

1 - age (numérico)
2 - job: tipo de trabajo (categórico: "administrativo", "desconocido", "desempleado", "gerencia", "ama de casa", "emprendedor", "estudiante", "trabajador manual", "autónomo", "jubilado", "técnico", "servicios")
3 - marital: estado civil (categórico: "casado", "divorciado", "soltero"; nota: "divorciado" significa divorciado o viudo)
4 - education (categórico: "desconocido", "secundaria", "primaria", "terciaria")
5 - default: ¿tiene crédito en mora? (binario: "sí", "no")
6 - balance: saldo promedio anual, en euros (numérico)
7 - housing: ¿tiene préstamo hipotecario? (binario: "sí", "no")
8 - loan: ¿tiene préstamo personal? (binario: "sí", "no")
8 - car: ¿tiene préstamo de coche? (binario: "sí(1)", "no(0)")

**Relacionado con el último contacto de la campaña actual:**
9 - contact: tipo de comunicación de contacto (categórico: "desconocido", "teléfono", "celular")
10 - day: último día de contacto del mes (numérico)
11 - month: último mes de contacto del año (categórico: "ene", "feb", "mar", ..., "nov", "dic")
12 - duration: duración del último contacto, en segundos (numérico)

**Otros atributos:**
13 - campaign: número de contactos realizados durante esta campaña y para este cliente (numérico, incluye el último contacto)
14 - pdays: número de días que pasaron después de que el cliente fue contactado por última vez en una campaña anterior (numérico, -1 significa que el cliente no fue contactado anteriormente)
15 - previous: número de contactos realizados antes de esta campaña y para este cliente (numérico)
16 - poutcome: resultado de la campaña de marketing anterior (categórico: "desconocido", "otro", "fracaso", "éxito")
17 - subscribed: ¿el cliente se ha suscrito a un depósito a plazo? (binario: "sí", "no")

#Colaboradores
- Itziar Campo Juarros

- Mario Lamas Herrera

- Alexis Sanabria Castro

- Laura Lozano Ferrer

- Luis Llorente Muro

- Alfonso Andrés Lafuente
