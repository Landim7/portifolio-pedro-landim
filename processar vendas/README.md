# Analisador de Limite de Segurança de Vendas 🛡️

Este projeto é um script Python desenvolvido para monitorar se a média de vendas de um determinado período permanece dentro de um teto de segurança operacional estabelecido pelo usuário.

## 📋 Descrição do Projeto

O script funciona como uma ferramenta de validação simples. Ele solicita um parâmetro de segurança e três valores de vendas, calcula a média aritmética e verifica se essa média ultrapassa o limite aceitável.

## 🚀 Funcionalidades

O código executa as seguintes operações:
* **Entrada de Parâmetro**: Define o valor de referência para o `limite_segurança`.
* **Coleta de Dados**: Recebe três inputs individuais de vendas (`Venda_1`, `Venda_2`, `Venda_3`).
* **Cálculo de Totais**: Soma o volume total das vendas informadas.
* **Cálculo de Média**: Gera a média aritmética do período analisado.
* **Validação Lógica**: 
    * Se a média for **menor ou igual** ao limite: Retorna "Valor seguro".
    * Se a média for **maior** que o limite: Retorna "Valor não seguro".

## 🛠️ Tecnologias

* **Python 3.x**
* **Google Colab** (Ambiente de desenvolvimento original)

## 💻 Exemplo de Uso

Ao executar o script, a interação no console será semelhante a esta:

```text
valor de segurança: 5000
--------------------------------------------------
primeira venda: 4000
segunda venda: 5000
terceira venda: 4500

--------------------------------------------------
Valor total de vendas:  13500
Valor da media de vendas:  4500.0

--------------------------------------------------
Valor seguro


