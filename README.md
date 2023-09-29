# Eenvoudig aan de slag met Kubernetes HELM Charts

Jordi Obermeier, 29 september 2023

---

Deze blog is de deliverable voor het onderzoek naar Helm Charts in Kubernetes. Er wordt onderzocht naar Helm Charts en de werking met betrekking tot Kubernetes. Gedurende de DevOps minor is er geleerd om eenvoudig applicaties te deployen naar een cloud-omgeving. Het containerizen van een applicatie was hierin de eerste stap met Docker. Kubernetes was de vervolgstap om meerdere containers te containerizen. Kubernetes vangt een hoop problemen op zoals het automatisch opnieuw opstarten van pods wanneer deze down gaan, het verdelen van de workload over de nodes/ pods en het onderling samenwerken/ communiceren van containers binnen de Kubernetes cluster. Kubernetes doet dit met behulp van de gemaakte `.yaml` bestanden.

De hoofdvraag luidt als volgt: "Hoe kunnen software developers met beperkte kennis van Kubernetes succesvol HELM Charts gebruiken voor het deployen van containerized applicaties?"

De deelvragen luiden als volgt:

1. _Wat zijn Kubernetes en HELM Charts, en waarom zijn ze relevant voor software developers?_
2. _Wat zijn de voordelen en nadelen van het gebruik van HELM Charts voor het beheren van Kubernetes-applicaties?_
3. _Hoe kan ik een bestaande HELM Chart vinden en gebruiken voor mijn specifieke toepassing?_
4. _Hoe kan ik monitoring en onderhoud uitvoeren voor applicaties die zijn geïmplementeerd met HELM Charts?_

## Onderzoeksmethoden

Als ICT-student of -professional wordt er verwacht dat allerlei ICT-uitdagingen op te lossen zijn. Door het gebruik van de (verschillende) onderzoeksmethoden (Niels, 2022a) is het mogelijk snel antwoorden op vragen te krijgen en dus het probleem aan te pakken. Hieronder zijn de onderzoeksmethoden weergeven die gebruikt zijn tijdens het onderzoeksverslag "[Eenvoudig aan de slag met Kubernetes HELM Charts](../README.md)".

### Literature study (Library)

Literature study wordt gebruikt om informatie over HELM Charts te vergaren op het internet. Hierbij zijn er bronnen gebruikt, waarbij in de tekst(en) vermeld wordt waar de informatie vandaan is gehaald. Alle bronnen staan in de literatuurlijst.

### Community research (Library)

Community research wordt gebruikt om oplossingen te bieden voor de problemen waar de gemeenschap ook tegen aanloopt over HELM Charts. Hierbij worden meerdere bronnen bekeken om informatie te controleren op waarheden.

### Problem analyses (Field)

Problem analyses wordt gebruikt om te definiëren van het "waarom" en "wat" van het onderzoek voordat er dieper ingegaan wordt op het "hoe" (de onderzoeksmethodologie). Het legt een basis voor de gehele onderzoeksinspanning en zorgt ervoor dat het onderzoek relevant en doelgericht is.

### Pitch (Showroom)

Pitch wordt gebruikt om uiteindelijk het onderzoek te presenteren. Naast het onderzoek presenteren is de feedback dat hieruit komt waardevol om het onderzoek te verbeteren en te bekijken of de HELM Charts een goed idee is voor een volgend project.

### Prototyping (Workshop)

Prototyping wordt gebruikt om snel en visueel te valideren of een concept of idee haalbaar is en om eventuele risico's te identificeren. Er wordt dus een project gemaakt op basis van de HEML Chart.

## Literatuurlijst

- OpenAI. (2021). ChatGPT. Geraadpleegd op 29 september 2023, van [https://openai.com/research/chatgpt](https://openai.com/research/chatgpt)
- Hogeschool Arnhem en Nijmegen. (z.d.). AIM Controlekaart. Hogeschool Arnhem en Nijmegen. Geraadpleegd op 29 september 2023, van [https://han.onderwijsonline.nl/elearning/content/oNkklGNj](https://han.onderwijsonline.nl/elearning/content/oNkklGNj)
- Niels, R. (2022a, 10 juni). Methods.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Methods](https://ictresearchmethods.nl/Methods)
- Niels, R. (2022b, 24 mei). Literature study.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Literature_study](https://ictresearchmethods.nl/Literature_study)
- Niels, R. (2018a, 9 februari). Community research.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Community_research](https://ictresearchmethods.nl/Community_research)
- Niels, R. (2018b, 9 februari). Problem analysis.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Problem_analysis](https://ictresearchmethods.nl/Problem_analysis)
- Niels, R. (2018c, 9 februari). Pitch.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Pitch](https://ictresearchmethods.nl/Pitch)
- Niels, R. (2018d, 9 februari). Prototyping.  ICT Research Method. Geraadpleegd op 29 september 2023, van [https://ictresearchmethods.nl/Prototyping](https://ictresearchmethods.nl/Prototyping)
- Bron per deelvraag...

> **NOTE**: **Bron titel cursief** & **bronvermelding**
