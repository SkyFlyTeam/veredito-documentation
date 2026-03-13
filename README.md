![Banner Veredito](./mgt/BannerSmartFarm.png)

<br>

<p align="center">
    <a href="#sobre"> Sobre o projeto</a> &nbsp |&nbsp &nbsp
    <a href="#entregas"> Entregas </a> &nbsp |&nbsp &nbsp
    <a href="#tecnologias"> Tecnologias utilizadas </a> &nbsp |&nbsp &nbsp  
    <a href="#estrutura"> Estutura do projeto </a> &nbsp |&nbsp &nbsp  
    <a href="#backlog"> Backlog do produto </a> &nbsp |&nbsp &nbsp
    <a href="#autores"> Equipe </a> &nbsp |&nbsp &nbsp
    <a href="#links"> Links Úteis </a> 
</p>

<span id="sobre">

# 📑 Sobre o projeto

---

<br>

# Requisitos funcionais

- **RFN01. Envio de Petição:** A aplicação deve permitir o envio de um arquivo contendo uma petição inicial.

- **RFN02. Geração de Resumo:** A aplicação deve gerar um resumo com as principais informações extraídas da petição inicial, como solicitação e tese, facilitando a compreensão e o direcionamento para a pesquisa de precedentes.

- **RFN03. Sugestão de Precedentes:** Dado uma petição inicial, a aplicação deverá sugerir precedentes judiciais que possam ser utilizados no caso, contendo dados estruturados como tribunal/origem, tema, enunciado, status, tese firmada, espécie e data de atualização.

- **RFN04. Filtro de Precedentes:** Na listagem dos precedentes sugeridos, a aplicação deve oferecer a opção de filtrar por tribunal, espécie de precedente e status.

- **RFN05. Cálculo de Similaridade:** Para cada precedente sugerido, a aplicação deve calcular e exibir um percentual de similaridade ou a probabilidade de o precedente ser aplicado ao caso concreto.

- **RFN06. Classificação de Aplicabilidade:** Para cada precedente sugerido, a aplicação deve rotular cada resultado com uma indicação clara: "Aplicável", "Possivelmente aplicável" ou "Não aplicável".

- **RFN07. Geração de Síntese Explicativa:** Para cada precedente sugerido, a aplicação deve gerar um texto curto explicando a relação lógica/jurídica entre o precedente encontrado e a petição inicial do usuário.

- **RFN08. Histórico de Petições:** A aplicação deve manter um histórico detalhado de cada petição enviada ao sistema, incluindo a síntese gerada, os precedentes sugeridos e a data cujo a ação foi realizada.

- **RFN09. Cadastro de Usuários:** A aplicação deve permitir o registro de um novo usuário, solicitando informações como nome completo, e-mail e senha.


<span id="backlog">

# 🎯 Backlog do Produto

| RFN | Rank | Prioridade | User story | Estimativa | Sprint | Critérios de aceitação |
|-----|------|------------|------------|------------|--------|-------------------------|
| 01 | 1 | Alta | Como juiz, quero fazer o upload do arquivo da minha petição inicial para que o sistema possa analisar os fatos envolvidos. | 5 | 1 | - Suporte aos formatos .docx, .pdf, .txt <br> - Confirmação visual de que o arquivo foi recebido com sucesso. <br> - Mensagem de erro caso o arquivo não seja suportado. |
| 09 | 2 | Alta | Como novo usuário, desejo poder me cadastrar para obter acesso ao sistema e poder utilizar todas as suas funcionalidades. | 3 | 1 | - Campos obrigatórios: Nome completo, e-mail válido e senha segura. <br> - A senha deve conter no mínimo 8 dígitos, um caractere especial e um número <br> - O sistema deve impedir cadastros com e-mails existentes. |
| 03 | 3 | Alta | Como juiz, desejo receber sugestões de precedentes para identificar quais podem auxiliar na minha tomada de decisão. | 13 | 1 | - Listar tribunal, tema, enunciado, status e tese firmada, data de atualização e espécie. |
| 05 | 4 | Alta | Como juiz, desejo que cada precedente sugerido apresente um percentual de similaridade com o caso para que eu possa julgar quais podem ser utilizados. | 5 | 2 | - Exibir em porcentagem (%) o índice de similaridade semântica |
| 06 | 5 | Alta | Como juiz, desejo que cada precedente sugerido apresente um indicador claro de aplicabilidade no caso, para que eu possa facilmente se ele é relevante para a minha decisão. | 3 | 2 | - Classificar entre: "Aplicável", "Possivelmente aplicável" ou "Não aplicável" <br> - Mostrar uma legenda com o parâmetro de classificação |
| 07 | 6 | Alta | Como juiz, eu quero ler uma síntese explicativa da relação entre o precedente e minha petição para entender o porquê daquela sugestão e usá-la na minha fundamentação. | 8 | 2 | - Texto curto, no máximo um parágrafo <br> - Deve descrever a correlação entre o precedente e a petição enviada |
| 02 | 7 | Média | Como juiz, quero visualizar um resumo automático da petição enviada para que eu possa identificar rapidamente os que podem auxiliar na minha tomada de decisão. | 5 | 2 | - O resumo deve destacar claramente a "Tese Jurídica" e a "Solicitação/Pedido" <br> - No máximo um parágrafo, escrito de forma clara e concisa. |
| 04 | 8 | Média | Como juiz, quero filtrar a lista de precedentes sugeridos por tribunal, espécie ou status para focar apenas nas decisões que são vinculantes ou do meu estado. | 5 | 3 | - Filtros funcionais para Tribunal (ex: STJ, STF, TJSP) <br> - Filtros por Espécie (ex: IRDR, Recurso Repetitivo). <br> - Filtros por Status (ex: Transitado em Julgado). |
| 08 | 9 | Baixa | Como juiz, eu quero acessar o histórico das petições analisadas anteriormente para recuperar análises já feitas sem precisar reenviar os arquivos. | 3 | 3 | - Exibir a data e hora em que o processo foi realizado <br> - Listar nome do arquivo, resumo gerado e precedentes sugeridos, com os indicadores de aplicabilidade e síntese explicativa. |

