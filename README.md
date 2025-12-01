# ASISTE

**Administración de Servicios Informáticos con Sistema de Tickets Empresarial**

ASISTE es una solución integral de gestión de servicios TI y ticketing basada en GLPI, diseñada para facilitar la administración eficiente de incidentes, solicitudes de servicio y activos informáticos en entornos empresariales.

## Características

- 📋 **Gestión de Tickets** - Creación, seguimiento y resolución de incidentes
- 💾 **Inventario de Activos** - Control centralizado de recursos informáticos
- 👥 **Gestión de Usuarios** - Administración de perfiles y accesos
- 📊 **Reportes y Análisis** - Métricas de desempeño y SLA
- 🔒 **Seguridad Integrada** - Autenticación y control de accesos

## Tecnología

- **Backend:** GLPI (PHP)
- **Base de Datos:** MySQL 8.0
- **Containerización:** Docker & Docker Compose
- **Despliegue:** AWS EC2
- **HTTPS:** Cloudflare SSL

## Despliegue Rápido

```bash
git clone https://github.com/tuusuario/asiste-glpi-docker.git
cd asiste-glpi-docker
cp .env.example .env
docker-compose up -d
```

Accede a: `https://asiste.tudominio.com`

**Credenciales por defecto:**
- Usuario: `glpi`
- Contraseña: `glpi`

## Documentación

- [Guía de Instalación](./docs/INSTALLATION.md)
- [Configuración](./docs/CONFIG.md)
- [Troubleshooting](./docs/TROUBLESHOOTING.md)

## Licencia

Este proyecto utiliza GLPI bajo licencia GPL-3.0. Ver [LICENSE](./LICENSE) para más detalles.

## Autor

Desarrollado como proyecto académico de ingeniería en computación.
