## Description
Nel campo della didattica rivolta ai bambini possono essere impiegati, assieme ai tradizionali me- todi di insegnamento, strumenti basati su tecnologie multimediali. Alcune soluzioni propongono sistemi che permettono l’insegnamento di nozioni teoriche, ad esempio le norme di sicurezza in un campus, le regole per uno stile di vita corretto o concetti di botanica, puntando ad uno sviluppo della capacità di analisi, comprensione, memorizzazione e valutazione. Altre stimolano il parlato del bambino incoraggiandolo a ripetere parole o fonemi avvalendosi in alcuni casi di ani- mazioni video che mostrano la parte interna ed esterna del tratto vocale. Molte delle applicazioni si presentano però sofisticate e difficili da utilizzare e non in grado di coinvolgere pienamente il bambino nell’attività didattica.
In questo lavoro viene presentato il processo di realizzazione di un’applicazione multimodale interattiva per la didattica, denominata SoundRise, basata sull’analisi real-time di feature vocali. SoundRise è proposta come un nuovo modo di insegnare ai bambini le caratteristiche della propria voce attraverso un’esplorazione delle capacità vocali, facendo modo che sia lo stesso bambi- no a scoprire, e poi interpretare e comprendere, il contenuto informativo che riceve attraverso un feedback grafico. Egli ricopre un ruolo attivo dal momento che è lui stesso a controllare tramite la propria voce l’evoluzione grafica del feedback. Questo offre un incentivo all’utilizzo dell’applicazione, con la possibilità di ottenere un maggior impegno e tempo dedicato all’utilizzo di SoundRise. L’applicazione è inoltre creata per essere utilizzabile su sistemi operativi differenti, quali Windows, Mac OS X e Linux, e sviluppata pensando anche alla possibilità di estenderne la multimodalità grazie all’integrazione con un altro sistema interattivo, la Stanza Logo-Motoria. Questo impiego dell’applicazione permette di rendere ancora più attivo il ruolo del bambino, consentendo un esplorazione dell’ambiente in cui i due sistemi sono installati.  
Per la progettazione è stato utilizzato l’ambiente di programmazione grafica real-time Pure Data (Pd). In appoggio agli oggetti di elaborazione audio forniti da Pd, è stata utilizzata una libreria esterna denominata timbreID per l’analisi del timbro vocale.  
Nel primo capitolo vengono proposti sistemi multimodali per la didattica intesi come strumenti per aiutare i bambini nel processo cognitivo di nozioni teoriche, che non interessano un’analisi delle produzioni vocali, ed applicazioni che propongono invece un riconoscimento del parlato e delle vocalizzazioni per l’insegnamento ed il training.
Nella prima parte del secondo capitolo viene presentata l’idea alla base del progetto SoundRise, gli obiettivi di questo lavoro e gli strumenti utilizzati per lo sviluppo. Segue poi uno studio sul- l’estrazione delle feature ed in particolare del timbro, per il riconoscimento delle cinque vocali della lingua italiana, e una panoramica della patch Pure Data che definisce SoundRise, descriven- do inoltre l’interfaccia grafica ed il mapping delle feature in contenuti informativi multimediali. Nel terzo capitolo si includono i risultati dei test di studio fatti per identificare le soluzioni piu` adatte all’estrazione delle feature timbriche. Seguono inoltre i risultati di una fase di speri- mentazione fatta per valutare l’intuitività dell’interfaccia grafica di SoundRise e dalla quale si sono ricavate utili indicazioni di tendenza da confrontare con le prestazioni dell’applicazione riscontrate.

## bit

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
**SoundRise PD patch**  
![SoundRise PD patch](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/experience/contenuto%20della%20patch%20Sounrise%20pd.png)  
**SoundRise Control Console**  
![SoundRise Control Console](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/experience/console%20di%20controllo%20di%20SounRise.png)  
**A PC running soundrise**  
![A PC running soundrise](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/experience/SoundRise%20in%20esecuzione%20su%20un%20PC.png)  
**SoundRise grphical apprence 1**  
![SoundRise grphical apprence 1](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/experience/esempio%20di%20schermata%20della%20finestra%20grafica%20a.png)  
**SoundRise grphical apprence 2**  
![SoundRise grphical apprence 2](https://github.com/zGiada/soundrise-application/blob/main/2012_Giusto/experience/esempio%20di%20schermata%20della%20finestra%20grafica%20b.png)

