# Portfolio Minor Data Science

Manon Rongen,
19075235,
groep 1

## 1. Inleiding
### 1.1 Inhoud*

### 1.2 Project Foodboost*
<details>
  <summary>Inleiding project</summary>
  Tijdens dit project hebben we ons bezig gehouden met voeding en het zoeken naar een gebalanceerd dieet met behulp van Data Science. Zelf goede recepten vinden om een dieet mee vol te houden is moeilijk en als je een app gebruikt wil je wel dat deze rekening kan houden met jouw persoonlijke voorkeuren, allergiën en dergelijke. Het is mogelijk met Data Science op basis van data te voorspellen of iemand een recept lekker vindt en samen met technieken als Lineair Programmeren is het misschien mogelijk een optimale weekplanning van recepten te maken, die rekening houdt met alle eisen (van het dieet, voor genoeg variatie + andere restricties).
</details>

<details>
  <summary>Verloop project*</summary>
  In [dit document]() is uitgelegd hoe het project is verlopen en wat in het kort de stappen waren die we hebben genomen en wat het eindresultaat is.
</details>

### 1.3 Project Cofano*
<details>
  <summary>Inleiding project</summary>
  Dit project gaat over het optimaliseren van de processen bij containerterminals. Als schepen lang aan de kade liggen voor het in en uitladen van containers kost dit meer geld en dus wil het bedrijf Cofano dit zo snel mogelijk doen. Zij willen dat het vinden van een optimale aanpak geautomatiseerd wordt. Daar gaan wij ons mee bezig houden.
</details>

<details>
  <summary>Verloop project*</summary>
  Wij hebben de 2 laatste periodes aan dit project gewerkt (8 weken).
  Toen wij startten besloten we maar een klein deel van het probleem aan te pakken. Namelijk de indeling op de kade, zonder rekening te houden met de volgorde van de containers die binnen komen. We maken de indeling dus zo, dat deze optimaal is voor schepen die ze op komen halen. Tijdens de eerste presentatie van dit project had ik (want ik zou presenteren) geprobeerd ons doel te verwoorden: "Het vinden van een indeling van containers in de terminal, zo dat de tijd dat de zeevaartschepen aan de kade liggen minimaal is." Zo zijn we later met de hele groep tot de volgende onderzoeksvraag gekomen: "...?"
   ...
</details>


## 2. Kennis en Literatuur
In dit hoofdstuk laat ik zien hoe ik me verdiept heb in onderwerpen die te maken hadden met het project en Data Science.

### 2.1 Foodboost*
<details>
  <summary>Minor Data Science</summary>
    In deze eerste periode van de minor heb ik gewerkt aan DataCamp Courses, ben ik bij de Lectures over Data Science aanwezig geweest en heb ik in NoteBooks geexpirimenteerd met het maken van Simpele Modellen. Zo ben ik me gaan verdiepen in Data Science en heb ik ook veel geleerd over Classification modellen, wat hetgene is dat we voor dit project nodig zouden hebben.
</details>

### 2.2 Cofano
<details>
  <summary>Literatuuronderzoek CSP*</summary>  
  In de eerste week heb ik Literatuuronderzoek gedaan en best wat papers gelezen over Het Container Stacking Problem, want ik kwam er achter dat dit redelijk leek op het probleem waar wij mee bezig zijn. Het gaat daar ook om terminalprocessen optimaliseren, zo dat schepen niet lang aan de kade hoeven te wachten. Er zijn veel verschillende kanten van dit probleem en ik heb meerdere papers gelezen die net anders het probleem aanpakte. Ik heb in [dit](link) document een samenvattingetje voor mezelf gemaakt van papers die ik nuttig vond (papers die ik minder relvant vond heb ik maar heel kort omschreven).
  Dit zijn de Linkjes naar de artikelen die ik in het document omschrijf:
  [1](link)
  [2](link)
  ...
</details>

