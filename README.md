
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

```bash
pac pcf push --publisher-prefix <prefijo_del_publicador>
```