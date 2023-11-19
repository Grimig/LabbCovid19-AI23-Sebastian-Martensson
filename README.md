# LabbCovid19-AI23-Sebastian-Martensson
Assignment for course AI-12
### Laboration-Covid-19

Covid-19 pandemin har påverkat hela världen med många dödsfall som följd. Ett kraftfullt verktyg för att förstå hur viruset påverkar världen är att analysera och visualisera data för att förstå trender.

- Folkhälsomyndigheten har samlat in data kring nya fall, dödsfall med mera. Vi ska använda oss av följande dataset:
- Covid-19 bekräftade fall - refereras som "covid19" i texten nedan
- Statistik för vaccination mot covid-19 - refereras som "vaccin" i texten nedan


Uppgifter:
- Alla grafer ska exporteras till en undermapp som heter "Visualiseringar" i din mapp för labben.
- Exportera matplotlib/seaborn grafer i png-format och plotly grafer som html-filer.
- Ge relevant namn till dina filer så det blir lätt att referera till dem. Notera att du behöver ställa in bakgrundsfärg när du sparar matplotlib grafer, annars blir det transparent och svåra att läsa.

Uppgift 1 - Uppvärmning covid-19 data:
Börja med att manuellt läsa Excel-filerna och de olika bladen i varje dokument. Använd därefter Pandas för att läsa in bladet "Veckodata Riket" i covid19-filen.

- a) Gör initial dataanalys för att snabbt få en överblick över datasetet. Använd metoder som ex.info(), describe(), value_counts(), head(), columns, index för att snabbt få en överblick.

- b) Slå ihop kolumnerna "år" och "veckonummer" till en kolumn med namn "Vecka" med följande format: Vecka 2020v6, Vecka 2020v7, ..., Vecka 2022v41.
