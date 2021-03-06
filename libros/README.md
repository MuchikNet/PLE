# Libros Electrónicos

## REGLAS GENERALES DE LA INFORMACIÓN DE LOS LIBROS Y REGISTROS ELECTRÓNICOS		

El Programa de Libros Electrónicos - PLE valida los libros y registros generados por el contribuyente en archivos en formato de texto, con la estructura que se indica en las siguientes hojas y cuyos campos deben estar separados por el caracter "\|" (conocido como pipe o palote). Adicionalmente, dichos archivos deben ser generados con los nombres que se detallan en la hoja "Libros Tributarios".

| N°|Aspecto solicitado|Regla|
|--|--|--|
|1|Monto negativo|Consignar el formato  "- #.##"|
|2|Texto|Texto libre entre palotes. No debe contener los caracteres: \|, /, &#92;|
|3|Alfanumerico|Letras en mayusculas y minusculas (de la A a la Z) y los caracteres especiales ( ) , . \-|
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

<pre>
LO Longitud	
T	 Tipo	
   A: Alfanumérico (Solo letras y números)	
   N: Numérico	
L  Tipo de longitud	
   F: Fija	
   V: Variable	
M  Módulo 11	
   M: Aplica	
   - : No aplica	
</pre>

## ANEXO 2: ESTRUCTURAS E INFORMACIÓN DE LOS LIBROS Y/O REGISTROS ELECTRÓNICOS

* [Reglas generales de los comprobantes de pago](reglas_comprobantes.csv)
* [Estructura del nombre del archivo](libros_nombre.csv)
* [Lista de Libros Electrónicos](libros_lista.csv)

  * (1) Se detalla lo que significa cada parte de la estructura del nombre
  * (2) Podrán ser elaborados sin consignar información, siempre que cuente con la referida información con la estructura establecida en otro libro y/o registro llevado de manera electrónica y sea presentado cuando le sea requerido por la SUNAT
  * (3) Este libro deberá registrarse en formato pdf. Su información y contenido debe estar de acuerdo a la normatividad señalada por la Superintendencia del Mercado de Valores - SMV

## Estructura de los Libros Electrónicos

* [1.1 - LIBRO CAJA Y BANCOS - DETALLE DE LOS MOVIMIENTOS DEL EFECTIVO](010100.csv)
* [1.2 - LIBRO CAJA Y BANCOS - DETALLE DE LOS MOVIMIENTOS DE LA CUENTA CORRIENTE](010200.csv)


* [3.1 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE SITUACIÓN FINANCIERA](030100.csv)
  * Resolución Gerencia General N° 044-2007-EF/94.11
* [3.2 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 10 EFECTIVO Y EQUIVALENTES DE EFECTIVO](030200.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.3 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 12 CUENTAS POR COBRAR COMERCIALES – TERCEROS Y 13 CUENTAS POR COBRAR COMERCIALES – RELACIONADAS](030300.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.4 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO  DE LA CUENTA 14 CUENTAS POR COBRAR AL PERSONAL, A LOS ACCIONISTAS (SOCIOS), DIRECTORES Y GERENTES](030400.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.5 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO  DE LA CUENTA 16 CUENTAS POR COBRAR DIVERSAS - TERCEROS O CUENTA 17 - CUENTAS POR COBRAR DIVERSAS - RELACIONADAS](030500.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.6 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 19 ESTIMACIÓN DE CUENTAS DE COBRANZA DUDOSA](030600.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.7 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 20 - MERCADERIAS Y LA CUENTA 21 - PRODUCTOS TERMINADOS](030700.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.8 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 30 INVERSIONES MOBILIARIAS](030800.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.9 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 34 - INTANGIBLES](030900.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.11 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 41 REMUNERACIONES Y PARTICIPACIONES POR PAGAR](031100.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.12 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 42 CUENTAS POR PAGAR COMERCIALES – TERCEROS Y LA CUENTA 43 CUENTAS POR PAGAR COMERCIALES – RELACIONADAS](031200.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.13 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 46 CUENTAS POR PAGAR DIVERSAS – TERCEROS Y DE LA CUENTA 47 CUENTAS POR PAGAR DIVERSAS – RELACIONADAS](031300.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.14 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 47 - BENEFICIOS SOCIALES DE LOS TRABAJADORES (PCGR) - NO APLICABLE PARA EL PCGE](031400.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.15 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 37 ACTIVO DIFERIDO Y DE LA CUENTA 49 PASIVO DIFERIDO](031500.csv)
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* 3.16 - LIBRO DE INVENTARIOS Y BALANCES - DETALLE DEL SALDO DE LA CUENTA 50 CAPITAL
  * Los deudores tributarios que lleven su contabilidad de acuerdo  a un plan contable distinto al Plan Contable General Empresarial (PCGE) deberán adecuar la información equivalente.
