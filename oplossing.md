## a) 
Github Actions wordt gebruikt om automatisatie te implementeren voor deployment-processen en continue integratie. Je kan hierdoor code bouwen en testen bij elke commit die plaatsvindt.
Het is ook mogelijk om wijzigingen automatisch toe te passen naar staging alsook naar de productieomgeving. Door gebruik te maken van deze tool kunnen developers dankzij de geautomatiseerde workflow hun meer concentreren op het schrijven van hun code, terwijl de routine taken worden uitgevoerd.

Docker zorgt ervoor dat het makkelijker wordt om applicaties op verschillende plekken te laten draaien. Dit wordt gedaan door de applicaties in containers te steken. Deze container bestaat uit de benodigde software om de applicatie te kunnen runnen.
Docker zorgt er ook voor dat elke applicatie geïsoleerd is van elkaar, zodat ze niet met elkaar in de war komen. Ook kun je met Docker makkelijk bepalen hoe groot of klein je app moet zijn, afhankelijk van wat je precies nodig hebt.

## b)
YAML is een taal waarmee mensen gemakkelijk leesbare gegevens kunnen opslaan en structureren. Het wordt vaak gebruikt voor het maken van configuratiebestanden, waarin instellingen en parameters op een begrijpelijke manier kunnen worden vastgelegd. De syntax/structuur van YAML files is heel simpel, zo kan je een lijst maken met vierkante haakjes [] en kan je waardes geven aan je "sleutels" door gemakkelijk een ':' te gebruiken. Je hoeft geen gebruik te maken van " of ;. Bijvoorbeeld: 

```
Groepsnaam: Team21
Leden:
- Cédric
- Dietmar
- Wout
- stef
```

## c)

DockerHub is een open source containerregister gemaakt om container images te vinden, te gebruiken en te delen. Met DockerHub kunnen ontwikkelaars openbare repositories hosten die gratis kunnen worden gebruikt of prive repositories voor teams en bedrijven.

Link naar mijn DockerHub repository: https://hub.docker.com/r/dietmardamiaens/opsdev-calculator

## d)
We gebruiken secrets zodat mensen die in de repository kunnen kijken niet zomaar kunnen inloggen op onze dockerhub en zodat ze niet onze webhook kunnen gebruiken in andere repositories. We kunnen het ook doen zonder secrets maar dan moeten we onze gebruikersnaam en acces token van dockerhub uittypen in de yml file. We kunnen tenslote ook nog gebruik maken van een repository variable maar iedereen die in de repository kan kan deze zien dus dit is ook niet veilig voor inlog gegevens of gegevens die we geheim willen houden.

## e)
Azure is een cloudcomputingplatform van Microsoft. Hierop kan je via internetverbinding verschillende tools deployen, zoals onder andere servers, VM's, databases,.... De grootste concurrenten van Azure zijn AWS (Amazon Web Services) en Google. IaaS kan je vergelijken met het huren van computerservers, PaaS is als het huren van een platform om apps te maken, en SaaS is als het gebruiken van kant-en-klare software online. Het idee is dat je alleen betaalt voor wat je gebruikt, zonder zelf fysieke computers te hoeven bezitten.

## f)
Publieke URL van de applicatie:

2tin-team21.azurewebsites.net

Screenshot van App Service:

![image](https://github.com/PXL-2TIN-DevOps-2324/opdracht-8-integratieopdracht-team-21/assets/57450200/d59eef27-0a1c-4602-86c2-6c3f60417cb0)


![image](https://github.com/PXL-2TIN-DevOps-2324/opdracht-8-integratieopdracht-team-21/assets/57450200/6047b425-7890-4c29-987a-82458000d087)
