# NOPROYECT-detectar-chatgpt

## DESPERDICIANDO RECURSOS VL1:
## Cómo Usar Wazuh y Suricata para Cazar el Uso de ChatGPT

Suricata y Wazuh trabajan en conjunto para monitorizar y gestionar la seguridad en tiempo real. Suricata se encarga de analizar el tráfico de red en la máquina objetivo. Cuando detecta el acceso a ChatGPT, genera una alerta.

![image](https://github.com/user-attachments/assets/f466bd1b-1110-4c93-9550-7096031b560e)


Wazuh recibe la alerta de Suricata y la evalúa según las reglas configuradas. Dado que hemos establecido criterios específicos para identificar el uso de ChatGPT, Wazuh emite una notificación visible en función de la gravedad del evento, lo que nos permite monitorear y reaccionar de manera efectiva.

![image](https://github.com/user-attachments/assets/865601f4-ad3f-4a52-bc78-36652484b058)

Una vez que la alerta llega a Wazuh, puedes desplegarla para ver todos los detalles. Esto incluye información sobre el agente que la detectó, el tipo de evento y cualquier otro dato relevante. Esto te permite hacer un seguimiento exhaustivo y responder adecuadamente a la alerta.

![image](https://github.com/user-attachments/assets/d22ae43d-b899-4571-bfa4-ec95942167db)

### ¿Y si detienen el servicio wazuh-agent?

![image](https://github.com/user-attachments/assets/2f3a2316-fbf3-4577-8ca4-36477ad648f3)


