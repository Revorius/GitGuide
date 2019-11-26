Wil je niet constant inloggen? Voer dan:
git config --global user.name 'email_of_gebruikersnaam_op_github'
git config --global user.password 'jouw_wachtwoord_op_github'
in in de terminal voordat je iets doet.

BIJ HET KLONEN VAN EEN REPOSITORY:
Clone de repository van GitHub naar jouw computer:
git clone https://github.com/ROCMondriaanTIN/project-greenfoot-game-molotov

BIJ HET MAKEN VAN EEN NIEUWE REPOSITORY:


Maak een nieuwe branch, en wissel onmiddelijk naar deze branch:
git checkout -b [NAAM]

Push deze branch naar de server.
git push origin [NAAM]

Bekijk alle branches
git branch -a
De branch met een * ervoor is de branch waar je momenteel op zit.

In het geval van conflicts met mergen kan je twee dingen doen:

1) Het bestand editen, zie: 
2) Het commando:
git checkout --[ours/theirs] path/to/conflict-file.css
uitvoeren. Als je "ours" invoert, houd je je eigen bestand.
Als je "theirs" invoert, houd je hun bestand.

Hierna moet je het bestand toevoegen aan de nieuwe commit.
Dit kan op meerdere manieren.
Je kan een map toevoegen aan een commit door middel van
