# Labo 07

![status](https://img.shields.io/badge/status-inprogress-red)
![version](https://img.shields.io/badge/version-0.1.0-green)
![size](https://img.shields.io/badge/mimified%20size-7%20kB-blue)

### Note

Le répertoire `./stylus/core-css` contient les élements indispensable à l'utilisation
du framework.  
**Important :** Sans ce répertoire les générateur de class ne fonctionerons pas.

### Commandes

- Complie tous les fichiers stylus présent des le rep `./css/stylus` dans le fichier `./css/dist/app.css`

```
stylus ./css/stylus/main.styl --include ./css/stylus --out ./css/dist --watch --compress
```
