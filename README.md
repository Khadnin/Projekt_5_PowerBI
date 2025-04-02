# Projekt_5_PowerBI

## Účel
Vizuál PowerBI v tomto repozitáři je výcuc dat ohledně dopravních nehod v Brně mezi lety 2010-2023 včetně. Obsahuje jak časové údaje, tak místní/pozicové a jiné, jako jsou třeba přítomnost alkoholu/drog u řidiče, pneumatiky na vozidle či stav vozovky v době nehody.

### Obsah repozitáře
V repozitáři je přítomen pouze .pbix soubor, jelikož zdrojové soubory přesahují max povolenou velikost souborů na GitHubu.

### Zdrojová data
Pro vytvoření tohoto vizuálu byly použita následující zdrojová data (veškerá data jsou volně dostupná):
1. Data o dopravních nehodách v Brně jsou dostupná zde: ```https://data.gov.cz/datov%C3%A1-sada?iri=https%3A%2F%2Fdata.gov.cz%2Fzdroj%2Fdatov%C3%A9-sady%2F44992785%2Ff7604237598371dd478232df3ad93ce9```
2. Součástí souboru v odkazu z bodu 1. jsou i souřadnice nehod v souřadnicové soustavě S-JTSK. Bohužel PowerBI neumí s touto soustavou pracovat a tak jsou data převedena na WGS84 souřadnicový systém (GPS) - převod není součástí tohoto repozitáře.
3. Geografická data potřebná pro vytvoření kartogramu jsou na tomto odkazu (GeoJSON - WGS84): ```https://gis.brno.cz/ost/edas/public/0e477a82-0566-45f1-a10b-c1cad0d76474```
