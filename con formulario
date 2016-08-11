<!DOCTYPE html>
<html>
  <head>
    <link type='text/css' rel='stylesheet' href='style.css'/>
    <title>PHP!</title>
  </head>
  <body>

<!– dejo espacio para que el primer boton aparezca mas centrado en verticalmente en la pantalla–>




  
 <?php   
    
/* Defino las relaciones generales positivas e inversas */ 
    
    
    function relacioninv ($var1,$var2,$nomvar) {
            
    for ($posibvar1 = 0; $posibvar1 <  8; ++$posibvar1) {
    
    if ($var1[$posibvar1][0] == 2) {
        
        for ($posibvar2 = 0; $posibvar2 <  8; ++$posibvar2) {
        
        if ($var2[$posibvar2][0] == 0)  
        
          
            {   $var2 [$posibvar2][1] = $nomvar; 
                $var2 [$posibvar2][0] = 1;    
                break;  } 
        }
                         return $var2;   }  
                                
     if ($var1[$posibvar1][0] == 1) {
        
        for ($posibvar2 = 0; $posibvar2 <  8; ++$posibvar2) {
        
        if ($var2[$posibvar2][0] == 0)  

            {   $var2 [$posibvar2][1] = $nomvar; 
                $var2 [$posibvar2][0] = 2;    
                break; } 
                            } return $var2; } 
                            
                            }                                           
                            return $var2;
                            
                            }  
                            
   
    function relacionpos ($var1,$var2,$nomvar) {
            
    for ($posibvar1 = 0; $posibvar1 <  8; ++$posibvar1) {
    
    if ($var1[$posibvar1][0] == 2) {
        
        for ($posibvar2 = 0; $posibvar2 <  8; ++$posibvar2) {
        
        if ($var2[$posibvar2][0] == 0)  
        
          
            {   $var2 [$posibvar2][1] = $nomvar; 
                $var2 [$posibvar2][0] = 2;    
                break;  } 
                        }     return $var2; } 
                                
     if ($var1[$posibvar1][0] == 1) {
        
        for ($posibvar2 = 0; $posibvar2 <  8; ++$posibvar2) {
        
        if ($var2[$posibvar2][0] == 0)  

            {   $var2 [$posibvar2][1] = $nomvar; 
                $var2 [$posibvar2][0] = 1;    
                break; } 
        }
                             return $var2; } 
                            }  return $var2;
                                                                    
                            } 

   
 /* Funcion para crear variable nueva   */   
   
  function creavar ($nomvar) { 
      
      $var=array();
      array_push ($var, $nomvar);
      
      for ($tiempo = 1; $tiempo <  20; ++$tiempo) { 
          
          
          $var[]=array (array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0)) ;
          
            
            }
            
            return $var;
            }
   
   
   /* Funcion para mandar una variable nueva a la matriz global de variables   */  
   
   function ingmodelo ($variable,$variables) { 
   
   
   $variables[$variable[0]] = $variable;
   
   return $variables;
   }
      

/*  Lo siguiente ya esta desactualizado: Defino las variables del modelo económico, el primer argumento es el nombre, los siguientes representan distintos tiempos y dentro de cada tiempo hay un array que contiene el estado de la variable y el nombre de la variable que causó su variación de estado */    
   
    
    $liquidez= array("Liquidez Dineraria",array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0),array (0,0));
   
/* Aca  abajo crear nueva variable con funcion   */ 


