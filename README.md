![Banner Veredito](./mgt/BannerVeredito.png)

<br>

<p align="center">
    <a href="#objetivos"> Objetivos da Sprint </a> &nbsp |&nbsp &nbsp
    <a href="#entregas"> Entregas </a> &nbsp |&nbsp &nbsp
    <a href="#backlog"> Backlog da Sprint </a>  &nbsp |&nbsp &nbsp  
    <a href="#links"> Links úteis </a>
</p>

No início do desenvolvimento da aplicação de análise de precedente, o objetivo inicial foi assegurar o fluxo de cadastro e autenticação do sistema, e sobretudo, o envio de uma petição e a sugestão de possíveis precedentes relacionados a ela, utilizando pesquisa vetorial.

<span id="objetivos">

# 🎯 Objetivos da Sprint
Os requisitos funcionais atendidos nesta sprint foram:

- ✔️ **RFN04. Filtro de Precedentes:** A aplicação deve oferecer a opção de filtrar os precedentes sugeridos por tribunal e espécie de precedente, antes da busca. <br> <br>
- ✔️ **RFN08. Histórico de Petições:**  A aplicação deve manter um histórico detalhado de cada petição enviada ao sistema, incluindo a síntese gerada, os precedentes sugeridos e a data cujo a ação foi realizada. <br> <br>
- ✔️ **RFN10. Envio de Processo Jurídico:** O sistema deve permitir o envio de arquivos contendo processos jurídicos completos e inserir o contexto do tribunal, possibilitando o armazenamento e processamento das informações para análise posterior. <br> <br>
- ✔️ **RFN11. Classificação das Partes de um Processo:** Dado um processo jurídico completo, o sistema deve classificar automaticamente partes relevantes, como petição inicial, contestação, recurso, sentença/acórdão. <br> <br>
- ✔️ **RFN12. Geração de Minuta de Sentença:**  O sistema deve permitir a geração automática de uma minuta de petição inicial com base na descrição e nas informações fornecidas sobre o caso, contendo fatos estruturados, fundamentos jurídicos e precedentes relevantes destacados. <br> <br>
- ✔️ **RFN13. Geração de Minuta de Petição Inicial:** O sistema deve permitir que o usuário edite as minutas de petições iniciais geradas, possibilitando alterações no conteúdo antes da finalização do documento. <br> <br>
- ✔️ **RFN14. Edição de Minuta de Petição Inicial:** Dado um processo jurídico completo, o sistema deve classificar automaticamente partes relevantes, como petição inicial, contestação, recurso, sentença/acórdão. <br> <br>
- ✔️ **RFN15. Exportação de Minuta de Petição Inicial:** O sistema deve permitir a exportação das minutas de petições iniciais geradas em formato de arquivo, assim possibilitando seu download. <br> <br>

<br> 

<span id="entregas">

# 📲 Entregas
Durante esta sprint, o time enfrentou um grande desafio para cumprir todos os novos requisitos, porém tudo foi entregue com sucesso. 

### RF 10: Envio de Processo Jurídico
Como juiz, desejo enviar arquivos contendo processos jurídicos completos e inserir o contexto do tribunal, para que eu possa os analisar posteriormente

### RF 11: Classificação das Partes de um Processo
Como juiz, devo visualizar todas as partes do processo classificadas devidamente, para que eu possa visualizar de forma clara todo seu conteúdo facilmente.

### RF 12:  Geração de Minuta de Sentença
Como juiz, desejo gerar automaticamente uma minuta de sentença com base em um processo jurídico enviado, para que eu possa obter uma versão inicial do documento formalizando minha decisão e considerando as informações do processo.

### RF 13:  Geração de Minuta de Petição Inicial
Como advogado, desejo gerar automaticamente uma minuta de petição inicial a partir da descrição e das informações do caso, para que eu tenha uma versão inicial estruturada do documento jurídico

### RF 14:  Edição de Minuta de Petição Inicial
Como advogado, quero editar o conteúdo da minuta de petição inicial gerada, para que eu possa ajustar o documento antes de finalizá-lo

### RF 15:  Exportação de Minuta de Petição Inicial
Como advogado, quero exportar a minuta de petição inicial em formato de arquivo, para que eu possa realizar o download e utilizar o documento posteriormente.

### RF 04:  Filtro de Precedentes
Como juiz, quero filtrar a busca por precedentes por tribunal ou espécie para focar apenas nas decisões que são vinculantes ou do meu estado.

### RF 08:  Histórico de Petições
Como juiz, eu quero acessar o histórico das petições analisadas anteriormente para recuperar análises já feitas sem precisar reenviar os arquivos.


