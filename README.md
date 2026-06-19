# Dokumentation slutprojekt 8.1
Slutprojekt Webbutveckling 1, en webbplats om S*Palbäcks sibiriska katter. 

# Syfte och målgrupp
Syftet med webbplatsen är att vara ett skyltfönster för min och min frus eventuella framtida kattuppfödning. Målgruppen är köpare och uppfödare av sibiriska katter. 

# UI skisser och ev. mockup
Planen från början var att ha ett bildspel som loopade, enligt tidigare övning i denna kurs. Dock har vi endast tre katter i hushållet och jag kände då att det inte riktigt var den bästa lösningen. 

Jag valde då i stället att använda CSS Grid för kattgalleriet eftersom det gör det enklare att få till en snygg layout även för mobilen. 

Till min webbplats har jag återanvänt väldigt mycket som vi har arbetat med under kursen. Det jag däremot tycker om med webbplatsen är att den har flera olika ändamål rent designmässigt. Detta då till exempel en personlig tränare, mindre veterinärklinik eller annat mindre företag skulle kunna använda grunddesignen. 

Den kan också användas av andra uppfödare, eftersom det är huvudtemat för designen. Det som är bra är att HTML:en och CSS:en är logiskt uppbyggd som gör att bakgrundsfärger, header/footer mm enkelt kan anpassas utifrån beställarens behov. 

# Så här uppfyller min webbplats GDPRs kriterier
I nuläget finns det ingenting i min webbplats som strider mot dataskyddsförordningen eftersom jag inte har några analysverktyg, inbäddade filmer från Youtube eller liknande. 

Däremot skulle det rimligtvis finnas ett kontaktformulär på kontakta oss-sidan. Då blir det annorlunda eftersom användaren skulle fylla i namn, e-postadress och sitt meddelande.

I närhet till formuläret skulle då en informationstext, liknande: 
”När du skickar ett meddelande till oss behandlas dina personuppgifter som du lämnar ut. Detta för att kunna besvara din fråga. Uppgifterna sparas inte längre än nödvändigt.” 

Det skulle även gå att lägga till en kryssruta ”Jag har tagit del av informationen om hur mina personuppgifter behandlas”. 
Det är också därför jag har valt att lägga till en integritetspolicy i footern, så det finns möjlighet att koppla på en undersida som beskriver hur personuppgifterna behandlas och vilka kontaktvägar som finns vid behov.

# Tester och testresultat
Grunden var väldigt enkel att bygga då jag kopierat tidigare delar som vi arbetat med under kursen. Det som varit tog lite tid var att få till är snygga övergångar när man hovrar över ett kort i kattgalleriet. Även header/footer var lite krånglig och blev ärligt talat ganska ful initialt för mobilen.

Då min grund varit enkelt uppbyggd räckte det med att lägga till flex direction och align-items/text-align på några ställen under @media i HTML:en så blev det betydligt snyggare i mobilen. 

Några saker som jag experimenterat med under projektets gång är användarvänligheten. Då jag i dagsläget arbetar som webbredaktör har jag försökt att koppla på funktioner som gör webbplatsen logisk, till exempel länkar i header/footer, inklusive att komma tillbaka till startsidan via logotypen, samt understruken text som visar vilken sida besökaren är på. 

# Analys av webbprojektet efter färdigställande
Jag tycker att webbplatsen fyller sitt syfte väl. Det är sällan man visar upp alla katter (inklusive kastrater alltså) på en sådan här typ av webbplats, men i mitt fall har jag experimenterat med en väldig enkel, men samtidigt otroligt användbar design för dessa sammanhang. Till exempel kan kattungar till salu eller liknande användas istället om man inte vill visa upp alla katter i hemmet. 

När det kommer till användarvänlighet och tillgänglighet så finns det alltid med i bakhuvudet för min del. Det svåra för mig är istället att tänka vilken teknisk lösning som är den bästa. Genom att testa olika sätt att få CSS:en att lira tillsammans med HTML:en så tycker jag att jag kommit fram till ett bra resultat utifrån syftet. 

Jag tycker dock att det är betydligt lättare att tänka HTML än CSS, och jag har verkligen fått utmana mig själv genom att testa olika tekniker för att få webbplatsen presenterad på det sätt som jag fick upp i skissandet. 

Det jag gillar med border-box är att storlekarna blir väldigt förutsägbara i kombination med att jag försökt hålla HTML:en enkel och förutsägbar i form av att märka upp innehållet i olika klasser som gjort det enklare att styra respektive del. 
Annat som varit svårt för mig har varit att tänka funktioner i CSS:en på engelska, men när det väl började sätta sig blev det lättare att våga experimentera sig fram. Detta syns bland annat i .kattkort-hover där jag lagt till en transform. 


