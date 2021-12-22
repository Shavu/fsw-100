# CSS Box Model

All HTML elements can be considered as boxes. In CSS, the term "box model" is used when taking 
about design and layout. The CSS box model is essentially a box that wraps around every HTML
element. It consists of:
    -margins
    -borders
    -padding
    -and tha actual context

Explaination of the different parts: 

* Content - The content of the box, where text and images appear
* Padding - Clears an area around the content. The padding is transparent
* Border - A border that goes around the padding and content
* Margin - Clears an area outside the border. The margin is transparent

The box model allows us to add a border around elements, and to define space between elements.

index.css exmaple box model
 
 body, html {
     margin: 10xp;
 }
 .space-one {
     display: inline-block;
     boder: 2px black dashed; ( requries three  size, color , type of border)
     padding: 40px;
     four values (padding  TOPpx RIGHTpx BOTTOWpx LEFTpx)

 }

 .space-two {
     display: inline-block;
 }

 .box-model {
     height: 350px;
     width: 450;
 }