# 🐱 Cat vs Non-Cat Classifier

Este projeto é uma implementação simples de um classificador de imagens que identifica se uma imagem contém um **gato** ou **não**.

## 📂 Estrutura do projeto

cat-or-not-cat-classifier/
├── data/ # Contém os arquivos .h5 com os datasets
├── main.py # Script principal com todo o código
└── README.md # Este arquivo

## 🚀 Como usar

1. Clone o repositório:

    ```
    git clone https://github.com/seu-usuario/cat-or-not-cat-classifier.git
    cd cat-or-not-cat-classifier
    ```

2. Adicione os arquivos train_catvnoncat.h5 e test_catvnoncat.h5 na pasta data/.

3. (Opcional) Crie um ambiente virtual:

    ```
    python -m venv .venv
    source .venv/bin/activate  # Linux/macOS
    .venv\Scripts\activate     # Windows
    ```

4. Instale as dependências:

    pip install requirements.txt

5. Execute o script:

    python main.py