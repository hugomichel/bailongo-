<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

</head>
<body><div class="container"><h1 id="readme"> <strong>README</strong></h1>

<p><strong>Bailongo!</strong></p>

<h2 id="qué-es">¿Qué es?</h2>

<blockquote>
  <p><em>Bailongo!</em>  es una aplicación móvil en la cual el usuario podrá encontrar lugares o eventos recomendados basados en su gusto musical, como lo son restaurantes, clubes nocturnos, bares, festivales y conciertos.</p>
  
  <blockquote>
    <p>La intención de <em>Bailongo!</em> es incrementar la oferta de entretenimiento para sus usuarios, permitiéndoles conocer nuevos lugares en donde suena música similar a la que escuchan frecuentemente, mientras tanto los dueños de estos lugares pueden atraer a nuevos clientes. De igual forma, la industria musical se vería beneficiada, ya que los usuarios de Bailongo recibirán información sobre los próximos conciertos de sus grupos favoritos cerca de ellos y también sobre nuevas bandas que podrían interesarles.</p>
  </blockquote>
  
  <p><strong>Cliente:</strong> Restaurantes, clubes nocturnos, bares, festivales de música y conciertos.</p>
  
  <p><strong>Product Owner:</strong> Hugo Alberto Michel Castillo, creador de <em>“Bailongo!”</em>.</p>
  
  <p><strong>Mercado y canales de distribución:</strong> Jóvenes de 18 a 35 años, comunicación directa con nuestros clientes, ofreciendo apps para iOS y Android por medio de la AppStore y la PlayStore (GooglePlay) completamente gratuita para los usuarios.. </p>
  
  <p><strong>Scope Definition:</strong> El Project Owner se va a encargar de contactar a los clientes para hacer una cita personal con ellos para ofrecerles <em>Bailongo!</em>, mostrandoles el gran potencial con el que cuenta nuestro producto para atraer una importante cantidad de clientes, en su mayoría nuevos. Si se llega a un acuerdo el cliente firmará un contrato para que su local o evento sea promocionado en nuestra aplicación, además, el cliente nos proporcionará la lista de canciones con las que se identifica el lugar, de esta forma se compara con la lista de canciones de nuestros usuarios y se les notificara si son compatibles para darles a conocer el establecimiento o evento.   </p>
  
  <p>El proyecto debe de incluir una guía de establecimientos y eventos que forman parte de nuestra clientela y potenciales clientes, otro atractivo principal de nuestro proyecto serán las promociones de los establecimientos, por lo tanto debemos de comunicarnos con nuestros clientes para mantener el registro de las promociones que ofrecerán en nuestra aplicación.</p>
</blockquote>

<h2 id="team">Team:</h2>

<blockquote>
  <ul>
  <li>Project Owner: Encargado de contactar a los clientes personalmente para ofrecerles <em>Bailongo!</em> y recibir retroalimentación que después será compartida con el equipo para mejorar la aplicación.</li>
  <li>Technical Writers: Dos, uno que esté trabajando junto con el developer de frontend y otro junto con los developers de backend.</li>
  <li>Project Manager: Uno que supervise el trabajo de todos.</li>
  <li>Developers: Tres, uno para el Frontend y dos para el Backend.</li>
  </ul>
</blockquote>

<h2 id="gantt">Gantt</h2>

<blockquote>
  <p>Para la realización de este proyecto se necesitarán dos meses y medio de tiempo, comenzando el 3 de julio del 2017 y terminando el 19 de septiembre del 2017.</p>
</blockquote>



<h2 id="economic-justification">Economic Justification:</h2>

