# Gula - Releases

<div align="center">

![Gula](https://img.shields.io/badge/Version-1.0.25-blue.svg)
![Platform](https://img.shields.io/badge/Platform-macOS%2015.0%2B-lightgrey.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)
![Signed](https://img.shields.io/badge/Signed-Developer%20ID-success.svg)
![Notarized](https://img.shields.io/badge/Notarized-Apple-success.svg)

**Herramienta de gestión de proyectos iOS, Android y Flutter para macOS**

[Descargar Última Versión](https://github.com/rudoapps/mac-gula-releases/releases/latest) • [Ver Releases](https://github.com/rudoapps/mac-gula-releases/releases) • [Reporte de Bugs](https://github.com/rudoapps/mac-gula-releases/issues)

</div>

---

## 📋 Descripción

**Gula** es una aplicación nativa para macOS diseñada para facilitar la gestión de proyectos móviles en iOS, Android y Flutter. Proporciona herramientas automatizadas para la generación de módulos, gestión de hooks de Git y templates, mejorando significativamente el flujo de trabajo de desarrollo.

## ✨ Características Principales

- 🚀 **Gestión de Proyectos**: Soporte completo para iOS, Android y Flutter
- 🔧 **Generación Automática de Módulos**: Crea estructuras de módulos con comandos simples
- 🔐 **Integración con Google Sign-In**: Autenticación segura
- 🎯 **Pre-commit Hooks**: Gestión automatizada de hooks de Git
- 📝 **Sistema de Templates**: Genera código repetitivo de manera eficiente
- 🔄 **Actualizaciones Automáticas**: Powered by Sparkle Framework
- ✅ **Firmada y Notarizada**: Sin advertencias de seguridad en macOS
- 🔒 **Hardened Runtime**: Máxima seguridad y compatibilidad

## 📦 Instalación

### Descarga Directa

1. Descarga la última versión desde [Releases](https://github.com/rudoapps/mac-gula-releases/releases/latest)
2. Abre el archivo `.dmg` descargado
3. Arrastra Gula.app a tu carpeta Aplicaciones
4. ¡Listo! La aplicación está firmada y notarizada, no verás advertencias de seguridad

### Requisitos del Sistema

- **macOS**: 15.0 (Sequoia) o superior
- **Arquitectura**: Apple Silicon (M1/M2/M3) e Intel
- **Espacio en disco**: ~6 MB

## 🔄 Sistema de Actualizaciones

Gula utiliza **Sparkle Framework** para proporcionar actualizaciones automáticas seguras:

- ✅ Verificación automática de actualizaciones (cada hora)
- ✅ Instalación silenciosa en segundo plano
- ✅ Firmas EdDSA para garantizar autenticidad
- ✅ Notificaciones de actualizaciones críticas
- ✅ Posibilidad de posponer actualizaciones no críticas

## 📊 Historial de Versiones

### 🎯 Versión 1.0.25 (Actual) - 14 Nov 2025
**Selección de Tags y Mejoras de Verificación**
- 🏷️ **Soporte de Tags**: Selecciona ramas o tags al instalar módulos desde el gestor
- 📋 **Listado Inteligente**: Tags aparecen primero (más reciente primero), luego ramas
- 🔄 **Integración JSON**: Usa `gula branches --json` para información estructurada
- ✨ **UI Mejorada**: Picker con secciones separadas para Tags (🏷️) y Ramas (🌿)
- 🎯 **Selección por Defecto**: Selecciona automáticamente el tag más reciente disponible
- ✅ **Verificación Robusta**: Detección mejorada de Gula CLI con soporte para nuevos formatos
- 🔧 **Actualizaciones Confiables**: Mejor manejo de actualizaciones automáticas
- 🎨 **Tags en Verde**: Color corregido para tags con contenido en info de Git
- 🐛 **Correcciones**: Error de verificación en configuración inicial solucionado
- Tamaño: 6 MB

### Versión 1.0.24 - 13 Nov 2025
**Sistema de Logs y Mejoras de Verificación**
- 📊 **Sistema Completo de Logs**: Ventana independiente para ver todos los comandos Gula en tiempo real
- 💬 **Logs en Tiempo Real**: Timestamps precisos con milisegundos y color-coding
- 🔵 **Botón Flotante**: Acceso rápido a logs desde cualquier pantalla
- 🚀 **Transición Automática**: Ya no requiere clic en "Continuar" después de verificación exitosa
- 🔧 **Detección Mejorada**: Limpieza de códigos ANSI para correcta detección de versiones de Gula CLI
- 📋 **Registro Automático**: Todos los comandos Gula se registran automáticamente en los logs
- 🐛 **Correcciones**: Detección de versión, manejo de errores mejorado, navegación corregida
- Tamaño: 6 MB

### Versión 1.0.23 - 11 Nov 2025
**Git Analytics con Validación de Commits**
- 📊 Nueva card de información de Git en el resumen del proyecto
- 🔢 Contador de ramas con alerta si hay más de 8 (mensaje: "Revisar ramas antiguas")
- 🏷️ Contador de tags con warning si no hay ninguno
- ✅ Análisis de formato de commits con validación de estándares:
  - Conventional Commits (feat:, fix:, docs:, etc.)
  - Formato Imperativo (Add, Fix, Update, Merge, Merged, etc.)
  - Formato JIRA/Ticket ([JIRA-123]: mensaje)
- 📈 Barra de progreso visual mostrando porcentaje de commits válidos
- 🎨 Modal interactivo con análisis detallado de los últimos 10 commits
- 🎯 Color-coded por estado: Verde (≥80%), Naranja (50-79%), Rojo (<50%)
- Tamaño: 6 MB

### Versión 1.0.22 - 10 Nov 2025
**Diseño Mejorado del Resumen de Proyecto**
- 🎨 Rediseño sofisticado de la vista de resumen del proyecto
- ✨ MetadataCard con fondos gradientes circulares y efectos hover dinámicos
- ✨ ProjectInfoCard con estilo visual mejorado e iconos con gradiente
- 💫 Animaciones interactivas basadas en spring para experiencia fluida
- 🌈 Sombras dinámicas basadas en colores que se intensifican al pasar el cursor
- 🎯 Bordes degradados que responden a las interacciones del usuario
- Tamaño: 38 MB

### Versión 1.0.19 - 3 Nov 2025
- Mejoras generales de estabilidad
- Correcciones de bugs
- Optimizaciones de rendimiento
- Tamaño: 5.6 MB

### Versión 1.0.18 - 3 Nov 2025
- Mejoras generales de estabilidad
- Correcciones de bugs
- Optimizaciones de rendimiento
- Tamaño: 5.6 MB

### Versión 1.0.17 - 3 Nov 2025
- Mejoras generales de estabilidad
- Correcciones de bugs
- Optimizaciones de rendimiento
- Tamaño: 5.6 MB

### Versión 1.0.16 - 31 Oct 2025
- Mejoras generales de estabilidad
- Correcciones de bugs
- Tamaño: 5.9 MB

### 🎯 Versión 1.0.15 - 31 Oct 2025
**Primera versión con Sparkle completamente funcional**
- ✅ SUFeedURL configurado correctamente
- ✅ SUPublicEDKey configurado
- ✅ Verificación cada 1 hora
- ✅ Actualizaciones automáticas funcionando
- Tamaño: 5.9 MB

### ⚠️ Versión 1.0.14 - 31 Oct 2025 (Crítica)
**Actualización crítica obligatoria**
- 🔒 Mejoras críticas de estabilidad
- ⚡ Actualización obligatoria para todos los usuarios
- Tamaño: 5.9 MB

### 🔐 Versión 1.0.13 - 31 Oct 2025
**Primera versión firmada y notarizada**
- ✅ Firmada con certificado Developer ID
- ✅ Notarizada por Apple
- ✅ Hardened Runtime habilitado
- ✅ Sin advertencias de seguridad en macOS
- Tamaño: 5.9 MB

### Versiones 1.0.5 - 1.0.12 (30 Oct 2025)
- Mejoras incrementales de rendimiento
- Correcciones de bugs
- Optimizaciones del sistema de actualizaciones

### 📌 Versión 1.0.3 - 23 Oct 2024 (Base)
**Primera versión con integración de Sparkle**
- ✅ Carga automática de API key
- ✅ Carga automática de ramas del repositorio
- ✅ Mejor detección de errores de red vs API key
- ✅ Corrección del icono de la aplicación
- ✅ Soporte para actualizaciones automáticas
- ✅ Eliminación de dependencia del comando timeout

[Ver historial completo de versiones →](https://github.com/rudoapps/mac-gula-releases/releases)

## 🔐 Seguridad

Todas las versiones de Gula están:

- ✅ **Firmadas** con certificado Apple Developer ID
- ✅ **Notarizadas** por Apple
- ✅ **Verificadas** mediante firmas EdDSA en actualizaciones
- ✅ **Hardened Runtime** habilitado
- ✅ Sin código malicioso (verificado por Apple)

## 🛠 Tecnología

Este repositorio contiene:

- **Archivos DMG**: Instaladores firmados y notarizados de cada versión
- **Sparkle Framework**: Sistema de actualizaciones automáticas (v2.7.3)
- **Appcast.xml**: Feed de actualizaciones con firmas EdDSA
- **Herramientas Sparkle**:
  - `generate_appcast`: Generación automática de feeds
  - `generate_keys`: Gestión de claves EdDSA
  - `sign_update`: Firma de actualizaciones
  - `BinaryDelta`: Actualizaciones diferenciales

## 🔐 Claves de Firmado Sparkle

**⚠️ IMPORTANTE**: Para crear releases correctas, es crucial usar las claves correctas.

### Configuración de Claves

La app está configurada con la siguiente **clave pública** en `Info.plist`:
```xml
<key>SUPublicEDKey</key>
<string>11MM9rve3qw5UtLY+dAo+FtwLVa55fC+u5JkZW/eC/M=</string>
```

La **clave privada** correspondiente se encuentra en:
- **Ubicación**: `/Users/fer/mac-app-vibe-coding/sparkle_private_key`
- **Valor**: `iUK2uxqOglQdmzvkyUP9EE0cHsaB5en7jvmchn1rvYs=`

### Proceso de Firmado

Para firmar un DMG correctamente:

```bash
/Users/fer/mac-app-vibe-coding/build/SourcePackages/artifacts/sparkle/Sparkle/bin/sign_update \
  --ed-key-file /Users/fer/mac-app-vibe-coding/sparkle_private_key \
  Gula-1.0.X.dmg
```

**NO usar el Keychain** para firmar, ya que contiene una clave diferente que genera firmas incompatibles:
- Clave pública incorrecta en Keychain: `+BOntVOzwPutvXQGowY8OEd5eCdCvjcn6WpVVk9uaAY=`

### Script Automático

El script `create_full_release.sh` ya está configurado correctamente para usar `--ed-key-file`:
```bash
./scripts/create_full_release.sh 1.0.X BUILD_NUMBER "Descripción"
```

### Verificación de Firma

Para verificar que una firma es válida:

```bash
# Verificar firma de un DMG
SIGNATURE="..." # copiar del appcast
/Users/fer/mac-app-vibe-coding/build/SourcePackages/artifacts/sparkle/Sparkle/bin/sign_update \
  --verify \
  --ed-key-file /Users/fer/mac-app-vibe-coding/sparkle_private_key \
  Gula-1.0.X.dmg \
  "$SIGNATURE"
```

### Backup de Claves

**CRÍTICO**: Mantener backup de estas claves en lugar seguro:
- Clave privada: `/Users/fer/mac-app-vibe-coding/sparkle_private_key`
- Clave pública: `11MM9rve3qw5UtLY+dAo+FtwLVa55fC+u5JkZW/eC/M=`

Si se pierden las claves, **todos los usuarios deberán descargar e instalar manualmente** la app para poder recibir actualizaciones futuras.

## 📝 Licencia

Gula está distribuido bajo la licencia MIT. Sparkle Framework está licenciado bajo su propia licencia (ver [LICENSE](LICENSE)).

## 🤝 Contribuir

Para reportar bugs o solicitar nuevas características:

1. Visita la [página de Issues](https://github.com/rudoapps/mac-gula-releases/issues)
2. Busca si el issue ya existe
3. Si no existe, crea un nuevo issue con una descripción detallada

## 📞 Soporte

- **Issues**: [GitHub Issues](https://github.com/rudoapps/mac-gula-releases/issues)
- **Releases**: [GitHub Releases](https://github.com/rudoapps/mac-gula-releases/releases)
- **Documentación**: Ver el repositorio principal

## 🔗 Enlaces Útiles

- [Sparkle Project](https://sparkle-project.org) - Framework de actualizaciones
- [Documentación de Sparkle](https://sparkle-project.org/documentation/)
- [Sandboxing con Sparkle](https://sparkle-project.org/documentation/sandboxing/)

---

<div align="center">

**Desarrollado por RudoApps**

*Última actualización: 13 de Noviembre de 2025*

</div>
