# Disease detection

This projects is about detecting a disease with given symptoms.

## Install

Create venv and install requirements

```bash
pip install -r requirements.txt
```

## Usage

Edit `predict_disease.py` last line :
```python
print(predictDisease("Itching,Abdominal Pain,Altered Sensorium,Palpitations,Enlarged Thyroid"))
```
with the symptoms you want (chosen from the first line of the dataset files)

Also, don't forget to download the dataset folder!

Then, run the file:
```bash
python predict_disease.py
```
