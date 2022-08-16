#Solución de componente de tarjeta de vista previa del producto

## Visión general
Esta es una solución al desafío Tarjeta de Vista Previa de Producto (https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa).
el cual los usuarios deben de ser capaces de ver el diseño óptimo de la pagina web con los diferentes tamaños de pantalla de cada dispositivo


### Enlaces

- URL de la solución: https://pruebas020491.000webhostapp.com/
- URL del sitio en vivo: https://pruebas020491.000webhostapp.com/

## Mi proceso
se realizo primero la creacion de la pagina para desktop y posteriormente se fue desarrollando para movil, el cual se realizo primero la pagina HTML para posteriormente darle estilo con CSS, esta pagina fue construido con Caja GRID para la estructura de la pagina, Caja FLEX para ajustar cada elemento y elemento flotante.
En la creacion de la pagina aprendí combinar CSS GRID con CSS FLEX.

Use esta sección para recapitular algunos de sus principales aprendizajes mientras trabajaba en este proyecto. Escribirlos y proporcionar ejemplos de código de las áreas que desea resaltar es una excelente manera de reforzar su propio conocimiento.

Para ver cómo puede agregar fragmentos de código, consulte a continuación:

```html

    <section class="section">
        <div class="container">
           ...............
	<button class="boton-card">
                    <a href="#">
                        <img src="/images/icon-cart.svg" alt="">    
                        <h3 >Add to Cart</h3>
                    </a>
                </button>
        </div>
    </section>

-----> CSS

.container{
    background: white;
    width: 50%;
    margin: auto;
    border-radius: 5px;
    display: grid;
    grid-template-columns: 1fr 1fr ;
    gap: 0;
}
.boton-card{
    background: var(--buttonC);
    width: 100%;
    height: 3.5em;
    margin-top: 20px;
    border: none;
    border-radius: 5px;
    display: flex;
    flex-flow: row wrap;
    gap: 55px;
    justify-content: center;
    align-items: center;
}

## Autor

- Sitio web - https://pruebas020491.000webhostapp.com/
- Mentor de frontend - [@JuanKLM02](https://www.frontendmentor.io/profile/JuanKLM02)
