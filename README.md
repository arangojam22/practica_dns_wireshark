# Práctica DNS + Wireshark

Repositorio con:

- Script Python para generar tráfico DNS
- Guía de ejecución en Debian
- Análisis de capturas en Wireshark
- Notas de seguridad DNS

## Estructura

```
├── README.md
├── dns_query.py
├── docs/
│   ├── ejecucion.md
│   ├── analisis-wireshark.md
│   └── seguridad-dns.md
└── capturas/
    ├── permisos.png
    ├── practica.png
    ├── practica_db.png
    └── practica_debian.png
```

## Uso rápido

```bash
python3 dns_query.py example.com
```

Consulta `docs/ejecucion.md` para más detalles.

## Actividad realizada

En esta práctica se generó tráfico DNS mediante un script en Python que realiza consultas a servidores DNS públicos. El tráfico de red se capturó con Wireshark mientras se ejecutaba el script en una máquina Debian.

Posteriormente, se analizó la captura en Wireshark para observar:

- Las consultas DNS enviadas (nombre de dominio, tipo de registro)
- Las respuestas recibidas (direcciones IP, tiempos de respuesta)
- La estructura de los paquetes DNS (cabecera, sección de preguntas y respuestas)

Con esto se pudo entender el funcionamiento básico del protocolo DNS y cómo se ve su tráfico a nivel de red.

## Capturas de la actividad

- [permisos.png](capturas/permisos.png)
- [practica.png](capturas/practica.png)
- [practica_db.png](capturas/practica_db.png)
- [practica_debian.png](capturas/practica_debian.png)
