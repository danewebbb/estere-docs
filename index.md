---
layout: home
title: Panoramica
nav_order: 1
description: Documentazione ufficiale di Estere
---

# Estere

Software AI per la lettura di fatture estere e la creazione automatica dell'autofattura su Fatture in Cloud.

> **Cosa fa Estere?**
> Carichi una fattura estera in PDF, l'AI estrae automaticamente tutti i dati rilevanti, e con un click crei l'autofattura direttamente sul gestionale del tuo cliente su **Fatture in Cloud**.

## Come funziona

Il flusso di Estere si articola in tre passaggi:

1. **Carica** la fattura estera in PDF dall'interfaccia web
2. **Estere legge** il documento tramite AI (OpenAI GPT) e popola tutti i campi: fornitore, importo, numero fattura, data, codice fiscale estero, nazione, ecc.
3. **Crea l'autofattura** su Fatture in Cloud in un click — il documento viene creato come `self_supplier_invoice` direttamente tramite le API FiC

## Sezioni della documentazione

| Sezione | Descrizione |
|---|---|
| [Guida Utente](/fattureestere/guida-utente/) | Come caricare le fatture, collegare Fatture in Cloud e creare le autofatture |
| [Architettura Tecnica](/fattureestere/architettura/) | Stack tecnologico, flusso dei dati e schema del database |
| [API Reference](/fattureestere/api-reference/) | Tutti gli endpoint REST e le Supabase Edge Functions documentati |
| [Field Mapping](/fattureestere/field-mapping/) | Corrispondenza tra i campi parsati dalla fattura e i campi FiC |
| [FAQ](/fattureestere/faq/) | Domande frequenti su utilizzo, integrazione e risoluzione dei problemi |
