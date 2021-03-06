# Onboardingleonn

### Instalacion y ejecucion

Dentro de un proyecto de React Native

Instalar la libreria

```
npm i Onboardingleonn
```


Ejecutar el proyecto

```
cd [proyecto]
expo start
```


## Forma de uso

```
import React from 'react';
import { StyleSheet, Text, View } from 'react-native';
import Onboarding from'onboardingleonn/src'
import Img from './images'

const onPressSkip=()=>{
  console.log("");

}
const data = [
  {
    Img:Img.IMG,
    titulo: 'Hito 4',
    descripcion: 'Glenn Julian Castro Duarte',    
    colortexto: '#fff',
    colorFondo: '#F44611',
    textoBotonPrev: 'Inicio',
    textoBotonNext: 'Sig.',
    

  },
  {
    Img:Img.IMG2,
    titulo: 'Onboarding',
    descripcion: 'Unifranz 7mo semestre',    
    colortexto: '#F44611',
    colorFondo: '#fff',
    textoBotonPrev: 'Ant.',
    textoBotonNext: 'Sig.',
    

  },
  {
    Img:Img.IMG3,
    titulo: 'PDM',
    descripcion: 'ING: William Barra',    
    colortexto: '#fff',
    colorFondo: '#F44611',
    textoBotonPrev: 'Ant.',
    textoBotonNext: 'Fin',
    
  },

];
export default function App() {
  return (
    <Onboarding data={data}  onPressSkip={onPressSkip}></Onboarding>  
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    backgroundColor: '#fff',
    alignItems: 'center',
    justifyContent: 'center',
  },
});
```
## Vista previa
![View1](./assets/s1.jpeg) 


![View2](./assets/s2.jpeg) 


![View3](./assets/s3.jpeg) 


# Documentacion

## Funciones

| Nombre | Descripcion | Tipo |
| :---:          |     :---:      |         :---:  |
| onPressSkip   | Funcion final (navigate To)     | Func    |



## Informacion de variables

| Nombre | Descripcion | Tipo |
| :---:          |     :---:      |         :---:  |
| titulo   |  Describir titulo     | string    |
| Descripcion   | Texto Secundario     | string    |
| Img   | Imagen a mostrar     | string    |
| colorFondo   | Color de fondo     | string    |
| textBotonPrev   | Texto del boton izquierdo   | string    |
| textBotonNext   | Texto del boton derecho   | string    |
| colortexto   | Color de texto y del boton derecho   | string    |


## Version

0.0.5

## Autor

* **Glenn Julian Castro Duarte** - [Leonjaeger](https://github.com/leonjaeger)



