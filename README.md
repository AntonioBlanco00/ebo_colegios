# ebo_colegios

## Configuración de `ebo_gpt`

Para que `ebo_gpt` funcione correctamente, es necesario crear un archivo `.env` y agregar tu clave de OpenAI.

### Pasos para crear el archivo `.env`
1. Navega a la carpeta `ebo_gpt` en tu terminal:
   ```sh
   cd EBO2/ebo_gpt
   ```
      
2. Ejecuta el siguiente comando para crear el archivo `.env`:
   ```sh
   touch .env
   ```
3. Abre el archivo `.env` con tu editor de texto preferido y agrega la siguiente línea:
   ```env
   OPENAI_API_KEY="tu_clave_aqui"
   ```
4. Guarda los cambios y cierra el archivo.

Ahora `ebo_gpt` estará configurado correctamente para utilizar la API de OpenAI.

## Cómo lanzar la aplicación.

Te abres un terminal y accedes a la carpeta EBO 2:

   ```sh
   cd EBO2
   ```

Conectas tanto EBO como el portátil a la misma red wifi, normalmente compartida por tus datos móviles. Para configurar la IP debes consultar la IP en EBO y ejecutar en el portátil el comando:

   ```sh
   python3 actualizar_configs.py
   ```

Una vez hecho esto, para lanzar los juegos bastará con ejecutar el siguiente comando para que se lance todo de forma automática:

   ```sh
   bash iniciar_juegos.sh
   ```

Si escribes en la aplicación de control manual de EBO y habla y expresa emociones, todo está bien configurado, en caso de que no vaya, la IP no estará bien configurada.


