# Seguridad DNS

## Riesgos comunes

- DNS spoofing / cache poisoning
- DNS tunneling para exfiltración
- Consultas a dominios maliciosos

## Buenas prácticas

- Usar DNS sobre HTTPS (DoH) o TLS (DoT)
- Validar respuestas con DNSSEC si es posible
- Monitorizar patrones anómalos de consultas

## En Wireshark

- Filtrar por dominios sospechosos
- Buscar consultas inusuales (TXT largos, muchos subdominios)
