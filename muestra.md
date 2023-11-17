### Codigo JS
<scrpit>

    document.addEventListener("DOMContentLoaded", function() {

    var tabla = document.getElementById("miTabla");

   
    var fila = tabla.insertRow();

    
    var celdaNombre = fila.insertCell(0);
    var celdaEdad = fila.insertCell(1);
    var celdaPais = fila.insertCell(2);

   
    celdaNombre.innerHTML = "Carlos";
    celdaEdad.innerHTML = "28";
    celdaPais.innerHTML = "Argentina";
});

</scrpit>

### Codigo Java

```java
class U3_B5_18{
	public static void main(String[] args){
		
		for(int i=0; i<10; i++){//cada linea esta formada por i+1 caracteres
			for(int j=0; j<i+1; j++){//imprimir la linea caracter a caracter
				System.out.print("*");
			}
			System.out.println();
		}
	}
}
```

### Codigo PHP

```php

$id = POST_['id'];
$sql = select * from empleados where idEmpleado = $id
$consulta = $conexion->prepare($sql);
$consulta->execute();

header("location:index.php");

```

[enlace repositorio GitHub](https://github.com/a23loisrm/libro-git.git)
