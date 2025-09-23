# TAREA: Historia de la Informática, Internet y Sociedad del Conocimiento



---

# 1. HISTORIA DE LA INFORMÁTICA

## La máquina de calcular de Pascal (pascalina)

- **Año de fabricación:** 1642 (primeros prototipos construidos por Blaise Pascal).

- **Descripción y funcionamiento (5 líneas):**  
  La pascalina es una calculadora mecánica que realiza sumas y restas mediante ruedas dentadas (ruedas numeradas del 0 al 9) conectadas por engranajes. Al girar una rueda se hacía avanzar la siguiente cuando se sobrepasaba la cifra 9 (retenedor de acarreo). Estaba construida principalmente en metal y madera y tenía una interfaz de ruedas y ventanillas para mostrar resultados.

  ![Pascalina ilustrativa](https://upload.wikimedia.org/wikipedia/commons/thumb/8/80/Arts_et_Metiers_Pascaline_dsc03869.jpg/1200px-Arts_et_Metiers_Pascaline_dsc03869.jpg)

- **¿Por qué no tuvo el éxito esperado?**  
  Era cara de fabricar, compleja de producir en serie y limitada (sólo sumas y restas básicas). Además su público objetivo (administraciones y mercaderes) no la adoptó masivamente por coste, tamaño y la falta de alfabetización técnica generalizada.

---

## La máquina analítica de Babbage

- **Año de diseño / fabricación:** c. 1830s (proyecto teórico y fragmentos construidos; nunca se completó por completo en su época).

- **Estructura y finalidad de la máquina:**  
  Máquina mecánica de vapor diseñada para realizar cálculos complejos automáticamente. Tenía unidades conceptuales similares a un ordenador moderno: **molinete (almacén) para datos**, **unidad de cálculo (la "máquina diferencial/analítica")**, y un **sistema de tarjetas perforadas** para controlar operaciones.

  ![Máquina analítica - ilustración](https://upload.wikimedia.org/wikipedia/commons/thumb/a/ac/AnalyticalMachine_Babbage_London.jpg/250px-AnalyticalMachine_Babbage_London.jpg)

- **Concepto de programa y algoritmo:**  
  Babbage ideó el uso de tarjetas perforadas para indicar secuencias de operaciones —eso es un **programa**— y la máquina debía ejecutar pasos bien definidos (un **algoritmo**), anticipando la idea de secuencias de instrucciones.

- **El papel de Ada Byron (Ada Lovelace):**  
  Ada tradujo y amplió notas sobre la máquina de Babbage e incorporó un ejemplo considerado el primer **algoritmo** destinado a ser ejecutado por una máquina. Por ello se le reconoce como la primera *programadora*.

- **Inconvenientes:**  
  Tecnología mecánica compleja y costosa; problemas de precisión y tolerancias; falta de financiación y apoyo; la precisión mecánica disponible en la época no permitía completar la máquina a escala funcional.

---

## La máquina universal de Turing

- **Idea principal:**  
  Propuesta por Alan Turing en 1936 como modelo teórico de una máquina capaz de **simular cualquier algoritmo** mediante una cinta infinita y una cabeza lectora/escritora. Introduce la noción de computabilidad y de una **máquina universal** que puede ejecutar cualquier programa codificado en la cinta.

  ![Máquina de Turing - esquema](https://www.researchgate.net/publication/320982510/figure/fig1/AS:559155770347520@1510324532578/Figura-3-Esquema-de-una-maquina-de-Turing-Fuente-Doodle-de-una-maquina-de-Turing.png)

- **Importancia:** Base teórica de la informática y de los límites de lo que es computable.

---

## La arquitectura de Von Neumann

- **Idea clave:**  
  Propuesta en los años 40: un ordenador con **memoria que almacena datos e instrucciones** (programa y datos en la misma memoria), una unidad de control, una unidad aritmético-lógica (ALU) y canales de E/S. Este esquema sigue siendo la base de la mayoría de ordenadores actuales.

  ![Arquitectura Von Neumann - esquema](https://upload.wikimedia.org/wikipedia/commons/thumb/2/2c/Eckert-Mauchly_%28von_Neumann%29_architecture.svg/330px-Eckert-Mauchly_%28von_Neumann%29_architecture.svg.png)

- **Consecuencia práctica:** Facilita la programación y la flexibilidad (el mismo hardware puede ejecutar distintos programas cargándolos en memoria).

---

## Los primeros ordenadores (breve explicación y fotografía comparativa)

> Estos primeros ordenadores nacieron por necesidades militares, científicas y de cálculo a gran escala (balística, criptoanálisis, modelos matemáticos).

### Colossus Mark I
- **¿Para qué se creó?**: Desarrollo británico (segunda guerra mundial) para descifrar mensajes cifrados de la máquina Lorenz.
- **Características:** Usaba válvulas de vacío y electrónica para procesamiento de señales; fue uno de los primeros computadores electrónicos programables (limitado y específico).

### ENIAC (Electronic Numerical Integrator and Computer)
- **¿Para qué se creó?**: EEUU, 1945 — originalmente para cálculos balísticos y series de tablas de tiro para el ejército.
- **Características:** Ocupaba una sala, usaba miles de válvulas de vacío, se programaba mediante cableado físico (plugboards) y conmutadores; muy rápido para su época.

### EDVAC (Electronic Discrete Variable Automatic Computer)
- **¿Para qué se creó?**: Proyecto sucesor de ENIAC que incorporó el concepto de almacenar instrucciones en memoria (inspirado por la arquitectura de Von Neumann).

![Foto comparativa: Colossus / ENIAC / EDVAC](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4b/Colossus.jpg/1200px-Colossus.jpg)

---

## Generaciones de ordenadores

- **Primera generación (≈ 1945–1956):** Válvulas de vacío (tubos). Características: gran tamaño, consumo energético enorme, calor, programación mediante cableado; usos militares y científicos.

- **Segunda generación (≈ 1956–1964):** Transistores. Características: menor tamaño, más fiabilidad, menor consumo, introducción de lenguajes de alto nivel como FORTRAN y COBOL.

- **Tercera generación (≈ 1964–1971):** Circuitos integrados (chips con múltiples transistores). Características: mayor miniaturización, multiprogramación, sistemas operativos más sofisticados.

- **Cuarta generación (≈ 1971–1980s):** Microprocesadores (CPU en un solo chip). Características: aparición de PCs, reducción de costes, computación personal masiva.

- **Quinta generación (≈ 1980s–actualidad en evolución):** IA, paralelismo, arquitecturas especializadas (GPUs, TPUs). Características: énfasis en procesamiento en paralelo, aprendizaje automático, grandes centros de datos y computación en la nube.

**Diferencia entre electrónica de vacío y electrónica de semiconductores:**  
- *Electrónica de vacío (válvulas):* control de corriente mediante tubos de vacío; voluminosas, frágiles, gran dissipación de calor.  
- *Electrónica de semiconductores (transistores y circuitos integrados):* control de corriente mediante materiales semiconductores (silicio), mucho más pequeños, eficientes, fiables y económicos.

---

# 2. HISTORIA DE INTERNET

> Breve desarrollo de los hitos clave: fecha y por qué importan.

- **ARPANET (1969):** Red financiada por ARPA (EE. UU.) para compartir recursos de cómputo entre universidades y centros de investigación; semilla de la red global.

  ![ARPANET - mapa conceptual](https://c8.alamy.com/comp/DHG67G/mountain-view-california-usa-09th-nov-2013-a-1983-map-of-the-arpanet-DHG67G.jpg)

- **TCP/IP (década de 1970 – estandarización 1983):** Conjunto de protocolos que permite el enrutamiento y la entrega de paquetes entre redes; pieza clave que permitió la interconexión de distintas redes.

- **INTERNET (años 80–90):** Conjunto interconectado de redes que adoptó TCP/IP; evolución de ARPANET y redes académicas/comerciales.

- **WWW (World Wide Web) y HTML (1989–1991):** Propuesta por Tim Berners-Lee: sistema de hipervínculos y un lenguaje de marcado (HTML) para acceder a documentos interconectados sobre HTTP; transformó Internet hacia una plataforma de información accesible.

- **Wandex y Mosaic (principios de los 90):** Mosaic (Netscape precursor) fue uno de los primeros navegadores gráficos que popularizó la web. (Wandex fue uno de los primeros índices/buscadores y experimentos de navegación.)

- **Internet 2.0:** Término usado para describir la evolución de la web hacia servicios interactivos, sociales y multimedia (redes sociales, APIs, web semántica, mayor interactividad). A veces se refiere a la segunda generación de servicios web.

---

## Personajes destacados

- **Leonard Kleinrock:** Trabajo pionero sobre conmutación de paquetes —fundamental para ARPANET.
- **Robert Kahn y Vinton Cerf:** Diseñadores clave de TCP/IP ("padres de Internet").
- **Bill Gates y Steve Jobs:** Figuras centrales del desarrollo del software y hardware personal (Microsoft y Apple), influencia en la adopción masiva de PCs y software comercial.
- **Tim Berners-Lee:** Inventor de la World Wide Web (HTTP, URLs, HTML).
- **Larry Page y Sergéi Brin:** Fundadores de Google, importantes por revolucionar la búsqueda y procesamiento de información en la web.
- **La magia de los garajes:** Anécdota cultural: muchas startups tecnológicas (Apple, HP, Google, Amazon, etc.) comenzaron de forma humilde en garajes o dormitorios, simbolizando innovación accesible.

---

# 3. LA SOCIEDAD DEL CONOCIMIENTO

## Información vs Conocimiento
- **Información:** Datos procesados, organizados, sin necesariamente interpretación profunda.
- **Conocimiento:** Información interpretada, entendida y aplicable; incluye contexto, experiencia y juicio.

## Domótica
- **Definición:** Automatización de tareas domésticas mediante sistemas electrónicos (control de luces, climatización, seguridad, persianas, electrodomésticos).

## Domótica vs IoT
- **Domótica:** Enfoque en automatización del hogar.
- **IoT (Internet of Things):** Concepto más amplio: dispositivos conectados (hogar, industria, ciudades) que intercambian datos por internet. La domótica puede ser una aplicación del IoT.

## Sensores y Actuadores
- **Sensores:** Detectan magnitudes físicas (temperatura, luz, movimiento, humedad, CO₂, presencia).
- **Actuadores:** Dispositivos que realizan acciones (motores, relés, válvulas, sirenas) en respuesta a señales.

## Comunicación
- Protocolos y redes que permiten que sensores, actuadores y sistemas se comuniquen (Wi-Fi, Bluetooth, Zigbee, LoRaWAN, Ethernet, 5G).

---

## Big Data
- **Concepto:** Conjuntos de datos tan voluminosos, variados o rápidos que requieren nuevas técnicas y herramientas para su captura, almacenamiento, procesamiento y análisis.
- **Origen de los datos:** Sensores IoT, registros de transacciones, logs web, redes sociales, transacciones financieras, imágenes, vídeo, sensores médicos, etc.
- **Algoritmos de machine learning (enumeración simple):** Regresión lineal, regresión logística, árboles de decisión, random forests, SVM, k-means, k-NN, redes neuronales, aprendizaje profundo (deep learning), clustering jerárquico.
- **Aplicaciones del Big Data:** Salud (detección precoz), marketing personalizado, análisis financieros, mantenimiento predictivo, ciudades inteligentes, seguridad, investigación científica.

## Consecuencias no deseables de la sociedad del conocimiento
- **La brecha digital:** Desigualdad en acceso a tecnología e información.
- **Ciberdelincuencia:** Fraudes, robos de identidad, hacking.

## Malware y delitos informáticos (breve listado)
- **Malware:** virus, gusano, troyano, rootkit, ransomware (ej.: WannaCry), adware, spyware, keyloggers.
- **Spam y Hoax:** correos no deseados y bulos virales.
- **Ciberacoso:** ciberbullying y sexting (problemas sociales y legales juveniles).
- **Técnicas de ataque:** phishing (correo fraudulento), smishing (SMS fraudulento), pharming (redirigir tráfico DNS), ataques DDoS (botnets), hijacking (secuestro de sesiones), man-in-the-middle, escalado de privilegios.

## Seguridad: herramientas y prácticas
- **Antivirus/antimalware, firewalls (cortafuegos), proxies, VPNs.**
- Buenas prácticas: actualizaciones, backups, autenticación fuerte (2FA), cifrado, educación del usuario.

---

# BIBLIOGRAFÍA CONSULTADA (sugerida)

_Enlaces generales que puedes usar para ampliar:_

- https://es.wikipedia.org/wiki/Historia_de_la_inform%C3%A1tica
- https://es.wikipedia.org/wiki/Blaise_Pascal
- https://es.wikipedia.org/wiki/Charles_Babbage
- https://es.wikipedia.org/wiki/Ada_Lovelace
- https://es.wikipedia.org/wiki/Alan_Turing
- https://es.wikipedia.org/wiki/Arquitectura_de_von_Neumann
- https://es.wikipedia.org/wiki/ENIAC
- https://es.wikipedia.org/wiki/Colossus_computer
- https://es.wikipedia.org/wiki/ARPANET
- https://es.wikipedia.org/wiki/Internet
- https://es.wikipedia.org/wiki/World_Wide_Web
- https://es.wikipedia.org/wiki/Tim_Berners-Lee
- https://es.wikipedia.org/wiki/Big_data

---

*Fin del documento.*

