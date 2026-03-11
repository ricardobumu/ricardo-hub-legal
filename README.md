# Centro de Información Legal - Peluquería Consciente Barcelona

Este proyecto centraliza toda la documentación normativa y legal de Ricardo Buriticá (Autónomo) para sus dominios asociados: ricardoburitica.com, ricardoburitica.net y ricardoburitica.eu.

## 🌐 Dominios y Propósito
- **ricardoburitica.eu:** Hub legal y transparencia (Este repositorio).
- **ricardoburitica.com:** Web principal de servicios, reservas y captación de clientes.
- **ricardoburitica.net:** Dominio técnico asociado.

## 🚀 Stack Técnico
- **Hosting:** Cloudflare Pages (Ancho de banda ilimitado y seguridad perimetral).
- **Despliegue:** Integración continua vía GitHub.
- **Seguridad:** Cabeceras HSTS, CSP y Permissions-Policy configuradas en el archivo _headers.
- **Formularios:** Integración de derechos ARCO y Consentimiento RGPD mediante Tally.so.

## 📂 Estructura de Directorios (Clean URLs)
Para garantizar una navegación profesional y evitar archivos duplicados, el proyecto utiliza una estructura de carpetas. Cada carpeta contiene un index.html, permitiendo URLs limpias (ej: /aviso-legal/ en lugar de /aviso-legal.html).

```
Plaintext/
├── style.css             # CSS Maestro: Estética Zen, responsive y minimalista.
├── index.html            # Home: Hub con acceso a los 4 documentos principales.
├── _headers              # Configuración de seguridad para Cloudflare.
├── robots.txt            # Instrucciones para motores de búsqueda.
├── aviso-legal/          # Datos del titular y responsabilidad[cite: 2, 3].
├── politica-privacidad/  # Tratamiento de datos RGPD/LOPD-GDD[cite: 7].
├── politica-cookies/     # Gestión de cookies propias y de terceros[cite: 277].
├── terminos-condiciones/ # Condiciones de contratación y uso[cite: 1, 14].
├── formulario-arco/      # Ejercicio de derechos (Acceso, Rectificación, etc.).
└── consentimiento-rgpd/  # Gestión de permisos del usuario.
```

## ⚖️ Reglas de Negocio Legales
El contenido ha sido optimizado para cumplir con la LSSICE y el RGPD en España, redactado en primera persona para reflejar la actividad de Ricardo Buriticá como autónomo.

- **Anticipo de Reserva:** Se requiere un abono del 25% del servicio como garantía.
- **Política de Cancelación:**
  - 24 horas de antelación: Cancelación permitida con reembolso total del anticipo.
  - Menos de 24 horas/No-Show: El anticipo del 25% no es reembolsable.
- **Derecho de Desistimiento:** 14 días naturales para productos no desprecintados (Art. 102 RD Legislativo 1/2007).

## 🛠️ Mantenimiento y Modificaciones
Para evitar "parches" e incongruencias visuales:
- **Estética:** Cualquier cambio de color o fuente debe realizarse exclusivamente en el archivo style.css de la raíz.
- **Navegación:** El header y el footer deben mantenerse idénticos en todas las páginas para asegurar la coherencia de marca.
- **Identidad:** La marca comercial única es Peluquería Consciente Barcelona.

## 🔒 Seguridad (Headers)
El archivo _headers está configurado para permitir la carga de formularios externos de Tally.so sin comprometer la seguridad del sitio, mediante políticas de frame-src y script-src específicas.

**Contacto Legal:** info@ricardoburitica.com | +34 646 24 64 87.
