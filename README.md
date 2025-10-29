# cinemapedia

# Def

1. Copiar el .env.template y renombrarlo a .env
2. Cambiar las variables de entorno (The MovieDB)
3. Utilizar cualquiera de estos dos comandos para generar o actualizar archivos de drift al cambiar el esquema de la base de datos
```bash
1. dart run build_runner watch
2. dart run build_runner build
```

# Prod
Para cambiar el nombre de la aplicación:
```
dart run change_app_package_name:main com.jorgechavezrnd.cinemapedia
```

Para cambiar el ícono de la aplicación:
```
dart run flutter_launcher_icons
```

Para cambiar el splash screen:
```
dart run flutter_native_splash:create
```
