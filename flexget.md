
Ejecutar en modo tests
	/home/javier/.local/bin/flexget -c config-peliculas.yml --test execute
Ejecutar
	/home/javier/.local/bin/flexget -c prueba.yml execute
ejecutar forzando descubrimiento
	/home/javier/.local/bin/flexget -c prueba.yml execute --discover-now
ejecutar una tarea especifica (reg)
	/home/javier/.local/bin/flexget -c prueba.yml execute --tasks Series-*
trakt.tv
	Autorizar
		/home/javier/.local/bin/flexget -c config-peliculas.yml trakt auth gacomun@gmail.com
	Refresh token
		/home/javier/.local/bin/flexget -c config-peliculas.yml trakt refresh gacomun@gmail.com
Buscadores:
	/home/javier/.local/bin/flexget plugins --interface search

Instalar
	/home/javier/.local/bin/pip install transmissionrpc
	*/home/javier/.local/bin/pip install descarga2020
	*/home/javier/.local/bin/pip install divxatope

* Ejemplos
	flexget --test -c jco-peliculas.yml execute
*Test
	flexget --test
*Especifico
	flexget -c movies.yml execute
* Activar virtualEnv
	source ~/flexget/bin/activate