# Inlämningsuppgift Planned Planthood

Uppgiften Planned Planthood gick ut på att bygga en komplett, responsiv webbsida utifrån färdiga designunderlag för mobil, tablet och desktop.

## Uppgiften

Arbetet gjordes med enbart HTML och CSS, med fokus på struktur, semantik och tillgänglighet.

Jag utgick från det givna GitHub-repot och använde de befintliga CSS-variablerna i style.css som grund för färger, typsnitt och spacing. Layouten byggdes upp så att den följer designen så nära som möjligt och anpassar sig mellan olika skärmstorlekar med hjälp av grid, flexbox och media queries.

Ett stort fokus i uppgiften låg på tillgänglighet (a11y). Jag har därför arbetat med semantisk HTML, tydlig struktur och korrekt användning av element som header, nav, main, section och article. Formulär, länkar och knappar är uppmärkta så att de fungerar för både tangentbordsnavigation och skärmläsare, och jag har testat sidan med tillgänglighetsverktyg som WAVE.

Koden är strukturerad för att vara lätt att läsa och underhålla, med genomtänkta klassnamn och uppdelning enligt CUBE-principer där det varit möjligt. Om jag har använt externa lösningar, som reset-CSS eller utility-klasser, har jag angett källa i kommentarerna.

Vissa delar av designen var frivilliga, till exempel mer avancerade hover-effekter, overlay-bilder och funktionalitet för hamburgarmenyn. Dessa har jag valt att implementera i den mån tiden tillät, med fokus på att behålla en tydlig och tillgänglig lösning.

Sammanfattningsvis har uppgiften handlat om att kombinera responsiv layout, tillgänglighet och ren kodstruktur i en realistisk frontend-uppgift, och att visa att jag förstår och kan motivera de tekniska val som gjorts.

## Hur jag arbetade och vad jag hade kunnat göra bättre

Jag hann inte med alla detaljer i designen, framför allt när det gäller spacing och vissa typografiska val som fet text, vilket gör att designen på några ställen inte är helt pixelperfekt. Medvetet valde jag dock att lägga mest fokus på grid, tillgänglighet och semantisk HTML, eftersom det är områden jag vill bli starkare i.

Ett område jag inte fick till fullt ut var formuläret. Jag lyckades inte göra inputfältet responsivt på ett bra sätt utan att använda fasta bredder i pixlar. Jag testade olika alternativ men hann inte fördjupa mig tillräckligt, och här hade jag gärna velat utforska lösningar som minmax(), clamp() eller andra mer flexibla CSS-tekniker. Vet inte om det hade fungerat, vet ni vad som hade fungerat här? Tar gärna feedback! 

Jag hann heller inte styla inputfältet vid focus, vilket hade varit en viktig förbättring både visuellt och ur tillgänglighetssynpunkt.

Jag använde i stor utsträckning de variabler som redan fanns i projektet istället för att skapa egna. Ibland passade de väldigt bra med designen, och ibland hade det varit bättre att komplettera med egna variabler. Samtidigt tyckte jag det var lärorikt att försöka anpassa mig till ett befintligt system istället för att jaga exakta pixlar.

I efterhand hade jag även gjort vissa textval annorlunda. Jag skrev till exempel navigationslänkar och andra texter direkt i versaler, men hade istället valt att använda CSS (text-transform: uppercase) för att behålla bättre tillgänglighet för skärmläsare.

När det gäller layoutval hade jag sannolikt förenklat vissa delar. Call-to-action-sektionerna med SVG (plantan och fröpåsen) hade troligen blivit både enklare och mer lättlästa i kod om jag använt flexbox istället för grid, särskilt eftersom layouten bara behövde ändras i ordning på mobil. Nu använde jag grid-areas och tycker kanske det blev lite onödigt komplext.

Slutligen är en tydlig förbättringspunkt att jag borde ha pushat oftare till GitHub. I vissa fall samlades många ändringar i samma commit, och det är något jag behöver bli bättre på för att få en tydligare historik och arbetsprocess.