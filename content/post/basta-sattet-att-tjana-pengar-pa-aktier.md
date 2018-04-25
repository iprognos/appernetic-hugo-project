---
type: "post"
draft: true
author: "author"
description: "description"
keywords: ["key", "words"]
topics: ["topic 1"]
tags: ["one", "two"]
---


![enter image description here][1]
# Bästa sättet att tjäna pengar på aktier
Aktier är en överlägsen sparform för att få pengarna att växa om man kan hitta rätt aktier och få avkastning på investeringen. Men aktieplacering är också mer riskfyllt än sparande på konto eller obligationer.
## Hur värderar jag risken?
Nobelpristagaren William Sharpe upptäckte ett samband  mellan avkastning och risk. Uppkallad efter honom kallas det för Sharpe kvoten, den visar på ett sätt att mäta risk genom att i formeln stoppa in avkastning, volatiliteten (svängningarna i portföljen) och den riskfria räntan:

Sharpe-kvoten = (Avkastningen – Riskfria räntan) / volatiliteten

## Vad är en bra riskkvot?
Formeln ger att en hög avkastning och låg svängning i portföljen ger en större Sharpe-kvot. Så ju högre Sharpe-kvot desto bättre. På kort sikt kan värdet svänga kraftigt men över tiden brukar de hamna på 0.2 - 0.6. 

Många fondförvaltare redovisar sharpe-kvoten såsom Morningstar, Avanza och Nordnet.

## Är det bara tur om man lyckas investera rätt?
Många menar på att det är ren slump som avgör om man lyckas investera i rätt aktier oavsett om man är en välutbildad fondförvaltare med resurser som superdatorer och stora analysavdelningar. Undersökningar har visat att ett endast 0.6% av stora fonder konsekvent slår indexet. 

Eugen Fama har visat genom empirisk forskning hur marknaden beter sig i verkligheten och den stödjer den effektiva marknadshypotesen (EMH) vilket innebär att det är mycket svårt att vinna över marknaden genom att använda information som marknaden redan känner till. Framförallt över längre tidsperioder som 5 - 10 år.

## Ekonomipristagare sågar svenskarnas fondsparande

Intervju med Eugene Fama
<iframe width="640" height="360" src="https://www.youtube.com/embed/Xzkpkr7jA3o" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen></iframe>


## Den mänskliga faktorn
Dessutom tycks den mänskliga faktorn spela in, vi fattar dåliga beslut om det handlar om komplex information som ska värderas och vi har som småsparare ett informationsunderläge då vi inte har tid att bevaka all information som behövs för att kunna göra bra beslut. 

Det är också lätt att ha övertro på sin egen förmåga om man har lyckats pricka rätt aktie tidigare. Ett av de vanligaste misstagen är att ha en alldeles för liten riskspridning i portföljen. 
  ![enter image description here][2]
## Är det en dålig idé att investera i aktier?
Är det med andra ord meningslöst och en för stor risk att aktivt handla med aktier själv? 
Bör man överlåta det till stora fonder med tid och  rätt resurser?
Det kan man tro. Jag har själv undersökt om det är möjligt att kunna tjäna pengar på aktier med den begränsade tid och resurser jag har. Min hypotes är att om man kan låta datorerna sköta aktieanalysen genom att samla in all information åt en och bestämma köp och säljlägen med hjälp av teknisk analys utan inblandning av den mänskliga faktorn så kan man bli minst lika bra som de största fonderna. 

## Teknisk analys med hjälp av datorn
Teknisk analys ,TA som jag använder för att bestämma köp och säljlägen skulle man kunna förklara som ett fönster vi kan titta in i för att se psykologin bakom marknadens handel och rörelser. Flertalet påstår att priset på en aktie är slumpvist satt. Det är inte helt sant. Flera forskningsrapporter menar att marknaden inte är helt slumpmässig men att slumpmässighet och kaos förekommer periodvis (flockbeteende och spekulation)  och att marknaden kan jämföras med ett vädersystem.
Artikel om komplexitet och kaos och implementering av forskning inom kaosteori på finansmarknaden:
https://www.r-bloggers.com/chaos-in-the-financial-markets/
The Heterogeneous Dynamics of Economic Complexity:
http://journals.plos.org/plosone/article?id=10.1371/journal.pone.0117174

