# Stolen Studio: catálogo de canciones

Catálogo público que lee la app Stolen Studio desde `raw.githubusercontent.com`.

```
catalog.json                       lista de canciones (id, título, artista, duración, versión)
songs/<id>/song.json               secciones, letra sincronizada y archivos
songs/<id>/instrumental.mp3        pista sin voz (separada con Demucs)
songs/<id>/vocals.mp3              voz original
songs/<id>/cover.jpg               carátula (opcional)
```

Las canciones se generan con `tools/prepare_song.py` del repositorio de la app.
Material de audio usado exclusivamente con fines educativos (asignatura Informática Audiovisual, Universidad de Oviedo).
