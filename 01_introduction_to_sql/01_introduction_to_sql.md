# Introduction to SQL

## ¿Por qué necesitamos Bases de Datos y SQL?

- En el mundo actual, todo genera datos: desde tu nombre y lo que hay en tu móvil hasta las transacciones bancarias y los productos de una empresa. Mientras que una persona puede usar archivos de texto o Excel para sus datos personales, las empresas manejan volúmenes masivos que requieren algo "más grande, fuerte y audaz".
  - La Base de Datos: Es un contenedor que organiza la información para que sea fácil de acceder, gestionar y buscar. A diferencia de las hojas de cálculo, que pueden corromperse con millones de registros, las bases de datos son seguras, profesionales y capaces de manejar cantidades ingentes de datos.
  - SQL (Structured Query Language): Es el lenguaje estándar que utilizamos para "hablar" con la base de datos. Es la herramienta que nos permite transformar una pregunta compleja (como "¿cuánto fue el gasto total?") en un resultado rápido y preciso, evitando procesos manuales largos y desordenados.

## El Ecosistema de Gestión de Datos

- Para que SQL funcione en un entorno empresarial, intervienen tres componentes esenciales:
  - DBMS (Database Management System): Es el software que actúa como "gerente". Gestiona todas las solicitudes (SQLs) que provienen de personas, aplicaciones o herramientas de visualización como Power BI, decidiendo qué prioridades ejecutar y verificando la seguridad.
  - El Servidor: Es la máquina física (o en la nube) donde reside la base de datos. Es una computadora potente que permanece encendida las 24 horas, los 7 días de la semana, para asegurar que los datos estén siempre disponibles.
  - Interacciones: No solo los humanos escriben SQL; las páginas web, las aplicaciones móviles y los tableros de control también envían comandos SQL constantemente para interactuar con los datos.

## Tipos de Bases de Datos

- Existen diversas formas de organizar los datos según el objetivo:
  - Relacionales (SQL): Son las más comunes y se basan en tablas con filas y columnas que se relacionan entre sí. Ejemplos incluyen Microsoft SQL Server, MySQL y PostgreSQL.
  - NoSQL: Incluyen otros modelos como Clave-Valor (diccionarios), Basadas en Columnas (para búsquedas masivas), Grafos (enfocadas en conexiones entre objetos) y Documentales (donde la estructura es flexible).

## El Lenguaje: Tipos de Comandos SQL

- SQL se divide en familias de comandos según su función:
  1. DDL (Data Definition Language): Se usa para definir la estructura (crear, alterar o borrar tablas). Comandos: `CREATE`, `ALTER`, `DROP`.
  2. DML (Data Manipulation Language): Se usa para manipular los datos dentro de las tablas. Comandos: `INSERT` (agregar), `UPDATE` (editar) y `DELETE` (eliminar).
  3. DQL (Data Query Language): Se usa para hacer preguntas a los datos. El comando principal es `SELECT`, que es el más utilizado para obtener respuestas y análisis.

## ¿Por qué es vital aprender SQL?

- Es el estándar de la industria. Es un requisito casi universal en descripciones de empleo para desarrolladores de software, analistas de datos, ingenieros y científicos de datos. Aprender SQL es como aprender el idioma local al mudarte a un nuevo país: es la única forma de comunicarte eficazmente con el entorno de los datos.

## Analogía para recordar

- Imagina que la Base de Datos es una biblioteca gigante y muy organizada. El Servidor es el edificio físico que alberga los libros y que nunca cierra. El DBMS es el bibliotecario jefe que recibe todas las peticiones y mantiene el orden. Finalmente, SQL es el formulario específico que debes llenar para pedirle al bibliotecario exactamente qué información necesitas encontrar.
