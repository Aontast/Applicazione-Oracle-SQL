# Applicazione Oracle Apex SQL

## Overview
Nella directory Databoss_App si trova l'export di un'Applicazione Oracle Apex SQL che permette di visualizzare i dati contenuti in un Database creato, sempre tramite oracle, seguendo la seguente traccia:

## Traccia
Un’agenzia spaziale internazionale sta sviluppando un sistema informatico per consentire la 
gestione e l’analisi avanzata dei dati raccolti durante le missioni di esplorazione lunare. 
Ciascuna missione prevede l’utilizzo di sensori avanzati posizionati in diverse regioni della 
superficie lunare e di robot autonomi che supportano le operazioni sul campo, insieme a un 
team di specialisti in orbita. Il sistema ha l’obiettivo di coordinare in tempo reale le attività dei 
membri della missione, gestire i dati provenienti dai sensori e consentire un monitoraggio 
completo e dettagliato delle operazioni in corso. 

## Features
- Coordinamento in tempo reale delle attività dei membri della missione
- Gestione dei dati provenienti dai sensori
- Monitoraggio completo e dettagliato delle operazioni in corso

## Entities
- **MISSIONE**: Identificata da un codice e caratterizzata da un obiettivo specifico (mappatura geologica, rilevamento di risorse, ecc.)
- **MEMBRI DELL’EQUIPAGGIO**: Responsabili della manutenzione e riparazione dei sensori
- **SENSORI**: Identificati da un ID univoco e registrati in base alla posizione geografica
- **ROBOT**: Utilizzati come supporto tecnico e identificati da un ID univoco
- **RILEVAZIONE**: Registrazione delle misurazioni effettuate dai sensori
- **ANOMALIA**: Stato dei sensori che richiede intervento
- **INTERVENTO**: Azioni per risolvere le anomalie
- **REPORT**: Compilazione dello stato delle missioni
- **...**

## Installation
1. Clone the repository
   ```sh
   git clone https://github.com/Aontast/Applicazione-Oracle-SQL.git