$invprivada= creavar ("Inversión Bruta Privada");
$pbi= creavar ("Producto Bruto Interno"); 
$invneta= creavar ("Inversión Neta General"); 
$gastopub= creavar ("Gasto Público");
$saldofiscal= creavar ("Saldo Fiscal Público");
$consumo= creavar ("Consumo");
$ingempresas= creavar ("Ingreso de las Empresas");
$endeudpubnac= creavar ("Endeudamiento Público Nacional");
$endudpubext= creavar ("Endeudamiento Público Exterior");
$basemon= creavar ("Base Monetaria (dinero en circulación)");
$impuestos= creavar ("Impuestos");
$rentabilidad= creavar ("Rentabilidad Empresaria");
$inghogares= creavar ("Ingresos de los Hogares");
$ahorrohogares= creavar ("Ahorro de los Hogares");
$gananciasemp= creavar ("Ganancias de las Empresas");
$expo= creavar ("Exportaciones");
$saldobp= creavar ("Saldo de la Balanza de Pagos");
$ofertadivisas= creavar ("Oferta de Divisas");
$impo= creavar ("Importaciones");
$demandadivisas= creavar ("Demanda de Divisas");
$bzacomercial= creavar ("Balanza Comercial (Exportaciones netas de Importaciones)");
$actfinhog= creavar ("Activos Financieros de los Hogares");
$uticapprod= creavar ("Utilización de Capacidad Productiva");
$productividad= creavar ("Productividad");
$precios= creavar ("Nivel de Precios (Inflación)");
$pbipotencial= creavar ("PBI Potencial de la Economía");
$salreal= creavar ("Salario Real");
$tcr= creavar ("Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)");
$transfhog= creavar ("Transferencias a los hogares");
$reservas= creavar ("Reservas Internacionales del Banco Central");
$salnom= creavar ("Salario Nominal");
$costoprod= creavar ("Costos de Producción");
$ofertatrabajo= creavar ("Oferta de Trabajo (Fuerza Laboral)");
$desigualdad= creavar ("Desigualdad");
$depreciacion= creavar ("Depreciacion del capital fijo");
$skf= creavar ("Stock de Capital Fijo (Capacidad Productiva Instalada)");
$invpublica= creavar ("Inversión Pública");
$demandatrabajo= creavar ("Demanda de Trabajo");
$tasainteres= creavar ("Tasa de Interés (Precio del Dinero/ Activos Financieros)");
$credinv= creavar ("Créditos a la Inversión");
$credconsumo= creavar ("Créditos al Consumo");
$rendactfin= creavar ("Rendimiento Activos Financieros");
$ingcapfin= creavar ("Ingreso de Capitales Financieros");
$demactfin= creavar ("Demanda de Activos Financieros");
$depbancarios= creavar ("Depositos Bancarios");
$encaje= creavar ("Encaje Bancario (Liquidez Obligatoria de los Bancos)");
$intdeupub= creavar ("Intereses de Deuda Pública");
$cambiotech= creavar ("Cambio Tecnológico");
$arancel= creavar ("Aranceles de Importacion");
$retenciones= creavar ("Retenciones a las Exportaciones");
$ied= creavar ("Inversión Extranjera Directa");
$endeuprivext= creavar ("Endeudamiento Privado con el Exterior");
$tcn= creavar ("Tipo de Cambio Nominal($/US$)");
$tcfuturo= creavar ("Tipo de cambio futuro esperado");
$inflamundial= creavar ("Inflación Mundial");
$tasaint= creavar ("Tasa de Interés Internacional (Rendimiento de activos financieros exernos)");
$pbimundial= creavar ("PBI Mundial");
$salcapfin= creavar ("Salida de Capitales Financieros");
$empleo= creavar ("Empleo");
$markup= creavar ("Mark-Up");
$caphum= creavar ("Cualificación de la Fuerza de Trabajo");
$compragobbon= creavar ("Compra por parte del Gobierno de Bonos Públicos");
$ventagobbon= creavar ("Venta por parte del Gobierno de Bonos Públicos");
$concentracion= creavar ("Concentración de Mercado (Monopolios/Oligopolios)");
$a= creavar ("");
$a= creavar ("");
$a= creavar ("");
$a= creavar ("");
$a= creavar ("");



/* Modifico el estado de una variable para dar comienzo a la ejecución del modelo   */ 
    


    
    $invpublica[1][0][0]=1;
     
   
   
   /* Creo la matriz general, el arrays con todas las variables  */  
    
 $variables= array();
    
    
/* Aca abajo ingreso nuevas variables al modelo  */ 
    
    
    
    $variables= ingmodelo ($invneta,$variables);
    $variables= ingmodelo ($pbi,$variables);
    $variables= ingmodelo ($gastopub,$variables);
    $variables= ingmodelo ($saldofiscal,$variables);
    $variables= ingmodelo ($consumo,$variables);
    $variables= ingmodelo ($ingempresas,$variables);
    $variables= ingmodelo ($invprivada,$variables);
    $variables= ingmodelo ($endeudpubnac,$variables);
    $variables= ingmodelo ($endudpubext,$variables);
    $variables= ingmodelo ($basemon,$variables);
    $variables= ingmodelo ($impuestos,$variables);
    $variables= ingmodelo ($rentabilidad,$variables);
    $variables= ingmodelo ($inghogares,$variables);
    $variables= ingmodelo ($ahorrohogares,$variables);
    $variables= ingmodelo ($gananciasemp,$variables);
    $variables= ingmodelo ($expo,$variables);
    $variables= ingmodelo ($saldobp,$variables);
    $variables= ingmodelo ($ofertadivisas,$variables);
    $variables= ingmodelo ($impo,$variables);
    $variables= ingmodelo ($demandadivisas,$variables);
    $variables= ingmodelo ($bzacomercial,$variables);
    $variables= ingmodelo ($actfinhog,$variables);
    $variables= ingmodelo ($uticapprod,$variables);
    $variables= ingmodelo ($productividad,$variables);
    $variables= ingmodelo ($precios,$variables);
    $variables= ingmodelo ($pbipotencial,$variables);
    $variables= ingmodelo ($salreal,$variables);
    $variables= ingmodelo ($tcr,$variables);
    $variables= ingmodelo ($transfhog,$variables);
    $variables= ingmodelo ($reservas,$variables);
    $variables= ingmodelo ($salnom,$variables);
    $variables= ingmodelo ($costoprod,$variables);
    $variables= ingmodelo ($ofertatrabajo,$variables);
    $variables= ingmodelo ($desigualdad,$variables);
    $variables= ingmodelo ($depreciacion,$variables);
    $variables= ingmodelo ($skf,$variables);
    $variables= ingmodelo ($invpublica,$variables);
    $variables= ingmodelo ($demandatrabajo,$variables);
    $variables= ingmodelo ($tasainteres,$variables);
    $variables= ingmodelo ($credinv,$variables);
    $variables= ingmodelo ($credconsumo,$variables);
    $variables= ingmodelo ($rendactfin,$variables);
    $variables= ingmodelo ($ingcapfin,$variables);
    $variables= ingmodelo ($demactfin,$variables);
    $variables= ingmodelo ($depbancarios,$variables);
    $variables= ingmodelo ($encaje,$variables);
    $variables= ingmodelo ($intdeupub,$variables);
    $variables= ingmodelo ($cambiotech,$variables);
    $variables= ingmodelo ($arancel,$variables);
    $variables= ingmodelo ($retenciones,$variables);
    $variables= ingmodelo ($ied,$variables);
    $variables= ingmodelo ($endeuprivext,$variables);
    $variables= ingmodelo ($tcn,$variables);
    $variables= ingmodelo ($tcfuturo,$variables);
    $variables= ingmodelo ($inflamundial,$variables);
    $variables= ingmodelo ($tasaint,$variables);
    $variables= ingmodelo ($pbimundial,$variables);
    $variables= ingmodelo ($salcapfin,$variables);
    $variables= ingmodelo ($empleo,$variables);
    $variables= ingmodelo ($markup,$variables);
    $variables= ingmodelo ($caphum,$variables);
    $variables= ingmodelo ($compragobbon,$variables);
    $variables= ingmodelo ($ventagobbon,$variables);
    $variables= ingmodelo ($concentracion,$variables);
    
    
    
    
    
