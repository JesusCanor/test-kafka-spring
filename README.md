Spring For Apache Kafka
=

#### Este repo recoge el ejemplo realizado en el siguiente video --> https://www.youtube.com/channel/UCTXForyROk00E6jiaNKSV1A
Es una prueba para publicar y escuchar eventos desde apache kafka, pero se ha añadiendo el tipo Event, para el objeto que se guarda
en vez de utilizar un string.

### Comandos para ejecutar dentro del contenedor Docker

#### ESTE COMANDO ES PARA PODER CREAR UN PRODUCTOR DE EVENTOS EN CONSOLA

`kafka-console-producer --bootstrap-server kafka:9092 --topic customers`

#### ESTE COMANDO ES PARA PODER RECIBIR LOS EVENTOS EN OTRA CONSOLA
`kafka-console-consumer --bootstrap-server kafka:9092 --topic customers --from-beginning`



