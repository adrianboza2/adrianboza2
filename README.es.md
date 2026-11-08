<img src="assets/header.svg" alt="Adrián Boza Suárez — estudiante de Cloud y DevSecOps, Madrid" width="100%">

[LinkedIn](https://www.linkedin.com/in/adrian-boza-suarez/) · [English](README.md)

Estudio el Máster en Ciberseguridad Cloud y DevSecOps de Tajamar Tech y el curso de AWS Security del CTIC, después de terminar el ciclo de Administración de Sistemas en Red (ASIR). Aprendo montando cosas de principio a fin y documentando cómo funcionan. Estas son las que merece la pena ver.

## Proyectos

<table>
<tr>
<td width="50%" valign="top">
<a href="https://github.com/adrianboza2/proyecto-intermodular-asir"><img src="assets/k8s-diagram.svg" alt="Arquitectura del lab de Kubernetes" width="100%"></a>

**[Kubernetes que se recupera solo](https://github.com/adrianboza2/proyecto-intermodular-asir)**<br>
Una web en Minikube que sigue sirviendo cuando cae un pod, monitorizada con Prometheus y Grafana y cerrada con políticas de red de denegación por defecto. Proyecto final de ASIR en equipo de tres; yo monté el clúster y los despliegues.

<sub>`kubernetes` `docker` `prometheus` `grafana`</sub>
</td>
<td width="50%" valign="top">
<a href="https://github.com/adrianboza2/script-aemet-python"><img src="assets/aemet-alert.jpg" alt="Ventana de aviso: sube a naranja" width="100%"></a>

**[Monitor de avisos de AEMET](https://github.com/adrianboza2/script-aemet-python)**<br>
Lo escribí en mis prácticas y allí se usó de verdad: vigila los avisos oficiales de AEMET y avisa al equipo por email y con una ventana en pantalla cuando un aviso aparece, cambia de nivel o se resuelve.

<sub>`python` `rss` `smtp` `cron`</sub>
</td>
</tr>
</table>

Aún no son públicos, pero puedo enseñarlos:

- **jobscout** — recoge ofertas de empleo, las guarda en SQLite y las ordena según mi perfil con un LLM. Se ejecuta solo cada tres días en mi servidor.
- **Servidor propio** — un VPS Ubuntu con tareas programadas, health checks, copias nocturnas a git y un pequeño servidor MCP detrás de Tailscale.
- **Lab on-premises** — routers Debian (DHCP con Kea, NAT con nftables) y un dominio Active Directory en Windows Server 2025, montado para el máster.

## Estudiando ahora

| | |
|---|---|
| Infraestructura en Azure · AZ-900 | Máster, oct 2026 – may 2027 |
| AWS Security · camino al SCS-C03 | CTIC, nov – dic 2026 |
| Terraform, GitHub Actions, DevSecOps | Máster, primavera 2027 |
