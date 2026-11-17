# Tablero en la nube · Clasificadora de limones

Tablero web de la planta clasificadora de limones (curso MT-325, FIM-UNI).
Se conecta al broker MQTT público de HiveMQ (`broker.hivemq.com`, WebSocket seguro 8884) y muestra en vivo el estado de la planta (PIC16F877A + ESP32-S3-CAM).

- **Ver los datos:** abrir la página; se conecta sola.
- **Telecomandar** (marcha, paro, velocidad, sentido): escribir el PIN de mando.