* [3.16.1 - DETALLE DEL SALDO DE LA CUENTA 50 - CAPITAL](031601.csv)
* [3.16.2 - ESTRUCTURA DE LA PARTICIPACIÓN ACCIONARIA O DE PARTICIPACIONES SOCIALES](031602.csv)
* [3.17 - LIBRO DE INVENTARIOS Y BALANCES - BALANCE DE COMPROBACIÓN](031700.csv)
  * Las cifras deben ser presentadas a valores históricos.
* [3.18 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE FLUJOS DE EFECTIVO - MÉTODO DIRECTO](031800.csv)
* [3.19 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE CAMBIOS EN EL PATRIMONIO NETO](031900.csv)
* [3.20 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE RESULTADOS](032000.csv)
* 3.23 - LIBRO DE INVENTARIOS Y BALANCES - NOTAS A LOS ESTADOS FINANCIEROS
  * Este libro deberá registrarse en formato pdf. Su información y contenido debe estar de acuerdo a la normatividad señalada por la Superintendencia del Mercado de Valores - SMV (ex CONASEV)
* [3.24 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE RESULTADOS INTEGRALES](032400.csv)
* [3.25 - LIBRO DE INVENTARIOS Y BALANCES - ESTADO DE FLUJOS DE EFECTIVO - MÉTODO INDIRECTO](032500.csv)



* [4.1 - LIBRO DE RETENCIONES INCISO E) Y F) DEL ART. 34° DE LA LEY DEL IMPUESTO A LA RENTA](040100.csv)


* [5.1 - LIBRO DIARIO](050100.csv)
  * En caso el contribuyente se exima de llevar el Libro Caja y Bancos electrónico por llevar el presente libro, deberá completar la información en los campos de libre utilización (22 al 44), de corresponder.
* [5.3 - LIBRO DIARIO - DETALLE DEL PLAN CONTABLE UTILIZADO](050300.csv)
  * Obligatorio en el periodo de enero cada año o cuando se genera el libro electrónico por primera vez. En los demás meses se puede optar por generar un libro vacio salvo que el Plan Contable sufra modificaciones. 
* [5.2 - LIBRO DIARIO DE FORMATO SIMPLIFICADO](050200.csv)
* [5.4 - LIBRO DIARIO DE FORMATO SIMPLIFICADO - DETALLE DEL PLAN CONTABLE UTILIZADO](050400.csv)
  * Obligatorio en el periodo de enero cada año o cuando se genera el libro electrónico por primera vez. En los demás meses se puede optar por generar un libro vacio salvo que el Plan Contable sufra modificaciones.


* [6.1 - LIBRO MAYOR](060100.csv)


* [7.1 - REGISTRO DE ACTIVOS FIJOS - DETALLE DE LOS ACTIVOS FIJOS REVALUADOS Y NO REVALUADOS](070100.csv)
  * El Catálogo de Naciones Unidas es el mismo que se hace referencia en la Tabla 13 "Catálogo de Existencias".
* [7.3 - REGISTRO DE ACTIVOS FIJOS - DETALLE DE LA DIFERENCIA DE CAMBIO](070300.csv)
* [7.4 - REGISTRO DE ACTIVOS FIJOS - DETALLE DE LOS ACTIVOS FIJOS BAJO LA MODALIDAD DE ARRENDAMIENTO FINANCIERO AL 31.12](070400.csv)


* [8.1 - REGISTRO DE COMPRAS](080100.csv)
  * (1) Señalar la fecha correspondiente, de acuerdo a lo establecido en el literal b) del inciso II del numeral 1 del Artículo 10° del Reglamento de la Ley del Impuesto General a las Ventas e Impuesto Selectivo al Consumo, aprobado por Decreto Supremo N.° 029-94-EF, publicado el 29.3.1994 y normas modificatorias.
  * (2) En caso la anotación corresponda a un ajuste respecto de operaciones registradas antes del 10/07/2011 y siempre que por las mencionadas operaciones se lleve un sistema de control computarizado que mantenga la información detallada y que permita efectuar la verificación individual de cada documento.
  * (3) Utilizado conforme lo dispuesto en las normas sobre la materia.
  * (4) El  monto ajustado de la base imponible y/o del impuesto o valor, según corresponda, señalado en las notas de crédito, se consignará en las columnas utilizadas para registrar los datos vinculados a las adquisiciones gravadas destinadas a operaciones gravadas y/o de exportación; adquisiciones gravadas destinadas a operaciones gravadas y/o de exportación y a operaciones no gravadas y adquisiciones gravadas destinadas a operaciones no gravadas. El monto de la base imponible y/o impuesto o valor, según corresponda, señalados en las notas de débito, se consignará en las columnas indicadas en el párrafo anterior.
  * (5) Sólo para los casos de detracciones. Es optativo el llenado cuando exista un sistema de enlace que mantenga dicha información y se pueda identificar los comprobantes de pago respecto de los cuales se efectuó el depósito.
