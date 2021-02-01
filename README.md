# bem-opgave-bootcamp
Henriks bem-opgave

Opgave:

Lav et markdown (md) dokument på din Github.

Og skriv hvad der tales/beskrives på følgende tidspunkter i videoen:

(emnet startes ved tiden og varer x-antal minutter)

03.50 - 05.20 - 06.30 - 08.57 - 19.05 - 20.50 - 22.06 - 24.20

Og afslutningsvis skal du nu med egne ord skrive lidt om hvad du fik ud af videoen.


# 03.50:
Decoupling - Adskille objekter så de ikke sidder for tæt sammen, og dermed ikke påvirker hinanden for meget.
Single responsibility principal - Man beskriver i classenavnet, hvad objektets funktion er.
Seperation of concerns - Det skal være tydeligt, hvad gør hvad. Hvert objekt skal gøre så få ting som muligt.

# 05.20:
Encapsulation - Man skal i teorien kunne tage koden ud og bruge den i andre projekter. Det skal være genbrugeligt og ikke være afhængig af andre elementer i koden. Det er simpelt og gør én ting.
OOCSS - Object Orientet CSS.  

# 06.30:
Identificér objekter (modules) og de mønstre de er i, og genbrug dem. Gentagne møsntre er en module.

# 08.57:
Scalable and Modular Architecture for CSS: et system til at organisere kode. 5 kategorier/niveauer:
- Base: Gælder HTML. Ingen classes eller id'er.
- Layout: De store dele af hjemmesiden, som du lægger mærke til. Header, sidebar etc.
- Module: De gentagne mønstre. Teoretisk kunne de sidde i layout.
- State: Hvor du tager et module ændre ved dens funtion gennem JavaScript. Kunne være et mail icon, som får et rødt mærke, som indikerer en ulæst  besked. Ændret midlertidigt.
- Theme eller Shame: Ikke påkrævet, men hvis forskellige temaer (kunne være farve) er nødvendige. Shame bruges til alle de gange, hvor de satte regler ikke er blevet brugt. Kan være en Shame-sektion nederst i stylesheetet med ting, som ikke passer reglerne eller ikke kunne passe grundet tid eller andet. 

Basal navngivning:
- .{Block}__{Element}
- .{Block}__{Element}--{Modifier}
- .{Block}--{Modifier}

# 19.05:
Jo mere specifikt reglerne er defineret, jo større er chancen for at de bliver taget i brug.

# 20.50 & 22.06:
Hvis du har brug for at lave lange classnames til et objekt, er det en meget bedre mulighed, end at gøre styles mere specifikke. Brug ALDRIG id'er til styles! Kun til JavaScript! Man kan ikke override et id.

# 24.20:
Flat selectors (et enkelt classname på et objekt) er meget bedre, da det er simpelt. Hvis man holder sig til det, behøver man ikke at bekymre sig om at være specifik. Et niveau for specifikation.

Sidste kommentar: .classname{@extend .pull-left .col-md-6}. Her påtager .classname sig styles fra de andre klasser med @extend.

# Hvad fik jeg ud af opgaven?
Jeg fik en bedre forståelse for god navngivning. Min opfattelse af, hvad der er good practice er blevet bedre, men det er en måde at arbejde med CSS på, som jeg lige skal vende mig lidt til. Jeg tror jeg forstår det, men jeg skal lige ind i rutinen.