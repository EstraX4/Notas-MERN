## Metodologia

    <div  class="contact-form">

    <input  type="text"  class="Contact_form_input">

    <input  type="password"  class="Contact_form_input">

    <input  type="text"  class="Contact_form_input">
    
    <input  type="text"  class="Contact_form_input">
    
    <input  type="text"  class="Contact_form_input">
    
    </div>

  <br>

    .contact_form_input {
    
    }
--> Agarra todos los inputs de dicha clase.
  

## first-child

    .contact_form_input:first-child {
    
    }

--> Dentro de la clase contact-form agarra el primer input.
  

## Active

    <input  type="text"  name=""  id=""  class="Contact_form_input--active">
<br>

    .contact_form_input--active {
    
    }

--> El chiste de ponerle active, es que luego en JavaScript, podemos ponerlo a una clase u otra segun la necesidad.