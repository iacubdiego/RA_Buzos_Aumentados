# 🚀 Deployment Rápido

## GitHub Pages (Recomendado)

### Primera vez:
```bash
git init
git add .
git commit -m "Initial commit"
git remote add origin https://github.com/iacubdiego/RA_Buzos_Aumentados.git
git branch -M main
git push -u origin main
```

### Actualizar después:
```bash
git add .
git commit -m "Actualización"
git push
```

### Activar GitHub Pages:
1. Ir a tu repo en GitHub
2. Settings → Pages
3. Source: main branch
4. Save
5. Tu URL: `https://iacubdiego.github.io/RA_Buzos_Aumentados`

---

## Netlify (Más fácil)

1. Arrastrá la carpeta a: https://app.netlify.com/drop
2. ¡Listo! URL instantánea

---

## Vercel

```bash
npm i -g vercel
vercel
```

---

## 🔧 Si tenés problemas con Git

### Error: "rejected"
```bash
git pull origin main --allow-unrelated-histories
git push -u origin main
```

### O forzar:
```bash
git push -u origin main --force
```

---

## ✅ Checklist

- [ ] Código funciona localmente
- [ ] Marker probado
- [ ] git init
- [ ] git add .
- [ ] git commit
- [ ] git push
- [ ] Activar Pages
- [ ] Probar URL en móvil
- [ ] Compartir con compañeros
