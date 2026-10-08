# Kernekompetencer i 2030: fra WEF til Zealands strategiske indsatser

Interaktiv figur, der lægger fire perspektiver på kernekompetencer i 2030 oven på hinanden:

1. **World Economic Forum skills.** WEF, *The Future of Jobs Report 2025*, figur 3.6 «Core skills in 2030».
2. **Kompetencer som efterlyses i DK/EU.** Tilføjelser og flytninger baseret på danske, nordiske og europæiske kilder (DigComp 3.0, AI Act art. 4, Union of Skills, Eurobarometer, ENISA, Digitaliseringsstyrelsen, Danmarks Statistik, PwC, Klimarådet, Kompetansebehovsutvalget, Arbetsmarknadens AI-råd m.fl.).
3. **Diskuterede kompetencer, Zealand Videndag 2026.** Workshoppens egne kompetencer og placeringer.
4. **Officielle strategiske indsatser på Zealand (under udvikling).** Redigerbart lag. Indsatser gemmes kun i den enkelte brugers browser og kan sendes som mail eller eksporteres som JSON.

Figuren bygger på anerkendte offentlige kilder, som kan sammenholdes med diskussionerne på Zealands workshop.

## Indhold

| Fil | Beskrivelse |
|---|---|
| `index.html` | Selve figuren. Én selvstændig fil, ingen build. |
| `data/videndag-2026.json` | Videndagens kompetencer og placeringer. Kan importeres i trin 4. |
| `docs/sammenligning-wef-dk-eu.md` | Arbejdsnotat med sammenligningen af WEF og danske, nordiske og europæiske kilder. |

## Metode og forbehold

- WEF-placeringerne er aflæst fra figur 3.6 og afrundet (ca. ±2 procentpoint). Fire værdier er afstemt med tal i rapportens tekst. Eksakte værdier findes i WEF's [Data Explorer](https://www.weforum.org/publications/the-future-of-jobs-report-2025/data-explorer/).
- Placeringerne i trin 2 er kvalitative vurderinger baseret på kilderne, ikke surveydata.
- Placeringerne i trin 3 er omtrentlige. De blev sat hurtigt på workshoppen og er lidt tilfældige, så de bør læses som kvadrant, ikke som præcise procenter. Først i trin 4 placeres indsatserne præcist. Navne på bidragydere er udeladt.
- Stabile-kvadranten er tom på Videndagen: ingen kompetencer blev vurderet som kerne i dag uden at vokse.

## Kilde

World Economic Forum. (2025). *The Future of Jobs Report 2025* (Figur 3.6: Core skills in 2030). https://www.weforum.org/publications/the-future-of-jobs-report-2025/in-full/3-skills-outlook/

Grafisk forlæg: Adam Danyal og Julia Danyal, AIForLeaders.com.

Interaktiv version: Andras Ács Pedersen, Zealand, 2026.
