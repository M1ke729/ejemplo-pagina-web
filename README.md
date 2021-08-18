
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="CSS/estilos.css">
    <title>Formulario</title>
</head>
<body >    
    <form action="" method="POST" class="estiloFormulario" >
        <fieldset>
    
            <legend>DATOS PERSONALES</legend>
            <label for="">NOMBRE: </label>
            <input type="text" name="txtNombre" placeholder="Ingresa tu nombre" required> <br>
            
            <label for="">EMAIL: </label>
            <input type="text" name="txtEmail" placeholder="ejemplo@gmail.com" required><br>
            
            <label for="">NUMERO: </label>
            <input type="text" name="txtNumero" placeholder="+51 930 7** ***" maxlength="11" required pattern="[0-9] {0-11}"><br>
            
            <label for="">FECHA NAC.</label>
            <input type="date" name="FECHA" required> <br>
            
            <label for="">SEXO: </label>
            <select name="" id="">
                <option>MASCULINO</option>
                <option>FEMENINO</option>
            </select>
    
    
        </fieldset>
        <br>
        <fieldset>
            <legend>DATOS COMPLEMENTARIOS</legend>
            <label for="">IDIOMAS : </label> <br>
                <input type="checkbox" name="idiomas" id="">ESPAÑOL
                <input type="checkbox" name="idiomas" id="">INGLES
                <input type="checkbox" name="idiomas" id="">FRANCES
                <input type="checkbox" name="idiomas" id="">PORTUGUES
        
        </fieldset>
        <br>
        <fieldset>
    
            <legend>CREACION DE CUENTA</legend>
            <label for="">PASSWORD: </label>
            <input type="password" name="txtPassword" placeholder="************" required> <br>
            <label for="">TIPO: </label>
            <input type="radio" name="TIPO">DELUXE
            <input type="radio" name="TIPO">PREMIUM
    
        </fieldset>
        
        <input type="submit" value="REGISTRAR CUENTA">
    
    </form>


    
    
</body>
</html>
