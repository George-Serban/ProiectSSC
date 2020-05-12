# ProiectSSC
Tema SSC AN4

###Descrierea aplicaţiei

Aplicatia este folosita pentru a crea automatizat un setup in OpenStack. Vor fi create toate elementele de suport, cum ar fi: o retea, o subretea, un router si un VM. Pentru a securiza VM-ul va fi creat un grup de securitate caruia ii vor fi atasate reguli de permitere a accesului doar pe porturile de SSH, HTTP, HTTPS (20, 80, 443) ale masinii virtuale.

###Motivaţie alegere tema:

Am ales aceasta tema deoarece este in concordanta cu cerintele, folosind atat tehnologii cloud cat si introducerea unor elemente de securitate. De asemenea, tehnologiile folosite imi sunt familiare din mediul profesional.

###Utilitatea aplicaţiei:

Aplicatia este folosita pentru a crea rapid un setup ca cel mentionat anterior insa poate fi usor modificata pentru a mari numarul de elemente/modifica configuratia.

###Pasi pentru rularea aplicatiei:
1.	Descarcarea codului:
	git clone https://github.com/George-Serban/ProiectSSC.git

2.	Setarea parametrilor de environment:
	source ~/devstack/openrc admin admin

3.	Rularea playbook-ului:
	ansible-playbook pbook.yaml