* [8.2 - REGISTRO DE COMPRAS - INFORMACIÓN DE OPERACIONES CON SUJETOS NO DOMICILIADOS](080200.csv)
* [8.3 - REGISTRO DE COMPRAS SIMPLIFICADO](080300.csv)


* [9.1 - REGISTRO DE CONSIGNACIONES - PARA EL CONSIGNADOR - CONTROL DE BIENES ENTREGADOS EN CONSIGNACIÓN](090100.csv)
* [9.2 - REGISTRO DE CONSIGNACIONES - PARA EL CONSIGNATARIO - CONTROL DE BIENES RECIBIDOS EN CONSIGNACIÓN](090200.csv)
  * (1) Una vez perfeccionada la venta de bienes por parte del consignatario; en este caso, deberá anotarse en los campos 9 y 10 , la serie y el número de la guía de remisión con la que se emitieron los referidos bienes al consignatario
  * (2) Deberá anotarse en los campos 9 y 10 la serie y el número de la guia de remisión con la que recibió los referidos bienes del consignador


* [10.1 - REGISTRO DE COSTOS - ESTADO DE COSTO DE VENTAS ANUAL](100100.csv)
* [10.2 - REGISTRO DE COSTOS - ELEMENTOS DEL COSTO MENSUAL](100200.csv)
* [10.3 - REGISTRO DE COSTOS - ESTADO DE COSTO DE PRODUCCION VALORIZADO ANUAL](100300.csv)
* [10.4 - REGISTRO DE COSTOS - CENTRO DE COSTOS](100400.csv)


* [12.1 - REGISTRO DEL INVENTARIO PERMANENTE EN UNIDADES FÍSICAS - DETALLE DEL INVENTARIO PERMANENTE EN UNIDADES FÍSICAS](120100.csv)
  * El Catálogo de Naciones Unidas es el mismo que se hace referencia en la Tabla 13 "Catálogo de Existencias".


* [13.1 - REGISTRO DEL INVENTARIO PERMANENTE VALORIZADO - DETALLE DEL INVENTARIO VALORIZADO](130100.csv)


* [14.1 - REGISTRO DE VENTAS E INGRESOS](140100.csv)
  * (1) En los casos de comprobantes de pago emitidos por empresas de servicios públicos.						
  * (2) También podrá efectuarse la anotación de manera consolidada cuando ésta corresponda a alguna de las situaciones previstas en el inciso e) del artículo 8 de la Resolución de Superintendencia N.° 286-2009/SUNAT respecto de operaciones registradas antes del 10/07/2011 por las que se emitieron comprobantes de pago que no otorgan derecho a crédito fiscal diferentes a los tickets o cintas emitidos por máquinas registradoras y siempre que por las mencionadas operaciones se lleve un sistema de control computarizado que mantenga la información detallada y que permita efectuar la verificación individual de cada documento. En el caso de las boletas de venta de acuerdo al numeral 3.10 del art. 8 del Reglamento de Comprobantes de Pago, a partir del 1 de julio de 2016, se deberá registrar de manera cuando el monto total sea igual o mayor a S/ 700.00.
  * (3) Utilizado conforme a lo dispuesto en las normas sobre la materia.						
  * (4) En caso de ser una operación gravada con el Impuesto selectivo al Consumo (ISC), no debe incluir el monto de dicho impuesto. 						
  * (5) Utilizado conforme lo dispuesto en las normas sobre la materia.						
  * (6) El monto ajustado de la base imponible y/o del impuesto o valor, según corresponda, señalado en las notas de crédito, se consignará respectivamente, en las columnas utilizadas para registrar los datos vinculados a  las adquisiciones  gravadas destinadas a  operaciones gravadas y/o  de  exportación; adquisiciones gravadas destinadas a  operaciones gravadas y/o  de exportación y a operaciones no gravadas y adquisiciones gravadas destinadas a operaciones no gravadas. El monto de la base imponible y/o impuesto o valor, según corresponda, señalados en las notas de débito, se consignarán respectivamente en las columnas indicadas en el párrafo anterior.
* [14.2 - REGISTRO DE VENTAS E INGRESOS SIMPLIFICADO](140200.csv)
