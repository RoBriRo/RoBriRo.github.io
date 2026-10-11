# OSINT: métodos lícitos e ilícitos

**Trabajo de investigación.** Marco legal de referencia: Unión Europea y España (RGPD, LOPDGDD y Código Penal).

---

## Índice

1. Introducción
2. ¿Qué es OSINT? Conceptos básicos
3. Marco legal: qué dice la ley
4. OSINT lícito: métodos explicados con ejemplos
5. OSINT ilícito: métodos explicados con casos reales
6. La zona gris
7. ¿En qué se diferencian? Criterios para distinguirlos
8. Cómo buscarte a ti mismo: comprobar si tus datos están expuestos
9. Cómo reclamar y borrar tus datos
10. Cómo protegerse
11. Conclusiones
12. Bibliografía y recursos

---

## 1. Introducción

Cada vez que nos registramos en una tienda online, publicamos una foto, aparecemos en el BOE por unas oposiciones o simplemente damos nuestro teléfono a una empresa, dejamos un rastro de datos. A ese rastro se le llama **huella digital**. La mayor parte de las veces no le damos importancia, pero toda esa información, unida, puede revelar quiénes somos, dónde vivimos, dónde trabajamos, con quién nos relacionamos y cuáles son nuestras rutinas.

La disciplina que se dedica a recopilar y analizar esa información disponible se llama **OSINT** (*Open Source Intelligence*, inteligencia de fuentes abiertas). Es una herramienta muy valiosa: la usan periodistas para destapar crímenes de guerra, policías para localizar a desaparecidos y empresas de ciberseguridad para proteger a sus clientes. Pero las mismas técnicas, o versiones ilegales de ellas, las usan también estafadores, acosadores y extorsionadores.

Este trabajo tiene tres objetivos:

- **Explicar** qué métodos de OSINT son legales y cuáles no, con ejemplos concretos.
- **Analizar** qué es exactamente lo que convierte una investigación en ilegal.
- **Dar herramientas prácticas** para que cualquier persona pueda comprobar si sus datos circulan por fuentes ilícitas, reclamar su eliminación y protegerse.

## 2. ¿Qué es OSINT? Conceptos básicos

### 2.1 Definición

OSINT es la obtención, el análisis y el uso de información procedente de **fuentes abiertas**, es decir, fuentes a las que cualquiera puede acceder **sin romper ninguna medida de seguridad, sin engañar a nadie y sin necesidad de un permiso especial**. Ejemplos de fuentes abiertas son un periódico, un perfil público de Instagram, el Registro Mercantil o una página web.

El término nace en el ámbito militar y de los servicios de inteligencia. Durante la Guerra Fría, se calcula que buena parte de la información que los servicios occidentales obtenían sobre la URSS procedía de leer su prensa, sus revistas técnicas y escuchar su radio. Con Internet y las redes sociales, la cantidad de información abierta se ha multiplicado y el OSINT se ha extendido al mundo civil.

### 2.2 ¿Por qué es tan potente?

Un dato aislado casi nunca es peligroso. El poder del OSINT está en **cruzar datos**. Por ejemplo:

- En LinkedIn aparece dónde trabaja una persona.
- En Instagram sube una foto corriendo cada mañana con la etiqueta de un parque.
- En Strava (app de deporte) su ruta es pública y empieza siempre en el mismo portal.
- En el BOE aparece su nombre completo y parte de su DNI por unas oposiciones.

Ninguno de estos datos, por separado, parece grave. Juntos, permiten saber su nombre, su trabajo, su casa y a qué hora sale cada día. Este fenómeno se conoce como **efecto mosaico**, y es la razón por la que el uso que se hace de la información importa tanto como su origen.

> **Caso real (efecto mosaico):** en 2018, el mapa de calor global de Strava reveló la ubicación y las rutas de patrulla de bases militares secretas en Siria, Afganistán y otros países, simplemente porque los soldados corrían con sus relojes deportivos conectados.

### 2.3 El ciclo de inteligencia

Una investigación OSINT profesional sigue unas fases:

1. **Planificación**: qué se quiere saber y para qué. Esta fase es clave para la legalidad, porque define la finalidad.
2. **Recolección**: búsqueda de información en las fuentes.
3. **Procesamiento**: ordenar, eliminar duplicados y datos irrelevantes.
4. **Análisis y verificación**: contrastar los datos (en Internet hay mucha información falsa) y relacionarlos.
5. **Difusión**: elaborar un informe para quien lo encargó.

### 2.4 ¿Quién usa OSINT de forma legítima?

- **Periodistas de investigación.** El colectivo Bellingcat demostró con fotos y vídeos publicados en redes sociales qué lanzador de misiles derribó el vuelo MH17 sobre Ucrania en 2014.
- **Fuerzas de seguridad.** Europol tiene la campaña *Stop Child Abuse – Trace an Object*, en la que pide a ciudadanos que identifiquen objetos que aparecen en imágenes de abusos para localizar el país donde se tomaron.
- **Empresas de ciberseguridad.** Antes de una auditoría autorizada, analizan qué información de la empresa cliente está expuesta (correos de empleados, servidores visibles, documentos publicados por error).
- **Bancos y empresas** para prevenir fraudes y verificar a socios comerciales (*due diligence*).
- **Verificadores de noticias** (Maldita, Newtral, EFE Verifica) para comprobar si una foto viral es real o antigua.
- **ONG** para documentar violaciones de derechos humanos.

