<head>
<h1 align="center">Jump-n-Run-Spiel/Projektseite</h1> 
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
Damit diese Vielzahl von Programmen auch sinnvoll eingesetzt werden konnte, begannen wir immer zuerst mit der Einarbeitung in das jeweilige Programm. Dafür wurden unterschiedliche Quellen und Arten genutzt. Als besonders hilfreich haben sich YouTube-Tutorials für eine grobe Übersicht und Foreneintrage für die Beantwortung konkreter Fragen herausgestellt. Hierbei waren die am meisten verwendeten Quellen:

https://www.youtube.com/watch?v=By8fojS0sIU 

https://www.youtube.com/watch?v=SBcIb4_ST8I 

https://www.youtube.com/watch?v=FoD7cjW_5lU 

https://www.youtube.com/watch?v=RQUYT9svlTg 

https://www.youtube.com/watch?v=z7RB-KSlCFQ 


<hr>

<h4> <a id="Idee"> &#10123; &nbsp Die Idee</a> </h4>

Viele von uns kennen das T-Rex-Spiel, welches erscheint, wenn man keine Internetverbindung, auf Google Chrome, hat. Oder das Konsolen Spiel Super Mario. Diese Spiele waren ein Anreiz, für unser eigenes Spiel. Die Idee war also ein Spiel zu entwickeln, welches typischen Jump and Run Spielen ähnelt, aber unsere eigenen Vostellungen, wiederspiegelt.


<h4> <a id="Entwicklungsprozess"> &#10123; &nbsp Entwicklungsprozess</a> </h4>

Der Entwicklungsprozess startete am 16.8.2022, der ersten Informatikstunde mit einer Brainstormingphase und dem Aufgreifen der Idee eines Spiels. Innerhalb der nächsten Stunden, kristallisierte sich herraus, das wir eine Art Jump and Run Spiel programmieren wollten. Daraufhin folgte ein viermonatiger Entwicklungsprozess, wo wir unsere Plänse und Gedanken, zur Wirlichkeit werden lassen konnten. Anfangs konnten wir guten Fortschritt vermerken, doch nachdem wir die Integrierung des Spielers und dessen Steuerung fertig hatten, mussten wir aufgrund von Problemen fast alles nochmal machen, da wir zu diesem Zeitpunkt einen anderen Weg für unser Spiel eingeschlagen hatten.

<h4> <a id="Software"> &#10123; &nbsp softwaretechnische Umsetzung </a> </h4>
Die Aufgabe der Software ist ein Spiel zu erstellen, in dem der Spieler eine fliege steuert, miut welcher er dann von A nach B kommen muss, in dem einen, von der Software erstellten, Jump and Run Parkour absolviert. Die Software dient der Steuerung der Fliege, sowie des erstellens eines Starts, eines Ziels, der einzelnen Platformen und der Schielder. 
<ul>
	<li>Die Steuerung für die Bewegungen lässt sich in Greenfoot unter Fly finden. Unter public void movement haben wir da eingestellt welche Taste man drücken muss, damit sich die Fliege bewegt. Um das zu machen sagt man der Software durch if(Greenfot.isKeyDown) und dann definirt man welche Taste gedrückt werden muss, in dem man das dahinter in Klammern schreibt. Damit ist für die Software klar, wenn die Taste D gedückt wird muss die Flige auf der x-Achse bewegt werden. Damit die Software aber auch weiß in welche Richtung und wie weit sie die Fliege  bewegen soll, schreibt man darunter noch move(3). Damit ist klar die Fliege soll um 3 nach rechts bewegt werden. Damit man die Fliege aber auch in die andere Richtung auf der x-Achse bewegen kann, haben wir das gleiche nochmal gemacht. Dabei haben wir jedoch D durch A ersetzt und -3 anstelle von 3 geschrieben. -3 haben wir geschrieben damit sich die Fliege zurück bewegt, eben um 3 nach hinten. Damit die Fliege auch springen kann, sagen wir ihr über das gleiche Systhem, dass wenn space gedrückt wird sie springen soll.
Damit wir verschiedene PLatformen haben, haben wir als erstes in Greenfoot eine Platform hinzugefügt und der ein entsprechendes Bild zugeordnet. Die einzelnen Platformen haben wir dann unter ScrollingWorld eingefüg. Dabei mussten wir nur sagen auf welcher x- und y-Koordinate wir die Platformen haben wollen.
Damit der Spieler auch ein Erfolgslebnis haben kann, haben wir die Erdbeere eingefügt, welche, wenn sie berührt wird, dafür sorgt, dass das Spiel vor bei ist. Wird die Erbeer berührt, so erscheint ein Bild auf dem Victory drauf steht. Das schafft man, in dem man sagt, dass wenn die Erbeere berührt wird soll das Bild eingefügt werden. Sagen tut man das mit if (isTouching(Finish.class)) und dann sagt man, wenn dass der Fall ist addObject und dann der Name vom dem Object, in diesem Fall YouWin. Danach sagt man noch das die Fliege entfernt werden soll mit getWorld().removeObject(this);. Zu guter letzt muss man dem Spiel nur noch sagen das es angehalten werden soll. Dies tut man indem man sagt Greenfoot.stop(); Das gleiche Prinzip muss man auch anwenden, wenn man einen Gegner, in unserem Fall der Frosch, einfügen möchte.
Die Schilder haben wir auch unter ScrollingWorld eingefügt. Zu vor haben wir jedoch erst einmal die Bilder in Greenfoot hochgeladen und sie dann unter Actor benannt. Damit man die Schilder jetzt in der Welt sieht, muss man unter public void fillWorld() den Namen eingeben und dann wieder die x- und y-Koordinate bestimmen, sodass das Spiel weiß wo die Schilder zusehen sein sollen. Der Code sieht dann so aus:

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


	
	
