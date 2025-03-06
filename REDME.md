# Projekt

## Szacowanie wskaźnika proliferacji komórek Ki-67 z wykorzystaniem głębokich sieci neuronowych

Celem projektu jest opracowanie modelu głębokiej sieci neuronowej o architekturze SUNet (Stacked U-Net) do segmentacji jąder komórkowych na obrazach immunohistochemicznych markera Ki-67. Model ten ma na celu automatyczne szacowanie wskaźnika proliferacji komórek, co jest istotne w diagnostyce nowotworów, takich jak rak piersi. System oparty na sieci SUNet pozwoli na bardziej precyzyjne i efektywne przetwarzanie obrazów niż tradycyjne metody manualnego liczenia komórek.

## Wymagania

Wymagane oprogramowanie i zależności:

- Python 3.x
- Conda
- TensorFlow GPU
- OpenCV
- NumPy, Pandas, Matplotlib, SciPy

## Instalacja

Aby skonfigurować środowisko, wykonaj:

```bash
# Tworzenie środowiska Conda
conda env create -f environment.yml

# Aktywacja środowiska
conda activate tf-gpu
```

Jeśli korzystasz z `pip`, możesz zainstalować zależności ręcznie:

```bash
pip install -r requirements.txt
```

## Użycie

Po aktywowaniu środowiska uruchom projekt:

```bash
python main.py
```

lub jeśli używasz Jupyter Notebook:

```bash
jupyter notebook
```

## Licencja

Informacje o licencji, np. MIT, GPL itp.