## 3. Marco legal: qué dice la ley

Un error muy común es pensar que "si está en Internet, es público y puedo hacer lo que quiera con ello". **Es falso.** Un dato personal sigue siendo un dato personal aunque esté publicado, y está protegido por la ley.

### 3.1 Protección de datos: RGPD y LOPDGDD

El **Reglamento General de Protección de Datos (RGPD)**, en vigor en toda la UE desde 2018, y la **Ley Orgánica 3/2018 (LOPDGDD)** en España, establecen que:

- Cualquier **tratamiento** de datos personales (recogerlos, guardarlos, cruzarlos, publicarlos) necesita una **base legal** (art. 6 RGPD): consentimiento, un contrato, una obligación legal, un interés legítimo, etc.
- Los datos solo pueden usarse para una **finalidad concreta y legítima** y en la cantidad mínima necesaria (**principio de minimización**).
- Las personas tienen **derechos**: acceso, rectificación, supresión ("derecho al olvido"), oposición, limitación y portabilidad.
- Las sanciones pueden llegar a **20 millones de euros o el 4 % de la facturación anual** mundial.

Excepción importante: el RGPD no se aplica a actividades **puramente personales o domésticas**. Mirar el perfil público de alguien no es ilegal; lo que puede serlo es recopilar sistemáticamente sus datos, almacenarlos y usarlos o difundirlos.

### 3.2 Código Penal

Cuando la conducta es grave, entra en juego el Código Penal:

| Artículo | Delito | Ejemplo relacionado con OSINT |
|---|---|---|
| **197.1 y 197.2** | Descubrimiento y revelación de secretos | Apoderarse de correos, mensajes o datos reservados de otra persona |
| **197.3** | Difusión de lo anterior | Publicar los datos obtenidos (penas mayores) |
| **197.7** | Difusión de imágenes íntimas sin consentimiento | Reenviar fotos íntimas aunque se obtuvieran con permiso |
| **197 bis** | Acceso ilegal a sistemas informáticos | Entrar en una cuenta o base de datos sin autorización |
| **197 ter** | Producir o facilitar herramientas para cometer estos delitos | Vender contraseñas o programas para acceder a sistemas |
| **172 ter** | Acoso (*stalking*) | Vigilar, perseguir o contactar insistentemente con alguien |
| **169 y ss.** | Amenazas | Mostrar a alguien que conoces su dirección para intimidarle |
| **248 y ss.** | Estafa | Usar datos recopilados para engañar y obtener dinero |
| **401** | Usurpación de estado civil (suplantación) | Hacerse pasar por otra persona con sus datos |

### 3.3 Otras normas

- **Constitución Española, art. 18**: protege el honor, la intimidad, la propia imagen y la protección de datos frente a la informática.
- **Ley Orgánica 1/1982**: permite reclamar una indemnización por intromisiones en la intimidad o la propia imagen.
- **Reglamento de Servicios Digitales (DSA)**: obliga a las plataformas a tener canales para denunciar contenidos ilegales y a actuar con rapidez.
- **Condiciones de uso de las plataformas**: casi todas prohíben la extracción masiva automatizada de datos (*scraping*). Incumplirlas no siempre es delito, pero puede acarrear demandas y cierre de cuentas.

## 4. OSINT lícito: métodos explicados con ejemplos

Un método de OSINT es lícito cuando se cumplen **tres condiciones**: la fuente es realmente pública, el acceso se hace sin vulnerar seguridad ni engañar, y la finalidad es legítima y proporcionada.

### 4.1 Búsqueda avanzada en buscadores (Google Dorking)

Los buscadores admiten **operadores** que filtran los resultados con mucha precisión:

| Operador | Qué hace | Ejemplo |
|---|---|---|
| `"..."` | Busca la frase exacta | `"María López García"` |
| `site:` | Limita a una web | `site:boe.es "López García"` |
| `filetype:` | Busca un tipo de archivo | `filetype:pdf site:miayuntamiento.es listado` |
| `intitle:` | Palabras en el título | `intitle:"currículum" "María López"` |
| `-` | Excluye un término | `"María López" -futbolista` |

**Uso lícito:** una empresa busca `site:suempresa.com filetype:xls` para comprobar si ha publicado por error hojas de cálculo con datos de clientes. Un ciudadano busca su propio nombre en `site:boe.es` para ver qué aparece.

### 4.2 Registros y fuentes oficiales

- **BOE y boletines autonómicos/provinciales**: nombramientos, oposiciones, sanciones, subvenciones.
- **BORME y Registro Mercantil**: administradores de empresas, cuentas anuales.
- **Catastro**: datos de inmuebles (la titularidad está protegida, pero la parte no protegida es consultable).
- **CENDOJ**: sentencias judiciales (anonimizadas).
- **Portales de transparencia y datos abiertos** (datos.gob.es).

**Ejemplo:** un periodista descubre, cruzando el BORME y los contratos públicos, que el administrador de la empresa que gana todos los contratos de un ayuntamiento es familiar del alcalde.

### 4.3 Redes sociales (contenido público)

Consultar publicaciones, fotos y comentarios **públicos** en X, Instagram, TikTok, Facebook o LinkedIn. Se pueden analizar redes de contactos, fechas y lugares.

**Ejemplo:** los verificadores comprueban si un vídeo de un incendio "de hoy" ya se había publicado años antes buscando en redes y en archivos.