/*construyo lista de variables para lista desplegable*/

Function generolista($variables) {

$listadesplegable=array();

foreach ($variables as $variable=>$nombre) {
        
            
        array_push ($listadesplegable, $variables[$variable][0]);
    
    }
        return $listadesplegable;
    }

$listadesplegable= generolista($variables);


    
    
    
/* Acá doy forma al modelo, esta funcion contiene todas las relaciones entre las distintas variables */ 
    
    function itera($variables,$tiempo) {
    
   
    
    
     
     $variables["Inversión Neta General"][$tiempo+1]=relacionpos($variables["Inversión Bruta Privada"][$tiempo],$variables["Inversión Neta General"][$tiempo+1],$variables["Inversión Bruta Privada"][0]);
     
    
     $variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Inversión Bruta Privada"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Inversión Bruta Privada"][0]); 
    
     $variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Gasto Público"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Gasto Público"][0]); 
   
    $variables["Saldo Fiscal Público"][$tiempo+1]=relacioninv($variables["Gasto Público"][$tiempo],$variables["Saldo Fiscal Público"][$tiempo+1],$variables["Gasto Público"][0]);
    
    $variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Consumo"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Consumo"][0]);
    
    $variables["Ingreso de las Empresas"][$tiempo+1]=relacionpos($variables["Consumo"][$tiempo],$variables["Ingreso de las Empresas"][$tiempo+1],$variables["Consumo"][0]);
    
    $variables["Endeudamiento Público Nacional"][$tiempo+1]=relacioninv($variables["Saldo Fiscal Público"][$tiempo],$variables["Endeudamiento Público Nacional"][$tiempo+1],$variables["Saldo Fiscal Público"][0]);
    
$variables["Endeudamiento Público Exterior"][$tiempo+1]=relacioninv($variables["Saldo Fiscal Público"][$tiempo],$variables["Endeudamiento Público Exterior"][$tiempo+1],$variables["Saldo Fiscal Público"][0]);

$variables["Base Monetaria (dinero en circulación)"][$tiempo+1]=relacioninv($variables["Saldo Fiscal Público"][$tiempo],$variables["Base Monetaria (dinero en circulación)"][$tiempo+1],$variables["Saldo Fiscal Público"][0]);

$variables["Saldo Fiscal Público"][$tiempo+1]=relacionpos($variables["Impuestos"][$tiempo],$variables["Saldo Fiscal Público"][$tiempo+1],$variables["Impuestos"][0]);

$variables["Rentabilidad Empresaria"][$tiempo+1]=relacioninv($variables["Impuestos"][$tiempo],$variables["Rentabilidad Empresaria"][$tiempo+1],$variables["Impuestos"][0]);

$variables["Ingresos de los Hogares"][$tiempo+1]=relacioninv($variables["Impuestos"][$tiempo],$variables["Ingresos de los Hogares"][$tiempo+1],$variables["Impuestos"][0]); 


$variables["Consumo"][$tiempo+1]=relacionpos($variables["Ingresos de los Hogares"][$tiempo],$variables["Consumo"][$tiempo+1],$variables["Ingresos de los Hogares"][0]); 
 
 $variables["Ahorro de los Hogares"][$tiempo+1]=relacionpos($variables["Ingresos de los Hogares"][$tiempo],$variables["Ahorro de los Hogares"][$tiempo+1],$variables["Ingresos de los Hogares"][0]); 

$variables["Ganancias de las Empresas"][$tiempo+1]=relacionpos($variables["Rentabilidad Empresaria"][$tiempo],$variables["Ganancias de las Empresas"][$tiempo+1],$variables["Rentabilidad Empresaria"][0]);

