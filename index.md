---
layout: default
title: Documentazione
description: Documentazione ufficiale di Estere
---

<h1>Estere</h1>
<p class="page-subtitle">Software AI per la lettura di fatture estere e la creazione automatica dell'autofattura su Fatture in Cloud.</p>

<div class="callout callout-info">
  <strong>Cosa fa Estere?</strong><br />
  Carichi una fattura estera in PDF, l'AI estrae automaticamente tutti i dati rilevanti, e con un click crei l'autofattura direttamente sul gestionale del tuo cliente su <strong>Fatture in Cloud</strong>.
</div>

## Come funziona

Il flusso di Estere si articola in tre passaggi:

1. **Carica** la fattura estera in PDF dall'interfaccia web
2. **Estere legge** il documento tramite AI (OpenAI GPT) e popola tutti i campi: fornitore, importo, numero fattura, data, codice fiscale estero, nazione, ecc.
3. **Crea l'autofattura** su Fatture in Cloud in un click — il documento viene creato come `self_supplier_invoice` direttamente tramite le API FiC

<div class="doc-cards">
  <a href="/guida-utente/" class="doc-card">
    <div class="doc-card-icon">📖</div>
    <div class="doc-card-title">Guida Utente</div>
    <div class="doc-card-desc">Come caricare le fatture, collegare Fatture in Cloud e creare le autofatture.</div>
  </a>
  <a href="/architettura/" class="doc-card">
    <div class="doc-card-icon">🏗️</div>
    <div class="doc-card-title">Architettura Tecnica</div>
    <div class="doc-card-desc">Stack tecnologico, flusso dei dati e schema del database.</div>
  </a>
  <a href="/api-reference/" class="doc-card">
    <div class="doc-card-icon">⚡</div>
    <div class="doc-card-title">API Reference</div>
    <div class="doc-card-desc">Tutti gli endpoint REST e le Supabase Edge Functions documentati.</div>
  </a>
  <a href="/field-mapping/" class="doc-card">
    <div class="doc-card-icon">🔗</div>
    <div class="doc-card-title">Field Mapping</div>
    <div class="doc-card-desc">Corrispondenza tra i campi parsati dalla fattura e i campi FiC.</div>
  </a>
  <a href="/faq/" class="doc-card">
    <div class="doc-card-icon">💬</div>
    <div class="doc-card-title">FAQ</div>
    <div class="doc-card-desc">Domande frequenti su utilizzo, integrazione e risoluzione dei problemi.</div>
  </a>
</div>
