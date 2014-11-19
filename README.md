datetime-strategy
=================

ZF2 DateTime Strategy para lidar com objetos datetime em formulários.

Por padrão, o DoctrineHydrator tenta recriar os objetos DateTime, porém quando se passa as datas em um formato diferente de Y-m-d é disparada uma exceção na construção do objeto. Com esse Hydrator você poderá especificar qual formato de data você deseja utilizar
