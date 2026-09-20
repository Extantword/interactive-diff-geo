# Superficies regulares — diapositivas interactivas

Las diapositivas del seminario de geometría diferencial «Superficies regulares» (do Carmo,
capítulo 2), como una página web: las figuras se giran con el ratón, las fórmulas se escriben y
la página dibuja lo que significan.

**<https://extantword.github.io/interactive-diff-geo/>**

Se recorre con → y ←; `R` devuelve la cámara a su sitio.

Lo que hay aquí es el sitio ya construido. Se genera desde el deck (Vite + TypeScript) con

    npx vite build --base=/interactive-diff-geo/

y el motor de geometría diferencial que dibuja las superficies vive en su propio proyecto.
