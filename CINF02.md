
<img src="https://github.com/lualopezpe/sas/blob/master/sas.png">

## CINF02- COSMOS

_Actividad evaluativa transferencia de conocimiento CINF02-COSMOS_

**Responda las preguntas `1` y `2` con base en el `Snippet 1`.**

#### Snippet 1


```sas
libname lcata XLSX 
"/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx";

proc contents data=lcata._all_ nods;
run;
```

    SAS Connection established. Subprocess id is 2724
<style>
  .markdown-body table td {
    font-size: 12px !important;
  }
</style>
<table class="table" style="border-spacing: 0" aria-label="Directory Information">
<caption aria-label="Directory Information"></caption>
<colgroup><col/><col/></colgroup>
<thead>
<tr>
<th class="c b header" colspan="2" scope="colgroup">Directory</th>
</tr>
</thead>
<tbody>
<tr>
<th class="rowheader" scope="row">Libref</th>
<td class="data">LCATA</td>
</tr>
<tr>
<th class="rowheader" scope="row">Engine</th>
<td class="data">XLSX</td>
</tr>
<tr>
<th class="rowheader" scope="row">Physical Name</th>
<td class="data">/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx</td>
</tr>
<tr>
<th class="rowheader" scope="row">Por</th>
<td class="data">.</td>
</tr>
</tbody>
</table>
</div>
<div id="IDX1" style="padding-bottom: 8px; padding-top: 1px">
<table class="table" style="border-spacing: 0" aria-label="Library Members">
<caption aria-label="Library Members"></caption>
<colgroup><col/></colgroup><colgroup><col/><col/><col/></colgroup>
<thead>
<tr>
<th class="r b header" scope="col">#</th>
<th class="b header" scope="col">Name</th>
<th class="b header" scope="col">Member Type</th>
<th class="b header" scope="col">DBMSTYPE</th>
</tr>
</thead>
<tbody>
<tr>
<th class="r rowheader" scope="row">1</th>
<td class="data">APLICACION_SAP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">2</th>
<td class="data">CALIFICACION_EXTERNA_COMERCIAL</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">3</th>
<td class="data">CALIFICACION_EXTERNA_CONSUMO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">4</th>
<td class="data">CALIFICACION_EXTERNA_MICRO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">5</th>
<td class="data">CALIFICACION_EXTERNA_VIVIENDA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">6</th>
<td class="data">CALIFICACION_INTERNA_COMERCIAL</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">7</th>
<td class="data">CALIFICACION_INTERNA_CONSUMO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">8</th>
<td class="data">CALIFICACION_INTERNA_MICRO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">9</th>
<td class="data">CALIFICACION_INTERNA_VIVIENDA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">10</th>
<td class="data">CARTERA_CON_REV_1000</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">11</th>
<td class="data">CLIENTE_FORANEO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">12</th>
<td class="data">COLGAAP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">13</th>
<td class="data">CONTROL_VERSION</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">14</th>
<td class="data">ENTIDAD_RELACIONADA</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">15</th>
<td class="data">FORMATO110</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">16</th>
<td class="data">HOMOLOGACION_SAP_PRODUCTO</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">17</th>
<td class="data">MODALIDAD</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">18</th>
<td class="data">MODALIDAD_EMP</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">19</th>
<td class="data">PLANES EMPLEADOS</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
<tr>
<th class="r rowheader" scope="row">20</th>
<td class="data">PROVISION_CON_REV_1000</td>
<td class="data">DATA</td>
<td class="data">TABLE</td>
</tr>
</tbody>
</table>
</div>
</div>
</body>
</html>

**Pregunta 1.** ¿Cuál es la ventaja de usar `libname XLSX` para la carga de los Catálogos Contables? <br><br>
a) Permite acceder los archivos _xlsx_ directamente y trabajar con ellos como si fueran tablas _SAS_. <br>
b) Es un motor que utiliza componente de Microsoft para la carga del _xlsx_. <br>
c) No ofrece ninguna ventaja sobre alternativas como `libname EXCEL` ó `libname PCFILES`. <br>
d) Para la carga de los Catálogos Contables no se emplea `libname XLSX`. 

