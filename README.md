<head>
<h1 align="center">Arduino/Radar</h1> 
</head>
<h3 align="center"> Ein Projekt von Patric Heil und Liam Limberts</h3>
<h3 align="left">Stormarnschule Ahrensburg <br/> Informatik, Bl <br/> Schuljahr 2022/23, 2. Halbjahr </br> </h3> </div>
<h3 align="left"> &#10132; <a href="https://github.com/liamlimberts/Schulprojekt"> Stundenprotokolle</a> </h3> 

<br>
<hr>
<h3>Navigation</h3>

<b>1. Grundlagen</b>	

<ul>
	<li> <a href="#Team"> Das Team </a> </li>
	<li> <a href="#Programme"> Verwendete Programme </a> </li>
	<li> <a href="#Lernprozess"> Erlenen der benötigten Fähigkeiten </a> </li>
</ul>

<b>2. Das Projekt</b>	

<ul>
	<li> <a href="#Idee"> Die Idee </a> </li> 
	<li> <a href="#Entwicklungsprozess"> Entwicklungsprozess </a> </li>
	<li> <a href="#Software"> softwaretechnische Umsetzung </a> </li> 
	<li> <a href="#Produkt"> Das Endprodukt </a> </li>
</ul>

<b>3. Reflexion</b>

<ul>
	<li> <a href="#Reflexion"> Reflexion und Fazit des Projektes </a> </li>
	<li> <a href="#Ausblick"> Ausblick auf kommende Veränderungen </a> </li>
</ul>

<hr>

<h4> <a id="Team"> &#10122; &nbsp Das Team</a> </h4>
Als gute Freunde haben sich Patric und Liam zu einem Team zusammengeschlossen. Beide hatten wenig bis garkeine Vorkenntnisse, was das Programmieren angeht mit dem Arduino. Da jedoch bei beiden das Interesse am programmieren mit dem Arduino geweckt wurde, aufgrund des Projekts von Philipp Rinne und Arvid Spät, haben sie sich zusammen dazu entschlossen es auch einmal mit dem programmieren eines Arduinos zu probieren. 

<h4> <a id="Programme"> &#10122; &nbsp Verwendete Programme</a> </h4>
Zur präzisen Umsetzung und ansprechenden Dokumentation wurde eine Vielzahl von verschiedenen Programmen benutzt und dessen Handhabung erlernt.

<ul>
	<li>Arduino </li>
	Diese Sofware stellt die Basis von unserem Projekt dar. Mit der Software Arduino konnten wir alles was wir uns vorstellten auf den kleinen Computer übertragen, sodass dieser dann im optimal fall das macht was wir uns vorstellen.
	<li>Paint </li>
	Auf Paint haben wir unsere Pläne  für unser Computerprogramm skizziert.
	<li>Snipping Tool </li>
	Mit diesem Programm konnten wir Fotos von unserem Bildschirm machen, um diese Fotos anschließend in unsere Projektseite oder unser Stundenprotokoll einzufügen
	<li>Github </li>
	GitHub ist eine Software zur Versionsverwaltung von Software. Für dieses Projekt wurde GitHub für die Dokumentation genutzt, um Stundenprotokolle, eine Art Tagebuch für jede Stunde, und eine Projektseite, eine Zusammenfassung des Halbjahresprojektes, zu erstellen. 

</ul>

	
	
	
<h4> <a id="Lernprozess"> &#10122; &nbsp Erlernen der benötigten Fähigkeiten</a> </h4>
Für das Zusammenstecken des Arduino, dem Servo-Motor und des Entfernungsmessers mussten wir uns erst Grundlegend mit dem Arduino vertraut machen. Wir haben mithilfe von YouTube Videos und Internetseiten verschiedene Tests mit dem Arduino UNO durchgeführt. Zu diesen gehörte ein LED zu blicken bringen bzw. es schneller und langsamer blinken zu lassen. Außerdem konnten wir durch unseren ersten Anlauf für ein Radar mithilfe eines Bewegungsmelders erste Erkenntnisse gewinnen. Hauptsächlich haben wir uns über YouTube und Internetseiten informiert über Aufbau und das Coden. Fehlermeldungen im Arduino Code konnten wir beheben indem wir die Fehlermeldungen kopiert und im Internet nach Lösungen gesucht haben. Durch diese Methode konnten wir ein breiteres Verständnis für den Code aufbauen und zukünftige Fehler vermeiden.



<hr>

<h4> <a id="Idee"> &#10123; &nbsp Die Idee</a> </h4>

Auf das Programieren mit Arduino waren wir durch Philipp und Arvid gestoßen. Zu erst hatten wir keinen genauen Plan was wir überhaupt prgrammieren wollen. Wir hatten erst überlegt einen Computer so zu programmieren das uns verschiedene farben auf einem Bildschirm angezeigt werden, wenn man entsprechende Tasten auf einer Tastatur drückt, haben diesen Gedanken jedoch sehr schnell wieder verworfen, da es uns dann doch zu kompliziert erschien. Also haben wir nach einer vermeindlich etwas leichteren zu bewerkstelligen Aufgabe für uns gesucht. Dabei kamen wir dann darauf einen Radar zu programmieren und da uns das noch zu simple erschien wollten wir das sich dieser auf einem servo Motor dreht und uns auf einem Bildschirm gezeigt wird wo dieser Gegenstand, der vom Radar erfasst wurde, gerade ist.


<h4> <a id="Entwicklungsprozess"> &#10123; &nbsp Entwicklungsprozess</a> </h4>

