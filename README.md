# 🎓 AR Buzos Egresados 2024

Aplicación de Realidad Aumentada para buzos de egresados. Muestra efectos de celebración al escanear un marker.

## 🚀 Inicio Rápido

### 1. Descargar el marker
Descargá e imprimí el marker Hiro: https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png

### 2. Probar localmente
```bash
# Con Python
python -m http.server 8000

# Con Node.js
npx http-server -p 8000
```

Abrí: `http://localhost:8000`

### 3. Subir a GitHub Pages
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/TU-USUARIO/TU-REPO.git
git branch -M main
git push -u origin main
```

Luego en GitHub: Settings → Pages → Deploy from main branch

Tu URL será: `https://TU-USUARIO.github.io/TU-REPO`

## 📱 Uso

1. Abrí la URL en tu móvil (Chrome/Safari)
2. Permitir acceso a cámara
3. Apuntá al marker impreso
4. ¡Disfrutá la celebración en AR!

## 🎨 Personalización

### Cambiar textos
En `index.html` buscá y modificá:
```html
<a-text value="FELICITACIONES" ...>
<a-text value="EGRESADOS 2024" ...>
```

### Cambiar colores
```html
<a-text color="#FFD700" ...>  <!-- Dorado -->
<a-sphere color="#FF6B6B" ...>  <!-- Rojo -->
```

### Usar marker personalizado

1. Generá tu marker en: https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
2. Descargá `pattern-marker.patt` y renombralo a `marker.patt`
3. En `index.html` cambiá:
```html
<!-- De esto: -->
<a-marker preset="hiro" id="marker">

<!-- A esto: -->
<a-marker type="pattern" url="./marker.patt" id="marker">
```

## 🖨️ Imprimir en el Buzo

### Opción 1: Transfer térmico
- Comprar papel transfer
- Imprimir el marker
- Aplicar con plancha

### Opción 2: Serigrafía
- Contratar servicio local
- Enviar imagen del marker
- Tamaño: 10x10 cm mínimo

### Opción 3: Parche
- Hacer parche bordado/impreso
- Coserlo al buzo

## ⚡ Características

- ✨ Copa dorada giratoria
- 🎆 Fuegos artificiales
- 🎊 Confeti cayendo
- ⭐ Estrellas parpadeantes
- 📱 Optimizado para móviles

## 🔧 Requisitos

- Navegador con WebGL/WebXR
- Cámara del dispositivo
- HTTPS (o localhost)
- Marker de 8x8 cm mínimo

## 🆘 Problemas Comunes

**La cámara no se activa**
- Verificá permisos de cámara
- Usá HTTPS (o localhost)
- Probá otro navegador

**El marker no se detecta**
- Mejor iluminación
- Marker plano y sin brillo
- Distancia: 20-40 cm
- Marker más grande (10x10 cm)

**Objetos desalineados**
- Leer GUIA-MARKERS.md
- Marker con buen contraste
- Evitar sombras

## 📄 Licencia

MIT - Usá libremente para tu graduación

---

**¡Felicitaciones Egresados! 🎓✨**
