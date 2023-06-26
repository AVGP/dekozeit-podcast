+++
Description = "Was ist das Ziel von Sättigungsmodellen? Das Ziel eines Sättigungsmodells ist es, die Menge der Inertgassättigung und -übersättigung im Gewebe zu berechnen und somit die Menge des im Gewebe vorhandenen Gases in einem sicheren Ausmaß zu halten. Hierdurch soll die Entstehung von Gasblasen im Körper verhindert werden. Diese Modelle werden bis heute als Neo-Haldanish bezeichnet. Zu den gängigsten Modellen gehört der Bühlmann-Algorithmus. Wie funktionieren die Modelle und wo liegen die Grenzen?"
Date = 2023-06-19T09:00:00+02:00
podcast_file = "14-saettigungsmodelle.mp3" # the name of the podcast file, after the media prefix.
podcast_duration = "30:20"
#podcast_bytes = "" # the length of the episode in bytes
episode_image = "img/episode/14/cover.jpg"
#episode_banner = ""
#guests = [] # The names of your guests, based on the filename without extension.
#sponsors = []
episode = "14"
title = "Sättigungsmodelle"
#subtitle = ""
images = ["img/episode/14/cover.jpg"]
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

## Was ist das Ziel von Sättigungsmodellen?

Das Ziel eines Sättigungsmodells ist es, die Menge der Inertgassättigung und -übersättigung im Gewebe zu berechnen und somit die Menge des im Gewebe vorhandenen Gases in einem sicheren Ausmaß zu halten. Hierdurch soll die Entstehung von Gasblasen im Körper verhindert werden. 
Diese Modelle werden bis heute als “Neo-Haldanish" bezeichnet.
Zu den gängigsten Modellen gehört der Bühlmann-Algorithmus.

## Was war an Haldanes Arbeiten neu und was hat Workman geändert?

Haldane erkannte, dass es sich bei der Gasumverteilung um einen exponentiellen Prozess handelt, welcher mit sogenannten Halbwertszeiten beschrieben werden kann.
Er erkannte außerdem, dass dieser Prozess im Körper unterschiedlich schnell abläuft und führte 5 virtuelle Gewebskompartimente ein, um diesen Prozess zu beschreiben. Diese hatten unterschiedliche Halbwertszeiten von 5, 10, 20, 40 und 75 Minuten. Nach 6 Halbwertszeiten kann man von einem vollständigen Ausgleich ausgehen.
Tauchtiefe und Tauchzeit beeinflussen die Nullzeit, bevor ein Auftauchen aus der Tiefe nicht mehr problemlos möglich ist.
Haldane ging davon aus, dass eine Übersättigungsfaktor von 2:1 ohne Probleme möglich sei. Aus diesen Überlegung entstanden die ersten klassischen Tauchtabellen. Anmerkung: Die heute verbreiteten Tauchtabellen sind deutlich konservativer und die ursprünglichen Haldane-Tabellen werden effektiv nicht mehr genutzt.

Der Übersättigungsfaktor wurde später durch Robert Workman auf 1,58 gesenkt, um mehr Sicherheitsmarge zu integrieren. Workman erstellte außerdem als erster eine lineare Gleichungsform, mit der das Berechnen von individuellen Tauchtabellen deutlich vereinfacht wurde.
Die Workman-Gleichungen stellen somit die Basis für die aktuellen Sättigungsmodelle dar.

## Welche Neuerungen sind durch Bühlmann entstanden? 

Albert Bühlmann verwendete in seinen Arbeiten zunächst 8 Gewebskompartimente für seine Berechnungen und später sogar 16 Kompartimente. Auf dieser Basis entwickelte er den Algorithmus ZHL-16 (ZHL = Zürich Limits). Es gibt verschiedene Varianten des Algorithmus: Während zunächst die Variante ZHL-16A verwendet wurde, wird bei der Variante ZHL-8ADT auch Temperatur und Atemgasvolumen einberechnet. Die Variante ZHL-16B wurde speziell für das Erstellen von Tauchtabellen erstellt und die Variante ZHL-16C ist besonders gut für die Verwendung auf Tauchcomputern geeignet. 
Es gibt noch weitere spezielle Varianten des Bühlman-Algorithmus, welche zum Beispiel die Arbeit des Tauchers auf Tiefe besser berücksichtigen.
Eine gute Übersicht liefert Wikipedia:
https://en.wikipedia.org/wiki/Bühlmann_decompression_algorithm

Zusammen mit Hannes Keller adaptierte Bühlmann in Experimenten seine Algorithmen auch für die Anwendung bei Mischgasen mit Helium.
Dabei stellte er fest, dass Helium schneller in den Körper wandert als Stickstoff und auch schneller wieder absättigt.
Bühlmann validierte seine Modelle auch mit zivilen Tauchern, die sich als Freiwillige bei ihm meldeten.

## Schnelle und langsame Gewebe, das “führende" Gewebe…

