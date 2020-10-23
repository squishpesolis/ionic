# ionic
version: 6

# Al descargar de Git debe ejecutarse
npm install

# Para configurar el Dispositivo de ejecución en Android con Capacitor
https://ionicframework.com/docs/developing/android
1. Configurar un dispositivo virtual

# Capacitor
2. Dentro de la carpeta del proyecto ejecutar

    2.1 ionic build
    2.2 ionic capacitor add android
    2.3 ionic cordova prepare android --> solo si se utiliza cordova
    2.4 ionic capacitor copy android --> para copiar a la app, tambien sirve
    para dispositivos fisicos
3. Exportar el Proyecto Ionic a Android estudio
    3.1 Open an existing proyect
    3.2 Ejecutar el emulador
    3.3 Para que los cambios se reflejen de manera automatica una vez realizada
    algun cambio en el proyecto Ionic se ejecuta este comando en el 
    proyecto ionic

    ionic capacitor run android -l --host=192.168.1.2  --> IP local

# Cordova

ionic cordova prepare android