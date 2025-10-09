# Un acercamiento a CAKEPHP 5 con la aplicación de Chuck Jokes

## Descripción del proyecto
Aplicación web desarrollada con CakePHP 5 que obtiene chistes aleatorios de Chuck Norris desde la API pública y permite guardarlos en una base de datos SQLite.

## Funcionalidades implementadas

### ✅ Funcionalidades básicas
- Obtención de chistes aleatorios desde la API de Chuck Norris
- Guardado de chistes en base de datos SQLite
- Prevención de duplicados usando api_id

### ✅ Funcionalidades avanzadas
- Listado de chistes guardados (visible en `/jokes/random`)
- Eliminación de chistes individuales
- Interfaz mejorada con navegación
- Mensajes de éxito/error

### ✅ Infraestructura
- Dockerización completa con docker-compose
- Configuración de Apache con mod_rewrite
- Base de datos SQLite persistente
- Tests básicos con PHPUnit

## Instalación y ejecución

### Con Docker (Recomendado)

```bash
# Clonar el repositorio
git clone https://github.com/cifpfbmoll/chuck-jokes-como-acercamiento-a-cakephp-5-Carlos-Lopez-Calvo.git

# Entrar al directorio
cd chuck-jokes-como-acercamiento-a-cakephp-5-Carlos-Lopez-Calvo/chuck-jokes

# Construir y ejecutar
docker-compose build
docker-compose up -d

# Acceder a la aplicación
open http://localhost:5504/jokes/random
```

## Uso de la aplicación

1. **Obtener chiste aleatorio**: La página principal muestra un chiste aleatorio de Chuck Norris
2. **Guardar chiste**: Haz clic en "Guardar en la base de datos"
3. **Ver chistes guardados**: La lista aparece automáticamente debajo del chiste actual
4. **Eliminar chiste**: Usa el botón "Eliminar" en cada chiste guardado
