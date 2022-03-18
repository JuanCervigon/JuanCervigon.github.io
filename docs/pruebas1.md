---
layout: default
title: Página de pruebas 1
nav_order: 6
---

# Página de pruebas para practicar opciones


## Cómo hacer una tabla



| Clasificadores     | Variables                          | Comentarios |
|:-------------------|:-----------------------------------|:------------|
| Temática           | Usar la clasificación INE          | xx  |
| Temporalidad       | Longitudinal, Panel, Transversal   | xx  |
| Microdatos         | Si/no                              | xx   |
| Geografía          | España, CCAA, Provincia, Municipio, Sección | xx  |
| Unidad de análisis | empresas personas/hogares          | xx |
| Clasificaciones    | sexo, CNAE, ocupación, edad, estudios | xx  |
| Grandes Estadística | Contabiliad, EPA, IPC, etc | xx  |


## Cómo hacer etiquetas

Etiqueta azul 
  {: .label .label-blue }
  
Etiqueta verde
  {: .label .label-green }


## Cómo hacer un botón

[Ir al INE](http://ine.es/){: .btn }


## Cómo hacer otro botón

<button type="button" name="Botón" class="btn">Elemento botón</button>

# Cómo comparar fechas

{% assign date = '2020-04-13T10:20:00Z' %}

- Original date - {{ date }}
- With timeago filter - {{ date | timeago }}


source 'https://rubygems.org'

gem 'jekyll', '~> 4.2'

group :jekyll_plugins do
  gem 'jekyll-timeago', '~> 0.13.1'
end




