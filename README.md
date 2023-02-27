# Learning-API
Deploy a machine learning model using Flask.
Create a model that predicts which passengers survived the Titanic shipwreck.

## Model serialization
Run `python model.py` for pickle model serialization.
After running you will see 2 files, model.pkl and model_columns.pkl


## Running API
Run  `python api.py` on localhost.
</br>
Request example
```
[
    {"Age": 85, "Sex": "male", "Embarked": "S"},
    {"Age": 24, "Sex": "female", "Embarked": "C"},
    {"Age": 3, "Sex": "male", "Embarked": "C"},
    {"Age": 21, "Sex": "male", "Embarked": "S"}
]
```
</br>
return surviived
```
{
    "prediction": "[0, 1, 0, 0]"
}
```