**Pregunta 2.** En caso de que se requiera ejecutar nuevamente el código anterior ¿Qué sucede si uno de los nombres de las hojas de Excel contiene espacios? <br><br>
a) Falla. Puesto que el nombre de la hoja de _EXCEL_ contiene espacios y el nombre de la tabla SAS resultante no es válido. <br>
b) No falla. En la tabla de resultado resultado aparece la hoja _EXCEL_ aún con espacios. Pero, en caso de intentar acceder a la tabla SAS correspondiente se produce un `error` por no ser un nombre SAS válido. <br>

**Responda la pregunta `3` con base en el `Snippet 2`.**

#### Snippet 2


```sas
libname lcata XLSX ("/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Contabilidad.xlsx" 
                    "/folders/myfolders/catalogos/Catalogos_Bancolombia_IFRS9_Cuentasconta.xlsx"
                    );
```

**Pregunta 3.** ¿Qué se puede afirmar con respecto del _Snippet 2_? <br><br>
a) Falla. Contiene un error de sintaxis. <br>
b) No falla pero solo asigna a `lcata` las hojas del primer archivo `EXCEL`. <br>
c) No falla y asigna a `lcata` las hojas de ambos archivos `EXCEL`. <br>
d) El `libname XLSX` no soporta múltiples archivos asignados a un mismo `libref`. <br>

**Pregunta 4.** ¿Cuál de los siguientes no hace parte del flujo de los procesos Contables? <br> <br>
a) Interfaz Contable <br> 
b) Controles Reportes <br>
c) Revelaciones <br>
d) Generación Resultado Final

**Pregunta 5.** ¿Cuál es el objetivo del Control Saldos _Base Final_? <br> <br>
a) Verificar que los saldos anteriores de la _base final_ actual sean consistentes con los saldos actuales de la _base final_ anterior <br>
b) Validar que obligaciones tienen saldos $>= 0$ y verifica que se hayan asignado cuentas.<br>
c) Agrupar saldos por cuenta contable.<br>
d) Verificar inconsistencia en cuentas, es decir, identificar cuentas asignadas como `INVALIDAS`.<br>

**Responda las pregunta `6` con base en el `Snippet 3`.**

#### Snippet 3


```sas
/*Concepto Interes */
if( Saldo_Int_Cte_Total NE . ) then 
    do;
        llave_CALIFICACION=catx('#',PUT((Codigo_Clase),$FClasificacion.), Modalidad, Calificacion_Externa,"INTERES",codigo_moneda_aux );
        cuenta=putC(upcase(llave_CALIFICACION),formato);
        CodContCUIFInteresCALIF=TRIM(cuenta);
    end;
```

 Obligacion | Saldo_Int_Cte_Total | CodContCUIFInteresCALIF
-----|---------------------|------------------------
 a   |        0            |      INVALIDA
 s   |        8            |      1410058216
 d   |        -1           |      1410058216
 f   |        0            |      1410058216
 z   |        .            |      INVALIDA

Supongase que se tiene un grupo de obligaciones para las que se requiere calcular el campo `CodContCUIFInteresCALIF` y cuyos saldos se muestran en la tabla anterior. Ahora bien, considere las siguientes afirmaciones: <br><br>
I.   Existe un error de inconsistencia en cuenta en la obligación `z`.<br>
II.  La asignación de cuentas de la tabla no corresponde a la aplicada en el `Snippet 3` puesto que la obligación `z` tiene saldo `missing`.<br>
III. La inconsistencia en `CodContCUIFInteresCALIF` para la obligación `z` **no** aparece en el informe de inconsistencia en cuenta.<br>
IV.  La asignación de cuenta de la obligación `a` es una inconsistencia en cuenta.<br>


