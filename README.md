Zadání závěrečné práce: Webová aplikace pro rezervaci sedadel v kině.

Cíl práce

Cílem této závěrečné práce je vytvořit webovou aplikaci pro rezervaci kinových sedadel. Aplikace bude postavena na frameworku Flask, využije Bootstrap 5 pro responzivní design a bude integrovat API pro načítání filmů. Ceny představení budou načítány ze souboru ve formátu JSON.

Funkce aplikace

1. Načítání filmů z API:
   * Na hlavní stránce aplikace budou zobrazeny filmy načtené z free API.
   * Filmy budou zobrazovány v seznamu s názvem, obrázkem a tlačítkem detail.
   * Po kliknutí na konkrétní film se uživatel přesměruje na stránku s detaily filmu.
2. Detaily filmu:
   * Na této stránce se objeví obrázek, nějaké informace o filmu (popis, herci, režisér apod.) 
   * Tlačítko Rezervace
3. Formulář pro rezervaci:
   * Uživatel vyplní svůj e-mail a vybere cenu lístku (ta se načítá z JSON souboru).
   * Tyto údaje budou uloženy do databáze.
4. Správa rezervací (něco navíc, nepovinné):
   * Na speciální URL pro administrátora (např. /admin) se zobrazí seznam všech filmů na které máme rezervace.
   * Po výběru konkrétního filmu se zobrazí všechny rezervace pro tento film.
   * Po kliknutí na tlačítko “Smazat” se rezervace odstraní a sedadlo se uvolní.

Technické požadavky

* Framework: Flask
* Design: Bootstrap 5
* JavaScript framework: Dle výběru
* API pro filmy: RapidAPI Movies
* Načítání cen představení ze souboru ve formátu JSON
* UML diagram projektu
* Technická dokumentace
________________
Zásady objektově orientované aplikace
Celá aplikace by měla dodržovat zásady objektově orientovaného programování, jako je zapouzdření, dědičnost a polymorfismus.

UML diagram
Před začátkem si navrhněte pomocí UML Doménového modelu, objektovou strukturu webu. Před tím Vám může i pomoci Use Case diagram.

Dokumentace
Veškeré metody budou popsány pomocí komentářů… příklad viz níže
