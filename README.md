# 🌍 ModernMUD i18n Editor

Editor web intuitivo para gestionar traducciones de juegos MUD. Diseñado para hacer la gestión de archivos i18n fácil y accesible para usuarios no técnicos.

## ✨ Características

- 📝 **Formularios guiados paso a paso** - No necesitas saber sobre estructuras JSON complejas
- 🗺️ **Gestión inteligente de mapas** - Crea islas, zonas y habitaciones fácilmente
- 🎮 **Soporte completo** - Items, enemigos, NPCs, comandos, mensajes y UI
- 💾 **Auto-guardado** - Tus cambios se guardan automáticamente cada 2 segundos
- 📦 **Exportación en ZIP** - Descarga todos tus archivos en un ZIP organizado
- 🌐 **Multi-idioma** - Crea y gestiona múltiples idiomas
- 🎨 **Interfaz moderna** - Diseño limpio y fácil de usar

## 🚀 Demo en Vivo

👉 [Probar el editor](https://tupagina.github.io/mudtools/i18n/)

## 📖 Cómo Usar

### 1. Selecciona un Idioma
Elige entre los idiomas existentes (ES, EN) o crea uno nuevo.

### 2. Selecciona un Archivo
Escoge qué tipo de contenido quieres editar:
- 🗺️ **map.json** - Islas, zonas y habitaciones
- 🎒 **items.json** - Items y objetos del juego
- ⚔️ **enemies.json** - Enemigos y criaturas
- 💬 **npcs.json** - NPCs y personajes
- 🎮 **commands.json** - Comandos del juego
- 📝 **messages.json** - Mensajes del sistema
- 🖥️ **ui.json** - Interfaz de usuario

### 3. Elige una Acción
- ✨ **Crear** - Añadir nuevas entradas
- ✏️ **Editar** - Modificar entradas existentes
- 🗑️ **Eliminar** - Borrar entradas

### 4. Completa el Formulario
El editor te mostrará un formulario específico según lo que quieras crear. Por ejemplo:

**Para crear una habitación:**
1. Selecciona la isla
2. Selecciona la zona
3. Escribe el ID de la habitación
4. Escribe el nombre
5. Escribe la descripción

¡Listo! El editor crea automáticamente la estructura correcta.

## 📦 Exportar

Haz clic en **"💾 Exportar Todo"** para descargar un archivo ZIP con la siguiente estructura:

```
i18n-es.zip
└── es/
    ├── commands.json
    ├── enemies.json
    ├── items.json
    ├── map.json
    ├── messages.json
    ├── npcs.json
    └── ui.json
```

## 🛠️ Instalación Local

```bash
# Clonar el repositorio
git clone https://github.com/tuusuario/mudtools.git

# Ir al directorio
cd mudtools/i18n

# Abrir index.html en tu navegador
# O usar un servidor local:
python -m http.server 8000
# Visita http://localhost:8000
```

## 💾 Persistencia de Datos

Los datos se guardan automáticamente en el `localStorage` de tu navegador cada 2 segundos. Esto significa que:
- ✅ Tus cambios persisten si cierras la pestaña
- ✅ No necesitas conexión a internet después de cargar la página
- ⚠️ Los datos se almacenan por dominio/navegador
- ⚠️ Recuerda exportar tus cambios antes de limpiar la caché del navegador

## 🎨 Estructura de Archivos

```
i18n/
├── index.html          # Aplicación principal
├── public/             # Archivos de traducción base
│   └── i18n/
│       ├── es/         # Español
│       │   ├── commands.json
│       │   ├── enemies.json
│       │   ├── items.json
│       │   ├── map.json
│       │   ├── messages.json
│       │   ├── npcs.json
│       │   └── ui.json
│       └── en/         # Inglés
│           └── ...
└── README.md           # Este archivo
```

## 🤝 Contribuir

Las contribuciones son bienvenidas. Por favor:
1. Haz fork del proyecto
2. Crea una rama para tu feature (`git checkout -b feature/AmazingFeature`)
3. Commit tus cambios (`git commit -m 'Add some AmazingFeature'`)
4. Push a la rama (`git push origin feature/AmazingFeature`)
5. Abre un Pull Request

## 📝 Licencia

Este proyecto es de código abierto y está disponible bajo la licencia MIT.

## 🐛 Reportar Bugs

Si encuentras algún problema, por favor [abre un issue](https://github.com/tuusuario/mudtools/issues).

---

**Hecho con ❤️ para la comunidad de ModernMUD**