**Límite:** la AEPD ha señalado que las empresas pueden revisar el perfil profesional de un candidato (LinkedIn), pero investigar sus redes personales para decidir si lo contratan puede ser desproporcionado.

### 4.4 Análisis de imágenes y geolocalización

- **Búsqueda inversa de imágenes** (Google Lens, TinEye, Yandex): encontrar dónde más aparece una foto.
- **Metadatos EXIF**: muchas fotos guardan la fecha, el modelo de móvil e incluso las coordenadas GPS donde se hicieron.
- **Geolocalización por elementos visuales**: carteles, montañas, sombras, matrículas, con ayuda de Google Maps y Street View.

**Ejemplo:** Bellingcat geolocaliza vídeos de conflictos comparando el perfil de los edificios con imágenes de satélite.

### 4.5 Información técnica (ciberseguridad)

- **WHOIS**: quién registró un dominio.
- **DNS y certificados** (crt.sh): qué subdominios tiene una web.
- **Shodan / Censys**: buscadores de dispositivos conectados a Internet (cámaras, servidores, routers).

**Ejemplo lícito:** un auditor contratado por un hospital usa Shodan para comprobar si el hospital tiene equipos expuestos a Internet y les avisa para que los protejan. **Si ese mismo auditor entrara en una cámara expuesta sin permiso, ya sería acceso ilegal** (art. 197 bis).

### 4.6 Archivos web

La **Wayback Machine** (archive.org) guarda copias de webs a lo largo del tiempo. Permite ver qué publicaba una empresa hace años o recuperar una noticia borrada.

### 4.7 Herramientas de automatización

**Maltego**, **SpiderFoot** o **theHarvester** automatizan búsquedas y dibujan relaciones entre datos. Son legales y se enseñan en cursos de ciberseguridad; lo que determina la legalidad es sobre quién y para qué se usan. El portal **OSINT Framework** (osintframework.com) recopila cientos de herramientas por categorías.

## 5. OSINT ilícito: métodos explicados con casos reales

Estrictamente hablando, muchos de estos métodos **no son OSINT**, porque la información no es abierta: se obtiene robando, engañando o accediendo sin permiso. Sin embargo, se suelen estudiar junto al OSINT porque se combinan con él y porque sus resultados acaban circulando por Internet como si fueran "información disponible".

### 5.1 Filtraciones de datos (data breaches) y su compraventa

**Qué es:** unos delincuentes atacan una empresa, roban su base de datos de clientes (nombres, emails, teléfonos, DNI, direcciones, a veces contraseñas o datos bancarios) y la venden o publican en foros de la *dark web*, en foros de hacking o en canales de Telegram.

**Por qué es ilícito:** el robo es acceso ilegal (197 bis) y revelación de secretos (197); quien compra y usa esos datos también comete un delito y trata datos sin base legal.

**Casos reales:**
- **Facebook (2021):** se publicaron gratis datos de **533 millones de usuarios**, más de 10 millones de ellos en España, incluidos números de teléfono. Se obtuvieron abusando de una función de la plataforma (scraping) y acabaron en un foro de hackers. Ese mismo año se filtraron datos de unos **700 millones de perfiles de LinkedIn** recogidos de forma similar.
- **Iberdrola (2024):** un ciberataque expuso datos de **1,35 millones de clientes** (nombre, DNI, dirección, teléfono, email).
- **Banco Santander (2024):** se accedió a una base de datos alojada en un proveedor con datos de clientes y empleados, que los delincuentes pusieron a la venta.
- **Telefónica (2025):** un grupo de atacantes publicó información de un sistema interno de gestión de incidencias con datos de empleados.

**Peligro para el ciudadano:** aunque estos datos no incluyan contraseñas, sirven para estafas muy creíbles. Un SMS que te llama por tu nombre y conoce tu banco parece legítimo.

### 5.2 Bases de datos de "doxeo" y bots de búsqueda ilegales

**Qué es:** servicios clandestinos (a menudo bots de Telegram o webs de la dark web) que agregan millones de registros filtrados. Escribes un teléfono, un DNI o un email y te devuelven todo lo que hay sobre esa persona: dirección, familiares, vehículos, empresas, cuentas.

**Caso real – Alcasec (España, 2022-2023):** el joven hacker José Luis Huertas, conocido como *Alcasec*, fue detenido por la Policía Nacional por, presuntamente, acceder al **Punto Neutro Judicial** (red que conecta juzgados con otras administraciones) y obtener datos de cientos de miles de contribuyentes, incluidos cuentas bancarias. Según la investigación, los usaba para alimentar una base de datos ("BlackDB") cuyas consultas vendía a terceros. Es un ejemplo claro de cómo los datos robados se convierten en un "servicio de búsqueda de personas" ilegal.

### 5.3 Credential stuffing (relleno de credenciales)

**Qué es:** los delincuentes cogen listas de emails y contraseñas filtradas de una web (las llamadas *combolists*) y las prueban automáticamente en otras (Gmail, Netflix, Amazon, bancos), porque saben que mucha gente repite contraseña.

**Ejemplo:** te robaron la contraseña de un foro de recetas en 2016. Si es la misma que la de tu Instagram, alguien puede entrar en tu cuenta hoy, aunque el foro ya no exista.

**Por qué es ilícito:** acceso ilegal a cuentas ajenas (197 bis), aunque la contraseña "esté en Internet".

### 5.4 Ingeniería social y pretexting

