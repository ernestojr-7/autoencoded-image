# Experimento com Autoencoder em imagens de Raio-x de tórax

Dataset: [COVID-19 Radiography Database](https://www.kaggle.com/datasets/tawsifurrahman/covid19-radiography-database).

Dessa base de dados foi pego 1k imagens com labels COVID e 1k Normal. Desses 2k, 1k foi para treino e validação do Autoencoder.

As imagens usadas para o treino e validação dos classificadores foram das mil que não foram vistas pelo Autoencoder, para excluir data leakage.
