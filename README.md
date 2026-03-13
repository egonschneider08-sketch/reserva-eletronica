Sistema de Reserva de Componentes

Sistema simples de controle e reserva de componentes de laboratório desenvolvido com HTML, CSS e JavaScript puro, utilizando LocalStorage para armazenar os dados no navegador.

O sistema permite registrar reservas de componentes, visualizar o estoque disponível, consultar reservas por data e acompanhar um gráfico de uso.

🚀 Funcionalidades

✅ Login de usuário
✅ Registro de reservas de componentes
✅ Controle automático de estoque
✅ Calendário de reservas por data
✅ Histórico completo de reservas
✅ Cancelamento de reservas (apenas professor)
✅ Gráfico de uso dos componentes
✅ Interface responsiva simples
✅ Armazenamento local com LocalStorage

👥 Tipos de Usuário

O sistema possui dois tipos de acesso:

👨‍🎓 Aluno

Pode:

Registrar reservas

Visualizar estoque

Ver histórico

Ver calendário

Login:

Usuário: aluno
Senha: 1234

👨‍🏫 Professor

Pode:

Registrar reservas

Visualizar estoque

Ver histórico

Ver calendário

Cancelar reservas

Login:

Usuário: professor
Senha: 1234

🧰 Componentes Disponíveis

O sistema inicia com os seguintes itens no estoque:

Kit Arduino — 24 unidades

Protoboard pequena — 24 unidades

Protoboard grande — 24 unidades

Tapete de borracha — 12 unidades

📊 Funcionalidades do Sistema
📌 Nova Reserva

Permite registrar uma reserva informando:

Nome

Turma

Data

Componente

Horário de retirada

Horário de devolução

Quantidade

Observações

O sistema verifica automaticamente se há estoque suficiente.

📅 Calendário do Dia

Mostra todas as reservas de uma data específica.

Exibe:

Componente

Horário de retirada

Horário de devolução

Responsável

📦 Estoque

Tabela com todos os componentes e suas quantidades disponíveis.

📜 Histórico

Lista completa de todas as reservas registradas.

Se o usuário for professor, aparece o botão Cancelar para remover a reserva e devolver o item ao estoque.

📈 Gráfico de Uso

Um gráfico simples desenhado com Canvas que mostra quantas vezes cada componente foi reservado.

💾 Armazenamento

Os dados são armazenados no navegador usando:

localStorage


Itens salvos:

reservas

estoque

⚠️ Limpar os dados do navegador apagará as informações.

🖥️ Tecnologias Utilizadas

HTML5

CSS3

JavaScript

LocalStorage

Canvas API

📂 Estrutura do Projeto
sistema-reserva-componentes
│
├── index.html
└── README.md

▶️ Como Executar

Baixe ou clone o repositório

git clone https://github.com/seu-usuario/seu-repositorio.git


Abra o arquivo:

index.html


em qualquer navegador.

Não é necessário servidor ou instalação.

📌 Possíveis Melhorias

Banco de dados real (Firebase / MySQL)

Sistema de autenticação real

Cadastro de novos componentes

Dashboard mais avançado

Exportar histórico em CSV

Interface mais moderna
