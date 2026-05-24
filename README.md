# PROYECTO-SISTEMAS-EMBEBIDOS-

# Proyecto de Aula: Sistema Embebido para Riego Automatizado y Monitoreo de Humedad
# 1. Asignación de Roles
El equipo de desarrollo se estructura bajo los siguientes roles para gestionar el proceso de desarrollo replicando prácticas de entornos profesionales:

Technical Lead: Samuel Redondo Gómez
Responsabilidades: Definir la arquitectura del sistema, aprobar decisiones técnicas, garantizar coherencia entre requisitos y diseño, y supervisar la integración.

Firmware Engineer: Miguel Angel Vanegas Manrique
Responsabilidades: Implementación de módulos, documentación de código, cumplimiento de estándares, manejo de errores y logging.

Hardware Integration Engineer: Kebin Andrés Gómez Zuluaga
Responsabilidades: Integración física, diseño esquemático/PCB, validación eléctrica, ensamblaje y carcasa.

Verification & Testing Engineer: Todos
Responsabilidades: Plan de pruebas, evidencia objetiva, construcción y mantenimiento de la matriz SRTM, y validación final.

# 2. Descripción del Problema

El mantenimiento de la humedad adecuada en el suelo es un factor crítico para la supervivencia y desarrollo óptimo de las plantas. El riego manual, al depender de la estimación humana, frecuentemente resulta en un suministro hídrico ineficiente: ya sea por déficit, causando estrés hídrico en la planta, o por exceso, lo que puede derivar en la pudrición de las raíces y el desperdicio del recurso hídrico. Se requiere una solución tecnológica que elimine esta incertidumbre mediante el monitoreo constante de la variable física y la automatización del suministro de agua.

# 3. Introducción

Este proyecto propone el desarrollo de un sistema embebido de lazo cerrado diseñado para la gestión eficiente del riego. El sistema integrará la lectura física de la humedad del suelo y la actuación electromecánica sobre una bomba de agua para mantener la variable dentro de un rango preestablecido. Se aplicarán metodologías rigurosas de ingeniería, priorizando el diseño arquitectónico estructurado, la trazabilidad a través de una matriz SRTM, el manejo de fallos y la documentación técnica formal.

# 4. Objetivos

Objetivo General: Desarrollar un sistema embebido funcional que automatice el proceso de riego mediante el monitoreo de la humedad del suelo, aplicando buenas prácticas de ingeniería en hardware y firmware.

Objetivos Específicos:

Implementar un subsistema de sensado físico para medir la humedad del suelo, incorporando un manejo robusto de errores asociados al sensor.
Controlar un actuador (bomba de agua) basándose en la lógica de firmware y las lecturas obtenidas.
Desarrollar un módulo de logging que registre eventos y códigos de error estructurados para facilitar el diagnóstico del sistema.
Diseñar una interfaz gráfica de usuario que permita configurar parámetros del sistema y visualizar su estado en tiempo real.
5. Alcance del Proyecto
El proyecto comprende el ciclo de desarrollo del sistema embebido, abarcando:

Definición formal de requisitos funcionales y no funcionales.
Diseño e implementación de la arquitectura de hardware y firmware.
Construcción de una matriz de trazabilidad (SRTM) para la validación mediante pruebas objetivas.
Integración de al menos dos protocolos de comunicación documentados.
Ensamblaje físico del prototipo en una tarjeta universal o PCB dentro de una carcasa funcional, operando con una fuente de alimentación independiente.
