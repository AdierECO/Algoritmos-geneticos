<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Algoritmo Genético Interactivo en Python</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      line-height: 1.6;
      margin: 20px;
      background-color: #f9f9f9;
      color: #333;
    }
    h1, h2, h3 {
      color: #2c3e50;
    }
    code, pre {
      background: #eaeaea;
      padding: 4px;
      border-radius: 4px;
      font-size: 0.95em;
    }
    a {
      color: #2980b9;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    .highlight {
      background-color: #dff9fb;
      padding: 10px;
      border-radius: 6px;
      margin-bottom: 10px;
    }
  </style>
</head>
<body>
  <h1>🧬 Algoritmo Genético Interactivo en Python</h1>
  <p>
    Este proyecto implementa un algoritmo genético (AG) sencillo para maximizar la función <code>f(x) = x²</code>.  
    Puedes ajustar parámetros como la población, la tasa de cruce y mutación usando una interfaz interactiva con <strong>ipywidgets</strong> en Google Colab.
  </p>

  <h2>📋 Requisitos</h2>
  <ul>
    <li>Python 3.7 o superior</li>
    <li>Librerías: <code>matplotlib</code>, <code>ipywidgets</code></li>
    <li>Recomendado: Ejecutar en Google Colab</li>
  </ul>

  <h2>🚀 Ejecución en Google Colab</h2>
  <ol>
    <li>Abre <a href="https://colab.research.google.com/" target="_blank">Google Colab</a>.</li>
    <li>Sube el archivo <code>algoritmo_genetico_interactivo.py</code> o copia el contenido del código principal.</li>
    <li>Ejecuta el siguiente comando para instalar <code>ipywidgets</code> si no lo tienes:</li>
  </ol>
  <pre><code>!pip install ipywidgets --quiet</code></pre>
  <p>Luego, simplemente ejecuta la celda principal para iniciar los controles interactivos.</p>

  <h2>⚙️ ¿Cómo funciona el algoritmo?</h2>
  <p>El ciclo del algoritmo genético es el siguiente:</p>
  <ol>
    <li>Crear una población inicial de soluciones aleatorias (representadas en binario).</li>
    <li>Evaluar la aptitud de cada individuo con la función <code>f(x) = x²</code>.</li>
    <li>Seleccionar los mejores individuos (torneo).</li>
    <li>Cruzar los padres para crear nuevos hijos (recombinación).</li>
    <li>Aplicar mutación aleatoria a algunos bits.</li>
    <li>Repetir el proceso por varias generaciones.</li>
  </ol>

  <h2>🎛 Parámetros ajustables</h2>
  <ul>
    <li><strong>Bits (x):</strong> Define el rango de valores posibles de x.</li>
    <li><strong>Población:</strong> Tamaño del conjunto de soluciones.</li>
    <li><strong>Generaciones:</strong> Número de iteraciones del algoritmo.</li>
    <li><strong>Cruce:</strong> Probabilidad de recombinar dos individuos.</li>
    <li><strong>Mutación:</strong> Probabilidad de cambiar un bit aleatoriamente.</li>
  </ul>

  <h2>📊 Visualización</h2>
  <p>Al final de cada ejecución se muestra una gráfica con la evolución del mejor individuo en cada generación.</p>

  <h2>🤝 Contribuciones</h2>
  <p>¡Las contribuciones son bienvenidas! Si quieres mejorar el código o agregar ejemplos, haz un fork del proyecto y envía un pull request.</p>

  <h2>📄 Licencia</h2>
  <p>Este proyecto está bajo la licencia MIT. Puedes usarlo libremente, citando este repositorio.</p>
</body>
</html>
