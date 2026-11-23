# ¿Phishing o legítimo?

Simulador de bandeja de entrada para la asignatura **Digitalización (4º ESO)**, saberes de los bloques 3 y 4 sobre seguridad, fraudes en la red y estrategias de detección.

El alumnado analiza 10 mensajes (correos, SMS y WhatsApp) de un alumno ficticio, Álex, y decide cuáles son phishing y cuáles son legítimos. Las respuestas se entregan en un cuestionario de Aules/Moodle aparte, que no está en este repositorio.

## Contenido

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El simulador completo (HTML, CSS y JavaScript en un solo archivo). Lleva una etiqueta `noindex` para que no aparezca en Google. |
| `.nojekyll` | Indica a GitHub Pages que sirva los archivos tal cual, sin procesarlos con Jekyll. |
| `.gitignore` | Evita subir por error el cuestionario o el solucionario. |

## Publicar en GitHub Pages

1. Crea un repositorio nuevo en GitHub, por ejemplo `phishing-o-legitimo`. Tiene que ser **público** si usas una cuenta gratuita.
2. Sube los archivos: **Add file › Upload files**, arrastra todo el contenido de esta carpeta (incluidos `.nojekyll` y `.gitignore`) y pulsa **Commit changes**.
3. Ve a **Settings › Pages**.
4. En **Build and deployment › Source**, elige **Deploy from a branch**.
5. En **Branch**, elige `main` y la carpeta `/ (root)`, y pulsa **Save**.
6. Espera uno o dos minutos y recarga la página de ajustes. Aparecerá la dirección:
   `https://TU-USUARIO.github.io/phishing-o-legitimo/`
7. Pon ese enlace en el curso de Aules, junto al cuestionario.

## Notas

- Todas las marcas son inventadas (GameVault, Fotogram, StreamBox, PaqExpress, Banco Turia, RunPlanet, Bono Joven Digital). El aviso de Aules es una simulación hecha para clase.
- Ningún enlace ni adjunto funciona: al pulsarlos solo se muestra su destino real.
- La página no guarda ni envía ningún dato del alumnado.
- Solo necesita conexión para cargar la tipografía de Google Fonts; sin conexión usa la del sistema.
