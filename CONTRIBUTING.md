# 🤝 Cómo contribuir / mantener este repositorio

Este es un repositorio personal de consulta. Estas son las convenciones para mantenerlo ordenado.

## Agregar una herramienta

1. Identifica la **categoría** correcta en `categorias/`.
2. Añade una fila a la tabla respetando las columnas:

   ```markdown
   | Nombre | Descripción breve | [Enlace](https://...) | 📚 |
   ```

3. Usa la marca de **estado** adecuada:
   - ✅ La he utilizado
   - 📚 La conozco
   - 🎯 Por aprender

4. Mantén las descripciones **cortas y neutrales** (qué hace la herramienta, no cómo atacar).

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
