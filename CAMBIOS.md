# Cambios respecto a la obra original

Most Interface es una obra derivada de **FigCraft**, del equipo ArtCraft y
su comunidad (https://github.com/storytold/figcraft), distribuida bajo Apache-2.0.

Este archivo cumple la cláusula 4(b) de Apache-2.0, que obliga a declarar los
cambios. Los archivos que admiten comentarios lo dicen además en su cabecera.

## Qué se ha cambiado

- **La marca.** Se ha retirado la de ArtCraft —nombre, wordmark, logo y marca
  «A»— y puesto la de Grupo MOST, como exige `docs/brand/LICENSE-brand.txt`
  de la obra original para toda versión modificada.
- Nombre de producto: `FigCraft` → `Most Interface`.
- Identificador del paquete: `ai.storyteller.figcraft` → `com.grupomostmexico.mostinterface`.
- Extensión de archivo: `.figcraft` → `.mostinterface`.
- Icono de la aplicación y marca de la interfaz, sustituidos por los nuestros.
- Carpeta `docs/brand/` de la obra original, eliminada.

Lo que NO se ha tocado: los nombres internos de los crates de Rust. Son
identificadores de código, no marcas presentadas al usuario.

## Archivos modificados sin aviso en cabecera

Su formato no admite comentarios:

- `packaging/linux/ai.storyteller.figcraft.metainfo.xml.in`
- `packaging/linux/ai.storyteller.figcraft.mime.xml`
- `packaging/macos/Info.plist.in`
- `packaging/macos/entitlements.plist`
- `packaging/windows/install-policy.json`
- `plugins/examples/counter/figcraft-plugin.json`
- `plugins/examples/export-names/figcraft-plugin.json`
- `plugins/examples/swatch-grid/figcraft-plugin.json`
- `plugins/examples/tidy-names/figcraft-plugin.json`

## Atribución

> Most Interface está basado en FigCraft, del equipo ArtCraft y su
> comunidad (https://github.com/storytold/figcraft), bajo licencia Apache-2.0. Grupo MOST no está
> asociado con el equipo ArtCraft, que no patrocina ni avala este producto.

Total de archivos modificados: 357.
