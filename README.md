# Plan de Energía Personalizado para Optimización

Este repositorio te proporciona una serie de comandos útiles para optimizar el consumo de energía en tu sistema operativo Windows. A través de estos comandos, podrás ajustar la configuración de energía según tus necesidades para mejorar la eficiencia y prolongar la vida útil de tu dispositivo.

**Funciones Destacadas:**

- **Obtener el Plan de Energía Actual:** Utiliza `powercfg /getactivescheme` para conocer el plan de energía que está actualmente en uso.

- **Listar los Planes de Energía Activos:** Ejecuta `powercfg /list` para obtener una lista de los planes de energía disponibles.

- **Configuración de Modos de Ahorro de Energía:** Cambia entre diferentes modos de energía utilizando comandos como `powercfg /setactive` para Ahorro de Energía, Equilibrado o Alto Rendimiento.

- **Establecer Tiempo de Apagado del Monitor:** Ajusta el tiempo de apagado del monitor utilizando `powercfg /change monitor-timeout-ac` y `powercfg /change monitor-timeout-dc`.

- **Exportar e Importar Planes de Energía:** Guarda tu plan actual o importa planes personalizados utilizando los comandos `powercfg /export` y `powercfg /import`.

- **Configuración de Opciones de Energía Personalizada:** Utiliza `powercfg.cpl` para acceder a la ventana de configuración de opciones de energía y personalizar ajustes específicos.

- **Desactivar la Hibernación:** Ejecuta `powercfg /hibernate off` para desactivar la función de hibernación y liberar espacio en disco.

Recuerda que los ajustes de energía pueden influir en el rendimiento y la duración de la batería de tu dispositivo. Aprovecha estos comandos para crear un plan de energía personalizado que se adapte a tus necesidades y estilo de uso, optimizando así la eficiencia energética y el rendimiento de tu sistema.

Para obtener más detalles sobre las opciones de línea de comandos de `powercfg`, puedes consultar la [documentación oficial](https://learn.microsoft.com/es-es/windows-hardware/design/device-experiences/powercfg-command-line-options).

## Licencia
Este proyecto está bajo la licencia [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/). Puedes compartir, adaptar y utilizar estos archivos siempre que des el crédito correspondiente al autor original.