**Qué es:** manipular a una persona para que entregue información. El *pretexting* consiste en inventarse un pretexto: hacerse pasar por un técnico, un banco, un repartidor o un familiar. Suele apoyarse en OSINT previo para resultar creíble.

**Ejemplos:**
- **Estafa del "hijo en apuros"**: un WhatsApp de un número desconocido dice "Mamá, se me ha roto el móvil, este es mi número nuevo" y después pide una transferencia urgente. Los datos de quién es tu hijo pueden haberse obtenido de redes sociales.
- **Fraude del CEO**: alguien se hace pasar por el director de una empresa (cuyo nombre y estilo se han estudiado en LinkedIn y en noticias) y pide al departamento de finanzas una transferencia urgente. Ahora se usa incluso con voces clonadas por inteligencia artificial.
- **SIM swapping**: el delincuente reúne tus datos (nombre, DNI, dirección) y, haciéndose pasar por ti, consigue que tu operadora le dé un duplicado de tu tarjeta SIM. Con él recibe los SMS de verificación de tu banco. La Policía Nacional ha desarticulado varias redes en España que robaron así cientos de miles de euros.

### 5.5 Phishing, smishing y vishing

**Qué es:** mensajes falsos (email, SMS o llamada) que suplantan a una entidad para que introduzcas tus datos o contraseñas en una web falsa. Es una forma de obtener información que **no es abierta** engañando a su dueño.

**Ejemplos habituales en España:** SMS falsos de Correos ("tu paquete está retenido, paga 1,99 €"), de la DGT ("tienes una multa pendiente"), de la Agencia Tributaria ("tienes una devolución") o de tu banco ("hemos bloqueado tu cuenta"). El INCIBE publica avisos casi a diario.

### 5.6 Doxing

**Qué es:** recopilar información personal de alguien (a menudo con técnicas OSINT legales combinadas con datos filtrados) y **publicarla** para exponerlo, humillarlo o animar a otros a acosarlo: dirección, teléfono, lugar de trabajo, colegio de sus hijos.

**Por qué es ilícito:** aunque cada dato fuera público, su difusión con esa finalidad vulnera el RGPD y puede constituir revelación de secretos, amenazas o acoso. El daño es grave: muchas víctimas tienen que mudarse.

**Ejemplos:** periodistas, activistas, árbitros o *streamers* a los que se les publica la dirección tras una polémica en redes; y el *swatting* en EE. UU., donde tras doxear a alguien se hace una llamada falsa a la policía para que un equipo armado irrumpa en su casa.

### 5.7 Stalking y stalkerware

**Qué es:** vigilar de forma continuada a una persona. Puede hacerse con OSINT (seguir sus publicaciones, su ubicación en historias, sus rutas deportivas) o con herramientas claramente ilegales:
- **Stalkerware:** aplicaciones espía instaladas a escondidas en el móvil de otra persona que permiten leer sus mensajes, ver su ubicación y escuchar el micrófono. Es frecuente en casos de violencia de género.
- **Localizadores** (AirTag, SmartTag) escondidos en el bolso o el coche de la víctima.

**Por qué es ilícito:** delito de acoso (172 ter) y de descubrimiento de secretos (197). Instalar una app espía en el móvil de la pareja es delito aunque se tenga acceso al teléfono.

### 5.8 Explotación de vulnerabilidades

**Qué es:** aprovechar un fallo de una web para obtener datos que no deberían verse. Por ejemplo, cambiar un número en la dirección de una página (`.../factura?id=1001` → `id=1002`) y ver la factura de otro cliente (fallo conocido como **IDOR**).

**Por qué es ilícito:** aunque no haya contraseña que "romper", acceder a datos sabiendo que no tienes permiso es acceso ilegal. Lo correcto, si se descubre por casualidad, es avisar a la empresa (**divulgación responsable**), sin descargar ni difundir los datos.

### 5.9 Sextorsión basada en filtraciones

**Qué es:** el delincuente envía un email en el que muestra **una contraseña real tuya** (sacada de una filtración antigua) y afirma haber hackeado tu webcam y tener vídeos íntimos. Pide un pago en criptomonedas. En la gran mayoría de casos es un farol: solo tienen la contraseña filtrada.

**Qué hacer:** no pagar, no responder, cambiar esa contraseña donde se use y denunciar.

## 6. La zona gris

Hay prácticas cuya legalidad depende mucho del uso, del país y de la forma concreta:

- **Scraping masivo de datos públicos.** Descargar automáticamente miles de perfiles. **Caso Clearview AI:** esta empresa descargó miles de millones de fotos de redes sociales para crear un buscador de reconocimiento facial que vendía a policías. Las autoridades de protección de datos de Italia, Francia, Grecia y Países Bajos la multaron con hasta 30,5 millones de euros por tratar datos biométricos sin base legal.
- **Buscadores de reconocimiento facial** (por ejemplo, PimEyes): subes una foto de alguien y encuentras dónde aparece su cara en Internet. Se presentan como herramientas para buscarte a ti mismo, pero pueden usarse para identificar a desconocidos por la calle. Han recibido críticas y reclamaciones ante autoridades de protección de datos.
- **Data brokers / páginas de búsqueda de personas**: muy comunes en EE. UU. (Spokeo, Whitepages); en la UE su modelo suele chocar con el RGPD.
- **Cambridge Analytica (2018):** se recogieron datos de hasta 87 millones de usuarios de Facebook a través de un test de personalidad (que obtenía también datos de los amigos) y se usaron para crear perfiles con fines políticos. Facebook fue multada con 5.000 millones de dólares en EE. UU.
- **Cuentas falsas ("sock puppets")** para investigar: los investigadores profesionales las usan para no revelar su identidad, pero violan las condiciones de las plataformas y pueden ser ilegales si se usan para engañar a alguien y obtener información privada.
- **Consultar bases de datos filtradas con fines de investigación**: un investigador de seguridad puede analizar una filtración para avisar a los afectados, pero no puede usar los datos para otros fines ni difundirlos.

