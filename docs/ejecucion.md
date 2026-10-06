# Guía de ejecución

## Requisitos

- Python 3
- `python3-dnspython` instalado

## Instalación en Debian

```bash
sudo apt update
sudo apt install python3-dnspython
```

## Ejecución

```bash
python3 dns_query.py example.com
```

## Parámetros

- Primer argumento: dominio a consultar
- Opcional: tipo de registro (A, AAAA, MX, etc.)

## Ejemplos

```bash
python3 dns_query.py google.com
python3 dns_query.py google.com MX
```
