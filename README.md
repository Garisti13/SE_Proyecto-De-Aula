# SmartDose: Sistema Automatizado de Dispensación de Medicamentos Programados

## Introducción

## Descripción del Problema

## Alcance del Proyecto
¿Qué incluye el proyecto?
-Programación de hasta 4 horarios de dispensación diarios configurables desde la GUI (Graphical User Interface)
-Dispensación automática de una dosis(pastilla) por evento programado
-Detección de si la pastilla fue dispensada correctamente mediante sensor de presencia.
-Alerta sonora y visual (buzzer + led) si el usuario no recoge la pastilla después de un tiempo
-Alerta si el compartimento de medicamentos está vacío.
-Sistema de logging con timestamp, niveles INFO/WARN/ERROR y códigos estructurados. Se utiliza comunicación UART
-Interfaz gráfica ILI9341([LCD-3.2-TOUCH-ILI9341] Pantalla táctil LCD de 3.2’’. ILI9341)
(preguntar si es la adecuada para este proyecto), el protocolo que usa es el SPI.
-RTS DS3231 para manejo del tiempo, se comunica por vía I2C
-Firmware estructurado, con manejo de errores y documentación.

Prototipo esperado
-Tarjeta universal ensamblada dentro de una carcasa impresa en 3D o construida en acrílico/madera MDF
- Fuente de alimentación externa.
  

Limites técnicos
-Microcontrolador ESP 32
-Protocolos usados: I2C (RTC DS3231), UART (logging) y SPI (interfaz).
-El sistema no distingue el tipo de medicamento.
-Capacidad de dosis a dispensar (por determinar (depende del diseño físico))
- No es un dispositivo medico certificado.
-No incluye conectividad WI-FI o bluetooth.
-No controla temperatura de almacenamiento






## Objetivo General

## Objetivos Específicos

## Asignación de Roles
### Technical Lead:
Elisa Calle Escobar

### Firmware Engineer:
David Aristizábal

### Hardware Integration Engineer:
Gabriel García 

## Verification & Testing Engineer:
Santiago Soto

