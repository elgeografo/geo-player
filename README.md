# geo-player
A deck.gl-based GeoJSON layer animation player with sequenced transitions and camera movements

## Uso

Para abrir la aplicación, abre el archivo `index.html` en tu navegador.

### Parámetros URL

Puedes especificar qué escena cargar mediante el parámetro `scene`:

```
index.html?scene=scenes/01-explanacion-horizontal
```

Si no especificas ningún parámetro, se cargará la escena por defecto: `scenes/01-explanacion-horizontal`

### Estructura de escenas

Cada escena debe estar en su propio directorio y contener:
- `config.json` - Configuración de capas y vista inicial
- `animations.json` - Secuencia de animaciones
- `json/` - Directorio con los archivos GeoJSON de las capas
- `img/` - Directorio con las imágenes utilizadas en las animaciones
