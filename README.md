# 📧 Ecoscooting - Plantillas de Email Interactivas

Aplicación web interactiva con **47 plantillas de email profesionales** para el equipo de atención al cliente de Ecoscooting.

## 🚀 Características

✅ **47 plantillas completas** - Todas las plantillas del archivo original  
✅ **Búsqueda en tiempo real** - Encuentra plantillas por palabra clave  
✅ **Filtros dinámicos** - Por categoría y tag (CSOP/COSP)  
✅ **Copiar al portapapeles** - Con un click  
✅ **Ver completo** - Modal para ver el contenido total  
✅ **Diseño responsive** - Funciona en desktop, tablet y móvil  
✅ **Interfaz profesional** - Tailwind CSS + diseño moderno  

## 📁 Estructura

```
proyecto-ecoscooting/
├── index.html          # Aplicación principal (todo incluido)
├── plantillas.json     # Base de datos de plantillas (opcional)
├── README.md          # Este archivo
└── netlify.toml       # Configuración Netlify (opcional)
```

## 🎯 Categorías de Plantillas

1. **Plazo de entrega** (9 plantillas)
2. **Experiencia de Servicio** (8 plantillas)
3. **Solicitud del Cliente** (25 plantillas)
4. **Escalada de insatisfacción** (4 plantillas)
5. **Otras Consultas** (1 plantilla)
6. **Sesiones Inválidas** (1 plantilla)

## 🌐 Desplegar en Netlify

### Opción 1: Conectar GitHub (Recomendado)

1. Crea un repositorio en GitHub con estos archivos
2. Ve a [netlify.com](https://netlify.com)
3. Click en "New site from Git"
4. Conecta tu repositorio GitHub
5. Elige la rama main
6. Build command: (dejar en blanco o `echo 'Build complete'`)
7. Publish directory: `.` (raíz)
8. Deploy!

### Opción 2: Arrastra y Suelta

1. Ve a [netlify.com/drop](https://netlify.com/drop)
2. Arrastra la carpeta del proyecto
3. ¡Listo! Tu sitio estará en vivo en segundos

### Opción 3: CLI de Netlify

```bash
npm install -g netlify-cli
netlify deploy --prod
```

## 📝 Cómo Usar

1. **Buscar**: Escribe una palabra clave en la barra de búsqueda
2. **Filtrar**: Selecciona una categoría o tag (CSOP/COSP)
3. **Copiar**: Click en "Copiar" para copiar al portapapeles
4. **Ver completo**: Click en "Ver completo" para ver toda la plantilla

## 🎨 Personalización

### Cambiar Colores

En `index.html`, busca la sección `colores`:

```javascript
const colors = {
    "Plazo de entrega": "0891B2",
    "Experiencia de Servicio": "F59E0B",
    // ...
}
```

### Agregar Nuevas Plantillas

Modifica el array `plantillas` en `index.html`:

```javascript
{
    "id": 48,
    "categoria": "Nueva Categoría",
    "subcategoria": "Subcategoría",
    "nombre": "Nombre Plantilla",
    "tag": "CSOP",
    "contenido": "Contenido de la plantilla..."
}
```

## 📊 Performance

- **Carga**: < 1 segundo
- **Búsqueda**: Instantánea
- **Sin servidor**: Hosting estático
- **Costo**: Gratuito en Netlify (plan básico)

## 🔧 Desarrollo Local

Para editar localmente:

```bash
# Simplemente abre index.html en tu navegador
open index.html

# O usa un servidor local
python -m http.server 8000
# Luego ve a http://localhost:8000
```

## 📱 URLs Útiles

- **Sitio en vivo**: Tu URL de Netlify
- **Repositorio**: GitHub
- **Editor**: Edita directamente en Netlify o en tu editor local

## 💡 Tips

- Las plantillas se cachean automáticamente en el navegador
- Compatible con navegadores modernos (Chrome, Firefox, Safari, Edge)
- Funciona offline una vez cargado
- Exporta plantillas copiando el contenido

## 🐛 Soporte

Si encuentras errores o tienes sugerencias:
1. Edita `index.html` directamente
2. Prueba localmente
3. Sube los cambios a GitHub
4. Netlify autodeploy

## 📄 Licencia

Interno - Ecoscooting España

---

**Versión**: 1.0  
**Última actualización**: Marzo 2026  
**Plantillas**: 47  
**Status**: ✅ Activo
