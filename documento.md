### Instalación global del CLI de NestJS

Para poder utilizar el CLI de NestJS en cualquier lugar de tu sistema, es necesario instalarlo globalmente. Ejecuta el siguiente comando en tu terminal:

```
npm install -g @nestjs/cli
```

### Creación de un nuevo proyecto en NestJS

Para crear un nuevo proyecto con NestJS, puedes usar el comando `nest new` seguido del nombre que le quieras dar al proyecto. Por ejemplo, para crear un proyecto llamado `nestfirstapp`, ejecuta:

```
nest new nestfirstapp
```

Sigue las instrucciones en pantalla para elegir entre `npm` o `yarn` como gestor de paquetes.

### Generar un módulo 'tasks'

Los módulos en NestJS son contenedores que agrupan servicios, controladores y otros componentes relacionados. Para generar un módulo llamado `tasks`, usa el siguiente comando:

```
nest generate module tasks
```

Esto creará el archivo del módulo y lo registrará automáticamente.

### Generar un controlador 'tasks' sin archivo de pruebas

NestJS genera un archivo de pruebas (`.spec.ts`) por defecto para los controladores, pero si no deseas incluir este archivo, puedes usar la opción `--no-spec`. Para generar un controlador llamado `tasks` sin el archivo de pruebas, ejecuta:

```
nest generate controller tasks --no-spec
```

### Generar un servicio 'tasks'

Una vez dentro de tu proyecto, puedes generar un nuevo servicio utilizando el comando `nest g service` seguido del nombre del servicio. En este caso, para generar un servicio llamado `tasks`, ejecuta:

```
nest g service tasks
```

Esto creará los archivos necesarios para el servicio y los añadirá automáticamente al módulo correspondiente.

### Instalar dependencias para validación y transformación de clases

Para realizar validaciones y transformaciones de datos en tus DTOs (Objetos de Transferencia de Datos), es recomendable utilizar las bibliotecas `class-validator` y `class-transformer`. Para instalarlas, ejecuta el siguiente comando:

```
npm install --save class-validator class-transformer
```

Con esto, tendrás todas las dependencias necesarias para implementar validaciones en tus controladores y servicios.