## 7. ¿En qué se diferencian? Criterios para distinguirlos

Para saber si un método es lícito, podemos hacernos **cinco preguntas**:

1. **¿La fuente es realmente pública?** Un perfil abierto de Instagram, sí. Un perfil privado al que se accede con una cuenta falsa haciéndose pasar por un amigo, no. Una base de datos robada, nunca, aunque se haya publicado gratis.
2. **¿Cómo se ha accedido?** Si ha hecho falta saltarse una contraseña, aprovechar un fallo, engañar a alguien o instalar software sin permiso, es ilícito.
3. **¿Para qué se usa?** La misma búsqueda puede ser legal para un periodista que investiga corrupción y delito para alguien que quiere intimidar a su expareja.
4. **¿Es proporcionado?** ¿Se recogen solo los datos necesarios o se construye un expediente completo de la vida de alguien?
5. **¿Hay autorización o base legal?** Un auditor de seguridad necesita un contrato firmado; una empresa que trata datos necesita una base legal del RGPD.

| Criterio | OSINT lícito | Métodos ilícitos |
|---|---|---|
| Fuente | Pública y accesible legalmente | Privada, robada o filtrada |
| Acceso | Sin vulnerar seguridad ni engañar | Contraseñas ajenas, fallos, engaño, malware |
| Autorización | Existe o no es necesaria | No existe |
| Finalidad | Seguridad, periodismo, justicia, autoprotección | Acoso, fraude, extorsión, venganza |
| Proporcionalidad | Datos mínimos necesarios | Recopilación masiva o íntima |
| Transparencia | Se puede documentar y justificar | Se oculta |
| Consecuencias | Ninguna, si se cumple el RGPD | Multas del RGPD y penas de prisión |

> **Conclusión del apartado:** la herramienta no decide la legalidad. Shodan, Maltego o Google son legales. Lo que convierte una investigación en ilícita es **de dónde salen los datos, cómo se consiguen y para qué se usan**.

## 8. Cómo buscarte a ti mismo: comprobar si tus datos están expuestos

Hacerse un "autoanálisis OSINT" es la mejor forma de saber qué puede averiguar un desconocido sobre ti. Conviene hacerlo en dos niveles: lo que está en fuentes abiertas y lo que circula en filtraciones.

### 8.1 Nivel 1: fuentes abiertas (lo que cualquiera ve)

1. **Busca tu nombre completo entre comillas** en Google, Bing y DuckDuckGo: `"Nombre Apellido1 Apellido2"`. Prueba también combinaciones con tu ciudad, tu colegio o tu trabajo.
2. **Busca tu email, tu teléfono y tus alias (nombres de usuario)** entre comillas. Prueba `"tuemail@gmail.com"` y `"612345678"` (también con espacios: `"612 34 56 78"`).
3. **Busca tu nombre en boletines oficiales:** `"Nombre Apellidos" site:boe.es` y en el boletín de tu comunidad o provincia.
4. **Haz una búsqueda inversa de tu foto de perfil** en Google Lens o TinEye para detectar si alguien usa tus fotos en perfiles falsos.
5. **Comprueba tus nombres de usuario** en distintas plataformas: herramientas como *WhatsMyName* (whatsmyname.app) muestran en qué webs existe un usuario con ese nombre. Así descubres cuentas antiguas olvidadas.
6. **Mira tus redes como las vería un extraño**: Facebook e Instagram permiten ver tu perfil "como público". Revisa fotos antiguas, etiquetas y quién puede ver tu lista de amigos.
7. **Activa la herramienta "Resultados sobre ti" de Google** (en la app de Google o en myactivity.google.com/results-about-you): busca de forma periódica resultados con tu teléfono, email o dirección, te avisa y te permite pedir su retirada directamente.
8. **Crea una Alerta de Google** (google.com/alerts) con tu nombre para recibir un correo cuando aparezca algo nuevo.

### 8.2 Nivel 2: filtraciones y fuentes ilícitas

**Importante:** no hace falta (ni es recomendable) entrar en la dark web ni en canales de Telegram para buscarte. Además de peligroso (malware, estafas), comprar o descargar bases filtradas puede ser ilegal. Existen servicios legales que indexan esas filtraciones y te dicen si apareces, sin mostrarte los datos de otros.