$variables["Inversión Bruta Privada"][$tiempo+1]=relacionpos($variables["Rentabilidad Empresaria"][$tiempo],$variables["Inversión Bruta Privada"][$tiempo+1],$variables["Rentabilidad Empresaria"][0]);

$variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Exportaciones"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Exportaciones"][0]);  
 
 $variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Exportaciones"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Exportaciones"][0]);
 
 $variables["Oferta de Divisas"][$tiempo+1]=relacionpos($variables["Exportaciones"][$tiempo],$variables["Oferta de Divisas"][$tiempo+1],$variables["Exportaciones"][0]);
 
 $variables["Producto Bruto Interno"][$tiempo+1]=relacioninv($variables["Importaciones"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Importaciones"][0]);  
 
 $variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacioninv($variables["Importaciones"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Importaciones"][0]);
 
 $variables["Demanda de Divisas"][$tiempo+1]=relacionpos($variables["Importaciones"][$tiempo],$variables["Demanda de Divisas"][$tiempo+1],$variables["Importaciones"][0]);
 

 $variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Balanza Comercial (Exportaciones netas de Importaciones)"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Balanza Comercial (Exportaciones netas de Importaciones)"][0]);  
 
 $variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Balanza Comercial (Exportaciones netas de Importaciones)"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Balanza Comercial (Exportaciones netas de Importaciones)"][0]);
 
 $variables["Oferta de Divisas"][$tiempo+1]=relacionpos($variables["Balanza Comercial (Exportaciones netas de Importaciones)"][$tiempo],$variables["Oferta de Divisas"][$tiempo+1],$variables["Balanza Comercial (Exportaciones netas de Importaciones)"][0]);
 
 $variables["Ingresos de los Hogares"][$tiempo+1]=relacionpos($variables["Activos Financieros de los Hogares"][$tiempo],$variables["Ingresos de los Hogares"][$tiempo+1],$variables["Activos Financieros de los Hogares"][0]); 
 
 $variables["Producto Bruto Interno"][$tiempo+1]=relacionpos($variables["Utilización de Capacidad Productiva"][$tiempo],$variables["Producto Bruto Interno"][$tiempo+1],$variables["Utilización de Capacidad Productiva"][0]);  
 
 $variables["Rentabilidad Empresaria"][$tiempo+1]=relacionpos($variables["Productividad"][$tiempo],$variables["Rentabilidad Empresaria"][$tiempo+1],$variables["Productividad"][0]);
 
 $variables["Nivel de Precios (Inflación)"][$tiempo+1]=relacionpos($variables["Productividad"][$tiempo],$variables["Nivel de Precios (Inflación)"][$tiempo+1],$variables["Productividad"][0]);
 
 $variables["PBI Potencial de la Economía"][$tiempo+1]=relacionpos($variables["Productividad"][$tiempo],$variables["PBI Potencial de la Economía"][$tiempo+1],$variables["Productividad"][0]);
 
$variables["Salario Real"][$tiempo+1]=relacioninv($variables["Nivel de Precios (Inflación)"][$tiempo],$variables["Salario Real"][$tiempo+1],$variables["Nivel de Precios (Inflación)"][0]); 
 
$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1]=relacionpos($variables["Nivel de Precios (Inflación)"][$tiempo],$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1],$variables["Nivel de Precios (Inflación)"][0]);  
 
 $variables["Impuestos"][$tiempo+1]=relacionpos($variables["Nivel de Precios (Inflación)"][$tiempo],$variables["Impuestos"][$tiempo+1],$variables["Nivel de Precios (Inflación)"][0]);  
 
 $variables["Ingresos de los Hogares"][$tiempo+1]=relacionpos($variables["Transferencias a los hogares"][$tiempo],$variables["Ingresos de los Hogares"][$tiempo+1],$variables["Transferencias a los hogares"][0]); 
 
 $variables["Gasto Público"][$tiempo+1]=relacionpos($variables["Transferencias a los hogares"][$tiempo],$variables["Gasto Público"][$tiempo+1],$variables["Transferencias a los hogares"][0]); 
 
$variables["Reservas Internacionales del Banco Central"][$tiempo+1]=relacionpos($variables["Saldo de la Balanza de Pagos"][$tiempo],$variables["Reservas Internacionales del Banco Central"][$tiempo+1],$variables["Saldo de la Balanza de Pagos"][0]); 
 
$variables["Salario Real"][$tiempo+1]=relacionpos($variables["Salario Nominal"][$tiempo],$variables["Salario Real"][$tiempo+1],$variables["Salario Nominal"][0]); 

$variables["Costos de Producción"][$tiempo+1]=relacionpos($variables["Salario Nominal"][$tiempo],$variables["Costos de Producción"][$tiempo+1],$variables["Salario Nominal"][0]); 

$variables["Ingresos de los Hogares"][$tiempo+1]=relacionpos($variables["Salario Real"][$tiempo],$variables["Ingresos de los Hogares"][$tiempo+1],$variables["Salario Real"][0]); 

$variables["Oferta de Trabajo (Fuerza Laboral)"][$tiempo+1]=relacionpos($variables["Salario Real"][$tiempo],$variables["Oferta de Trabajo (Fuerza Laboral)"][$tiempo+1],$variables["Salario Real"][0]); 

