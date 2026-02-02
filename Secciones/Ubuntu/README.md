# 🐧🖥️🦭 Ubuntu

Para trabajar con robots móviles y su simulación, es altamente recomendable utilizar una distribución de Linux, ya que muchas herramientas especializadas, como ROS (Robot Operating System), solo son compatibles con este sistema operativo. Ubuntu 20.04 es una opción ampliamente utilizada en la comunidad de robótica debido a su estabilidad y compatibilidad con ROS Noetic, así como con otras herramientas esenciales para el desarrollo y control de robots. En la sección [⚙️🧰 Algunas herramientas utiles](./../Herramientas/README.md), se presentarán algunas herramientas clave para facilitar el uso de Ubuntu 20.04, permitiendo una gestión más eficiente del sistema y optimizando el flujo de trabajo en la programación y simulación de robots.

En el entorno profesional y académico es común encontrar el sucesor de ROS1, denominado ROS2, una reescritura del sistema orientada a cubrir las necesidades de aplicaciones robóticas modernas, lo que implica el uso de distribuciones de Linux más recientes.

Estas distribuciones de ROS2 requieren distribuciones de Linux específicas, por lo que a continuación se presentan algunas versiones de Linux compatibles, las cuales debes tener en cuenta si en el futuro trabajas con ROS2.


| Versión | Nombre de código       | Tipo        | Fecha de lanzamiento | Estado actual                                   |
|--------:|------------------------|-------------|----------------------|-------------------------------------------------|
| 18.04   | Bionic Beaver          | LTS         | Abril 2018           | Soporte extendido hasta 2028                    |
| 20.04   | Focal Fossa            | LTS         | Abril 2020           | Soporte estándar hasta mayo 2025, ESM hasta 2030 |
| 22.04   | Jammy Jellyfish        | LTS         | Abril 2022           | Soporte estándar hasta 2027                    |
| 23.04   | Lunar Lobster          | Estándar    | Abril 2023           | Finalizada                                     |
| 23.10   | Mantic Minotaur        | Estándar    | Octubre 2023         | Finalizada                                     |
| 24.04   | Noble Numbat           | LTS         | Abril 2024           | Actual / Soporte activo                        |
| 25.04   | Plucky Puffin          | Estándar    | Abril 2025           | Finalizada en enero de 2026                    |
| 25.10   | Questing Quokka        | Estándar    | Octubre 2025         | Soporte activo (corto plazo)                  |
| 26.04   | Resolute Raccoon       | LTS         | Abril 2026 (estimado)| Futuro / LTS en desarrollo                    |


## 🖥️💾🧑🏼‍💻 Formas de usar linux

Para usar correr un sistemas linux en nuestra computadora tenemos diversas formas de hacerlo que se presentaran a continuación:

| Método                              | Ventajas | Desventajas |
|-------------------------------------|----------|-------------|
| **Instalación completa**            | Máximo rendimiento, acceso total al hardware, estabilidad. | No puedes usar otro sistema sin reinstalar o usar una VM. |
| **Arranque dual**                   | Permite elegir entre Ubuntu y otro SO, buen rendimiento. | Requiere reiniciar para cambiar de sistema, posible riesgo en la gestión del arranque. |
| **Máquina virtual**                 | No afecta el sistema principal, útil para pruebas. | Menor rendimiento, especialmente en gráficos. |
| **WSL (Windows Subsystem for Linux)** | Integración con Windows, sin necesidad de reiniciar. | No tiene acceso completo al hardware, no es ideal para interfaces gráficas pesadas. |
| **Aplicaciones dockerizadas**       | Permite ejecutar aplicaciones aisladas sin modificar el sistema. | Se necesita aprender Docker, y algunas aplicaciones pueden requerir configuración avanzada. |


## 💾🖥️ Instalación de linux

A continuación se mostrara como realizar cada una de las instalaciones para cada metodo de uso:

- [💿🏠 Intalación nativa (Recomendada, casi mandatoria)](./Instalacion_nativa.md)

- [🖥️📦 Máquina virtual](./Maquina_virtual.md)

- [🪟🔧🐧WSL (Windows Subsystem for Linux)](./WSL.md)

- 🚢🐳 Aplicaciones dockerizadas: Su configuración es compleja y requiere el uso del WSL por lo cual esta opción no se vera empleada.