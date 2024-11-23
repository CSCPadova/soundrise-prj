## Description
In questo lavoro si presentano i passi e gli strumenti utilizzati per lo sviluppo di SoundRise a partire da un prototipo Pure Data e i primi test effettuati per valutare e migliorare il risultato ottenuto.  
SoundRise è un’applicazione multimodale e interattiva a fini didattici, finalizzata a proporre ai bambini della scuola primaria una modalità alternativa di apprendimento delle caratteristiche del suono. Il bambino può esplorare tali caratteristiche attraverso una rappresentazione grafica in tempo reale delle proprie produzioni vocali.
Protagonista di questo gioco è il sole e mediante la sua posizione sull’orizzonte di un paesag- gio stilizzato, le sue dimensioni e il suo colore si cerca di dare una raffigurazione coerente delle caratteristiche sonore.  
L’altezza del sole sull’orizzonte corrisponde all’altezza del tono prodotto dall’utente, la sua dimensione all’ampiezza della produzione, mentre la durata è rappresentata dal viso sorridente del sole che apre o chiude gli occhi in presenza o assenza di produzione vocale. Non poten- do ottenere un’immagine ragionevole del timbro partendo dall’analisi delle caratteristiche della voce, quest’ultimo è sostituito con una visualizzazione delle cinque vocali della lingua italiana associando a ciascuna un colore col quale disegnare il sole.  
Le caratteristiche possono essere ispezionate singolarmente oppure tutte assieme, lasciando piena libertà di scelta al bambino.
Si è cercato di proporre un’interfaccia semplice e amichevole, che fosse intuitiva e non cau- sasse confusione o distraesse l’utente dall’obiettivo dell’applicazione, basandosi su alcune delle caratteristiche indicate come importanti per una applicazione di questo tipo nel lavoro di Anne- MarieO ̈ster dove si valutal’applicazione clinica di un’applicazione di speech training nel trattamento di bambini affetti da deficit uditivo.  
Tra gli obiettivi di questo lavoro vi è lo studio delle potenzialità offerte dall’uso di Pure Data e libpd, una libreria C++ che consente di integrare un’istanza di Pure Data all’interno di una applicazione qualsiasi. Questa libreria permette di utilizzare Pure Data per creare in modo semplice e veloce un prototipo di ciò che si vuole realizzare e di convertirlo successivamente in un’appli- cazione multi-piattaforma facilmente distribuibile, in quanto non dipendente dalla presenza di Pure Data nel computer dell’utente. Molto interessante è la possibilità di creare applicazioni per i principali sistemi operativi mobili a partire dallo stesso codice.
Si è cercato inoltre di strutturare il progetto in modo da ottenere una piattaforma versatile e adattabile alla sperimentazione delle tecnologie di analisi audio nel trattamento di patologie che interessano la produzione vocale di base.  
Questo progetto è stato testato su sistemi Apple Mac OS X, Apple iOS, Microsoft Windo- wsXP e Microsoft Windows7. Il test e l’eventuale adattamento su piattaforme GNU/Linux e Google Android saranno oggetto di lavori futuri.  
Nel primo capitolo si propone una selezione di lavori riguardanti applicazioni a supporto di logopedisti e terapeuti nel trattamento di patologie che riguardano la produzione vocale, sia dovute a deficit fisici che neurologici. Infine si propone una panoramica sul campo molto recente delle applicazioni per dispositivi mobili a supporto di persone affette da disturbo autistico, dei loro familiari o dei terapeuti che si occupano di queste sindromi.  
Nel secondo capitolo si presentano gli obiettivi di questo lavoro, un’analisi degli strumenti utilizzati, le caratteristiche dei progetti per lo sviluppo delle tre versioni dell’applicazione e le linee guida da rispettare per realizzare una patch Pure Data adatta ad essere utilizzata con libpd. Infine si descrivono le parti più interessanti del codice sorgente prodotto.  
Nel terzo capitolo si illustrano le caratteristiche offerte dell’interfaccia grafica dell’applica- zione e le modalità di utilizzo.  
Infine nel quarto capitolo vengono esposti i risultati di un test sull’usabilità dell’applicazione sottoposto a un pubblico eterogeneo di utenti.  

## bit
[SoundRise C++ Source Code](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/bit/Randon.zip)

## data
**Flowchart - Audio feature extraction**  
![Flowchart - Audio feature extraction](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/data/flowchart-audiofeatureextraction.png)  
**Mapping - Audio features to graphical feedback**  
![Mapping - Audio features to graphical feedback](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/data/mapping-audiofeature2graphic.png)  

__link vowels-colors__  
[a] ⇒ rosso;  
[O] ⇒ arancione;   
[E] ⇒ verde;  
[i] ⇒ blu;  
[u] ⇒ grigio  

## experience
**SoundRise Interface A**  
![SoundRise Interface A](https://github.com/zGiada/soundrise-application/blob/main/2012_Randon/experience/interfaccia%20a.png)  
**SoundRise Interface B**  
![SoundRise Interface B](https://github.com/zGiada/soundrise-application/blob/main/2012_Randon/experience/interfaccia%20b.png)  
**Evaluation of the application**  
![Evaluation of the application](https://github.com/zGiada/soundrise-application/blob/main/2012_Randon/experience/validazione%20applicazione.png)  

