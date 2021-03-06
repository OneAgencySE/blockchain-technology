# Blockchain Technology

Kod och förberedelser för DFK-kursen "Blockchain Technology".

http://www.dfkompetens.se/utbildning/blockchain-technology

## Intro

Det här GitHub-repot är till för att deltagare som går Dataföreningen Kompetens kurs i __Blockchain Technology__ enklare
ska kunna komma igång. Det innehåller instruktioner för vad som behöver installeras och förberedas för att komma igång
fortare vid själva kurstillfället.

## Föreberedelser innan kursstart

### Installera Visual Studio

Ladda ner och installera lämplig variant från https://www.visualstudio.com/vs/community/

### Installera BitCoin Core

BitCoin Core finns att ladda ner på https://bitcoin.org/sv/ladda-ner.
* Installera och starta BitCoin Core enligt standard.
* Välj en katalog som är lätt att nå. I våra exempel har vi använd oss av _&lt;desktop&gt;/BitCoinCore_.
* Stäng av direkt.
* Starta med _scripts/bcc-start.sh_ (Mac) eller _scripts/bcc-start.ps1_ (Win). Detta startar BitCoin Core mot ett testnätverk. Det kommer att
  ta ca 1-2 timmar att initera första gången.

## Exempelprojekt

Repot innehåller ett Visual Studio-projekt, _BitCoin.sln_, som är en tom Console App. Denna har referenser till två nugets (NBitCoin och QBitNinja) 
som kommer att användas när vi kodar.