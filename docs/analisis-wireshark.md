# Análisis en Wireshark

## Filtros útiles

- `dns` — todo el tráfico DNS
- `dns.flags.response == 1` — solo respuestas
- `dns.qry.name contains "google"` — por dominio

## Campos importantes

- `dns.qry.name`: nombre consultado
- `dns.a`: dirección IPv4 en respuesta
- `dns.aaaa`: dirección IPv6 en respuesta
- `dns.time`: tiempo de respuesta

## Qué observar

- Diferencia entre consulta y respuesta
- Campos de la cabecera DNS
- Sección de preguntas y respuestas