Die Überlegungen zu den verschiedenen Gewebegeschwindigkeiten führen zu einem interessanten Phänomen: Die verschiedenen Gewebskompartimente verhalten sich, bedingt durch ihre Geschwindigkeit, während dem Tauchgang recht unterschiedlich.
Bei der isolierten Betrachtung eines schnellen Gewebes sättigt dieses zunächst auf und sättigt später während des Aufstiegs ab.
Bei der gleichzeitigen Betrachtung eines langsamen Gewebes hat dieses zum Zeitpunkt des Aufstiegs seine erste Halbwertszeit noch nicht vollständig durchlaufen und sättigt während der ersten Stopps sogar noch weiter auf.

Während einer Dekompression muss sich der Taucher also immer an unterschiedlichen Geweben orientieren. Die schnellen Gewebe sättigen recht schnell ab. Je höher ich in den Dekompressionsstopps komme, desto mehr werden die langsameren Gewebe zum Problem. Dabei wird immer das Gewebe, welches als nächstes den M-Wert überschreiten würde, als “führendes Gewebe" bezeichnet, da es den Fortschritt der Dekompression “führt".
Mit der Zeit werden immer mehr die langsamen Gewebskompartimente zum führenden Gewebe…

Auf vielen Tauchcomputern kann man sich die Aufsättigung der verschiedenen Kompartimente auch anzeigen lassen und im Bezug auf den aktuellen Druck darstellen lassen. Das ist zum einen mit Bezug auf den jetzigen Tauchgang interessant. Aber auch im Verlauf von verschiedenen Tauchgängen in Folge kann man eine markante Aufsättigung der langsameren Gewebe beobachten.
https://youtu.be/O81vX79X_mA

## Was sind die Limitationen eines Sättigungsmodells?

Das liegt zunächst einmal in der Sache selbst: Ein Modell ist dazu gedacht, die Wirklichkeit vereinfacht darzustellen, damit sie einfacher zu begreifen ist. Das führt aber auch zwangsweise zu Ungenauigkeiten und nicht abgebildeten Sachverhalten…
Kein Sättigungsmodell kann die vollständige Vielfalt der vorhandenen Gewebe im Körper abbilden oder auch deren aktuellen Zustand.

Die Statistik zeigt ganz klar: Es gibt viele Taucher, die sich an die Grenzen eines Tauchcomputer halten und trotzdem ein Dekompressionssyndrom entwickeln. 
Mit Ultraschalluntersuchungen lässt sich mittlerweile nachweisen, dass viele Taucher auch innerhalb der Grenzen eines Sättigungsmodells eine gewisse (und stark variable) Menge an Blasen im venösen Blut haben. 

Nun reicht es natürlich, wenn nur eine einzelne dieser vorhandenen Blasen an einen unguten Ort eingespült wird und bspw. im Gehirn einen Schaden verursacht.
Dieses Risiko kann bspw. durch eine PFO persistierendes Foramen Ovale markant erhöht werden. (Wobei auch hier eine Vielzahl von anderen Faktoren zu beachten ist.) In diesem Fall trifft das Modell zum Beispiel nur sehr eingeschränkt zu.

Auch die M-Werte selbst sind nur verhältnismäßig wenig kontrolliert und stellen eher einen schwammigen Graubereich dar, als eine strikte Grenze, an der man sich orientieren kann. Statistik ist ein Arschloch: Zwar senkt die Einhaltung der M-Werte im Modell die Anzahl der Taucher mit DCS auf ein geringes Prozent. Wenn du aber einer dieser betroffenen Taucher bist, dann bist du ja trotzdem zu 100% betroffen ;-) 

## Wie kann man zusätzlichen Sicherheitsabstand zum M-Wert schaffen?

Zum Beispiel über eine reduzierte Aufstiegsgeschwindigkeit. Oder auch ganz einfach darüber, dass ich nicht an der Grenze zur Nullzeit “kratze"...
Ich kann auch einen Sicherheitsstopp ausdehnen und mich so etwas weiter von der statistischen Grenze entfernen. 
Und ich kann das ganze auch mathematisch korrekter machen über die sogenannten “Gradient Faktoren". Um die geht es allerdings in der nächsten Folge ;-) 

## Unsere Literaturliste zum Thema Dekompression: (für alle Folgen gleich)

- "Deco for divers"; Mark Powell; aquapress-Verlag; 2019; ISBN 978-1-905492-29-2
- Wetnotes spezial "Tauchmedizin; Hartig et al.; www.wetnotes.de
- "TDI decompression procedures - student manual"; tdisdi.com (Tip: lieber auf Englisch lesen…)
- "Decompression controversies"; DAN Southern Africa; https://youtu.be/UY61E49lyos
- "RF 3.0 - Decompression Methods" https://youtu.be/pH5zw_fi5RE
- "Deep stops update"; DAN Southern Africa; https://youtu.be/DjOx1kcIrTc
- "Thoughtful management of decompression stress"; Dr. Neal Pollock; https://youtu.be/HU04JhXggPg
- "Is decompression sickness an inflammatory disease?"; DAN Southern Africa; https://www.youtube.com/live/jR0Fu20zlYQ?feature=share
- "Understanding Gradient Factors"; Przemyslaw Kacprzak; https://youtu.be/-3EXqWcUL_Y
- "Clearing up the confusion about deep stops"; Erik C. Baker; https://www.shearwater.com/wp-content/uploads/2012/08/Deep-Stops.pdf
