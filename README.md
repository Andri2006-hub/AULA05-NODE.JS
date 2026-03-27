# AULA05-NODE.JS - Manipulação de Arquivos com Node.js
Aplicação Node.js para praticar manipulação assíncrona de arquivos (fs.promises), criação de diretórios, e terminal colorido com chalk.
✨ Funcionalidades
✅ Cria automaticamente a pasta ./storage
✅ Gera arquivo ./storage/aula05.txt com conteúdo específico
✅ Exibe progresso colorido no terminal
✅ Lê e exibe o conteúdo criado
✅ Tratamento completo de erros
✅ Funciona no CMD Windows, Linux e Mac
🎬 Demo Terminal
🚀 Iniciando criação da aplicação de manipulação de arquivos...
📁 Verificando pasta storage...
✅ Pasta storage criada com sucesso
💾 Criando arquivo aula05.txt...
✅ Arquivo ./storage/aula05.txt criado com sucesso!
📖 Lendo conteúdo do arquivo...

📄 Conteúdo do arquivo:
Aula 05 - Manipulação de arquivos com Node.js.

Arquivo criado com sucesso durante a atividade final.

🎉 Atividade finalizada com sucesso!
🛠️ Tecnologias Utilizadas
🚀 Como Executar
# 1. Clone o repositório
git clone https://github.com/SEU_USUARIO/aula-node-files.git
cd aula-node-files

# 2. Instale dependências
npm install

# 3. Execute
npm start
Comandos NPM (já configurados)
npm start    # Executa a aplicação
npm run dev  # Mesmo que start
📁 Estrutura do Projeto
aula-node-files/
├── storage/          # Criado automaticamente
│   └── aula05.txt    # Arquivo gerado
├── index.js          # Código principal
├── package.json
├── package-lock.json
└── .gitignore
💻 Código Principal
const fs = require('fs').promises;
const path = require('path');
const chalk = require('chalk');

// async/await + fs.promises + chalk
async function main() {
    // Cria pasta, escreve, lê e exibe com cores
}
📚 Conceitos Praticados
fs.promises vs callbacks
path.join() para caminhos seguros
fs.mkdir({ recursive: true })
fs.access() para verificar existência
Tratamento de erros com try/catch
Terminal colorido com chalk
🔍 Como Testar
Execute npm start
Verifique se ./storage/aula05.txt foi criado
Confirme se o conteúdo está correto
Delete storage/ e execute novamente
🤝 Contribuições
Fork o projeto
Crie sua branch (git checkout -b feature/nova-funcionalidade)
Commit suas mudanças (git commit -m 'feat: nova funcionalidade')
Push para a branch (git push origin feature/nova-funcionalidade)
Abra um Pull Request