| Servicio | Qué comprueba | Cómo se usa |
|---|---|---|
| **Have I Been Pwned** (haveibeenpwned.com) | Si tu email aparece en filtraciones conocidas (más de 14.000 millones de cuentas indexadas) y en cuáles | Escribe tu email. Te lista cada filtración, la fecha y qué datos se expusieron (contraseñas, teléfonos, direcciones…). Puedes suscribirte para recibir avisos de nuevas filtraciones. |
| **Have I Been Pwned – Passwords** | Si una contraseña concreta aparece en filtraciones | Escribe la contraseña; se comprueba de forma anónima (no se envía completa). Si aparece, no la uses nunca más. |
| **Mozilla Monitor** (monitor.mozilla.org) | Filtraciones asociadas a tu email | Gratuito, envía alertas. |
| **Comprobación de contraseñas de Google** (passwords.google.com) | Contraseñas guardadas en tu cuenta Google que han aparecido en filtraciones, que son débiles o están repetidas | Entra en "Revisión de contraseñas". |
| **Recomendaciones de seguridad del iPhone** (Ajustes > Contraseñas > Recomendaciones de seguridad) | Lo mismo para usuarios de Apple | Avisa de contraseñas filtradas. |
| **Gestores de contraseñas** (Bitwarden, 1Password, etc.) | Informes de contraseñas expuestas | Función de "informes" o "vigilancia". |
| **Servicios de antivirus** (por ejemplo, alertas de identidad de Bitdefender o Norton) | Rastreo de email, teléfono o DNI en filtraciones | Algunos son de pago. |

**Cómo interpretar el resultado:** si Have I Been Pwned te dice que tu email está en una filtración de, por ejemplo, 2019, mira **qué tipo de datos** se expusieron:
- Si incluye **contraseñas**: cambia esa contraseña en ese servicio y en todos los que la repitieras.
- Si incluye **teléfono o dirección**: espera intentos de phishing o smishing personalizados.
- Si incluye **datos bancarios o DNI**: avisa a tu banco y vigila posibles suplantaciones.

**Señales de alerta de que tus datos circulan:**
- Te llegan correos de "sextorsión" con una contraseña antigua tuya.
- Recibes SMS o llamadas de supuestos bancos que conocen tu nombre.
- Recibes códigos de verificación que no has pedido (alguien intenta entrar en tus cuentas).
- Te llegan notificaciones de inicios de sesión desde lugares desconocidos.
- Aparecen deudas, préstamos o contratos que no has firmado (posible suplantación de identidad).
- Tu móvil se queda de repente sin cobertura (posible SIM swapping): llama inmediatamente a tu operadora.

## 9. Cómo reclamar y borrar tus datos

El procedimiento depende de **dónde** estén tus datos. No es lo mismo una web española que publica tu teléfono que una base de datos en un foro de la dark web.

### 9.1 Paso 1: Reunir pruebas

Antes de pedir que se borre nada, guarda pruebas: **capturas de pantalla donde se vean la fecha y la URL completa**, enlaces y, si es posible, la página guardada. Si el caso es grave (acoso, amenazas, extorsión), se puede certificar el contenido con un notario o con servicios de evidencia digital (como eGarante), porque en un juicio una captura simple puede ser cuestionada.

### 9.2 Paso 2: Pedir la supresión al responsable

Si tus datos están en una web, un foro o una empresa identificable, puedes ejercer tus derechos del RGPD directamente:
- **Derecho de supresión** (art. 17 RGPD): que borren tus datos cuando ya no son necesarios, se tratan sin base legal o retiras tu consentimiento.
- **Derecho de oposición** (art. 21): que dejen de tratarlos.
- **Derecho de acceso** (art. 15): saber qué datos tienen y **de dónde los obtuvieron** (útil para saber quién vendió tus datos).

¿Cómo se hace? Busca en la web la "Política de privacidad" o el "Aviso legal" para encontrar el email del responsable o del Delegado de Protección de Datos (DPD). Envía la solicitud por un medio que deje constancia. Es **gratuito** y deben responder en **un mes** (ampliable dos meses más en casos complejos, avisándote). La AEPD tiene **formularios modelo** en su web.

**Modelo de solicitud:**
> Asunto: Ejercicio del derecho de supresión (art. 17 RGPD)
>
> D./Dña. [nombre y apellidos], con DNI [número] y domicilio a efectos de notificaciones en [email o dirección], mediante el presente escrito ejerzo el derecho de supresión previsto en el artículo 17 del Reglamento (UE) 2016/679 y en el artículo 15 de la LOPDGDD.
>
> He comprobado que en la dirección [URL] se publican los siguientes datos personales míos: [describir]. Este tratamiento se realiza sin mi consentimiento y sin base legal que lo legitime.
>
> Solicito la eliminación de dichos datos y que se me comunique, en el plazo de un mes, la supresión efectuada. Asimismo, ejerzo mi derecho de acceso para conocer el origen de los datos.
>
> En [ciudad], a [fecha]. Firma.

### 9.3 Paso 3: Desindexar en buscadores ("derecho al olvido")

Aunque una web no borre el contenido, puedes pedir que **no aparezca en los buscadores al buscar tu nombre**. Este derecho nació en 2014 con la sentencia del Tribunal de Justicia de la UE en el caso de un ciudadano español, Mario Costeja, contra Google (*Google Spain*), y hoy lo recoge el art. 93 de la LOPDGDD. Se aplica a información inadecuada, irrelevante, desfasada o excesiva.

- **Google:** formulario "Solicitud de retirada de información personal en virtud de la legislación europea de privacidad" y la herramienta "Resultados sobre ti" (para teléfono, email, dirección, documentos de identidad, datos bancarios o imágenes íntimas).
- **Bing:** formulario "Solicitud de bloqueo de resultados de búsqueda en Europa".

Si el buscador lo rechaza, puedes reclamar ante la AEPD.

### 9.4 Paso 4: Denunciar en la plataforma

