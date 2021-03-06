# AI_Eksamen


## Kort introduktion

Projektet har til formål at præsentere data i to eller flere Machine Learning algorithmer med fokus på et virkelig data. Med en vinkel på brug i den virkelig verden som et firma eller privat person eller noget ligende.

## Case
Jeg er et spil udviklings firma, som har fået til opgave at producere et spil, med højst mulig intægt. Spillets inden hold er irrelevent and spillets kvalitet er ikke vigtigt. Det eneste formål er at finde de parameter i et spil, der kan indsamle mig den højeste indtjening. Jeg vil gerne vide hvilke features jeg skal udsemig for at spillets anmeldese score kan sikre mig det største salg, ved hjælp af en linear reggresion.

Jeg skal vide hvilke parameter der skal til for at ramme den bedste Review Socre for at kunne hjælpe min linear reggresion. Det kan jeg beslutte mig ved brug af en Random Forest Classifier. 

Når jeg har fundet frem til spillets bedste score, udgivelseår, genre og antal spillere. Skal jeg udse mig den bedst muglige title til spillet ved hjælp af spillets genre. Problemet har jeg valgt at løse ved hjælp af Natural Beyers Therom med Natural Language Processing

## Mit Projekt
Jeg har valgt at tage udgangs punkt i en data omking video spil. Jeg har fundet et data sæt der sætter fokus på individuelle spils featuers, salg, spil længde, anmeldeses score m.m. for en dybere gennemgang af dataens documentation kan du klikke 

https://corgis-edu.github.io/corgis/csv/video_games/

De mest væsentlige data linjer jeg har arbejdet med er
- Metrics.Sales             - Spillets omsætning i mil. $  
- Metrics.Review Socre      - Spillets Anmeldese Score fra 0-100
- Metadata.Genres           - Spillets Genre
- Metadata.Publisher        - Spillets udgiver
- Features.Max Players      - Spillets antal af spillere
- Release.Year              - Spillets Udgivelses år              


Dataten er udarbejdet med udgangspunkt fra et andet datasæt

https://researchportal.port.ac.uk/portal/en/publications/what-makes-a-blockbuster-video-game(a6d848fe-38ae-4584-8c95-a0f735ec9b4c).html

Den sammensatte data (Den jeg har brugt) er ikke en proffesionel data samling, og er noget der kan afspejles i modellernes validerings score. Dog har det været tilstrækkeligt til at udarbejde funktionelle modeller.

Modellerne i denne opgave er:
- Linear Regression with multiple features
- Decission Trees with Random Forest Classifiers
- Natural Beyers Therom for Natural Language Processing


Moden er skrevet i .ipynb (Jupyter notebook) - Opgaven har vedlagt .PDF af notebook koden
