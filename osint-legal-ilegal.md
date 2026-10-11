# OSINT: métodos lícitos e ilícitos

**Trabajo de investigación** — Marco legal de referencia: Unión Europea y España (RGPD, LOPDGDD, Código Penal).

---

## Índice

1. Introducción
2. ¿Qué es OSINT?
3. Marco legal aplicable
4. Métodos de OSINT lícitos
5. Métodos ilícitos o en zona gris
6. Diferencias clave entre lo lícito y lo ilícito
7. Cómo detectar si tus datos están expuestos
8. Cómo reclamar y borrar tus datos
9. Prevención y buenas prácticas
10. Conclusiones
11. Bibliografía y recursos

---

## 1. Introducción

La cantidad de información personal disponible en Internet crece cada año: redes sociales, registros públicos, foros, filtraciones de bases de datos… La **Inteligencia de Fuentes Abiertas (OSINT)** es la disciplina que recopila y analiza esa información. Se usa en periodismo, ciberseguridad, investigación policial o due diligence empresarial, pero también la emplean delincuentes para estafas, acoso o suplantación de identidad.

El objetivo de este trabajo es distinguir qué métodos de OSINT son legales y cuáles no, explicar en qué se diferencian y mostrar qué puede hacer una persona que encuentre sus datos en fuentes ilícitas.

## 2. ¿Qué es OSINT?

**OSINT (Open Source Intelligence)** es la obtención, análisis y uso de información procedente de **fuentes de acceso público**, sin necesidad de autorización especial ni de vulnerar ningún sistema.

**Ciclo de inteligencia OSINT:**
1. **Planificación**: definir qué se busca y con qué finalidad.
2. **Recolección**: obtener datos de las fuentes.
3. **Procesamiento**: ordenar, filtrar y verificar.
4. **Análisis**: relacionar datos y extraer conclusiones.
5. **Difusión**: entregar el informe a quien lo necesita.

**Usos legítimos:** ciberseguridad (pentesting autorizado, análisis de la superficie de ataque), periodismo de investigación (p. ej. Bellingcat), fuerzas de seguridad, prevención del fraude, verificación de noticias falsas (fact-checking) y estudios de mercado.

> Idea clave: que un dato sea *accesible* no significa que *cualquier uso* sea legal. La legalidad depende de **cómo** se obtiene y **para qué** se usa.

## 3. Marco legal aplicable

| Norma | Qué regula |
|---|---|
| **RGPD** (Reglamento UE 2016/679) | Tratamiento de datos personales: requiere base legal (art. 6), finalidad legítima, minimización. Reconoce derechos de acceso, supresión, oposición, etc. Los datos públicos *siguen siendo datos personales*. |
| **LOPDGDD** (Ley Orgánica 3/2018) | Adapta el RGPD en España; regula el derecho al olvido en buscadores y redes sociales (arts. 93 y 94). |
| **Código Penal** | Art. 197 (descubrimiento y revelación de secretos), 197 bis (acceso ilegal a sistemas), 197.7 (difusión de imágenes íntimas), 172 ter (acoso/stalking), 248-249 (estafa), 401 (usurpación de estado civil). |
| **Constitución Española** | Art. 18: derecho al honor, intimidad, propia imagen y protección de datos. |
| **LO 1/1982** | Protección civil del honor, intimidad y propia imagen. |
| **Ley de Propiedad Intelectual** y **Condiciones de uso** de plataformas | Pueden limitar el scraping masivo. |
| **Reglamento de Servicios Digitales (DSA)** | Obliga a las plataformas a tener mecanismos de notificación y retirada de contenidos ilegales. |

## 4. Métodos de OSINT lícitos

Son lícitos cuando la fuente es realmente pública, no se vulnera ninguna medida de seguridad y el uso tiene una finalidad legítima y proporcionada.

