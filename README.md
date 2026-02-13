# 🎬 MovieFinder

Aplicação web desenvolvida com React e TypeScript para descoberta de filmes, visualização de informações detalhadas e criação de uma lista personalizada de títulos para acompanhamento.<br><br>

O projeto foi desenvolvido com foco em organização arquitetural, boas práticas de desenvolvimento front-end e consumo estruturado de API externa.


##

📌 Objetivo do Projeto

O objetivo deste projeto foi simular um produto real de descoberta de filmes, aplicando conceitos como:<br><br>

Consumo de API REST<br>
Gerenciamento de estado assíncrono<br>
Organização por domínio (feature-based structure)<br>
Componentização e reutilização<br>
Tratamento de estados de carregamento e erro<br>
Persistência local de dados<br>
Experiência do usuário e acessibilidade<br>

<br>
🚀 Funcionalidades
<br>
🎞️ Listagem de Filmes

Exibição de filmes populares e lançamentos<br>
Paginação ou carregamento incremental<br>
Estados de loading e tratamento de erros<br>

<br>
🎬 Página de Detalhes

Exibição de informações completas do filme:

Poster e backdrop<br>
Nota média<br>
Gêneros<br>
Duração<br>
Sinopse<br>
Elenco principal<br>
Trailer (quando disponível)

<br>
🔎 Busca

Busca por título<br>
Implementação de debounce para otimização de requisições<br>
Exibição de resultados dinâmicos<br>

<br>
📌 Watchlist

Adição e remoção de filmes<br>
Persistência utilizando LocalStorage<br>
Página dedicada para gerenciamento da lista<br>

<br>
⭐ Avaliação Pessoal

Sistema de nota individual
Armazenamento local da avaliação
Exibição integrada à página do filme

<br>
🛠️ Tecnologias Utilizadas

React<br>
TypeScript<br>
Vite<br>
React Router DOM<br>
TanStack Query (gerenciamento de estado assíncrono e cache)<br>
Axios<br>
TailwindCSS (ou Styled Components)<br>
LocalStorage API<br>

<br>
🧱 Arquitetura

O projeto segue organização por domínio (feature-based structure), visando escalabilidade e manutenção futura.

src/
  features/
    movies/
    watchlist/
    ratings/
  pages/
  components/
  services/
  hooks/


Essa abordagem favorece separação de responsabilidades e facilita evolução do projeto.

<br>
🔐 Variáveis de Ambiente

Para execução local, é necessário criar um arquivo .env na raiz do projeto:

VITE_TMDB_API_KEY=SUA_CHAVE
VITE_TMDB_BASE_URL=https://api.themoviedb.org/3

<br>
📈 Possíveis Evoluções

Implementação de autenticação<br>
Sincronização da watchlist via backend<br>
Testes automatizados<br>
Melhorias adicionais de performance<br>
Internacionalização<br>

<br>
📚 Fonte de Dados

Os dados exibidos são fornecidos pela API do The Movie Database (TMDB).
