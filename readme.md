### SUCCESVOL GEPUSHT VANAF BranchTest
## Wil je niet constant inloggen?
Voer dan de volgende commando's uit in de terminals:  
git config --global user.name 'email\_of\_gebruikersnaam\_op\_github'  
git config --global user.password 'jouw\_wachtwoord\_op\_github'  
  
# BIJ HET KLONEN VAN EEN REPOSITORY:  
1. Clone de repository van GitHub naar jouw computer:  
> git clone https://github.com/ROCMondriaanTIN/project-greenfoot-game-molotov
  
2. Ga naar jouw branch. Als je geen branch hebt zie dan onderin: **Maak een nieuwe branch**  
> git checkout **NAAM**
  
3. Ga aan de slag.  
4. Op het moment dat je wat werk af hebt moet je nieuwe en aangepaste bestanden toevoegen aan de nieuwe commit.  
> git add.
  
5. Je kan nu committen.  
> git commit -m "Wat heb je veranderd? Wat heb je toegevoegd? Geef dit hier aan!"
  
6. Je kan de branch op server nu updaten.  
> git push
  
# BIJ HET MAKEN VAN EEN NIEUWE REPOSITORY:
1. Maak een nieuwe map aan, doe dit door de terminal te openen in jouw documenten/projecten map, en in de terminal het volgende commando in te voeren:  
**LET OP!! DE NAAM MAG GEEN SPATIES HEBBEN.**  
**mkdir NAAM**  
2. Open de terminal in de nieuwe map die je hebt aangemaakt voor dit project. Dit doe je als volgt: **cd naam_van_map**  
3. Volg daarna [deze guide](https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line)  

# MERGE CONFLICTS
In het geval van conflicts met mergen kan je twee dingen doen:  
1) Het bestand editen, zie [deze pagina](https://www.git-tower.com/learn/git/ebook/en/command-line/advanced-topics/merge-conflicts)  
2) Het commando:  
git checkout --**(ours/theirs) path/to/conflict-file.css**  
uitvoeren. Als je "ours" invoert, houd je je eigen bestand op de branch waar je nu op zit.  
Als je "theirs" invoert, houd je hun bestand op de branch waar je nu op zit..  
**LET OP: JE MOET WEL DE PATH NAAR HET BESTAND AANGEVEN.**  
  
# ALS JE EEN UPDATE AF HEBT.
**Dan voeg je alle veranderde bestanden toe aan de nieuwe commit die je gaat maken.**  
Dit doe je door middel van:  
**git add .**  
zo voeg je alle bestanden toe aan de nieuwe commit.  
Je kan elke commit zien als een nieuwe versie van jouw branch met updates, en nieuwe bestanden.  
Je moet niet alleen nieuwe bestanden toevoegen, **ook aangepaste bestanden**, anders neemt hij de aanpassingen niet mee in de nieuwe commit!  
  
**Hierna commit je de update, ofterwijl je maakt een nieuwe versie van jouw branch.**  
Dit doe je met het commando:  
**git commit -m "Wat heb je veranderd? Wat heb je toegevoegd? Geef dit hier aan!"**  
  
# OVERIGE COMMANDO"S
**Commit een update, en maak hem klaar om te uploaden.**  
git commit -m "Wat heb je veranderd? Wat heb je toegevoegd? Geef dit hier aan!"  
  
**origin is de remote repository op github (voorbeeld: https://github.com/ROCMondriaanTIN/project-greenfoot).**  
**master is de branch die je op de repository wilt zetten.**  
**Dus als je bijvoorbeeld aan de branch 'Level3' werkt, dan voer je Level3 in in plaats van master!**
**Haal de nieuwste commit(versie) van de branch waar je op zit van de server.**  
git pull origin master  
  
**Zet jouw commit(versie) van de branch waar je op zit op de server.**  
git push origin master  
  
**Als je niet elke keer origin master wilt invoeren,** [kijk dan hiernaar](https://devconnected.com/how-to-set-upstream-branch-on-git/)
**Maak een nieuwe branch, en wissel onmiddelijk naar deze branch:**  
git checkout -b **NAAM**  
  
**Bekijk alle branches:**  
git branch -a  
> De branch met een * ervoor is de branch waar je momenteel op zit.
> Hierna moet je het bestand toevoegen aan de nieuwe commit.
  
**ALS JE EEN BESTAND VAN EEN ANDERE BRANCH WILT CLONEN, DAN:**  
git checkout Jouw_Branch  
**OF**  
git checkout Andere_Branch path/to/file.txt  
git add . **< JE VOERT DIT UIT OM HET NIEUWE BESTAND TOE TE VOEGEN AAN JE BRANCH**  
  
**Je kan een bestand of map toevoegen aan een branch door middel van:**  
git add **path/to/file.css**  
  
**Je kan alle bestanden of mappen toevoegen aan een commit door middel van:**  
git add .  
  
**Bij eventuele vragen kan je dit altijd aan een leraar of iemand anders vragen.**  
