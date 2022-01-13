Naam: Collin van Adrichem

Studentnummer: 17059259

Docentent: J. Vuurens, R. Vermeij en T. Andrioli

Probleem eigenaar: R. van der Slikke

Project: Wheels

# Portfolio Datascience
Dit is een individueel portfolio over mijn deelname in het project, mijn kunnen en wat ik geleerd heb tijdens deze minor.

## Introductie
Ik ben Collin van Adrichem, ik zit momenteel in het vierde jaar van elektrotechniek en heb afgelopen periode deelgenomen aan de minor applied datascience. Tijdens deze minor heb ik geleerd wat data is, verschillende manieren om data te verwerken en wat er allemaal mogelijk is met data. 
## Datacamp

<details>
  <summary>Klik om te openen</summary>
  
  Gedurende deze minor stond de programeertaal Phyton centraal. Om deze taal meer onder de knie te krijgen heeft iedereen tijdens de minor een online cursussen phyton coderen   gevolgd via Datacamp. Bij deze cursus stonden de volgende onderwerpen centraal: het omgaan met panda dataframes, het visualiseren van data, data preparation en het toepassen en valideren van verschillende machine learning modellen.
  
  Ik had redelijk wat moeite met deze cursussen phyton. Coderen is nooit mijn sterkste kant geweest toch vind ik het erg interresant en wil ik er graag beter in worden. Ondanks dat het mij wat extra tijd gekost heeft heb ik toch alle Datacamp cursussen af kunnen ronden. Door deze cursussen heb ik veel geleerd over werken met datasets en het implementeren van verschillende modellen als KNN, Decision Tree en RFC in phyton. Mijn bewijs van het afronden van mij cursussen is te vinden via deze link: [Datacamp](Datacamp/Datacamp_bewijs.JPG)
  
</details>

## Reflectie en evaluatie met STARR

### Op eigen deelname aan het project
<details>
  <summary>Klik om te openen</summary>
  
| | |
| :---:   | :-: |
| Situatie | During the minor I was part of the Wheels project group. This project was about how you can use IMU data to classify specific wheelchair basketball movements. |
| Taak | During the project I wanted to make a good contribution to my project team and didn't want to lack in work ethic. Furthermore, I wanted to learn about Applied Data Science and wanted to share my knowledge about specific subjects I learned from school to the rest of my project team. |
| Actie | In the project I started with learning the basics of machine learning through an online programming course named Datacamp. When this was finished I began with focussing on what the possibilities were with the given dataset and started with writing code to improve the given dataset. When this was done is started to dive into predictive models like neural networks through research and trial and error, to understand how it all worked and how I could be implemented into my project. In between all of this I gave internal and external presentations to the class and external people|
| Resultaat | I finished the online programming course Datacamp and wrote code that worked well to fix a few issues that we had with the dataset like cleaning and finding more ground truths. After that I finished multiple Neural Network models like a 1D Convolution Neural Network and a Recurrent Neural Network with LSTM that were heavily used during the project. In these models and models of my teammates I implemented many features that helped me and my teammates to have better results on our models, a few examples are data loaders, data cleaners and validation programs. I also helped my teammates with coding their parts so that they wouldn’t be stuck on problems. Furthermore, I wrote parts of the Research paper that I knew most off and kept the whole class updated on my project through internal and external presentations. Also, I gave a learning lab to the whole class about the importance of data preparation of sensor data and how you could implement it. |
| Reflectie| My coding contribution to this project was good. I did a lot of the coding for my project and helped my teammates with coding when it was needed. For the research paper I had a good but not excellent contribution, I wrote what in needed to write and I reviewed everybody’s work but I did just as much work as my teammates. I gave a lot of presentations during the project, and I kept the class updated about my project, I also gave a learning lab about data preparation for sensor data. This was a great contribution to the project, the whole class and my own learning experience.|
  
</details>

### Op eigen leerdoelen
<details>
  <summary>Klik om te openen</summary>
  
</details>

### Op de project groep als een geheel
<details>
  <summary>Klik om te openen</summary>
  
</details>

## Project onderzoek


<details>
  <summary>Klik om te openen</summary>
  
  
### Defenitie van opdracht
  
