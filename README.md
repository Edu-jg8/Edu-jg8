# Carlos Jiménez Grados | IT Infrastructure & Security 
**Técnico IT | SysAdmin  | Network & Identity Automation**

📍 Sevilla, España | ✉️ carlosedujimenez31@gmail.com 

## 👨‍💻 Sobre mí
Soy un profesional IT al que le apasiona llevar las operaciones IT al siguiente nivel: pasar de la resolución manual de incidencias a la automatización de infraestructuras y la seguridad por diseño (Zero Trust).

Ingles : Competencia Profecional Completa

Actualmente diseño, despliego y mantengo un **Lab Corporativo Interconectado**, un ecosistema de cuatro proyectos que simula un entorno empresarial real: desde el enrutamiento de red y la seguridad L2, hasta el gobierno de identidades en la nube y el aprovisionamiento automatizado.

## 🛠️ Stack Tecnológico y Competencias
*   **Sistemas y Cloud:** Linux/Unix, Windows 10/11, Active Directory, Microsoft Entra ID / M365.
*   **Redes (Networking):** Modelo OSI, TCP/IP, VLANs, Spanning Tree Protocol (RSTP), Cisco IOS.
*   **Automatización e Infraestructura como Código (IaC):** Python, Bash, PowerShell, Microsoft Graph API, Netmiko.
*   **Bases de Datos:** PostgreSQL (Diseño relacional e idempotencia UPSERT).
*   **Control de Versiones y Metodología:** Git, GitHub, Documentación Técnica, Resolución de problemas técnicos (Troubleshooting).

---

## 🚀 Arquitectura: Ecosistema de Producción Simulado
He construido un ecosistema donde múltiples servicios se comunican con una unica base de datos en PostgreSQL. 

### 1. Identity Lifecycle Automation
Sistema automatizado e idempotente para el aprovisionamiento y desaprovisionamiento de usuarios.
*   **Flujo:** Ingesta y sanitización de CSV de RRHH -> Aprovisionamiento de cuentas y ACLs en Linux -> Integración híbrida con Microsoft Entra ID (licencias y grupos de seguridad).
*   **Seguridad:** Auditoría en base de datos, protección contra colisiones, gestión segura de ciclos de red y prevención de accesos residuales tras el offboarding.

### 2. Network Automation & L2 Contingency
Automatización de topología de red Cisco y blindaje contra fallos de Capa 2 y rogue devices.
*   **Flujo:** Despliegue de configuraciones (VLANs, Trunks) masivas mediante Python y Netmiko.
*   **Seguridad:** Hardening de red con RSTP, PortFast y BPDU Guard, logrando la recuperación automática de puertos bloqueados (err-disabled).

### 3. Continuous Identity, RBAC & Shadow IT Audit
Motor de auditoría continua que mapea privilegios desde entornos locales hasta la nube de Microsoft.
*   **Flujo:** Análisis de grupos administrativos en Linux (sudoers) correlacionado con auditoría de Service Principals, Enterprise Applications y permisos delegados vía Microsoft Graph API.
*   **Seguridad:** Detección de desviaciones del principio de mínimo privilegio y evaluación Zero Trust.

### 4. ITSM Backend & Dynamic Inventory
Backend API que fusiona el estado de la red con el inventario de activos y la gestión de tickets.
*   **Flujo:** Descubrimiento dinámico (Nmap/ARP) volcado sobre PostgreSQL, permitiendo asociar cada ticket a un usuario y activo real para reducir el MTTR y maximizar el FCR.
*   **Seguridad:** Aislamiento dinámico. Si Netmiko detecta una MAC no autorizada, el puerto se mueve a una VLAN de cuarentena automáticamente.

---

## 📜 Certificaciones 
*   **Microsoft 365 Copilot & Agent Administration Fundamentals (AB-900)** 
*   **Cisco Certified Support Technician (CCST)** 
