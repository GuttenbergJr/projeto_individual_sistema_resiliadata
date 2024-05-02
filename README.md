<h1> ⇢ Projeto Resilia Módulo 2 – Sistema RESILIADATA </h1>

🛠️ <h2>Descrição do projeto</h2
<p>- Realização da modelagem lógica de dados para o sistema RESILIADATA, que auxiliará na avaliação das tecnologias utilizadas pelas empresas parceiras e seus colaboradores.</p>

📊 <h2>Modelo lógico</h2>
<img src="https://github.com/GuttenbergJr/projeto_individual_sistema_resiliadata/assets/114154174/a2380786-29e6-4505-888c-f485e8f93b06" alt="Print_Modelo_logico">
<p>Print do modelo lógico feito através do site lucidchart</p>

❔ <h2>Perguntas feitas sobre o modelo</h2>

<h3>Quais são as entidades necessárias?</h3>
<p>Para esse banco de dados, as entidades(tabelas) necessárias são: empresa_parceira,tecnologia e colaborador</p>

<h3>Quais são os principais campos e seus respectivos tipos?</h3>
<p>Os principais campos e seus tipos são:
Inteiro(int): id_empresa, id_tecnologia, id_colaborador, e qualquer outra chave primária ou estrangeira. 
Texto(varchar): Nome, Localização, Área, Cargo
</p>

<h3>Como essas entidades estão relacionadas?</h3>
<p>as relações são:
•	Uma Empresa Parceira pode ter muitos Colaboradores.
•	Uma Empresa Parceira pode ter muitas relações com Tecnologias (e vice-versa).
•	Uma Tecnologia pode estar relacionada com muitas Empresas Parceiras.
</p>

<h3>Simule 2 registros para cada entidade.</h3>
1. **Empresa Parceira**:

| ID_Empresa | Nome             | Localizacao     |
|------------|------------------|-----------------|
| 1          | Empresa A        | São Paulo, SP   |
| 2          | Empresa B        | Rio de Janeiro  |

