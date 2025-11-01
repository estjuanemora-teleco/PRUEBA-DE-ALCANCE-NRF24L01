Este proyecto tiene como objetivo evaluar el alcance máximo de comunicación entre dos módulos nRF24L01 empleando dos Raspberry Pi Pico 2W, configuradas como transmisor y receptor. El sistema transmite y recibe datos provenientes de un acelerómetro, además de enviar información del movimiento de un joystick, la cual es utilizada en el receptor para controlar un micro servomotor.

Las pruebas se realizaron en campo abierto, específicamente detrás de la Universidad Militar Nueva Granada, midiendo las distancias mediante Google Earth para garantizar la precisión de los valores obtenidos.

Durante las pruebas, se evaluaron diferentes configuraciones de potencia de transmisión (0 dBm, -6 dBm, -12 dBm y -18 dBm) y tasas de transferencia de datos (250 kbps, 1 Mbps y 2 Mbps) con el fin de analizar su impacto en la distancia máxima alcanzada y la estabilidad de la comunicación inalámbrica.

Este proyecto busca ofrecer una referencia práctica sobre el desempeño real del nRF24L01 en distintos escenarios y configuraciones, integrando además el control remoto de actuadores y la transmisión de datos de sensores en tiempo real.
