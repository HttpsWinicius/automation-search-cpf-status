
# Automacao de Consulta de CPF e Registro em Planilha

Este software automatiza a consulta de CPFs em um site e registra os resultados em uma planilha do Excel. Ele utiliza as bibliotecas Selenium e OpenPyXL para interagir com o navegador e manipular arquivos Excel.

## Funcionalidades

- Lê uma planilha (dados_clientes.xlsx) contendo nome, preço, CPF e data de vencimento.
- Acessa um site de consulta de CPF.
- Insere o CPF de cada cliente no campo de busca e realiza a consulta.
- Coleta as informações retornadas, incluindo status da dívida, data do pagamento e método de pagamento.
- Registra os resultados na planilha planilha fechamento.xlsx, diferenciando clientes em dia e pendentes.


## Stack utilizada

Python 3.x

ChromeDriver compatível com a versão do navegador

Bibliotecas necessárias:

openpyxl - Leitura/Escrita em planilha.

selenium - Interação com navegador.



## Instalação

Certifique-se de que os arquivos dados_clientes.xlsx e planilha fechamento.xlsx estejam na mesma pasta do script.

```bash
  pip install openpyxl selenium
  python app.py
```
    
## Autor

- [@HttpsWinicius](https://github.com/HttpsWinicius)