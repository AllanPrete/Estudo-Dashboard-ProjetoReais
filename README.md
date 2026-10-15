📊 Estudo de Dashboards

Repositório dedicado ao estudo, à prática e à documentação de boas práticas na criação de dashboards e visualização de dados.

📌 Sobre o projeto

Este repositório reúne meus estudos sobre construção de dashboards, desde a coleta e tratamento dos dados até a entrega de painéis claros, interativos e orientados à tomada de decisão.

A ideia é documentar o processo de aprendizado, os projetos desenvolvidos e as lições aprendidas ao longo do caminho.

🎯 Objetivos
Entender os princípios de visualização de dados e design de dashboards
Praticar ETL: extração, tratamento e modelagem de dados
Criar indicadores (KPIs) relevantes para o negócio
Comparar ferramentas e abordagens de BI
Construir um portfólio com projetos reais e reproduzíveis
🛠️ Tecnologias e ferramentas
Categoria	Ferramentas
Visualização / BI	Power BI, Tableau, Looker Studio
Linguagens	Python, SQL, DAX
Bibliotecas	Pandas, Numpy Plotly, Streamlit, Matplotlib, Lambda e Seaborn
Banco de dados	PostgreSQL, SQLite, Excel/CSV, MySQL
Versionamento	Git e GitHub

✏️ Ajuste a tabela de acordo com as ferramentas que você realmente usa.

📁 Estrutura do repositório
estudo-dashboard/
│
├── data/
│   ├── raw/              # Dados brutos (originais)
│   └── processed/        # Dados tratados
│
├── notebooks/            # Análises exploratórias (Jupyter)
├── sql/                  # Consultas e scripts SQL
├── dashboards/           # Arquivos .pbix, .twbx e apps Streamlit
├── images/               # Prints e capturas dos dashboards
├── docs/                 # Anotações e documentação do estudo
├── requirements.txt      # Dependências Python
└── README.md

🔗 Demo online: link do dashboard publicado

📚 Conteúdo estudado
 Fundamentos de visualização de dados
 Escolha do gráfico ideal para cada tipo de informação
 Teoria das cores, tipografia e hierarquia visual
 Modelagem de dados (esquema estrela, fato e dimensão)
 Medidas e cálculos (DAX / SQL)
 Storytelling com dados
 Otimização de performance
 Publicação e compartilhamento de dashboards
 Automação de atualização dos dados

✅ Boas práticas aplicadas
Defina o objetivo antes de começar: quem usará o dashboard e qual decisão ele apoia?
Menos é mais: evite poluição visual e excesso de gráficos.
Hierarquia visual: KPIs principais no topo, detalhes abaixo.
Consistência: paleta de cores, fontes e formatos padronizados.
Interatividade com propósito: filtros e segmentações que realmente ajudam.
Dados confiáveis: sempre validar e documentar as fontes.

🚀 Como executar
Pré-requisitos
Python 3.10+
Git
Power BI Desktop (se for abrir os arquivos .pbix)
Passo a passo
bash
# 1. Clone o repositório
git clone https://github.com/seu-usuario/estudo-dashboard.git

# 2. Acesse a pasta
cd estudo-dashboard

# 3. Crie e ative um ambiente virtual
python -m venv venv
source venv/bin/activate      # Linux/Mac
venv\Scripts\activate         # Windows

# 4. Instale as dependências
pip install -r requirements.txt

# 5. (Opcional) Execute o app Streamlit
streamlit run dashboards/app.py

🗺️ Roadmap
 Adicionar novos dashboards (RH, Marketing, Logística)
 Incluir testes de qualidade dos dados
 Criar pipeline de atualização automática
 Publicar versão online dos dashboards
📖 Referências e materiais de apoio
Storytelling com Dados, Cole Nussbaumer Knaflic
The Big Book of Dashboards, Steve Wexler et al.
Documentação do Power BI
Documentação do Streamlit

🤝 Contribuições

Sugestões e melhorias são bem-vindas! Para contribuir:

Faça um fork do projeto
Crie uma branch: git checkout -b minha-feature
Faça o commit: git commit -m "Adiciona minha feature"
Envie para a branch: git push origin minha-feature
Abra um Pull Request
📄 Licença

Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais detalhes.

👤 Autor

💼 LinkedIn: https://www.linkedin.com/in/allan-prete-7ab7402b8/?isSelfProfile=true
- 📧 E-mail:
   Outlook: allan-prete@hotmail.com
   Gmail: allanprete2017@gmail.com
