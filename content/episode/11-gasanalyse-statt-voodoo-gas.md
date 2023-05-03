+++
Description = "Die meisten von uns haben im Nitrox-Kurs gelernt, dass wir unser Nitrox analysieren müssen. Im Regelfall nimmt man dazu einfach einen "Oxyspy" und misst nach. Aber wie relevant sind die Messergebnisse wirklich? Und wie kommen Ungenauigkeiten zu Stande? Martin und Jan gehen dieser und einigen anderen Fragen in der aktuellen Folge Dekozeit nach…"
Date = 2023-04-02T09:00:00+02:00
podcast_file = "11-gasanalyse-statt-voodoo-gas.mp3" # the name of the podcast file, after the media prefix.
podcast_duration = "35:27"
#podcast_bytes = "" # the length of the episode in bytes
episode_image = "img/episode/11/cover.jpg"
#episode_banner = ""
#guests = [] # The names of your guests, based on the filename without extension.
#sponsors = []
episode = "11"
title = "Gasanalyse statt Voodoo-Gas"
#subtitle = ""
images = ["img/episode/11/cover.jpg"]
#hosts = [] # The names of your hosts, based on the filename without extension.
#aliases = ["/4"]
#youtube = ""
explicit = "no" # values are "yes" or "no"
#media_override # if you want to use a specific URL for the audio file
#truncate = ""
#upcoming = true # set to true if you want this to be listed as upcoming, etc, etc
#categories = []
#series = []
#tags = []
+++

<style>
img {
max-width: 80%;
max-height: 400px;
}
</style>

**_Disclaimer: Die in diesem Podcast getätigten Aussagen spiegeln lediglich die Meinungen der Produzenten wieder. Obwohl wir die Aussagen im Podcast reflektiert und nach Möglichkeit auf der Basis wissenschaftlicher und technischer Standards treffen, bleibt die verantwortungsbewusste Nutzung dieser Informationen dem Hörer überlassen! Taucht nicht über eure eigenen Grenzen und der eurer Buddies! Haltet euch an eure Zertifizierung und besucht praktische Trainings und Kurse, um eure taucherischen Fähigkeiten zu verbessern._**

## Weshalb sollten wir uns über das Thema Gasanalyse überhaupt unterhalten?

Nicht jeder von uns hat das Glück eines eigenen Trimix-Analysers. Die Geräte sind nicht ganz günstig und Sauerstoffsensoren laufen ja auch gelegentlich ab. Da ist schon die Verlockung groß, nur im Diveshop des Vertrauen zu messen und ansonsten einfach zu rechnen. Es gibt allerdings auch Risiken…

Am Ende gilt: Jeder ist für sein Gas selbst verantwortlich und auch für dessen Nutzung…

## Warum analysieren wir eigentlich Gase?

Aus der Zusammensetzung eines Gases resultieren je nach Zusammensetzung verschiedene Gefahren. 
Eine der relevantesten Gefahren ist die zentrale Sauerstofftoxizität, bei der es zu Krampfanfällen mit Bewusstseinsverlust kommen kann. Das ist natürlich unter Wasser eher ungünstig. Daher will ich meinen Partialdrucks des Sauerstoff (PO2) nachrechnen können und in der Regel im Sporttauchen den Wert von 1.4 bar nicht überschreiten. Dafür muss ich wissen, wie viel Sauerstoff in meinem Atemgas enthalten ist.
Reminder: Der Partialdruck ist der anteilige Druck eines Teilgases. D.h. 21% Sauerstoff bei 1 bar an der Oberfläche = 0,21 bar. Luft auf 10 Meter Tiefe mit 2 bar Umgebungsdruck = 0,42 bar...

Ein erhöhter Sauerstoffanteil sorgt aber auch für einen niedrigen Stickstoffanteil im Atemgas. Wo weniger Stickstoff ist, kann auch weniger Stickstoff in den Körper aufgenommen werden. Die Nullzeit steigt also entsprechend an. Nur wenn ich den Anteil des Stickstoffs im Atemgas kenne, kann ich meine Nullzeit korrekt berechnen...

Wenn Helium in der Gasmischung vorhanden ist, dann ist noch ein weiterer Faktor zu beachten: Das Helium wird schneller in den Körper aufgenommen und man baut schneller verpflichtende Deko-Stopps auf. Auch hier kann ich die korrekte Nullzeit / Dekozeit nur auf der Basis der Atemgasmischung berechnen.

Der Stickstoffanteil der Gasmischung (und evtl. auch der Sauerstoffanteil - je nachdem, welcher Studie man glauben mag) ist außerdem für die narkotische Wirkung der Gasmischung verantwortlich. Je mehr Stickstoffpartialdruck ich auf Tiefe atme, desto "dümmer" bin ich während dem Tauchgang.

Einen guten Artikel dazu findet man übrigens im Magazin "Wetnotes Tauchmedizin" vom Autor Dr. Frank Hartig ;-) 

## Womit kann man analysieren?

