# MVC-webprogrammering in Java

Deze repository bevat bronnen en oefeningen om de basisprincipes van webontwikkeling in Java te ontdekken, met behulp van **servlets** en **JSP-pagina's**.

> [!TIP]
> **Ga naar de volledige cursus:** [https://stahe.github.io/nl-java-web-mvc-mai-2006/](https://stahe.github.io/nl-java-web-mvc-mai-2006/)

---

## 📖 Inleiding

Het doel van dit lesmateriaal is om de basisbegrippen van Java-webprogrammering onder de knie te krijgen aan de hand van een **MVC 3-tier**-architectuur. Dit document is gebaseerd op het artikel uit januari 2005 „Webontwikkeling in Java met Eclipse en Tomcat”, met de volgende toevoegingen:

* Het gebruik van de **WTP-plugin voor Eclipse**.


* Een structuur gericht op **3-tier-architectuur**.


* Een concreet voorbeeld met gebruik van een **database**.



## 🏗️ Architectuur van de applicatie

Het project volgt een structuur met drie afzonderlijke lagen om de modulariteit en stabiliteit van de code te waarborgen:

| Laag | Beschrijving |
| --- | --- |
| **Weblaag [web]** | Interface waarmee de gebruiker de applicatie kan bedienen en informatie kan ontvangen.

 |
| **Bedrijfslaag [metier]** | Bevat de bedrijfsalgoritmen. Deze laag is onafhankelijk van de interface (web, console, enz.) en is de meest stabiele laag.

 |
| **Gegevenslaag [dao]** | Beheert de toegang tot persistente gegevens (DBMS) of externe gegevens (sensoren, netwerk).

 |

## 🚀 Leermethoden

Er zijn verschillende manieren om deze inhoud te benaderen, van de snelste tot de meest effectieve:

1. 
**Ervaren aanpak:** Installeer de tools en test de gedownloade code direct (alleen voor ontwikkelaars die bekend zijn met Eclipse/WTP).


2. **Snelle aanpak:** De code kopiëren en plakken volgens het document. Hiermee kun je snel vooruitgang boeken, maar sommige concepten kunnen ‘mysterieus’ blijven.


3. 
**Begeleide aanpak:** Identiek aan methode 2, maar met raadpleging van het referentiedocument `[ref1]` (Inleiding tot webprogrammeren in Java) zodra dit wordt aangeraden.


4. **Aanbevolen aanpak:** Typ de volledige code handmatig in terwijl je aandachtig leest. Dit is de meest effectieve methode om de logica te begrijpen en je eigen syntaxfouten te corrigeren.

