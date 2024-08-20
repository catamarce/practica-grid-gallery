Practica Grid CSS

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)

### GRID CSS GALLERY
Galeria construida con la utilizacion de propiedades GRID de CSS.
```css
.grid-container {
  width: 80%;
  margin: auto;
  display: grid;/*habilita este container a modo grilla*/
  grid-template-columns: 1fr 1fr 1fr;/*define cantidad de columnas(3) y sus anchos(1fr)*/
  justify-items: center;/*alinea horizontalmente los items (hijos) del container*/
  align-items: center;/*alinea verticalmene los items (hijos) del container*/
  gap: 10px;/*define espaciado horizontal-vertical entre los items(hijos)*/
}
```
Para mas detalles reviza el archivo:  _style.css_
