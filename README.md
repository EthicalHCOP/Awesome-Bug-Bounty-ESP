# Awesome-Bug-Bounty-ESP

## Tabla de contenidos

- [¿Que es bug bounty?](#Que_es)
- [Conceptos comunes y básicos en el bug bounty.](#Conceptos)
- [Inicios y evolución del Bug Bounty.](#Historia)
- [Plataformas más conocidas para trabajar en el bug bounty.](#Plataformas)
- [Programas bug bounty más concurridos.](#Programas)
- [Herramientas usadas en el Bug bounty.](#Herramientas)
  - [Enumeración de directorios](#Enumeracion_de_directorios)
  - [Enumeracion de dominios y subdominios](#Enumeracion_de_dom_y_subdom)
  - [Escaners web / proxy](#Escaners_web)
  - [Escaners de CMS](#Escaners_de_CMS)
  - [Motores de busqueda de hosts](#Motores_de_busqueda_de_hosts)
  - [Analisis y Explotacion de vulnerabilidades](#Analisis_y_Explotacion_de_vulnerabilidades)
  - [Otras](#Otras)
- [Metodologias implementadas.](#Metodologias)

##

### ¿Que es Bug Bounty?

El bug bounty es una forma muy conveniente y eficiente para que las empresas prueben de manera continua la seguridad en sus activos informáticos, ya que cuenta con el respaldo de una comunidad de testers de seguridad, que analizan la aplicación en todo momento en búsqueda de errores y fallos que puedan comprometer la seguridad de los activos informáticos expuestos en internet.
Sin importar si la empresa ofrece su propio programa de bug bounty o emplea una plataforma que brinde este servicio, el bug bounty da un acceso a una base de talento mucho mayor que las compañías tradicionales de seguridad.
Es decir, el bug bounty permite la conexión entre hackers y clientes quien tienen la necesidad de descubrir fallos de seguridad en sus aplicaciones.

También puedes leer:
- [what is bug bounty](https://hacken.io/research/education/what-is-bug-bounty-bug-bounty/)
- [Bug bounty, ¿solo una moda o ha llegado para quedarse?](https://empresas.blogthinkbig.com/bug-bounty-ciberseguridad/)
- [Que son los programas bug bounty](https://www.ticbeat.com/seguridad/qu-son-los-bug-bounty-programs/)

### Conceptos comunes y básicos en el Bug Bounty. 

Si bien la mayoría de programas de bug bounty que existen son públicos, en donde cualquier persona con la capacidad de encontrar bugs puede acceder al programa, algunas otras empresas optan por realizar programas privados en donde el acceso es mediante alguna recomendación o invitación y sus reglas/normas sobretodo en cuanto a la confidencialidad son mucho más estrictas.  

El bug bounty utiliza y obedece al término de CrowdSourcing (Crowd: grupo/multitud, OutSourcing: ayuda/abastecimiento/colaboración externa) para lograr el contacto entre quienes hacen y solicitan las pruebas, entregando una recompensa monetaria por bug aceptado al tester.

### Inicios y evolución del Bug Bounty.

El primer programa de bug bounty fue creado por la compañía ‘hunter ready’ en el año 1983, para su sistema operativo ‘Versatile Real-Time Executive (VRTX)’. La recompensa por encontrar un bug en dicho sistema, consta de un automóvil ‘Volkswagen Beetle’.

Sin embargo, en 1995,  el ingeniero de soporte tecnico en Netscape ‘Jarrett Ridlinghafer’, acento el término de ‘bug bounty program’ al presentar una propuesta ante la compañía en donde según sus estudios, habían ingenieros de software que arreglaban los errores por su propia cuenta. Así que propuso un programa de recompensas de bugs más estructurado en donde una de sus características que más resalta es recompensar a los usuarios que reporten los bugs ​​con un premio en efectivo y su valor varía dependiendo de la clase de error.

En el 2002,  la empresa de seguridad IDefense implementó su propio programa y aumento las recompensas hasta con 400 $USD por cada informe de vulnerabilidades. En los años posteriores, diferentes empresas fueron creando sus propios programas bug bounty con mejoras y recompensas cada vez más altas.
Algunos ejemplos de compañías son: 
- 2004: mozilla / firefox ofrece recompensas de hasta 500 $USD.
- 2007: concurso pwn2own con un premio mayor de 10,000 $USD.
- 2010: Google impulsa el bug bounty hacia la web.
 -2011: Facebook ofrecerá recompensas desde 500 $USD, sin límite máximo. 
Hasta la fecha, muchas empresas más han creado sus programas de bug bounty o se ha hecho intermediaria entre las partes para brindar este servicio. Empresas como HackerOne, VulnScope, BugCrowd o SynAck, lideran el mercado del bug bounty con miles de usuarios inscritos en sus plataformas haciendo pruebas a centenares de empresas clientes.

También puedes leer:
- [¿Qué son los ‘Bug Bounty Programs’?](https://derechodelared.com/bug-bounty-programs/)

### Plataformas más conocidas para trabajar en el Bug Bounty.

Aunque hay empresas que manejan de manera interna sus programas de bug bounty, hay empresas que se dedican a hacer un contacto entre quien solicita las pruebas y quien las haga. Mediante una plataforma web, hackers y empresas pueden realizar dicho contacto y reportar las fallas de seguridad de una manera más centrada, directa y responsable.
Las plataformas mas conocidas y usadas para el bug bounty son:

- [Hackerone](https://hackerone.com/users/sign_up): Creada en el 2012 por Michiel Prins, Jobert Abma, Alex Rice y Merijn Terheggen, hackerone cuenta con aproximadamente 480 programas bug bounty y ha pagado mas de 31 millones $USD en recompensas.

- [BugCrowd](https://bugcrowd.com/user/sign_up): Tambien fundada en el 2012 por Casey Ellis, Chris Raethke y Sergei Belokamen. Bugcrowd se considera una de las plataformas mas grandes con mas de 800 programas disponibles.

- [SynAck](https://www.synack.com/contact/): Jay Kaplan y Mark Kuhr, ex-empleados de la NSA, crearon en el 2013 la plataforma de bug bounty SynAck.

- [VulnScope](https://app.vulnscope.com/signup/hacker): Creada en chile en el año 2017, vulnscope es una plataforma de bug bounty mas conocida y usada en america latina. 

- [SafeHats](https://app.safehats.com/signup): Creada por la compañia de seguridad InstaSafe en el 2012.

- [ZeroDayIniciative](https://www.zerodayinitiative.com/portal/register/): Creada en el 2005 y con una metodologia de trabajo diferente a otras plataformas. [leer mas.](https://resources.infosecinstitute.com/the-zero-day-initiative/)

- [Hackenproof](https://hackenproof.com/users/new): Creada tambien en el año 2017, hackenproof contiene proyectos que varian entre entornos web, mobil y blockchain.

- [Intigriti](https://login.intigriti.com/account/register): Fundada en el 2016, cuenta con aproximadamente, intigriti cuenta con aproximadamente 8000 analistas de seguridad.

### Programas Bug Bounty más concurridos.

Tomando en cuenta que en la plataforma BugCrowd existen un listado con más de 800 programas bug bounty, podremos decir que en realidad son más de 1000 programas de bug bounty entre públicos y privados en otras plataformas y diversas compañías que ofrecen dicho servicio.
Sin embargo, es de resaltar algunos programas que actualmente son los más concurridos o en donde se reportan más bugs tales como:

- [Uber](https://hackerone.com/uber): Uber paga recompensas de entre 500 a 50,000 $USD por bug encontrado.

- [Google](https://www.google.com/about/appsecurity/reward-program/): Con un rango de recompenzas entre 100 a 31,337 $USD.

- [Facebook](https://www.facebook.com/whitehat): Sin un limite maximo de recompenza, facebook ha pagado bugs desde 500 $USD y el maximo hasta el momento ha sido de 60,000 $USD.

- [Apple](https://developer.apple.com/security-bounty/): Pagando desde 5,000 $USD hasta 1,000,000 $USD apple es uno de los programas bugbounty mejor pagados hasta el momento.

- [Microsoft](https://www.microsoft.com/en-us/msrc/bounty): Microsoft oferta subprogramas en su programa de bug bounty con pagos desde 15,000 $USD hasta 300,000 $USD.

- [Twitter](https://hackerone.com/twitter): Twitter ofrece entre 140 $USD a 20,160 $USD por reporte segun su categoria.

- [Mozilla](https://www.mozilla.org/en-US/security/bug-bounty/): Mozilla maneja 2 tipos de programas bug bounty, uno para firefox y otro para los servicios y paginas propios de mozilla. Paga recompensas entre 500 $USD a  3,000 $USD.

- [Intel](https://www.intel.com/content/www/us/en/security-center/bug-bounty-program.html): Con mas de 800,000 $USD de recompensas totales pagadas, intel paga entre 500 a 100,000 $USD por bug segun el riesgo que represente.

- [Paypal](https://hackerone.com/paypal): Entre 50 y 20,000 $USD paypal paga a los investigadores por bug encontrado segun la gravedad determinada por CVSS v3.0, ya sea en sus plataformas web o moviles.

- [Github](https://hackerone.com/github): Github ofrece recompensas desde 617 $USD hasta 30,000 $USD segun el riesgo que represente el bug.

En muchos de estos programas , las recompensas en van desde los 50 $USD hasta los 1,000.000 $USD, pero en algunos otros las recompensas no tienen límite mínimo o máximo de recompensa.
Otros programas que es de importancia nombrar son: [Apache](https://hackerone.com/apache), [Apache http](https://hackerone.com/ibb-apache), [Cisco](https://hackerone.com/cisco), [Dropbox](https://hackerone.com/dropbox), [Yahoo](https://hackerone.com/verizonmedia), [Vimeo](https://hackerone.com/vimeo), [Avast](https://www.avast.com/bug-bounty), [Starbucks](https://hackerone.com/starbucks), [AT&T](https://hackerone.com/att), [Linkedin](https://hackerone.com/linkedin), [WordPress](https://hackerone.com/wordpress), [Joomla](https://hackerone.com/joomla). También hay programas para móviles como el de la [play store de google](https://hackerone.com/googleplay), [Samsung mobile bug bounty](https://security.samsungmobile.com/rewardsProgram.smsb), [Huawei](https://hackerone.com/huawei), [Pillar Project Worldwide](https://hackerone.com/pillarproject/) o GovTech Singapore.


### Herramientas usadas en el Bug bounty.

Una de las recomendaciones más comunes para las personas que estamos iniciando en el bug bounty, es ingresar y empaparse un poco del mundo de los CTF. No solo porque ahi conoceras un poco mejor técnicas para vulnerar algún sistema, sino que también vas a adquirir práctica en el uso de algunas herramientas para conseguir las banderas. En el bug bounty, tenemos la posibilidad de utilizar gran parte de estas herramientas y utilizar algunas otras herramientas que han sido construidas específicamente para facilitar el proceso para encontrar el bug.

Dependiendo de la necesidad del tester, hay herramientas que nos podran ayudar a encontrar una falla o a analizar algo en especifico, algunas de estas son:

Deserializacion:
- [Java-Deserialization-Cheat-Sheet](https://github.com/GrrrDog/Java-Deserialization-Cheat-Sheet)
- [ysoserial](https://github.com/frohoff/ysoserial)
- [ysoserial.net](https://github.com/pwntester/ysoserial.net)
- [Java Deserialization Scanner](https://github.com/federicodotta/Java-Deserialization-Scanner)

Enumeracion de directorios:
- [Dirb](https://github.com/v0re/dirb)
- [DirBuster](https://github.com/KajanM/DirBuster)
- [DirHunt](https://github.com/Nekmo/dirhunt)
- [Dirsearch](https://github.com/maurosoria/dirsearch)
- [Gobuster](https://github.com/OJ/gobuster)

Enumeracion de dominios y subdominios:
- [Dig](https://github.com/enjoyhot/dig)
- [DNSenum](https://github.com/fwaeytens/dnsenum)
- [Subfinder](https://github.com/projectdiscovery/subfinder)
- [Amass](https://github.com/OWASP/Amass)

Escaners web / proxy:
- [Burp Suite](https://portswigger.net/burp/communitydownload)
- [ZAP](https://www.zaproxy.org/)
- [IronWasp](https://resources.infosecinstitute.com/ironwasp-part-1-2/)
- [W3af](http://w3af.org/)

Escaners de CMS:
- [WPscan](https://github.com/wpscanteam/wpscan)
- [JoomScan](https://github.com/rezasp/joomscan)
- [CMSmap](https://github.com/Dionach/CMSmap)
- [Droopescan](https://github.com/droope/droopescan)

Motores de busqueda de hosts:
- [Shodan](https://www.shodan.io/)
- [Censys](https://censys.io/)
- [Zoomeye](https://www.zoomeye.org/)
- [GreyNoise](https://viz.greynoise.io/)

Analisis / Explotacion de vulnerabilidades:

- XSS
    - [XSSHunter](https://github.com/mandatoryprogrammer/xsshunter)
    - [BruteXSS](https://github.com/rajeshmajumdar/BruteXSS)
    - [XSSer](https://github.com/epsylon/xsser)
    - [XSStrike](https://github.com/s0md3v/XSStrike)
- SQLinjection
    - [Sqlmap](http://sqlmap.org/)
    - [JSQLi](https://github.com/ron190/jsql-injection)
    - [BBqSQL](https://github.com/Neohapsis/bbqsql)
    - [NoSQLMap](https://github.com/codingo/NoSQLMap)
- LFI 
    - [LFISuite](https://github.com/D35m0nd142/LFISuite)
    - [Kadimus](https://github.com/P0cL4bs/Kadimus)
    - [Fimap](https://tools.kali.org/web-applications/fimap) 
- JWT
    - [JWT.io](https://jwt.io/)
    - [JWT_Tool](https://github.com/ticarpi/jwt_tool)
    - [jwtcrack](https://github.com/Sjord/jwtcrack)
    - [c-jwt-cracker](https://github.com/brendan-rius/c-jwt-cracker)
     
Y algunas otras herramientas como:
- [Curl](https://curl.haxx.se/download.html): 
  Script en linea de comandos para transferencia de datos.
- [Geekflare](https://geekflare.com/):
  Herramienta en linea para el analisis de buenas practicas
- [Wfuzz](https://github.com/xmendez/wfuzz)
  Escáner de contenido web.
- [Wappalyzer](https://www.wappalyzer.com/):
  Escaner de tecnologias en sitios web.
- [Wafw00f](https://github.com/EnableSecurity/wafw00f)
  Identificador de Web Application Firewall (WAF).
- [builtwith](https://builtwith.com/)
  Identificador de tecnologias en sitios web
- [HackBar](https://hackbar.site/)
  Plugin para chrome o firefox para el analisis y explotacion de vulnerabilidades web

Sin embargo, podemos encontrar que algunos analistas de seguridad han hecho sus propias herramientas o su propio set de herramientas, en donde encontraremos estas tools anteriormente mencionadas y algunos desarrollos específicos para romper alguna vulnerabilidad o verificar si el sistema es vulnerable.
Algunos repositorios y sitios web poseen set de herramientas o listas las cuales pueden ser bastante útiles en el momento de una auditoría.

- https://github.com/ethicalhackingplayground/Bug-Bounty-Tools
- https://github.com/AlexisAhmed/BugBountyToolkit
- https://github.com/AlexisAhmed/BugBountyTools
- https://github.com/wwwarrior/BugBounty
- https://bugbountyforum.com/tools/
- https://github.com/SecFathy/Bugzee
- https://github.com/DaniLabs/tools-tbhm

Es de recalcar que no hay ninguna herramienta mágica que te servirá a la primera para vulnerar tus objetivos, también se trata de ir probando con herramientas que se acomoden a la explotación en proceso, ejemplo: si un servidor web te esta bloqueando el escaneo de directorios con dirbuster, puedes usar dirhunt para evitar hacer la fuerza bruta en el servidor. 


### Metodologias implementadas.

En el 2020, se ha lanzado la metodologia Bug Bounty en la version 4, sin embargo, a lo largo de diferentes sitios web y comunidades se pueden encontrar diversos aportes acerca de metodologias implementadas. Estas son algunas:
-[The Bug Hunter's Methodology v4.02 by jhaddix](https://www.youtube.com/watch?v=gIz_yn0Uvb8)
-[The Bug Hunter's Methodology v4 by 0x0G](https://www.youtube.com/watch?v=qLTe6Z10vj8)
-[Newbie bug bounty hunter recon methodology](https://igbinosuneric.medium.com/newbie-bug-bounty-hunter-recon-methodology-971396531cbc)
-[The Bug Hunter's Methodology (TBHM)](https://github.com/jhaddix/tbhm)
-[Bug Hunting Methodology (part-1)Updated on 4-Jan-2020](https://blog.usejournal.com/bug-hunting-methodology-part-1-91295b2d2066)

