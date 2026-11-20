# Case Revi

Analise de campanhas de WhatsApp, pedidos e propensao de compra. O projeto usa um notebook Jupyter com dados carregados localmente.

## Estrutura

```text
data/
  h_messages.csv   # adicione localmente
  h_orders.csv     # adicione localmente
src/
  desafio_revi.ipynb
requirements.txt
```

Os CSVs nao sao distribuidos neste repositorio. Para executar a analise, obtenha os arquivos de dados por um canal autorizado e coloque-os na pasta `data/` com os nomes `h_messages.csv` e `h_orders.csv`. Essa pasta e os CSVs estao ignorados pelo Git para evitar o envio acidental de dados.

## Ambiente

O notebook foi executado com Python 3.14.7. Na raiz do projeto, instale as dependencias:

```powershell
python -m pip install -r requirements.txt
```

Abra `src/desafio_revi.ipynb` no VS Code, selecione um kernel Python 3.14.7 com as dependencias instaladas e execute as celulas em ordem.

O notebook procura `data/` na raiz do projeto e tambem funciona quando o diretorio de trabalho e `src/`.