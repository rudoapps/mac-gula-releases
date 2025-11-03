# Gula - Releases

<div align="center">

![Gula](https://img.shields.io/badge/Version-1.0.18-blue.svg)
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

### 🎯 Versión 1.0.18 (Actual) - 3 Nov 2025
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

*Última actualización: 3 de Noviembre de 2025*

</div>
