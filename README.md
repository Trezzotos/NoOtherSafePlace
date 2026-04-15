# Survival Horror UE

![Map Overview](docs/images/Overview.PNG)

---

## Overview

**Survival Horror UE** è un progetto _**in sviluppo**_ realizzato con Unreal Engine, progettato come vertical slice di un’esperienza survival horror moderna ispirata ai classici del genere.

Il focus principale è sulla costruzione della tensione attraverso level design, gestione delle risorse e sistemi di gioco modulari. Il progetto punta a dimostrare competenze tecniche nella progettazione di gameplay systems, AI comportamentale e ottimizzazione in real-time.

---

## Key Features

* Gameplay loop survival horror basato su esplorazione, combattimento e puzzle
* Sistema di inventario con gestione limitata delle risorse
* Enemy AI con stati comportamentali dinamici
* Level design interconnesso con backtracking
* Atmosfera costruita tramite lighting dinamico e audio spaziale
* Architettura modulare scalabile

---

## Gameplay

![Exploration](docs/images/gameplay_02.png)

Il gameplay è costruito attorno a:

* **Exploration-driven progression**: avanzamento tramite scoperta e risoluzione di enigmi
* **Resource management**: munizioni e oggetti limitati
* **Deliberate combat design**: combattimento intenzionalmente lento e rischioso
* **Environmental storytelling**: narrativa integrata negli ambienti
* **Tension pacing**: alternanza tra calma e pericolo

---

## Systems Architecture

Il progetto è strutturato secondo un’architettura modulare per garantire scalabilità e manutenibilità.

**Core Systems:**

* **Player Controller**
  Gestione input, movimento, interazioni e stato del player

* **Inventory System**
  Gestione oggetti, stacking, combinazioni e utilizzo

* **Enemy AI System**
  AI basata su Behavior Trees con stati: Idle, Patrol, Alert, Chase, Attack

* **Game State Manager**
  FSM semplificata per controllo stati globali

* **Interaction System**
  Sistema generico per oggetti interattivi e puzzle

* **Save System**
  Persistenza dei dati di gioco e checkpoint

---

## AI & Enemies

![Enemy Encounter](docs/images/enemy_01.png)

L’intelligenza artificiale è progettata per massimizzare la pressione sul giocatore:

* Sistema di percezione basato su **vista e suono**
* Transizioni dinamiche tra stati comportamentali
* Reazioni contestuali alle azioni del player
* Supporto per estensione a diversi archetipi di nemici

---

## Technical Highlights

* **Unreal Engine (Blueprint + C++)**
* Behavior Trees per AI
* Event-driven architecture (Event Dispatchers)
* Dynamic lighting per mood e leggibilità
* Spatial audio per immersione
* Collision & interaction system modulare
* Ottimizzazione per ambienti indoor

---

## Development Status

**Stato attuale**: In sviluppo (Vertical Slice)

**Progressi principali:**

* [x] Core gameplay loop
* [x] Sistema inventario base
* [x] AI nemico prototipo
* [x] Level blockout iniziale
* [ ] Combat system avanzato
* [ ] Puzzle system completo
* [ ] UI/UX finale
* [ ] Polish e ottimizzazione

---

## Build & Usage

Il progetto può essere eseguito tramite Unreal Engine:

* Play direttamente in editor
* Test delle singole feature in mappe dedicate
* Build standalone per Windows

---

## Media

![Environment](docs/images/environment_01.png)
![Interior](docs/images/environment_02.png)
![UI](docs/images/ui_01.png)

---

## Goals

Questo progetto è stato sviluppato per dimostrare:

* Progettazione di sistemi di gioco modulari
* Implementazione di AI comportamentale
* Costruzione di atmosfera in un contesto horror
* Capacità di sviluppo end-to-end in Unreal Engine

---

## Notes

Il progetto è attualmente in fase di sviluppo attivo e soggetto a modifiche.
Ulteriori aggiornamenti e feature verranno integrati nelle prossime iterazioni.

---
