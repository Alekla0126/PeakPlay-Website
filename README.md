# PeakPlay NFL - Sitio Web de Políticas

Este directorio contiene el sitio web de políticas para PeakPlay NFL, requerido para el cumplimiento de Google Play Console.

## Estructura del Sitio

```
web_policies/
├── index.html              # Página principal del sitio
├── privacy-policy.html     # Política de privacidad
├── terms-conditions.html   # Términos y condiciones
├── styles.css             # Estilos CSS del sitio
├── assets/                # Imágenes y recursos
│   └── logo.png          # Logo de la aplicación
└── README.md             # Este archivo
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
- **Accesibilidad**: Cumple con estándares de accesibilidad web
- **SEO Optimizado**: Meta tags apropiados para cada página

## Cumplimiento Legal

Este sitio web cumple con los requisitos de:

- **Google Play Console**: Política de privacidad y términos requeridos
- **GDPR**: Derechos de usuarios y transparencia de datos
- **AdMob Policies**: Divulgación de uso de publicidad
- **NFL Content**: Disclaimer sobre contenido de terceros

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
- **Soporte**: support@peakplay.app
- **Legal**: legal@peakplay.app
- **Privacidad**: privacy@peakplay.app

## Licencia

Este sitio web es parte de PeakPlay NFL y está sujeto a los términos y condiciones de la aplicación.

---

**Nota**: Este sitio es específicamente para cumplimiento de Google Play Console y App Store. No requiere funcionalidad de backend compleja, solo hosting estático de archivos HTML/CSS.