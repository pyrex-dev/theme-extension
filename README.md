<center>
<img src="./icon.png"></img>
</center>


<center>
<h1> PYX File Icon - Extensión de Iconos Personalizados para Archivos `.pyx` </h1>
</center>

**Pyx Icon** es una extensión para Visual Studio Code que asigna íconos personalizados a archivos con la extensión `.pyx`, así como a carpetas y archivos relacionados con la configuración del proyecto PyRex. El objetivo de esta extensión es mejorar la experiencia del usuario al trabajar con proyectos PyRex, facilitando la identificación rápida de archivos y carpetas relevantes.

## Instalación

### Desde el Marketplace de VSCode

1. Abre Visual Studio Code.
2. Ve a la pestaña de **Extensiones** (o presiona `Ctrl+Shift+X`).
3. Busca **Pyx Icon**.
4. Haz clic en **Instalar**.

### Instalación Manual

1. Clona el repositorio:
   ```bash
   git clone https://github.com/pyrex-dev/theme-extension.git
   ```
2. Navega al directorio del proyecto:
   ```bash
   cd theme-extension
   ```
3. Empaqueta la extensión con `vsce`:
   ```bash
   vsce package
   ```
4. Instala la extensión en VSCode:
   ```bash
   code --install-extension pyx-icon-1.2.0.vsix
   ```

## Características

- Íconos personalizados para archivos con la extensión `.pyx`.
- Íconos personalizados para carpetas y archivos específicos, como `pyxconfig/` y `pyxconfig`.
- Fácil identificación de archivos de configuración y estructuras relacionadas con PyRex.

### Ejemplo de archivos y carpetas soportados:

<table>
  <tr>
    <td>pyxconfig/</td>
    <td><img src="./icons/pyx-config-folder.svg" alt="Ícono carpeta pyxconfig" width="30"></td>
  </tr>
  <tr>
    <td>pyxconfig.pyx</td>
    <td><img src="./icons/pyx-config-file.svg" alt="Ícono archivo pyxconfig" width="30"></td>
  </tr>
  <tr>
    <td>Archivos .pyx</td>
    <td><img src="./icons/pyrex.svg" alt="Ícono archivo .pyx" width="30"></td>
  </tr>
</table>


## Uso

Una vez que la extensión esté instalada, todos los archivos con la extensión `.pyx` y las carpetas o archivos relacionados con PyRex mostrarán íconos personalizados en el explorador de archivos de VSCode.

## Licencia

Esta extensión se distribuye bajo la licencia **MIT**. Puedes ver más detalles en el archivo `LICENSE`.

<p class="credits">CREDITOS A <a href="https://github.com/tal7aouy/vscode-icons">Vscode Icons</a></p>
