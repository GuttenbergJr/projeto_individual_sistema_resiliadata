<h1> ⇢ Projeto Resilia Módulo 2 – Sistema RESILIADATA </h1>

 <h2>🛠️ Descrição do projeto</h2
<p>- Realização da modelagem lógica de dados para o sistema RESILIADATA, que auxiliará na avaliação das tecnologias utilizadas pelas empresas parceiras e seus colaboradores.</p>

 <h2>📊 Modelo lógico</h2>
<img src="https://github.com/GuttenbergJr/projeto_individual_sistema_resiliadata/assets/114154174/a2380786-29e6-4505-888c-f485e8f93b06" alt="Print_Modelo_logico">
<p>Print do modelo lógico feito através do site lucidchart</p>

<h2>❔ Perguntas feitas sobre o modelo</h2>

<h3>1 - Quais são as entidades necessárias?</h3>
<p>Para esse banco de dados, as entidades(tabelas) necessárias são: empresa_parceira,tecnologia e colaborador</p>

<h3>2 - Quais são os principais campos e seus respectivos tipos?</h3>
<p>Os principais campos e seus tipos são:
Inteiro(int): id_empresa, id_tecnologia, id_colaborador, e qualquer outra chave primária ou estrangeira. 
Texto(varchar): Nome, Localização, Área, Cargo
</p>

<h3>3 - Como essas entidades estão relacionadas?</h3>
<p>as relações são:
 <ul>
<li>	Uma Empresa Parceira pode ter muitos Colaboradores.</li>
<li>Uma Empresa Parceira pode ter muitas relações com Tecnologias (e vice-versa).</li>
<li>Uma Tecnologia pode estar relacionada com muitas Empresas Parceiras.</li>
 </ul>
</p>

<h3>4 - Simule 2 registros para cada entidade.</h3>

<p>empresa_parceira</p>

| id_empresa | nome             | localizacao     |
| ---------- | ---------------- | --------------- |
| 1          | Microsoft        | São Paulo, SP   |
| 2          | Apple            | Xique-Xique, BA |



<p>tecnologia</p>

| id_tec        | nome            | area            |
| ------------- | --------------- | --------------- |
| 1             | Java            | Desenvolvimento |
| 2             | Python          | Desenvolvimento |

<p>colaborador</p>

| id_colaborador | nome           | cargo           | id_empresa |
| -------------- | -------------- | --------------- | ---------- |
| 1              | João Silva     | Desenvolvedor   | 1          |
| 2              | Maria Santos   | Analista        | 1          |
| 3              | Eliana Fernand.| Programador     | 2          |
| 4              | Ana Souza      | Engenheiro      | 2          |

<p>Relacionamento empresa_tecnologia</p>

| id_empresa | id_eecnologia |
| ---------- | ------------- |
| 1          | 1             |
| 1          | 2             |
| 2          | 2             |
| 2          | 1             |