Si el contenido está en una red social, usa sus herramientas de denuncia: "suplantación de identidad", "acoso", "información privada publicada", "imagen íntima sin consentimiento". Por la DSA, las plataformas que operan en la UE están obligadas a revisar estas denuncias y a justificar sus decisiones. Para imágenes íntimas, la herramienta **StopNCII.org** permite impedir que se suban a las principales redes sin tener que enviar la imagen (solo se genera una "huella" desde tu dispositivo).

### 9.5 Paso 5: Reclamar ante la AEPD

Si el responsable no responde en plazo, se niega o la situación es urgente, presenta una **reclamación ante la Agencia Española de Protección de Datos** en su sede electrónica (sedeagpd.gob.es). Debes adjuntar la solicitud que enviaste y la respuesta (o la falta de ella).

**Canal Prioritario de la AEPD:** está pensado para casos de **difusión de contenido sexual o violento** sin consentimiento (fotos o vídeos íntimos, agresiones). La AEPD puede ordenar su retirada urgente a las plataformas y webs, y además puede sancionar a quien lo difundió.

### 9.6 Paso 6: Denuncia penal

Si hay un delito (acceso a tus cuentas, acoso, amenazas, extorsión, suplantación de identidad, difusión de datos robados o de imágenes íntimas), **denuncia**:
- **Policía Nacional** (Brigada Central de Investigación Tecnológica): en comisaría o con la denuncia online en algunos delitos.
- **Guardia Civil** (Grupo de Delitos Telemáticos).
- **Policías autonómicas** (Mossos d'Esquadra, Ertzaintza).
- **Juzgado de guardia** o **Fiscalía** (Fiscalía de Criminalidad Informática).

La denuncia, además, sirve como prueba si en el futuro alguien usa tus datos para contratar algo a tu nombre.

### 9.7 ¿Y si tus datos están en una filtración en la dark web?

Hay que ser realistas: **los datos publicados en foros criminales no se pueden borrar**. Se copian y redistribuyen. Lo que sí se puede hacer es **dejarlos inservibles y minimizar el daño**:

1. **Cambia las contraseñas** afectadas y todas las que fueran iguales o parecidas.
2. **Activa la verificación en dos pasos (2FA)** en email, redes y banca, preferiblemente con una app (Google Authenticator, Microsoft Authenticator) o llave física, mejor que por SMS.
3. **Si se filtró tu DNI**, denuncia para tener constancia y vigila que no aparezcan contratos o préstamos a tu nombre. Puedes consultar si figuras en ficheros de morosos (ASNEF, Experian/Badexcom) ejerciendo tu derecho de acceso, y en la **CIRBE** del Banco de España para ver préstamos a tu nombre.
4. **Si se filtraron datos bancarios**, avisa a tu banco, bloquea o cambia la tarjeta y revisa movimientos.
5. **Reclama a la empresa que sufrió la brecha.** Por ley (arts. 33 y 34 RGPD), debe notificar la brecha a la AEPD en 72 horas y avisar a los afectados si hay riesgo alto. Puedes ejercer tu derecho de acceso para saber exactamente qué datos tuyos se expusieron, reclamar ante la AEPD si no actuó bien y pedir una **indemnización por daños** (art. 82 RGPD).
6. **Desconfía** de cualquier mensaje que use esos datos: tu banco nunca te pedirá claves por SMS o teléfono.
7. **Llama al 017**, la línea gratuita y confidencial de ayuda en ciberseguridad del INCIBE, que te orienta en cada caso.

### Resumen del procedimiento

```
1. Detectar (autoanálisis)  →  2. Guardar pruebas
→ 3. Pedir supresión al responsable (plazo: 1 mes)
→ 4. Desindexar en Google/Bing  →  5. Denunciar en la plataforma
→ 6. Reclamar ante la AEPD (Canal Prioritario si es urgente)
→ 7. Si hay delito: denuncia ante Policía/Guardia Civil
(Si es una filtración: cambiar contraseñas + 2FA + vigilar + reclamar a la empresa)
```

## 10. Cómo protegerse

Protegerse consiste en **reducir lo que se puede encontrar** (fuentes abiertas) y **limitar el daño de lo que se filtre** (fuentes ilícitas).

### 10.1 Reducir tu huella en fuentes abiertas

- **Pon tus redes en privado** y revisa la configuración cada cierto tiempo, porque las plataformas la cambian.
- **No publiques ubicación en tiempo real.** Sube las fotos del viaje cuando vuelvas, no mientras estás fuera (anuncia que tu casa está vacía).
- **Cuidado con lo que se ve en las fotos:** el portal, la matrícula, el uniforme del colegio de los niños, documentos sobre la mesa, la tarjeta de embarque (su código de barras contiene datos de la reserva).
- **Elimina los metadatos** de las fotos antes de enviarlas como archivo (la mayoría de redes los borran al subirlas, pero el envío como documento por WhatsApp o email los conserva). En el móvil, desactiva la ubicación en la cámara.
- **Revisa las apps deportivas** (Strava, Garmin): define "zonas de privacidad" alrededor de tu casa.
- **Usa alias y emails distintos** para registros poco importantes (o servicios de alias de correo).
- **Borra las cuentas antiguas** que ya no uses. Cada cuenta abandonada es una posible filtración futura.
- **No respondas a tests virales** ("¿cómo se llamaba tu primera mascota?") que coinciden con preguntas de seguridad.
- **Inscríbete en la Lista Robinson** (listarobinson.es) para reducir la publicidad no deseada.

### 10.2 Limitar el daño de las filtraciones

- **Contraseña única para cada servicio.** Es la medida más importante contra el *credential stuffing*. Para recordarlas, usa un **gestor de contraseñas** (Bitwarden, 1Password, el de Google o Apple).
- **Contraseñas largas**, mejor frases ("TortugaVerde-Bebe-Cafe-2026") que palabras cortas con símbolos.
- **Verificación en dos pasos** en todas las cuentas importantes, empezando por el **email** (quien controla tu email puede restablecer todas tus contraseñas).
- **Usa passkeys (llaves de acceso)** cuando el servicio lo permita: no hay contraseña que robar.
- **Suscríbete a las alertas** de Have I Been Pwned o Mozilla Monitor.
- **Pide a tu operadora un PIN o medidas extra** para solicitar duplicados de SIM.
- **Comparte tu DNI solo cuando sea obligatorio**, y si envías una copia, añade una marca de agua ("Copia para [empresa] – [fecha]") para que no pueda reutilizarse.

### 10.3 Protegerse de la ingeniería social

- **Desconfía de la urgencia:** "tu cuenta se bloqueará en 24 horas" es la frase típica de una estafa.
- **No pulses enlaces de SMS o emails**: entra en la web o app oficial escribiéndola tú.
- **Verifica por otro canal:** si "tu hijo" te escribe desde un número nuevo pidiendo dinero, llámale a su número de siempre. Algunas familias acuerdan una **palabra clave** para emergencias (útil frente a voces clonadas por IA).
- **Tu banco nunca te pedirá** contraseñas, PIN ni códigos SMS.
- **Revisa tu móvil** si sospechas de stalkerware: apps desconocidas, batería que se agota rápido, permisos de accesibilidad o administrador extraños. En caso de violencia de género, contacta con el **016**, que no deja rastro en la factura.

## 11. Conclusiones

1. **El OSINT en sí es legal y útil.** Es una herramienta fundamental para el periodismo, la seguridad, la justicia y la autoprotección.
2. **Que algo sea público no significa que cualquier uso sea legal.** Los datos personales siguen protegidos por el RGPD aunque estén publicados, y su recopilación y difusión con fines dañinos puede ser delito.
3. **La frontera entre lo lícito y lo ilícito la marcan cuatro factores**: el origen de los datos, la forma de acceder a ellos, la finalidad y la proporcionalidad. La herramienta empleada no decide la legalidad.
4. **Los métodos ilícitos** (filtraciones y su compraventa, credential stuffing, ingeniería social, phishing, doxing, stalkerware o explotación de vulnerabilidades) causan daños reales, como demuestran los casos de Facebook, Iberdrola, Santander o Alcasec, y están castigados por el Código Penal.
5. **Cualquier ciudadano puede actuar**: buscarse a sí mismo con herramientas legales como Have I Been Pwned, pedir la supresión de sus datos, ejercer el derecho al olvido, acudir a la AEPD y denunciar.
6. **Lo que llega a la dark web no se puede borrar, pero sí neutralizar**: contraseñas únicas, verificación en dos pasos y vigilancia.
7. **La prevención es la mejor defensa**: cuanta menos información compartamos y mejor protejamos nuestras cuentas, menos podrán averiguar y menos daño podrán hacer.

## 12. Bibliografía y recursos

**Legislación y jurisprudencia**
- Reglamento (UE) 2016/679, General de Protección de Datos (RGPD).
- Ley Orgánica 3/2018, de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD).
- Ley Orgánica 10/1995, del Código Penal (arts. 169, 172 ter, 197, 197 bis, 197 ter, 248, 401).
- Ley Orgánica 1/1982, de protección civil del derecho al honor, a la intimidad personal y familiar y a la propia imagen.
- Reglamento (UE) 2022/2065, de Servicios Digitales (DSA).
- STJUE de 13 de mayo de 2014, asunto C-131/12, *Google Spain SL y Google Inc. contra AEPD y Mario Costeja*.

