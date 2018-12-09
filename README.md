# NEW WEBISTE PLAN GENERACIÓN DE EMPLEO

Repositorio del código fuente del nuevo sitio de "Plan Generación de Empleo" desarrollada con Wordpress mediante contenedores Docker.

## Dependencias

Wordpress 4.9.8
PHP 7.1
MariaDB 10
Apache2
Docker

## Instalación

Debe tener instalado docker-compose para ejecutar el sitio, use el siguiente comando para levantar el sitio con docker:

```bash
$ sudo docker-compose up -d
```

## Uploads.ini en servidor

```bash
file_uploads = On
memory_limit = 500M
upload_max_filesize = 30M
post_max_size = 30M
max_execution_time = 600
```


## Instalation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install foobar.

```bash
pip install foobar
```

## Usage

```python
import foobar

foobar.pluralize('word') # returns 'words'
foobar.pluralize('goose') # returns 'geese'
foobar.singularize('phenomena') # returns 'phenomenon'
```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)