Der Entwicklungsprozess startete am 16.8.2022, der ersten Informatikstunde mit einer Brainstormingphase und dem Aufgreifen der Idee eines Spiels. Innerhalb der nächsten Stunden, kristallisierte sich herraus, das wir eine Art Jump and Run Spiel programmieren wollten. Daraufhin folgte ein viermonatiger Entwicklungsprozess, wo wir unsere Plänse und Gedanken, zur Wirlichkeit werden lassen konnten. Anfangs konnten wir guten Fortschritt vermerken, doch nachdem wir die Integrierung des Spielers und dessen Steuerung fertig hatten, mussten wir aufgrund von Problemen fast alles nochmal machen, da wir zu diesem Zeitpunkt einen anderen Weg für unser Spiel eingeschlagen hatten.

<h4> <a id="Software"> &#10123; &nbsp softwaretechnische Umsetzung </a> </h4>
Die Aufgabe unsere Codes ist es den Servo-Motor und den Entfernungsmesser zu steuern.

Damit der Arduino UNO mit dem Entfernungsmesser und dem Servo-Motor verbunden ist und die Teilkomponenten mit Strom versorgt sind haben wir diese mithilfe eines Steckbrettes und vielen Kabeln miteinander Verbunden.

Die Aufgabe des Servo-Motors ist es sich in einem 180 Grad Winkel dauerhaft von links nach rechts und wieder zurück zu bewegen, damit Objekte in einem 180 Grad Radius erfasst werden können. Dazu steht im Code wieweit und wie schnell bzw. mit welcher Verzögerung sich der Servo-Motor bewegen soll. 

Der Entfernungsmesser ist so programmiert, dass dieser auf eine im Vorhinein bestimmte Entfernung anspricht. Dazu wurde das Serial Monitor Tool benutzt um, dies visuell zu zeigen. Wenn sich ein Objekt hinter der festgelegten Grenze befindet, schreibt der Serial Monitor in einem bestimmten Takt eine 0 an. Unterschreitet das Objekt jedoch die Grenze, schriebt der Serial Monitor lauter Zahlen.

Die Aufgabe unsere Codes ist es den Servo-Motor und den Entfernungsmesser zu steuern.

Damit der Arduino UNO mit dem Entfernungsmesser und dem Servo-Motor verbunden ist und die Teilkomponenten mit Strom versorgt sind haben wir diese mithilfe eines Steckbrettes und vielen Kabeln miteinander Verbunden.

Die Aufgabe des Servo-Motors ist es sich in einem 180 Grad Winkel dauerhaft von links nach rechts und wieder zurück zu bewegen, damit Objekte in einem 180 Grad Radius erfasst werden können. Dazu steht im Code wieweit und wie schnell bzw. mit welcher Verzögerung sich der Servo-Motor bewegen soll. 

Der Entfernungsmesser ist so programmiert, dass dieser auf eine im Vorhinein bestimmte Entfernung anspricht. Dazu wurde das Serial Monitor Tool benutzt um, dies visuell zu zeigen. Wenn sich ein Objekt hinter der festgelegten Grenze befindet, schreibt der Serial Monitor in einem bestimmten Takt eine 0 an. Unterschreitet das Objekt jedoch die Grenze, schriebt der Serial Monitor lauter Zahlen.


public void fillWorld()
[
Start myStart;
myStart = newStart();
addObject(myStart, 700, 620);
]
		
<h4> <a id="Produkt"> &#10123; &nbsp Das Endprodukt </a> </h4>

Unser Endprodukt ist in unserem Ordner, unter Datein > Ordner > kurs.informatik.12bfgcd > Liam_Patric, zu finden.

<h4> <a id="Reflexion"> &#10124; &nbsp Reflexion und Fazit des Projekts </a> </h4>

Aus einer Idee am Anfang des Informatikunterrichts ist ein funktionierendes Spiel geworden, welches fordernd, aber machbar ist und Spaß beim spielen bringt. Von fast garkeinen Programmierkenntnissen, konnten wir unser Wissen erheblich Steigern und auch die Software hinter technischen Geräten besser verstehen. Die vielen Probleme konnten wir dank Herrn Buhl und eigener Recherche beheben, um so ein funktionierendes Spiel auf die Beine zu stellen. Am Ende dieses Projekts sind wir zufrieden mit dem was wir geleistet haben und mitdem was wir gelernt haben, obwohl wir nicht alle, im vorhinein festgelegten Ziele, errecht haben.

<h4> <a id="Ausblick"> &#10124; &nbsp Ausblick auf kommende Veränderungen </a> </h4>

Wenn wir die Möglichkeit bekommen würden an dem Projekt weiter arbeiten zu dürfen, würden wir viele kleine und manche große Änderungen vornehmen, um das Spiel noch einzigartiger und unterhaltsamer zu gestalten. Zu den Änderungen würden Gegenstände, die man einsammeln kann, gehören. Bei dem Sammeln von Gegenständen würde eine Score-Tafel, diese Gegenstände mitzählen. Wir würden außerdem Sound-Effekte hinzufügen, dass zum Beispiel bei Springen, Laufen oder Sterben bestimmte Geräusche zu hören sind. Wir würden warscheinlich auch den Hintergrund des Spiels und andere Grafiken verändern, damit das Spiel harmonischer wirkt. Zuletzt würden wir das Spiel verlängern und den Schwierigeitsgrad erhöhen oder meherere Level erstellen, die unterschielich schwer sind


	
	
