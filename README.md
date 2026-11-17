# Model versioning and retraining

The scripts split the dataset, train and evaluate a baseline, save numbered versions and retrain the model. Flask exposes POST /predict. After starting it, run python src/cliente.py in another terminal.

## Run locally

```sh
python -m pip install -r requirements.txt
python src/preprocessa_dados.py
python src/treina_modelo.py
python src/avalia_modelo.py
python src/versiona_modelo.py
python src/retreina_modelo.py
python src/deploy_modelo.py
```
