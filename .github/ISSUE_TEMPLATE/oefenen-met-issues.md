---
name: Oefenen met issues
about: Volg de instructies van dit issue stap voor stap en vink ze af.
title: ''
labels: ''
assignees: ''

---

Dit issue is gemaakt door [[NAAM]]

Zodra je een stap uitgevoerd hebt, kun je het vinkje naast de onderstaande stap zetten.

### Waarvoor gebruik je issues?
Issues zijn de basis van iedere verandering die je aan je project doet. Ze helpen je daarnaast om een project goed te kunnen plannen. Issues kunnen bugs zijn, ongewenste fouten die in je spel zijn geslopen, maar ook nieuwe opties die je aan je spel wilt toevoegen. Voor de PO wordt het correct gebruik van issues meegenomen in het cijfer.

### Stappenplan
- [ ] Geef deze issues hierboven bij 'Title' de titel "[[je naam]] oefent met GitHub".
- [ ] Issues schrijf je normaal gesproken grotendeels zelf. We gaan even oefenen met het schrijven van tekst in een issue: vervang in hierboven [[NAAM]] met je voornaam.

Er ontstaan in de loop van de tijd waarschijnlijk een groot aantal issues. Om door de bomen het bos te blijven zien, maken we gebruik van labels. Issues kunnen meerdere labels hebben.
- [ ] Geef aan dit issue hiernaast bij 'Labels'  het label 'feature'.

Een medeleerling of docent kan onder een issue commentaar toevoegen. Zo kan er een 'discussie' ontstaan waardoor duidelijker wordt wat er precies moet gebeuren.
- [ ] Voeg onder dit issue een nieuw commentaar toe en 'start' daarmee een discussie.

Je GitHub-repository heeft ook [planborden](https://github.com/informatica-emmauscollege/playground/projects/1) om bij te houden welke issues / taken nog gedaan moeten worden, welke op dit moment door iemand zijn opgepakt en  welke zijn afgerond. Een nieuw issue komt automatisch onder To Do te staan.
- [ ] Ga naar het planboard en zoek bij To Do naar het kaartje van dit issue. Wijs onder 'assignees' jezelf toe als persoon die dit issue gaat aanpakken.
- [ ] Verplaats het kaartje van dit issue op het To-Do-bord naar het In-Progress-bord.

Nu we weten wie dit issue gaat oppakken en het In Progress hebben gezet, wordt het tijd om de code aan te passen zodat we het issue 'oplossen'. Laten we er vanuit gaan dat dit issue opgelost is als je je naam in het scherm van de game hebt gezet.

Omdat je met meerdere mensen tegelijkertijd aan de code wilt kunnen werken, maak je in GitHub een eigen branch aan. Dit geeft je de mogelijkheid om zonder door anderen gestoord te worden onze eigen wijzigingen aan te brengen. Als je de uiteindelijke oplossing voor dit issue hebben geprogrammeerd, kun je je branch gaan samenvoegen (dit heet mergen) met het grote geheel.  
- [ ] Ga naar de [code](https://github.com/informatica-emmauscollege/playground) van het repository en maak daar een nieuwe branch aan. Geef de branch dezelfde naam als de titel van het bijbehorende issue (nu dus "[[je naam]] oefent met GitHub").

We hebben een eigen branch aangemaakt en gaan nu naar een programmeeromgeving om de code van de game aan te passen. Wij gebruiken hiervoor [GitPod.io](http://gitpod.io) .
- [ ] Log in op GitPod.
- [ ] De **eerste keer** dat je een repository van GitHub wilt bewerken in GitPod, gebruik je een speciale link: http://gitpod.io/# en daarachter gelijk de URL van het GitHub repository. Nu dus [http://gitpod.io/#https://github.com/informatica-emmauscollege/playground](http://gitpod.io/#https://github.com/informatica-emmauscollege/playground). Het repository zit nu in GitPod. De volgende keer is inloggen genoeg.
- [ ] Zorg dat je in de workspace zit van dit playground repository.
- [ ] Klik links onderin op 'master' en kies vervolgens de branch die je zojuist op github hebt aangemaakt.
- [ ] Ga naar de file 'script.js' en voeg ook jouw naam toe op de plek waar de achtergrond getekend wordt.
- [ ] Kies in GitPod File -> Save All.
- [ ] Controleer met preview of het commando python3 http.server -m 3000 of je wijziging goed is. Zo niet, blijf programmeren, opslaan en controleren.
- [ ] Kies in de linkerkolom de optie *Source control: Git* en commit het gewijzigde bestand. Geef de commit een duidelijke beschrijving.

Je hebt nu in jouw branch in de omgeving van GitPod een wijziging aangebracht. Je gaat nu jouw branch op GitHub 'updaten'. Dit heet *pushen*.
- [ ] Links onderin, naast de naam van je branch, zie je een refresh knop. Druk hierop. Jouw commits worden nu naar je branch in GitHub gepusht.
- [ ] Kies nu de branch master en refresh deze indien nodig (dan staan er pijltjes met getallen bij).
- [ ] Ga opnieuw in de linkerkolom naar de optie *Source control: Git*, klik op de ... knop en kies 'Merge'. Kies vervolgens jouw eigen branch om die in te voegen in de master.
- [ ] Los evt. conflicten op.
- [ ] Push de nieuwe commit(s) van de master naar GitHub.

### Bijna klaar
Je hebt je issue verwerkt, gefeliciteerd! Nu nog even de administratie bijwerken:
- [ ] Zet rechts naast dit issue onder projects de status op 'Done'.
- [ ] Kies onderaan deze pagina "Close issue".

Geniet van je game en ga verder met het volgende issue 😄
