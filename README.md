# :card_index_dividers: repo-python-libs

Respositorio con librerias de python, generalmente son para python 3.8 en adelante.

Las librerias siempre tienen la misma estructura para homologar y hacer algo automatico.

![docs](docs/img/python-lib.png)

## :tada: Uso

Copiar la carpeta de la libreria que se encuentra dentro de la version que se quiere y pegarla en la estructura de carpetas de `/logic/libs/`.
Por ejemplo la libreria de **variables** quedaria asi:

```bash
/logic/libs/variables
    |- src/
    |- variables.py
```

Esto es para que se pueda cambiar de version con solo reemplazar una carpeta por otra

## :books: Librerias disponibles

- [exception](libs/exception/docs.md): Para manejar errores de negocio
- [logger](libs/logger/docs.md): SImple herramienta de logueo
- [rest](libs/rest/docs.md): Sirve para configurar Flask
- [variables](libs/variables/docs.md): Para agregarle variables a un proyecto
