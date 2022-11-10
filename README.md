# oci-grand-prix-oic
Material disponible para ejecturar el laboratorio de Oracle para OIC

1_ Para acceder a la Instancia de Integración, buscamos DEVELOPER SERVICES y luego INTEGRATION
 
2_ Una vez allí buscamos el Compartment en donde creamos la instancia y seleccionamos la instancia de integración que creamos al principio de la sesión. 
Los nombres de instancia pueden variar de acuerdo a lo que cada uno haya colocado. 












3_ Al seleccionar la instancia nos dirige a esta página, en donde deberemos seleccionar SERVICE CONSOLE









4_ Esta el la página de SERVICE CONSOLE, en donde deberemos desplegar el menú que se encuentra resaltado 

















5_ Una vez allí deberemos seleccionar INTEGRATIONS y dentro de INTEGRATIONS












6_ Aquí en BROWSE, importar uno a uno los siguientes archivos primero GRAND_PRIX_INICIAR y luego GRAND_PRIX_FINALIZAR













 Así nos quedaría página de Integración










Y en Connections











Si pasamos el cursor por la primera conexión CONN_LLAMADO sobre la fecha nos muestra un menú que nos permite editarla 
En el URL que es campo obligatorio, deberemos referenciar la integración con la aplicación   

https://test643-idi1o0a010nx-ia.integration.ocp.oraclecloud.com:443/ic/api/integration/v1/flows/rest/


Y en el campo de autenticación deberemos colocar las credenciales correspondientes para poder hacer uso de ese URL 

Usuario : laura.bigatti@oracle.com	

Passwd: Maipu19197546

Seleccionamos TEST  y aplicamos SAVE siempre que nos lo pida . 

Si pasamos el cursor por la segunda conexión CONN_INICIO_CARRERA sobre la fecha nos muestra un menú que nos permite editarla 
Seleccionamos TEST  y aplicamos SAVE siempre que nos lo pida .

7_ Si pasamos el cursor por la primera Integración GRAND_PRIX_INICIAR sobre la fecha nos muestra un menú que nos permite primero ACTIVARLA.  Una vez que esta activada la corremos con seleccionando test.





























{

  "Equipo": "Oracle",
  
  "Categoria": "Privada",
 
 "Piloto": "Laura"

}

Equipo, Categoria, Piloto son variable que reemplazaran en ese body con lo que corresponda 


8_Si pasamos el cursor por la primera Integración GRAND_PRIX_FINALIZAR sobre la fecha nos muestra un menú que nos permite primero ACTIVARLA.  Una vez que esta activada la corremos con seleccionando test.

 
En Nombre Piloto deberán colocar su propio nombre para que la carrera finalice y allí seleccionan TEST
