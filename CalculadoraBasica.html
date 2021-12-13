<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8"/>
    <title>Calculadora Basica</title>
	<link rel="stylesheet" href="CalculadoraBasica.css"/>
</head>
<body>

    <?php
session_start();

class CalculadoraBasica {
    protected $pantalla;

    public function __construct(){
        $this->pantalla = "";
    }
    
    public function getPantalla(){
       
         return $this->pantalla;   
    }

    public function setPantalla($pantalla){
        
         $this->pantalla = $pantalla ;

   }

    public function escribe(){
       
         $this->pantalla = $_POST['pantalla'].$_POST['boton'];
       
      
    }

    public function igual(){
        $this->pantalla = $_POST['pantalla']; //OBTIENE EL VALOR DE LA PANTALLA
        try {
            return eval("return $this->pantalla ;");
        }catch (Throwable $t) {
            $this->pantalla = null;
        } 
    }

}

$operacion = "";
$calculadora = new CalculadoraBasica();
//Solo se ejecutará si se ha pulsado un botón
if (count($_POST)>0) 
    {
        if(isset($_POST['igual'])){
            $operacion =  $calculadora->igual();
        }else if(isset($_POST['C'])){
            $operacion = "";
        }else if(isset($_POST['boton'])){
            $calculadora->escribe();
            $operacion = $calculadora->getPantalla();
        }
    
        //MEMORIA
    if( isset( $_SESSION['acontecimientos'] ) ) {
        if(isset($_POST['m+'])){
            $_SESSION['acontecimientos'] += $calculadora->igual();
        }else if(isset($_POST['m-'])){
            $_SESSION['acontecimientos'] -= $calculadora->igual();
        }else if(isset($_POST['mrc'])){
            $operacion =  $_SESSION['acontecimientos'];
        }
    }else {
        $_SESSION['acontecimientos'] = $operacion;
    }

}


// Interfaz con el usuario. En el interior de comillas dobles se deben usar comillas simples
echo "  
    <main>
        <h1>Ejercicio 1</h1>  
        <form action='#' method='post' name='botones'>
            <p>
                <label for='pantalla'>pantalla</label>
                <input id='pantalla' type='text' title='pantalla' name='pantalla' value = '$operacion' readonly />
                
            </p>
            <p>
                <input type = 'submit' class='button' name = 'mrc' value='mrc'  />
                <input type = 'submit' class='button' name = 'm-' value='m-'  />
                <input type = 'submit' class='button' name = 'm+' value='m+' />
                <input type = 'submit' class='button' name = 'boton' value='/' />
            </p>
            <p> 
                <input type = 'submit' class='button' name = 'boton' value = '7'/>
                <input type = 'submit' class='button' name = 'boton' value = '8'/>
                <input type = 'submit' class='button' name = 'boton' value = '9'/>
                <input type = 'submit' class='button' name = 'boton' value='+' />
            </p>           
            <p>
                <input type = 'submit' class='button' name = 'boton' value = '4'/>
                <input type = 'submit' class='button' name = 'boton' value = '5'/>
                <input type = 'submit' class='button' name = 'boton' value = '6'/>
                <input type = 'submit' class='button' name = 'boton' value='*' />
            </p>        
            <p>
                <input type = 'submit' class='button' name = 'boton' value = '1'/>
                <input type = 'submit' class='button' name = 'boton' value = '2'/>
                <input type = 'submit' class='button' name = 'boton' value = '3'/>
                <input type = 'submit' class='button' name = 'boton' value='-' />
            </p>
            <p>
            <input type = 'submit' class='button' name = 'boton' value = '0'/>
            <input type = 'submit' class='button' name = 'boton' value = '.'/>
            <input type = 'submit' class='button' name = 'C' value = 'C'/>
            <input type = 'submit' class='button' name = 'igual' value = '='/>
            </p>
        </form>
    </main>
    ";

?>
 
    
</body>
</html>
