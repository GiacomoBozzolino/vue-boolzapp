Problema: Boolzapp - a (not very) innovative messaging platform

Ragionare una milestone alla volta, suddividendo il problema in sottosezioni più semplici.

Milestone 1
●	Replica della grafica con la possibilità di avere messaggi scritti dall’utente (verdi) e dall’interlocutore (bianco) assegnando due classi CSS diverse
●	Visualizzazione dinamica della lista contatti: tramite la direttiva v-for, visualizzare nome e immagine di ogni contatto


1- Realizzo la parte grafica della pagina web
2- assegnare due classi css diverse ai messaggi a seconda se dell'untente o dell'interlocutore
3- Collegare Vuejs al file e assicurarsi funzioni correttamente
4- Creazione della lista dei contatti, prima statica così da avere una traccia visiva del risultato e poi in modo dinamico prendendo i dati dall'array nel file js --> usare v-for



Milestone 2
●	Visualizzazione dinamica dei messaggi: tramite la direttiva v-for, visualizzare tutti i messaggi relativi al contatto attivo all’interno del pannello della conversazione
●	Click sul contatto mostra la conversazione del contatto cliccato

1- Creo un ciclo v-for che estragga i messaggi contenuto nell'array message a sua volta contenuto dentro l'array contacts
2- Faccio il binding di una classe per status e ci associo una condizione. ? se 0 a ricevuti assegno una classe css : altrimenti assegno un altra classe.
3- Creo una variabile in appdata main_chat a cui associo il valore =0
4- recupero questa variabile in una funzione per selezionare la chat corrispondente all'indice dell'array quando clicco su uno dei contatti.