<br>

<span id="entregas">

# 🏁 Entregas de Sprints

Cada entrega foi realizada a partir da criação de uma **tag** em cada repositório, além da criação de uma branch neste repositório com um relatório completo de tudo o que foi desenvolvido naquela sprint.
| Sprint | Previsão de entrega | Status | Histórico |
|:--:|:----------:|:-------------------|:-------------------------------------------------:|
| 01 | 08/09/2025 a 28/09/2025 | Concluída | [Ver relatório](https://github.com/SkyFlyTeam/Atmos-documentation/tree/sprint1) |
| 02 | 06/10/2025 a 26/10/2025 | Concluída | [Ver relatório]() |
| 03 | 03/11/2025 a 23/11/2025 | Concluída |  [Ver relatório]()|

<br />

<span id="tecnologias">

# 🛠️ Tecnologias Utilizadas

As seguintes ferramentas, linguagens, bibliotecas e tecnologias foram usadas na construção do projeto:

![Typescript](https://img.shields.io/badge/TypeScript-20232A?style=for-the-badge&logo=typescript&logoColor=007ACC)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Node.js](https://img.shields.io/badge/Node%20js-20232A?style=for-the-badge&logo=nodedotjs&logoColor=339933)
![Next](https://img.shields.io/badge/Nextjs-20232A?style=for-the-badge&logo=next.js&logoColor=23ED8B00)
![Express](https://img.shields.io/badge/Expressjs-20232A?style=for-the-badge&logo=express&logoColor=23ED8B00)
![Arduino](https://img.shields.io/badge/Arduino-20232A?style=for-the-badge&logo=arduino&logoColor=00979D)
![Docker](https://img.shields.io/badge/docker-20232A?style=for-the-badge&logo=docker&logoColor=87CEEB)
![MySQL](https://img.shields.io/badge/mysql-20232A?style=for-the-badge&logo=mysql&logoColor=4682B4)
![MongoDB](https://img.shields.io/badge/MongoDB-20232A?style=for-the-badge&logo=mongodb&logoColor=234ea94b)
![CSS3](https://img.shields.io/badge/css3-20232A?style=for-the-badge&logo=css3&logoColor=4682B4)
![Figma](https://img.shields.io/badge/figma-20232A?style=for-the-badge&logo=figma&logoColor=800000)
![Discord](https://img.shields.io/badge/Discord-20232A?style=for-the-badge&logo=discord&logoColor=61DAFB)
![Jira](https://img.shields.io/badge/Jira-20232A?style=for-the-badge&logo=Jira&logoColor=4169E1)

<br>

# Manual de Usuário e Instalação

O manual da aplicação pode ser acessado através do seguinte: https://frill-walkover-a45.notion.site/ATMOS-Manual-do-usu-rio-2a2a1b635ed68083be75ea39f2c097fc?source=copy_link


<span id="estrutura">

# Estrutura do Projeto

![Estrutura](./mgt/Arquitetura%20do%20projeto.png)


## Como executar o projeto

1 . Clone os repositórios:
- [Necessita do git instalado](https://git-scm.com/downloads)
```
git clone https://github.com/SkyFlyTeam/Atmos-frontend.git
git clone https://github.com/SkyFlyTeam/Atmos-backend.git
```

2 . Configurando e executando backend: 
- [Necessita do node.js 20.17](https://nodejs.org/pt)
- [Necessita do postgres 18](https://hub.docker.com/_/postgres)

Na pasta do backend:
- Crie um arquivo chamado ".env" e insira as seguintes informações:
```
DB_NAME='Nome da database do banco'
DB_USER='postgres'
DB_PASSWORD='Senha do banco de dados'
DB_HOST='Ip do bando de dados'
DB_PORT=Porta do banco de dados (5432 por padrão)
```

Instale as depêncencias do projeto:
```
npm install
```

Inicie o backend:
```
npm start
```

3 . Configurando e executando o frontend
- [Necessita do node.js 20.17](https://nodejs.org/pt)

Na basta do frontend, execute:

Para instalar as dependências do projeto:
```
npm install
```

Para iniciar o projeto:
```
npm run dev
```


## DoR (Definition of Ready) 

- **User Stories completas:** Todos os requisitos descritos em User Stories planejadas para caber na sprint.
- **Tarefas detalhadas e atribuídas:** Cada User Story deve ter ao menos uma task detalhada e atribuída a um responsável.
- **Critérios de aceitação definidos:** Cada User Story deve ter critérios de aceitação bem estabelecidos.
- **Estimativas definidas:** Todas as User Stories devem ter uma estimativa de esforço/tamanho feita pelo time
- **Wireframe/Mockup aprovados:** O cliente deve ter validado e aprovado os protótipos visuais.
- **Modelo de dados finalizado:** Estrutura de dados completamente definida e documentada.
- **Testes de aceitação definidos:** Incluindo testes sugeridos pelo cliente e testes de aceitação.
- **Ambiente de desenvolvimento pronto:** O time deve ter acesso a todos os ambientes, ferramentas e permissões necessárias.

<br>

## DoD (Definition of Done) 

- **Critérios de aceitação validados:** Todos os critérios de aceitação foram atendidos e verificados com testes apropriados.
- **Execução de testes adequados:** Testes unitários, de integração e de aceitação foram realizados para garantir a estabilidade e funcionamento correto da aplicação.
- **Código-fonte completo e padronizado:** O código está 100% implementado, refatorado e segue as boas práticas e padrões de qualidade definidos.
- **Commits organizados e documentados:** Os commits seguem a nomenclatura acordada, são claros, segmentados e possuem histórico bem documentado.
- **Guia de instalação detalhado:** A documentação de instalação é clara e completa, permitindo que qualquer usuário ou desenvolvedor configure e execute a aplicação sem dificuldades.
- **Manual do usuário disponível:** Um manual foi criado para orientar o cliente sobre o funcionamento da aplicação.

<br>

<span id="links">

# 🔗 Links úteis
- [Modelo lógico do Banco de Dados](https://drive.google.com/file/d/12QT37gpqIwlUWXJmurE72GGgu8Mt4sjX/view?usp=sharing)
- [Product backlog detalhado](https://docs.google.com/document/d/1vjvclXg3ROMe8RTefvWXqM33MQ0H1MwmVwH9GwyZX0k/edit?usp=sharing)
- [Wireframe da aplicação](https://www.figma.com/design/I2ve5ty4HGnBXGKYEpamqh/Atmos?node-id=0-1&p=f&t=etRZoSKjtiXJjEUf-0)
- [Arquitetura do projeto](https://drive.google.com/file/d/1Z24zyW6E9l9ZoS8rbZVUWsgV5O73bVz_/view?usp=sharing)
- [Fluxo de trabalho no git](https://docs.google.com/document/d/1S3pPiDfFxXogIJifizV-DtknxKtDUQphnejfTrRW8t8/edit?usp=sharing)
- [Estratégia de branch](https://drive.google.com/file/d/18F6FAJzD4ICA4dIlYwwmbBYVurj4LQJG/view?usp=sharing)
<br>


<span id="autores">

# 👥 Equipe


|    Função     | Nome                                  |                                                                                                                                                      LinkedIn & GitHub                                                                                                                                                      |
| :-----------: | :------------------------------------ | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: |
|  Scrum Master  | Sarah Montuani Batagioti               |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/sarahbatagioti/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/SarahBatagioti)   |
| Team Member   | André Salerno |      [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/andresalerno/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/andresalerno)     |
|  Team Member  | Brenno Rosa Lyrio de Oliveira               |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/brennolyrio/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/BrennoLyrio)   |
| Product Owner   | Eric Lourenço Mendes da Silva      |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)]() [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/ericloumendes)        |
|  Team Member  | Gustavo Muraoka Silva                 |         [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/gustavo-muraoka-4256721ba/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gustavomuraoka)        |
|  Team Member  | Karen de Cássia Gonçalves     |           [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/karen-cgonçalves) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/karengoncalves8)   |
|  Team Member  | Guilherme dos Santos Benedito               |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/guilherme-benedito/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/gui-benedito)   |
|  Team Member  | Arthur Johannes Rodrigues Peres y Peres              |   [![Linkedin Badge](https://img.shields.io/badge/Linkedin-blue?style=flat-square&logo=Linkedin&logoColor=white)](https://www.linkedin.com/in/ajperes/) [![GitHub Badge](https://img.shields.io/badge/GitHub-111217?style=flat-square&logo=github&logoColor=white)](https://github.com/ajperes)   |
