# 🚀 Guía de Deploy a GitHub

## Paso 1: Crear Repositorio en GitHub

1. Ve a [github.com/new](https://github.com/new)
2. Nombre del repositorio: `sisgest` (o el que prefieras)
3. Descripción: `Sistema de Gestión de Inventario Hospitalario`
4. Elige **Private** si es confidencial, o **Public** si quieres compartirlo
5. **NO** inicialices con README (ya tenemos uno)
6. Click en "Create repository"

## Paso 2: Conectar tu Repositorio Local a GitHub

Una vez que GitHub te muestre las instrucciones, en tu terminal:

```bash
# Navega al directorio del proyecto
cd /Users/belenhirschfeld/Desktop/PRUEBAS\ CLAUDE

# Conecta al repositorio remoto (reemplaza TU_USUARIO con tu usuario de GitHub)
git remote add origin https://github.com/TU_USUARIO/sisgest.git

# Cambia la rama a 'main' si es necesario
git branch -M main

# Sube el código a GitHub
git push -u origin main
```

## Paso 3: Habilitar GitHub Pages (Opcional)

Para que tu landing page sea accesible como sitio web:

1. Ve a tu repositorio en GitHub
2. Abre **Settings** → **Pages**
3. En "Source", selecciona **Deploy from branch**
4. Branch: `main` / Folder: `sisgest/public`
5. Click en "Save"

En pocos minutos tu sitio estará en:
```
https://TU_USUARIO.github.io/sisgest
```

## Paso 4: Compartir la Demo

Una vez en GitHub, puedes compartir:
- **Landing Page**: `https://tu-usuario.github.io/sisgest/`
- **Dashboard Demo**: `https://tu-usuario.github.io/sisgest/dashboard.html`
- **Credenciales**: Usuario `demo` / Contraseña `demo123`

## Alternativa: Git en Línea de Comandos

Si prefieres todo desde terminal:

```bash
cd /Users/belenhirschfeld/Desktop/PRUEBAS\ CLAUDE

# Ver estado actual
git status

# Ver commits
git log --oneline

# Agregar cambios (si hiciste modificaciones)
git add .
git commit -m "Update: [descripción de cambios]"

# Pushear a GitHub
git push origin main
```

## 📋 Checklist Antes de Subir

- [x] README.md con instrucciones
- [x] Código limpio y funcional
- [x] .gitignore configurado
- [x] Landing page (index.html)
- [x] Dashboard demo (dashboard.html)
- [x] Primera versión del código (v1.0)

## 🔐 Proteger el Repositorio (Recomendado)

En GitHub → Settings → Branches:
1. Crea una regla de protección para `main`
2. Requiere pull requests antes de merge
3. Requiere aprobación antes de merge
4. Apunta cambios críticos solo tú

## 🚀 Actualizaciones Futuras

Cuando hagas cambios locales:

```bash
# 1. Haz cambios en los archivos
# 2. Confirma los cambios
git add .
git commit -m "Descripción del cambio"

# 3. Sube a GitHub
git push origin main
```

Si habilitaste GitHub Pages, se actualiza automáticamente.

## 📊 Monitoreo y Analytics (Opcional)

Una vez en GitHub Pages, puedes ver:
- Visitas a tu sitio
- Países de acceso
- Navegadores usados
- Tiempo de permanencia

En GitHub → Settings → Pages → "View site traffic"

## 💡 Tips

- Usa **Issues** en GitHub para seguimiento de bugs/features
- Crea **Releases** cuando hayas versiones estables
- Usa **Discussions** para recopilar feedback
- Configura **Actions** para automatizar deploys

---

**¿Necesitas ayuda?** Pregunta en [Stack Overflow](https://stackoverflow.com) o consulta la [Documentación de GitHub](https://docs.github.com)
