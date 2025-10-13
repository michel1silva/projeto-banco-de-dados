# Descrição do Sistema de Avaliação de Filmes

O sistema tem como objetivo permitir que usuários avaliem filmes
cadastrados, atribuindo notas e comentários. Ele armazena informações
sobre usuários, filmes, gêneros, atores e avaliações realizadas. A
aplicação deve gerar relatórios e gráficos com base nesses dados,
utilizando consultas SQL com junções, agrupamentos e filtros.

------------------------------------------------------------------------

## Fluxo de Funcionalidades

1.  **Cadastro de gêneros:** inclusão de diferentes gêneros de filmes
    (ação, comédia, drama etc.).\
2.  **Cadastro de atores:** cada ator possui nome, data de nascimento e
    nacionalidade.\
3.  **Cadastro de filmes:** cada filme tem título, ano de lançamento,
    duração, sinopse e gênero associado.\
4.  **Associação de atores aos filmes:** define os atores participantes
    de cada filme e seus papéis.\
5.  **Cadastro de usuários:** permite que usuários se registrem para
    avaliar filmes.\
6.  **Avaliação de filmes:** cada usuário pode avaliar um filme apenas
    uma vez, atribuindo nota e comentário.\
7.  **Consultas e relatórios:** exibição de médias de notas, rankings e
    comparativos com base nas avaliações.

------------------------------------------------------------------------

## Relatórios e Consultas Esperadas

-   Média de notas por filme.\
-   Top 10 filmes mais bem avaliados.\
-   Média de notas por gênero.\
-   Histórico de avaliações por usuário.\
-   Atores mais presentes em filmes bem avaliados.\
-   Comparativo entre a nota do usuário e a média geral do filme.

------------------------------------------------------------------------

## Visualizações Esperadas

-   Lista de filmes com média de notas.\
-   Página de detalhes do filme com elenco, comentários e gráfico de
    notas.\
-   Relatórios com gráficos de média por gênero, evolução de avaliações
    e ranking dos filmes mais bem avaliados.
