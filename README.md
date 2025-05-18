# <span style="color:#4CAF50;">Photo Gallery App (Edición de icono y splash screen)</span>
## Nombres: García Mireya 
## <span style="color:#2196F3;">Descripción</span>

Esta aplicación está construida con **Ionic** y **Angular** para gestionar fotos utilizando la cámara del dispositivo y mostrarlas en una galería. Los usuarios pueden capturar fotos y verlas de inmediato.
[Descargar aquí el apk](https://drive.google.com/file/d/1cEv171Fne-wVl1iVjuJtubuLrcF5yw1L/view?usp=drive_link)

### <span style="color:#FF5722;">Un poco de cual su el metodo que se utilizo para realizar la actividad</span>

1. **Descarga de imagenes** para el icono de la aplicación que se visualiza a la hora de la descarga se utilizó una imagen realizada en canva con dimensiones 1024 * 1024 px y para el splash screen se utilizaron dos iamgenes de 2732 * 2732 px, una para el modo oscuro y otra para el modo claro. Cabe recalcar que el nombre de los archivos obligatoriamente se llaman "icon", "splash" y "splash-dark" (en formato "png").
2. **Carpeta "assets"** se crea una carpeta en la raiz del proyecto "assets" y se mueven allí las imagenes. 
3. **Intalación del capacitor** Se lo instala con el comando "npm i -D @capacitor/assets".
4. **Generación de recursos** Se los genera con el comando "npx @capacitor/assets generate \
  --iconBackgroundColor '#eeeeee' \
  --iconBackgroundColorDark '#222222' \
  --splashBackgroundColor '#eeeeee' \
  --splashBackgroundColorDark '#111111'
".
5. **Construcción y prueba**
   - ionic build
   - npx cap add android
   - npx cap copy android
   - npx cap sync
   - npx cap open android
6. **Problematicas que se resolvieron**
   En Androids mayores a 12 se colocaba por defecto el icono en el splash, por lo que, se creo otroarchivo "style" que maneja versiones actuales. 

## <span style="color:#2196F3;">Evidencias</span>

**Icono que se presenta al intalar la aplicación**
![icono](https://github.com/user-attachments/assets/ac40154c-cf25-4418-84d7-c430e7fda796)
**Splash Screen (modo claro)
![Imagen de WhatsApp 2025-05-18 a las 01 07 54_78d9c7db](https://github.com/user-attachments/assets/78373f2b-962f-45f1-8e8c-b8ad3d84bbff)
**Splash Screen (modo oscuro)
![Imagen de WhatsApp 2025-05-18 a las 01 07 54_b5f88c36](https://github.com/user-attachments/assets/4b62f355-dcf4-4943-8f88-3ec09fbd6a32)

# Deber_Splash_Screen_Garc-a-Mireya
