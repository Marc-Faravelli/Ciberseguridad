# Ciberseguridad

Caso Práctico

Imaginemos que una entidad bancaria ha considerado utilizar Big Data para una toma de decisiones estratégicas de negocio en función de una predicción de comportamiento basada en datos reales de sus clientes, con lo cual debe tomar la decisión de escoger el Business Intelligence (BI).

La función BI se basa en aplicaciones, infraestructura, Base de Datos, Middleware de acceso a los datos de los clientes, así como en las mejores prácticas que permiten el acceso y el análisis de la información.

No obstante el CISO (director de seguridad de la información) de la entidad considera que la ciberseguridad del BI, el cumplimiento normativo de la nueva LOPD vigente a finales del 2018 y GDPR, que entró en vigor el 25 de Mayo de 2018, la anonimización de los datos, el tiempo de retención de estos, la Gestión de Riesgos que esto conllevará, así como la respuesta a incidentes son temas que se escapan de su área de conocimiento actual (y zona de confort) y decide preguntárnoslo a nosotros que estamos estudiando conceptos de Big Data/Data Science y, concretamente, ahora que estamos inmersos en el módulo de Ciberseguridad.

Este proyecto lo impulsa el departamento de expansión de negocio de la entidad bancaria (marketing y ventas), pero en un café se lo comenta al responsable del área de fraudes asociado a la unidad de auditoria y estos comentan que les gustaría participar del BI pero no para expandir el negocio sino para disminuir el fraude de divisas y los robos en los cajeros.

Por lo tanto, en este punto del caso práctico parece que la infraestructura de BI no solo habrá que protegerla de ataques y fugas de información, hacerla Compliance, estar preparado en caso de ataque, sino que habrá que utilizarla (operarla) para disminuir los fraudes de divisas y robos de cajeros. Por lo tanto, esta utilización del Big Data/Data Science servirá también para la seguridad del negocio.

Con el fin de que demos respuesta a todas las dudas, el CISO nos irá haciendo preguntas sobre todos estos temas que le vienen encima con la implantación del BI, tanto para su protección como para su utilización para disminuir el fraude de divisas y robos.

Antes de empezar con las preguntas el CISO queda para tomar un café con uno de vosotros y le empieza a preguntar por los temas de robos de cajeros y fraudes de dividas. Contestáis que para disminuir los robos de los cajeros a través de reglas de negocio haríais algo así como: “si el sistema detecta como un cliente va sacando de diferentes o el mismo cajero el máximo permitido diario durante 2 días seguidos, el sistema bloqueará la tarjeta temporalmente y se le enviará una notificación al cliente informando que para desbloquearla deberá introducir el código firma si es cliente on-line de la entidad o indicar por teléfono información privada que solo debería saber el propio cliente."

Cuando se le pregunta por cómo detectar la fuga de dividas, la norma española dice algo así “para los movimientos de dinero entre el extranjero y el territorio nacional superiores a 10.000 €, incluyendo las transferencias, deberán declararse.”

Pero el problema que quieren resolver con el BI es que mucha gente/empresas para evitar superar esta cifra realizan pequeñas transferencias dispersas en el tiempo. El alumno no ve demasiada complicación para detectar estos comportamientos desde cualquier cuenta de un usuario/empresa en el tiempo y así informar a la unidad de fraude para que analice estos hábitos susceptibles de que puedan ser fraude.

El caso práctico consistirá en dar una respuesta coherente con todo lo que habréis visto en el módulo de Ciberseguridad. El CISO te puntuará dependiendo de lo satisfecho que queda con las respuestas.

Preguntas de caso práctico:

¿Se te ocurre/n alguna/s otra/s regla/s de BI que puedan ayudar a disminuir el fraude en la entidad bancaria?
Dentro de los 3 ejes de la ciberseguridad CIA (Confidencialidad, Integridad y Disponibilidad) y viendo tu sistema de Big Data, no solo como los sistemas operativos, sino también los datos, tanto los datos en crudo como la información de negocio que sale del sistema: ¿Podrías argumentar como mitigaríamos el riesgo en cuanto a la ciberseguridad en cada uno de los 3 ejes?    
A nivel de los sistemas que deberían proteger tu plataforma de Big Data:
¿Debería estar segmentada de la red interna o de lo contrario podría estar integrada dentro de alguna red interna?
¿Cuáles son los Pros y Contras de tenerla segmentada?
Si decidimos segmentarla: ¿crees necesario instalar un firewall?
Si decidimos añadir un IPS (Intrusion Protection System): ¿Por qué ganaríamos en seguridad?
¿Qué entiendes por Hardening de Servidores?
Al tener las redes segmentadas y requerir que los flujos de datos pasen por Firewalls para una mayor seguridad: ¿qué problemas pueden conllevar este escenario comentado?
Mírate este enlace y responde brevemente porque es importante, principalmente, clasificar los datos a nivel de seguridad.
Imagínate que tienes que gestionar un incidente relacionado con una fuga de datos de la información ya procesada de utilidad para el negocio. Tu equipo de seguridad ha detectado un Command & Control (telecontrol de un sistema que un hacker realiza desde fuera de la empresa a través de internet) y tienes el dilema de erradicar cuanto antes el problema o buscar evidencias Forensics para una posible denuncia: ¿Cuál sería tu decisión?
Respecto a las estrategias de Recuperación del Negocio del banco que va a instaurar un Data Science para mejorar las ventas y teniendo en cuenta que el coste de la estrategia debe ser coherente con los datos a proteger: argumenta si utilizar un COLD, WARM, HOT SITE. Argumenta tu respuesta.
Imagínate que tu Data Science lo tienes afinado y empieza a dar información que guía o enfoca las campañas de marketing a públicos objetivos ofreciéndoles productos que encajan a sus necesidades. Se filtra esta información a la competencia. En esta situación: ¿crees que tu empresa estaría más expuesta a un ataque APT? Argumenta la respuesta. (Doc en recursos de la clase)
¿Por qué deberíamos anonimizar los datos de los clientes?
En el caso que parte de tu solución requiriera servicios SaaS en el Cloud: ¿Qué tienes que decir sobre las medidas de seguridad que adoptarías para interconectar tu red al Cloud?
¿Crees necesario que Cloud Computing puede ser de ayuda para tu Análisis de Datos? Razona la respuesta.

Objetivos: Ponerse en el papel de experto en BI y dar respuesta al CISO de la compañía que no tiene conocimientos específicos de la seguridad para este entorno. Además, tendrás dos roles respecto a la utilidad que el BI puede hacer para este entorno bancario: el primero es como las reglas de BI pueden ayudar a la seguridad para evitar robos de cajeros y fraude bancario y el segundo desde un aspecto de ciberseguridad en cuanto a que debes proteger unos activos, principalmente los datos.  
