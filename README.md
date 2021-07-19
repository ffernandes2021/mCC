# mCC

## Sobre
   
   Este é um projeto acadêmico chamado **mCC**, cuja sigla significa **Materiais Complementares Compartilhados**. Nele proponho o desenvolvimento de uma plataforma web, na qual é possível cadastrar, excluir, listar e compartilhar mCC's, estes, por sua vez, formados por mídias como vídeos, imagens, artigos, livros, links, filmes, áudios, entre outros.

   Este é um projeto em **andamento**. Ele é semanalmente incrementado e compartilhado aqui no GitHub.

   É um projeto **open source**, sob a licença [**GNU GPLv3**](https://www.gnu.org/licenses/gpl-3.0.pt-br.html). Assim, pode ser baixado, modificado, mas distribuído apenas sob a mesma licença.
   
   É um projeto que envolve inúmeras tecnologias, tais como tecnologias front-end, back-end, base de dados NoSQL e chamadas REST API's. Assim sendo, comentarei todos os commits aqui mesmo com vocês para um melhor entendimento do projeto, bem como sua evolução.

## Commit

   **Commit 1:**

   - Texto inicial do README.md; 
   - Desenvolvimento de interface (estática) inicial; 
   - Desenvolvimento de componentes de interface (dinâmicos) com jQuery (JS); 
   - GET de blogs e posts do Blogger, utilizando requisições AJAX/JSON com jQuery para REST API (Blogger API 3.0).

   **Commit 2:**
   
   - Atualização do README.md; 
   - GET de vídeos e playlists do YouTube, utilizando requisições AJAX/JSON com jQuery para REST API (YouTube Data API 3.0).

   **Commit 3:**

   - Atualização do README.md;
   - GET de vídeos e playlists do Vimeo, utilizando requisições AJAX/JSON com jQuery para REST API (oEmbed);
   - GET de vídeos e playlists do Dailymotion, utilizando requisições AJAX/JSON com jQuery para REST API (Dailymotion Data API).

   **Commit 4:**
   
   - Atualização do README.md; 
   - GET de modelos e coleções do Sketchfab, utilizando requisições AJAX/JSON com jQuery para REST API (Sketchfab Data API 3.0).

   **Commit 5:**
   
   - Atualização do README.md; 
   - GET de artigos do PLOS - Public Library of Science, utilizando requisições AJAX/JSONP com jQuery para REST API (PLOS Search API);
   - GET de artigos do bioRxiv, utilizando requisições AJAX/JSON com jQuery para REST API (bioRxiv API).

   **Commit 6:**

   - Atualização do README.md;
   - Otimização de código: substituição dos scripts procurar por uma única function search;
   - GET de artigos do ERIC - Education Resources Information Center, utilizando requisições AJAX/JSON com jQuery para REST API (ERIC API);
   - GET de artigos do Semantic Scholar, utilizando requisições AJAX/JSON com jQuery para REST API (Semantic Scholar API).

   **Commit 7:**

   - Atualização do README.md;
   - Atualização de brands;
   - GET de artigos e periódicos do DOAJ - Directory of Open Access Journals, utilizando requisições AJAX/JSON com jQuery para REST API (DOAJ API 2.0);
   - GET de dado, ocorrência e espécie do GBIF - Global Biodiversity Information Facility, utilizando requisições AJAX/JSON com jQuery para REST API (GBIF API 1.0).

   **Commit 8:**

   - Atualização do README.md;
   - Atualização sugerida por @bitebait para mensagem de erro;
   - GET de livros do Google Books, utilizando requisições AJAX/JSON com jQuery para REST API (Google Books API 1.0).
   - GET de itens do WDL - World Digital Library, utilizando requisições AJAX/JSON com jQuery para REST API (WDL API (IIIF Presentation 2.0)).
   - Implementação de ferramenta de zoom em elementos do tipo imagem, utilizando o plugin jQuery Panzoom 3.2.2.

## Tecnologias

   **Front-end:**
   
   - **Linguagem:** HTML 5, CSS 3 e JSP (Scriptlets e JSTL)
   - **Fonte:** Font Awesome 5.15.3 e Google Fonts (Carrois Gothic)
   - **Framework:** Twitter Bootstrap 3.4.1
   - **Biblioteca JS:** jQuery 3.4.1 e jQuery Panzoom 3.2.2
   - **API e relacionados:** XMLHttpRequest/AJAX, JSON/JSONP, Blogger API 3.0, YouTube Data API 3.0, oEmbed, Dailymotion Data API, Google Books API 1.0, ERIC API, Semantic Scholar API, DOAJ API 2.0, PLOS Search API, bioRxiv API, GBIF API 1.0, WDL API (IIIF Presentation 2.0) e Sketchfab Data API 3.0.
   - **Browser:** Google Chrome 90.0.4430.93 (64 bits) e Mozilla Firefox 88.0 (64 bits)
   
   **Back-end, Database, Infra e Outros:**
   
   - **Java Web:** JavaBeans, DAO e Servlet API 2.5 (MVC Pattern)
   - **Descritor:** web.xml
   - **Database:** MongoDB Server e Shell 4.4.3
   - **Server:** Apache Tomcat 8.0.27.0
   - **Builder:** Apache Ant 1.9.7
   - **Platform:** Oracle Java EE 7 (OpenJDK 8)
   - **IDE:** Apache NetBeans IDE 8.2
   - **OS:** Canonical Linux Ubuntu 21.04
   
## Instalação

   1. Instale o [OpenJDK 8+](https://openjdk.java.net/) (ou [JDK 8+](https://www.oracle.com/java/), se preferir) e defina as variáveis de ambiente do Java;
   2. Instale o [NetBeans IDE 8.2](https://netbeans.apache.org/). Inclua na instalação da IDE o servidor [Apache Tomcat](http://tomcat.apache.org/) e defina as variáveis de ambiente do Tomcat;
   3. Instale o [MongoDB 4.4.3.](https://www.mongodb.com/). A instalação inclui o Server e o Shell. Lembre sempre de startar o database antes de executar a aplicação;
   4. Instale um browser de sua preferência;
   5. Baixe o zip do GitHub, descompacte e abra o projeto no NetBeans IDE.
   6. No NetBeans para construir (builder), clique sobre o projeto, em seguida pressione F11. Para limpar e construir, pressione Shift + F11. Para executar (run), pressione F6. Para executar com depuração (debugger), pressione Ctrl + F5.
    8. Se tudo correr bem, a aplicação iniciará em um browser (definido na IDE), cuja URL segue a notação: **http://[IP]:[PORTA]/[CONTEXTO]**.
    
## API keys

   Ao fazer o download deste projeto, por favor, obtenha suas próprias API Keys nos links abaixo e substitua pelos valores correspondentes no arquivo **script.js**. 
   
   - Blogger ==> [Blogger API 3.0](https://developers.google.com/blogger)
   - YouTube ==> [YouTube Data API 3.0](https://developers.google.com/youtube/v3)
