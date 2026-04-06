🤖 Automação SimulaContábil com Python & Playwright
Este projeto é uma automação web desenvolvida para interagir com o sistema SimulaContábil, realizando o fluxo completo de lançamentos financeiros (receitas e despesas) de forma automática. Foi meu primeiro projeto prático focado em RPA (Robotic Process Automation) e manipulação de elementos DOM.

![DEMONSTRAÇÃO DA AUTOMAÇÃO](https://github.com/user-attachments/assets/c5746a21-1de0-4331-8200-6a3c04051770)


📌 Funcionalidades
Login e Navegação: Acessa o sistema e navega automaticamente entre as abas de Dashboard e Lançamentos.

Cadastro Automático: Abre o modal de "Novo Lançamento" e preenche campos de descrição, valor, data, tipo, categoria e status.

Tratamento de Dados: Insere valores monetários e datas respeitando a formatação do sistema.

Gestão de Status: Diferencia lançamentos entre "Pago", "Pendente" e "Atrasado".

🛠️ Tecnologias Utilizadas
Python: Linguagem principal do projeto.

Playwright: Framework moderno para automação de navegadores (Chromium/WebKit/Firefox).

Lógica de Seletores: Uso de seletores CSS e XPath para identificação precisa de elementos na página.

🚀 Como Executar o Projeto
Clone o repositório:

Bash
git clone https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git
Crie um ambiente virtual (opcional, mas recomendado):

Bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
Instale as dependências:

Bash
pip install playwright
playwright install
Execute a automação:

Bash
python main.py
🧠 Aprendizados
Durante o desenvolvimento deste projeto, pude consolidar conhecimentos em:

Ciclo de vida de uma automação Web.

Manipulação de Modais e formulários dinâmicos.

Sincronismo (esperar o elemento carregar antes de interagir).

Estruturação de scripts para escalabilidade.

📄 Licença
Este projeto está sob a licença MIT - veja o arquivo LICENSE para detalhes.
