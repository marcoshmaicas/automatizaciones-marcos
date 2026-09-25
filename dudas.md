# Dudas y cosas que repasar

Lo que se me queda flojo, lo que no entiendo y lo que no debo olvidar. Una sección por semana.

## Semana 0 · Instalación del entorno (25/09/2026)

- Nunca usar `docker compose down -v`: la `-v` borra los volúmenes, es decir, todos mis flujos y credenciales de n8n. `docker compose down` a secas es seguro.
- Al abrir la terminal empiezo en `C:\Users\marco`. Para ir al repositorio: `cd C:\Users\marco\curso\automatizaciones-marcos`.
- Las claves van en `C:\Users\marco\curso\secretos\.env`, nunca dentro del repositorio ni en un chat.
-