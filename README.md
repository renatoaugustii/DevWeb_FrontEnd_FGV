# DevWeb_FrontEnd_FGV

Nesta atividade, você deve desenvolver um cardápio de produtos on-line com foco nos aspectos de front-end.
Em cada etapa do desenvolvimento do projeto, você deve aplicar os assuntos abordados ao longo da disciplina. Sendo assim, você irá elaborar a estrutura das páginas em HTML, definir os estilos em CSS, tratar eventos com JavaScript e adequar o código utilizando um framework de mercado.

## Menu de Navegação
<details>

<summary>Conteudo</summary>
<ol>
<li><a href="#Sobre">Sobre</a></li>
<li><a href="#funcionalidades">Funcionalidades</a></li>
<li><a href="#Pré-Requisitos">Pré-Requisitos</a></li>
<li><a href="#Dependências e Libs Instaladas">Dependências e Libs Instaladas</a></li>
<li><a href="#Contribuição">Contribuição</a></li>
<li><a href="#licença">Licença</a></li>
</ol>    
</details>

## Sobre

### Contextualização
A loja de ferramentas "Ferramentas Essenciais" solicitou à sua equipe de desenvolvedores a criação do seu catálogo on-line.
O proprietário da "Ferramentas Essenciais" deseja que, no catálogo, os clientes possam pesquisar produtos pelo nome ou categoria (ferramentas elétricas, manuais, acessórios, etc.). Na lista de produtos, é desejado que os clientes visualizem o preço e uma foto do produto (quando disponível). Além disso, ao clicar em um produto, os clientes devem ser capazes de ver os detalhes completos, incluindo uma descrição abrangente.

### Tarefa
Utilizando o Replit, um ambiente de desenvolvimento on-line, gratuito e colaborativo para programar no navegador, você deve desenvolver o catálogo on-line da loja de ferramentas "Ferramentas Essenciais", seguindo as especificações fornecidas para o projeto. 

### Desenvolvimento
O desenvolvimento inclui as seguintes etapas:

1. Estruturação do layout das páginas com HTML; '1° Commit' : "31d79db"
    - Criação do arquivo Readme.md
    - Criação do arquivo index.html que será o arquivo incial desse projeto.
    - Criação das pastas para organizar as imagens. Subpastas com imagens das ferramentas e imagem do favicon e logotipo.
    - Criação da pasta css para os estilos iniciais. Criei inicialmente apenas para ter um entregável minimamente agradável quanto ao uso de estilos.
    - No HTML criaçao de um cabeçalho simples apenas com a logo e o nome da loja. Criação de tabelas para apresentar as ferramentas e suas devidas contruções.
    - Criação de página auxiliar para 1 único produto apenas como teste de navegação. A ideia no futuro é ter apenas 1 única página para apresentar os produtos.

2. Aplicação da folha de estilos; '2° Commit' : 2b754ad
    - Importação dos links CDN do Bootstrap, estilos e javascript.
    - Importacao do CDN de icones do bootstrap.
    - Imagens das ferramentas adicionadas ao template HTML.
    - Importação de modelo carrousel do Botstrap.
    - Importação de fonte ROBOTO para body.
    - Inserindo imagens para o Banner do carrousel.
    - Criação da página detalhe, que será responsável por exibir as ferramentas em páginas individualizadas.
    - Todos os links da página index levam para a página detalhe de uma única ferramenta, irei deixar dinâmico com o recurso do Vue.js.

3. Montagem de lista de feerramentas via arquivo .JSON; '3° Commit': efd6ab0
    -  Criação do arquivo Json com os devidos links das imagens e descrição das ferramentas.
    -  Adicionado o JavaScript responsavel em ler o Json e manipular o DOM com os valores capturados.
    - A pesquisa das ferramentas será realizada pelo Vue.js no proximo commit.

