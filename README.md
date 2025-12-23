# Shopify CSV a PDF - Convertidor de Catálogos

Herramienta web para convertir archivos CSV exportados de Shopify en PDFs de catálogo profesionales.

## 🚀 Características

- ✅ Soporte para múltiples tiendas (Naturesse, BioNaturesse, El Jardín de Eva)
- ✅ Eliminación automática de productos duplicados
- ✅ Generación de URLs según el origen
- ✅ Formato de precio en pesos colombianos
- ✅ Exportación a PDF y HTML
- ✅ Diseño profesional y responsive

## 📦 Instalación en GitHub Pages

### Pasos para publicar:

1. **Crear un nuevo repositorio en GitHub**
   - Ve a https://github.com/new
   - Nombre sugerido: `shopify-to-pdf`
   - Márcalo como público
   - No inicialices con README (ya tienes este archivo)

2. **Subir los archivos**
   
   Opción A - Desde la terminal (si tienes git instalado):
   ```bash
   git clone https://github.com/TU-USUARIO/shopify-to-pdf.git
   cd shopify-to-pdf
   # Copia el archivo index.html aquí
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

   Opción B - Desde la interfaz web de GitHub:
   - Ve a tu repositorio
   - Click en "Add file" → "Upload files"
   - Arrastra el archivo `index.html`
   - Click en "Commit changes"

3. **Activar GitHub Pages**
   - Ve a Settings del repositorio
   - En el menú lateral, busca "Pages"
   - En "Source", selecciona "main" branch
   - Click en "Save"
   - Espera unos minutos

4. **¡Listo!**
   - Tu app estará disponible en: `https://TU-USUARIO.github.io/shopify-to-pdf/`

## 🎯 Uso

1. Selecciona el origen de tus productos
2. Carga el archivo CSV exportado de Shopify
3. Procesa el archivo
4. Genera tu PDF o descarga el HTML

## 📝 Notas

- Solo se procesa la primera aparición de cada producto (identificado por Handle)
- Las líneas duplicadas se descartan automáticamente
- Compatible con todos los navegadores modernos

## 🔧 Tecnologías

- React 18
- Tailwind CSS
- PapaParse (procesamiento CSV)
- HTML5 + CSS3

## 📄 Licencia

Libre de uso para proyectos personales y comerciales.
