# Carlos Jiménez Grados | IT Infrastructure & Security 
**Técnico IT | SysAdmin  | Network & Identity Automation**

📍 Sevilla, España | ✉️ carlosedujimenez31@gmail.com 

## 👨‍💻 Sobre mí
Soy un profesional IT con formación en Ingeniería de Tecnologías de Telecomunicación y experiencia en soporte Help Desk[cite: 10]. Mi pasión es llevar las operaciones IT al siguiente nivel: pasar de la resolución manual de incidencias a la automatización de infraestructuras y la seguridad por diseño (Zero Trust)[cite: 10, 11]. 

Actualmente diseño, despliego y mantengo un **Homelab Corporativo Interconectado**, un ecosistema de cuatro proyectos que simula un entorno empresarial real: desde el enrutamiento de red y la seguridad L2, hasta el gobierno de identidades en la nube y el aprovisionamiento automatizado[cite: 11].

## 🛠️ Stack Tecnológico y Competencias
*   **Sistemas y Cloud:** Linux/Unix, Windows 10/11, Active Directory, Microsoft Entra ID / M365[cite: 10].
*   **Redes (Networking):** Modelo OSI, TCP/IP, VLANs, Spanning Tree Protocol (RSTP), Cisco IOS[cite: 10, 11].
*   **Automatización e Infraestructura como Código (IaC):** Python, Bash, PowerShell, Microsoft Graph API, Netmiko[cite: 10, 11].
*   **Bases de Datos:** PostgreSQL (Diseño relacional e idempotencia UPSERT)[cite: 10, 11].
*   **Control de Versiones y Metodología:** Git, GitHub, Documentación Técnica, Resolución de problemas técnicos (Troubleshooting)[cite: 10, 11].

---

## 🚀 Arquitectura Homelab: Ecosistema de Producción Simulado
He construido un ecosistema donde múltiples servicios se comunican con una fuente única de verdad (PostgreSQL)[cite: 11]. 

### 1. Identity Lifecycle Automation
Sistema automatizado e idempotente para el aprovisionamiento y desaprovisionamiento de usuarios[cite: 11].
*   **Flujo:** Ingesta y sanitización de CSV de RRHH -> Aprovisionamiento de cuentas y ACLs en Linux -> Integración híbrida con Microsoft Entra ID (licencias y grupos de seguridad)[cite: 11].
*   **Seguridad:** Auditoría en base de datos, protección contra colisiones, gestión segura de ciclos de red y prevención de accesos residuales tras el offboarding[cite: 11].

### 2. Network Automation & L2 Contingency
Automatización de topología de red Cisco y blindaje contra fallos de Capa 2 y rogue devices[cite: 11].
*   **Flujo:** Despliegue de configuraciones (VLANs, Trunks) masivas mediante Python y Netmiko[cite: 11].
*   **Seguridad:** Hardening de red con RSTP, PortFast y BPDU Guard, logrando la recuperación automática de puertos bloqueados (err-disabled)[cite: 11].

### 3. Continuous Identity, RBAC & Shadow IT Audit
Motor de auditoría continua que mapea privilegios desde entornos locales hasta la nube de Microsoft[cite: 11].
*   **Flujo:** Análisis de grupos administrativos en Linux (sudoers) correlacionado con auditoría de Service Principals, Enterprise Applications y permisos delegados vía Microsoft Graph API[cite: 11].
*   **Seguridad:** Detección de desviaciones del principio de mínimo privilegio y evaluación Zero Trust[cite: 11].

### 4. ITSM Backend & Dynamic Inventory
Backend API que fusiona el estado de la red con el inventario de activos y la gestión de tickets[cite: 11].
*   **Flujo:** Descubrimiento dinámico (Nmap/ARP) volcado sobre PostgreSQL, permitiendo asociar cada ticket a un usuario y activo real para reducir el MTTR y maximizar el FCR[cite: 11].
*   **Seguridad:** Aislamiento dinámico. Si Netmiko detecta una MAC no autorizada, el puerto se mueve a una VLAN de cuarentena automáticamente[cite: 11].

---

## 📜 Certificaciones 
*   **Microsoft 365 Copilot & Agent Administration Fundamentals (AB-900)** - *En curso*[cite: 10]
*   **Cisco Certified Support Technician (CCST)** - *En curso*[cite: 10]
