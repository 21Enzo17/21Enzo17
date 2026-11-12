<div align="center">

# Enzo Meneghini

**Redes, infraestructura y soporte IT · Desarrollo en Java, Python y Angular**<br>
Jujuy, Argentina · Español nativo, inglés C1

[![Portfolio](https://img.shields.io/badge/Portfolio-enzo--meneghini.com-2563eb?style=flat-square)](https://www.enzo-meneghini.com/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-enzo--meneghini-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/enzo-meneghini/)
[![Email](https://img.shields.io/badge/Email-contacto@enzo--meneghini.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:contacto@enzo-meneghini.com)

</div>

Trabajé en el **NOC de un ISP** (Canal 4 Jujuy, +50.000 abonados en GPON/FTTH), como **Support Engineer — Site Lead** en Accenture (proyecto Rio Tinto) y a cargo de la **infraestructura TI** de Agua Potable de Jujuy. Hoy diseño e instalo redes para oficinas y desarrollo **isitmyisp**, un monitor de conectividad open source.

## Proyecto destacado: isitmyisp

**¿Es tu Wi-Fi, tu router o tu ISP?** Un monitor self-hosted para casas, oficinas y comercios que dice en una frase de quién es la falla y arma el informe de evidencia para el reclamo al proveedor. Lo hice con lo que aprendí del otro lado del teléfono, en el NOC.

<a href="https://github.com/21Enzo17/isitmyisp"><img src="https://raw.githubusercontent.com/21Enzo17/isitmyisp/main/docs/screenshots/es/incident.png" alt="El panel de isitmyisp durante un problema en la red del ISP" width="720"></a>

- Separa la pérdida real del ruido de ICMP, exige que ICMP y TCP coincidan y detecta cortes intermitentes, el paso al enlace de respaldo y la saturación del propio enlace (SNMP).
- Informe para el NOC del ISP con capturas mtr, calidad de llamadas (MOS), túneles VPN, dispositivos del local, modo TV y alertas por Telegram, email o webhook.
- Python, Flask, SQLite y Docker multi-arquitectura (amd64/arm64), instalador de un comando, 277 tests, documentación en español e inglés.

[Demo en vivo](https://isitmyisp.enzo-meneghini.com/es/isp/) · [Repositorio](https://github.com/21Enzo17/isitmyisp) · [Documentación](https://isitmyisp.enzo-meneghini.com/docs/es/) · [Docker Hub](https://hub.docker.com/r/21enzo03/isitmyisp)

## Otros proyectos

| Proyecto | Qué es | Stack |
|---|---|---|
| [asist.io](https://github.com/21Enzo17/asist.io) | API REST de control de asistencia, con JWT RS256, refresh tokens y lista negra en Redis | Java, Spring Boot, MySQL, Redis, Docker |
| [url-shortener](https://github.com/21Enzo17/url-shortener) | API para acortar URLs con estadísticas de visitas | Java, Spring Boot |
| [Signal-Modulator](https://github.com/21Enzo17/Signal-Modulator) | Simulador de codificación y modulación digital: NRZ, Manchester, BFSK, BPSK, BASK ([versión web](https://github.com/21Enzo17/Signal-Modulator-web)) | Python |
| [ClusterAltaDisponibilidadBackup](https://github.com/21Enzo17/ClusterAltaDisponibilidadBackup-TPF-MMV) | Servicio en alta disponibilidad con balanceo HAProxy, monitoreo y backups automáticos | Docker Compose, HAProxy, Prometheus, Telegraf, Bash |
| [AguaPotableWeb](https://github.com/21Enzo17/AguaPotableWeb) | Sitio web de Agua Potable de Jujuy | Angular, GeneXus, Node.js |
| [Portfolio](https://github.com/21Enzo17/Portfolio) | Mi portfolio multilenguaje con generador de CV en PDF | Angular, TypeScript, Tailwind |

Otros proyectos son de empresas o clientes y no son públicos.

## Con qué trabajo

- **Redes:** GPON/FTTH, BGP, OSPF, IPv6, VLANs, CGNAT, MikroTik, Cisco, Aruba, UniFi, VPN (WireGuard, IPsec, L2TP), cableado estructurado y fibra óptica
- **Infraestructura:** Linux (Debian/Ubuntu), Proxmox, Windows Server, Active Directory, Docker, NGINX, AWS, Microsoft 365
- **Monitoreo:** Prometheus, Grafana, Nagios, SNMP, Wireshark, GLPI, ServiceNow
- **Desarrollo:** Java (Spring Boot), Angular, Python, TypeScript/Node.js, MySQL, PostgreSQL, SQL Server
- **Formándome en:** CCNA/CCNP, con beca de NetDreamTeam