## Djupinlärning av tekniska indikatorer
Genom att använda det senaste inom maskininlärning, djupinlärning och kombinera det med teknisk analys och låter programmet själv komma fram till de värden som bör användas för de tekniska indikatorerna och bedöma om aktien kommer att gå upp eller ned under en viss tidsperiod kan jag se att det är möjligt att komma fram till bra resultat.
Jag har använt en målindikator som summerar den övergripande tendensen över 10 dagar med en marginal för transaktionskostnader på 2.5%. 
I och med att indikatorn summerar för 10 dagar framåt så har man ingen information för de 10 senaste dagarna. Men om man låter en algoritm som använder sig av djupinlärning, lära sig målindikatorn och använda den för de 10 senaste dagarna kan man få en ganska bra träffsäkerhet. Förutom aktiens kurs använder jag flera tekniska indikatorer som algoritmen använder sig av för att lära sig målindikatorn. I diagrammet visas tre krurvor. Den översta är kursen för Nibe B under tre månader. Kurvan under visar målindikatorn som pendlar mellan 0, 1 och 2. 
0 när kursen är på sin lägsta nivå och 1 när den är på sin högsta nivå under en 10 dagarsperiod. 
Den nedersta kurvan visar hur ai-djupinlärningen har lärt sig målindikatorn för Nibe B under hela perioden. 
![enter image description here][3]

Jag har låtit algoritmen ta fram modeller för samtliga aktier på Stockholmsbörsen och presenterar dom i en tabell där förutsägelsen av algoritmen presenteras som en sannolikhet för uppgång i %. 
Om man nu kombinerar det med en momentumstrategi där man rangordnar aktierna efter ett genomsnitt på 1, 3 och 6 månaders förändringshastighet av priset så har man en bra strategi att följa.
Flera artiklar och undersökningar visar på att momentumstrategier fungerar:
Financial Times, The hard facts about momentum investing 2014:
https://www.ft.com/content/58852d80-d910-11e3-837f-00144feabdc0
Börslabbet: https://borslabbet.se/borslabbets-strategier/
Lunds universitet Profitability of momentum strategies on the nordic stock market 2006: http://lup.lub.lu.se/luur/download?func=downloadFile&recordOId=1348919&fileOId=2434583
Lappeenranta University of Technology, Performance of value and momentum strategies in the Swedish stock market 2016: https://www.doria.fi/bitstream/handle/10024/120274/VALMIS.pdf?sequence=2&isAllowed=y
![enter image description here][4]
Vi väljer  de 5 aktier som hade bästa rankningen i början på året och ser hur de har utvecklats fram till 2 mars.
Med en simulerad investering på 100000SEK i varje aktie, köps och säljs den baserat på sannolikheten för att uppgång är 100%, säljs om sannolikhet för uppgång är 0%. 
Den simulerade köpkursen är öppningskursen dagen efter prognosen.  
Då får vi följande avkastning
170589
196717
26128

Sensys Gatso Group,  0
Eolus Vind B, -2840
Hexatronic Group +2917
MedCap, 0
Nolato B +26051
En utveckling på +15.3% jämfört med OMX benchmarkindex som hamnar på -2.24%.
Jag gjorde egna köp på Avanza under perioden med information från simuleringen: 
MedCap köp den 7 feburari och sälj den 13 februari +7.8%.
Nolato B köp 2 januari, sälj 12 januari, köp 26 januari, sälj 30 januari. +1.9%.
Courtage är medräknade. Totalt +4.85%
![enter image description here][5]
![enter image description here][6]


  [1]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650158/board-marketing-strategy-6229-3_q1sbz2.jpg
  [2]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650131/analytics-colored-pencils-coloured-pencils-185576-2_vjltb3.jpg
  [3]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650334/image10_fuakuj.jpg
  [4]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650346/indikatornibe_au4y88.jpg
  [5]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650313/image3_ljgf1f.jpg
  [6]: http://res.cloudinary.com/dtnahfj7l/image/upload/v1524650320/image4_r9jyra.jpg
