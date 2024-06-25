##teste-tecnico-Pokedex

Óla! este é meu rpimeiro teste tecnico em React.JS, a ideia é uma pequena pagina com uma listagem de pokemons e descriçâo de suas respectivas habilidades, nome e tipo.

### Funcionalidades
A pagina inicial fornece uma barra de pesquisa para encontrar um pokemon especifico pelo nome, também até 10 cards clicavéis de pokemons e 2 botões para carregar mais pokemons ou menos pokemons. Ao clicar nos cards, uma nova pagina é renderizada com nome habilidade e tipo do pokemon.

### Ferramentas utilizadas
-axios, por fornecer chamadas de API assincronas
-@mui/material, por fornecer estilizações prontas de cards, button slide e Navbar flexiveis á personalização do usuario
-useContext, por permitir o compartilhamento de dados entre componentes, sem precisar passar por props de forma manual de uma componente para o outro
-useNavigate, por ser uma metodo de navegação entre rotas especificas de componentes funcionais
-useEffect, por lidar com efeitos de API,como buscar dados
-useState, por fornecer a possibilidade de criar estados a partir de uma função com menos codigo
-styled-components, por permitir estilizações especificas para cada um dos componentes, usando codigo CSS em React.jsx 

### Decisões, planejamento e Execução
Inicialmente, pensei em adotar mais biblioteca de dados para a estilização mais facilitada da pagina inicial, sempre pesquisando mais sobre estilo de botões, barra de pesquisa e afins, porem depois vi que acabaria ficando muitas importações de varios arquivos, então decidi usar o styled-components para finalizar o restante do projeto, decidi fazer com que os cards mudassem de tema claro ou escuro, ao invés da pagina pois ficaria bem diferente do que vemos na internet. precisei rever as aulas do curso varias e varias vezes, fazer anotações em folha mesmo e consultar tutoriais na internet ao mesmo tempo em que lia foruns para a resolução de muitas duvidas recorrentes durante o projeto. já na execuçao, procurei deixar o mais simples possivel parecido com uma tela de descrição de personagem de jogos de RPG.

### Como rodar a Pokedex na sua maquina
Inicialmente, clique com o botão direito do mouse na pasta "desafio-teste-tecnico" e abra usando o VS code, então no terminal do powershell digite "npm run dev" e clique em localhost, em seguida, "seguir link" e Pronto! Na pagina, em "trocar tema" podemos trocar o tema dos cards para claro ou escuro, pesquisar por pokemons especificos atraves do nome em "pesquisar", clicar nos cards para acessar as descrições detalhadas sobre os pokemons e por fim, aumentar a quantidade de cards de pokemons em "carregar + pokemons" ou reduzir a quantidade em "carregar - pokemons".
