# Documnetación UD-1 Lenguajes de Marcas

## Introduccion a Lenguaje de Marcas

### Definición

Un lenguaje de marcas organiza información mediante una sintaxis basada en marcas o etiquetas

### Clasificación de Lenguajes de Marcas

|Tipo|Uso|Ejemplos|
|----|---|--------|
|Presentación|Dar forma a documentos de texto|HTML, CSS|
|Intercambio de información de forma ordenada|Almacenar información de forma ordenada|XML, RSS|
|Documentación||Markdown, WikiTex |
|||

## Instalación y configuracion del entorno
1. Instalamos [VsCode](https://code.visualstudio.com/)
2. Instalamos Plugins
   - [Markdown all in one](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)
   - [HTML CSS Suport](https://marketplace.visualstudio.com/items?itemName=ecmel.vscode-html-css)
   - [XML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-xml) 
   - [Live Preview](https://marketplace.visualstudio.com/items?itemName=ms-vscode.live-server)
  
  ### Tabla Descripción de Plugins

| Plugin | Uso | Logo |
|------------------|---------------|------|
|Markdown all in one |Ofrece atajos de teclado, tabla de contenidos automática y vista previa para redactar documentos Markdown fácilmente|![mark](IMG/images.png)
|HTML CSS Suport |Proporciona autocompletado inteligente de clases e IDs de CSS en tus archivos HTML.|![mark](IMG/Microsoft.VisualStudio.Services.Icons.Default)
|XML |Añade soporte para el lenguaje XML con formateo de código, validación y autocompletado de etiquetas.|![mark](IMG/images_XML.png)
|Live Preview |Permite ver una vista previa en tiempo real y en vivo de tus páginas web dentro del propio editor.|![mark](IMG/livepreview.Default)|

3. Instalamos Git
```bash
sudo apt install git
```
4. Inicializar repositorio de git (en la carpeta del proyecto)
```bash
git init
git add.
git commit -m "README básico UD1"
```
5. Conectar VSCode con GitHub
```bash
git remote add origin https://github.com/Ccollazo15/LM-Carlos.git
git branch -M main
git push -u origin main
```
6. Conectar repositorios de una maquina a otra
- Primero debemos clonar el repositorio en una maquina nueva.
 ```bash
  git clone https://github.com/Ccollazo15/LM-Carlos.git
```
- Segundo debemos tener los mismos archivos que la otra maquina.
```bash
git pull
```