**Pregunta 6.** De las afirmaciones anteriores se puede decir que <br> <br>
a) I y I son verdaderas. <br>
b) II, III, IV son verdaderas.<br>
c) Todas son ciertas.<br>
d) II y IV son verdaderas.<br>

**Responda las preguntas `7` con base en el `Snippet 4`.**

##### Snippet 4


```sas
DATA Modalidad_;
    SET LCATA.MODALIDAD (keep=Codigo_Producto Descripcion Rename=(Codigo_Producto=Codig ));
    Codigo = PUT(Codig, 2.);
    DROP Codig;
RUN;

DATA WORK._EG_CFMT;
    LENGTH label $ 50;
    SET Modalidad_ (KEEP=Codigo Descripcion RENAME=(Codigo= start Descripcion=label)) END=__last;
    RETAIN fmtname "FModalidad" type "C";
    end=start;
    OUTPUT;
    IF __last = 1 THEN
        DO;
            hlo = "O";
            label = "CARTERA DE CREDITOS";
            OUTPUT;
    END;
RUN;
```


```sas
proc format library=work ctrlin = _EG_CFMT;
run;
```

Codigo_Producto | Descripcion
----------------|---------------
6	            | VIVIENDA VIS
7	            | VIVIENDA NO VIS
18	            | LEASING HABITACIONAL
19	            | LEASING FINANCIERO
21	            | LEASING FINANCIERO
20	            | CÁNONES DE BIENES DADOS EN LEASING OPERACIONAL


**Pregunta 7.** En el `Snippet 4` se muestra la creación de un formato personalizado utilizando un `PROC FORMAT`. También se muestra la tabla `SAS` con la que se genera el formato. Teniendo en cuenta la información anterior y el seguiente `DATA STEP` es correcto afirmar:


```sas
data test1;
    test1 = put(3, $FModalidad.);
run;

proc print data=test1; run;
```

a) Imprime `INVALIDA`<br>
b) Imprime `CARTERA DE CREDITOS`<br>
c) Imprime `VIVIENDA VIS`<br>
d) Error, no encuentra `FMODALIDAD`.

**Responda la pregunta `8` con base en el `Snippet 5`.**

#### Snippet 5

`Saldos Acumulados` <br>
El reporte saldos acumulados, tiene como objetivo agrupar los saldos por cuentas contables y conceptos, para facilitar al usuario la conciliación.



```sas
/*Asignación de cuentas*/
if( saldo_n NE . ) then 
    do;
        /*
        Se forma llave y se calcula cuenta_n
        */
    end;
```

`Base Final`

| obligacion | cuenta1 | cuenta2  | cuenta3 | saldo1 | saldo2 | saldo3 |
|------------|-------- |----------|---------|--------|--------|--------|
|     1      | 161214  |          | 410051  |    0   |        |   100  |
|     2      | 143122  |  192121  |         |    0   |   -150 |        |
|     3      | 818189  |          |         |    250 |        |        |
|     4      | 161214  |          | 410051  |    250 |        |   -50  |
|     5      | 143122  |  192121  |         |    0   |   -150 |        |

**Pregunta 8.** Teniendo en cuenta la información del `Snippet 5`, el valor del saldo para la cuenta `161214` en el reporte de saldos acumulados es <br><br>
a) 0 <br>
b) 500 <br>
c) 250 <br>
d) 200 <br>


**Pregunta 9.** ¿Qué validación se hace para asignar cuenta? <br> <br>
a) Saldo actual $>= 0$ <br>
b) Saldo anterior $>= 0$ <br>
c) Saldo actual $\not = missing$ ó Saldo anterior $\not = missing$ <br>
d) Saldo actual $> 0$ ó Saldo anterior $> 0$ <br>

