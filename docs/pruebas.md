---
layout: default
title: Página de pruebas
nav_order: 6
---

# Página de pruebas para practicar opciones


Cómo hacer una tabla

| Clasificadores     | Variables                          | Comentarios |
|:-------------------|:-----------------------------------|:------------|
| Temática           | Usar la clasificación INE          | xx  |
| Temporalidad       | Longitudinal, Panel, Transversal   | xx  |
| Microdatos         | Si/no                              | xx   |
| Geografía          | España, CCAA, Provincia, Municipio, Sección | xx  |
| Unidad de análisis | empresas personas/hogares          | xx |
| Clasificaciones    | sexo, CNAE, ocupación, edad, estudios | xx  |
| Grandes Estadística | Contabiliad, EPA, IPC, etc | xx  |


Cómo hacer una etiqueta

{: .label .label-blue }

Etiqueta azul


Cómo hacer un botón

[Ir al INE](http://ine.es/){: .btn }


Cómo hacer otro botón

<button type="button" name="Botón" class="btn">Elemento botón</button>



<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.accordion {
  background-color: #eee;
  color: #444;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
  transition: 0.4s;
}

.active, .accordion:hover {
  background-color: #ccc; 
}

.panel {
  padding: 0 18px;
  display: none;
  background-color: white;
  overflow: hidden;
}
</style>
</head>
<body>

<h2>Accordion</h2>

<button class="accordion">Section 1</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 2</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<button class="accordion">Section 3</button>
<div class="panel">
  <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
</div>

<script>
var acc = document.getElementsByClassName("accordion");
var i;

for (i = 0; i < acc.length; i++) {
  acc[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var panel = this.nextElementSibling;
    if (panel.style.display === "block") {
      panel.style.display = "none";
    } else {
      panel.style.display = "block";
    }
  });
}
</script>

</body>
</html>


