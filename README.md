# Gulp

## Instalar

1) Asegurate de tener instalado el cliente de gulp.

``` sh
npm install gulp-cli -g
```

2) Descarga `gulpfile.js` y `package.json`.

``` sh
curl -L -s -o gulpfile.js https://raw.githubusercontent.com/Pixelmouse/gulp/master/gulpfile.js
curl -L -s -o package.json https://raw.githubusercontent.com/Pixelmouse/gulp/master/package.json
```

3) Instala dependencias.

``` sh
npm i
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
