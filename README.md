
# React PCF (PowerApps Component Framework)

:fa-file-code-o:

Este proyecto es una demostración de un componente de PowerApps construido con React y PCF.

## Pre-requisitos

1. Node.js
2. PowerApps CLI

## Instalación

1. Clona el repositorio

```bash
git clone <url_del_repositorio>
```

2.  Navega a la carpeta del proyecto

```bash
cd  cd CanvasGridControl
```

3. Instala las dependencias:

```bash
npm install
```


  ##Uso
4. Para construir el componente, ejecuta:

```bash
npm run build
```

5.Para iniciar el componente en modo de desarrollo, ejecuta:

```bash
npm start
```

##Despliegue
Para empaquetar el componente para su despliegue, ejecuta:

Login al entorno

```bash
pac auth create --url https://entorno-prod.crm.dynamics.com/
```

```bash
pac pcf push --publisher-prefix <prefijo_del_publicador>
```

`<Doc oficial del PCF demo de MS>` : <https://learn.microsoft.com/en-us/power-apps/developer/component-framework/tutorial-create-canvas-dataset-component?tabs=before>


`<Doc oficial del PCF Ciclo de ALM>` : <https://learn.microsoft.com/en-us/power-apps/developer/component-framework/code-components-alm>

