# Colicky-Horses-DSC530

Dataset:
The dataset I am using for the project is a flat-file source (.csv file) and the data can be obtained/accessed from the below places:
1. https://archive.ics.uci.edu/ml/datasets/Horse+Colic
2. https://www.kaggle.com/uciml/horse-colic?select=datadict.txt

Dataset description:
* This dataset consists of data from colicky horses. 

Variables:
* The original dataset includes a total of 28 variables.
* I will be using 11 of those variables for my project.

Variable descriptions:
* surgery: a variable that indicates whether a horse had colic surgery or not (categorical). 
    * 1 = no Surgery
    * 2 = surgery
* age: the age of the horse, split into two (2) categories.
    * 1 = young horse (< 6 months)
    * 2 = adult horse
* rectal_temp: the rectal temperature of the horse (in degrees Celsius). Normal is 37.8.
* pulse: the horse’s heart rate in beats per minute. Normal range (for adults) is 30-40 bpm.
* respiratory_rate: breaths per minute of a horse. Normal range is 8-10 breaths.
* mucous_membrane: color of these membranes indicates current circulation. Normal pink and bright pink indicate normal or slightly increased circulation.
* capillary_refill_time: another indicator of circulation. The longer the refill, the poorer the circulation.
    * 1 = less than 3 seconds
    * 2 = more than or equal to 3 seconds
* abdominal_distension: an important parameter/indicator for colic (since colic is an abdominal/digestive issue). No distension is healthy/normal.
    * 1 = none		
    * 2 = slight
    * 3 = moderate		
    * 4 = severe
* abdomen: the status of the horse's abdomen overall. A value of 3 is likely an obstruction caused by mechanical impaction. 4 and 5 indicate a surgical lesion.
    * 1 = normal		
    * 2 = other		
    * 3 = firm feces in the large intestine		
    * 4 = distended small intestine		
    * 5 = distended large intestine		
* packed_cell_volume: the number of red cells by volume in the blood, normal range is 30-50.
* outcome: the life outcome of the horse – did it live, die, or was it euthanized?


Additional background information on the dataset and some of the variables:
* A horse’s rectal temperature:
    * An elevated temp may occur due to infection.		
    * Temperature may be reduced when the animal is in late shock			
    * This parameter will usually change as the problem progresses		
* A horse’s pulse:
    * It is rare to have a lower-than-normal rate although athletic horses may have a rate of 20-25
    * Those with painful lesions or suffering from circulatory shock may have an elevated heart rate
* A horse’s mucous membrane:
    * 1 and 2 probably indicate a normal or slightly increased circulation (normal pink, bright pink)	
    * 3 may occur in early shock (pale pink)	
    * 4 and 6 are indicative of serious circulatory compromise (pale cyanotic, dark cyanotic)	
    * 5 is more indicative of a septicemia (bright red/injected)
* A horse’s abdominal distension: 
    * Abdominal distension is likely to be painful and have reduced gut motility		
    * A horse with severe abdominal distension is likely to require surgery just to relieve the pressure
* A horse’s packed cell volume: 
    * The level rises as the circulation becomes compromised or as the animal becomes dehydrated

