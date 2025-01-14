![](https://github.com/BoldBlueTechnologies/SuperSegurosPartners/blob/main/super-sdk-splash.png)

# SuperSegurosSDKAndroid

SuperSegurosSDKAndroid es un SDK que muestra una interfaz para que tus usuarios puedan cotizar y contratar un Seguro de Auto de manera sencilla y rápida.
Este repositorio contiene todo lo necesario para integrar el SDK en tu proyecto Android.

# 1. Instalación

Paso 1. Agrega el repositorio JitPack a tu archivo de compilación:

```
allprojects {
  repositories {
    maven { url 'https://jitpack.io' }
  }
}
```
Paso 2. Agrega la dependencia
```
dependencies {
      implementation 'com.github.BoldBlueTechnologies:SuperSegurosSDKAndroid:${version}'
}
```
# 2. Uso

El SDK ofrece un botón personalizado (SuperButton_superapi) que mostrará la interfaz de cotización y contratación. 

Integración por XML

Ejemplo:
```
<
com.app.boldblue.superseguros.partners.SuperButton_superapi
android:layout_width="match_parent"
android:layout_height="wrap_content"
/>
```
![SuperButton_superapi](https://github.com/BoldBlueTechnologies/SuperSegurosPartners/blob/main/boton_super_seguros.jpg)

# 3. Requerimiento
   
Android: SDK 26 o superior.

# 4. Soporte
   
Si tienes dudas, sugerencias o problemas:

Abre un issue en este repositorio. O contacta al equipo de Bold Blue Technologies.
