# 📊 MATLAB

MATLAB es una herramienta esencial en múltiples disciplinas debido a su capacidad para realizar cálculos numéricos, análisis de datos, modelado y simulación de sistemas complejos. En ingeniería y ciencia, su versatilidad permite desarrollar algoritmos avanzados, procesar señales e imágenes, diseñar sistemas de control y optimizar modelos matemáticos. Su amplia gama de bibliotecas y funciones especializadas, junto con su compatibilidad con otros lenguajes y hardware, lo convierten en una plataforma poderosa para la investigación y el desarrollo. Además, su interfaz intuitiva y su capacidad para visualizar datos facilitan la interpretación de resultados, haciendo de MATLAB una herramienta clave en la resolución de problemas científicos y tecnológicos.

En el mundo de la robótica, MATLAB permite diseñar, simular y probar algoritmos de control, percepción y planificación de movimiento antes de implementarlos en hardware real. Su integración con herramientas como Robotics System Toolbox facilita el desarrollo de sistemas autónomos, la simulación de cinemática y dinámica, y la comunicación con plataformas como ROS. Gracias a su capacidad para procesar grandes volúmenes de datos y optimizar modelos complejos, es una herramienta indispensable en la investigación y desarrollo de robots para aplicaciones industriales, médicas y de exploración.

## 💾🖥️ Instalación de matlab

Para conocer el proceso de instalación dirigase a:

[🚀🛠️📊 Guia de instalación MATLAB](./Instalacion.md)



MATLAB es una herramienta muy valiosa en el ámbito de la ingeniería; sin embargo, al combinarla con el Toolbox de Peter Corke, se amplían significativamente sus capacidades, permitiendo desarrollar aplicaciones más completas y, además, poner en práctica la teoría vista en clase.

# 🤖 Toolbox de Peter Corke

El Toolbox de Peter Corke es una de las herramientas más utilizadas en el ámbito de la robótica, ya que proporciona una amplia colección de funciones para la simulación, análisis y control de robots en MATLAB. Este conjunto de herramientas permite a investigadores, estudiantes y profesionales modelar cinemática y dinámica de robots, realizar planificación de trayectorias, diseñar controladores y trabajar con visión por computadora. Su integración con MATLAB facilita la experimentación y validación de algoritmos antes de implementarlos en hardware real, convirtiéndolo en un recurso esencial para el desarrollo de aplicaciones robóticas.

## 💾🖥️ Instalación de toolbox

Para conocer el proceso de instalación dirigase a:

[🚀🛠️💾🖥️ Guia de instalación Toolbox de Peter Corke](./Instalacion.md)

## 📂 Funcionalidades

Una vez instaladas las funcionalidades del toolbox de Peter Corke, en los siguientes enlaces se encuentra la información necesaria para utilizar estas herramientas.

- [📕📝  Manual toolbox V9.10](./robot.pdf)
- [🔢⚙️ Funciones basicas toolbox](./resumen_funciones_basicas_toolbox.pdf)

Teniendo en cuenta las funciones que nos ofrece el toolbox, se proponen los siguientes ejercicios con el fin de adquirir dominio en esta herramienta, la cual es ampliamente utilizada en las temáticas de robótica.

<details>
  <summary>✍🏼🦾📚 Ejemplos de uso del Toolbox</summary>

- [🏹Vectores](./scripts/Matlab_General_RVC/Ejemplo_Clase_0_revisado.m)
- [➕✖️➖🏹 Operaciones con vectores](./scripts/Matlab_General_RVC/Ejemplo_Clase_1_revisado.m)
- [🔄️🏹 Rotaciones de vectores](./scripts/Matlab_General_RVC/Ejemplo_Clase_2_revisado.m)
- [✍🏼📄 Modelo para hacer informes](./scripts/Matlab_General_RVC/Ejemplo_Publish_revisado.mlx)
- [➕🏹 Ejemplos de operaciones con vectores](./scripts/Matlab_General_RVC/Ejemplos_Matlab_2_revisado.m)
- [🦾🔄️🏹 Ejercicios de rotación de vectores](./scripts/Matlab_General_RVC/Ejemplos_Matlab_3.m)
- [🪢🔄️🏹 Transformacion de vectores](./scripts/Matlab_General_RVC/Ejemplos_Matlab_4.m)


</details>

## 📂 Recursos

<details>
  <summary>🛤️🚗🤖📡 Simulacion de robots moviles</summary>

