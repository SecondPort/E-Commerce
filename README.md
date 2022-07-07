# Django E-commerce
---
Este es un sitio web de comercio electrónico muy simple construido con Django.
---

## Project Summary

El sitio web muestra productos. Los usuarios pueden agregar y quitar productos a/de su carrito mientras especifican la cantidad de cada artículo. Luego pueden ingresar su dirección y elegir Stripe para manejar el procesamiento del pago.

---

## Ejecutando este proyecto

Para poner en marcha este proyecto, debe comenzar por tener Python instalado en su computadora. Se recomienda que cree un entorno virtual para almacenar las dependencias de sus proyectos por separado. Puedes instalar virtualenv con

```
pip install virtualenv
```

Clone o descargue este repositorio y ábralo en el editor de su elección. En una terminal (mac/linux) o terminal de Windows, ejecute el siguiente comando en el directorio base de este proyecto

```
virtualenv env
```

Eso creará una nueva carpeta `env` en el directorio de su proyecto. A continuación, actívelo con este comando en mac/linux:

```
source env/bin/active
```

Luego instale las dependencias del proyecto con

```
pip install -r requirements.txt
```

Ahora puede ejecutar el proyecto con este comando

```
python manage.py runserver
```

**Nota** si desea que los pagos funcionen, deberá ingresar sus propias claves API de Stripe en el archivo `.env` en los archivos de configuración.
---
