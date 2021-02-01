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