- [✍🏼🤖 Dibujar robot circular 2D](./scripts/Simulacion_Robot_Moviles/dibrob.m)

- [✍🏼🤖🔴 Dibujar robot circular 2D dado un radio](./scripts/Simulacion_Robot_Moviles/dibrobr.m)

- [✍🏼🚗📍🧭Dibujar vehículos en posiciones y orientaciones](./scripts/Simulacion_Robot_Moviles/dibveh1.m)

<div align="center">
  <img src="https://media4.giphy.com/media/v1.Y2lkPTc5MGI3NjExMmRnaW44ZGVtM3VoNTB2eHBpa3V1eHRoMmxqM3M1MDg0NTh3M2M5bCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/SJojxpkk5PWYSGfIdi/giphy.gif" alt="dibrob" width="400px">
</div>

- [✍🏼🚗🚙📍🧭 Dibujar vehículos con diferentes radios en posiciones y orientaciones dada](./scripts/Simulacion_Robot_Moviles/dibveh2.m)

<div align="center">
  <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExdjR2dmE2anJucG5kbmNicDRoYm1zMXhlaXhiNXlzdDY5ZDJyMmdzZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/COBJzcVXEEdc4ZPoTv/giphy.gif" alt="dibrobr" width="400px">
</div>

- [∫📈🧮 Metodos de integración](./scripts/Simulacion_Robot_Moviles/intgr.m)
- [🏎️💨 Movimiento cinemático de un móvil en un plano](./../Archivos/Matlab/scripts/Simulacion_Robot_Moviles/kinetbas.m)

<div align="center" style="display: flex; gap: 20px; justify-content: center;">
  <a>
    <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExYnZuYXc4ajdkNzZ5cjZxMGU5OWlkbmNlYngxazBjN2J6NDZ6YTBtcyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xZTttNyht33ycdOxEr/giphy.gif" alt="Ori_vel_const" width="400px">
  </a>
  <a>
    <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExeGhiNnFhcncwYzZsbnY3Y2txcDd4dmloMnZzbXd4Zmhtb2Z2aHRlMyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/rlNJZpUkfEQodHfA8p/giphy.gif" alt="Ori_diff_cero_Vel_const" width="400px">
  </a>
</div>

<div align="center" style="display: flex; gap: 20px; justify-content: center;">
  <a>
    <img src="https://media1.giphy.com/media/v1.Y2lkPTc5MGI3NjExMjM4bWdhNjJobXZsaWVkNGJiNng1czBrY3lub3c4M21jNTNrOGkzMSZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/383g9Zm7gu5Cnwq9nJ/giphy.gif" alt="Ori_cambia_Vel_const" width="400px">
  </a>
  <a>
    <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcDFoemdyaXcxOTllYWNiMXQ5MzQxZjRqNXlpZzBwcHNlN3BlOG95ZCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/x11lyohsDalHuURsvF/giphy.gif" alt="Vel_ang_const_Vel_lin_const" width="400px">
  </a>
</div>


- [🏎️💨📈 Movimiento cinemático de un móvil perfiles de velocidad](./scripts/Simulacion_Robot_Moviles/kinetbas2.m)


<div align="center" style="display: flex; gap: 20px; justify-content: center;">
  <a>
    <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExaWk4bzZxM3R0eW41OTlqd2QyZGMya2Z0ZmZ3YnI1NzN6Ymx3cDBwbCZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/uplExeTdNn43zsLAhJ/giphy.gif" alt="acel_lin_vel_trap" width="400px">
  </a>
  <a>
    <img src="https://media2.giphy.com/media/v1.Y2lkPTc5MGI3NjExM3k3d2J1OW1sNmNndTA3eDk1cWgwZGxqOHNhd2MzOXZtM3EzNndkdyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/7mzPNA1IR4o4DfAuX2/giphy.gif" alt="vel_trap_cam_ori" width="400px">
  </a>
</div>

- [📍➡️📍 Simulacion de movimiento](./scripts/Simulacion_Robot_Moviles/sim1.m)
</details>

<details>
  <summary>🗺️🏁🛤️🤖 Mapas de ocupación binarios</summary>

  - [✍🏼🗺️🏁 Cración de mapas y ocupación de celdas](./scripts/Mapas/demo_maps.mlx)

  - [🛤️✍🏼🗺️🏁 Creación de mapas apartir de imagenes](./scripts/Mapas/mapa2.mlx)
</details>