---
layout: post
title:  Utveckling
date:   2016-04-08 14:16:42
categories: jekyll update
phase: produktion
sort-index: 1
tags: [Tech, QA]
owner: Pär Stigenberg
---
Under utvecklingen omsätter vi arkitektur, funktionella och ickefunktionella krav till en fungerande tenkisk lösning. Creuna har samma angreppssätt när vi utvecklar enskilda applikationer som vi har för arkitektur, d.v.s. vi lägger stor vikt vid att bygga modulära appilkationer som snabbt kan anpassas till förändrade krav och behov. Att dela in lösningen i mindre enheter har många fördelar, en av dem är att arbetet med kvalitetssäkring blir mycket mer effektivt. Varje del kan testas separat och utvecklare på Creuna arbetar med att skriva enhets- och integrationstester som testar avgränsade delar samt hur olika funktioner fungerar tillsammans. De tester som utvecklarna implementerar enligt vår test-drivna utvecklingsmetodik körs varje gång en utvecklare uppdaterar eller lägger till funktionalitet i lösningen och utvecklaren får direkt feedback på om något gått fel.

Utöver enhets- och integrationstesterna genomförs även manuella tester, både av utvecklarna själva, av testledare men också av andra kompetenser inom teamet. Vilka verifieringar som ska genomföras definieras i den definition-of-done (DOD) som tas fram för projektet.

![Utvecklingsprocess](http://localhost:4000/assets/utveckling_1.png)

När en funktion är testad, godkänd och lanserad är det viktigt att övervaka att applikationen fungerar som avsett. För att säkerställa detta arbetar Creuna med olika tjänster för applikationsövervakning som t.ex. New Relic m.fl. Denna övervakning gör att vi snabbt upptäcker om en förändring skapat nya problem.

Creuna har utvecklingsprocesser och verktyg för att kunna arbeta iterativt och kontinuerligt göra releaser till test-, stage- och produktionsmiljöer. Release-processerna är automatiserade vilket gör arbetet effektivare och det minimerar även risken för manuella misstag. Bilden nedan visar en översikt över Creunas tekniska miljöer samt flöden till test-, stage- och produktionsmiljöer.

![Utvecklingsprocess](http://localhost:4000/assets/utveckling_2.png)

Testmiljön på Creuna uppdateras löpande med den senaste funktionaliteten och våra kunder har alltid möjlighet att följa utvecklingsarbetet på denna server. De automatiserade releaseprocesserna används också för att uppdatera våra kunders stage- och ibland också produktionsmiljöer och det är möjligt att sätta upp processerna så att releaser kan göras utan nertid.

Creunas kunder har även möjlighet att få åtkomst till ärende- pch projektstyrningsverktyget Jira där man kan arbeta med lösningens roadmap/backlog samt följa pågående utveckling. Jira används också för rapportering och uppföljning av fel och ändringar.

Annan läsning
-------------

[Tech WIKI på Redmine]

[Tech WIKI på Redmine]: https://redmine.creuna.se/projects/creunatechnology/wiki