**Pregunta 10.** ¿Cuál es el directorio donde se alojan los reportes `XLSX` generados en Controles Reportes? <br> <br> 
a) SAS_Salidas <br>
b) SAS_DataMart <br>
c) SAS_Controles_Reportes <br>
d) SAS_Catalogos

**Pregunta 11.** ¿Dónde se encuentra parametrizado el cuerpo y asunto del correo de notificaciones para Controles Reportes? <br> <br>
a) Parámetros Notificaciones <br>
b) Catálogo Emails <br>
c) Notificaciones Controles Reportes <br>
d) Parámetros Controles Reportes <br>

**Pregunta 12.** ¿Qué tabla se debe revisar si se requiere ajustar el correo o lista distribución a la que se envian las notificaciones de Controles Reportes?<br> <br>
a) Parámetros Notificaciones<br>
b) Catálogo Emails<br>
c) Notificaciones Controles Reportes<br>
d) Parámetros Controles Reportes<br>

**Pregunta 13.** ¿Cuál es el objetivo del Reporte Balance Comparativo y Delta?<br><br>
a) Contiene las Cuentas de Ajuste para la _Interfaz Contable_.<br>
b) Facilitar la Conciliación de Saldos Acumulados. <br>
c) Informar los saldos de SAS por cuentas contables y el valor del Delta.<br>
d) Garantizar la consistenia de la _Interfaz Contable_. <br>

**Pregunta 14.** ¿Qué control tiene como objetivo verificar que todas las obligaciones que posean saldo en cada uno de los conceptos (Capital, Intereses, Cuentas por Cobrar y/o Otros Conceptos) tenga asociada una calificación? <br><br>
a) Inconsistencia en Cuentas <br>
b) Error Calificación <br>
c) Saldos Acumulados <br>
d) Intereses Bucket 3 <br>


**Pregunta 15.** Si se desea ampliar el plazo del día límite de espera del archivo ERP del balance SAP para que sea efectivo en la ejecución del proceso de `Cargar Balance`, ¿cuál es la tabla que contiene el parámetro a ser ajustado? <br> <br>
a) Parametros Generales<br>
b) Parametros Switch<br>
c) Parametros Notificaciones<br>
d) Parametros Contables<br>

**Pregunta 16.** En el proceso de generación de la _Base Final_ se hace válidación de registros duplicados?<br><br>
a) Si, en Generales Calificación hay una macro que verifica la existencia de registros duplicados en el insumo de Resultado Final.<br>
b) No, no es necesario hacer validación de registros duplicados puesto que desde Perdida Esperada garantizan la consistencia de ls datos. <br>

**Responda la pregunta `17` con base en el `Snippet 6`.**

#### Snippet 6
ERROR: El archivo LIB_BCO.BCO_SEGMENTO_GENERALES_31JAN2018.DATA no existe.
**Pregunta 17.** La causa más probable para que en la ejecución de la malla contable se presente un error como el que aprece en el Snippet 6 es <br><br>
a) No se ejecutó el orden adecuado la generación de la Base Final.<br>
b) No se generó el insumo `LIB_BCO.BSP_SEGMENTO_GENERALES_31JAN2018.DATA` desde PE.<br>
c) No se hizo una adecuada segmentación en los formatos de revelaciones. <br>
d) No es un error que se presente en el flujo de la malla contable. <br>

**Pregunta 18.** ¿Cuál es el orden correcto de ejcución de la _Base Final_? <br><br>
a) Resultado Final - Generales Calificación - Saldos Bucket 3 - Saldos Cuentas Temp Calif - Cuentas Provision - Provision Prorrateo - Base Final <br>
b) Base Cero - Saldos Bucket 3 - Saldos Cuentas  Temp Calif - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
c) Generales Calificación - Saldos Bucket 3 - Saldos Cuentas  Temp Calif - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
d) Generales Calificación - Saldos Cuentas  Temp Calif - Saldos Bucket 3 - Provisión Prorrateo - Cuentas Provisión - Base Final <br>