| Método | Ejemplos | Uso típico |
|---|---|---|
| **Búsqueda avanzada en buscadores** (Google dorks) | `site:`, `filetype:`, `intitle:` | Encontrar documentos publicados por una organización |
| **Registros públicos oficiales** | BOE, BORME, Registro Mercantil, Catastro (datos no protegidos), sentencias anonimizadas (CENDOJ) | Investigación empresarial, due diligence |
| **Redes sociales (perfiles públicos)** | Consultar publicaciones abiertas en X, LinkedIn, Instagram | Periodismo, selección de personal (con límites) |
| **Información técnica de dominios e infraestructura** | WHOIS, DNS, Shodan, Censys, certificados (crt.sh) | Ciberseguridad: auditar la propia exposición o con autorización |
| **Análisis de imágenes y geolocalización** | Búsqueda inversa (Google Lens, TinEye), metadatos EXIF de fotos públicas, Google Earth | Verificar noticias y desinformación |
| **Archivos web** | Wayback Machine | Recuperar versiones antiguas de webs |
| **Comprobar filtraciones propias** | Have I Been Pwned, Firefox Monitor | Saber si tus cuentas se han filtrado |
| **Herramientas de automatización** | Maltego, SpiderFoot, theHarvester (en ámbito autorizado) | Pentesting, informes de exposición |
| **Prensa, publicaciones académicas, datos abiertos** | datos.gob.es, hemerotecas | Investigación general |

**Condiciones para que sea lícito:**
- Finalidad legítima y definida (seguridad, interés periodístico, investigación autorizada).
- Respeto a la minimización: solo los datos necesarios.
- Si se tratan datos personales de forma sistemática, cumplir el RGPD (base legal, informar, conservar lo justo).
- Autorización por escrito del cliente en auditorías de seguridad.

## 5. Métodos ilícitos o en zona gris

### 5.1 Claramente ilícitos

| Método | Por qué es ilegal |
|---|---|
| **Acceso a cuentas ajenas** (adivinar contraseñas, usar credenciales filtradas) | Acceso ilegal a sistemas (art. 197 bis CP) |
| **Compraventa o uso de bases de datos filtradas/robadas** (foros de la dark web, canales de Telegram) | Tratamiento ilícito de datos; posible revelación de secretos y receptación |
| **Ingeniería social / pretexting** (hacerse pasar por otro para obtener datos) | Usurpación, estafa, revelación de secretos |
| **Phishing** | Estafa y acceso ilícito |
| **Doxing** (recopilar y publicar datos de una persona para exponerla o intimidarla) | Revelación de secretos, acoso, amenazas; infracción del RGPD |
| **Stalking / seguimiento persistente** con datos recopilados | Delito de acoso (art. 172 ter CP) |
| **Instalación de stalkerware o rastreadores (AirTags) sin consentimiento** | Revelación de secretos, acoso |
| **Explotar vulnerabilidades** para extraer datos (p. ej. IDOR, inyecciones) sin autorización | Acceso ilegal y daños informáticos |
| **Difundir imágenes íntimas** obtenidas aunque fuera con consentimiento | Art. 197.7 CP |

### 5.2 Zona gris (depende del uso)

- **Web scraping masivo** de perfiles públicos: puede violar el RGPD y las condiciones del servicio (caso Clearview AI, multado por varias autoridades europeas, entre ellas Italia, Francia, Grecia y Países Bajos).
- **Data brokers / buscadores de personas**: agregan datos públicos en perfiles; en la UE suele faltar base legal.
- **Perfilado de candidatos o empleados** revisando redes personales: la AEPD lo limita a lo profesional y proporcionado.
- **Cuentas falsas (sock puppets)** para investigar: habitual en investigación profesional, pero vulnera las condiciones de las plataformas y puede ser ilegal según el uso.
- **Consultar filtraciones** para investigación de seguridad: aceptable para notificar a afectados, no para explotar los datos.

## 6. Diferencias clave entre lo lícito y lo ilícito

