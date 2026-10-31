# 🤝 Cómo contribuir

Este es un repositorio **colaborativo**. ¡Gracias por querer aportar! Estas son las convenciones para mantenerlo ordenado y que tu propuesta se acepte sin fricción.

## Flujo general

1. Haz un **fork** del repositorio (o una rama, si eres colaborador).
2. Haz tus cambios siguiendo las convenciones de abajo.
3. Abre un **Pull Request** hacia `main`.
4. El mantenedor revisa y **aprueba**, **pide cambios** o **rechaza** la propuesta. Ningún cambio llega a `main` sin esa revisión.

## Agregar una herramienta

1. Identifica la **categoría** correcta en `categorias/`.
2. Añade una fila a la tabla respetando las columnas:

   ```markdown
   | Nombre | Descripción breve | [Enlace](https://...) | 📚 |
   ```

3. Usa la marca de **estado** adecuada:
   - ✅ Utilizada
   - 📚 Conocida
   - 🎯 Por aprender / probar

4. Mantén las descripciones **cortas y neutrales** (qué hace la herramienta, no cómo atacar).
5. Enlaza siempre a la **fuente oficial** (sitio o repositorio del proyecto).

## Documentar una herramienta a fondo

Copia la plantilla y guárdala en `notas/`:

```bash
cp plantillas/herramienta.md notas/nombre-herramienta.md
```

## Convención de commits

Formato recomendado (*Conventional Commits*):

```
feat(categoria): agregar <herramienta>
docs(readme): actualizar índice
fix(web): corregir enlace de sqlmap
chore: reorganizar carpetas
```

Ejemplos:

```bash
git add categorias/05-aplicaciones-web.md
git commit -m "feat(web): agregar ffuf"
```

## Estructura de carpetas

| Carpeta | Para qué |
|---------|----------|
| `categorias/` | Fichas de catálogo por fase |
| `notas/` | Apuntes propios, writeups, comandos favoritos |
| `scripts/` | Scripts propios de automatización |
| `plantillas/` | Plantillas reutilizables |
