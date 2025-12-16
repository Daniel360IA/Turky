# 📊 Sistema de Inventario Automatizado

Sistema web profesional para gestión de inventario con alertas automáticas, reportes en tiempo real y almacenamiento persistente.

![Sistema de Inventario](https://img.shields.io/badge/Estado-Activo-success)
![Versión](https://img.shields.io/badge/Versi%C3%B3n-1.0-blue)
![Licencia](https://img.shields.io/badge/Licencia-MIT-green)

## 🚀 Demo en Vivo

**[👉 Acceder al Sistema](https://daniel360ia.github.io/Turky/)**

---

## ✨ Características Principales

### 📦 Gestión de Inventario
- ✅ Agregar, editar y eliminar productos
- ✅ Búsqueda y filtrado avanzado
- ✅ Visualización en tabla interactiva
- ✅ Códigos de producto únicos

### 🔔 Sistema de Alertas Inteligente
- ⚠️ Alertas automáticas de stock bajo
- 📊 Notificaciones de sobrestock
- 🚨 Indicadores visuales de estado
- ⚡ Reabastecimiento rápido

### 📈 Dashboard y Reportes
- 📊 Métricas en tiempo real
- 📉 Análisis por categorías
- 💰 Valor total del inventario
- 📱 Responsive (funciona en móviles)

### 📤 Importación/Exportación
- 📊 Importar desde Excel (.xlsx, .xls)
- 📄 Importar desde CSV
- 📋 Copiar y pegar desde Excel
- 💾 Exportar datos a CSV
- 🔄 Importar/Exportar JSON

### 💾 Almacenamiento Persistente
- 💿 Los datos se guardan automáticamente
- 🔐 Almacenamiento local en el navegador
- 🔄 Sin necesidad de servidor

---

## 🎯 Cómo Usar

### 1️⃣ Acceder al Sistema
Abre el enlace en tu navegador (Chrome, Firefox, Safari, Edge)

### 2️⃣ Importar tus Datos
**Opción A: Desde Excel**
1. Haz clic en "📤 Importar Datos"
2. Selecciona "Desde Excel/CSV"
3. Arrastra o selecciona tu archivo
4. Revisa la vista previa
5. Haz clic en "Importar"

**Opción B: Copiar y Pegar**
1. Abre tu Excel
2. Selecciona tus datos (incluye encabezados)
3. Copia (Ctrl+C o Cmd+C)
4. En el sistema: "📤 Importar Datos" → "Copiar y Pegar"
5. Pega y haz clic en "Importar"

### 3️⃣ Gestionar Inventario
- **Ver productos**: En la pestaña "📦 Inventario"
- **Ver alertas**: En la pestaña "🔔 Alertas"
- **Ver reportes**: En la pestaña "📈 Reportes"
- **Gestionar categorías**: En la pestaña "🏷️ Categorías"

### 4️⃣ Exportar Datos
Haz clic en "📥 Exportar Datos" para descargar un CSV con tu inventario

---

## 📋 Formato de Datos

### Columnas Requeridas
```
Código | Producto | Categoría | Stock | Mínimo | Máximo
```

### Ejemplo
```csv
111000,CHICKEN TENDER CON PANKO,APANADOS,735,225,760
111001,CRISPETAS POLLO,APANADOS,334,249,545
```

---

## 🔧 Instalación Local (Opcional)

Si prefieres ejecutarlo en tu computadora:

1. Descarga el archivo `index.html`
2. Abre el archivo en tu navegador
3. ¡Listo! No requiere instalación

---

## 🌐 Tecnologías Utilizadas

- **HTML5** - Estructura
- **CSS3** - Diseño moderno con animaciones
- **JavaScript** - Lógica y funcionalidad
- **SheetJS (xlsx.js)** - Procesamiento de Excel
- **LocalStorage API** - Almacenamiento persistente

---

## 📱 Compatibilidad

| Navegador | Versión Mínima | Estado |
|-----------|----------------|--------|
| Chrome | 90+ | ✅ Totalmente compatible |
| Firefox | 88+ | ✅ Totalmente compatible |
| Safari | 14+ | ✅ Totalmente compatible |
| Edge | 90+ | ✅ Totalmente compatible |
| Opera | 76+ | ✅ Totalmente compatible |

**Dispositivos Móviles**: ✅ Compatible con iOS y Android

---

## 🔐 Privacidad y Seguridad

- ✅ Todos los datos se almacenan **localmente** en tu navegador
- ✅ No se envía información a servidores externos
- ✅ No requiere registro ni login
- ✅ Tus datos son 100% privados

---

## 🆘 Soporte

### Problemas Comunes

**❓ "Los datos no se guardan"**
- Los datos se guardan en tu navegador local
- Si cambias de navegador/dispositivo, exporta e importa tus datos

**❓ "No puedo importar mi Excel"**
- Verifica que el archivo tenga las columnas correctas
- Usa el formato: Código, Producto, Categoría, Stock, Mínimo, Máximo

**❓ "La página no carga"**
- Limpia la caché del navegador (Ctrl+F5)
- Verifica tu conexión a internet

### ¿Necesitas Ayuda?
Abre un [Issue](https://github.com/Daniel360IA/Turky/issues) en GitHub

---

## 📝 Licencia

Este proyecto está bajo la Licencia MIT - puedes usarlo libremente para proyectos personales o comerciales.

---

## 🙏 Créditos

Desarrollado con ❤️ para facilitar la gestión de inventarios

---

## 🚀 Próximas Funcionalidades

- [ ] Gráficos avanzados con Chart.js
- [ ] Historial de movimientos
- [ ] Múltiples usuarios con roles
- [ ] Notificaciones por email
- [ ] Integración con APIs externas
- [ ] Modo offline completo
- [ ] Impresión de reportes PDF

---

## 🤝 Contribuciones

¿Quieres mejorar el sistema? ¡Las contribuciones son bienvenidas!

1. Fork el proyecto
2. Crea una rama (`git checkout -b feature/nuevaCaracteristica`)
3. Commit tus cambios (`git commit -m 'Agregar nueva característica'`)
4. Push a la rama (`git push origin feature/nuevaCaracteristica`)
5. Abre un Pull Request

---

<div align="center">

### ⭐ Si te gusta este proyecto, dale una estrella!

**[⬆ Volver arriba](#-sistema-de-inventario-automatizado)**

</div>
