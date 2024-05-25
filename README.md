# Habilidades
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Formulario de registro</title>
    <link rel="stylesheet" href="css/style.css" />
  </head>
  <body>
    <div class="title-set">
      <h1 id="title">Curso de habilidades digitales</h1>
    </div>
    <form id="formulario" method="get" action="">
      <div class="container">
        <h2>Formulario de registros</h2>
        <label>Nombre:</label>
        <br />
        <input class="form-inputs" required />
        <br />
        <label>Apellido:</label>
        <br />
        <input class="form-inputs" required />
        <br />
        <label>Correo electr&oacute;nico:</label>
        <br />
        <input class="form-inputs" name="email" required />
        <br />
        <label>Tel&eacute;fono:</label>
        <br />
        <input
          class="form-inputs"
          placeholder="Formato: 123-456-789"
          required
        />
        <br />
        <label>Direcci&oacute;n:</label>
        <br />
        <textarea
          id="address"
          class="form-inputs"
          required
          placeholder="Ingrese su direcci&oacute;n"
          title="Direcci&oacute;n de residencia"
        ></textarea>
        <br />
        <label>Pa&iacute;s:</label>
        <br />
        <select class="form-inputs" required name="countries" id="country">
          <option value="" selected disabled>Seleccionar país</option>

          <option value="Costa Rica">Costa Rica</option>
          <option value="Nicaragua">Nicaragua</option>
          <option value="Panam&aacute;">Panam&aacute;</option>
          <option value="Honduras">Honduras</option>
          <option value="El Salvador">El Salvador</option>
        </select>
        <br />
        <label>G&eacute;nero:</label>
        <br />
        <input required type="radio" id="male" name="gender" value="male" />
        <label for="male">Masculino</label>
        <input type="radio" id="female" name="gender" value="female" />
        <label for="female">Femenino</label>
        <br />
        <label>Pretenci&oacute;n salarial</label>
        <br />
        <input
          class="form-inputs"
          required
          type="range"
          id="salary"
          name="salary"
          min="0"
          max="100000"
        />
        <br />
        <button class="button" type="submit">Registrarse</button>
        <br />
        <a href="indexprueba.html">Regresar</a>
      </div>
    </form>
  </body>
</html>