$variables["Desigualdad"][$tiempo+1]=relacioninv($variables["Salario Real"][$tiempo],$variables["Desigualdad"][$tiempo+1],$variables["Salario Real"][0]); 

 $variables["Inversión Neta General"][$tiempo+1]=relacioninv($variables["Depreciacion del capital fijo"][$tiempo],$variables["Inversión Neta General"][$tiempo+1],$variables["Depreciacion del capital fijo"][0]); 
 
$variables["Stock de Capital Fijo (Capacidad Productiva Instalada)"][$tiempo+1]=relacionpos($variables["Inversión Neta General"][$tiempo],$variables["Stock de Capital Fijo (Capacidad Productiva Instalada)"][$tiempo+1],$variables["Inversión Neta General"][0]);  
 
$variables["PBI Potencial de la Economía"][$tiempo+1]=relacionpos($variables["Stock de Capital Fijo (Capacidad Productiva Instalada)"][$tiempo],$variables["PBI Potencial de la Economía"][$tiempo+1],$variables["Stock de Capital Fijo (Capacidad Productiva Instalada)"][0]); 
 
$variables["Inversión Neta General"][$tiempo+1]=relacionpos($variables["Inversión Pública"][$tiempo],$variables["Inversión Neta General"][$tiempo+1],$variables["Inversión Pública"][0]);  

$variables["Gasto Público"][$tiempo+1]=relacionpos($variables["Inversión Pública"][$tiempo],$variables["Gasto Público"][$tiempo+1],$variables["Inversión Pública"][0]);   
 
$variables["Demanda de Trabajo"][$tiempo+1]=relacionpos($variables["Producto Bruto Interno"][$tiempo],$variables["Demanda de Trabajo"][$tiempo+1],$variables["Producto Bruto Interno"][0]);   

$variables["Créditos a la Inversión"][$tiempo+1]=relacioninv($variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][$tiempo],$variables["Créditos a la Inversión"][$tiempo+1],$variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][0]);    
 
$variables["Créditos al Consumo"][$tiempo+1]=relacioninv($variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][$tiempo],$variables["Créditos al Consumo"][$tiempo+1],$variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][0]);   
 
$variables["Rendimiento Activos Financieros"][$tiempo+1]=relacionpos($variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][$tiempo],$variables["Rendimiento Activos Financieros"][$tiempo+1],$variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][0]);   
 
$variables["Consumo"][$tiempo+1]=relacionpos($variables["Créditos al Consumo"][$tiempo],$variables["Consumo"][$tiempo+1],$variables["Créditos al Consumo"][0]);   
 
$variables["Inversión Bruta Privada"][$tiempo+1]=relacionpos($variables["Créditos a la Inversión"][$tiempo],$variables["Inversión Bruta Privada"][$tiempo+1],$variables["Créditos a la Inversión"][0]);    
 
$variables["Inversión Bruta Privada"][$tiempo+1]=relacionpos($variables["Rendimiento Activos Financieros"][$tiempo],$variables["Inversión Bruta Privada"][$tiempo+1],$variables["Rendimiento Activos Financieros"][0]);     
 
$variables["Demanda de Activos Financieros"][$tiempo+1]=relacionpos($variables["Rendimiento Activos Financieros"][$tiempo],$variables["Demanda de Activos Financieros"][$tiempo+1],$variables["Rendimiento Activos Financieros"][0]);  

$variables["Ingreso de Capitales Financieros"][$tiempo+1]=relacionpos($variables["Rendimiento Activos Financieros"][$tiempo],$variables["Ingreso de Capitales Financieros"][$tiempo+1],$variables["Rendimiento Activos Financieros"][0]);  
 
$variables["Activos Financieros de los Hogares"][$tiempo+1]=relacionpos($variables["Ahorro de los Hogares"][$tiempo],$variables["Activos Financieros de los Hogares"][$tiempo+1],$variables["Ahorro de los Hogares"][0]);  
 
$variables["Depositos Bancarios"][$tiempo+1]=relacionpos($variables["Ahorro de los Hogares"][$tiempo],$variables["Depositos Bancarios"][$tiempo+1],$variables["Ahorro de los Hogares"][0]);   
 
$variables["Créditos a la Inversión"][$tiempo+1]=relacionpos($variables["Depositos Bancarios"][$tiempo],$variables["Créditos a la Inversión"][$tiempo+1],$variables["Depositos Bancarios"][0]);   

$variables["Créditos al Consumo"][$tiempo+1]=relacionpos($variables["Depositos Bancarios"][$tiempo],$variables["Créditos al Consumo"][$tiempo+1],$variables["Depositos Bancarios"][0]);   

$variables["Demanda de Activos Financieros"][$tiempo+1]=relacionpos($variables["Base Monetaria (dinero en circulación)"][$tiempo],$variables["Demanda de Activos Financieros"][$tiempo+1],$variables["Base Monetaria (dinero en circulación)"][0]);   

 $variables["Créditos a la Inversión"][$tiempo+1]=relacioninv($variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][$tiempo],$variables["Créditos a la Inversión"][$tiempo+1],$variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][0]);   

