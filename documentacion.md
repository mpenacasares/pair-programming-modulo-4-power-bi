**Datos proyecto modulo 2**
CSV:

- artista_id, estadisticas, info_canciones, informacion_artista.

Intro de la presentación:
- Explicar que es una continuaciónd el proyecto del módulo 2 donde extraímos info de las APIs de Spoti, MB y Lastfm para los años 2021 y 2022 y los géneros electrónica, rock, latino y música española.
- Presentar grupo con fotos de cada una y que luego desaparezcan y se vean las nuestras.

Primer dashboard: info. de artistas
- Gráfica de barras donde podemos ver número de artistas por país.
- De ahí, va a un mapa donde se pueden ver bolas con diferentes tamaños en función de número de artistas de los países. BN con total de artistas, pies con % sobre el total y gráfica circular interactiva que cambia por país mostrando % de artistas sobre el total. 

Segundo dashboard: estadísticas.
- Gráfica de barras agrupadas u horizontales mostrando lanzamientos de canciones por género.



Propuestas:

- Paises donde pertenecen mas artistas (DB 1 [Dashboard 1])

- Comparar los lanzamientos de canciones por genero en los anios de la muestra -> boton que te lleve a pag con analisis mas detallado (DB 2)

- Produccion por artistas -> que artistas han sacado mas canciones en los anios de muestra? genero de las mismas? (DB 2)

- Top 10 artistas mas escuchados, comparando listener y playcount (DB 2)

**Info electronica** -> electro_music_on_Spotify.csv. 1987 a 2022.
Podríamos coger la info. desde 1987 hasta el 2020, ya que en el otro CSV tenemos info. de 2021 y 2022.

'track_name', 'track_id', 'track_popularity', 'track_number',
       'explicit', 'available_markets', 'artists_names', 'artists_ids',
       'album_id', 'main_artist_id', 'danceability', 'energy', 'key',
       'loudness', 'mode', 'speechiness', 'acousticness', 'instrumentalness',
       'liveness', 'valence', 'tempo', 'duration_sec', 'time_signature',
       'album_name', 'album_release_date', 'total_tracks', 'type', 'image_url',
       'album_popularity', 'album_label', 'followers', 'genres', 'artist_name',
       'artist_popularity', 'lowest position', 'mean_position', 'position_std',
       'best_position', 'times_in_rating', 'born_or_founded_in',
       'positions_and_years_data', 'dj_score', 'release_year', 'release_month',
       'track_name_length', 'main_artist_name_length', 'album_name_length',
       'available_markets_count', 'artists_count', 'cover_id'

**Info rock** -> UltimateClassicRock.csv. Música rock - 1962 to 2024
Podríamos coger la info. desde 1962 hasta el 2020, ya que en el otro CSV tenemos info. de 2021 y 2022.

'Track', 'Artist', 'Album', 'Year', 'Duration', 'Time_Signature',
       'Danceability', 'Energy', 'Key', 'Loudness', 'Mode', 'Speechiness',
       'Acousticness', 'Instrumentalness', 'Liveness', 'Valence', 'Tempo',
       'Popularity'

Propuestas:
- Gráfica de línea que muestre la evolución del número de albumes de cada género en los 10/15 últimos años.
- Cuál es el artista/album dentro de cada género que tiene más albumes?
- Popularidad de esos artistas?
- Podríamos hacer alguna correlación entre la popularidad y el danceability de cada género.

