**Table of content**

- [INTRODUCERE](#introducere)
- [Utilizatori si Serviciile applicatiei](#utilizatori-si-serviciile-applicatiei)
    - [Utilizatorii paginilor web :](#utilizatorii-paginilor-web-)
    - [Utilizatorii applicatiei Android :](#utilizatorii-applicatiei-android-)
    - [Utilizatorii Webserviciilor :](#utilizatorii-webserviciilor-)

# INTRODUCERE

> *Biroul Istoriilor de Credit Infodebi* in continuare (***BIC INFODEBIT***) reprezinta o baza unica de date, care acumuleaza informatia de la Banci, Organizatii de Creditare Nebancare (***OCN***), Utilitati, Companii de Telecomunicatii etc., cu privire la creditele acordate persoanelor fizice / juridice si stocarea istoricul acestora.

> ***Clientii*** interesati de Istoricul Creditar a subiectului de credit sunt institutiile financiare ce doresc sa gestioneze riscurile de default a creditelor acordate. Prin urmare clientii apeleaza la serviciile infodebit pentru a verifica clientul sau inainte de a eliberarea creditului.


# Utilizatori si Serviciile applicatiei

> Applicatia infodebit este exploatata de utilizatori prin intermediul :
> 1. Paginilor web
> 2. Aplicatie android
> 3. WebServicii 

### Utilizatorii paginilor web :

1. **[Web Client / Organization](/ref_doc/WebClientOrg.md)** - Organizatiile ce au semnat contract de prestare servicii cu compania infodebit. Acest tip de client declara lista utilizatorilor (identificarea dupa IDNP) autorizati carora trebuie sa le oferim acces la sistem.
Dupa acordarea accesului, utilizatorii utilizeaza semnatura electronica sau mobila pentru autentificarea in sistemul infodebit.
2. **Web Client / Individuals()** - Reprezinta persoanele fizice ce doresc sa se logheze in cabinetul personal in baza semnaturii mobile sau electronice, pentru verificarea raportului personal.
3. **Web Client / Managers** - Reprezinta angajatii Infodebit, ce utilizeaza panoul administrativ (vizionarea rapoarte, oferirea accesului, crearea utilizatorilor, etc.)

> Web Client/Manager, Web Client/Organization, Web Client/Individuals - toate sunt medii diferite de consumarea serviciului si trebuie despartite. La momenul actual ele se afla pe acelasi domen.

<br/>

### Utilizatorii applicatiei Android :

- Applicatia Android este destinata utilizatorilor (Client / Individuls) - persoanele fizice ce doresc sa se logheze in cabinetul personal in baza semnaturii mobile sau electronice, pentru verificarea raportului personal.
- Applicatia Android utilizeaza webserviciile pentru solicitarea informatia de la applicatia infodebit.

<br/>


### Utilizatorii Webserviciilor : 

- Utilizatorii Webserviciile sunt (Client / Organizations) - clientii ce au incheiate contract de prestari servicii cu compania infodebit.
- Utilizatorii dati utilizeaza webserviciile pentru integrarea produsului infodebit in applicatia proprie.


![Infodebit Services](img/Service_Actors.png)