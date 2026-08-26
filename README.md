# Construindo um Pipeline CI/CD com Python e GitHub Actions [ci-cd-python]

## Função repositório
Gerar o artefato de um programa em python, realizando testes de execução.

## 1. O que representa a etapa de CI neste projeto? 
O CI representa a validação, onde ele baixa o código, configura o ambiente, instala as dependências e realiza testes conforme arquivo `test_calculadora.py`

## 2. O que impede a execução do Continuous Delivery quando existe um defeito? 
Se um dos passos do job `ci` falhar, o job `ci` é marcado com o status de Falha. O GitHub Actions cancela automaticamente a execução de qualquer tarefa seguinte.

## 3. Qual seria a próxima etapa necessária para  transformar este pipeline em Continuous Deployment?
automatizar o envio do artefato gerado direto para o ambiente de produção, pois ele publica o artefato, mas cabe ao usuário colocar ele onde for necessário.


----
## Sobre o Autor

Desenvolvido e documentado por **Arthur Marques Diniz**.

*   **GitHub:** [@arthurmdiniz](https://github.com)
*   **LinkedIn:** [arthurmdiniz](https://www.linkedin.com/in/arthurmdiniz/)
*   **E-mail:** arthurmdiniz@outlook.com.br
