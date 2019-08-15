# Labo 07

### Note

Le répertoire `./stylus/core-css` contient les élements indispensable à l'utilisation
du framework.  
**Important :** Sans ce répertoire les générateur de class ne fonctionerons pas.

### Commandes

- Complie tous les fichiers stylus présent des le rep `./css/styles` dans le fichier `./css/dist/app.css`

```
stylus ./css/stylus/app.styl --include ./css/stylus --out ./css/dist --watch --compress
```
