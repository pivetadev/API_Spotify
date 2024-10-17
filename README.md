# Projeto de Coleta de Dados: Kaggle e API do Spotify

## Descrição do Projeto
Este projeto tem como objetivo demonstrar diferentes formas de coleta e manipulação de dados, utilizando métodos disponíveis na plataforma Kaggle e a integração com a API do Spotify. Durante o desenvolvimento, foram coletados dados exclusivamente por meio das ferramentas de coleta de dados que o Kaggle oferece, permitindo aprender sobre como acessar e trabalhar com datasets públicos.

Além disso, exploramos a API do Spotify para obter informações em tempo real sobre artistas e suas músicas mais populares, ilustrando a versatilidade das APIs na coleta de dados.

Esse projeto foi utilizado em uma aula, onde foram abordadas as técnicas de coleta de dados e como podemos automatizar a extração de informações de uma API, exemplificando com o Spotify.

## Coleta de Dados
1. Coleta de Dados do Kaggle
  Dataset do Kaggle:

    **Link para o Dataset:** [2024 Olympics Medals and Economic status](https://www.kaggle.com/datasets/mohamedyosef101/2024-olympics-medals-and-economic-status) <br>
    **Conteúdo:** Este conjunto de dados fornece a contagem de medalhas dos Jogos Olímpicos de verão de 2024 para os países com melhor desempenho,
   juntamente com os valores correspondentes do Produto Interno Bruto (PIB) para o ano de 2023. O conjunto de dados inclui o número de medalhas
   de ouro, prata e bronze conquistadas, o número total de medalhas e o PIB por país.
   <br>
3. Coleta de Dados da API do Spotify

Na segunda parte, integramos a API do Spotify para coletar dados em tempo real sobre artistas e suas faixas mais populares. O foco aqui foi mostrar como utilizar a API para extrair informações detalhadas sobre músicas, como:

    Nome da faixa
    Popularidade
    Álbum

A utilização da API permite a obtenção de dados dinâmicos e sempre atualizados, sendo uma excelente forma de demonstrar o poder das APIs para coleta de dados de grandes plataformas.
Endpoints Utilizados:

    Get Artist's Top Tracks: Coleta as faixas mais populares de um determinado artista.
    Get Track Features: Coleta atributos detalhados sobre uma música específica.
## Requisitos

Tecnologias e Bibliotecas Utilizadas

Para rodar o projeto, você precisará ter as seguintes ferramentas e bibliotecas instaladas:

    Python 3.8+
    Bibliotecas Python:
        pandas: Manipulação de dados.
        requests: Realização de requisições HTTP para a API do Spotify.
        matplotlib: (Opcional) Para visualização dos dados.
        spotipy: Biblioteca para integração com a API do Spotify.
        numpy: Para cálculos numéricos.
        
Obtenha suas credenciais da API do Spotify:

    Crie uma conta no Spotify Developer.
    Crie um aplicativo para obter suas credenciais (Client ID e Client Secret).
    Adicione suas credenciais no arquivo .env ou diretamente no código, conforme o exemplo no projeto.

## Uso em Aula
Este projeto foi desenvolvido como material didático para uma aula sobre coleta de dados. Nele, exploramos como trabalhar tanto com dados estáticos, utilizando datasets como os do Kaggle, quanto com dados dinâmicos e atualizados em tempo real, utilizando a API do Spotify. O uso da API foi um exemplo prático de como obter informações diretamente de uma plataforma popular, integrando-as ao nosso pipeline de dados.

Durante a aula, explicamos:

    O processo de obtenção e preparação de dados do Kaggle.
    Como configurar e usar a API do Spotify para extrair dados.
    Como automatizar e integrar a coleta de dados em diferentes fontes.
