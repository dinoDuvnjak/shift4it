# 📘 KAKO GENERIRATI SINOPSISE - KORAK PO KORAK

## PREDUVJETI:
- Claude Desktop app ili claude.ai
- PDF prezentacija za dan koji generiraš
- Prompt template iz ovog foldera

## KORAK 1: PRIPREMA
1. Otvori novi chat u Claudeu
2. Uploadaj PDF prezentaciju za dan koji želiš generirati
3. Uploadaj raspored predavanja (ako Claude nema context)

## KORAK 2: KORIŠTENJE PROMPTA
1. Otvori `01-PROMPT_TEMPLATE.md`
2. Kopiraj cijeli prompt
3. Zalijepi u Claude chat
4. Dodaj na kraju: "Kreiraj sinopsis za Dan X prema ovom PDF-u"

## KORAK 3: FINE-TUNING
Ako Claude nešto propusti ili trebaš korekciju:
- "Slajd X nema notes - provjeri ponovo"
- "Dodaj više backup aktivnosti"
- "Prevedi sve na hrvatski"

## KORAK 4: EXPORT
1. Claude će generirati kompletan MD
2. Copy-paste u VS Code
3. Spremi kao: `Dan_XX_Naziv.md`
4. Commitaj na GitHub

## SAVJETI:
- Provjeravaj brojeve slajdova - moraju biti točni!
- Ako Claude daje engleski tekst, podsjeti ga: "SVE na hrvatskom"
- Provjeravaj reference linkove - moraju raditi

## TROUBLESHOOTING:
Vidi: `04-TROUBLESHOOTING.md`