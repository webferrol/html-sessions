# Solución del formulario 1

```html
 <form class="user-form">
      <fieldset class="fields">
        <legend>Datos fiscales</legend>

        <div class="field">
          <label>
            <input checked type="radio" value="en-paro" name="datos-fiscales">
            En paro
          </label>
        </div>

        <div class="field">
          <label>
            <input type="radio" value="autonomo" name="datos-fiscales">
            Autónomo
          </label>
        </div>

        <div class="field">
          <label>
            <input type="radio" value="cuenta-ajena" name="datos-fiscales">
            Por c. ajena
          </label>
        </div>

      </fieldset>

      <fieldset class="fields">
        <legend>Datos personales</legend>
        <div class="field">
          <label for="name">Nombre:</label>
          <input required placeholder="Pepito de los palotes" name="user-name" type="text" id="name">
        </div>
        <div class="field">
          <label for="last-name">Apellidos:</label>
          <input  placeholder="Speedy González" name="last-name" type="text" id="last-name">
        </div>
        <div class="field">
          <label for="salary">Sueldo:</label>
          <select name="salary" id="salary">
            <option value="">Seleccione una opción</option>
            <option value="mas-400">
              Más de 400 €
            </option>
            <option value="men-400">
              Menos de 400 €
            </option>
            <option value="variables">
              Variables
            </option>
          </select>
        </div>
        <fieldset>
          <div class="field">
            <label>
              <input name="enfermedad-profesional" type="checkbox">
              Con enfermedad profesional
            </label>
          </div>
          <div class="field">
            <label>
              <input name="con-papis" type="checkbox">
              Con padres a cargo
            </label>
          </div>
          <div class="field">
            <label>
              <input name="con-hijos" type="checkbox">
              Con hijos a cargo
            </label>
          </div>
        </fieldset>
      </fieldset>


      <button>Enviar formulario</button>
    </form>
```