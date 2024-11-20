
# Actores
## Cliente
Descripcion: Puede reservar o alquilar peliculas
## Proveedor
Descripcion: Abastece las peliculas al administrador
## Administrador VIDEOMAX
Descripcion: Registra datos neceasrios de peliculas, clientes y compras
# Casos de uso por actores
## Cliente
i. Proporciona datos personales

ii. Alquila Pelicula

iii. Reserva Pelicula
## Proveedor
i. Abastece Peliculas segun existencia
## Administrador VIDEOMAX
i. Registra a los clientes mediante sus datos personales

ii. Registra el alquiler de las peliculas

iii. Registra la reserva de las peliculas

iv. Registra la pelicula al ser abastecida

v. Actualiza al Proveedor
### Actores
#### Cliente
|  Actor |  Cliente |
|---|---|
| Descripción  | _Cliente de la tienda_  |
| Características  |_Consume productos de la tienda_ |
| Relaciones | __  |
| Referencias | _Proporciona datos personales, Alquila pelicula, Reserva Pelicula, Seleccionar pelicula, Devolver pelicula_ |   
|  Notas |  __ |
| Autor  | _Emanuel santamaria_ |
|Fecha | _19/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
#### Administrador VIDEOMAX
|  Actor | Administrador VIDEOMAX |
|---|---|
| Descripción  | _Administrador del local_  |
| Características  |_Administra el local_ |
| Relaciones | __  |
| Referencias | _Registra a los clientes, Registra Alquiler, Registra reserva, Registra Pelicula, Actualiza Proovedor_ |   
|  Notas |  __ |
| Autor  | _Emanuel Santamaria_ |
|Fecha | _19/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
#### Proovedor
|  Actor | Proovedor |
|---|---|
| Descripción  | _Abastece la tienda de peliculas_  |
| Características  |_Abastece pelicullas_ |
| Relaciones | __  |
| Referencias | _Abastece peliculas segun existencia_ |   
|  Notas |  __ |
| Autor  | _Emanuel Santamaria_ |
|Fecha | _19/11/2024_ |

|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

### Casos de uso
#### Proporciona datos
|  Caso de Uso	CU | Proporciona datos |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Cliente_ |
  | Descripción | _El cliente puede proporcionar datos personales al Administrador_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Estar dentro de la  tienda_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | _Debe estar de acuerdo con las normas y condiciones_  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Alquilar pelicula
|  Caso de Uso	CU | Alquilar pelicula  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Cliente_ |
  | Descripción | _Tiene la posibilidad de alquilar una pelicula_  |
  | Flujo básico | __ |
  | Pre-condiciones | Escoger una Pelicula_  |  
  | Post-condiciones  | _Devolver la Pelicula_  |  
  |  Requerimientos | _El cliente debe de estar de acuerdo con las normas y condiciones_  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Reservar Pelicula
|  Caso de Uso	CU | Reservar Pelicula  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _Cliente_ |
  | Descripción | _El cliente puede reservar la pelicula_  |
  | Flujo básico | __ |
  | Pre-condiciones | _Escoger una Pelicula_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | _El cliente debe de estar de acuerdo con las normas y condiciones_  |
  |  Notas |  __ |
  | Autor  | Emanuel Santamaria_ |
  |Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Registra cliente
|  Caso de Uso	CU | Registra Cliente  |
  |---|---|
  | Fuentes  | _[Documento]()_  |
  | Actor  |  _AdminiistradorVIDEOMAX_ |
  | Descripción | _El administrador toma los datos personales del cliente_  |
  | Flujo básico | _El cliente da sus datos personales, Administrador los toma_ |
  | Pre-condiciones | _Haber un cliente_  |  
  | Post-condiciones  | __  |  
  |  Requerimientos | __  |
  |  Notas |  __ |
  | Autor  | _Emanuel Santamaria_ |
  |Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Registrar Alquiler
| Caso de Uso CU | Registrar Alquiler  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _AddministradorVIDEOMAX_|
  | Descripcion | _El administrador registra el alquiler de una pelicula_ |
  | Flujo Basico | _El cliente alquila una pelicula, El administrador la registra_ |
  | Pre-condiciones | _Haber un cliente queriendo alquilar una pelicula_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Registra reserva
| Caso de Uso CU | REgistrar reserva |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _AdministradorVIDEOMAX_ |
  | Descripcion | _Registra la reserva de una pelicula_ |
  | Flujo Basico | _EL cliente reserva una pelicula, El administrador la registra_ |
  | Pre-condiciones | _Haber un cliente reservando una pelicula_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
#### Registra Pelicula
| Caso de Uso CU | Registra Pelicula  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _AdministradorVIDEOMAX_|
  | Descripcion | _El administrador registra las peliculas abastecidas_ |
  | Flujo Basico | _EL proovedor abastece una Pelicula, El administrador la registra_ |
  | Pre-condiciones | _Que se abastesca una pelicula_ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _19/11/2024_ |
  
  |  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |

#### Actualizar Proovedor
| Caso de Uso CU | Actualizar proovedor  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _AdministradorVIDEOMAX_ |
  | Descripcion | _EL administrador actualiza al proovedor_ |
  | Flujo Basico | __ |
  | Pre-condiciones | __ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
  #### Abastecer pelicula segun existencia
| Caso de Uso CU | Abastecer pelicula  |
  |---|---|
  | Fuentes | _[Documento]()_|
  | Actor | _Proovedor_ |
  | Descripcion | _El proovedor abastece al administrador de peliculas_ |
  | Flujo Basico | __ |
  | Pre-condiciones | __ |
  | Post Condiciones | __ |
  | Requerimientos | __ |
  | Notas | __ |
  | Autor | _Emanuel Santamaria_ |
  | Fecha | _19/11/2024_ |
  
|  Atributo |||
|---|---|---|
| _Nombre_  | _Descripción_  | _Tipo_ |
| | |
  