<blockquote>
  <p>Considerando que realizaremos nuestro proyecto en un plazo de alrededor de dos meses y medio, la inversión necesaria debería de cubrir el salario de las personas que colaborarán con nosotros para la realización del mismo.</p>
  
  <p>Nuestro equipo está conformado por: </p>
  
  <blockquote>
    <ul>
    <li>2 Technical Writers</li>
    <li>1 PM</li>
    <li>3 Developers</li>
    <li>1 Project Owner</li>
    </ul>
  </blockquote>
  
  <p>Estimamos que necesitaríamos alrededor de 100 mil pesos al mes para poder cumplir con sus salarios, considerando que no todos nuestros colaboradores trabajan tiempo completo.</p>
  
  <p>Con este estimado necesitamos 250 mil pesos para contar con nuestro MVP (Minimum Viable Product). </p>
  
  <p>Para poder cubrir esta inversión inicial necesitamos contar con por lo menos 10 clientes los cuales aporten  mil pesos mensuales por anunciar sus establecimientos dentro de nuestra aplicación.</p>
  
  <p>Para obtener nuestro NPV(Net Present Value) usamos la siguiente fórmula: <br>
  tomando en cuenta una tasa de interés de 6.25%(BANXICO)</p>
  
  <blockquote>
    <p>NPV= -250,000 + 120,000(P/A, 6.25,1)= 167,000.00</p>
    
    <p>Podemos definir que es una inversión razonable ya que podriamos recuperar nuestra inversión en poco más de dos años si adquirimos por lo menos 10 clientes mensuales.</p>
  </blockquote>
  
  <p>PBP (Payback Period) = 250,000/120,000=2.083</p>
  
  Calculando el Internal Rate of Return de nuestro proyecto, encontramos que la tasa de descuento es de 7.3% la cual resulta atractiva para emprender el proyecto. 
  
  <blockquote>
    <p>IRR (Internal Rate of Return): <br>
        -250000 +(120000/(1+r)) + (120,000/(1+r)^2)=0 <br>
        r=7.3%</p>
  </blockquote>
</blockquote>



<h2 id="software-requirement-specifications">Software Requirement Specifications</h2>

<p>Requerimientos funcionales:</p>

<blockquote>
  <blockquote>
    <ul>
    <li>El usuario se registrará con su correo electrónico y contraseña de su preferencia. Al registrarse se le enviará un correo de confirmación al correo proporcionado.</li>
    <li>El usuario podrá conectar su cuenta de Spotify por medio de la API de Spotify para que la aplicación obtenga los datos musicales del usuario.</li>
    <li>Por medio de los datos musicales del usuario se le recomendarán lugares de acuerdo a los datos musicales del cliente.</li>
    <li>El usuario podrá realizar reservaciones en el local de preferencia. El cliente (local) deberá confirmar dicha reservación.</li>
    <li>Al ser confirmada una reservación se le notificará al usuario con un correo que incluye las especificaciones de la reservación.</li>
    </ul>
  </blockquote>
</blockquote>

<p>Requerimientos no-funcionales:</p>

<blockquote>
  <blockquote>
    <ul>
    <li>Bailongo! realizará sus funciones de manera eficiente y veloz. </li>
    <li>Al enfocarnos primeramente en el mercado local, estará en español, al expandirnos consideraremos una versión en inglés. </li>
    <li>Solo se podrá iniciar sesión en un dispositivo a la vez.</li>
    <li>La aplicación deberá estar siempre disponible.</li>
    <li>Los correos enviados por la aplicación deberán de llegar en máximo cinco minutos.</li>
    </ul>
  </blockquote>
</blockquote>

<p>Herramientas a utilizar:</p>

<blockquote>
  <p>Dentro de las herramientas que encontramos, consideramos que Waka-time es la ideal para utilizar con nuestros desarrolladores, ya que de esta manera podemos obtener la información necesaria sobre su rendimiento de trabajo, sin necesidad de invadir su privacidad. Igualmente la información que obtenemos, puede ser utilizada por los desarrolladores en el futuro, ya que así pueden dar a conocer su experiencia considerando el uso de cualquier entorno de desarrollo.</p>
</blockquote>

<p>Tickets:</p>

<blockquote>
  <p>Utilizaremos la metodología FCFS (First Come First Served) para administrar los tickets que nos envíen los usuarios, esto quiere decir que se revisarán los tickets conforme los vayamos recibiendo sin darle importancia a la relevancia del ticket. De esta manera los usuarios quedarán satisfechos cuando vean que se trabajó en su ticket rápidamente.</p>
</blockquote></div></body>
</html>
