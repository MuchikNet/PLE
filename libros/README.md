# Libros Electrónicos

## REGLAS GENERALES DE LA INFORMACIÓN DE LOS LIBROS Y REGISTROS ELECTRÓNICOS		

El Programa de Libros Electrónicos - PLE valida los libros y registros generados por el contribuyente en archivos en formato de texto, con la estructura que se indica en las siguientes hojas y cuyos campos deben estar separados por el caracter "| (conocido como pipe o palote). Adicionalmente, dichos archivos deben ser generados con los nombres que se detallan en la hoja "Libros Tributarios".

| N°|Aspecto solicitado|Regla|
|--|--|--|
|1|Monto negativo|Consignar el formato  "- #.##"|
|2|Texto|Texto libre entre palotes. No debe contener los caracteres: |,  /, \|
|3|Alfanumerico|Letras en mayusculas y minusculas (de la A a la Z) y los caracteres especiales ( ) , . -|
|4|Fecha|Debe ser menor o igual al periodo informado|
		
### Reglas de tipo y número de documento

|Nro.|Descripcion|LO|T|L|M|
|--|--|--|--|--|--|
|0|OTROS                        |15|A|V|-|	
|1|LIBRETA ELECTORAL O DNI      |08|N|F|-|
|4|CARNET DE EXTRANJERIA        |12|A|V|-|
|6|REG. UNICO DE CONTRIBUYENTES |11|N|F|M|
|7|PASAPORTE                    |12|A|V|-|
|A|CEDULA DIPLOMATICA           |15|N|F|-|

Donde:

´´´
LO	Longitud	
T	Tipo	
	A: Alfanumérico (Solo letras y números)	
	N: Numérico	
L	Tipo de longitud	
	F: Fija	
	V: Variable	
M	Módulo 11	
	M: Aplica	
	- : No aplica	
´´´

## ANEXO 2: ESTRUCTURAS E INFORMACIÓN DE LOS LIBROS Y/O REGISTROS ELECTRÓNICOS

* [Reglas generales de los comprobantes de pago](reglas_comprobantes.csv)
* [Estructura del nombre del archivo](libros_nombre.csv)
* [Lista de Libros Electrónicos](libros_lista.csv)

  (1) Se detalla lo que significa cada parte de la estructura del nombre
  (2) Podrán ser elaborados sin consignar información, siempre que cuente con la referida información con la estructura establecida en otro libro y/o registro llevado de manera electrónica y sea presentado cuando le sea requerido por la SUNAT
  (3) Este libro deberá registrarse en formato pdf. Su información y contenido debe estar de acuerdo a la normatividad señalada por la Superintendencia del Mercado de Valores - SMV
