# Project Title: Railway Reservation System - ZuulApp
This repository is about the Zuul configuration for implementing API gateway for the project.

<h2>Requirments: </h2>
<li>JDK 1.8 or later</li>
<li>Gradle 4+ or Maven 3.2+</li>
<li>SpringBoot <2.4.0</li>
<li>Used IntelliJ Idea as IDE</li>

<h2>Configuration Steps</h2>
<li>Go to /src/main/resources/application.properties</li>
<li>Against the name of the particular api, configure the url</li>
<li>To do that change the zuul.routes.{application name}.url</li>
<li>For Example, to configure login service, change the zuul.routes.loginRailway.url to the ip address and the port in which that service is running</li>

<h2>Demo</h2>
<li>To configure the bookAndSearch</li>
<p>zuul.routes.railwayRegistration.url=<b>http://10.177.68.53:8081/</b><p>
<li>Change the bold part to the ip address and port in which the service is running</li>
