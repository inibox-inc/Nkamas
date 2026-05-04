# NKAMAS Player - Sistema de Actualizaciones

Este paquete contiene la lógica para la gestión de actualizaciones remotas de la aplicación NKAMAS utilizando Firebase.

## Descripción de la App
**NKAMAS** es un reproductor de video avanzado para Android diseñado para la máxima compatibilidad con flujos de red (streams). A diferencia de los reproductores convencionales, NKAMAS incluye herramientas para capturar contenido de sitios web y reproducirlo sin interferencias.

### Características Principales:
*   **Reproducción Universal**: Soporte para HLS (.m3u8), DASH (.mpd) y archivos de video directos.
*   **Media Capturer**: Motor interno que simula navegación real para extraer el flujo de video de páginas con reproductores embed o protecciones.
*   **Stream Proxy Local**: Servidor local (127.0.0.1) que actúa como puente para inyectar cabeceras HTTP necesarias (User-Agent, Referer) y evitar errores como el 403 Forbidden.
*   **AdBlocker Integrado**: Filtra peticiones de publicidad y rastreadores durante la fase de captura.
*   **Interfaz Minimalista**: Basada en Jetpack Compose, enfocada en la facilidad de uso y rapidez.

---
**Vivix Labs**
*Innovación en reproducción multimedia.*