<details>
  <summary>Verdiepen in RL</summary>
    We hadden bij andere groepen al gehoord dat zij Reinforcement Learning (RL) gebruikte toen wij begonnen aan het project. Jeroen had ons tijdens een van de eerste gesprekken ook RL uitgelegd en verteld waarom het handig was dit te gebruiken.
  
  We bestudeerde [snake](https://github.com/grantsrb/Gym-Snake) voorbeelden. Joeri en ik namen grondig dit [taxi](https://www.learndatasci.com/tutorials/reinforcement-q-learning-scratch-python-openai-gym/) voorbeeld (alleen de code is [hier](https://casey-barr.github.io/open-ai-taxi-problem/) te vinden) door om goed te begrijpen hoe RL stap voor stap werkt. Dit heeft me erg geholpen met het begrijpen van RL.
</details>

<details>
  <summary>Environment maken</summary>
  Tijdens het onderzoek doen naar RL modellen, kwamen we vaak gym environments tegen (bijvoorbeeld bij het snake en taxi voorbeeld). Ook andere groepen waren hiermee aan de slag gegaan en zeiden dat het goed te gebruiken was voor dit probleem.
  
  Met de volgende video heb ik geleerd hoe ik een eigen environment moet bouwen: [video](https://www.youtube.com/watch?v=Mut_u40Sqz4). Ik heb het derde project uit deze video mee gedaan en stap voor stap geprobeerd te begrijpen wat er precies gebeurd. Dat voorbeeld is te zien in dit [Notebook](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/Voorbeeld%20Environment%20Douche%20Video.ipynb) en mijn [aantekeningen](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/environment%20douche%20-%20video.pdf).
  
  Vervolgens gingen we allemaal aan de slag met het maken van een environment met ons probleem. Ik heb toen Jesse uit de andere groep gevraagd om ons een keer te helpen en die heeft toen nog wat tips gegeven, waarmee ik tot [deze environment code](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/P_simple_ENV_3x3grid.ipynb) voor een 3 bij 3 grid kwam. Later is dit nog wat uitgebreid en veel verbeterd (zoals veel uitgebreidere reward en het meegeven van de volgende container die geplaatst gaat worden aan het model), maar het werkte nu wel om een grid in te vullen zonder dubbel plaatsingen.
</details>


## 3. Notebooks
In dit hoofdstuk laat ik zien wat ik gedaan heb op het gebied van data preprocessing en predictive analyses, aan de hand van een paar notebooks die ik gedurende de twee projecten gemaakt heb.

### 3.1 Foodboost*
  - [Data preprocessing](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/Data%20voorbereiden%20klein%20classificatie%20model%20Foodboost.ipynb)
  - [Ingrediënten groeperen*](link)
  - [Lineaire Regressie](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/LinaireRegressie%20Nutritions%20Foodboost.ipynb)
  - [Classificatie model(s)](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/Classifier%20Tomaat%20Foodboost.ipynb)

### 3.2 Cofano*
  - [3x3 yard model](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/P_Env_RL_3x3_snellersimpeler_optimaal.ipynb)
  - [2x2x2 yard model](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/P_Env_RL_2x2x2_optimaal.ipynb)


## 4. Presentaties
<details>
  <summary>Mijn rol</summary>
    Op het gebied van presenteren heb ik een grote rol gespeeld. Ik nam initiatief de eerste presentatie te doen en heb daarin eigenlijk gedurende beide projecten grotendeels de leiding genomen. Ik maakte vaak de powerpoint aan en zorgde dat er taken verdeeld werden en dat we altijd iets lieten zien. Ik heb bijna alle interne presentaties gepresenteerd en ook een van de externe presentaties met joeri op me genomen.
</details>

### 4.1 Mijn presentaties
Hieronder een paar van de slides die ik gepresenteerd heb. Ik heb niet alles erin gezet, maar stukken van de presentaties die ik gepresenteerd heb.

**Foodboost**:
  - [interne presentatie](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/FOODBOOST%2017-10-2022%20intern%20pres.pdf)

**Cofano**:
  - [interne presentatie](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/pres1%20week2%20-%20Containers%20groep%201.pdf)
  - [interne presentatie](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/pres4%20week8%20-%20Containers%20groep%201.pdf)
  - [externe presentatie](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/week4%20EXTERN%20van%20Containers%20presentatie%20groep%201.pdf) met [tekst](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/manon%20-%20tekst%20externe%20presentatie%201.pdf)


## 5. Paper Cofano*
<details>
  <summary>Mijn rol</summary>
  Tijdens het werken aan paper heb ik mij erg ingezet en veel input geleverd. Ik heb ervoor gezorgd, samen met joeri die ook veel initiatief nam in het organiseren, dat er duidelijke afspraken kwamen, ben bij alle werksessies volle tijd aanwezig geweest en heb mijn taken netjes op tijd afgerond. Joeri en ik hadden 9 januari samen een opzet geschreven voor het paper en die vervolgens met de groep besproken, zodat we op tijd (14 januari) feedback konden vragen van Tony. Hij heeft ons toen geholpen met het afmaken van de opzet en we hebben taken verdeeld voor de eerste stukken van het paper: Introductie zou ik doen, Onderzoeksopzet deden Hidde en Joeri, Bonno begon met de resultaten en Mohamed en Micheal gingen wat stukjes over hun eigen onderdelen schrijven. Na de vakantie zouden we samen aan de andere stukken schrijven. Ik heb toen, naast de introductie verbeteren en afmaken, gewerkt aan de conclusie en sommige aanbevelingen samen met de rest. Daarnaast heb ik het paper in meerdere fases grondig doorgelezen en veel opmerkingen geplaatst.
</details>

<details>
  <summary>Introductie</summary>
  Hieronder is de introductie te lezen die uiteindelijk in het paper is gekomen.
</details>

[Introductie door Manon](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/Introductie%20eindversie.pdf)

<details>
  <summary>Bijdrage andere stukken</summary>
  Ik had in steekwoorden wat over de Conclusie en Discussie geschreven, voordat anderen dit gingen uittypen en we samen de conclusie afgemaakt hebben. Daarnaast heb ik stukjes in de aanbevelingen geschreven (over de schaalbaarheid en rewardfunctie). In het document hieronder staan de steekwoorden en daarna de stukken zoals ze in het paper zijn gekomen.
</details>

[Conclusie en Discussie steekwoorden + eindresultaat](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/paper%20steekwoorden%20Conclusie%20en%20Discussie%20(1).pdf)

## 6. DataCamp
Ik heb ongeveer 94% van de [DataCamp Courses](https://github.com/ManonRongen/Portfolio-Minor-Data-Science/blob/main/DataCamp%20voltooid%20schermafbeelding.pdf) afgerond.