Fitness trackers en health apps worden steeds populairder onder de sporters. Iedere dag je hoeveelheid stappen bijhouden of kijken hoeveel calorieën je hebt verbrand tijdens een workout. Deze trackers worden veel al gebruikt bij hardlopen en wielrennen, maar ook bij sporten als rugby, voetbal en hockey. Bij al deze sporten geeft de tracker een duidelijk beeld over de prestaties van de gebruiker. Helaas zijn bijna alle trackers gemaakt voor non rolstoel gebruikers. Aangezien ze bijna allemaal gebaseerd zijn op het tellen van stappen. Maar zoals een rolstoel athleet in een onderzoek zei "But, I don't take steps". Misschien bied het gebruik van IMU sensors in combinatie met machinelearning een uitkomst voor hun. Dit is exact waar ons project zich op focust

Voor ons project zullen wij ons gaan focussen op het detecteren van bewegingen in rolstoelbasketbal met behulp van IMU opnames. Om voor ons zelf een duidelijk beeld te schetsen waar wij heen willen met dit project, hebben wij een plan van aanpak geschreven. Zie [Plan van Aanpak](Documentatie/Planofapproach.pdf). Hierin heb ik onderandere de onderzoeks vraag met deelvragen bedacht en opgesteld. Deze luiden als volgt:

- How can IMU data be used to identify wheelchair basketball-specific movements?
    - Which form of data processing will be used?
    - Which specific movements can be detected?
    - Which sensor data is used for each movement?
    - Can movements be used to predict fatigue?
    - Can movements be used to detect overload? These sub question will help us to get an answer to the main research question.

### Evaluatie

  In de loop van het project kwamen we er toch achter dat we niet genoeg tijd zouden hebben om alle subquestions te kunnen beantwoorden. Daarom hebben we besloten om de onderzoeksvraag en deelvragen aan te passen voor de research paper. Dit resulteerde in de volgende onderzoeks- en deel vragen:
  
