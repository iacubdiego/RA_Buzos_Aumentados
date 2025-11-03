# 🎯 Guía de Markers

## Opción 1: Marker Hiro (Predeterminado) ⭐

### Paso 1: Descargar
https://raw.githubusercontent.com/AR-js-org/AR.js/master/data/images/hiro.png

### Paso 2: Imprimir
- Tamaño: 10x10 cm
- Papel: Blanco mate
- Calidad: Alta

### Paso 3: Listo
Ya funciona con `index.html` sin cambios.

---

## Opción 2: Marker Personalizado

### Paso 1: Crear diseño
- Tamaño: 512x512 px
- Alto contraste (B&N recomendado)
- Logo simple de tu escuela/año

### Paso 2: Generar marker
1. Andá a: https://jeromeetienne.github.io/AR.js/three.js/examples/marker-training/examples/generator.html
2. Upload image
3. Descargar `pattern-marker.patt`
4. Descargar imagen del marker (para imprimir)

### Paso 3: Integrar
```bash
# Renombrar archivo
mv pattern-marker.patt marker.patt

# Colocarlo junto a index.html
```

### Paso 4: Actualizar código
En `index.html`:
```html
<!-- Cambiar de: -->
<a-marker preset="hiro" id="marker">

<!-- A: -->
<a-marker type="pattern" url="./marker.patt" id="marker">
```

---

## 💡 Tips para Buenos Markers

### ✅ Hacer:
- Alto contraste
- Bordes definidos
- Diseño asimétrico
- Tamaño 10x10 cm al imprimir

### ❌ Evitar:
- Muchos detalles pequeños
- Degradados
- Diseños simétricos
- Colores similares

---

## 🖨️ Imprimir en el Buzo

### 1. Transfer Térmico ($)
```
Papel transfer → Imprimir → Planchar
Precio: $500-1000 ARS
Duración: 10-20 lavados
```

### 2. Serigrafía ($$)
```
Buscar serigrafía local → Enviar diseño → Retirar
Precio: $1500-3000 ARS
Duración: 50+ lavados
```

### 3. Parche ($$$)
```
Hacer parche bordado → Coser al buzo
Precio: $2000-4000 ARS
Duración: Permanente
```

---

## 🎨 Combinar QR + Marker

Podés combinar un QR (que abre la web) con el marker (que activa el AR):

```
┌─────────────┐
│   [QR]      │ ← Escanear para abrir web
│             │
│ ┌─────────┐ │
│ │ MARKER  │ │ ← La web detecta esto
│ └─────────┘ │
│             │
│ EGRESADOS   │
│    2024     │
└─────────────┘
```

### Generar QR:
https://www.qr-code-generator.com/

URL del QR: Tu GitHub Pages URL

---

## ✅ Checklist

- [ ] Elegir tipo de marker (Hiro o personalizado)
- [ ] Descargar/generar marker
- [ ] Imprimir en papel (10x10 cm)
- [ ] Probar con la app en el celular
- [ ] ¿Funciona bien? → Imprimir en buzo
- [ ] ¿No funciona? → Más grande o mejor contraste

---

## 📏 Especificaciones de Impresión

**En papel (para probar):**
- Tamaño: 10x10 cm
- Papel: Blanco mate A4
- Impresora: Láser o inkjet

**En buzo (final):**
- Tamaño: 10x10 cm mínimo (ideal 12x12 cm)
- Ubicación: Pecho o espalda
- Negro: Bien oscuro
- Blanco: Bien claro
- Superficie: Plana (no en costuras)
