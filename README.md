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
  <summary>Click to expand!</summary>
  Gedurende deze minor stond de programeertaal Phyton centraal. Om deze taal meer onder de knie te krijgen heeft iedereen tijdens de minor een online cursussen phyton coderen   gevolgd via Datacamp. Bij deze cursus stonden de volgende onderwerpen centraal: het omgaan met panda dataframes, het visualiseren van data, data preparation en het toepassen en valideren van verschillende machine learning modellen.
  
  Ik had redelijk wat moeite met deze cursussen phyton. Coderen is nooit mijn sterkste kant geweest toch vind ik het erg interresant en wil ik er graag beter in worden. 
</details>

## Reflectie en evaluatie

### Op eigen deelname aan het project
<details>
  <summary>Click to expand!</summary>
  
</details>

### Op eigen leerdoelen
<details>
  <summary>Click to expand!</summary>
  
</details>

### Op de project groep als een geheel
<details>
  <summary>Click to expand!</summary>
  
</details>

## Predictive analytics
<details>
  <summary>Click to expand!</summary>
  
  ### Model selecteren

  #### Decision Tree
  
  De verkregen datasets voor het project wheels bestond uit deels verwerkte IMU (Inertial Measurement Unit) data. Dit deels verwerkte houd in dat er features waren met raw sensor data maar ook een aantal al berekende features zoals bijvoorbeeld acceleration en rotation angle. Tijdens mijn onderzoek naar een geschikt model ben ik opzoek gegaan naar papers die IMU data verwerkte met gebruik van de voor mij en de project groep al bekende machine learning modellen, destijds K nearest neighbors Decision tree, SVM logistic regresion:
  https://ieeexplore.ieee.org/abstract/document/8646253. Deze paper classifiseerd bewegingen van een exoskelet door middel van een Decision Tree. 
  https://ieeexplore.ieee.org/abstract/document/8323826. Deze paperclassifiseerd IMU data door middel van machine learning. In deze paper vergelijken ze, statistical technique, SVM en decision tree. uit deze vergelijking blijkt dat de Decision Tree het beste gebruikt kan worden voor het classificeren van IMU data.
  
  #### Random Forest Classifier (RFC
  
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
  Gezien de Decision Tree niet de gewenste resultaten liet zien is de RFC geprogrameerd. Deze liet bij de eerste versie al veel belovende resultaten zien dus ben ik verder gegaan met het uitbreiden en tunen van dit model en hebben we als groep besloten de Decision tree te laten voor wat het was. Ook dit model ontvangt de dataset in chunks van 1 seconde met een overlap van 0.5 seconde. De basis code was uitgebreid door Daan zijn data preparator, die automatisch alle features door geeft als max of mean waarde en de door mij toegevoegde quarter split, die er voor zorgt dat alleen de data die terug te vinden is in de video in het model gestopt wordt. De uiteindelijke code die dit is de uiteindelijke code die dit opleverde: [Random Forest Classifier] (Models/RandomForrestClassifier_sprint_detection.ipynb). Dit is ook het uiteindelijke model dat opgeleverd wordt aan de probleem eigenaar.
  
  ### Model trainen
  
  
</details>



## Comunication

### Presentations
<details>
  <summary>Click to expand!</summary>
  Ik heb in totaal 4 presentaties gemaakt en gegeven waarvan 2 internal en 2 external
</details>

### Writing paper
<details>
  <summary>Click to expand!</summary>
  
  Voor dit onderdeel heb ik veel werk geleverd. Voor de research paper heb ik de volgende dingen gedaan:
  
  - Het template gemaakt met hierbij een korte beschrijving wat er in de hoofdstukken moet komen.
  - Voor versie 0.5
    - De data set beschreven.
    - Random Forest Clasifier beschreven, Decision Tree beschreven, Recurrent Neural Network beschreven, Convolutional Neural network beschreven.
    - Het test onderdeel beschreven.
  - Voor versie 1
    - de abstract beschreven
    - de Dataset beschreven
  
</details>
