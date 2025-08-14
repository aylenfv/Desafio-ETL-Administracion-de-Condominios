# Desafio-ETL-Administracion-de-Condominios
Desafío 2 del curso "Pandas: transformación y manipulación de datos" de Alura Latam.

## Objetivo
Administrar condominios es una tarea que requiere mucha atención y organización. Entre las diversas responsabilidades de gestión se encuentra el cobro del alquiler a los inquilinos. Para garantizar la buena salud financiera de la empresa, es fundamental que estos pagos se realicen de forma regular y puntual. Sin embargo, sabemos que esto no siempre sucede.

Teniendo esto en cuenta, propongo un desafío de procesamiento de datos con el objetivo de analizar el retraso en el pago del alquiler en el condominio de algunos residentes. Pongo a disposición la base de datos datos_inmuebles.json, que contiene información sobre el departamento de los inquilinos, el día acordado para el pago del alquiler, el día en que se realiza el pago del alquiler y el monto del alquiler.

## Etapa 1

Con esta información, el desafío del proyecto 2: administración del condominio será similar al desafío del proyecto 1, abrir la base de datos con Pandas y aplicar json_normalize al DataFrame.

## Etapa 2

Leímos la base de datos en el desafío anterior, ahora podemos seguir adelante con la transformación de estos datos. Entonces, de la misma manera que en el proyecto 1, el desafío del proyecto 2 está listado en algunas metas:

Eliminar datos en listas dentro del DataFrame;
Verificar tipos de datos;
Identificar columnas numéricas;
Transformar la columna numérica a tipo numérico.

## Etapa 3

En el paso 2, trabajamos en transformar los datos numéricos. Ahora podemos trabajar con valores textuales.

Buscando explicar la organización de la identificación de los apartamentos, durante la creación del conjunto de datos se añadió el texto (blocoAP). Este texto informa que los nombres de los apartamentos están organizados con la letra mayúscula seguida del número del apartamento. Sin embargo, esto no aporta ninguna información a nuestros datos, por lo que resulta interesante eliminar este texto del conjunto de datos.

Con esto, manipular los textos de la columna apartamento para eliminar el texto (blocoAP) del DataFrame.

## Etapa 4

Al igual que en el Proyecto Desafío 1, trabajamos con todas las columnas excepto las que involucran fechas.

En las columnas datas_de_pagamento y datas_combinadas_pagamento tenemos fechas en el formato 'día/mes/año' (dd/mm/AAAA). Transforme estos datos al tipo datetime y busque una forma de visualización de subconjunto que pueda contribuir al objetivo del contexto en el que se insertan los datos.