$variables["Créditos al Consumo"][$tiempo+1]=relacioninv($variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][$tiempo],$variables["Créditos al Consumo"][$tiempo+1],$variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][0]);   

$variables["Base Monetaria (dinero en circulación)"][$tiempo+1]=relacioninv($variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][$tiempo],$variables["Base Monetaria (dinero en circulación)"][$tiempo+1],$variables["Encaje Bancario (Liquidez Obligatoria de los Bancos)"][0]);    

$variables["Intereses de Deuda Pública"][$tiempo+1]=relacionpos($variables["Endeudamiento Público Nacional"][$tiempo],$variables["Intereses de Deuda Pública"][$tiempo+1],$variables["Endeudamiento Público Nacional"][0]);  
 
$variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][$tiempo+1]=relacioninv($variables["Demanda de Activos Financieros"][$tiempo],$variables["Tasa de Interés (Precio del Dinero/ Activos Financieros)"][$tiempo+1],$variables["Demanda de Activos Financieros"][0]);  

$variables["Productividad"][$tiempo+1]=relacionpos($variables["Cambio Tecnológico"][$tiempo],$variables["Productividad"][$tiempo+1],$variables["Cambio Tecnológico"][0]);  

$variables["Inversión Bruta Privada"][$tiempo+1]=relacionpos($variables["Ganancias de las Empresas"][$tiempo],$variables["Inversión Bruta Privada"][$tiempo+1],$variables["Ganancias de las Empresas"][0]);  

$variables["Demanda de Activos Financieros"][$tiempo+1]=relacionpos($variables["Ganancias de las Empresas"][$tiempo],$variables["Demanda de Activos Financieros"][$tiempo+1],$variables["Ganancias de las Empresas"][0]);   

$variables["Demanda de Divisas"][$tiempo+1]=relacionpos($variables["Ganancias de las Empresas"][$tiempo],$variables["Demanda de Divisas"][$tiempo+1],$variables["Ganancias de las Empresas"][0]);  

$variables["Impuestos"][$tiempo+1]=relacionpos($variables["Aranceles de Importacion"][$tiempo],$variables["Impuestos"][$tiempo+1],$variables["Aranceles de Importacion"][0]);  

$variables["Impuestos"][$tiempo+1]=relacionpos($variables["Retenciones a las Exportaciones"][$tiempo],$variables["Impuestos"][$tiempo+1],$variables["Retenciones a las Exportaciones"][0]);  

$variables["Importaciones"][$tiempo+1]=relacioninv($variables["Aranceles de Importacion"][$tiempo],$variables["Importaciones"][$tiempo+1],$variables["Aranceles de Importacion"][0]);  

$variables["Exportaciones"][$tiempo+1]=relacioninv($variables["Retenciones a las Exportaciones"][$tiempo],$variables["Exportaciones"][$tiempo+1],$variables["Retenciones a las Exportaciones"][0]);  

$variables["Inversión Bruta Privada"][$tiempo+1]=relacionpos($variables["Inversión Extranjera Directa"][$tiempo],$variables["Inversión Bruta Privada"][$tiempo+1],$variables["Inversión Extranjera Directa"][0]);  

$variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Inversión Extranjera Directa"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Inversión Extranjera Directa"][0]); 

$variables["Oferta de Divisas"][$tiempo+1]=relacionpos($variables["Inversión Extranjera Directa"][$tiempo],$variables["Oferta de Divisas"][$tiempo+1],$variables["Inversión Extranjera Directa"][0]); 

$variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Endeudamiento Público Exterior"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Endeudamiento Público Exterior"][0]); 

$variables["Intereses de Deuda Pública"][$tiempo+1]=relacionpos($variables["Endeudamiento Público Exterior"][$tiempo],$variables["Intereses de Deuda Pública"][$tiempo+1],$variables["Endeudamiento Público Exterior"][0]);

$variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Endeudamiento Privado con el Exterior"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Endeudamiento Privado con el Exterior"][0]); 

$variables["Tipo de Cambio Nominal($/US$)"][$tiempo+1]=relacionpos($variables["Demanda de Divisas"][$tiempo],$variables["Tipo de Cambio Nominal($/US$)"][$tiempo+1],$variables["Demanda de Divisas"][0]);

$variables["Reservas Internacionales del Banco Central"][$tiempo+1]=relacioninv($variables["Demanda de Divisas"][$tiempo],$variables["Reservas Internacionales del Banco Central"][$tiempo+1],$variables["Demanda de Divisas"][0]);

$variables["Tipo de Cambio Nominal($/US$)"][$tiempo+1]=relacioninv($variables["Oferta de Divisas"][$tiempo],$variables["Tipo de Cambio Nominal($/US$)"][$tiempo+1],$variables["Oferta de Divisas"][0]);

$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1]=relacionpos($variables["Tipo de Cambio Nominal($/US$)"][$tiempo],$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1],$variables["Tipo de Cambio Nominal($/US$)"][0]);