**Organismos y recursos de ayuda**
- Agencia Española de Protección de Datos (AEPD): www.aepd.es (formularios para ejercer derechos, Canal Prioritario, guías).
- INCIBE, Instituto Nacional de Ciberseguridad: www.incibe.es · Línea de ayuda **017**. Oficina de Seguridad del Internauta (avisos de fraudes).
- Policía Nacional: www.policia.es · Guardia Civil: www.guardiacivil.es (Grupo de Delitos Telemáticos).
- Teléfono **016**, atención a víctimas de violencia de género.
- StopNCII.org (imágenes íntimas).

**Herramientas citadas**
- Have I Been Pwned: haveibeenpwned.com · Mozilla Monitor: monitor.mozilla.org
- Google "Resultados sobre ti" y Revisión de contraseñas (passwords.google.com)
- OSINT Framework: osintframework.com · WhatsMyName: whatsmyname.app
- Wayback Machine: web.archive.org · TinEye: tineye.com

**Lecturas recomendadas**
- Bellingcat, guías de investigación en fuentes abiertas (www.bellingcat.com).
- Bazzell, M., *OSINT Techniques: Resources for Uncovering Online Information*.
- Noticias sobre los casos citados: Facebook (2021), LinkedIn (2021), Iberdrola (2024), Banco Santander (2024), Telefónica (2025), Alcasec (2022-2023), Clearview AI y Cambridge Analytica (2018).