| Criterio | OSINT lícito | OSINT ilícito |
|---|---|---|
| **Fuente** | Pública y accesible legalmente | Privada, robada o filtrada |
| **Forma de acceso** | Sin vulnerar seguridad ni engañar | Rompiendo contraseñas, engaño, malware |
| **Consentimiento/autorización** | Existe o no es necesario | No existe |
| **Finalidad** | Legítima (seguridad, periodismo, justicia) | Acoso, fraude, extorsión, exposición |
| **Proporcionalidad** | Solo los datos necesarios | Recopilación masiva o íntima |
| **Transparencia** | Se puede justificar y documentar | Se oculta |
| **Consecuencias** | Ninguna o cumplimiento normativo | Sanciones RGPD (hasta 20 M€ o 4 % de la facturación) y penas de prisión |

> **Regla práctica:** la diferencia no está solo en la herramienta (Maltego o Shodan son legales), sino en **la fuente, el método de acceso y la intención**. Una misma búsqueda puede ser legal para un periodista y delito si se usa para acosar.

## 7. Cómo detectar si tus datos están expuestos

1. **Haz egosurfing**: busca tu nombre, email, teléfono y alias entre comillas en varios buscadores. Configura **Alertas de Google** con tu nombre.
2. **Comprueba filtraciones**: [haveibeenpwned.com](https://haveibeenpwned.com), Mozilla Monitor, el gestor de contraseñas de Google/Apple.
3. **Búsqueda inversa de tus fotos** (Google Lens, TinEye) para detectar perfiles falsos.
4. **Revisa la privacidad de tus redes** y qué ve un desconocido.
5. **Herramienta "Resultados sobre ti" de Google**: avisa cuando aparecen tu teléfono, email o dirección.
6. **Servicios del INCIBE**: línea **017** de ayuda en ciberseguridad (gratuita y confidencial).

## 8. Cómo reclamar y borrar tus datos

### 8.1 Paso 1: Reúne pruebas
Antes de pedir la retirada, guarda **capturas de pantalla con fecha y URL**. Si es grave (acoso, extorsión), puede ser útil una certificación (notario o servicios de evidencia digital como eGarante).

### 8.2 Paso 2: Ejercer tus derechos ante el responsable (RGPD)
Escribe al responsable de la web o empresa (busca su política de privacidad o el contacto del **Delegado de Protección de Datos**):
- **Derecho de supresión** (art. 17 RGPD): borrado de tus datos.
- **Derecho de oposición** (art. 21): que dejen de tratarlos.
- **Derecho de acceso** (art. 15): saber qué datos tienen y de dónde los sacaron.

Tienen **1 mes** para responder (ampliable 2 meses más). Es gratuito. La AEPD ofrece modelos de formulario en su web.

**Modelo breve de solicitud:**
> D./Dña. [nombre], con DNI [nº], ejerzo mi derecho de supresión conforme al art. 17 del RGPD y solicito la eliminación de mis datos personales publicados en [URL], ya que se tratan sin mi consentimiento ni base legal. Adjunto copia de mi DNI. Solicito respuesta en el plazo legal de un mes.

### 8.3 Paso 3: Desindexar en buscadores ("derecho al olvido")
Aunque la web no borre el contenido, puedes pedir que no aparezca en buscadores al buscar tu nombre (STJUE caso *Google Spain/Costeja*, 2014, y art. 93 LOPDGDD):
- Google: formulario "Solicitud de retirada de información personal" y "Resultados sobre ti".
- Bing: formulario de "Solicitud de bloqueo de resultados de búsqueda en Europa".

### 8.4 Paso 4: Denunciar en la propia plataforma
Todas las redes sociales tienen opciones para denunciar suplantación, acoso o publicación de datos privados (obligatorio en la UE por la DSA).

### 8.5 Paso 5: Reclamar ante la AEPD
Si el responsable no contesta o se niega, presenta una **reclamación ante la Agencia Española de Protección de Datos** (sede.agpd.gob.es).
- **Canal prioritario de la AEPD**: para la difusión de contenido sexual o violento sin consentimiento; actúa de forma urgente para retirar el contenido.
- Si la web está fuera de la UE, la AEPD tiene menos capacidad, pero sí puede actuar sobre buscadores y plataformas que operan en Europa.

### 8.6 Paso 6: Vía penal
Si hay delito (acoso, extorsión, suplantación, publicación de datos robados, acceso a tus cuentas), **denuncia** ante:
- Policía Nacional (Unidad de Ciberdelincuencia, denuncia online o en comisaría).
- Guardia Civil (Grupo de Delitos Telemáticos).
- Juzgado de guardia o Fiscalía (Fiscalía de Criminalidad Informática).

### 8.7 Si tus datos están en una filtración (dark web)
No es posible borrar los datos de foros criminales, así que hay que **minimizar el daño**:
1. Cambia las contraseñas afectadas y las repetidas en otros servicios.
2. Activa la **verificación en dos pasos (2FA)**.
3. Si se filtró el DNI o datos bancarios: avisa al banco, vigila movimientos y valora denunciar para tener constancia ante posibles suplantaciones.
4. La empresa que sufrió la brecha **debe notificar a la AEPD en 72 h** y a los afectados si hay alto riesgo (arts. 33-34 RGPD); puedes reclamarle y pedir indemnización por daños (art. 82).
5. Desconfía de emails o SMS que usen tus datos (phishing dirigido).

### Resumen del procedimiento

```
Detectar → Guardar pruebas → Pedir supresión al responsable (1 mes)
   → Desindexar en buscadores → Denunciar en la plataforma
   → Reclamar ante la AEPD → Si hay delito: denuncia policial
```

## 9. Prevención y buenas prácticas

- Perfiles en redes en modo privado; revisar quién ve tu lista de amigos, ubicación y fecha de nacimiento.
- No publicar documentos (DNI, billetes, matrículas) ni fotos con ubicación en tiempo real.
- Eliminar metadatos EXIF de las fotos antes de compartirlas.
- Contraseñas únicas + gestor de contraseñas + 2FA.
- Usar emails alternativos para registros poco importantes.
- Darse de baja de la publicidad: **Lista Robinson** (listarobinson.es).
- Eliminar cuentas antiguas que ya no se usan.
- Hacer un "autoanálisis OSINT" periódico.

## 10. Conclusiones

- OSINT es una técnica **legal en sí misma** y muy útil para la seguridad, el periodismo y la justicia.
- La frontera con la ilegalidad la marcan **la fuente, el método de acceso, la finalidad y la proporcionalidad**. Que un dato sea público no da derecho a usarlo para cualquier fin.
- Los métodos ilícitos (filtraciones, accesos indebidos, doxing, ingeniería social) pueden constituir delitos y vulneran el RGPD.
- El ciudadano tiene herramientas eficaces: derechos RGPD, derecho al olvido, canal prioritario de la AEPD y vía penal.
- La mejor defensa es la **prevención**: reducir la huella digital.

## 11. Bibliografía y recursos

- Reglamento (UE) 2016/679 (RGPD).
- Ley Orgánica 3/2018 de Protección de Datos Personales y garantía de los derechos digitales (LOPDGDD).
- Código Penal español, arts. 172 ter, 197, 197 bis, 248, 401.
- STJUE de 13 de mayo de 2014, asunto C-131/12 (*Google Spain*).
- Agencia Española de Protección de Datos: www.aepd.es (guías y formularios de ejercicio de derechos; Canal Prioritario).
- INCIBE – Instituto Nacional de Ciberseguridad: www.incibe.es · línea 017.
- OSINT Framework: osintframework.com.
- Bellingcat, *Guías de investigación en fuentes abiertas*.
- Have I Been Pwned: haveibeenpwned.com.
