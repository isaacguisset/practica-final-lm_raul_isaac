## RAUL OSUNA & ISAAC GUISSET -- PRÀCTICA FINAL


## MARKDOWN


# XML:
```xml
<?xml version="1.0" encoding="UTF-8"?>
<plats>
    <plat>
        <nom>Paella</nom>
        <preu>12.50€</preu>
        <ingredients>
            <ingredient>
                <nom>Arros</nom>
                <quantitat>200</quantitat>
                <unitats>grams</unitats>
                <calories>180</calories>
            </ingredient>
            <ingredient>
                <nom>Camaro</nom>
                <quantitat>100</quantitat>
                <unitats>grams</unitats>
                <calories>90</calories>
            </ingredient>
            <ingredient>
                <nom>Pollastre</nom>
                <quantitat>150</quantitat>
                <unitats>grams</unitats>
                <calories>210</calories>
            </ingredient>
            <ingredient>
                <nom>safra</nom>
                <quantitat>0,5</quantitat>
                <unitats>grams</unitats>
                <calories>2</calories>
            </ingredient>
            <ingredient>
                <nom>Aigua</nom>
                <quantitat>500</quantitat>
                <unitats>mililitres</unitats>
                <calories>180</calories>
            </ingredient>
        </ingredients>
        <allergens>
            <allergen>Pot contenir traces de crustacis</allergen>
            <allergen>Conté safrà</allergen>
        </allergens>
    </plat>
    <plat>
        <nom>Amanida de tonyina</nom>
        <preu>8.00€</preu>
        <ingredients>
            <ingredient>
                <nom>Enciam</nom>
                <quantitat>80</quantitat>
                <unitats>grams</unitats>
                <calories>14</calories>
            </ingredient>
            <ingredient>
                <nom>Tomàquet</nom>
                <quantitat>100</quantitat>
                <unitats>grams</unitats>
                <calories>18</calories>
            </ingredient>
            <ingredient>
                <nom>Tonyina</nom>
                <quantitat>120</quantitat>
                <unitats>grams</unitats>
                <calories>132</calories>
            </ingredient>
            <ingredient>
                <nom>Ou dur</nom>
                <quantitat>5'</quantitat>
                <unitats>grams</unitats>
                <calories>40</calories>
            </ingredient>
            <ingredient>
                <nom>Oliva</nom>
                <quantitat>10</quantitat>
                <unitats>unitats</unitats>
                <calories>14080</calories>
            </ingredient>
        </ingredients>
        <allergens>
            <allergen>Conté ou</allergen>
        </allergens>
    </plat>
</plats>
```

# JSON
```json
{
    "plats" : 
    [
        {
            "nom" : "Paella",
            "preu" : 12.50,
            "ingredients" : 
            [
                {"nom" : "Arròs", "quantitat" : 200.0, "unitats" : "grams", "calories" : "180 kcal"}, 
                {"nom" : "Camaró", "quantitat" : 100.0, "unitats" : "grams", "calories" : "90 kcal"}, 
                {"nom" : "Pollastre", "quantitat" : 150.0, "unitats" : "grams", "calories" : "210 kcal"}, 
                {"nom" : "Safrà", "quantitat" : 0.5, "unitats" : "grams", "calories" : "2 kcal"}, 
                {"nom" : "Aigua", "quantitat" : 500.0, "unitats" : "ml", "calories" : "0 kcal"}
            ],
            "allergens" :
            [
                {"allergen" : "Pot contenir traces de crustacis"},
                {"allergen" : "Conté safrà"}
            ]
        },
        {
            "nom" : "Amanida de tonyina",
            "preu" : 8.00,
            "ingredients" : 
            [
                {"nom" : "Enciam", "quantitat" : 80.0, "unitats" : "grams", "calories" : "14 kcal"}, 
                {"nom" : "Tomàquet", "quantitat" : 100.0, "unitats" : "grams", "calories" : "18 kcal"}, 
                {"nom" : "Tonyina", "quantitat" : 120.0, "unitats" : "grams", "calories" : "132 kcal"}, 
                {"nom" : "Ou dur", "quantitat" : 50.0, "unitats" : "grams", "calories" : "77 kcal"}, 
                {"nom" : "Oliva", "quantitat" : 10.0, "unitats" : "unitats", "calories" : "40 kcal"}
            ],
            "allergens" :
            [
                {"allergen" : "Ou"}
            ]
        }
    ]
}

```

# CSV

```

Nom_Plat,Preu,Nom_Ingredient,Quantitat,Unitats,Calories,Allergens
Paella,12.50,Arròs,200.0,grams,180,Pot contenir traces de crustacis; Conté safrà
Paella,12.50,Camaró,100.0,grams,90,Pot contenir traces de crustacis; Conté safrà
Paella,12.50,Pollastre,150.0,grams,210,Pot contenir traces de crustacis; Conté safrà
Paella,12.50,Safrà,0.5,grams,2,Pot contenir traces de crustacis; Conté safrà
Paella,12.50,Aigua,500.0,ml,0,Pot contenir traces de crustacis; Conté safrà

Nom_Plat,Preu,Nom_Ingredient,Quantitat,Unitats,Calories,Allergens
Amanida de Tonyina,8.00,Enciam,80.0,grams,14,conté ou
Amanida de Tonyina,8.00,Tomàquet,100.0,grams,18,conté  ou
Amanida de Tonyina,8.00,Tonyina,120.0,grams,132,conté  ou
Amanida de Tonyina,8.00,conté conté ou dur,50.0,grams,77,conté  ou
Amanida de Tonyina,8.00,Oliva,10.0,unitats,40,conté  ou


```