<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Documentación PYX File Icon</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
      margin: 0;
      padding: 20px;
      line-height: 1.6;
    }

    h1, h2, h3 {
      color: #2c3e50;
    }

    h1 {
      text-align: center;
      font-size: 2.5em;
      margin-bottom: 0.5em;
    }

    h2 {
      font-size: 1.8em;
      border-bottom: 2px solid #2980b9;
      padding-bottom: 10px;
      margin-top: 1.5em;
    }

    h3 {
      font-size: 1.4em;
      margin-top: 1em;
      color: #2980b9;
    }

    p, ol, ul {
      margin-bottom: 20px;
    }

    a {
      color: #2980b9;
      text-decoration: none;
    }

    a:hover {
      text-decoration: underline;
    }

    ol, ul {
      padding-left: 20px;
    }

    code {
      background-color: #ecf0f1;
      padding: 2px 4px;
      border-radius: 3px;
      font-family: "Courier New", Courier, monospace;
    }

    pre {
      background-color: #ecf0f1;
      padding: 10px;
      border-left: 4px solid #2980b9;
      overflow-x: auto;
      border-radius: 5px;
    }

    pre code {
      background: none;
      padding: 0;
    }

    img {
      vertical-align: middle;
      width: 20px;
      height: 20px;
    }

    ul img {
      margin-left: 10px;
    }

    li {
      margin-bottom: 10px;
    }

    .credits {
      margin-top: 40px;
      font-style: italic;
    }
  </style>
</head>
<body>
  <h1>PYX File Icon - Extensión de Iconos Personalizados para Archivos `.pyx`</h1>
  <p><strong>PYX File Icon</strong> es una extensión para Visual Studio Code que asigna íconos personalizados a archivos con la extensión <code>.pyx</code>, así como a carpetas y archivos relacionados con la configuración del proyecto PyRex. El objetivo de esta extensión es mejorar la experiencia del usuario al trabajar con proyectos PyRex, facilitando la identificación rápida de archivos y carpetas relevantes.</p>

  <h2>Instalación</h2>
  <h3>Desde el Marketplace de VSCode</h3>
  <ol>
    <li>Abre Visual Studio Code.</li>
    <li>Ve a la pestaña de <strong>Extensiones</strong> (o presiona <code>Ctrl+Shift+X</code>).</li>
    <li>Busca <strong>Pyx Icon</strong>.</li>
    <li>Haz clic en <strong>Instalar</strong>.</li>
  </ol>

  <h3>Instalación Manual</h3>
  <ol>
    <li>Clona el repositorio:
      <pre><code>git clone https://github.com/pyrex-dev/theme-extension.git</code></pre>
    </li>
    <li>Navega al directorio del proyecto:
      <pre><code>cd theme-extension</code></pre>
    </li>
    <li>Empaqueta la extensión con <code>vsce</code>:
      <pre><code>vsce package</code></pre>
    </li>
    <li>Instala la extensión en VSCode:
      <pre><code>code --install-extension pyx-icon-1.2.0.vsix</code></pre>
    </li>
  </ol>

  <h2>Características</h2>
  <ul>
    <li>Íconos personalizados para archivos con la extensión <code>.pyx</code>.</li>
    <li>Íconos personalizados para carpetas y archivos específicos, como <code>pyxconfig/</code> y <code>pyxconfig</code></li>
    <li>Fácil identificación de archivos de configuración y estructuras relacionadas con PyRex.</li>
  </ul>

  <h3>Ejemplo de archivos y carpetas soportados:</h3>
  <ul>
    <li><code>pyxconfig/</code>: <img src="./icons/pyx-config-folder.svg" alt="Ícono carpeta pyxconfig"></li>
    <li><code>pyxconfig.pyx</code>: <img src="./icons/pyx-config-file.svg" alt="Ícono archivo pyxconfig"></li>
    <li>Archivos <code>.pyx</code>: <img src="./icons/pyrex.svg" alt="Ícono archivo .pyx"></li>
  </ul>

  <h2>Uso</h2>
  <p>Una vez que la extensión esté instalada, todos los archivos con la extensión <code>.pyx</code> y las carpetas o archivos relacionados con PyRex mostrarán íconos personalizados en el explorador de archivos de VSCode.</p>

  <h3>Personalización</h3>
  <ol>
    <li>Edita el archivo <code>pyx-icon-theme.json</code>.</li>
    <li>Añade las asociaciones necesarias bajo las secciones <code>fileNames</code>, <code>folderNames</code>, y <code>fileExtensions</code>.</li>
    <li>Recarga la ventana de VSCode (<code>Ctrl+R</code>) para ver los cambios aplicados.</li>
  </ol>

  <h2>Contribuciones</h2>
  <p>Las contribuciones son bienvenidas. Si deseas añadir más íconos o mejorar la extensión, sigue estos pasos:</p>
  <ol>
    <li>Haz un fork del repositorio.</li>
    <li>Crea una nueva rama:
      <pre><code>git checkout -b feature/nueva-funcionalidad</code></pre>
    </li>
    <li>Realiza tus cambios.</li>
    <li>Envía un Pull Request describiendo las mejoras o cambios que realizaste.</li>
  </ol>
  <p>Asegúrate de seguir los lineamientos de codificación y de realizar pruebas antes de enviar tu contribución.</p>

  <h2>Historial de Cambios</h2>
  <h3>[1.2.0] - 2024-09-14</h3>
  <ul>
    <li>Lanzamiento inicial de la extensión con soporte para archivos <code>.pyx</code> y carpetas <code>pyxconfig</code>.</li>
  </ul>

  <h2>Licencia</h2>
  <p>Este proyecto está licenciado bajo la <a href="LICENSE">MIT License</a>.</p>
  <p class="credits">CREDITOS A <a href="https://github.com/tal7aouy/vscode-icons">Vscode Icons</a></p>
</body>
</html>
