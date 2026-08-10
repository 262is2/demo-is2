# IS2 - demo-is2

Workspace de documentación del curso **Ingeniería de Software II** (IS2),
UPeU 2026-2. Este repo es solo de documentación (MkDocs): no hay código de
referencia dentro de este repositorio.

## Dónde está cada cosa

- `docs/silabo_is2_2026_2.md` — sílabo oficial **vigente** (no editar salvo
  pedido explícito; construido con temas de ISO/IEC 12207, ISO/IEC 29110,
  ISO/IEC 25010, CMMI y SCAMPI). `docs/silabo_is2_2026_1.md` es la versión
  de ciclo anterior, solo como referencia histórica.
- `docs/index.md` — **estado actual: contiene una transcripción del sílabo
  (no es una página de bienvenida curada** como en FP/POO/DIST). Si se pide
  construir una página de inicio propia, seguir el patrón de
  `2625dist/pagatu/docs/index.md` (propósito del curso + producto del
  curso), no duplicar el contenido de `silabo_is2_2026_2.md`.
- `mkdocs.yml` — nav con "Inicio" y "Sílabos" (2026-1/2026-2) únicamente.

## Convenciones

- No editar los archivos `silabo_is2_*.md` salvo que se pida explícitamente.
- No existen todavía guías de sesión (`S0X_*.md`) ni skill de sesión
  (`.claude/skills/`) — si se agregan, seguir el patrón ya usado en otros
  cursos del workspace (carpeta `docs/sesiones/`, publicadas en
  `mkdocs.yml` por unidad).
