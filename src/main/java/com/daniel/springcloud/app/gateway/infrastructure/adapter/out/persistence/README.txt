Aquí se tienen las carpetas de entity, mapper y repository, además se tienen las clases que implementan los contratos de acceso a datos que están en
domain/port/out

En entity, van las clases entity que mapean las tablas o colecciones donde se guadaran los modelos de datos del sistema
En mapper, van las clases que convierten de entity a modelo y de modelo a entity
En repository, van las interfaces por cada entity donde se extiende de JPA, CRUD o Mongo Repository, via directa a la persistencia de datos