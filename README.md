Descrição do Projeto
O Sistema de Gerenciamento é um banco de dados relacional desenvolvido para gerenciar informações de departamentos, funcionários, projetos e tarefas de uma organização. Ele permite:

Gerenciar departamentos e suas localizações.
Associar funcionários aos departamentos e definir cargos e salários.
Gerenciar projetos associados a departamentos.
Monitorar tarefas relacionadas aos projetos e funcionários.
Objetivos
Fornecer uma estrutura escalável para gerenciar organizações.
Permitir consultas eficientes para insights sobre departamentos, funcionários, projetos e tarefas.
Apoiar decisões estratégicas por meio de visualizações de dados e relatórios.
Requisitos de Sistema
Sistema Operacional: Windows/Linux/MacOS
Banco de Dados: MySQL 8.0+
Python: 3.8+
Bibliotecas Python: Listadas no requirements.txt.
Instruções de Execução

1. Clone este repositório:
   git clone https://github.com/seuprojeto/sistemadegerenciamento.git
   
2. Navegue até o diretório
   cd sistemadegerenciamento
   
3. Configure o ambiente Python:
   python -m venv env
source env/bin/activate   # Linux/Mac
env\Scripts\activate      # Windows

4. Instale as dependências
   pip install -r requirements.txt

5. Execute os scripts:
Criar e popular o banco de dados: SRC/create_database.sql e SRC/insert_data.sql.
Executar consultas: SRC/queries.sql.
Resultados Principais
Os gráficos gerados estão disponíveis em results/graphs. Exemplos:

Distribuição de salários por departamento.
Progresso dos projetos em gráfico de pizza.
Status das tarefas em gráfico de barras.

