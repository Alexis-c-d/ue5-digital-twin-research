# UE5 Digital Twin Research
Evaluación de la fidelidad física de Unreal Engine 5 como entorno de simulación para robots móviles diferenciales.

## Research Overview
This repository documents a research project evaluating the physical fidelity of Unreal Engine 5 as a simulation environment for differential-drive mobile robots.

## Research Topic
**Evaluación de la fidelidad física de Unreal Engine 5 como entorno de simulación para robots móviles diferenciales**

## Research Question
¿Qué tan precisa es la simulación física de Unreal Engine 5 al representar el comportamiento cinemático de un robot móvil diferencial en comparación con los modelos matemáticos teóricos?

## Hypothesis
Unreal Engine 5 puede reproducir el comportamiento cinemático de un robot móvil diferencial con un error inferior al 5 % respecto a los resultados obtenidos mediante modelos teóricos en condiciones controladas.

## Object of Study
La precisión con la que el motor de físicas de Unreal Engine 5 reproduce el comportamiento cinemático de un robot móvil diferencial en comparación con los modelos matemáticos teóricos utilizados en robótica.

## Justification
Los simuladores son una herramienta fundamental en el desarrollo de sistemas robóticos, ya que permiten probar algoritmos y diseños antes de construir prototipos físicos. Tradicionalmente se han utilizado plataformas como Gazebo o Webots; sin embargo, los motores gráficos comerciales como Unreal Engine 5 han comenzado a emplearse en aplicaciones de simulación robótica debido a su capacidad de renderizado fotorrealista y sus avanzados motores de físicas.

A pesar de su creciente popularidad, existe una necesidad de evaluar de manera más rigurosa la precisión física de estos entornos cuando se utilizan para representar el comportamiento de robots móviles. Esta investigación busca determinar si Unreal Engine 5 ofrece una fidelidad física suficiente para emplearse en etapas tempranas de diseño y validación de robots diferenciales.

## Methodology
1. **Virtual Robot Design**: Create a differential-drive mobile robot within Unreal Engine 5
2. **Controlled Test Environment**: Build a test environment with known parameters
3. **Test Cases**: Execute rectilinear displacement and rotation tests
4. **Comparison**: Compare simulation results with theoretical mathematical models
4. **Error Analysis**: Calculate percentage errors for each test

## Test Scenarios
- Rectilinear displacement tests
- Rotation tests  
- Trajectory comparison (simulated vs theoretical)
- Distance and angle error calculations

## Expected Outcomes
- Quantitative error percentages for each test case
- Validation of UE5 physical fidelity for differential-drive robots
- Identification of error sources and limitations
- Recommendations for digital twin applications

## Future Work
- Connection of digital twin with physical robot for real-time feedback
- Reinforcement learning integration within the simulation environment
- Expansion to other robot kinematic models

## Tools & Technologies
- **Unreal Engine 5** (Chaos Physics)
- **Mathematical models**: Differential-drive kinematic equations
- **Comparison metrics**: Position error, orientation error, trajectory deviation

## Documents
- `Esquema_Descriptivo_Detallado_UE5.docx` - Detailed descriptive schema
- `propuesta_investigacion_UE5.docx` - Full research proposal