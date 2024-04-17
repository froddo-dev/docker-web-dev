# Entorno de desarrollo con Docker Compose 

Este repositorio contiene una configuración básica para un entorno de desarrollo utilizando Docker Compose. Este entorno incluye:

- MariaDB como base de datos
- PHP 8.0 con Apache como servidor web
- phpMyAdmin para gestionar la base de datos

## Instrucciones

**Clonar el repositorio:**

```bash
git clone https://github.com/froddo-dev/docker-web-dev.git
```

**Iniciar los contenedores:**
```bash
docker-compose up -d
```

### Comandos útiles

**Iniciar los contenedores:**
```bash
docker-compose up -d
```

**Detener los contenedores:**
```bash
docker-compose down
```

**Ver el estado de los contenedores:**
```bash
docker-compose ps
```

**Ver los logs de todos los contenedores:**
```bash
docker-compose logs -f
```

## Configuración

### Entorno Web
- Url: `http://localhost:8080`

### phpMyAdmin
- Url: `http://localhost:8081`
- Usuario: `root`
- Contraseña: `developer`

### MariaDB
- Base de datos: `developerdb`
- Usuario: `root`
- Contraseña: `developer`

## Documentación
- Docker: [Documentación Docker Compose](https://docs.docker.com/compose/)
- PHP: [Documentación PHP](https://www.php.net/manual/es/)
- MariaDB: [Documentación MariaDB](https://mariadb.com/kb/en/documentation/)

## Notas:
- Las contraseñas, usuarios, puertos y otras opciones se pueden configurar modificando el archivo docker-compose.yml. 
- Con este repositorio y los comandos mencionados, puedes crear y administrar de manera eficiente tu entorno de desarrollo local utilizando Docker Compose.
