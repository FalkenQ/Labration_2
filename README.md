# Webbplatsens Falkens

Denna webbplats handlar kort om mig och vilka intressen jag har. Den visar några av mina resor och vad jag gjort under resorna.

## Om webbplatsen

Webbplatsen består av tre sidor, hem, hobby och kontakt. Hemsidan har lite grundläggande information av vad du kan hitta på webbplatsen och hur du kontaktar mig.  
Hobby berättar lite kort om mina intressen, men berättar om mina resor. Sidan har en tabell där besökare kan se var jag har varit och vad jag har gjort på platserna jag utforskat.  
Kontaktsidan har en mail direkt till mig ifall besökaren skulle vilja komma i kontakt direkt med mig. Sen finns det även ett formulär man kan fylla i för att ställa mer generella frågor.  

## Tekniker

- HTML

## Publicerade versioner

- [GitHub Pages](https://falkenq.github.io/Labration_2/index.html)
- [Netlify](https://astonishing-rolypoly-41a5a9.netlify.app/)

## Git

### Vad är skillnaden mellan git add och git commit?

git add lägger till ändringarna i staging area. git commit sparar ändringarna i staging area som en commit i historik loggen.

### Varför använder man branches istället för att jobba direkt i main?

Att jobba i branchen underlättar för personen som vill testa ny kod utan att påverka huvudkoden. För att vid ett senare tillfället kunna mergea koden till main efter att man testat att koden fungerar som den ska.

### Vad händer rent praktiskt när man gör en merge?

En merge lägger ihop två historiker/ändringar som gjorts i en branch till en annan, tex dev till main.

### Vad är skillnaden mellan att pusha till GitHub och att publicera direkt på Netlify?

Skillnaden är att Netlify är en webbhosting och Github är en lagringsplats för dina koder. På Github kan du spara kod, samarbeta och organisera kod. Medan Netlify tar din kod och omvandlar den till en färdig webbplats.

### Hur exkluderar man en fil från versionshanteringen?

För att exkludera en fil gör man en `.gitignore.` Du kan exkludera en specifik fil med `filnamn.txt`, samt exkludera en mapp  med `filnamn/`, med mera.
