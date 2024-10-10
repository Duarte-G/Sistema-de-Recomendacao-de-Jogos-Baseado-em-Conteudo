# Sistema de-Recomendação de Jogos Baseado em Conteúdo
Este repositório demonstra um sistema de recomendação de jogos desenvolvido utilizando técnicas de filtragem baseada em conteúdo. O código sugere jogos semelhantes com base nas características dos jogos, como nome, desenvolvedor, gênero e outras informações relevantes extraídas de um conjunto de dados obtido do Kaggle.

O script inclui as seguintes etapas:
1. **Carregamento e Pré-processamento dos Dados**: A base de dados é carregada e as entradas ausentes são removidas. As colunas relevantes para recomendação são formatadas adequadamente.

2. **Criação de Tags**: Uma nova coluna de tags é criada, combinando as características dos jogos. Essas tags são essenciais para a comparação de similaridade.

3. **Conversão de Tags em Vetores Numéricos**: As tags são convertidas em vetores numéricos utilizando a técnica de vetorização, permitindo a medição da similaridade.

4. **Cálculo de Similaridade**: A similaridade entre os jogos é calculada utilizando o método de similaridade de cossenos, que avalia a semelhança entre os vetores.

5. **Função de Recomendação**: Uma função é implementada para retornar os jogos mais semelhantes ao jogo selecionado pelo usuário.

<p align="center">
  <img src="https://github.com/user-attachments/assets/57b6a3fa-11ee-4b85-ac41-b99eb63c9e4a">
</p>

## Como Usar

 - Clone o repositório para sua máquina local.
 - Instale as bibliotecas necessárias.
 - Execute o arquivo `.ipynb` para explorar o código e visualizar os resultados.
 - Sinta-se à vontade para modificar a base de dados e ajustar o código para explorar diferentes conjuntos de dados e aplicar o sistema de recomendação em outros contextos.