Es gibt simple / günstige oder komplexe Varianten der Analyse:
Die simplen Geräte analysieren im Wesentlichen nur den Sauerstoffanteil, die komplexeren Geräte können auch Helium messen und kompensieren manchmal auch noch den Umgebungsdruck, was die Analyse präziser macht. Nachteil ist der Preis…
Verunreinigungen mit Kohlenstoffmonoxid werden von den Analysegeräten nicht erfasst und können mit separaten Analysegeräten ermittelt werden. Auch das kann durchaus Sinn machen, wie im Artikel bei "InDepth" erläutert wird: https://gue.com/blog/gas-analysis-protecting-yourself-from-carbon-monoxide-poisoning/
Die Geräte hierzu sind sogar erschwinglich.
Anmerkung: Ich selber kontrolliere die Luft und das Nitrox aus meinen regelmäßigen Füllanlagen nach dem Zufallsprinzip auf Kohlenstoffmonoxid. Sehr viel regelmäßiger kontrolliere ich dann im Urlaub, wo mit Benzinkompressoren gearbeitet wird und die Kompressoren lange laufen…

## Wie genau funktioniert jetzt die Analyse der Gase?

Der Sauerstoffsensor funktioniert elektrochemisch. Im Sensor reagieren verschiedene Chemikalien mit Sauerstoff aus der Umgebungsluft. Als Ergebnis liegt an den Kontakten des Sensors eine Spannung an, die man messen kann. Verschiedene elektronische Komponenten innerhalb des Sensors sorgen dafür, dass die Temperatur kompensiert wird und keinen messbaren Einfluss auf das Ergebnis hat. Wer sich weiter informieren will, der wird im Papier von Revo Rebreathers fündig: https://www.revo-rebreathers.com/wp-content/uploads/2016/02/Understanding_oxygen_sensors.pdf
Das heißt für die Praxis: Der Sensor misst also nicht die prozentuale Konzentration des Sauerstoffs, sondern die Anzahl von Sauerstoffmolekülen am Sensor. Das ist naturgemäß nicht nur von Gasgemisch, sondern auch vom Druck abhängig.
Der Umgebungsdruck muss also bei der Messung kompensiert werden. Bei manchen günstigen Geräten erfolgt das nicht automatisch.
Hier ergibt sich ein häufiger Anwendungsfehler: Wenn man beim Messen auf das Röhrchen eine Finger legt, dann erhöht sich der Druck. Es wird also ein höherer Sauerstoffanteil angezeigt, als in der Mischung vorhanden ist. Das sieht nur auf dem Papier gut aus… ;-) 
Außerdem ist auch auch ein hoher Wasseranteil in der Luft bei hoher Luftfeuchtigkeit relevant, der den Sauerstoff verdrängt. Wie hoch ist der Unterschied jetzt aber, der sich hieraus ergibt?
Im Experiment haben wir feststellen können, dass die Messunterschiede zwischen kalter, trockener Luft und warmer Luft bei 1-2% Messdifferenz liegen. Noch krasser kann man es mit warmer, feuchter Luft treiben: Hier kann man bis zu 4% Differenz messen. 

Helium wird in den meisten Fällen nicht elektrochemisch gemessen, weil die Sensoren teuer sind. Häufiger wird hier eine Messung über die Schallgeschwindigkeit im Gasgemisch vorgenommen (die Geräte "klickern" dann). Durch die Veränderung des Tons und den gemessenen Sauerstoffanteil kann man den Heliumanteil berechnen. Eine Alternative Messmethode ist die Berechnung aus der Temperaturleitfähigkeit des Gases.

Solid-State Sensoren für die O2-Messung verbrauchen sich im Gegensatz zu elektrochemischen Sensoren nicht, sind allerdings in der Herstellung extrem teuer. Daher sind diese noch sehr selten zu finden.

## Die Sache mit der Kalibrierung

Während bei einem "idealen Sauerstoffsensor" die ausgegebene Spannung linear zwischen 0% Sauerstoff und 100% Sauerstoff steigt, sieht dieser Wert in der Realität oft anders aus und bildet eine leichte Kurve. Außerdem verändern die Sensoren im Laufe der Zeit ihre Eigenschaften. Man muss also immer wieder Refferenzpunkte auf der Spannungskurve festlegen, damit die ausgegebenen Werte korrekt sind. 

An simplen Geräten gibt es den "Kalibrier-Button". Mit diesem ordnet man dem aktuell gemessenen Spannungswert die 21%-Marke zu, an der sich das Gerät orientiert. Dazu sollte man ein Kalibriergas mit ähnlicher Feuchtigkeit und Temperatur wählen, wie das zu messende Gas. 

