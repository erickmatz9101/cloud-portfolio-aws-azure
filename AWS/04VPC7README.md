🎯 Objetivo

Diseñar una red virtual en AWS que permita separar recursos públicos y privados dentro de una misma VPC. Esta segmentación es clave para construir arquitecturas seguras, escalables y alineadas con buenas prácticas de infraestructura en la nube.

🔐 Beneficio

La separación entre subnets públicas y privadas permite:

Controlar el tráfico de red: solo los recursos públicos tienen acceso directo a Internet.

Reducir la superficie de ataque: los recursos privados (como bases de datos o servidores internos) permanecen aislados.

Facilitar la administración de seguridad: mediante reglas de routing, NAT y grupos de seguridad.

Preparar la infraestructura para alta disponibilidad: distribuyendo subnets en múltiples zonas de disponibilidad.


Evidencia: 
<img width="1912" height="835" alt="VPC Creada" src="https://github.com/user-attachments/assets/bf5ebe91-1a74-46ba-8e0f-7a8b541838a2" />
<img width="1916" height="652" alt="subnets publicas y privadas" src="https://github.com/user-attachments/assets/be782e64-2b25-4ad1-a12d-a4c278b7e9f8" />
<img width="1912" height="678" alt="creando las route tables" src="https://github.com/user-attachments/assets/4410b7a9-6c6d-4cc9-bea2-1bc2f78f707e" />
<img width="1918" height="435" alt="creando internet gateway" src="https://github.com/user-attachments/assets/c7816e3c-0849-4ffc-920d-a096d119eccd" />
<img width="1918" height="716" alt="creando y asociando a la RT privada " src="https://github.com/user-attachments/assets/e569ff76-b4c8-4eb7-83b7-9c23911f2223" />
<img width="1918" height="436" alt="adjuntando IGW a VPV" src="https://github.com/user-attachments/assets/4857a86e-13db-4c9c-8f55-e01f90eab8c8" />


🧠 Reflexión técnica

Este diseño es una base sólida para arquitecturas más complejas como:

Aplicaciones web con frontend en subnets públicas y backend en privadas.

Bases de datos protegidas que solo responden a instancias internas.

Infraestructura escalable con balanceadores, NAT, y firewalls.

Separar recursos públicos y privados no solo es una práctica recomendada, sino una necesidad para entornos productivos que requieren seguridad, trazabilidad y control granular del tráfico.

