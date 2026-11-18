# Colombia Open

Datasets públicos de Colombia — curados, normalizados y validados, sin
lidiar con los portales/APIs/Excel de cada institución oficial.

[![PyPI](https://img.shields.io/pypi/v/colombia-open?color=blue)](https://pypi.org/project/colombia-open/)
[![Sitio](https://img.shields.io/badge/sitio-colombia--open.github.io-black)](https://colombia-open.github.io/)

## 📦 colombia-open

El proyecto principal es una librería de Python que distribuye datasets
públicos de Colombia ya limpios y listos para usar — sin raspar un
portal gubernamental ni pelear con un Excel mal formateado.

```bash
pip install colombia-open
```

- Código: [davidcasr/colombia-open](https://github.com/davidcasr/colombia-open)
- Catálogo de datasets y roadmap: [colombia-open.github.io](https://colombia-open.github.io/)
- Una fuente nueva se agrega aproximadamente cada semana — ver el roadmap
  del repo para lo ya publicado y lo que sigue.

## 🌐 Este sitio

[colombia-open.github.io](https://github.com/colombia-open/colombia-open.github.io)
es la landing page de la organización (Next.js) — muestra el catálogo de
datasets y su estado de licencia/procedencia a partir de lo que publica
`colombia-open`.

## 🚧 En construcción

Proyectos que consumen los datasets de `colombia-open` para construir
visualizaciones y análisis concretos:

- [colombia-violence-in-numbers](https://github.com/colombia-open/colombia-violence-in-numbers)
- [colombia-road-safety-atlas](https://github.com/colombia-open/colombia-road-safety-atlas)

## Licencia y procedencia

Cada dataset publicado lleva su fuente oficial (`source_url`) y su
licencia/política de reuso explícita. Ante licencia ambigua o
restrictiva, solo se publica la metadata y el link a la fuente — nunca el
dato en sí.
