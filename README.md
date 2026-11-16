# PeakPlay NFL - Official Website & Privacy Policies

This directory contains the PeakPlay website and policies for version 1.5, including Fantasy accounts, Premium subscriptions, privacy controls and account deletion. Deployment uses GitHub Pages from main.

## 🌟 Website Structure

```
web_policies/
├── index.html                      # Professional homepage
├── privacy-policy.html             # Spanish privacy policy draft
├── terms-conditions.html           # Spanish terms draft
├── privacy-policy-en.html          # English privacy policy draft
├── terms-conditions-en.html        # English terms draft
├── delete-account.html             # Bilingual external deletion request
├── styles.css                      # Professional CSS styling
├── assets/                         # Images and resources
│   ├── google_play_store_icon.png  # Official app icon (512x512)
│   ├── google-play-badge.png       # Official Google Play badge
│   └── logo.png                    # Legacy logo (backup)
└── README.md                       # This documentation
```

## Páginas Incluidas

### 1. Página Principal (index.html)
- Hero section con información de la app
- Grid de características principales
- Sección de descarga con enlaces a stores
- Información sobre la aplicación
- Footer with legal navigation

### 2. Política de Privacidad (privacy-policy.html)
- Información completa sobre recopilación de datos
- Detalles sobre el uso de Google AdMob
- Derechos de los usuarios según GDPR
- Información de contacto para asuntos de privacidad
- Política de retención de datos

### 3. Términos y Condiciones (terms-conditions.html)
- Términos de uso de la aplicación
- Limitaciones de responsabilidad
- Derechos de propiedad intelectual
- Política de publicidad
- Procedimientos de terminación

## Características del Sitio

- **Diseño Responsivo**: Compatible con dispositivos móviles y desktop
- **Navegación Intuitiva**: Menú de navegación claro entre páginas
- **Estilo Profesional**: Diseño moderno con gradientes y animations
- **Accesibilidad**: Estructura semántica; pendiente de auditoría
- **SEO Optimizado**: Meta tags apropiados para cada página

## Revisión para PeakPlay 1.5

Los borradores incluyen cuentas Fantasy, Firebase/RevenueCat, Premium con prueba
para usuarios elegibles, controles de privacidad publicitaria y borrado asíncrono.
No constituyen una certificación de cumplimiento legal ni resuelven por sí mismos
los rechazos de contenido de terceros de Apple.

Antes de publicar:

- Revisar el contenido con el titular y confirmar la titularidad/licencias.
- Verificar la recepción de `support@alekla.com` y quién procesa las solicitudes.
  La búsqueda de correo recibido en los últimos 180 días no encontró evidencia;
  eso no prueba que el buzón sea inválido. No se envió correo de prueba.
- Procesar solicitudes de borrado con verificación de titularidad, sin pedir
  contraseñas, y confirmar la finalización real del mismo proceso del backend.
- Publicar la página externa `delete-account.html` junto con las políticas y
  comprobar sus enlaces finales antes de actualizar Data Safety/App Privacy.


## Configuración

### Archivos Requeridos

Asegúrese de que los siguientes archivos estén presentes:

1. `assets/logo.png` - Logo de la aplicación
2. `favicon.ico` - Icono del sitio web (opcional)

### Personalización

Para personalizar el sitio:

1. Actualizar información de contacto en todas las páginas
2. Modificar el logo y colores en `styles.css`
3. Ajustar el contenido según los cambios en la app
4. Actualizar las fechas de "última actualización"

## Deployment

### Para hospedar este sitio:

1. **GitHub Pages**: Subir archivos al repositorio
2. **Netlify**: Arrastar carpeta al dashboard de Netlify
3. **Firebase Hosting**: `firebase deploy`
4. **Vercel**: Conectar repositorio o subir archivos

### URL del Sitio

Una vez desplegado, la URL debe ser proporcionada en:
- Google Play Console (App Content > Privacy Policy)
- App Store Connect (App Information > Privacy Policy URL)

## Mantenimiento

### Actualizaciones Regulares

- Revisar y actualizar políticas cada 6 meses
- Verificar enlaces externos funcionando correctamente
- Actualizar información de la app cuando sea necesario
- Mantener fechas de "última actualización" actuales

### Monitoreo

- Verificar que el sitio sea accesible
- Comprobar responsive design en diferentes dispositivos
- Validar HTML y CSS periódicamente
- Verificar cumplimiento con políticas de stores

## Contacto

Para preguntas sobre este sitio web:
- **Soporte**: support@alekla.com
- **Legal**: support@alekla.com
- **Privacidad**: support@alekla.com

## Licencia

Este sitio web es parte de PeakPlay NFL y está sujeto a los términos y condiciones de la aplicación.

---

**Nota**: Este sitio es específicamente para cumplimiento de Google Play Console y App Store. No requiere funcionalidad de backend compleja, solo hosting estático de archivos HTML/CSS.