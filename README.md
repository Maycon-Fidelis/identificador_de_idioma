# Deteção de Idiomas

Este é um projeto capaz de detectar qual é o idioma de um texto, sendo treinado em português, inglês e alemão. Ele detecta se o texto pertence a um desses idiomas e caso observe que seja de um idioma não compatível, retorna: "idioma desconhecido".

## Estrutura do Projeto

- `data/deu.txt`: Arquivo que contém palavras em alemão e inglês.
- `data/por.txt`: Arquivo que contém palavras em português e inglês.
- `indenticar_idioma.ipynb`: Arquivo Jupyter Notebook que contém os dados, treino do modelo e a execução do modelo.

## Requisitos

- Python 3.x
- Pandas
- NumPy
- Scikit-learn
- Jupyter Notebook

## Instruções para Execução
1. Clone este repositório:

    ```bash
    git clone https://github.com/Maycon-Fidelis/identificador_de_idioma.git
    cd identificador_de_idioma
    ```

2. Instale as dependências (se ainda não estiverem instaladas):

    ```bash
    pip install pandas numpy scikit-learn jupyterlab
    ```
    
3. Dentro da pasta `identificador_de_idioma`, digite o comando para abrir o Jupyter Notebook no navegador:
   ```
   jupyter notebook
   ```

5. No Jupyter, abra o arquivo `indenticar_idioma.ipynb`.

## Uso

Execute os comandos pela ordem em que aparecem no notebook. Após treinar o modelo, você pode usar a função `detectar_idioma` para identificar o idioma de uma frase. Exemplo:

```python
print(detectar_idioma('Eu estou certo')) # Retorna: Português
