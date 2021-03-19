# Indeed
**Indeed, Inc** ist die weltweit größte Jobsuchmaschine. Sie durchforstet Stellenangebote auf tausenden Websites, wobei neben Jobbörsen auch die Karrierewebsites von Unternehmen sowie Ausschreibungen von Personalvermittlern eingelesen werden. Das Angebot umfasst weltweit über 16 Millionen Jobs. Pro Monat verzeichnet Indeed rund 180 Mio. Besucher und ist somit die meistgenutzte Jobseite weltweit.
> Wikipedia

## Kurze Einführung

### Konzept
Das Projekt basiert sich auf dem Job-Suchdienst **Indeed**. Es sollte den Menschen helfen Arbeit zu finden. Das Konzept konzetriert sich auf Menschen, die die Möglichkeit haben sollten, sich besten geeigneten Job zu finden. Um dies zu gewährleisten, ziehen wir auf die Website und bemühen uns, ihre Probleme zu lösen, Mitarbeiter so schnell, bequem und effizient wie möglich zu finden.

### Die Idee

#### Die Möglichkeit sich Online und Bequem zu bewerben
Dies ist ein fortlaufender Prozess für uns. Einmal zu tun und anzuhalten, geht nicht um uns. Wir entwickeln das Projekt ständig weiter und gehen sogar darüber hinaus, um einen facettenreichen Service zu schaffen, der sich auf die Bedürfnisse der Menschen konzentriert.

#### Der beste Service 
Wir möchten, dass unser Service nicht einer von vielen ist, sondern der beste. Wir wollen uns ständig verbessern. Schließlich können Sie es immer noch besser, bequemer und effizienter machen. Jedes Mal, wenn etwas getan wird, versuchen wir uns zu fragen: "Ist dies das beste Ergebnis oder ist es möglich, etwas anderes zu verbessern?"
Jetzt entwickeln wir hauptsächlich die Site, aber in Zukunft können es Anwendungen, Bots und andere Dienste sein. Wir sehen Service auch zur Unterstützung von Benutzern und Kunden durch die Abteilungen Moderation und Vertrieb, durch Schulung und Entwicklung.

#### Menschen helfen, glücklicher zu sein

Freudige Arbeit ist ein wichtiger Teil des Glücks. Die Fähigkeit, einen interessanten Job zu machen, sich gefragt zu fühlen, sich zu entwickeln - macht einen Menschen glücklich. Arbeitsgeld ist natürlich auch im Leben eines Menschen wichtig. Jedes Mal, wenn wir jemandem helfen, einen Job zu finden, helfen wir ihm, glücklicher zu sein.

> Wir bieten den besten Service für die Stellensuche, Menschen dabei zu helfen, glücklicher zu sein

## Setup

### Docker
Der Begriff „Docker" kann sich auf verschiedene Dinge beziehen. Das können sein: ein Open Source Community-Projekt; Tools des Open Source-Projekts; Docker Inc., das Unternehmen, das dieses Projekt hauptsächlich unterstützt; und die Tools, die von Docker offiziell unterstützt werden. Die Tatsache, dass die Technologien und die Firma den gleichen Namen haben, kann verwirrend sein.

Hier ist eine kurze Erklärung:

1. Die IT-Software „Docker“ ist eine Containerisierungstechnologie, die die Erstellung und den Betrieb von Linux-Containern ermöglicht.
2. Die Open Source Docker-Community arbeitet an der Verbesserung dieser Technologien zum Nutzen aller Anwender – und das umsonst.
3. Das Unternehmen Docker Inc. verbessert die Arbeiten der Docker-Community, macht diese sicherer und teilt diese Verbesserungen mit der gesamten Community. Sie unterstützt dann die verbesserten und zuverlässigeren Technologien für Unternehmenskunden.

#### Installation

##### Docker

![Docker](https://www.docker.com/sites/default/files/d8/2019-07/horizontal-logo-monochromatic-white.png)

Vorausgesetzt ist, dass ihr System über folgende Eigenschaften Verfügt:
1. Community Version 18 oder höher
2. Betriebssystem: MacOS, Linux, Windows 10 Professional oder Enterprise Edition
3. Ram-Speicher: min. 8 GB; empfohlen: 16 GB
4. Festplatten Speicher: min. 10 GB
5. CPU-Kerne: Minimum: 2; empfohlen 4+

Ich nutze es auf einem Macbook-Air (Model-2019). 
Meine Einstellugen: 
1. MacOS Mojave
2. Prozessor: 1,6 GHz Intel Core i5
3. Speicher: 8 GB 2133 MHz LPDDR3

Installieren und Ausführen von Docker Desktop auf dem Mac
1. Doppelklick auf "Docker.dmg" und in Application Ordner verschieben
![erster Schritt](https://docs.docker.com/docker-for-mac/images/docker-app-drag.png)
2. Docker.app mit Doppelklick ausführen
![zweiter Schritt](https://docs.docker.com/docker-for-mac/images/docker-app-in-apps.png)
3. Das Docker-Menü in der oberen Statusleiste zeigt an, dass Docker Desktop ausgeführt wird und über ein Terminal zugänglich ist.
![dritter Schritt](https://docs.docker.com/docker-for-mac/images/whale-in-menu-bar.png)

Wenn Sie die App gerade installiert haben, startet Docker Desktop das Onboarding-Tutorial. Das Tutorial enthält eine einfache Übung zum Erstellen eines Beispiel-Docker-Images, zum Ausführen als Container, zum Pushen und Speichern des Images in Docker Hub.

Docker Symbol ist zwar im oberen Tab zusehen, jedoch müssen noch schauen, ob es richtig ausgeführt wird. Aus diesem Grund starten wir Terminal und geben im Terminal ``docker --version`` ein und sehen, dass es funktioniert hat! 
![Docker version](/bogdankotikov/Documents/terminal.png "Docker Version")

Ums zu sehen, dass es wirklich funktioniert, müssen wir im Terminal folgeden Befehl ausführen `docker ps`

![Docker is Running](/Users/bogdankotikov/Documents/example.png "Docker funktioniert")

###### Docker Image

Ein Docker Image ist eine Datei, die aus mehreren Schichten besteht und zur Ausführung von Code in einem Docker-Container verwendet wird. Ein Image wird im Wesentlichen aus den Anweisungen für eine vollständige und ausführbare Version einer Anwendung erstellt, die sich auf den Kernel des Host-Betriebssystems stützt. Wenn der Docker-Benutzer ein Image ausführt, kann es zu einer oder mehreren Instanzen dieses Containers werden.

![Docker Image](https://cs-geonode.readthedocs.io/en/2.8_a/_images/docker.png)