$variables["Balanza Comercial (Exportaciones netas de Importaciones)"][$tiempo+1]=relacionpos($variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo],$variables["Balanza Comercial (Exportaciones netas de Importaciones)"][$tiempo+1],$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][0]);

$variables["Costos de Producción"][$tiempo+1]=relacionpos($variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo],$variables["Costos de Producción"][$tiempo+1],$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][0]);

$variables["Rendimiento Activos Financieros"][$tiempo+1]=relacioninv($variables["Tipo de cambio futuro esperado"][$tiempo],$variables["Rendimiento Activos Financieros"][$tiempo+1],$variables["Tipo de cambio futuro esperado"][0]);

$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1]=relacionpos($variables["Inflación Mundial"][$tiempo],$variables["Tipo de Cambio Real (Precio relativo de bienes extranjeros frente a locales)"][$tiempo+1],$variables["Inflación Mundial"][0]);

$variables["Rendimiento Activos Financieros"][$tiempo+1]=relacioninv($variables["Tasa de Interés Internacional (Rendimiento de activos financieros exernos)"][$tiempo],$variables["Rendimiento Activos Financieros"][$tiempo+1],$variables["Tasa de Interés Internacional (Rendimiento de activos financieros exernos)"][0]);

$variables["Exportaciones"][$tiempo+1]=relacionpos($variables["PBI Mundial"][$tiempo],$variables["Exportaciones"][$tiempo+1],$variables["PBI Mundial"][0]);

$variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacionpos($variables["Ingreso de Capitales Financieros"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Ingreso de Capitales Financieros"][0]);

$variables["Oferta de Divisas"][$tiempo+1]=relacionpos($variables["Ingreso de Capitales Financieros"][$tiempo],$variables["Oferta de Divisas"][$tiempo+1],$variables["Ingreso de Capitales Financieros"][0]);

$variables["Depositos Bancarios"][$tiempo+1]=relacionpos($variables["Ingreso de Capitales Financieros"][$tiempo],$variables["Depositos Bancarios"][$tiempo+1],$variables["Ingreso de Capitales Financieros"][0]);

$variables["Saldo de la Balanza de Pagos"][$tiempo+1]=relacioninv($variables["Salida de Capitales Financieros"][$tiempo],$variables["Saldo de la Balanza de Pagos"][$tiempo+1],$variables["Salida de Capitales Financieros"][0]);

$variables["Demanda de Divisas"][$tiempo+1]=relacionpos($variables["Salida de Capitales Financieros"][$tiempo],$variables["Demanda de Divisas"][$tiempo+1],$variables["Salida de Capitales Financieros"][0]);

$variables["Depositos Bancarios"][$tiempo+1]=relacioninv($variables["Salida de Capitales Financieros"][$tiempo],$variables["Depositos Bancarios"][$tiempo+1],$variables["Salida de Capitales Financieros"][0]);

$variables["Empleo"][$tiempo+1]=relacionpos($variables["Demanda de Trabajo"][$tiempo],$variables["Empleo"][$tiempo+1],$variables["Demanda de Trabajo"][0]);

$variables["Salario Real"][$tiempo+1]=relacionpos($variables["Demanda de Trabajo"][$tiempo],$variables["Salario Real"][$tiempo+1],$variables["Demanda de Trabajo"][0]);

$variables["PBI Potencial de la Economía"][$tiempo+1]=relacionpos($variables["Oferta de Trabajo (Fuerza Laboral)"][$tiempo],$variables["PBI Potencial de la Economía"][$tiempo+1],$variables["Oferta de Trabajo (Fuerza Laboral)"][0]);

$variables["Ingresos de los Hogares"][$tiempo+1]=relacionpos($variables["Empleo"][$tiempo],$variables["Ingresos de los Hogares"][$tiempo+1],$variables["Empleo"][0]);

$variables["Nivel de Precios (Inflación)"][$tiempo+1]=relacionpos($variables["Mark-Up"][$tiempo],$variables["Nivel de Precios (Inflación)"][$tiempo+1],$variables["Mark-Up"][0]);

$variables["Rentabilidad Empresaria"][$tiempo+1]=relacionpos($variables["Mark-Up"][$tiempo],$variables["Rentabilidad Empresaria"][$tiempo+1],$variables["Mark-Up"][0]);

$variables["Ganancias de las Empresas"][$tiempo+1]=relacionpos($variables["Ingreso de las Empresas"][$tiempo],$variables["Ganancias de las Empresas"][$tiempo+1],$variables["Ingreso de las Empresas"][0]);

$variables["Productividad"][$tiempo+1]=relacionpos($variables["Cualificación de la Fuerza de Trabajo"][$tiempo],$variables["Productividad"][$tiempo+1],$variables["Cualificación de la Fuerza de Trabajo"][0]);

$variables["Nivel de Precios (Inflación)"][$tiempo+1]=relacionpos($variables["Costos de Producción"][$tiempo],$variables["Nivel de Precios (Inflación)"][$tiempo+1],$variables["Costos de Producción"][0]);

$variables["Base Monetaria (dinero en circulación)"][$tiempo+1]=relacionpos($variables["Compra por parte del Gobierno de Bonos Públicos"][$tiempo],$variables["Base Monetaria (dinero en circulación)"][$tiempo+1],$variables["Compra por parte del Gobierno de Bonos Públicos"][0]);

$variables["Endeudamiento Público Nacional"][$tiempo+1]=relacioninv($variables["Compra por parte del Gobierno de Bonos Públicos"][$tiempo],$variables["Endeudamiento Público Nacional"][$tiempo+1],$variables["Compra por parte del Gobierno de Bonos Públicos"][0]);

$variables["Base Monetaria (dinero en circulación)"][$tiempo+1]=relacioninv($variables["Venta por parte del Gobierno de Bonos Públicos"][$tiempo],$variables["Base Monetaria (dinero en circulación)"][$tiempo+1],$variables["Venta por parte del Gobierno de Bonos Públicos"][0]);

$variables["Endeudamiento Público Nacional"][$tiempo+1]=relacionpos($variables["Venta por parte del Gobierno de Bonos Públicos"][$tiempo],$variables["Endeudamiento Público Nacional"][$tiempo+1],$variables["Venta por parte del Gobierno de Bonos Públicos"][0]);

$variables["Nivel de Precios (Inflación)"][$tiempo+1]=relacionpos($variables["Concentración de Mercado (Monopolios/Oligopolios)"][$tiempo],$variables["Nivel de Precios (Inflación)"][$tiempo+1],$variables["Concentración de Mercado (Monopolios/Oligopolios)"][0]);




    return $variables ;

} 
          

/* Esta funcion es la que ejecuta la parte visual, va agregando los botones ordenamente */ 

Function agregavar($variables,$tiempo,$vario) {


/* Lo que sigue sirve para ordenar verticalmente, si una variable modifica a dos variables, tira la div siguiente más para arriba con longcol2 en vez de longcol1 */ 

/* Lo que sigue sirve para ordenar verticalmente, si una variable modifica a dos variables, tira la div siguiente más para arriba con longcol2 en vez de longcol1 */ 

$modifico=array();

foreach ($variables as $variable=>$nombre) {
        
        for ($posibilidad = 0; $posibilidad <  5; ++$posibilidad)
        {
        if ($variables [$variable][$tiempo][$posibilidad][1] === $vario) {


array_push ($modifico, "1");

}  
}
}

if (array_sum ($modifico )==0) {
    echo ' <div id="longcol"><p>';
}
if (array_sum ($modifico )==1) {
    
    echo ' <div id="longcol"><p>';
    }
if (array_sum ($modifico )==2) {
    
    echo ' <div id="longcol2"><p>';
    }
if (array_sum ($modifico )>=3) {
    
    echo ' <div id="longcol3"><p>';
    }

 

foreach ($variables as $variable=>$nombre) {

   for ($posibilidad = 0; $posibilidad <  5; ++$posibilidad) {
    
    if ($variables [$variable][$tiempo][$posibilidad][1] === $vario) {
        
        if ($variables [$variable][$tiempo][$posibilidad][0] == 2) {
         
         
          echo '  <div id="button0"><p>';
            echo "<font color='blue'> Baja" ;
            echo "   ";
            echo "<font color='black'>";
            echo $variables [$variable][0] ;
            echo  ' </div>';
    	 agregavar($variables,$tiempo+1,$variables [$variable][0]);
    	 
    	 
    	 } 
    	 
    	if ($variables [$variable][$tiempo][$posibilidad][0] == 1) {
             
            
            echo '  <div id="button0"><p>';
            echo "<font color='yellow'> Sube" ;
            echo " ";
            echo "<font color='black'>";
            echo $variables [$variable][0] ;
            echo  ' </div>';
            agregavar($variables,$tiempo+1,$variables [$variable][0]);
            
            
            
            }   
    	 
    	    
    	
    	    
    	  
     	    
    	}  	 }   }    echo ' </div> ';

                    } 

/* Corro el modelo. Itero primero en todos los tiempos disponibles y luego mando el agregavar para mostrar los resultados*/




$meses=array("azul", "verde","rojo");
$meses = $listadesplegable;  

echo '<form name="form1" id="form1" method="post" action="" >'; 
$nombre = 'meses'; 
$resultado = lista($nombre, $meses); 
echo $resultado; 
echo '</form>';  

function lista($nombre, $meses){ $array = $meses; $txt= "<select name='$nombre' id='$nombre' size='10' >  ";  

for ($i=0; $i<sizeof($array); $i++){ $txt .= "<option value='$i'>". $array[$i] . '</option>'; } $txt .= '</select>'; 
return $txt; };   

echo '<form name="form1" id="form1" method="post" action="" >';
echo "<select name='$nombre' id='$nombre' size='2' >  ";
echo " <option value='1'> Sube </option>";
echo " <option value='2'> Baja </option>";
echo "</form>";



$_POST["$nombre"];



for ($tiempo = 1; $tiempo <  6; ++$tiempo) {
    
    $variables=itera($variables,$tiempo);}

echo " <br> <br><br>
<br> <br><br>

<br> <br><br>
<br> <br><br>";



agregavar($variables, 1,0);








       ?>
      
    </p>
  </body>
</html> 
