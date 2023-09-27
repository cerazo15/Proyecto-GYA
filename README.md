# Proyecto-GYA
Proyecto Final de Gestion y Almacenamiento de Datos
# Cuál es su problemática
El objetivo principal del proyecto es realizar un diagnóstico del desempeño de las ventas y compras de una tienda pequeña, además de variables claves que le permitan al negocio tomar decisiones acertadas
# Que se encuentra en su repositorio
En el repositorio encontraremos:
 - Dataframe de las ventas y compras por día (data_ventas.csv y data_compras.csv) 
 - Análisis de los datos y gráficos (Proyecto_mi_market.ipynb)
 - Manejo de base de datos en Python con sqlite3 (sql_Proyecto_GYA.ipynb)
 - Query demostrativo del manejo de la base de datos 
# Los datos
Se tienen los registros diarios de las ventas y compras por producto desde julio de 2021 a febrero de 2023 los cuales reposaban en libros contables que el tendero diligenciaba diariamente. Estos datos se pasaron a formato digital (excel), obteniendo una tabla con las siguientes características:
  Cantidad de registros ventas: 4394
  Atributos:
   - Fecha
   - Año
   - Mes
   - Dia_semana
   - Semana
   - Producto
   - Presentacion
   - Tipo_producto
   - Cantidad
   - Precio
   - Venta_total
   Cantidad de registros compras: 770
   Atributos
   - Fecha Solicitud
   - Fecha Entrega  
   - Año                    
   - Semana                  
   - Status                 
   - Proveedor              
   - Tipo Producto          
   - Desc Producto          
   - Presentacion          
   - Cant. Comprada        
   - Cant. Prom           
   - Cantidad Total         
   - Costo Total        
   - Vr Unitario        
   - Precio de Venta
   - Margen % 
# Aporte al negocio
Con este análisis el negocio pudo:
 - Obtener un status de la evolución de sus ventas y compras
 - Conocer los productos (categorías) que mayor venta generan
# Análisis futuros
El análisis anterior obedece al alcance del proyecto que estaba dado por el tiempo del mismo, sin embargo, al tener los datos de manera digital, y con el detalle que actualmente presentan, permite realizar diversos análisis que le permitan al negocio, entre otros:
 - Generar pedidos de manera óptima
 - Evaluar el portafolio más rentable