An komplexen Geräten ist die Kalibrierung in die 1 bis 3-Punkt Kalibrierung unterteilt.
Bei der 1-Punkt Kalibrierung wird wie oben genannt der 21%-Wert der Spannungskurve festgelegt. Das Kalibrierungsgas ist simple Atemluft aus der Gasflasche.
Bei der 2-Punkt Kalibrierung wird neben dem 21%-Wert auch ein Referenzpunkt für 100% Sauerstoff vergeben. Das ist dann relevant, wenn man hohe Sauerstoffkonzentrationen messen will. Das zweite Kalibriergas ist Reinsauerstoff. Tipp: Man kann mit einem Adapter auch den Notfallsauerstoff verwenden, wenn man keinen anderweitigen Reinsauerstoff zur Verfügung hat. Der Verbrauch ist bei der Kalibrierung im Normalfall gering. 
Bei der 3-Punkt Kalibrierung wird zusätzlich ein Wert für 0% Sauerstoff festgelegt. Das ist dann relevant, wenn man hypoxische Gase messen will. Das dritte Gas ist im Regelfall Helium.
Bei allen Kalibiergasen muss ich mir über deren Zusammensetzung im Klaren sein: Eine falsche Kalibrierung verfälscht alle zukünftigen Messungen.
Eine Kalibrierung muss man regelmässig in sinnvollen Abständen wiederholt werden. Sensoren verändern sich im Laufe der Zeit.
Welche Fehlerquellen gibt es?
Über den häufigsten Bedienerfehler "Finger am Auslass" haben wir schon gesprochen. Auch sollte ich mein Gerät kennen und wissen, ob der Luftdruck kompensiert wird oder nicht.
Ich kann Messwerte verfälschen, indem ich ein falsches oder ungenaues Kalibriergas verwende. Die Kalibrierung kann ich über ein separates, bekanntes Messgas kontrollieren, bspw. indem ich die selten genutzte, bekannte Gasmischung noch einmal nachmesse.
Ein konstanter Gasfluss über den Sensor ist wichtig. Am besten kann hierfür ein Flowminderer des Herstellers verwendet werden.
Sensoren können technisch defekt sein oder auch zu alt werden. Dann sind die chemischen Bestandteile verbraucht und ein neuer Sensor ist fällig. Die Effekte merkt man in der Regel zuerst bei den hohen Sauerstoff Werten und bei häufiger Benutzung. Man spricht vom sogenannten "Current Limiting". 

## Wann ist eine Gasanalyse denn jetzt wirklich relevant?

Wie immer gilt: Hirn einschalten - mitdenken!
Eine Gasanalyse ist immer dann relevant, wenn ich (potentiell) Mischgas verwende. Wenn ich also meine Flaschen nur selber nutze, nie ausleihe und an meiner Füllanlage nur Luft verfügbar ist und auch keine Verwechslungsgefahr besteht, kann ich mir das Analysieren sparen. Wenn aber ein Risiko besteht, dass die Füllung nicht stimmt, dann muss analysiert werden.

Außerdem gibt es das Risiko, dass Füllanlagen defekt sind. Auch beim Partialdruckverfahren gibt es neben der Fehlbedienung das Risiko von Restgasen in der Leitung. Dabei ist neben dem Volumen der Leitung in der Anlage auch die Größe der gefüllten Flasche relevant. Bei einem Druck von 200 bar und einem Leitungsvolumen von 200ml ergibt sich für eine…
… 15 Liter Flasche eine Abweichung von 1,3%.
… 3 Liter Flasche eine Abweichung von 7%.
Eine Abweichung von 7% ist dann durchaus relevant in verschiedenen Bereichen. Neben der Atembarkeit des Gases können am CCR Probleme bei der Kalibrierung entstehen.
In der Dekompression entstehen hier allerdings nicht so schnell relevante Unterschiede: Bei einem TG 40 Meter mit einer Bottom-Time von 30 Minuten entstehen in der Dekompression keine markanten Abweichungen. Je länger die Expositionszeiten natürlich werden, desto größer ist der Unterschied.
Für die Praxis: Kleine Flaschen produzieren höhere Ungenauigkeiten beim Füllen. Je länger und tiefer die Tauchgänge sind, desto relevanter sind diese Fehler.

Die viel relevantere Frage ist also: 

## Wie präzise muss die Analyse sein?

Das lässt sich allerdings nicht so einfach beantworten. Hier sind unsere Strategien dazu: 
Im Urlaub, wenn wir OC im Sporttauchbereich unterwegs sind, checken wir den Sauerstoffgehalt bei allen Flaschen (auch Luft) und achten dabei nicht zu extrem auf geringe Abweichungen. Es geht darum, eine Sauerstofftoxizität oder eine versehentliche Dekompressionspflicht bei extremen Abweichungen (Luft vs. EAN 32 vs. EAN 40) zu verhindern. 
Im technischen Bereich achten wir deutlich detaillierter auf die präzise Analyse der Gase und versuchen, unsere Ansprüche auf den Tauchgang abzustimmen.

Jeder ist für sein Gas selbst verantwortlich und sollte selbst messen. Dann gilt es auch nach der Messung, ein Vertauschen der Flaschen zu verhindern. Das kann durch "Fertigmachen" und Anschließen der eigenen Ausrüstung geschehen oder durch eine Beschriftung. Ein markantes Problem ist außerdem die Beschriftung: Diese sollte adäquat sein und eindeutig sein. Es gibt verschiedenen Strategien: In der Tech-Szene ist das Labeling mit Klebeband verbreitet. Ein umweltfreundliche Alternative können im Sporttauchen wiederverwendbare Karten sein. 

**Gase müssen analysiert werden!** Fast immer…