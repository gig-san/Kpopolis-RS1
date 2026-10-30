# Kpopolis – Web Shop

Kpopolis je web aplikacija namijenjena prodaji neoficijalnih Kpop proizvoda i personalizovanih proizvoda izrađenih prema željama kupaca.

Projekat se razvija u okviru predmeta **Razvoj softvera I**, na Fakultetu informacijskih tehnologija.

## O projektu

Kpopolis je brend iz Bosne i Hercegovine koji se bavi izradom i prodajom Kpop merchandise proizvoda, uključujući cekere, bedževe, fotokartice, stikere, privjeske i druge personalizovane artikle.

Trenutno se prodaja i komunikacija s kupcima odvijaju putem društvenih mreža Instagram, TikTok i Facebook.

Cilj projekta je razviti web aplikaciju koja će omogućiti jednostavnije pregledavanje i naručivanje proizvoda, uz centralizovano upravljanje proizvodima, narudžbama i zalihama.

Poseban fokus stavljen je na personalizaciju proizvoda, praćenje njihove izrade i unapređenje organizacije poslovanja.

## Planirane funkcionalnosti

### Korisnički dio aplikacije

- Registracija, prijava i upravljanje korisničkim profilom.
- Pregled, pretraga i filtriranje proizvoda.
- Pregled detalja, cijena i dostupnosti proizvoda.
- Dodavanje proizvoda u korpu i upravljanje korpom.
- Kreiranje narudžbi i unos podataka za dostavu.
- Pregled historije i praćenje statusa narudžbi.
- Personalizacija proizvoda prema željama kupca.
- Upload vlastitih fotografija za personalizaciju.
- Praćenje statusa izrade personalizovanih proizvoda.
- Pregled najprodavanijih proizvoda.
- Primanje obavještenja o promjenama statusa narudžbi.

### Administratorski dio aplikacije

- Upravljanje proizvodima i kategorijama.
- Upravljanje narudžbama i njihovim statusima.
- Pregled i odobravanje zahtjeva za personalizaciju.
- Upravljanje zalihama i evidencija njihovih promjena.
- Upozorenja o niskom stanju zaliha.
- Upravljanje popustima i promotivnim ponudama.
- Pregled osnovnih izvještaja o prodaji.

## Tehnologije

**Backend**
- C# / ASP.NET Core Web API (.NET 10)
- Entity Framework Core
- SQL Server
- Clean Architecture
- CQRS / MediatR
- FluentValidation
- JWT autentifikacija

**Frontend**
- Angular 21
- TypeScript
- HTML i CSS
- Angular Material

**Razvojni alati**
- Git i GitHub
- GitHub Issues i GitHub Projects
- JetBrains Rider / Visual Studio
- Visual Studio Code / WebStorm

## Struktura projekta

- `Market.Backend/` – backend aplikacije, API i pristup bazi podataka.
- `Market.Frontend/` – Angular korisnički interfejs.
- `db-backups/` – sigurnosne kopije baze podataka.
- `dokumenti/` – dijagrami, modeli i projektna dokumentacija.

## Pokretanje aplikacije

Projekat je zasnovan na početnom RS1 projektu, koji zahtijeva:

- .NET 10 SDK
- Node.js kompatibilan s Angularom 21
- SQL Server
- JetBrains Rider ili Visual Studio 2026 za backend
- VS Code ili WebStorm za frontend

## Početni projekat

Aplikacija se razvija na osnovu zvaničnog početnog projekta predmeta Razvoj softvera I za akademsku 2026/27. godinu.

Izvor: https://github.com/adil-fit-ba/rs1-2026-27

Početni projekat sadrži unaprijed implementirane funkcionalnosti koje se koriste kao osnova za razvoj vlastitog rješenja.