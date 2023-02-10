# Solución del formulario 2

```html
<form method="post" class="my-form">
    <fieldset>
      <legend>Laboral</legend>
      <ul class="fields">
        <li class="field">
          <fieldset>
            <label>
              <input name="cuenta-ajena" type="checkbox" value="cuenta-ajena">
              Por cuenta ajena
            </label>
            <label>
              <input name="autonomo" type="checkbox" value="autonomo">
              Por autónomo
            </label>
          </fieldset>
        </li>
        <li class="field">
          <fieldset>
            <legend>¿Alguna vez en el extranjero?</legend>
            <!-- Parte del sí -->
            <div aria-labelledby="extr">
              <label>
                <input type="radio" name="extranjero" value="yes" >Sí
              </label>
              <select id="extr" name="onde">
                <option value="Dentro de la UE">Dentro de la UE</option>
              </select>
            </div>        
            
            <!-- Parte del no -->
            <label>
              <input checked type="radio" name="extranjero" value="no" >
                No
            </label>

          </fieldset>
        </li>
      </ul>
    </fieldset>
    <fieldset>
      <legend>Personal</legend>
      <ul class="fields">
        <li class="field">
          <label>
            Apellidos y Nombre
            <input name="full-name" type="text" placeholder="Fulanito de tal">
          </label>
        </li>
        <li class="field">
          <label>
            Conocimientos sobre:
            <select name="conocimientos" multiple>
              <option value="Informática">Informática</option>
              <option value="Conducción">Conducción</option>
              <option value="Finanzas">Finanzas</option>
              <option value="Leyes">Leyes</option>
            </select>
          </label>
        </li>
      </ul>
    </fieldset>
  </form>
```