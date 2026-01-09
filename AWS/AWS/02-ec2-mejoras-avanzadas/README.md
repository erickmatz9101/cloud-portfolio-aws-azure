Esta carpeta documenta un conjunto de prácticas avanzadas aplicadas sobre instancias EC2 en AWS, enfocadas no solo en la ejecución técnica, sino en el progreso estratégico de mi portafolio como Cloud Engineer. Aquí no se trata solo de "cómo hacerlo", sino de por qué hacerlo bien, qué riesgos se mitigan y cómo cada paso fortalece mi perfil profesional.

📘 Historia detrás de estas mejoras

Después de lograr el despliegue básico de una instancia EC2 con Apache y una página personalizada, identifiqué oportunidades para elevar la calidad del entorno:

¿Qué pasa si el servidor se reinicia y pierde la configuración?

¿Cómo puedo saber si el CPU se satura sin estar monitoreando manualmente?

¿Qué tan automatizable es el proceso para escalarlo en entornos reales?

🔧 Prácticas implementadas

1. Automatización con User Data

Script que instala Apache y despliega una página personalizada al iniciar la instancia.

Beneficio: cero intervención manual post-despliegue.

Riesgo mitigado: pérdida de configuración por reinicio.

2. Alarmas con CloudWatch + SNS

Configuré alarmas de CPU > 70% que disparan notificaciones vía correo.

Beneficio: monitoreo proactivo sin necesidad de estar conectado.

Riesgo mitigado: saturación silenciosa de recursos.

3. Evidencia técnica y reproducibilidad

Capturas de pantalla, comandos usados y validaciones documentadas.

Beneficio: portafolio verificable y profesional.

Riesgo mitigado: falta de trazabilidad en entornos colaborativos.

<img width="1460" height="661" alt="Conexion EC2" src="https://github.com/user-attachments/assets/328af120-1b66-4c31-a923-881c8b77a57f" />
<img width="1901" height="842" alt="Actualizacion de paquetes" src="https://github.com/user-attachments/assets/58b57889-c0e2-437b-8981-aa0e18e45e99" />
<img width="1907" height="246" alt="Instalacion Apache" src="https://github.com/user-attachments/assets/1d7ac960-4713-4ac3-b582-13ece57ed07c" />
<img width="1782" height="585" alt="Apache activo" src="https://github.com/user-attachments/assets/bb05cd87-900d-44cd-bf38-0410618c6185" />
<img width="1875" height="167" alt="Página de prueba en Apache" src="https://github.com/user-attachments/assets/d457097e-4b41-4a94-a8c2-912af8222954" />
<img width="1497" height="926" alt="prueba de http" src="https://github.com/user-attachments/assets/7c0b5d52-800f-463d-9bb0-7774d35927f4" />
<img width="1792" height="792" alt="seleccionando la métrica de clodwatch" src="https://github.com/user-attachments/assets/566b69f8-5b9b-4af8-9c2f-96477ca65de8" />
<img width="1682" height="732" alt="suscripcion para sns" src="https://github.com/user-attachments/assets/67c0b439-3f2b-4192-9165-fff9e469a774" />
<img width="1867" height="982" alt="creando el topic para las alertas de cloud watch" src="https://github.com/user-attachments/assets/5867a154-e55c-4a85-865a-b278d42314a8" />
<img width="1915" height="1002" alt="cloudwatchaws" src="https://github.com/user-attachments/assets/a53b7411-bb63-48aa-b04c-a16d4016a000" />
<img width="1912" height="810" alt="automatizando instancia EC2" src="https://github.com/user-attachments/assets/57f99fd9-e0c3-4773-b886-2218b323ef9b" />






















Reflexión final

Estas mejoras no son decorativas. Son respuestas a escenarios reales que un Cloud Engineer debe anticipar. Cada práctica aquí representa una decisión consciente de elevar la calidad, automatizar procesos y mitigar riesgos. Documentarlas no solo me ayuda a aprender, sino a mostrarle al mundo cómo pienso y cómo actúo.


Autor: Erick Martínez Cruz 
Rol: Cloud Engineer 


