<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/banner-dark.svg">
  <img alt="Yerson Gallardo. Automatización y mejora de procesos, gestión documental en salud y cloud en AWS y Azure. Trujillo, Perú." src="assets/banner-light.svg" width="100%">
</picture>

<br>

Trabajo en la Unidad de Registros Médicos de un hospital de alta complejidad de EsSalud, donde gran parte del trabajo documental todavía se hace a mano. Antes operé infraestructura en AWS, Azure y servidores on-premises durante más de dos años en NTT DATA, y antes de eso hice desarrollo backend con .NET.

> **Entender el proceso desde dentro cambia qué automatización tiene sentido proponer.**

[![Web](https://img.shields.io/badge/yersongallardo.com-265f51?style=flat-square)](https://yersongallardo.com)
[![Correo](https://img.shields.io/badge/contacto@yersongallardo.com-265f51?style=flat-square)](mailto:contacto@yersongallardo.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-265f51?style=flat-square)](https://www.linkedin.com/in/yrgg96/)

## Proyecto destacado

### [Conoce a tu Enfermera(o)](https://github.com/ygallardops/conoce-tu-enfermero-demo)

Prototipo de consulta pública de colegiatura que responde sin pedir identificación y sin guardar quién consultó, sobre un plan gratuito y sin infraestructura permanente. El reto: que la consulta sea útil para una persona e inútil para quien quiera copiar el padrón completo.

- **Sin datos del consultante:** no hay registro, login ni DNI. Lo que no se recolecta no se puede filtrar.
- **Proyección pública aislada:** la web solo lee una copia mínima del padrón; nunca llega al sistema de origen.
- **Controles anti-extracción sin servidores:** coincidencia exacta, máximo cinco resultados, Turnstile y límite de consultas por IP en el borde de Cloudflare.
- **Cadena de verificación bloqueante:** CodeQL, Dependency Review y Dependabot en cada cambio, y OWASP ZAP cada semana.

![Cloudflare Workers](https://img.shields.io/badge/Cloudflare_Workers-eef1ef?style=flat-square)
![D1](https://img.shields.io/badge/D1-eef1ef?style=flat-square)
![Turnstile](https://img.shields.io/badge/Turnstile-eef1ef?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-eef1ef?style=flat-square)
![React 19](https://img.shields.io/badge/React_19-eef1ef?style=flat-square)
![OpenAPI](https://img.shields.io/badge/OpenAPI-eef1ef?style=flat-square)

[![Ver la demo](https://img.shields.io/badge/Ver_la_demo-265f51?style=for-the-badge)](https://enfermeros-demo.yersongallardo.com/)
[![Caso de estudio](https://img.shields.io/badge/Caso_de_estudio-17201d?style=for-the-badge)](https://yersongallardo.com/proyectos/conoce-tu-enfermero/)
[![Contrato OpenAPI](https://img.shields.io/badge/Contrato_OpenAPI-17201d?style=for-the-badge)](https://github.com/ygallardops/conoce-tu-enfermero-demo/blob/main/openapi/consulta-api.yaml)

<sub>Datos sintéticos. Proyecto personal, sin relación con el Colegio de Enfermeros del Perú.</sub>

## Apuntes y laboratorios

No son entregables profesionales: son notas de estudio y prácticas que mantengo en público.

| Repositorio | Qué contiene |
| --- | --- |
| [**devops-notes**](https://github.com/ygallardops/devops-notes) | Apuntes de troubleshooting en Azure reunidos durante mi trabajo en soporte. Por ahora, diagnóstico de pods en AKS. [Leer en línea](https://ygallardops.github.io/devops-notes/) |
| [**ansible-playbooks**](https://github.com/ygallardops/ansible-playbooks) | Playbooks de práctica para configurar servidores Linux, instalar Docker y aplicar hardening básico. |
| [**ops-automation**](https://github.com/ygallardops/ops-automation) | Ejercicios de automatización operativa en Python y Bash, con pruebas y CI. |

## Trayectoria

- **Hoy:** Digitador Asistencial en la Unidad de Registros Médicos de EsSalud.
- **NTT DATA, más de dos años:** operación de infraestructura en AWS, Azure y on-premises. Pasé del soporte de primer nivel al de segundo nivel.
- **Antes:** soporte de aplicaciones y desarrollo backend con .NET y SQL Server para empresas del Grupo Romero.
- **Formación:** bachiller en Ingeniería de Sistemas Computacionales (UPN) y profesional técnico en Computación e Informática (Cibertec).

## Herramientas

**Cloud** &nbsp;
![AWS](https://img.shields.io/badge/AWS-265f51?style=flat-square)
![Azure](https://img.shields.io/badge/Azure-265f51?style=flat-square)
![Cloudflare](https://img.shields.io/badge/Cloudflare-265f51?style=flat-square)

**Desarrollo** &nbsp;
![.NET](https://img.shields.io/badge/.NET_Core-265f51?style=flat-square)
![SQL Server](https://img.shields.io/badge/SQL_Server-265f51?style=flat-square)
![TypeScript](https://img.shields.io/badge/TypeScript-265f51?style=flat-square)
![Python](https://img.shields.io/badge/Python-265f51?style=flat-square)

**Automatización** &nbsp;
![Bash](https://img.shields.io/badge/Bash-265f51?style=flat-square)
![PowerShell](https://img.shields.io/badge/PowerShell-265f51?style=flat-square)
![Terraform](https://img.shields.io/badge/Terraform-265f51?style=flat-square)
![Ansible](https://img.shields.io/badge/Ansible-265f51?style=flat-square)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-265f51?style=flat-square)

**Salud** &nbsp;
![HIS MINSA](https://img.shields.io/badge/HIS_MINSA-265f51?style=flat-square)
![SISCAP](https://img.shields.io/badge/SISCAP-265f51?style=flat-square)

<details>
<summary><b>Ver el detalle de servicios y funciones</b></summary>
<br>

**Cloud y operación:** soporte de primer y segundo nivel en AWS (EC2, S3, RDS, Lambda, DynamoDB, Route 53, Elastic Beanstalk, CloudFormation) y Azure (App Service, Azure SQL, Storage, AKS, API Management, Entra ID). Monitoreo con CloudWatch, Azure Monitor y New Relic.

**Desarrollo:** servicios backend con .NET Core y SQL Server, y APIs sobre API Gateway, Cognito y Lambda. Python, Bash y PowerShell para tareas operativas.

**Gestión de información:** historias clínicas y documentación asistencial, registro y consolidación en HIS MINSA y SISCAP, y elaboración de reportes.

</details>

## Certificaciones

![OCI 2025 Foundations](https://img.shields.io/badge/Oracle-OCI_2025_Foundations_Associate-17201d?style=flat-square&labelColor=265f51)
![AZ-900](https://img.shields.io/badge/Microsoft-Azure_Fundamentals_(AZ--900)-17201d?style=flat-square&labelColor=265f51)
![Scrum Fundamentals](https://img.shields.io/badge/SCRUMstudy-Scrum_Fundamentals_(SFC)-17201d?style=flat-square&labelColor=265f51)
