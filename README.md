# Torneo-banquitas-Base-NOSQL
Repositorio para las actividades de Bases de datos Avanzadas Ingeniería de Software virtual Iberoamericana.
Se crea en Mongo db la base de datos: banquitasdb y su colección inicial: equipos.
Con comandos CRUD, se crean las siguientes colecciónes, se suben los archivos Json, con los documentos de cada colección.
Mongo db shell
_________________________________________________
_________________________________________________
use banquitasdb
'switched to db banquitasdb'
db.createCollection ("jugadores")
{ ok: 1 }
db.createCollection ("arbitros")
{ ok: 1 }
db.createCollection("partidos")
{ ok: 1 }
db.createCollection("posiciones")
{ ok: 1 }
show collections
arbitros
equipos
jugadores
partidos
posiciones
_________________________________________________
_________________________________________________