- Can an RFC and a RNN be used to classify sprints in partially defined IMU recordings?
    - Which form of data processing will be used?
    - Which sensor data is used to detect a sprint?

  Deze vragen worden duidelijk beantwoord in onze [research paper](Documentatie/Research_Paper_Project_Wheels_V1.pdf). Maar dit is maar een deel van wat er allemaal mogelijk is met machine learning in combinatie met IMU sensor data. Ons onderzoek is compleet gefocust geweest op het detecteren van sprints, maar ons machine learning model zou ook andere eenvoudige bewegingen als rotaties en botsingen kunnen detecteren. Maar voor dit mogelijk is, zal net als bij de sprints, de data set uitgebreid moeten worden met meer positive data punten van deze bewegingen. Wanneer ook deze bewegingen gedetecteerd kunnen worden is het zelfs mogelijk om deze te combineren om complexere bewegingen in het spel te vinden. Zoals bijvoorbeeld de combinatie van rotaties en sprints om te bepalen of er aangevallen of verdedigd wordt. Maar dingen als vermoeitheid of uitputting kunnen voorspeld worden aan de hand van de afname van de hoeveelheid sprints en de afname in sprint topsnelheid. Dit kan trainers en coaches helpen bij het zien wanneer een speler gewisseld moet worden.
  
  Naast dieper in de sport wereld gaan met deze techniek van beweging detectie, kan het ook gebruikt worden op medisch gebied. Door de dagelijkse beweging van een patient in een rolstoel bij te houden, kan de gezondheid en het herstel van deze patient bijgehouden worden. Zo zijn er meerdere doeleinde waarin dit onderzoek als goede basis kan dienen. Wij hopen dan ook als project groep, dat iemand het stokje van ons overneemt en door gaat met een van deze ideeën.
  
  ### Conclusies
  
  TIjdens dit project is er onderzoek gedaan naar hoe machinelearning sprints kan detecteren uit deels gedefinieerde IMU sensor data. Tijdens dit onderzoek zijn meerdere modellen gebouwd, toegepast en getest. Na het testen van alle modellen bleek dat de RFC en de RNN het best gebruikt kunnen worden bij het classificeren van sprints. Tijdens dit project bleek dat de deels gedefinieerde sensor data wel voor wat problemen zorgde. Deze dataset is dan ook uitgebreid met meer positieve datapunten toe tevoegen. Deze datapunten zijn gevonden door de false positives van de RNN en de RFC te vergelijken met elkaar en met de video om er achter te komen of deze eigenlijk true positives zijn. Met deze techniek is de dataset uitgebreid van maar 2.3% positieve datapunten voor sprints naar 17.1%. Door deze verbeterde dataset, kon het RFC model 90.4% van alle getagde sprints met een precisie van 89% detecteren in de train/valideer dataset [RFC speler A](Models/RandomForrestCLassifier_sprint_detection.ipynb). Om zeker te zijn dat het model werkte, is het model ook gevoed met een compleet onbekende test set [RFC speler B](Models/RandomForrestCLassifier_Player8.ipynb). Het RFC model kon sprints uit deze dataset detecteren met een precisie van 91.67%. De recall is onbekend aangezien deze dataset ongedefinieerd was(. Dit resultaat bewijst dat het mogelijk is om sprints te classificeren uit deels gedefinieerde IMU sensor data met een RFC en een RNN.
  
  ### Planning
  
  Tijdens het hele project is er gebruikt gemaakt van scrum in Azure devops, zie https://dev.azure.com/Wheeeeeeeeeeeeeeels/wheels/_boards/board/t/wheels%20Team/Stories_m_. Iedere dag werd de dag gestart om 9:30 met een stand-up meeting, hier werd besproken wat iedereen de dag er voor gedaan had, of er nog complicaties opgetreden waren en wat ze vandaag gaan doen. Dit zorgde er voor dat iedereen up to date was met waar de rest mee bezig was en gaf een makkelijk instap moment om om hulp te vragen als je ergens tegen aan liep. Gedurende het hele project werkte we met sprints van 2 weken. Aan het eind van deze twee weken hadden we een retrospective en plande we wat er de volgende sprint gedaan moest worden. Tijdens deze retrospective bespraken we wat we wilde behouden, waarmee we wilde stoppen en wat we wilde verbeteren in het process van ons project. Bij het plannen van de volgende sprint maakte we gezamelijk de userstories en gebruikte we "scrum poker" om samen te bepalen hoeveel werk iedere userstory is. Het besluit van het gebruiken van scrum poker is genomen nadat we het idee hadden dat niet iedereen even veel werk verrichte. Voor het plannen van de internal en external presentations hadden wij een rouleringssysteem waarbij iedereen minimaal 2 keer aan de beurt was.

  
</details>




## Predictive analytics
<details>
  <summary>Klik om te openen</summary>
  
  ### Model selecteren

  #### Decision Tree
  
  De verkregen datasets voor het project wheels bestond uit deels verwerkte IMU (Inertial Measurement Unit) data. Dit deels verwerkte houd in dat er features waren met raw sensor data maar ook een aantal al berekende features zoals bijvoorbeeld acceleration en rotation angle. Tijdens mijn onderzoek naar een geschikt model ben ik opzoek gegaan naar papers die IMU data verwerkte met gebruik van de voor mij en de project groep al bekende machine learning modellen, destijds K nearest neighbors Decision tree, SVM logistic regresion:
  https://ieeexplore.ieee.org/abstract/document/8646253. Deze paper classifiseerd bewegingen van een exoskelet door middel van een Decision Tree. 
  https://ieeexplore.ieee.org/abstract/document/8323826. Deze paperclassifiseerd IMU data door middel van machine learning. In deze paper vergelijken ze, statistical technique, SVM en decision tree. uit deze vergelijking blijkt dat de Decision Tree het beste gebruikt kan worden voor het classificeren van IMU data.
  
  #### Random Forest Classifier (RFC)
  
 Na het ontwerpen en tunen van de Decision Tree waren we als groep nog niet tevreden met het resultaat dus besloten we verder te zoeken. op dit moment stuite wij op onderzoeken over RFC en zijn hier dieper op in gegaan.  
  https://ieeexplore.ieee.org/abstract/document/7962153	Deze paper vergelijkt de Decision Tree met de RFC. Hier uit komt naar voren dat de decision tree erg sterk is bij het classificeren van patronen maar ook snel overfit bij en grote dataset. Door een RFC te gebruiken, wat in feite "een bos van decision trees" is behoud je het sterke classificeren maar voorkom je het overfitten door de dataset te verdelen over meedere Decision Trees.
  https://ieeexplore.ieee.org/abstract/document/9393014. Deze paper vergelijkt traditionele manieren van beweging detectie met het gebruik van een RFC. Op vele aspecten wint de RFC van de traditionele technieken.
  Gezien de grote van de data set en de veel belovende onderzoeken heb ik besloten om de RFC uit te werken en te tunen.
  
  #### Conclusie
  
  Uit onderzoek blijkt dat beide modellen worden veel gebruikt in het herkennnen en classifiseren van van bewegingen uit IMU sensor data. Gezien Mijn dataset ook uit IMU sensor data bestaat, heb ik belsoten om beide modellen te bouwen en te tunen. Om er achter te komen welk model het beste werkte voor mijn dataset heb ik ze vergeleken op accuracy, precision en recall.
  
  ### Model configureren
  
  #### Decision Tree
  
  Na dat ik het besluit genomen had om de Decision Tree te gaan gebruiken moest deze geprogrameerd worden. Gelukkig hadden we net uitleg over dit model gehad in de les en was er redelijk veel over te vinden online. Na het een en ander geprobeerd te hebben heb ik de volgende code geschreven: [Decision Tree](Models/Decision_tree_sprint_detection.ipynb). Dit model ontvangt de dataset in chunks van 1 seconde met een overlapping van 0.5 seconde. Deze waarden zijn gekozen gezien sprints nooit korter dan 1 seconde duren. Deze waarden staan vast voor alle modellen die gemaakt worden voor dit project. Op deze manier zijn de modellen eenvoudig met elkaar te vergelijken. Dit model bepaalt dus iedere seconde of er gesprint wordt of niet.
  
  #### Random Forest Classifier (RFC)
  
  Gezien de Decision Tree niet de gewenste resultaten liet zien is de RFC geprogrameerd. Deze liet bij de eerste versie al veel belovende resultaten zien dus ben ik verder gegaan met het uitbreiden en tunen van dit model en hebben we als groep besloten de Decision tree te laten voor wat het was. Ook dit model ontvangt de dataset in chunks van 1 seconde met een overlap van 0.5 seconde. De basis code was uitgebreid door Daan zijn data preparator, die automatisch alle features door geeft als max of mean waarde en de door mij toegevoegde quarter split, die er voor zorgt dat alleen de data die terug te vinden is in de video in het model gestopt wordt. De uiteindelijke code die dit is de uiteindelijke code die dit opleverde: [RFC speler A](Models/RandomForrestCLassifier_sprint_detection.ipynb) en [RFC speler B](Models/RandomForrestCLassifier_Player8.ipynb). Dit is ook het uiteindelijke model dat opgeleverd wordt aan de probleem eigenaar.
  
  ### Model trainen
  
  Ik heb zowel de Decision Tree als de RFC getrained met de dataset van 1 gekozen speler die de rest van de projectgroep ook gebruikt om resultaten te kunnen vergelijken. Ik had de dataset in 2 delen opgesplitst een train en een valideer onderdeel. In het begin van de train fase was de dataset verdeeld in 80% train en 20% valideer. Nadat besloten was dat we alleen nog verder zouden gaan met de RFC en ik de quartersplit functie gebouwd had, is de dataset opgedeeld in 75% train en 25% valideer. Dit was een stuk logischer en eenvoudiger gezien de quarter split functie de data al opdeeld in de vier gespeelde kwarten van de wedstrijd. Tijdens het trainen van de modellen is gridsearch gebruikt om de beste hyper parameters bij de gekozen features te vinden, daarbij is de variance tussen de accuracy van de training en valideer set zo laag mogelijk gehouden om overfitting te voorkomen.
  
  ### Evalueer model
  
  na het trainen van de modellen moesten de resultaten geëvalueerd worden. Helaas zaten hier wel nog wat haken en ogen aan. De verkregen dataset was namelijk niet compleet. Niet alle sprints waren getagged namelijk. Dit betekende dat de modellen niet op de standaard manier geëvalueerd konden worden. Daarom had martijn de volgende code geschreven: [Positives Visualization](Data Visualisatie/Machine_Learning_Control_With_all_data.ipynb). Deze code visualiseerd alle positives (true en false) in grafieken. Vervolgens heb ik deze grafieken vergeleken met de video data om te bepalen of de grafiek een sprint weergaf of niet. indien dit het geval was heb ik in de code de begin en eind tijd van de sprint aan gegeven, was er geen sprint in de grafiek gaf ik een 'NaN' door in de code. Wanneer alle grafieken behandeld waren voegde de code de nieuw gevonden sprints toe aan de dataset. Dit proces heb ik 6 keer herhaald.
  Voor het evalueren van de modellen was de recall het belangrijkste van deze variabele wist ik zeker dat deze correct was. Voor beide modellen heb ik een confusion matrices gemaakt van de resultaten van de valideer dataset. Deze confusion matrices gebruikte ik om vervolgens de modellen met elkaar te vergelijken. Hier onder vind u een tabel met daarin de accuracy, precision en recall score voor het detecteren van sprints:
  
| Models | Recall  | Precision  | Accuracy |
| :---:   | :-: | :-: | :-: |
| Decision Tree | 0.92 | 0.51| 0.91 |
| RFC | 0.98 | 0.94| 0.96 |
  
  In de tabel hierboven is duidelijk te zien dat de RFC een stuk beter werkt dan de decision tree. Daarom heb ik gekozen om verder te gaan met dit model en deze met de RNN van martijn te gaan vergelijken.
 
  ### Model uitkomst visualiseren
  
  Om de uitkomst van de modellen duidelijk in beeld te krijgen is er bij beide modellen een confusion matrix geplot en de accuracy, precision en recall score geprint zie [Decision Tree](Models/Decision_tree_sprint_detection.ipynb) en [RFC](Models/RandomForrestCLassifier_sprint_detection.ipynb).

</details>

## Data pre-processing

<details>
  <summary>Klik om te openen</summary>
  
  ### Data verkenning
  
  Om een beter idee te krijgen hoe ik dit project aan ging pakken, moest er niet alleen onderzoek gedaan worden naar de verschillende beschikbare modellen, maar ook de verkregen data en op welke manier deze data gebruikt kan worden. Voor dit project waren 24 unike datasets beschikbaar gesteld. Deze datasets komen van 2 gespeelde wedstrijden door 12 verschillende spelers. Iedere dataset bestaat uit sensordata van 2 IMU sensoren op een rolstoel, een op het frame en een op het wiel. Naast deze sensor data kregen we ook de video's van de gespeelde wedstrijden en een appart document met getagde acties aan de hand van deze video. Om een duidlijk beeld te krijgen van wat de sensordata precies betekende moest deze data eerst gesynchroniseerd worden met de getagde acties uit de video. Voor het synchroniseren hebben we gekeken naar de start en stop tijdstippen van de kwarten van de wedstrijd. Deze waren redelijk snel gevonden, gezien iedereen hierbij voor een langere tijd stil staat was dit redelijk eenvoudig te vinden in de sensordata. Dit hebben we gezamelijk als groep gedaan.
  
  Terwijl de groep bezig was met het synchroniseren van de data met de getagde acties heeft Martijn een code geschreven die de sensordata visualiseerd in grafieken. Deze code hielp ons bij het begrijpen van de getagde acties. Zo kwam ik er achter dat sprints het beste zichtbaar waren bij WheelRotationalSpeedX. Het maken van bochten was juist het beste zichtbaar bij FrameRotationalSpeedZ. De actie botsen bestond uit een hoge wielsnelheid die abrubt stopte en vaak zelfs een stukje de andere kant op rolt (in de grafiek naar negatief gaat). Met deze informatie stelde ik hypothese  dat WheelRotationalSpeedX het beste werkt voor het detecteren van botsingen. Uiteindelijk is Jake verder gegaan met het uitwerken van deze hypothese helaas is door tijdsdruk deze hypothese niet vergenoeg uitgewerkt om een conclusie te kunnen trekken.
  
  ### Data Cleansing
 Voor de dataset gebruikt kon worden moest deze opgeschoond worden. De data bevatte namelijk een aantal 'NaN' waardes. Deze waardes waren redelijk eenvoudig omgezet naar 0 door middel van de ".fillna(0)" functie, zie [Decision Tree](Models/Decision_tree_sprint_detection.ipynb) code (de dataset die door het model geoutput werd, is gebruikt als input om het model te trainen, hierdoor was de ".fillna(0)" overbodig geworden). Tijdens het valideren van de data bleek al snel dat de IMU sensor langer bewegingen heeft opgenomen dan op de video te zien was. gelukkig hadden we bij het verkennen van de data al vast gesteld wat de begin en eind tijden van de gespeelde kwarten van de wedstrijd waren. Dit probleem hadden we dus al aan zien komen. Om dit op te lossen is de quartersplit functie toegevoegd aan de [RFC speler A](Models/RandomForrestCLassifier_sprint_detection.ipynb). 
  
  ### Data preparation
  Een groot probleem tijdens dit project was het tekort aan getagde "True Positives" voor sprints. Dit zorgde voor veel incorrecte "false positive". Om de dataset uit te breiden heb ik in eerste instantie alle "false positive" met de hand beoordeeld, door de grafieken met de video te vergelijken. Dit koste erg veel tijd. Toen er eenmaal 2 goed werkende modellen waren (de RNN en de RFC), heb ik samen met Martijn een code geschreven die de "false positives" van deze twee modellen vergelijkt om te kijken of het wel echt een "false positive" is, zie  [vergelijking van "false positives"](Models/Compare_sprint_models.ipynb). Onze theorie was dat als beide modellen van de zelde timestamp zeggen dat iets een "false positive" is dit eigenlijk een true positive moet zijn. Om te checken of onze theorie klopte hebben wij een aantal van deze timestamps terug gezocht in de video, hieruit bleek dat wij inderdaad gelijk hadden. Met deze techniek hebben wij de dataset verbeterd van 2.4% getagde sprints naar 17.1% getagde sprints.
  
  ### Data uitleg
  De verkregen dataset bestaat uit opnames van 2 IMU sensoren die over 3 assen rotaties meten (XYZ). Dit resulteerde in 6 features raw data. De dataset was verder nog uitgebreid met een aantal features, deze features waren berekende waarden met als basis de 6 raw data features. Deze berekende features waren dingen als "Frame acceleration", "Frame angle" en "Time line". In totaal bevatte de dataset 16 features die gebruikt konden worden om verschillende bewegingen te detecteren. De complete dataset had een sample frequentie van 100Hz.
  Naast deze dataset van sensordata ontvingen wij ook een dataset met verschillende getagde acties. Deze acties zijn met de hand getagd door iemand die de video van de wedstrijd bekeken had. Ook ontvingen wij de video's waar de getagde data en de sensor data vandaan kwam. De combinatie van deze 3 vormen van data moesten wij dit project gebruiken.
  
</details>

## Comunicatie

### Presentaties
<details>
  <summary>Klik om te openen</summary>
  Tijdens deze minor heb ik meerdere presentaties gemaakt en gegeven. Bij deze presentaties lieten wij als projectgroep onze resultaten zien en blikte we vooruit op de toekomst. Ook gebruikte wij deze presentaties om vragen te stellen aan medestudenten als we ergens op vast liepen. de links naar mijn presentaties staan hier onder:
  
  [Internal1](presentaties/Internal_presentation_1.pdf)
  
  [External1](presentaties/External_presentation_1.pdf)
  
  [External2](presentaties/External_presentation_2.pdf)
  
</details>

### Paper schrijven
<details>
  <summary>Klik om te openen</summary>
  
  Voor dit onderdeel heb ik veel werk geleverd. Voor de research paper heb ik de volgende dingen gedaan:
  
  - Het template gemaakt met hierbij een korte beschrijving wat er in de hoofdstukken moet komen.
  - Voor [versie 0.5](Documentatie/Research_Paper_Project_Wheels_V0.5.pdf) 
    - De data set beschreven.
    - Random Forest Clasifier beschreven, Decision Tree beschreven, Recurrent Neural Network beschreven.
    - Het valideer onderdeel beschreven.
  - Voor [versie 1](Documentatie/Research_Paper_Project_Wheels_V1.pdf)
    - zijn mijn stukken uit versie 0.5 verder uitgebreid door medestudenten
    - de abstract beschreven
    - de introductie geschreven
    - de Dataset beschreven
    - een deel van de discussion geschreven
  
</details>
