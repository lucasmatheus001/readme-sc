<h1 align="center">
    # Web Scrapping - BACKEND (NODE)
</h1>
<h1 align="center">
   (Login,captura de dados e geração de arquivo "csv" - AGESPISA)
</h1>
<p align="center"> Práticas desenvolvidas  💻 </p>

<p align="center">
 <a href="#objective">Objetivos</a> •
 <a href="#char">Características</a> •
 <a href="#run">Como Executar</a> •
 <a href="#dep">Dependências</a> •
</p>

<h4 align="center"> 
	🎨 AGESPISA
</h4>

<h2 id="objective" > 🎯 Objetivos </h2>
<p align="justify">
  Realizar login automatizado no site do ministério da Fazenda, em seguida buscar e coletar informações , por meio de web scrapping referentes a: (débitos, dados previdenciários e não previdenciários) e gerar ao final um arquivo "csv" com os dados coletados.
</p>

<h2 id="char" >Principais características Técnicas</h2>

* Realizar Login
* Web Scrapping de dados 
* geração de arquivo csv de dados
* manipulação de arquivos gerados

<h2 id="run" >Como Executar</h2>

```bash
# Clonar o repositório
$ git clone https://github.com/lucasmatheus001/desafio-frontend-pleno-main

# Vá para a pasta do repositório
$ cd nome repositorio

# Para instalar as dependências
$ npm install

# Iniciar aplicação web
$ npm start

# Acesse o seguinte link para acessar o arquivo .Json retornado da API.
http://localhost:8080

# Acesse o seguinte link para acessar os arquivo .Json retornados da API.
http://localhost:8080/arquivos/

# Acesse o seguinte link para realizar o download de um arquivo específico, passando como parâmetro seu nome na URL .
http://localhost:8080/files/nomedoarquivo
```

<h2 id="dep" >Dependências</h2>

* [Node js](https://nodejs.org/dist/latest-v14.x/docs/api/)
* [Puppeteer](https://pptr.dev)
* [Crawler](https://www.algolia.com/doc/tools/crawler/getting-started/overview/)
* [Fetch](https://developer.mozilla.org/pt-BR/docs/Web/API/Fetch_API/Using_Fetch)
* [Cors](https://developer.mozilla.org/pt-BR/docs/Web/HTTP/CORS)
* [Express](https://devdocs.io/express/)
* [Fs](https://nodejs.org/api/fs.html)
* [Objects-to-csv](https://www.npmjs.com/package/objects-to-csv)
