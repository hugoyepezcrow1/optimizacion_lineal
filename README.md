# optimizacion_lineal
Problema de Distribución y Transporte. Hoy en día, la fabricación global se está desarrollando rápidamente. Con este rápido desarrollo, la competencia entre las empresas manufactureras se vuelve más severa. La fabricación de productos, el envío de productos a almacenes y la entrega de productos a los clientes es muy difícil hoy en día. Por lo tanto, cada empresa está buscando un sistema logístico para equilibrar la cadena de suministro general de la empresa. Decidir las ubicaciones de los centros de distribución es la parte más difícil en la gestión de la cadena de suministro porque las ubicaciones ineficientes resultarán en un costo excesivo. Por lo tanto, la gerencia debe reconocer las condiciones futuras al tomar decisiones sobre la ubicación de las instalaciones. El diseño del sistema de distribución de productos múltiples es una generalización de un problema de ubicación de instalaciones donde tenemos varios productos y el envío de varias plantas a bodegas y de las bodegas al cliente. El trabajo ha realizarse es emplear el software GUROBI/AMPL, a fin de dar solución al problema presentado en la cadena de suministros.
Una determinada empresa forestal puede producir L productos distintos y tiene I plantas
productivas ubicadas en diferentes zonas, conocida la capacidad de total de producción de
cada planta en cada periodo sin importar de qué tipo de producto se trate. Cada tipo de
producto tiene un costo de producción sin importar la planta en que se fabrique ni el periodo
en cuestión. Los productos son demandados por J ciudades diferentes, y se conoce la
demanda de la ciudad por cada producto en cada periodo. Las demandas deben ser
satisfechas periodo a periodo. Como no existe la posibilidad de almacenar producto en las
plantas, la empresa esta estudiando la posibilidad de arrendar bodegas ubicadas en
diferentes puntos geográficos. El arriendo de las bodegas se hace periodo a periodo, esto
quiere decir que si se arrienda una bodega en un periodo no necesariamente la bodega
debe haber estado arrendada en el periodo anterior o seguir arrendada para el periodo
siguiente. Hay K posibles bodegas para arrendar.
De esta manera, la producción de las plantas se llevará a las bodegas y desde allí se
abastecerá a las ciudades. No existe inventario, las bodegas solo se utilizan para etiquetar
los distintos artículos. Si se arrienda la bodega se incurre en un gasto fijo en pesos
colombianos por el pago de arriendo en cada periodo. Pero si se arrienda una bodega por
3 o más períodos consecutivos se recibirá un reembolso en pesos. Por cada unidad de cada
artículo que ingresa a una bodega se conoce el gasto en pesos por concepto de
etiquetación, la capacidad de cada bodega es conocida en unidades de producto sin
importar su tipo.
Además, se sabe que cada ciudad debe ser abastecida desde una única bodega en cada
período y también la cantidad que cada bodega puede despachar como mínimo y como
máximo al total de ciudades que abastezca (de unidades de artículos, o sea, del total de
artículos que despacha). Si una bodega despacha mas de esa cota superior establecida de
unidades de producto, se le debe pagar un bono extra a los empleados de esa bodega en
pesos, independiente de la magnitud del exceso (pero difiere por bodega).
Se conoce el costo unitario de transporte de cada tipo de producto desde cada planta a
cada bodega en cada periodo en pesos y el costo unitario en transporte desde cada bodega
a cada ciudad a cada tipo de producto en cada periodo en pesos.
a. Plantee el modelo de Programación Lineal Mixto que permita determinar qué bodegas
deben arrendarse para que el costo de producción, transporte, arriendo y
almacenamiento sea mínimo.
b. Adapte el modelo anterior cuando se tiene un solo tipo de producto y un solo periodo.
c. Genere datos razonables (justifique como lo hizo) para resolver el modelo del inciso b.
