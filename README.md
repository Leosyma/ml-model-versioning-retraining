# Model versioning and retraining

The scripts split the dataset, train and evaluate a baseline, save numbered versions and retrain the model. Flask exposes POST /predict. After starting it, run python src/dsa_cliente.py in another terminal.

## Run locally

```sh
python -m pip install -r requirements.txt
python src/dsa_preprocessa_dados.py
python src/dsa_treina_modelo.py
python src/dsa_avalia_modelo.py
python src/dsa_versiona_modelo.py
python src/dsa_retreina_modelo.py
python src/dsa_deploy_modelo.py
```
