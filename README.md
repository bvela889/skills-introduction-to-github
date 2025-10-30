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

## 💻 Uso

1. Abre `login.html` en tu navegador
2. Ingresa las credenciales (admin/admin2025)
3. Navega por el directorio anual
4. Selecciona cualquier año para ver su contenido

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
