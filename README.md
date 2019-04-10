

# Gepres animate

Es una libreria de animaciones con mixins en sass

## ¿ Cómo usarlo ?
puedes usarlo con sass o css

## Con Css
* descarga el archivo `public/assets/css/gepres-animate.css` e incluyelo en tu proyecto luego puedes agregar las siguientes calses a los elementos que deseas que se animen:

```css
.fade-in
.fade-out
.slide-left
.slide-right
.slide-top
.slide-bottom
.slide-up
.slide-down
.zoom-in
.zoom-out
.bounce-left
.bounce-top
.bounce-right
.bounce-bottom
.bounce-borders
```

## Con Sass
* Instale gepres-animate con el comando `npm install --save-dev gepres-animate`
* Importante `gepres-animate/gepres-animate` en su proyecto.
* establecer la variable `animatehelpers:false` para compilar lo necesario
* los mixins disponibles son: 
```css
fadeIn($time)
fadeOut($time)
slideLeft($time)
slideRight($time)
slideTop($time)
slideBottom($time)
slideUp($time, $height)
slideDown($time, $height)
zoomIn($time)
zoomOut($time)
bounceLeft($time)
bounceTop($time)
bounceRight($time)
bounceBottom($time)
bounceBorders($time, $color)
```
