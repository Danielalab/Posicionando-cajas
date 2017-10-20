## **Cada caja en su lugar**
### **¿Qué es?**
#### Es un programa que muestra dos cajas posicionadas una al lado de la otra y cada una de estas contiene a dos cajas más de distinto tamaño. Para lograrlo la ubicación de la distintas cajas se hizo uso de *positioning*; es decir , que utilizamos la propiedad *position* de CSS y sus distintos valores.
![Sin titulo](assets/docs/cajas.png) 
### **¿Cómo lo hizimos?**
#### Para la creación de cada una de las cajas se hizo uso de la etiqueta *div* y a cada una de estas etiquetas(seis en total) se les asigno una *clase*:
     <div class="one">
        <div class="name-class-1"></div>
        <div class="name-class-2"></div>
     </div>
     <div class="two">
        <div class="name-class-3"></div>
        <div class="name-class-4"></div>
     </div>
#### Además,como se muestra en el código anterior se colocó dos etiquetas *div* dentro de otra etiqueta *div*,lo cual representa la caja más grande y sus cajas más pequeñas dentro de ella.  
#### Luego se señaló cada una de las clases como *selectores* en nuestro archivo CSS para poder darles tamaño, color y sobretodo poder variar *position* y darle como nuevo valor *relative* para ubicar nuestras cajas en la posición deseada cambiando el valor de las propiedades *top*, *rigth*, *bottom* y *left*.
     div.name-class {
         position: relative;
     }