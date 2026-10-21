[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=Chander98MB/MSFP2)

# Práctica 2: Modelo de control del sistema cardiovascular mediante el modelo Windkessel

## Información del estudiante

Zaid Alexander Arredondo Medina [L23212180@tectijuana.edu.mx]

Modelado de Sistemas Fisiológicos

Ingeniería Biomédica

## Docente

Dr. Paul Antonio Valle Trujillo; paul.valle@tectijuana.edu.mx

Departamento de Ingeniería Eléctrica y Electrónica, Tecnológico Nacional de México/IT Tijuana, Blvd. Alberto Limón Padilla s/n, Tijuana, C.P. 22454, B.C., México.

## Descripción de la asignatura

El modelizado de sistemas fisiológicos es una herramienta importante en Ingeniería Biomédica, permite comprender el funcionamiento del cuerpo humano, así como diseñar y evaluar terapias y dispositivos médicos; se define como el proceso de formular modelos matemáticos o computacionales que representan el comportamiento y la interacción de los sistemas biológicos y fisiológicos. Esta asignatura pretende aportar al perfil del Ingeniero Biomédico la capacidad de realizar investigación científica en el área de Biología de Sistemas con la finalidad de dirigir y participar en equipos de trabajo interdisciplarios en contextos nacionales e internacionales, así como de proporcionar soluciones informáticas para resolver problemas en el campo de la Ingeniería Biomédica con ética profesional; lo anterior al proporcionar al estudiante bases sólidas para modelizar sistemas y diseñar controladores para la solución de problemas en las áreas de atención médica y del sector industrial médico. La construcción de analogías entre circuitos eléctricos y sistemas fisiológicos para la formulación de modelos matemáticos y el diseño de controladores mediante la experimentación in silico brindan herramientas de gran aplicación en el quehacer profesional del Ingeniero Biomédico.

La asignatura de Modelado de Sistemas Fisiológicos forma parte del plan de estudios de la carrera en Ingeniería Biomédica con la siguiente competencia general del curso: Utiliza las propiedades de los circuitos RLC para describir la dinámica de sistemas fisiológicos, obtener modelos matemáticos y aplicar el control clásico, esto con el objetivo de integrar los principios de la Ingeniería de Control, la Electrónica Analógica y las Ciencias de la Computación con la Anatomía y Fisiología del cuerpo humano para proporcionar descripciones cuantitativas y cualitativas de sistemas fisiológicos complejos con el objetivo de modelizar, analizar, controlar, ilustrar y predecir su dinámica tanto en el corto como en el largo plazo.

## Objetivos

1. Formular la función de transferencia y el sistema de ecuaciones diferenciales del modelo cardiovascular.
2. Evaluar el comportamiento dinámico del sistema cardiovascular bajo tres condiciones hemodinámicas: Normotenso, Hipotenso e Hipertenso.
3. Diseñar y sintonizar controladores PID analógicos para corregir desviaciones en la presión arterial en condiciones patológicas.
4. Emular las señales hemodinámicas en Simulink/Simscape para lazo abierto y lazo cerrado en los tres casos fisiológicos.
5. Implementar y simular la respuesta numérica del modelo dinámico en MATLAB a partir del sistema de ecuaciones diferenciales ordinarias (EDOs).
6. Calcular y simular la respuesta del sistema dinámico mediante funciones de transferencia y lazo de control PID en Python (Visual Studio Code).

## Descripción detallada del sistema

En esta práctica se modela la dinámica del sistema cardiovascular mediante una analogía con un circuito eléctrico RLC. El modelo permite analizar la regulación de la presión arterial en tres estados hemodinámicos: paciente normotenso ($C = 1.5~\mu\text{F}$), hipotenso ($C = 3.5~\mu\text{F}$) e hipertenso ($C = 1.0~\mu\text{F}$). A través de la simulación de señales de presión arterial $P_a(t)$ registradas y procesadas mediante datos interpolados, se sintetizan y evalúan controladores PID implementados con amplificadores operacionales para restaurar la respuesta de la presión arterial $P_p(t)$ en condiciones patológicas hacia el comportamiento de un individuo normotenso.

Palabras clave: Circuito RLC; Sistema cardiovascular; Controlador PID; Presión arterial; Normotenso; Hipotenso; Hipertenso; Simulaciones numéricas.

## Lista de archivos incluidos en el repositorio

1. Cuaderno computacional de MATLAB [.mlx y .pdf].
2. Modelo de Simulink [.slx].
3. Archivos de Python [.py].
4. Datos de entrada de señal de presión [.xlsx].
5. Figuras de las simulaciones en Python y MATLAB [.pdf].
6. Diagrama de bloques del sistema cardiovascular en Simulink.

## Referencias

\[1] P. A. Valle, Syllabus para Modelado de Sistemas Fisiológicos, Tecnológico Nacional de México / Instituto Tecnológico de Tijuana, Tijuana, B.C., México, 2025. Permalink: https://biomath.xyz/course/

\[2] M. C. Khoo, Physiological Control Systems Analysis Simulation, and Estimation, 2nd ed. Piscataway, New Jersey, USA: IEEE Press, 2018, Section 4, Page 93.

\[3] N. S. Nise, Control Systems Engineering, 8th ed. Hoboken, New Jersey, USA: John Wiley & Sons, 2020.
