# Desarrollo Web en Entornos Servidor - 01 - Introducción a la Programación de Software en Servidor

Tema 01. Introducción a la Programación de software en Servidor. 2DAW. Curso 2025-2026.

![imagen](https://github.com/joseluisgs/DesarrolloWebEntornosServidor-00-2023-2024/raw/master/images/servicios.png)

- [Desarrollo Web en Entornos Servidor - 01 - Introducción a la Programación de Software en Servidor](#desarrollo-web-en-entornos-servidor---01---introducción-a-la-programación-de-software-en-servidor)
- [Contenido en Youtube](#contenido-en-youtube)
  - [1. Introducción al Desarrollo Web en Entorno Servidor](#1-introducción-al-desarrollo-web-en-entorno-servidor)
    - [1.1. El Desarrollo Web Actual Web](#11-el-desarrollo-web-actual-web)
    - [1.2. Modelos de Ejecución de Código en el Servidor y en el Cliente](#12-modelos-de-ejecución-de-código-en-el-servidor-y-en-el-cliente)
  - [2. Componentes de una Web: Front-end, Back-end, Página Web vs. Aplicación Web](#2-componentes-de-una-web-front-end-back-end-página-web-vs-aplicación-web)
    - [2.1. Front-end y Back-end: La División y la Universalidad del Back-end](#21-front-end-y-back-end-la-división-y-la-universalidad-del-back-end)
    - [2.2. Página Web vs. Aplicación Web: Diferencias y Tecnologías Clave](#22-página-web-vs-aplicación-web-diferencias-y-tecnologías-clave)
  - [3. Arquitecturas Web](#3-arquitecturas-web)
    - [3.1. Aspectos Generales y Evolución de las Arquitecturas Web](#31-aspectos-generales-y-evolución-de-las-arquitecturas-web)
    - [3.2. Modelos de Arquitectura Software: Monolítica, de Capas, Microservicios y Serverless](#32-modelos-de-arquitectura-software-monolítica-de-capas-microservicios-y-serverless)
      - [3.2.1. Monolítica, de Capas, Servicios Web, Microservicios y Serverless](#321-monolítica-de-capas-servicios-web-microservicios-y-serverless)
      - [3.2.2. Modelo-Vista-Controlador (MVC)](#322-modelo-vista-controlador-mvc)
    - [3.3. Patrones de Diseño Introductorios](#33-patrones-de-diseño-introductorios)
  - [4. El Protocolo HTTP y HTTPS](#4-el-protocolo-http-y-https)
    - [4.1. Características y Ventajas del Protocolo HTTP](#41-características-y-ventajas-del-protocolo-http)
    - [4.2. Formato de Peticiones y Respuestas HTTP](#42-formato-de-peticiones-y-respuestas-http)
    - [4.3. Cabeceras HTTP](#43-cabeceras-http)
    - [4.4. Métodos/Verbos HTTP (GET, POST, PUT, DELETE, HEAD)](#44-métodosverbos-http-get-post-put-delete-head)
    - [4.5. Códigos de Estado HTTP](#45-códigos-de-estado-http)
    - [4.6. El Protocolo HTTPS (SSL/TLS y Certificados Digitales)](#46-el-protocolo-https-ssltls-y-certificados-digitales)
  - [5. Servicio Web y Comunicación con APIs](#5-servicio-web-y-comunicación-con-apis)
    - [5.1. ¿Qué es un Servicio Web y Qué Aporta?](#51-qué-es-un-servicio-web-y-qué-aporta)
    - [5.2. Diferencia entre un Servicio Web y una Página Web Dinámica](#52-diferencia-entre-un-servicio-web-y-una-página-web-dinámica)
    - [5.3. Protocolos de Comunicación de API](#53-protocolos-de-comunicación-de-api)
      - [5.3.6. Otros Protocolos y Estilos de Comunicación (mención breve)](#536-otros-protocolos-y-estilos-de-comunicación-mención-breve)
    - [5.4. JWT (JSON Web Token) - Concepto de Autenticación y Autorización](#54-jwt-json-web-token---concepto-de-autenticación-y-autorización)
    - [5.5. Ejemplo de arquitectura Netflix](#55-ejemplo-de-arquitectura-netflix)
  - [6. Funcionamiento de una Web Dinámica y Generación de Contenido](#6-funcionamiento-de-una-web-dinámica-y-generación-de-contenido)
    - [6.1. Páginas estáticas vs. Páginas dinámicas](#61-páginas-estáticas-vs-páginas-dinámicas)
    - [6.2. Cómo Funciona una Página Web Dinámica](#62-cómo-funciona-una-página-web-dinámica)
    - [6.3. Tecnologías de Generación de Páginas Web Dinámicas y Ejemplos "Hola Mundo"](#63-tecnologías-de-generación-de-páginas-web-dinámicas-y-ejemplos-hola-mundo)
  - [7. Lenguajes y Frameworks de Programación en Entorno Servidor](#7-lenguajes-y-frameworks-de-programación-en-entorno-servidor)
    - [7.1. Tipos de Ejecución de Lenguajes del Lado del Servidor](#71-tipos-de-ejecución-de-lenguajes-del-lado-del-servidor)
    - [7.2. Plataformas Web Libres y Propietarias](#72-plataformas-web-libres-y-propietarias)
    - [7.3. Tecnologías para el Desarrollo de Servicios](#73-tecnologías-para-el-desarrollo-de-servicios)
    - [7.4. Integración del Código con Lenguajes de Marcas](#74-integración-del-código-con-lenguajes-de-marcas)
  - [8. Funcionamiento y Configuración de Servidores Web y de Aplicaciones](#8-funcionamiento-y-configuración-de-servidores-web-y-de-aplicaciones)
    - [8.1. Servidores Web: Apache y Nginx](#81-servidores-web-apache-y-nginx)
      - [8.1.1. Instalación y Configuración Básica de Apache (Linux)](#811-instalación-y-configuración-básica-de-apache-linux)
      - [8.1.2. Arranque y Detención del Servicio Apache](#812-arranque-y-detención-del-servicio-apache)
      - [8.1.3. Configuración de Hosts Virtuales](#813-configuración-de-hosts-virtuales)
    - [8.2. Servidores de Aplicaciones: Tomcat](#82-servidores-de-aplicaciones-tomcat)
      - [8.2.1. Instalación y Configuración Básica de Tomcat (requisito JDK)](#821-instalación-y-configuración-básica-de-tomcat-requisito-jdk)
    - [8.3. Gestores de Bases de Datos](#83-gestores-de-bases-de-datos)
  - [9. Despliegue de Aplicaciones Web](#9-despliegue-de-aplicaciones-web)
    - [9.1. Concepto de Despliegue](#91-concepto-de-despliegue)
    - [9.2. Escalabilidad (Vertical y Horizontal, Clusters y Balanceadores de Carga)](#92-escalabilidad-vertical-y-horizontal-clusters-y-balanceadores-de-carga)
    - [9.3. Despliegue en Contenedores (Docker, Kubernetes)](#93-despliegue-en-contenedores-docker-kubernetes)
    - [9.4. Despliegue en la Nube (AWS, Google Cloud, Azure)](#94-despliegue-en-la-nube-aws-google-cloud-azure)
    - [9.6. Introducción a la Integración Continua / Despliegue Continuo (CI/CD)](#96-introducción-a-la-integración-continua--despliegue-continuo-cicd)
  - [10. Conceptos Clave de Seguridad y Monitorización (introducción muy breve)](#10-conceptos-clave-de-seguridad-y-monitorización-introducción-muy-breve)
    - [10.1. Seguridad en Servidores Web (Autenticación HTTP Basic/Digest, Control de Acceso)](#101-seguridad-en-servidores-web-autenticación-http-basicdigest-control-de-acceso)
    - [10.2. Monitorización con Archivos de Registro (Logs CLF, Rotación de Logs)](#102-monitorización-con-archivos-de-registro-logs-clf-rotación-de-logs)
  - [Autor](#autor)
    - [Contacto](#contacto)
  - [Licencia de uso](#licencia-de-uso)



# Contenido en Youtube

- [Podcast](https://youtu.be/SJaedJqq8pE)
- [Resumen](https://youtu.be/8hMghl24sP8)
- [APIs y protocolos](https://youtu.be/-b2Aq3Dce_E)
- [Páginas Web Estáticas vs. Dinámicas](https://youtu.be/2e_s8vg3Qyg)
- [Lista de Reproducción](https://www.youtube.com/watch?v=tlRgLmopS1g&list=PLGIH-7eZDbVzq51Vk4XHAgQ4fTHZVTLRl)



## 1. Introducción al Desarrollo Web en Entorno Servidor

### 1.1. El Desarrollo Web Actual Web
¿Algunas vez has pensado lo que pasa una vez le das al botón de "Enviar" en un formulario web? ¿O cómo es posible que puedas ver tu perfil en una red social, comprar en una tienda online o ver una película en streaming desde cualquier dispositivo? ¿O que pasa cuando pones una URL en el navegador? Detrás de estas acciones aparentemente simples, hay un complejo ecosistema de tecnologías y procesos que hacen posible la experiencia web moderna.

![img](/images/clic.gif)

El desarrollo web moderno es un campo en constante evolución que abarca la creación y mantenimiento de sitios web y aplicaciones que operan a través de Internet. En la actualidad, el desarrollo no solo se enfoca en la funcionalidad, sino también en cómo estas aplicaciones se pondrán a disposición de los usuarios, un proceso crucial conocido como **despliegue**. Este proceso es fundamental para la viabilidad de cualquier proyecto web, ya que permite que la aplicación pase del entorno de desarrollo a un entorno de producción, donde será accesible para los usuarios finales.

Los principales objetivos del despliegue son garantizar la **accesibilidad**, la **estabilidad**, la **escalabilidad** y la **seguridad** de las aplicaciones. Un despliegue eficiente contribuye a una **rapidez en el *Time-to-Market***, lo que permite a las empresas lanzar productos más rápidamente. Facilita la **iteración rápida** y la entrega continua de nuevas funcionalidades y mejoras, esencial para adaptarse a las necesidades del mercado y de los usuarios. La **automatización** de los procesos de despliegue reduce los errores humanos y aumenta la eficiencia, liberando a los equipos de desarrollo para tareas más estratégicas. Un despliegue eficaz mejora la **competitividad** de una empresa al proporcionar un servicio fiable y de alta calidad. Además, la **documentación** de todos los procesos de despliegue es indispensable para asegurar que puedan ser replicados, para la resolución de problemas y para la formación de nuevos miembros del equipo.

![img](/images/webdev.png)

### 1.2. Modelos de Ejecución de Código en el Servidor y en el Cliente

La lógica de una aplicación web se divide y ejecuta en dos entornos principales, cada uno con responsabilidades específicas: el lado del cliente y el lado del servidor.

El **código que se ejecuta en el lado del cliente** (Front-end) opera en el navegador web del usuario. Se desarrolla principalmente con HTML y CSS para la estructura y el estilo, y JavaScript para la interactividad y la lógica dinámica que ocurre en el navegador. Este código permite animaciones, validaciones de formularios y la modificación del contenido de la página sin recargarla completamente, gracias a técnicas como AJAX.

Por otro lado, el **código que se ejecuta en el lado del servidor** (Back-end) corre en un servidor web o de aplicaciones. Es responsable de la lógica de negocio, la interacción con bases de datos y la generación del contenido dinámico que luego se envía al navegador del cliente.

Ambos modelos trabajan en conjunto: el servidor puede generar una página con contenido inicial, y el cliente puede ejecutar JavaScript para añadir interactividad, realizar validaciones preliminares en formularios o cargar datos adicionales de forma asíncrona. Por ejemplo, en una aplicación de correo web, el programa que obtiene los mensajes de una base de datos se ejecuta en el servidor, mientras que el navegador ejecuta el código que avisa si se olvida el asunto de un mensaje. Para verificar la longitud mínima de una contraseña, sería preferible que el código de comprobación se ejecutara en el navegador web, ya que no es necesario enviar la contraseña al servidor para esta tarea.

![img01](/images/anatomia_web.gif)

## 2. Componentes de una Web: Front-end, Back-end, Página Web vs. Aplicación Web

### 2.1. Front-end y Back-end: La División y la Universalidad del Back-end

El desarrollo web actual ha especializado los perfiles en dos roles principales, reflejando la división entre el cliente y el servidor:
*   El **Front-end** es la parte visible de la aplicación, con la que el usuario interactúa directamente. Se encarga del diseño, maquetación y la lógica interactiva en el navegador, utilizando tecnologías como HTML, CSS y JavaScript (y sus *frameworks*). Un desarrollador Front-end también se preocupa por la correcta presentación en cualquier tipo de dispositivo e incluso por el posicionamiento en buscadores.
*   El **Back-end** es la parte del desarrollo que se ejecuta en el servidor. Incluye la lógica de negocio, la interacción con bases de datos y la administración del servidor de aplicaciones. Tecnologías como PHP, Java (Servlets/JSP), Python, ASP.NET (C#) o Ruby se utilizan en el Back-end.

La tendencia actual es que el **Back-end se vuelva universal o agnóstico**. Esto significa que el servidor expone su funcionalidad a través de **APIs (Application Programming Interfaces)** que pueden ser consumidas por cualquier tipo de cliente. Esta separación del Back-end del Front-end es crucial porque permite que el mismo Back-end pueda servir a:
*   **Aplicaciones web** (ej., Single Page Applications - SPAs) que se ejecutan en navegadores.
*   **Aplicaciones móviles** (iOS y Android).
*   **Aplicaciones de escritorio** (con interfaces nativas).
*   **Otros servicios o sistemas**.

De esta manera, el Back-end se desvincula de una interfaz de usuario específica, ofreciendo datos en formatos estandarizados (como JSON o XML) que los clientes interpretan y renderizan según sus propias capacidades. Este enfoque es fundamental para la integración de diferentes servicios y para la creación de aplicaciones más flexibles y escalable.


![img](/images/front-back-api.jpg)

### 2.2. Página Web vs. Aplicación Web: Diferencias y Tecnologías Clave

Es fundamental distinguir entre una página web y una aplicación web:
*   Una **página web** es un documento o un conjunto de documentos que se muestran en un navegador. Puede ser **estática** (su contenido no cambia dinámicamente, a menos que un desarrollador la modifique manualmente), o **dinámica** (su contenido varía según interacciones, usuario o datos del servidor). Una página web estática puede visualizarse localmente sin un servidor web, pero una dinámica requiere de uno.
*   Una **aplicación web** es una herramienta de software más compleja, que utiliza páginas web dinámicas (y puede incluir estáticas) y tecnologías web para proporcionar un **servicio o conjunto de servicios** al usuario. Es similar a una aplicación de escritorio, pero ejecutada en un navegador, lo que la independiza del sistema operativo cliente. Las aplicaciones web siempre requieren de un servidor web y de otros componentes.

**Tabla de Tecnologías más usadas en el lado del cliente y servidor**:

| Perfil                  | Tipo de Entorno     | Tecnología                                          | Usos comunes                                                                                                                                                                                       |
| :---------------------- | :------------------ | :-------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Front-end / Cliente** | Navegador Web       | **HTML + CSS + JavaScript**                         | Estructura, estilo e interactividad de la interfaz de usuario. Animaciones, validación de formularios, comunicación asíncrona (AJAX). Frameworks JS (React.js, Vue.js, Angular, Svelte) para SPAs. |
| **Back-end / Servidor** | Servidor Web + BBDD | **PHP, Python, Ruby, Java / JSP, .Net / .asp (C#)** | Generación de páginas dinámicas, lógica de negocio, acceso a bases de datos, APIs. JavaScript (Node.js) también es popular.                                                                        |


## 3. Arquitecturas Web

### 3.1. Aspectos Generales y Evolución de las Arquitecturas Web

Las arquitecturas web son modelos que describen la forma en que los distintos elementos que participan en el intercambio y procesamiento de información a través de Internet se relacionan y funcionan. El modelo fundamental es la **Arquitectura Cliente-Servidor**, donde uno o varios clientes (navegadores web) solicitan servicios a un servidor.

**Ventajas de la Arquitectura Cliente-Servidor**:
*   **Centralización del control**: El servidor gestiona accesos, recursos y la integridad de los datos, facilitando actualizaciones.
*   **Escalabilidad**: Se puede aumentar la capacidad de clientes y servidores por separado.
*   **Portabilidad**: La ejecución de la aplicación web en un navegador web independiza el software del sistema operativo cliente.
*   **Fácil mantenimiento**: Al distribuir las funciones y responsabilidades entre varios ordenadores independientes, es posible reemplazar, reparar, actualizar, o incluso trasladar un servidor, sin que sus clientes se vean afectados (o mínimamente). Esta independencia de los cambios también se conoce como **encapsulación**.
*   Existen **tecnologías** suficientemente desarrolladas para seguridad en transacciones, usabilidad de la interfaz y facilidad de uso.

**Desventajas de la Arquitectura Cliente-Servidor (sin técnicas de mitigación)**:
*   **Congestión del tráfico**: Puede ocurrir sobrecarga si muchos clientes envían peticiones simultáneas.
*   **Fallo del servidor**: Si el servidor cae, las peticiones no pueden ser satisfechas.
*   **Software y hardware específico**: Puede requerir soluciones específicas que aumentan el coste.
*   *Nota*: Estas desventajas se mitigan con técnicas de escalado horizontal y vertical.

![img](/images/arquitectura_cliente_servidor.png)

La web ha experimentado una notable **evolución**. Desde la **Web 1.0**, caracterizada por contenidos estáticos y escasa interacción, hemos avanzado a la **Web 1.5**, donde surgieron las primeras aplicaciones web con bases de datos y contenido dinámico. La **Web 2.0** o **Web Social** marcó la transición hacia aplicaciones centradas en el usuario final, fomentando el trabajo colaborativo, las redes sociales y el contenido generado por el usuario. También se habla de la **Web 2.5** o **Web Simbiótica**, donde los servicios web usan los datos del usuario para ofrecer contenido personalizado y anuncios. La **Web 3.0** se orienta hacia una web semántica con contenido accesible por otras aplicaciones, inteligencia artificial y una gran base de datos. Incluso se especula sobre una futura **Web 4.0**.



### 3.2. Modelos de Arquitectura Software: Monolítica, de Capas, Microservicios y Serverless

Una arquitectura de software se refiere a la estructura organizativa fundamental de un sistema de software. Define cómo se dividen, combinan y coordinan sus componentes para lograr los objetivos del sistema. En el desarrollo de aplicaciones web del lado del servidor (*backend*), existen varias arquitecturas principales.

#### 3.2.1. Monolítica, de Capas, Servicios Web, Microservicios y Serverless

*   **Arquitectura Monolítica**: Es un enfoque tradicional en el que todos los componentes de una aplicación web se agrupan en un solo bloque. La lógica de negocio, la interfaz de usuario y la capa de acceso a datos se encuentran dentro de la misma aplicación. Es fácil de desarrollar y desplegar inicialmente, pero puede volverse complejo y difícil de mantener a medida que la aplicación crece. Todos los componentes se ejecutan en el mismo proceso y comparten recursos. La escalabilidad puede ser un desafío, ya que la aplicación se ejecuta en una sola instancia. Los cambios en una parte de la aplicación pueden afectar a otras partes.
*   **Arquitectura de Capas**: Esta arquitectura divide la aplicación en diferentes capas lógicas, donde cada capa tiene una responsabilidad específica. Las capas típicas incluyen la capa de presentación, la capa de lógica de negocio y la capa de acceso a datos. Cada capa se comunica con la capa adyacente a través de interfaces bien definidas. Mejora la modularidad y la reutilización del código, permite cambios en una capa sin afectar a las demás y facilita la escalabilidad y el mantenimiento del sistema.
*   **Arquitectura de Servicios Web**: Esta arquitectura se basa en la comunicación entre diferentes servicios a través de protocolos web estándar, como HTTP. Cada servicio es una unidad independiente que se puede desarrollar, desplegar y escalar de forma independiente. Los servicios se comunican entre sí para cumplir con los requisitos de la aplicación. Favorece la modularidad y la independencia de los servicios, permite la integración de diferentes tecnologías y lenguajes de programación y facilita la escalabilidad horizontal.
*   **Arquitectura Basada en Microservicios**: Es una evolución de la arquitectura de servicios web, donde los servicios se dividen en componentes aún más pequeños y autónomos llamados microservicios. Cada microservicio se enfoca en una tarea específica y se comunica con otros microservicios a través de protocolos ligeros. Cada microservicio se puede desarrollar, desplegar y escalar de forma independiente. Mejora la flexibilidad y la agilidad del desarrollo y permite la adopción de diferentes tecnologías y enfoques dentro de cada microservicio. Un ejemplo notable es la arquitectura de *backend* de Netflix.
*   **Arquitectura Serverless**: En este modelo, el proveedor de nube gestiona toda la infraestructura del servidor, y los desarrolladores solo se preocupan por escribir el código de la aplicación. Esto ofrece escalabilidad automática y pago por uso.
*   **Service-Oriented Architecture (SOA)**: Es un enfoque de diseño de software donde los componentes del sistema se organizan como servicios independientes que se comunican entre sí a través de interfaces bien definidas. Cada servicio es una unidad autónoma que realiza una función específica y puede ser reutilizado en diferentes aplicaciones. SOA promueve la interoperabilidad, la flexibilidad y la escalabilidad al permitir que los servicios se desarrollen, desplieguen y mantengan de forma independiente.
*   **Event Driven Architecture (EDA)**: En esta arquitectura, los componentes del sistema se comunican mediante eventos. Un componente emite un evento cuando ocurre una acción significativa, y otros componentes pueden suscribirse a estos eventos para reaccionar en consecuencia. Esto permite una mayor flexibilidad y desacoplamiento entre los componentes del sistema.


![img](/images/arquitecturas_web.gif) 

**Tabla Comparativa de Arquitecturas Software**

| Característica          | **Monolítica**                              | **De Capas**                                        | **Microservicios**                                     | **Serverless**                                             |
| :---------------------- | :------------------------------------------ | :-------------------------------------------------- | :----------------------------------------------------- | :--------------------------------------------------------- |
| **Complejidad Inicial** | Baja (fácil desarrollo y despliegue)        | Media (modular, pero aún una única aplicación)      | Alta (gestión y despliegue complejos)                  | Media (abstracción, pero desafíos de monitoreo)            |
| **Escalabilidad**       | Difícil de escalar componentes individuales | Buena (facilita la escalabilidad y mantenimiento)   | Independiente por servicio (alta)                      | Automática (muy alta)                                      |
| **Resiliencia**         | Un fallo puede afectar toda la aplicación   | Un fallo en una capa afecta a su funcionalidad      | Alta (fallo de un servicio no afecta al resto)         | Alta (proveedor gestiona tolerancia a fallos)              |
| **Mantenimiento**       | Se vuelve complejo a medida que crece       | Facilita el mantenimiento                           | Flexible y ágil, fácil de actualizar individualmente   | Reducción de la administración del servidor                |
| **Flexibilidad Tec.**   | Baja (todo en una pila tecnológica)         | Baja (puede permitir diferentes lenguajes por capa) | Alta (diferentes tecnologías por microservicio)        | Muy alta (independencia tecnológica por función)           |
| **Coste**               | Puede ser bajo inicialmente                 | Moderado                                            | Puede ser más alto por complejidad de infraestructura  | Pago por uso (potencialmente bajo si el uso es esporádico) |
| **Tiempo de Desp.**     | Largos ciclos de despliegue                 | Moderados                                           | Agilidad en despliegue de pequeños cambios             | Muy rápido para funciones individuales                     |
| **Comunicación**        | En memoria (rápida)                         | En memoria o a través de interfaces bien definidas  | Mayor sobrecarga entre servicios (red)                 | Vía eventos o API Gateway (latencia de "arranque en frío") |
| **Ideal para**          | Proyectos pequeños, MVPs                    | Aplicaciones empresariales con requisitos claros    | Aplicaciones complejas, grandes empresas (ej. Netflix) | Funciones esporádicas, microservicios específicos          |

**Macroservicios vs. Microservicios vs. Serverless vs SOA vs EDA:**

El término "Macroservicios" no es una arquitectura formal, pero a menudo se usa para describir aplicaciones que, aunque modularizadas, no alcanzan la granularidad y autonomía de los microservicios, o bien para referirse a arquitecturas monolíticas grandes.

La tendencia hacia los **Microservicios** se debe a la necesidad de construir sistemas más **flexibles, escalables y resilientes** en un entorno de desarrollo ágil. Mientras que un monolito requiere escalar toda la aplicación incluso si solo una pequeña parte tiene alta demanda, los microservicios permiten escalar de forma independiente cada componente. Esto facilita que equipos pequeños trabajen de forma autónoma, elijan sus propias tecnologías y desplieguen con mayor frecuencia y menor riesgo. El fallo de un microservicio no afecta a toda la aplicación, mejorando la resiliencia. Sin embargo, esta flexibilidad viene con una **mayor complejidad de gestión y despliegue**.

**Serverless** va un paso más allá, eliminando la preocupación por los servidores. Aunque puede verse como una evolución de los microservicios, no todos los microservicios son Serverless. Serverless es ideal para funciones cortas y bajo demanda que pueden beneficiarse de la escalabilidad automática y el pago por uso, pero tiene limitaciones de tiempo de ejecución y posibles latencias de "arranque en frío".

**Service-Oriented Architecture (SOA)** es un enfoque más amplio que puede incluir microservicios, pero se centra en la interoperabilidad y la reutilización de servicios a través de una arquitectura orientada a servicios. SOA puede ser más adecuado para organizaciones grandes con sistemas heredados que necesitan integrarse.

**Event Driven Architecture (EDA)** es un enfoque que puede complementar tanto a los microservicios como a las arquitecturas Serverless. En EDA, los componentes del sistema reaccionan a eventos, lo que permite una mayor flexibilidad y desacoplamiento. Esto es especialmente útil en sistemas distribuidos donde la comunicación asíncrona puede mejorar la escalabilidad y la resiliencia.


#### 3.2.2. Modelo-Vista-Controlador (MVC)

El **Modelo-Vista-Controlador (MVC)** es un modelo de arquitectura que separa los datos y la lógica de negocio de la interfaz de usuario y el componente encargado de gestionar los eventos y las comunicaciones.

Al separar los componentes en elementos conceptuales permite reutilizar el código y mejorar su organización y mantenimiento. Sus elementos son:
*   **Modelo**: representa la información y gestiona todos los accesos a ésta, tanto consultas como actualizaciones provenientes, normalmente, de una base de datos. Se accede via el controlador.
*   **Controlador**: Responde a las acciones del usuario, y realiza peticiones al Modelo para solicitar información. Tras recibir la respuesta del modelo, le envía los datos a la Vista.
*   **Vista**: Presenta al usuario de forma visual el Modelo y los datos preparados por el Controlador. El usuario interactura con la Vista y realiza nuevas peticiones al Controlador.

En este modelo, es el servidor el que lleva el peso principal tanto del procesado de la información como de su representación. El cliente web se dedica a enviar las peticiones al servidor, recibir la respuesta y representarla en pantalla. La página web (código HTML, JavaScript, etc.) se predetermina en el lado del servidor. Con este modelo, cada petición del cliente al servidor implicará un refresco de la información que se visualiza en la pantalla, aunque su apariencia haya cambiado poco. Esto implica que se vuelvan a descargar todos los datos y ficheros que no se mantengan en la caché del navegador, con lo que los tiempos de respuesta serán mayores. El usuario final apreciará que, por un intervalo corto de tiempo, todos los elementos de la pantalla desaparecen y después se conforma de nuevo la interfaz de usuario. En este caso, se dice que la aplicación no es **reactiva**. Este modelo de programación MVC se ajustará al primer proyecto del curso.

![img](/images/mvc.jpeg)


### 3.3. Patrones de Diseño Introductorios

Los patrones de diseño son soluciones generalmente aplicables a problemas comunes en el diseño de software. Proporcionan un enfoque probado y estructurado para resolver problemas recurrentes y mejorar la calidad y flexibilidad del código.
*   Los **Principios SOLID** son cinco principios que guían el diseño de software orientado a objetos para crear sistemas más robustos, mantenibles y escalables:
    1.  **Principio de responsabilidad única (SRP)**: Una clase debe tener una, y solo una, razón para cambiar.
    2.  **Principio abierto/cerrado (OCP)**: Las entidades de software deben estar abiertas para la extensión, pero cerradas para la modificación.
    3.  **Principio de sustitución de Liskov (LSP)**: Los objetos de una superclase deben poder ser reemplazados por objetos de una subclase sin afectar la corrección del programa.
    4.  **Principio de segregación de interfaces (ISP)**: Los clientes no deben ser forzados a depender de interfaces que no usan.
    5.  **Principio de inversión de dependencias (DIP)**: Los módulos de alto nivel no deben depender de los módulos de bajo nivel; ambos deben depender de abstracciones.
*   Existen otros **Tipos de Patrones de Diseño** que se clasifican en patrones de creación (cómo se instancian los objetos), estructurales (cómo se componen las clases y objetos), de comportamiento (cómo interactúan los objetos) y arquitectónicos (estructuras globales de las aplicaciones, como MVC o Microservicios).

![img](/images/solid.gif) 

## 4. El Protocolo HTTP y HTTPS

### 4.1. Características y Ventajas del Protocolo HTTP

El **Protocolo HTTP (HyperText Transfer Protocol)** es la base de la comunicación en la World Wide Web. Es un protocolo **no orientado a la conexión**, lo que significa que cada petición entre cliente y servidor es independiente y no requiere mantener una conexión continua.

Sus principales **características** son:
*   **Sencillo**: Es en modo texto y fácil de usar directamente por una persona.
*   **Extensible**: Se pueden enviar más metadatos que los que están por defecto.
*   **Sin estado**: Cada petición es independiente. Esto es un problema para sitios como un carrito de la compra, pero se soluciona con *cookies* y sesiones.

HTTP es fundamental en arquitecturas distribuidas como los microservicios y es la base para la creación de APIs REST. Ofrece ventajas como la mejora de la velocidad al controlar la **caché** de las páginas, la **autenticación** de usuarios, el uso transparente de **proxies** y el mantenimiento del estado entre peticiones gracias a las **sesiones**. También permite indicar el formato de lo que se envía, pide y retorna.


### 4.2. Formato de Peticiones y Respuestas HTTP

La interacción en la web se basa en un intercambio constante de peticiones y respuestas HTTP entre el navegador del cliente y el servidor.
Una **petición HTTP** tiene una primera línea que incluye el método (ej. GET), la ruta del recurso solicitado (ej. `/index.html`), y la versión del protocolo (ej. `HTTP/1.1`), seguida de varias líneas con cabeceras que proporcionan metadatos.
La **respuesta HTTP** del servidor comienza con la versión del protocolo (ej. `HTTP/1.1`), seguida de un código de estado (ej. `200 OK`) y un texto que indica el resultado de la operación. Después de una línea vacía, se incluye el contenido del recurso solicitado (ej. HTML).

![img](/images/http.png)


### 4.3. Cabeceras HTTP

Las cabeceras HTTP son mensajes adicionales que se envían tanto en las peticiones como en las respuestas para proporcionar información clave sobre la comunicación.
**Cabeceras de Petición Comunes**:
*   `Accept`: El formato MIME type en el que se quieren los datos (ej., `text/html`, `application/json`).
*   `Accept-Language`: El idioma preferido para la respuesta (ej., `fr`).
*   `Host`: El dominio al que se dirige la petición, muy útil para alojar varios dominios en un mismo servidor.
*   `Content-Type`: Describe el formato y la codificación de los datos que se envían en el cuerpo de la petición.
*   `Content-Length`: Tamaño en bytes de los datos que se envían.
*   `User-Agent`: Información sobre el navegador del cliente.

**Cabeceras de Respuesta Comunes**:
*   `Content-Type`: El formato y la codificación de los datos que se retornan (ej., `text/html; charset=utf-8`), crucial para que el navegador interprete correctamente el contenido.
*   `Content-Language`: El idioma de los datos que se retornan.
*   `Content-Length`: Tamaño en bytes de los datos que se retornan.
*   `Cache-Control`: Cuánto tiempo pueden estar cacheados los datos.
*   `Server`: Indica información del servidor (ej. Apache/2.2.3).


### 4.4. Métodos/Verbos HTTP (GET, POST, PUT, DELETE, HEAD)

Los métodos HTTP, también llamados verbos, definen la acción que un cliente desea realizar sobre un recurso en el servidor.
*   **GET**: Se utiliza para **obtener** o recuperar un recurso. Generalmente, no se envían datos en el cuerpo de la petición; cualquier parámetro se adjunta a la URL como una cadena de consulta (*query string*).
*   **POST**: Se usa para **añadir** un nuevo recurso o **enviar** datos al servidor. Los datos se incluyen en el cuerpo de la petición, después de las cabeceras, y no son visibles en la URL.
*   **PUT**: Se utiliza para **actualizar** o **reemplazar** completamente un recurso existente en el servidor con los datos proporcionados.
*   **DELETE**: Se usa para **borrar** un recurso o entidad específica del servidor.
*   **HEAD**: Solicita las mismas cabeceras de respuesta que un método GET, pero sin el cuerpo de la respuesta. Es útil para verificar la existencia de un recurso o sus metadatos sin descargar el contenido completo.

![img](/images/http-metodos.gif)

### 4.5. Códigos de Estado HTTP

Después de cada petición, el servidor envía una respuesta que incluye un código de estado HTTP. Este código es un número de tres dígitos que indica el resultado y el estado de la petición.
*   **1XX (Informativas)**: La petición ha sido recibida y el proceso continúa.
*   **2XX (Éxito)**: La acción del cliente fue recibida, entendida y aceptada. Por ejemplo, **200 OK** indica que la petición se ha procesado correctamente.
*   **3XX (Redirección)**: El cliente necesita realizar una acción adicional para completar la petición (ej., el recurso se ha movido).
*   **4XX (Error del Cliente)**: La petición contiene un error o no puede ser completada debido a un problema en el lado del cliente (ej. **403 Forbidden**, **404 Not Found**).
*   **5XX (Error del Servidor)**: El servidor falló al completar una petición aparentemente válida.

![img](/images/status-code.png)

### 4.6. El Protocolo HTTPS (SSL/TLS y Certificados Digitales)

**HTTPS** (HyperText Transfer Protocol Secure) es la versión segura del protocolo HTTP, esencial para la transferencia confidencial y segura de información entre el cliente y el servidor. A diferencia de HTTP, que transmite datos en texto claro y vulnerable a la intercepción, HTTPS **cifra** la información, asegurando su privacidad.

La seguridad en HTTPS se basa en el uso de **certificados digitales**. Estos documentos electrónicos vinculan una clave pública a la identidad de un propietario (servidor web). Son emitidos por **Autoridades de Certificación (AC)**, que son entidades de confianza que firman digitalmente los certificados para validar su autenticidad. Los navegadores web confían en estas AC y alertan al usuario si un certificado no es válido, está autofirmado o no coincide con el sitio, lo que puede generar advertencias de seguridad.

El proceso de cifrado utiliza el **cifrado de clave pública o asimétrico**. El navegador cifra la información con la clave pública del servidor, y solo el servidor, con su clave privada correspondiente, puede descifrarla, garantizando así la confidencialidad. Los protocolos **SSL/TLS** (Secure Sockets Layer/Transport Layer Security) son los estándares criptográficos que hacen posibles estas conexiones seguras, proporcionando autenticación y privacidad. El cifrado requiere recursos computacionales, lo que puede tener un impacto mínimo en el rendimiento del servidor web. HTTP y HTTPS pueden convivir en un mismo dominio.


## 5. Servicio Web y Comunicación con APIs

### 5.1. ¿Qué es un Servicio Web y Qué Aporta?

Un **servicio web** (o Web Service) es una **API (Application Programming Interface)** que permite a otra aplicación comunicarse remotamente para acceder a un servicio. Son conjuntos de reglas y protocolos que permiten a diferentes aplicaciones o sistemas comunicarse y compartir datos a través de la web. Se basan en protocolos web estándar como HTTP y utilizan formatos de intercambio de datos como JSON o XML. Cada funcionalidad o servicio expuesto por una API se identifica a menudo mediante un *endpoint* (URL en el lado servidor).

Los servicios web son **fundamentales en el desarrollo de aplicaciones modernas**. Aportan:
*   **Integración**: Permiten que diferentes sistemas se conecten y compartan funcionalidades, como una aplicación de escritorio publicando en Twitter vía su API.
*   **Flexibilidad y Escalabilidad**: Facilitan la creación de aplicaciones más robustas y escalables al dividir funcionalidades en servicios independientes.
*   **Reutilización**: Un servicio puede ser consumido por múltiples clientes (web, móvil, escritorio).
*   **Agnosticismo**: El Back-end se vuelve agnóstico al cliente, entregando datos que cada cliente representa a su manera.


### 5.2. Diferencia entre un Servicio Web y una Página Web Dinámica

La distinción entre un servicio web y una página web dinámica radica en su propósito y la naturaleza de su interacción:
*   Una **página web dinámica** está diseñada para **generar contenido HTML (u otros formatos interpretables por un navegador)** que el usuario final visualiza en su navegador. Su objetivo principal es la presentación y la interacción directa con el usuario a través de una interfaz gráfica.
*   Un **servicio web (API)**, por el contrario, está diseñado para **exponer datos y funcionalidades** a *otras aplicaciones*, no directamente a usuarios finales a través de una interfaz gráfica. Aunque se accede vía HTTP, su respuesta no es una página HTML para el usuario, sino **datos estructurados** (JSON, XML) que otras aplicaciones consumen para luego mostrarlos o procesarlos. Es el "lenguaje" que hablan las máquinas entre sí.

En una arquitectura moderna, una página web dinámica (especialmente una SPA) puede consumir múltiples servicios web para construir su interfaz y obtener datos, mientras que los servicios web actúan como el *backbone* de datos para esta y otras aplicaciones.

![img](/images/api_portada.jpg)

### 5.3. Protocolos de Comunicación de API

La elección del protocolo de comunicación de API adecuado es una decisión arquitectónica crítica que impactará el rendimiento, la escalabilidad, la experiencia del usuario e incluso los costes del proyecto. Comprender las fortalezas y debilidades de los diferentes protocolos es esencial.


![img](/images/apis.gif)

**Tabla Comparativa de Protocolos de Comunicación de API**

| Protocolo/Estilo | **Descripción**                                                                                                                                                      | **Formato Datos**           | **Comunicación**                                                                                                                                      | **Ventajas**                                                                                                                                                                                                                               | **Desventajas**                                                                                                                                                   | **Uso Ideal**                                                                                                                                                                           |
| :--------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **REST**         | Estilo arquitectónico basado en HTTP para operaciones CRUD (Crear, Leer, Actualizar, Borrar) sobre recursos. Los recursos se identifican mediante URLs.              | JSON (principalmente), XML. | Peticiones HTTP estándar (GET, POST, PUT, DELETE).                                                                                                    | Sencillo y familiar, amplia compatibilidad, escalable, sin estado (facilita escalabilidad), fácil de almacenar en caché HTTP, acoplamiento flexible.                                                                                       | Puede haber sobre-obtención o sub-obtención de datos (requiere múltiples peticiones para datos relacionados), sin un esquema estándar estricto para consistencia. | APIs públicas, operaciones CRUD, microservicios simples.                                                                                                                                |
| **GraphQL**      | Lenguaje de consulta y una especificación para APIs web. Permite a los clientes solicitar **exactamente los datos que necesitan** en una sola petición.              | JSON (para respuestas).     | Peticiones HTTP POST, con la consulta GraphQL en el cuerpo.                                                                                           | Recuperación muy eficiente de datos (evita sobre/sub-obtención), reduce la necesidad de múltiples viajes al servidor, tipado fuerte a través de esquemas, empodera al cliente.                                                             | Complejidad en el lado del servidor (gráficos, no recursos), dificultad para *caching* HTTP tradicional, posible problema de consulta N+1.                        | Aplicaciones complejas con interfaces de usuario exigentes (ej., paneles, *feeds* sociales), clientes móviles con ancho de banda limitado, equipos *frontend*/*backend* independientes. |
| **gRPC**         | Marco de **Llamada a Procedimiento Remoto (RPC)** moderno y de alto rendimiento, desarrollado por Google. Permite llamar a funciones remotas como si fueran locales. | Protocol Buffers (binario). | Se basa en HTTP/2.                                                                                                                                    | Extremadamente rápido y eficiente (serialización binaria Protobuf), bajo latencia, hereda beneficios de HTTP/2 (multiplexación, compresión), contratos fuertemente tipados con `.proto`, excelente soporte para *streaming* bidireccional. | Menos legible para humanos, requiere un proxy gRPC-web para navegadores, curva de aprendizaje más pronunciada (Protobuf, RPC).                                    | Comunicación interna de microservicios, servicios de *streaming* en tiempo real, entornos políglotas donde el rendimiento es crítico (servicios financieros, juegos).                   |
| **WebSocket**    | Protocolo de comunicación que proporciona canales de comunicación **persistentes, bidireccionales y en tiempo real** a través de una única conexión TCP.             | JSON, Texto, Binario.       | Después de un "apretón de manos" HTTP inicial, se establece una conexión persistente. Cliente y servidor pueden enviar mensajes en cualquier momento. | Verdadero tiempo real (chat en vivo, notificaciones, *feeds* en vivo), eficiente (elimina sobrecarga HTTP repetida), comunicación full-duplex simultánea.                                                                                  | Conexión con estado (escalabilidad horizontal más compleja), no encaja en el modelo CRUD típico, configuración compleja de proxy y balanceador de carga.          | Aplicaciones en tiempo real: chats, actualizaciones deportivas en vivo, herramientas de edición colaborativa, paneles de control en tiempo real, juegos multijugador.                   |
| **SOAP**         | Protocolo de mensajería basado en **XML** para el intercambio de información estructurada en servicios web. Es más antiguo y formal que REST.                        | XML.                        | Peticiones HTTP POST con mensajes XML estructurados. Puede operar sobre varios protocolos de transporte.                                              | Altamente estandarizado y extensible (WS-Security, WS-AtomicTransaction), independiente del lenguaje y la plataforma, manejo de errores incorporado.                                                                                       | Verboso y pesado debido al XML, complejo de implementar y trabajar con él, menos legible para humanos que JSON.                                                   | Grandes empresas, instituciones financieras y sistemas heredados donde los contratos formales y las características de seguridad avanzadas son críticas.                                |


#### 5.3.6. Otros Protocolos y Estilos de Comunicación (mención breve)

Existen otros protocolos y estilos de comunicación que se adaptan a necesidades específicas:
*   **Webhook**: Mecanismo de *callback* HTTP que permite a un servicio enviar notificaciones en tiempo real a una URL preconfigurada cuando ocurre un evento específico.
*   **MQTT (Message Queuing Telemetry Transport)**: Protocolo ligero de publicación-subscripción diseñado para dispositivos con recursos limitados y redes de bajo ancho de banda. Es el estándar para IoT.
*   **Server-Sent Events (SSE)**: Estándar que permite a un servidor enviar actualizaciones unidireccionales de texto a un cliente a través de HTTP. Más simple que WebSocket para flujos unidireccionales.
*   **Apache Kafka**: Plataforma distribuida de *streaming* de eventos que sirve como columna vertebral para arquitecturas modernas basadas en eventos, permitiendo el procesamiento de grandes volúmenes de datos en tiempo real.


### 5.4. JWT (JSON Web Token) - Concepto de Autenticación y Autorización

Un **JSON Web Token (JWT)** es un estándar abierto para crear tokens de acceso que permiten intercambiar información de forma segura entre dos partes como un objeto JSON firmado digitalmente. Son ampliamente utilizados para la autenticación y autorización en APIs web modernas.

Un JWT consta de tres partes separadas por puntos:
1.  **Header (Encabezado):** Contiene el tipo de token (JWT) y el algoritmo de firma utilizado (por ejemplo, HMAC SHA256).
2.  **Payload (Carga Útil):** Contiene las "reclamaciones" (*claims*), que son declaraciones sobre una entidad (normalmente el usuario) y otros datos. Pueden ser reclamaciones registradas (como el emisor o la fecha de expiración), públicas (información personalizada) o privadas (acordadas entre las partes).
3.  **Signature (Firma):** Se crea tomando el encabezado y el *payload* (ambos codificados en Base64Url), uniéndolos y luego firmando la cadena resultante con el algoritmo especificado en el Header y una clave secreta. La firma garantiza que el token no ha sido alterado.

La estructura final de un JWT es una cadena compacta que representa estas tres partes codificadas. Se utilizan para que el servidor pueda verificar la identidad de un usuario en peticiones posteriores sin tener que consultar repetidamente una base de datos de sesiones, mejorando la eficiencia y la escalabilidad.

![img](/images/jwt-structure.png)

### 5.5. Ejemplo de arquitectura Netflix

Netflix utiliza una arquitectura orientada a **microservicios** que les permite separar su plataforma en servicios pequeños e independientes. Esto mejora la escalabilidad, la disponibilidad y la fiabilidad de la plataforma. 

* **Microservicios**: Cada función, como la autenticación de usuarios, la gestión de perfiles o las recomendaciones de contenido, se ejecuta como un servicio individual. Esto permite que los equipos de desarrollo trabajen y desplieguen servicios de forma independiente.
* **Basado en la nube**: Netflix migró completamente a **Amazon Web Services (AWS)**, lo que le permite escalar recursos de forma dinámica según la demanda.
* **Open Connect**: Es su propia red de distribución de contenido (CDN) global. Este sistema almacena copias del contenido de Netflix en servidores locales de los proveedores de servicios de internet (ISP) para acercar el contenido a los usuarios, reduciendo la latencia y la carga en la red.
**Tecnologías Front-end**

El front-end de Netflix es la interfaz de usuario con la que los suscriptores interactúan, y se centra en una experiencia de usuario (UX) fluida y personalizada.

* **Lenguajes y frameworks**:
    * **JavaScript y React**: El sitio web y las aplicaciones para Smart TVs utilizan JavaScript, en su mayoría con la biblioteca **React**, para construir componentes y páginas de manera eficiente.
    * **HTML y CSS**: Son la base para la estructura y el diseño visual de la interfaz.

**Tecnologías Back-end**

El back-end es el cerebro de la plataforma, encargado de la lógica del negocio, el manejo de datos y el procesamiento de contenido.

* **Lenguajes de programación**:
    * **Java**: Es el lenguaje principal para la mayoría de los microservicios. Su rendimiento, escalabilidad y robustez lo hacen ideal para el núcleo de la arquitectura.
    * **Python**: Se utiliza para tareas específicas, como el análisis de datos, el aprendizaje automático para el sistema de recomendaciones y la automatización de procesos.
* **Bases de datos**:
    * **Apache Cassandra (NoSQL)**: Se usa para manejar grandes volúmenes de datos distribuidos, como la actividad de visualización de los usuarios, que requiere alta disponibilidad y un rendimiento de lectura/escritura muy rápido.
    * **MySQL**: Se utiliza para datos que requieren la consistencia de una base de datos relacional, como la facturación y los pagos.
* **APIs**: La comunicación entre los servicios y el front-end se realiza a través de **APIs (Interfaces de Programación de Aplicaciones)** que permiten un intercambio de datos constante y eficiente.
* **Codificación de video**: Cuando el contenido es subido, el back-end lo procesa y lo codifica en múltiples formatos y resoluciones (4K, HD, etc.) para que pueda ser entregado a cualquier dispositivo, en cualquier calidad de conexión.


![img](/images/netflix-2.gif)

## 6. Funcionamiento de una Web Dinámica y Generación de Contenido

### 6.1. Páginas estáticas vs. Páginas dinámicas
La principal diferencia entre una página web estática y una dinámica radica en cómo y cuándo se genera el contenido. Una página estática es como un documento fijo que siempre muestra el mismo contenido, mientras que una dinámica se construye en tiempo real para cada visitante, adaptándose a sus necesidades o interacciones.

**Páginas Web Estáticas** 

Son páginas que están compuestas por archivos predefinidos (HTML, CSS, JavaScript) que se almacenan directamente en el servidor. Cuando un usuario solicita la página, el servidor simplemente envía esos archivos tal como están, sin ningún procesamiento adicional.

* **Contenido fijo**: El contenido es el mismo para todos los usuarios, a menos que un desarrollador edite manualmente los archivos.
* **Velocidad**: Son muy rápidas de cargar porque no requieren procesamiento en el servidor ni consultas a bases de datos.
* **Tecnologías**: Utilizan principalmente lenguajes del lado del cliente como **HTML**, **CSS** y **JavaScript**.
* **Uso común**: Ideales para sitios sencillos y de pocas páginas, como blogs personales, portfolios o páginas de presentación de empresas.
* **Desventajas**: Tienen funcionalidad limitada, no permiten la interacción del usuario y su actualización es manual y laboriosa.

**Páginas Web Dinámicas**

Son páginas que se generan en el momento en que un usuario las solicita. El servidor procesa la petición, ejecuta código del lado del servidor, se conecta a una base de datos para obtener información y luego genera el HTML final que se envía al navegador del usuario.

* **Contenido variable**: El contenido puede cambiar según el usuario (ej. un saludo personalizado), la hora, la ubicación o las interacciones (ej. un carrito de compras).
* **Interactividad**: Permiten funciones complejas como formularios de contacto, inicio de sesión, carritos de compra, foros y sistemas de comentarios.
* **Tecnologías**: Requieren lenguajes de programación del lado del servidor como **PHP**, **Python** (con frameworks como Django o Flask), **Java** (JSP, Spring) o **Node.js**, además de bases de datos como MySQL o PostgreSQL.
* **Uso común**: Perfectas para sitios grandes y complejos como redes sociales (Facebook), tiendas en línea (Amazon), plataformas de video (YouTube) o cualquier sitio que necesite gestionar información de usuarios.
* **Desventajas**: Requieren más recursos del servidor, son más complejas de desarrollar y mantener, y pueden ser más lentas de cargar si no están bien optimizadas.

### 6.2. Cómo Funciona una Página Web Dinámica

Las páginas web dinámicas se caracterizan por su contenido variable, que se genera "sobre la marcha" en el servidor en función de diversas condiciones, como el usuario, sus acciones o los datos disponibles en una base de datos.

El proceso de funcionamiento es el siguiente:
1.  **El cliente web (navegador) solicita una página web al servidor web**.
2.  **El servidor web recibe la petición HTTP**. Si se trata de una página estática, el servidor simplemente la envía. Si es dinámica, el servidor no tiene la página almacenada en su forma final.
3.  **El servidor web contacta con el módulo responsable de ejecutar el código dinámico** y le envía la petición. Este módulo puede ser interno (ej. `mod_php` en Apache) o un servidor de aplicaciones externo (ej. Tomcat para Java).
4.  **El módulo de ejecución procesa el código (script)**. Como parte de este proceso, puede ser necesario obtener información de un repositorio, como una base de datos. Por ejemplo, en PHP, el código entre las etiquetas `<?php` y `?>` se ejecuta en el servidor.
5.  **El resultado de esta ejecución es una página en formato HTML**, que es el contenido que se devolverá al navegador. El servidor web integra este contenido HTML dinámicamente generado con cualquier parte estática de la página.
6.  **El servidor web envía esta página HTML resultante al navegador**, que la procesa y la muestra en pantalla.

![img](/images/What-can-be-Static-or-Dynamic_.webp)

![img](/images/03_how_dynamic_websites_work.webp)

Este dinamismo permite que, por ejemplo, una bandeja de entrada de correo electrónico muestre mensajes distintos para cada usuario, obteniendo sus datos de la base de datos y componiendo la página de forma personalizada. La ejecución del código en el lado del servidor, al operar entre las marcas (`<?php ... ?>`, `<% ... %>`), permite que se genere el contenido variable de la web, que luego se combina con el HTML estático para mostrar la página final correctamente en el navegador.


### 6.3. Tecnologías de Generación de Páginas Web Dinámicas y Ejemplos "Hola Mundo"

Las principales tecnologías para generar páginas web dinámicas utilizan la integración de lenguajes de programación del lado del servidor con lenguajes de marcado como HTML.

**Tabla Comparativa de Tecnologías de Generación de Páginas Web Dinámicas**

| Característica           | **PHP con Laravel**                                                                            | **Java con JSP**                                                              | **Java con Spring Boot**                                                                  | **C# con ASP.NET Core**                                                         | **Python con Django**                                                                |
| :----------------------- | :--------------------------------------------------------------------------------------------- | :---------------------------------------------------------------------------- | :---------------------------------------------------------------------------------------- | :------------------------------------------------------------------------------ | :----------------------------------------------------------------------------------- |
| **Lenguaje Base**        | PHP                                                                                            | Java                                                                          | Java                                                                                      | C# o Visual Basic .NET                                                          | Python                                                                               |
| **Framework/Tecnología** | Laravel (framework), PHP (lenguaje de *scripting*).                                            | JSP (JavaServer Pages) y Servlets.                                            | Spring Boot (framework), a menudo con motores de plantillas como Thymeleaf.               | ASP.NET Core (framework).                                                       | Django (framework).                                                                  |
| **Paradigma**            | Código embebido en HTML. Laravel sigue MVC.                                                    | Código Java embebido en HTML (JSP); Servlets generan HTML programáticamente.  | Basado en MVC, con enfoque en APIs RESTful y microservicios.                              | Basado en MVC.                                                                  | Basado en MVC.                                                                       |
| **Ejecución Servidor**   | Intérprete PHP (ej. `mod_php` en Apache o phpFPM con Nginx).                                   | Servidor de aplicaciones (ej. Tomcat), que compila JSP a Servlets.            | Servidor web embebido (Tomcat, Jetty) o externo (Apache/Nginx como *reverse proxy*).      | Servidor web (IIS en Windows) o auto-alojado.                                   | Servidor web (Apache con `mod_wsgi` o Nginx con Gunicorn).                           |
| **Características**      | Fácil aprendizaje, gran comunidad, ideal para pequeñas-medianas aplicaciones, código embebido. | Robustez, escalabilidad, amplia base de librerías, uso combinado Servlet/JSP. | Minimiza configuración, servidores embebidos, desarrollo rápido de microservicios y APIs. | Multiplataforma, alto rendimiento, modular, de código abierto, ecosistema .NET. | Legibilidad, "baterías incluidas" (ORM, admin), muy completo para desarrollo rápido. |

**Ejemplos de "Hola Mundo":**

*   **PHP (con código embebido en HTML)**:
    ```php
    <!DOCTYPE html>
    <html lang="es">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Hola Mundo PHP</title>
    </head>
    <body>
        <?php
            // El código PHP entre <?php y ?> se ejecuta en el servidor.
            // La función echo envía su argumento como parte del HTML al navegador.
            echo "<h1>Hola Mundo desde PHP</h1>";
        ?>
        <p>Esta es una página generada dinámicamente por PHP.</p>
        <?php
            $nombre = "Alumno";
            echo "<p>Bienvenido, " . $nombre . "!</p>";
        ?>
    </body>
    </html>
    ```

*   **Java con JSP (JavaServer Pages)**:
    ```jsp
    <!DOCTYPE html>
        <html>
        <head>
            <title>Ejemplo JSP</title>
        </head>
        <body>
            <h1>Hola, Mundo desde JSP</h1>
            
            <%
                String nombre = "Usuario";
                boolean mostrarSaludo = true;
            %>

            <% if (mostrarSaludo) { %>
                <p>¡Hola, <%= nombre %>!</p>
            <% } else { %>
                <p>No se muestra el saludo.</p>
            <% } %>

            <p>Conteo del bucle:</p>
            <ul>
            <% for (int i = 0; i < 5; i++) { %>
                <li>Ítem número <%= i %></li>
            <% } %>
            </ul>
        </body>
        </html>
    ```
    *Nota: Las páginas JSP se suelen compilar en Servlets la primera vez que se ejecutan, lo que las hace muy eficientes para la generación dinámica.*

*   **Java con Spring Boot (Controlador simple que devuelve una cadena HTML)**:
    ```java
      import org.springframework.web.bind.annotation.GetMapping;
      import org.springframework.web.bind.annotation.RestController;

      @RestController
      public class HelloController {

          @GetMapping("/hello")
          public String hello() {
              StringBuilder html = new StringBuilder();
              html.append("<!DOCTYPE html>");
              html.append("<html>");
              html.append("<head>");
              html.append("<title>Ejemplo Spring Boot</title>");
              html.append("</head>");
              html.append("<body>");
              html.append("<h1>Hola, Mundo desde Spring Boot</h1>");

              String nombre = "Usuario";
              boolean mostrarSaludo = true;

              if (mostrarSaludo) {
                  html.append("<p>¡Hola, ").append(nombre).append("!</p>");
              } else {
                  html.append("<p>No se muestra el saludo.</p>");
              }

              html.append("<p>Conteo del bucle:</p>");
              html.append("<ul>");
              for (int i = 0; i < 5; i++) {
                  html.append("<li>Ítem número ").append(i).append("</li>");
              }
              html.append("</ul>");
              html.append("</body>");
              html.append("</html>");

              return html.toString();
          }
      }
    ```
    *Nota: Spring Boot a menudo utiliza un servidor web embebido (como Tomcat o Jetty) y es ideal para crear APIs REST. En este ejemplo, el controlador devuelve una cadena HTML directamente. Para aplicaciones más complejas, se integrarían motores de plantillas como Thymeleaf o JSP.*

*   **C# con ASP.NET Core (Razor Pages)**:
    ```cshtml
        @page
        @{
            ViewData["Title"] = "Ejemplo ASP.NET Core";
            string nombre = "Usuario";
            bool mostrarSaludo = true;
            List<int> numeros = new List<int> { 0, 1, 2, 3, 4 };
        }

        <!DOCTYPE html>
        <html>
        <head>
            <title>@ViewData["Title"]</title>
        </head>
        <body>
            <h1>Hola, Mundo desde ASP.NET Core</h1>

            @if (mostrarSaludo)
            {
                <p>¡Hola, @nombre!</p>
            }
            else
            {
                <p>No se muestra el saludo.</p>
            }

            <p>Conteo del bucle:</p>
            <ul>
            @foreach (var numero in numeros)
            {
                <li>Ítem número @numero</li>
            }
            </ul>
        </body>
        </html>
    ```
    *Nota: Este es un ejemplo para una Razor Page (`.cshtml`) en ASP.NET Core, donde `@page` indica que es una página y los bloques `@` permiten incrustar código C# o acceder a variables que se ejecutan en el servidor. ASP.NET Core puede usar IIS o auto-alojarse.*

*   **Python con Django (plantilla y vista)**:
    *   **En el archivo `views.py` (controlador):**
        ```python
          from django.shortcuts import render

          def hello_world(request):
              context = {
                  'nombre': 'Usuario',
                  'mostrar_saludo': True,
                  'numeros': range(5)
              }
              return render(request, 'myapp/hello.html', context)
        ```
    *   **En la plantilla `myapp/templates/myapp/hello.html` (vista):**
        ```html
        <!DOCTYPE html>
          <html>
          <head>
              <title>Ejemplo Django</title>
          </head>
          <body>
              <h1>Hola, Mundo desde Django</h1>

              {% if mostrar_saludo %}
                  <p>¡Hola, {{ nombre }}!</p>
              {% else %}
                  <p>No se muestra el saludo.</p>
              {% endif %}

              <p>Conteo del bucle:</p>
              <ul>
              {% for numero in numeros %}
                  <li>Ítem número {{ numero }}</li>
              {% endfor %}
              </ul>
          </body>
          </html>
        ```
    *Nota: Django sigue el patrón MVC. La función `hello_world` en `views.py` actúa como controlador, que a su vez renderiza la plantilla `hello.html` (la vista) con el contexto proporcionado. Las dobles llaves `{{ variable }}` son las etiquetas de plantilla de Django para mostrar datos dinámicos.*


## 7. Lenguajes y Frameworks de Programación en Entorno Servidor

### 7.1. Tipos de Ejecución de Lenguajes del Lado del Servidor

Los lenguajes de programación utilizados en el lado del servidor se ejecutan de diferentes maneras. Debemos distinguir tres grandes grupos:
*   **Lenguajes de Guiones (Scripting)**: Los programas se ejecutan directamente a partir de su código fuente. Un intérprete procesa el código línea por línea y genera la respuesta. Pertenecen a este grupo Perl, Python, PHP y ASP (el precursor de ASP.NET). Tienen la ventaja de que no es necesario traducir el código fuente para ser ejecutados, lo que aumenta su portabilidad, pero ofrecen un rendimiento inferior.
*   **Lenguajes Compilados a Código Nativo**: El código fuente se traduce completamente a código máquina antes de la ejecución. Los programas se almacenan en modo binario y se ejecutan directamente. Son los más rápidos, pero presentan problemas de integración con el servidor web, ya que no están pensados para ejecutarse en este entorno. No son portables entre distintas plataformas y no reutilizan procesos para atender a varias peticiones.
*   **Lenguajes Compilados a Código Intermedio**: El código fuente se compila a un formato intermedio que luego es ejecutado por una máquina virtual. Operan de esta forma Java EE (Servlets, JSP) y ASP.NET. Ofrecen un equilibrio entre buen rendimiento y portabilidad entre distintas plataformas en las que exista una implementación de la arquitectura (como un contenedor de *servlets* o un servidor de aplicaciones Java EE).


### 7.2. Plataformas Web Libres y Propietarias

Una plataforma web es el entorno de desarrollo de software empleado para diseñar y ejecutar un sitio web. Generalmente, se compone de cuatro elementos clave:
1.  El **sistema operativo**: Bajo el cual opera el equipo donde se hospedan las páginas web y que representa la base misma del funcionamiento del computador. En ocasiones limita la elección de otros componentes.
2.  El **servidor web**: Es el software que maneja las peticiones desde equipos remotos a través de Internet. En el caso de páginas estáticas, el servidor web simplemente provee el archivo solicitado, el cual se muestra en el navegador. En el caso de sitios dinámicos, el servidor web se encarga de pasar las solicitudes a otros programas que puedan gestionarlas adecuadamente.
3.  El **gestor de bases de datos**: Se encarga de almacenar sistemáticamente un conjunto de registros de datos relacionados para ser usados posteriormente.
4.  Un **lenguaje de programación interpretado**: Que controla las aplicaciones de software que corren en el sitio web.

Algunas plataformas populares incluyen:
*   **LAMP**: Combina **L**inux, **A**pache, **M**ySQL (o MariaDB) y **P**HP/Perl/Python. Es una plataforma de código abierto muy difundida.
*   **WISA**: Integra **W**indows, **I**IS (Internet Information Services), **S**QL Server y **A**SP/ASP.NET. Es una plataforma propietaria de Microsoft.
*   **WAMP**: Consiste en **W**indows, **A**pache, **M**ySQL y **P**HP. Es una configuración común para entornos de desarrollo local, a menudo facilitada por paquetes como XAMPP.
*   **WIMP**: Otra combinación para Windows, con **W**indows, **I**IS, **M**ySQL y **P**HP.


### 7.3. Tecnologías para el Desarrollo de Servicios

El desarrollo de servicios se centra en la creación de APIs para que las aplicaciones se comuniquen. Las tecnologías varían según el lenguaje y el paradigma de la API.

**Tabla Comparativa de Tecnologías para el Desarrollo de Servicios**

| Tecnología                  | Lenguaje   | Uso Principal                                                                       | Ejemplos de Frameworks/Librerías                         |
| :-------------------------- | :--------- | :---------------------------------------------------------------------------------- | :------------------------------------------------------- |
| **Java con Spring Boot**    | Java       | APIs RESTful, microservicios, aplicaciones web de alta escala, *enterprise*.        | Spring MVC, Spring WebFlux, Spring Data REST, Hibernate. |
| **C# con ASP.NET Core**     | C#         | APIs RESTful, microservicios, servicios en la nube, aplicaciones web empresariales. | ASP.NET Core Web API.                                    |
| **PHP con Laravel**         | PHP        | APIs RESTful, aplicaciones web con MVC, desarrollo rápido.                          | Laravel API Resources, Symfony.                          |
| **Node.js (JavaScript)**    | JavaScript | APIs RESTful, microservicios, aplicaciones en tiempo real, *Full-stack* JavaScript. | Express.js, NestJS, Hapi.js, Meteor.js.                  |
| **Python con Django/Flask** | Python     | APIs RESTful, aplicaciones web complejas, Machine Learning, backend de datos.       | Django REST Framework, Flask-RESTful.                    |
| **Ruby con Rails**          | Ruby       | APIs RESTful, aplicaciones web con MVC, desarrollo rápido.                          | Ruby on Rails.                                           |
| **gRPC**                    | Varios     | Comunicación de alto rendimiento entre microservicios, *backend-to-backend*.        | Soporte nativo en Java, C#, Python, Go, Node.js, etc.    |


### 7.4. Integración del Código con Lenguajes de Marcas

Una técnica fundamental para crear páginas web dinámicas es integrar código de programación directamente dentro de lenguajes de marcado como HTML. Esto permite generar dinámicamente secciones de contenido HTML basándose en la lógica del programa.

*   En el modelo **MVC (Modelo-Vista-Controlador)**, esta combinación se realiza en el **lado del servidor**. El lenguaje de programación (ej. PHP, Python) se incrusta en el HTML, y el documento web resultante se envía al cliente desde el servidor.
*   En aplicaciones web basadas en **servicios REST**, la combinación se lleva a cabo en el **lado del cliente**. El lenguaje de programación (JavaScript o TypeScript) consume datos JSON del servidor y modifica el HTML de forma dinámica en el navegador del usuario.

Por ejemplo, un bucle en PHP puede recorrer una lista de productos y crear un bloque HTML para cada uno. Los lenguajes de programación utilizan etiquetas especiales (como `<?php ... ?>` en PHP) para delimitar el código incrustado.


## 8. Funcionamiento y Configuración de Servidores Web y de Aplicaciones

### 8.1. Servidores Web: Apache y Nginx

Un **servidor web** es un programa que se ejecuta continuamente en un ordenador, esperando peticiones de un cliente (un navegador) y respondiendo con el recurso solicitado (páginas web, imágenes, etc.). Puede servir contenido estático o delegar la ejecución de aplicaciones para generar contenido dinámico.

**Apache HTTP Server** es uno de los servidores web más populares y utilizados, conocido por ser de código abierto y gratuito, disponible para Windows y GNU/Linux.
*   **Características**: Apache se caracteriza por su **modularidad**, lo que permite activar o desactivar módulos específicos (ej., para PHP, SSL, control de acceso) para extender su funcionalidad. El archivo principal de configuración suele ser `apache2.conf` o `httpd.conf`.


#### 8.1.1. Instalación y Configuración Básica de Apache (Linux)

En sistemas Linux basados en Debian/Ubuntu, Apache se instala fácilmente. Una vez instalado, se verifica su funcionamiento accediendo a `http://localhost` o a la dirección IP del servidor.

Apache sirve las páginas web desde el directorio especificado por la directiva `DocumentRoot`, que por defecto suele ser `/var/www/html/`.
Las **directivas** son reglas que controlan el comportamiento de Apache. Algunas directivas básicas incluyen:
*   `ServerRoot`: Define el directorio base de la configuración de Apache.
*   `ServerName`: Establece el nombre del servidor web (ej., `www.ejemplo.local`). Puede estar a nivel global o dentro de un VirtualHost.
*   `Listen`: Especifica el puerto (y opcionalmente la dirección IP) por el que Apache escuchará las peticiones (por defecto el puerto 80 para HTTP).
*   `ErrorLog`: Ubicación del archivo donde se registran los errores.
*   `KeepAlive`: Permite mantener conexiones persistentes para múltiples peticiones.
*   `Timeout`: Tiempo máximo que el servidor esperará antes de cerrar una conexión inactiva.
Apache solo aplica los cambios después de ser iniciado o reiniciado.


#### 8.1.2. Arranque y Detención del Servicio Apache

En sistemas Linux, Apache se puede controlar (iniciar, detener, reiniciar) utilizando comandos como `sudo service apache2 start|stop|restart`. Es una buena práctica verificar la sintaxis de la configuración con `apache2ctl configtest` antes de reiniciar para evitar errores.


#### 8.1.3. Configuración de Hosts Virtuales

Los **Virtual Hosts** son una funcionalidad clave que permite a un único servidor físico alojar múltiples sitios web o dominios independientes.
*   **Virtual Hosts basados en nombre**: Varios nombres de dominio (ej., `www.miejemplo.local`, `www.misitio.local`) apuntan a la misma dirección IP del servidor. `ServerName` define el nombre principal y `ServerAlias` permite nombres alternativos.
*   **Virtual Hosts basados en IP**: Cada Virtual Host se asocia a una dirección IP distinta del servidor.
*   **Configuraciones mixtas**: Es posible combinar Virtual Hosts basados en nombre y en IP.
En sistemas Debian/Ubuntu, los Virtual Hosts se configuran en archivos específicos (ej., `/etc/apache2/sites-available/*.conf`) y se habilitan o deshabilitan mediante enlaces simbólicos y comandos como `a2ensite` y `a2dissite`. Las directivas no especificadas explícitamente en un Virtual Host se heredan de la configuración principal de Apache.


### 8.2. Servidores de Aplicaciones: Tomcat

Un **servidor de aplicaciones** es un software que proporciona servicios adicionales a los de un servidor web. Se especializa en contenido dinámico, ofrece servicios adicionales como balanceo de carga o *clustering*, y se integra frecuentemente con bases de datos. Simplifican el desarrollo al permitir ensamblar aplicaciones a partir de componentes predefinidos.

**Apache Tomcat** es un servidor de aplicaciones muy utilizado, que funciona como un contenedor de *servlets* y JSP. Es la implementación de referencia para ejecutar aplicaciones Java EE.


#### 8.2.1. Instalación y Configuración Básica de Tomcat (requisito JDK)

La instalación de cualquier versión de Tomcat requiere que el **Kit de Desarrollo de Java (JDK)** esté previamente instalado, ya que las peticiones a Apache a menudo se redirigen a Tomcat usando un conector Java. La gestión del servicio Tomcat se realiza mediante el *script* `catalina`, utilizando comandos como `start` y `stop`. Se puede verificar su funcionamiento accediendo a `http://127.0.0.1:8080` en un navegador.


### 8.3. Gestores de Bases de Datos

Los **gestores de bases de datos** son componentes fundamentales en cualquier plataforma web moderna. Son software encargados de almacenar, estructurar y recuperar grandes volúmenes de datos de manera eficiente.
*   **MySQL / MariaDB**: Son gestores de bases de datos relacionales de código abierto, muy populares por su eficiencia y velocidad, a menudo utilizados en combinación con PHP. MariaDB es un *fork* de MySQL completamente libre.
*   **PostgreSQL**: Otro potente gestor de bases de datos relacionales de código abierto, conocido por su robustez y cumplimiento de estándares.
*   **SQL Server**: Es el sistema gestor de bases de datos de Microsoft, típicamente empleado en plataformas WISA.
*   **MongoDB**: Es un gestor de bases de datos NoSQL orientado a documentos, ideal para aplicaciones que requieren alta escalabilidad y flexibilidad en el esquema de datos.


## 9. Despliegue de Aplicaciones Web

### 9.1. Concepto de Despliegue

Para desplegar una aplicación web, se necesitan varios elementos:
*   **Software**: Los componentes básicos de una plataforma web: un sistema operativo, un servidor web (Apache, Nginx), un servidor de aplicaciones (Tomcat para Java), el *runtime* del lenguaje de programación (JDK para Java, entorno PHP, .NET runtime) y un gestor de bases de datos. Además, para entornos de desarrollo local, herramientas como Docker Desktop o XAMPP son esenciales.
*   **Hardware**: Un servidor con la capacidad adecuada de CPU, memoria RAM y almacenamiento para la aplicación y la carga de usuarios prevista. La **escalabilidad** del hardware es un factor crítico.
*   **Dependencias**: Incluye librerías específicas del *framework* o del proyecto (como archivos JAR para Java, paquetes NuGet para C# o paquetes Composer para PHP).

### 9.2. Escalabilidad (Vertical y Horizontal, Clusters y Balanceadores de Carga)

La **escalabilidad** es la capacidad fundamental de un sistema web para soportar un aumento significativo en el número de usuarios o la carga de trabajo sin comprometer su rendimiento o funcionalidad. Es uno de los requisitos fundamentales de una aplicación web.
*   **Escalabilidad Vertical ("Scale Up")**: Consiste en aumentar los recursos (CPU, RAM, almacenamiento) de un único servidor existente.
*   **Escalabilidad Horizontal ("Scale Out")**: Implica añadir más servidores o "nodos" al sistema para distribuir la carga de trabajo entre ellos.
*   **Clusters**: Son agrupaciones de servidores que operan conjuntamente como una única entidad lógica, lo que mejora la disponibilidad y el rendimiento.
*   **Balanceadores de Carga**: Son dispositivos o software que distribuyen el tráfico de red de manera inteligente entre múltiples servidores. Su función es optimizar el uso de recursos, maximizar el rendimiento, minimizar los tiempos de respuesta y evitar la sobrecarga de un servidor individual. Pueden ser soluciones de **software** (como Apache con el módulo `mod_jk` que examina el paquete HTTP e identifica la sesión del usuario) o de **hardware** (que se basan en algoritmos de reparto de carga como Round Robin o LRU). Los balanceadores de **hardware HTTP** que examinan el paquete HTTP y mantienen la relación usuario-máquina servidora son una solución intermedia muy aceptada en el mercado.

### 9.3. Despliegue en Contenedores (Docker, Kubernetes)

El despliegue en contenedores es una estrategia muy extendida para aplicaciones dinámicas, ofreciendo portabilidad y consistencia entre diferentes entornos.
*   **Docker**: Es una plataforma de gestión de contenedores que facilita la creación, prueba y despliegue rápido de aplicaciones mediante el uso de "imágenes". Los contenedores proporcionan un método de virtualización ligero del sistema operativo, que consume menos recursos que las máquinas virtuales tradicionales. El proceso implica crear **Dockerfiles** para definir las imágenes de los contenedores, publicarlas en un registro (como Docker Hub) y luego desplegarlas.
*   **Docker Compose**: Es una herramienta que simplifica la orquestación de múltiples contenedores, lo que resulta muy útil para configurar entornos de desarrollo locales con servicios como Apache/Nginx y PHP.
    ![Diagrama de un entorno Docker Compose con servicios Apache/Nginx y PHP]
*   **Kubernetes**: Es una plataforma de orquestación de contenedores que automatiza el despliegue, el escalado y la gestión de aplicaciones en contenedores. Permite configurar el autoescalado y los balanceadores de carga para gestionar eficazmente el tráfico y la demanda.


### 9.4. Despliegue en la Nube (AWS, Google Cloud, Azure)

El despliegue en la nube es una estrategia que ofrece escalabilidad automática, acceso a servicios gestionados y alta disponibilidad.
*   **Proveedores Comunes**: Los principales proveedores de servicios en la nube incluyen Amazon Web Services (AWS), Google Cloud Platform (GCP) y Microsoft Azure.
*   **Proceso de Despliegue**:
    1.  **Configuración de la Infraestructura:** Creación de instancias de servidores virtuales, bases de datos y otros recursos necesarios en la plataforma de nube.
    2.  **Implementación del Código:** Utilización de servicios PaaS (Plataforma como Servicio), como AWS Elastic Beanstalk o Google App Engine, que simplifican la implementación y gestión de la aplicación.
    3.  **Configuración de Autoscaling y Balanceadores de Carga:** Ajustes para manejar eficientemente la carga de trabajo y garantizar la disponibilidad de la aplicación.
    4.  **Configuración de Seguridad:** Implementación de políticas de seguridad, *firewalls* y certificados SSL para proteger la aplicación.
    5.  **Pruebas y Validación:** Ejecución de pruebas exhaustivas para asegurar la funcionalidad y el rendimiento en el entorno de producción.
    6.  **Monitorización y Alerta:** Implementación de herramientas de monitorización y *logging* para detectar problemas en tiempo real y configurar alertas automáticas.
    7.  **Documentación**: Se documentan todas las configuraciones y procedimientos para la gestión continua y el *onboarding* de nuevos miembros del equipo.

### 9.6. Introducción a la Integración Continua / Despliegue Continuo (CI/CD)

Las prácticas de **CI/CD** (Integración Continua / Entrega Continua / Despliegue Continuo) son un conjunto de metodologías y herramientas que automatizan el ciclo de vida del desarrollo de software, desde la codificación hasta el despliegue en producción.
*   **Integración Continua (CI)**: Implica que los desarrolladores integran sus cambios de código de forma frecuente en un repositorio compartido. Cada vez que se realiza un *commit*, se dispara automáticamente una construcción de la aplicación y la ejecución de pruebas automatizadas (unitarias, de integración, funcionales). El objetivo es detectar errores de forma temprana y asegurar que el código siempre esté en un estado desplegable.
*   **Entrega Continua (CD - Continuous Delivery)**: Una extensión de la CI que asegura que el código, una vez que ha pasado las pruebas de CI, está siempre listo para ser lanzado a producción en cualquier momento. Esto incluye pruebas adicionales (de regresión, rendimiento, seguridad) y el despliegue en entornos de *staging* para pruebas de aceptación, a menudo con un paso de aprobación manual antes de pasar a producción.
*   **Despliegue Continuo (CD - Continuous Deployment)**: Es un paso más allá de la Entrega Continua, donde cada cambio que supera con éxito la *pipeline* de CI/CD se despliega automáticamente en producción. Esto reduce drásticamente los tiempos de espera y aumenta la frecuencia de los despliegues, minimizando los riesgos asociados a lanzamientos grandes y poco frecuentes. Requiere un monitoreo constante y el uso de técnicas como *rolling updates* y *canary releases* para mitigar cualquier impacto.


![img](/images/cicd2.png)

![img](/images/cicd.png)

![img](/images/cicd.gif)


## 10. Conceptos Clave de Seguridad y Monitorización (introducción muy breve)

### 10.1. Seguridad en Servidores Web (Autenticación HTTP Basic/Digest, Control de Acceso)

La seguridad es un pilar fundamental en las aplicaciones web, crucial para proteger la información confidencial y prevenir accesos no autorizados.
La **autenticación** y el **control de acceso** son mecanismos para verificar la identidad de los usuarios y determinar a qué recursos pueden acceder.
*   La **autenticación HTTP Basic** es un método simple donde el navegador envía las credenciales (usuario y contraseña) codificadas en Base64 con cada petición. Aunque fácil de implementar, es vital utilizarla siempre con HTTPS para cifrar las credenciales.
*   El **Esquema Digest** utiliza funciones *hash* para enviar las credenciales, en lugar de enviarlas tal cual, ofreciendo mayor seguridad.
*   El **control de acceso por IP** permite restringir o conceder acceso a directorios o Virtual Hosts específicos en función de la dirección IP del cliente (ej., en Apache con `Require ip ...`). La configuración de seguridad en servidores web como Apache se realiza a través de directivas en los archivos de configuración principales o en archivos `.htaccess` dentro de los directorios.


### 10.2. Monitorización con Archivos de Registro (Logs CLF, Rotación de Logs)

La **monitorización** a través de **archivos de registro (logs)** es esencial para el mantenimiento y el estudio del funcionamiento de los servidores.
Los logs guardan información detallada sobre las conexiones y eventos del servidor. Apache, por defecto, registra esta información en el **formato CLF (Common Log Format)**, una especificación estándar que facilita el análisis de registros entre diferentes servidores web. Las directivas `LogFormat`, `CustomLog` y `ErrorLog` permiten configurar la ubicación y el formato de los registros de acceso y errores.
![Ejemplo de entrada en un archivo de registro (log) de Apache en formato CLF]

La **rotación de archivos de registro** es una práctica crucial. Dado que los logs crecen con el tiempo, es necesario depurarlos, comprimirlos y guardarlos para evitar que consuman demasiados recursos del servidor. Esto se puede lograr con herramientas como `rotatelogs` (propia de Apache) o `logrotate` (una utilidad común en sistemas Linux). Es importante conservar estos registros durante un período mínimo debido a requisitos legales.

![img](/images/log.jpg)

## Autor

Codificado con :sparkling_heart: por [José Luis González Sánchez](https://twitter.com/JoseLuisGS_)

[![Twitter](https://img.shields.io/twitter/follow/JoseLuisGS_?style=social)](https://twitter.com/JoseLuisGS_)
[![GitHub](https://img.shields.io/github/followers/joseluisgs?style=social)](https://github.com/joseluisgs)
[![GitHub](https://img.shields.io/github/stars/joseluisgs?style=social)](https://github.com/joseluisgs)

### Contacto

<p>
  Cualquier cosa que necesites házmelo saber por si puedo ayudarte 💬.
</p>
<p>
 <a href="https://joseluisgs.dev" target="_blank">
        <img src="https://joseluisgs.github.io/img/favicon.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://github.com/joseluisgs" target="_blank">
        <img src="https://distreau.com/github.svg" 
    height="30">
    </a> &nbsp;&nbsp;
        <a href="https://twitter.com/JoseLuisGS_" target="_blank">
        <img src="https://i.imgur.com/U4Uiaef.png" 
    height="30">
    </a> &nbsp;&nbsp;
    <a href="https://www.linkedin.com/in/joseluisgonsan" target="_blank">
        <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/c/ca/LinkedIn_logo_initials.png/768px-LinkedIn_logo_initials.png" 
    height="30">
    </a>  &nbsp;&nbsp;
    <a href="https://g.dev/joseluisgs" target="_blank">
        <img loading="lazy" src="https://googlediscovery.com/wp-content/uploads/google-developers.png" 
    height="30">
    </a>  &nbsp;&nbsp;
<a href="https://www.youtube.com/@joseluisgs" target="_blank">
        <img loading="lazy" src="https://upload.wikimedia.org/wikipedia/commons/e/ef/Youtube_logo.png" 
    height="30">
    </a>  
</p>

## Licencia de uso

Este repositorio y todo su contenido está licenciado bajo licencia **Creative Commons**, si desea saber más, vea
la [LICENSE](https://joseluisgs.dev/docs/license/). Por favor si compartes, usas o modificas este proyecto cita a su
autor, y usa las mismas condiciones para su uso docente, formativo o educativo y no comercial.

<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="Licencia de Creative Commons" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">
JoseLuisGS</span>
by <a xmlns:cc="http://creativecommons.org/ns#" href="https://joseluisgs.dev/" property="cc:attributionName" rel="cc:attributionURL">
José Luis González Sánchez</a> is licensed under
a <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/">Creative Commons
Reconocimiento-NoComercial-CompartirIgual 4.0 Internacional License</a>.<br />Creado a partir de la obra
en <a xmlns:dct="http://purl.org/dc/terms/" href="https://github.com/joseluisgs" rel="dct:source">https://github.com/joseluisgs</a>.