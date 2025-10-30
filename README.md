# Directorio Anual 2009-2025 con Sistema de Login

Este repositorio contiene un directorio web organizado por años desde 2009 hasta 2025, con un sistema de autenticación básico.

## 🔐 Sistema de Login

El sistema incluye una página de login (`login.html`) que protege el acceso al directorio anual.

### Credenciales de Acceso

- **Usuario:** admin
- **Contraseña:** admin2025

## 📁 Estructura del Directorio

```
/
├── login.html          # Página de inicio de sesión
├── index.html          # Página principal del directorio
├── years/              # Directorio que contiene todos los años
│   ├── 2009/
│   │   └── index.html
│   ├── 2010/
│   │   └── index.html
│   ├── ...
│   └── 2025/
│       └── index.html
└── README.md
```

## 🚀 Características

- ✅ Sistema de login con validación de credenciales
- ✅ Directorio organizado por años (2009-2025)
- ✅ 17 años de directorios disponibles
- ✅ Interfaz moderna y responsiva
- ✅ Navegación intuitiva entre años
- ✅ Protección de sesión con sessionStorage

## 📥 Cómo Obtener el Proyecto

Hay dos formas de obtener el proyecto en tu computadora:

### Opción 1: Descargar como ZIP (Más Fácil)

1. Ve a la página principal del repositorio en GitHub
2. Haz clic en el botón verde **"Code"**
3. Selecciona **"Download ZIP"**
4. Descomprime el archivo ZIP en tu computadora
5. Abre la carpeta descomprimida

### Opción 2: Clonar con Git

Si tienes Git instalado:

```bash
git clone https://github.com/bvela889/skills-introduction-to-github.git
cd skills-introduction-to-github
```

## 💻 Cómo Usar el Proyecto

Una vez que tengas los archivos en tu computadora:

1. Navega a la carpeta del proyecto
2. Abre el archivo `login.html` con tu navegador web:
   - **Opción A:** Doble clic en `login.html` (se abrirá con tu navegador predeterminado)
   - **Opción B:** Clic derecho en `login.html` → "Abrir con" → Selecciona tu navegador (Chrome, Firefox, Edge, etc.)
3. Ingresa las credenciales:
   - **Usuario:** admin
   - **Contraseña:** admin2025
4. Navega por el directorio anual
5. Selecciona cualquier año (2009-2025) para ver su contenido

### Estructura de Archivos

- **login.html** - Archivo principal para iniciar sesión (¡Empieza aquí!)
- **index.html** - Página del directorio (se abre automáticamente después del login)
- **years/** - Carpeta con los 17 años (2009-2025), cada uno con su propia página

## 🎨 Diseño

- Interfaz moderna con gradientes
- Diseño responsivo para dispositivos móviles
- Cards interactivos con efectos hover
- Esquema de colores púrpura/azul

## 📝 Notas Técnicas

- El sistema de autenticación es básico y utiliza JavaScript del lado del cliente
- Las sesiones se manejan con `sessionStorage`
- Para uso en producción, se recomienda implementar autenticación del lado del servidor
- Cada año tiene su propia página de índice que puede personalizarse

## 🔧 Personalización

Cada directorio anual (`years/XXXX/index.html`) puede personalizarse para incluir:
- Documentos específicos del año
- Archivos y recursos
- Información relevante del período