4. Filtragem dos produtos via busca por palavras-chave ou categorias. '4° Commit': c53c606
    - Inserindo Vue via CDN.
    - Criação do script para renderização do Json dentro do Html utilizando o Vue
    - Criação da tratativa de erros do arquivo json.
    - Criação da página detalhes.html com interatividade via url.
    - Alterado arquivo json inserindo os ids dos produtos.
    - Filtro realizado utilizando v-model.
    - Projeto Finalizado.

## Funcionalidades

#### Listagem de Produtos: 
- Exibir uma lista de produtos disponíveis na loja, categorizados por tipos de ferramentas (elétricas, manuais, de jardinagem, etc.).

#### Detalhes do Produto:
- Ao clicar em um produto, exibir informações detalhadas, como descrição, preço, imagens e especificações.

#### Barra de Pesquisa: 
- Permitir aos usuários pesquisar produtos por nome ou palavra-chave.

#### Filtros por Categoria: 
- Possibilitar filtrar produtos por categorias específicas, facilitando a navegação.

## Pré-requisitos

### Conhecimento Básico de HTML, CSS e JavaScript
1. HTML: Para estruturar o conteúdo da página, como os elementos que compõem a lista de produtos, detalhes do produto, etc.
2. CSS: Para estilizar e dar aparência visual à loja, garantindo um design atraente e responsivo.
3. JavaScript: Para interações dinâmicas na página, como exibir detalhes de produtos, filtrar itens, etc.

### Compreensão do Vue.js
1. Vinculação de Dados: Compreender a forma como o Vue.js lida com a vinculação de dados entre a lógica do aplicativo e a interface do usuário.
2. Componentes: Saber como criar e utilizar componentes reutilizáveis para construir a interface.
3. Manipulação do DOM: Ter conhecimento sobre como o Vue.js manipula o DOM de forma reativa.

### Ambiente de Desenvolvimento
1. Editor de Código: Usar um editor de código de sua preferência, como Visual Studio Code, Sublime Text, Atom, entre outros.
2. Navegador Web: Ter um navegador atualizado (Chrome, Firefox, etc.) para testar e visualizar o front-end.

### Design Responsivo e UX/UI
1. Noções Básicas de Design Responsivo: Compreender como criar interfaces que se ajustem a diferentes tamanhos de tela.
2. Experiência do Usuário (UX): Ter uma compreensão básica de como criar uma experiência de usuário intuitiva e agradável.

### Boas Práticas e Documentação
1. Organização e Boas Práticas de Código: Conhecer boas práticas de codificação para manter o código limpo, legível e escalável.
2. Documentação e Pesquisa: Saber como buscar informações em documentações e recursos online para solucionar problemas ou aprender novas técnicas.

## Dependências e Libs Instaladas
1. Instalação do Vuejs poderá ser feito através do link: (https://vuejs.org/guide/introduction.html)


### Participante: 
|name|course|
| -------- | -------- |
|Renato Augusto|Desenvolvimento Web FGV|


## Contribuição

Agradecemos seu interesse em contribuir para o projeto! Siga as diretrizes abaixo para participar:

1. Faça um fork do projeto.
2. Crie uma branch para sua contribuição: `git checkout -b minha-contribuicao`.
3. Faça as alterações desejadas.
4. Commit suas alterações: `git commit -m "Minha contribuição"`.
5. Push para o repositório remoto: `git push origin minha-contribuicao`.
6. Abra um pull request descrevendo suas alterações.

Também incentivamos discussões e sugestões através das [issues](https://github.com/seu-usuario/seu-repositorio/issues).

## Licença

Este projeto está licenciado sob a <a href="https://opensource.org/licenses/MIT"><img src="https://img.shields.io/badge/Licen%C3%A7a-MIT-blue.svg" alt="Licença MIT"></a>.

Você é livre para utilizar este código em seus projetos, inclusive projetos comerciais. A única exigência é que você mantenha a atribuição de autoria.


