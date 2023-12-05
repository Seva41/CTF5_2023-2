# Aplicación de Inyección de SQL en login

## Descripción del Proyecto

Este proyecto es una aplicación web simple construida con Flask. Se utiliza para demostrar conceptos de seguridad de la información, específicamente la inyección de SQL en un aplicativo de login simple en web.

## Instalación

Para instalar las dependencias necesarias para este proyecto, necesitarás tener Python y pip instalados en tu sistema. Luego, puedes instalar las dependencias con el siguiente comando:

```sh
pip install -r requirements.txt
```

## Uso

Para iniciar la aplicación, ejecuta el siguiente comando:

```python
python injection.py
```

Esto iniciará el servidor Flask y podrás acceder a la aplicación en tu navegador web en `http://localhost:5000`.
Debes verificar que la variable `debug` en el archivo `injection.py` esté en `False`, y el host sea iguala `0.0.0.0` para que la aplicación funcione correctamente.

## Contribución

Las contribuciones son bienvenidas. Por favor, abre un problema primero para discutir lo que te gustaría cambiar.

## Licencia

Este proyecto está licenciado bajo los términos de la licencia [GPL-3.0](LICENSE).
