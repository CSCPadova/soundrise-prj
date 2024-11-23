# Soundrise

**Description:** SoundRise 2.0 is an application developed in React JS with the aid of Web Audio API, designed to help people with communication difficulties, especially children. The application provides an intuitive interface that allows the user to practise speech therapy voice exercises independently. The interface consists of a sun that symbolises the user’s voice and is animated according to the tonal and timbral characteristics of the voice itself: it analyses these vocal characteristics and displays a correspondent visual feedback in real time.

This application is the result of years of study and research by the CSC (Centro di Sonologia Computazionale). For years, the CSC has aimed to promote learning activities that encourage children, by considering physical actions as an integral part of cognition, through the use of technological enhancement.  
During these years, a number of prototypes have been developed and then shelved. The last update of Soundrise aims to develop an application maintainable over time, undertaking a reactivation process previously designed at CSC for the preservation and reactivation of artefacts.  
  
**Authors**: _Giada Zuccolo_; _Riccardo Fila_; _Stefano Giusto_; _Marco Randon_; _Gabriele Turetta_; _Alessandro Fiordelmondo_; _Antonio Rodà_; _Federico Avanzini_; _Sergio Canazza_; _Serena Zanolla_; _Raul Masu_

**Date Created** 2012  
**Last Update** 2023  

<img src="archive/photo/2023-soundrise2.0.png" alt="SOUNDRISE 2.0" height="500">

## Old Versions
| Year                       | Link                       | Img                       |
|:-------------------------------:|:-------------------------------:|:-------------------------------:|
| 2012 | [__Giusto__](./archive/past_versions/2012-Giusto/)  | <img src="archive/photo/2012-console di controllo di SounRise.png" width="150"> |
| 2012 | [__Randon__](./archive/past_versions/2012-Randon) | <img src="archive/photo/2012-interfaccia b.png" width="150"> |
| 2023 | [__Turetta__](./archive/past_versions/2023-Turetta) | <img src="archive/photo/2023-nuova interfaccia.png" width="150"> |

## Technical Notes

<details>

<!-- <summary>Technical Notes</summary> -->

### How soundrise works

**Flowchart - Audio feature extraction to graphical feedback** 
The application captures audio features from your voice using the device’s microphone and utilizes them to generate graphical feedback.

<img src="archive/data/2023-flowchart-audiofeature2graphic.png" alt="Audio feature extraction to graphical feedback" height="500">

The audio features of your voice are mapped to the movement of a sun on the screen.

<img src="archive/data/2012-mapping-audiofeature2graphic.png" alt="Mapping - Audio feature extraction to graphical feedback" height="200">

With the timber we consider only the five italian vowels

__link vowels-colors__  
[a] ⇒ rosso;  
[O] ⇒ arancione;   
[E] ⇒ verde;  
[i] ⇒ blu;  
[u] ⇒ grigio  

The vowels are extracted through an algorithm of Linear Predictive Coding (LPC) using defined vowel formants

<img src="archive/data/2023-instruction-formants-vowel.png" alt="Vowel format" height="70">

## Video Demostration
<video controls src="archive/video/2023-soundrise2.0-demo.mp4" title="Title"></video>

[link to the video](archive/video/2023-soundrise2.0-demo.mp4)

</details>

## Bibliography

<details>

####
| title | __SoundRise: studio e progettazione di un'applicazione multimodale interattiva per la didattica basata sull'analisi di feature vocali__|
| --- | --- |
| author | __Stefano Giusto__ |
| date | 2012-07-17 |
| type | __thesis__ |  
| link | [https://hdl.handle.net/20.500.12608/15800](https://hdl.handle.net/20.500.12608/15800)|
| bibtex | @article{giusto2012soundrise,title={SoundRise: studio e progettazione di un'applicazione multimodale interattiva per la didattica basata sull'analisi di feature vocali},author={Giusto, Stefano},year={2012}}|
####
| title | __SoundRise: sviluppo e validazione di un'applicazione multimodale interattiva per la didattica basata sull'analisi di feature vocali__|
| --- | --- |
| author | __Marco Randon__ |
| date | 2012-07-17 |
| type | __thesis__ |  
| link | [https://hdl.handle.net/20.500.12608/15833](https://hdl.handle.net/20.500.12608/15833)|
| bibtex | @article{randon2012soundrise,title={SoundRise: sviluppo e validazione di un'applicazione multimodale interattiva per la didattica basata sull'analisi di feature vocali},author={Randon, Marco},year={2012}} |
####
| title | __Soundrise 2.0: Sviluppo di un'interfaccia grafica interattiva in Three.js per supportare persone con disabilità uditive__|
| --- | --- |
| author | __Gabriele Turetta__ |
| date | 2023 |
| type | __thesis__ |  
| link | [https://hdl.handle.net/20.500.12608/44069](https://hdl.handle.net/20.500.12608/44069)|
| bibtex | @article{turettasoundrise,title={Soundrise 2.0: Sviluppo di un'interfaccia grafica interattiva in Three. js per supportare persone con disabilit{\`a} uditive},author={TURETTA, GABRIELE}} |
####
| title | __Soundrise 2.0: Sviluppo di un modello di riconoscimento timbrico per un sistema di assistenza web dedicato a persone con disabilità uditive__ |
| --- | --- |
| author | __Riccardo Fila__ |
| date | 2023 |
| type | __thesis__ |  
| link | [https://hdl.handle.net/20.500.12608/53325](https://hdl.handle.net/20.500.12608/53325)|
| bibtex | @article{filasoundrise,title={SOUNDRISE 2.0: Sviluppo di un modello di riconoscimento timbrico per un sistema di assistenza web dedicato a persone con disabilit{\`a} uditive},author={FILA, RICCARDO}}|
####
| title | __A New Sunrise for Speech Therapy: Development of SoundRise 2.0 Application__ |
| --- | --- |
| author | __Giada Zuccolo__ |
| date | 2023 |
| type | __thesis__ |  
| link | [https://hdl.handle.net/20.500.12608/60413](https://hdl.handle.net/20.500.12608/60413)|
| bibtex | |

</details>

## About repository

<details>

This repository serves as a tool for preserving the application and research project.  
The repository follows the guideline of the _Multilevel Dynamic Preservation_ (MDP) model ([https://www.frontiersin.org/articles/10.3389/frsip.2023.1183294/full](https://www.frontiersin.org/articles/10.3389/frsip.2023.1183294/full))  

</details>