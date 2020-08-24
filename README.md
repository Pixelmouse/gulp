# Gulp

## Instalar

1) Asegurate de tener instalado el cliente de gulp.

``` sh
npm install gulp-cli -g
```

2) Descarga `gulpfile.js`.

``` sh
curl -L -s -o gulpfile.js https://raw.githubusercontent.com/Pixelmouse/gulp/master/gulpfile.js
```

3) Instala dependencias.

``` sh
npm i browser-sync @babel/core @babel/preset-env gulp-exec gulp-sourcemaps gulp-babel gulp-uglify gulp-rename gulp-concat gulp-sass gulp-htmlmin
```

## Uso

### Compilar

``` sh
gulp
```

### Servidor de refresco automático que compila a cada cambio

Recuerda cambiar `proxy` dentro del `gulpfile.js`. (Por ejemplo, Django sería localhost:8000)

``` sh
gulp dev
```