<br>

<span id="backlog">

# 📃 Backlog da Sprint

| **RFN** | **Rank** | **Prioridade** | **User Story** | **Estimativa** | **Sprint** | **Critérios de Aceitação** |
| ------- | -------- | -------------- | -------------- | -------------- | ---------- | -------------------------- |
| 10 | 8 | Alta | Como juiz, desejo enviar arquivos contendo processos jurídicos completos e inserir o contexto do tribunal, para que eu possa os analisar posteriormente. | 5 | 3 | - Suporte aos formatos `.docx`, `.pdf`, `.txt`;<br>- Confirmação visual de que o arquivo foi recebido com sucesso;<br>- Formulário para a coleta do contexto do tribunal, contendo: tribunal, instância, classe processual e área do direito;<br>- O campo de tribunal deve ser preenchido com base nos tribunais registrados no sistema;<br>- Mensagem de erro caso o arquivo não seja suportado. |
| 11 | 9 | Alta | Como juiz, devo visualizar todas as partes do processo classificadas devidamente, para que eu possa visualizar de forma clara todo seu conteúdo facilmente. | 13 | 3 | - Obrigatoriamente, todo processo deve ter uma petição inicial;<br>- Caso haja, devem ser classificados: contestação, recurso, sentença/acórdão. |
| 12 | 9 | Alta | Como juiz, desejo gerar automaticamente uma minuta de sentença com base em um processo jurídico enviado, para que eu possa obter uma versão inicial do documento formalizando minha decisão e considerando as informações do processo. | 8 | 3 | - Exportar a minuta em um arquivo PDF;<br>- Antes, solicitar as seguintes informações através de um formulário: descrição da decisão e precedentes sugeridos para serem selecionados;<br>- A minuta deve conter as informações necessárias para formalizar a decisão com base no processo enviado. |
| 13 | 10 | Alta | Como advogado, desejo gerar automaticamente uma minuta de petição inicial a partir da descrição e das informações do caso, para que eu tenha uma versão inicial estruturada do documento jurídico. | 8 | 3 | - As seguintes informações devem estar contidas: fatos estruturados, fundamentos jurídicos, tese central, pedidos e citações de precedentes com trechos destacados;<br>- Formulário para preencher a descrição do caso, pedindo: área do direito, pedidos principais, tribunal/UF, tese pretendida e upload de documentos. |
| 14 | 11 | Alta | Como advogado, quero editar o conteúdo da minuta de petição inicial gerada, para que eu possa ajustar o documento antes de finalizá-lo. | 3 | 3 | - Para cada campo da minuta, deve ser possível editar e salvar automaticamente;<br>- Nenhum campo pode ser enviado vazio;<br>- Mensagem de erro caso as regras de validações sejam quebradas. |
| 15 | 12 | Alta | Como advogado, quero exportar a minuta de petição inicial em formato de arquivo, para que eu possa realizar o download e utilizar o documento posteriormente. | 3 | 3 | - O arquivo deve ser gerado no formato DOCX;<br>- O arquivo deve ser salvo automaticamente na pasta de Downloads;<br>- O nome do arquivo deve permitir identificar a minuta exportada;<br>- Mensagem de aviso informando caso o download não possa ser realizado. |
| 04 | 14 | Média | Como juiz, quero filtrar a busca por precedentes por tribunal ou espécie para focar apenas nas decisões que são vinculantes ou do meu estado. | 5 | 3 | - Filtros funcionais para Tribunal, por exemplo: STJ, STF, TJSP;<br>- Filtros por Espécie, por exemplo: IRDR, Recurso Repetitivo;<br>- Os filtros devem ser aplicados antes da busca de precedentes. |
| 08 | 15 | Baixa | Como juiz, eu quero acessar o histórico das petições analisadas anteriormente para recuperar análises já feitas sem precisar reenviar os arquivos. | 3 | 3 | - Exibir a data e hora em que o processo foi realizado;<br>- Listar nome do arquivo, resumo gerado e precedentes sugeridos, com os indicadores de aplicabilidade e síntese explicativa. |                                                                                                                         |


<span id="links">

# 🔗 Links úteis

- Tags geradas em cada repositório que simbolizam o fim da 3ª sprint: <br>
 [v3.0.0 BACKEND](https://github.com/SkyFlyTeam/veredito-backend/releases/tag/v3.0.0) <br>
 [v3.0.0 FRONTEND](https://github.com/SkyFlyTeam/veredito-frontend/releases/tag/v3.0.0)
<br>

