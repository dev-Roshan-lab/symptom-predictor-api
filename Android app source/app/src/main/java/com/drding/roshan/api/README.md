# Android App
- Here we Send Request in order to 'GET' the Disease name
- [url of sample request](https://symptom-predictor-api.herokuapp.com/rf/constipation/back%20pain/runny%20nose/congestion/abdominal%20pain) 
-  The symptoms are Passes through the Url 
-  In the python source code the url structure is defined as '_/rf/sym1/sym2/sym3/sym4/sym5_' where _sym1_, _sym2_, _sym3_, _sym4_, _sym5_ are varibales through which symptoms are passed for prediction
-  Other Symptoms include :
>       
        'back pain','constipation','abdominal pain','diarrhoea','mild fever','yellow urine',
        'yellowing of eyes','acute liver failure','fluid overload','swelling of stomach',
        'swelled lymph nodes','malaise','blurred and distorted vision','phlegm','throat irritation',
        'redness of eyes','sinus pressure','runny nose','congestion','chest pain','weakness in limbs',
        'fast heart rate','pain during bowel movements','pain in anal region','bloody stool',
        'irritation in anus','neck pain','dizziness','cramps','bruising','obesity','swollen legs',
        'swollen blood vessels','puffy face and eyes','enlarged thyroid','brittle nails',
        'swollen extremeties','excessive hunger','extra marital contacts','drying and tingling lips',
        'slurred speech','knee pain','hip joint pain','muscle weakness','stiff neck','swelling joints',
        'movement stiffness','spinning movements','loss of balance','unsteadiness',
        'weakness of one body side','loss of smell','bladder discomfort','foul smell of urine',
        'continuous feel of urine','passage of gases','internal itching','toxic look (typhos)',
        'depression','irritability','muscle pain','altered sensorium','red spots over body','belly pain',
        'abnormal menstruation','dischromic  patches','watering from eyes','increased appetite','polyuria','family history','mucoid sputum',
        'rusty sputum','lack of concentration','visual disturbances','receiving blood transfusion',
        'receiving unsterile injections','coma','stomach bleeding','distention of abdomen',
        'history of alcohol consumption','fluid overload','blood in sputum','prominent veins on calf',
        'palpitations','painful walking','pus filled pimples','blackheads','scurring','skin peeling',
        'silver like dusting','small dents in nails','inflammatory nails','blister','red sore around nose',
        'yellow crust ooze'

- The website request code is located in line no. 59 of the [main.java](https://github.com/dev-Roshan-lab/symptom-predictor-api/blob/master/Android%20app%20source/app/src/main/java/com/drding/roshan/api/MainActivity.java)
