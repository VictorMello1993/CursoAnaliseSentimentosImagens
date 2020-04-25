# CursoReconhecimentoEmocoes
Repositório contendo scripts responsáveis pela detecção de emoções com a visão computacional e Machine Learning, aprendidos em um curso da plataforma Udemy com professores Jones Granatyr e Gabriel Alves, utilizando a biblioteca TensorFlow para treinamento de redes neurais convolucionais (CNN). 

Os scripts foram implementados no Google Colab. Para testá-los, é preciso descompactar o arquivo zipado Material.zip através da linha abaixo:
```Python
from google.colab import drive
drive.mount('/content/drive', force_remount=True)
path = "/content/drive/My Drive/Material.zip"
zip_object = zipfile.ZipFile(file=path, mode="r")
zip_object.extractall("./")
```
O zip deve ficar na raíz do seu Google Drive (pasta Meu Drive).

Arquivo zipado: https://drive.google.com/file/d/1ZS3ya18nHgOWOvLSRP0uRchz8YMM-hc2/view?usp=sharing

Base de dados utilizada: FER2013.csv https://www.kaggle.com/nicolejyt/facialexpressionrecognition#fer2013.csv

Recursos:
* OpenCV
* TensorFlow
* Pandas
* Matplotlib
* NumPy
* ZipFile
* Sklearn
