# 🛠️ Guía para Contribuir a KChing

## 🤝 ¿Quién puede contribuir?
Este proyecto es parte de K-Forge y está restringido a miembros autorizados.

---

## 📌 Convención para Commits
Para mantener un historial limpio y comprensible, seguimos la convención **Git Glow** y el flujo de trabajo basado en ramas. Usa el siguiente formato para tus commits:

```
[TYPE][Scope] Mensaje corto en presente
```

---

### 🧾 Tipos de Commits (TYPE):
- **FEAT**: Nueva funcionalidad
- **FIX**: Corrección de errores
- **CHORE**: Tareas de mantenimiento del proyecto
- **RELEASE**: Preparación de una nueva versión
- **HOTFIX**: Corrección urgente en producción

---

### 🗂️ Scopes Comunes:
- **UI**: interfaz de usuario
- **AUTH**: autenticación y manejo de sesión
- **DB**: base de datos
- **API**: servicios o controladores
- **README**, **CONTRIBUTING**, **LICENSE**: archivos del repositorio
- **CONFIG**: configuración del proyecto

Puedes proponer nuevos scopes si se justifica por el contexto del cambio.

---

### ✅ Ejemplos Correctos:
- [FEAT][UI] Agregar pantalla de inicio
- [FIX][AUTH] Corregir bug en validación de usuario
- [CHORE][CONFIG] Actualizar dependencias
- [RELEASE][API] Preparar versión 1.0.0

---

### ⛔ Ejemplos Incorrectos:
- `update` → No describe nada útil
- `cambios` → Muy ambiguo
- `arreglos varios` → No es claro qué se hizo

---

📚 Para más información sobre Git Glow, visita [GitHub - Git Glow](https://github.com/arthurdenner/git-glow) o consulta la documentación interna del equipo.

---

<!-- Los scripts de instalación de hooks se encuentran en la carpeta scripts/ y están diferenciados por plataforma: macos-git-glow.sh y windows-git-glow.ps1. -->
