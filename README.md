
LabControl - Sistema de Reserva para kits de Arduino 

Um sistema web simples, responsivo e intuitivo desenvolvido para gerenciar o estoque e as reservas de componentes eletrônicos em laboratórios educacionais (como Kits Arduino e Protoboards). O projeto foi construído em um único arquivo, focando na praticidade e usando o armazenamento local do navegador para manter os dados.

Funcionalidades
Autenticação Baseada em Perfis: Dois níveis de acesso simulados (Aluno e Professor).

Controle de Permissões: Apenas o perfil "Professor" tem autorização para cancelar reservas e devolver itens ao estoque.

Gestão de Estoque Dinâmica: O sistema impede a reserva de componentes caso a quantidade solicitada seja maior que a disponível no inventário.

Histórico e Calendário: Tabela completa com o histórico de todas as reservas e um filtro por data para visualizar a agenda diária do laboratório.

Dashboard Visual: Gráfico de barras gerado de forma nativa indicando o volume de uso de cada componente.

Persistência de Dados: Uso do localStorage para garantir que as reservas e o estoque não sejam perdidos ao recarregar a página.

Interface Moderna: Design responsivo (Mobile-first em formulários) utilizando Glassmorphism e Dark Mode.

Tecnologias Utilizadas
HTML5: Estruturação semântica da aplicação e uso nativo da tag <canvas> para gráficos.

CSS3: Estilização com Flexbox, CSS Grid, media queries para responsividade e variáveis de cor.

JavaScript (Vanilla): Lógica de negócios, manipulação do DOM, controle de arrays/objetos e integração com o localStorage. Não requer bibliotecas externas.

Como Executar o Projeto
Como o projeto é construído inteiramente no front-end e não requer um servidor de banco de dados, executá-lo é muito simples:

Faça o clone deste repositório:

Bash
git clone file:///C:/Users/matheus_schneider150/Documents/html/reserva-eletronica/sistema_de_controle.html
Navegue até a pasta do projeto.

Dê um duplo clique no arquivo index.html para abri-lo no seu navegador de preferência.

Credenciais de Acesso (Login)
Para testar o sistema, utilize as seguintes credenciais pré-configuradas:

Perfil Aluno (Apenas visualização e reserva)

Usuário: aluno

Senha: 1234

Perfil Professor (Pode cancelar reservas)

Usuário: professor

Senha: 1234

Melhorias Futuras
Ideias para expandir o projeto:

Separar os códigos HTML, CSS e JS em arquivos distintos para melhor organização.

Criar um painel de administração para cadastrar novos componentes no estoque dinamicamente.

Conectar a um banco de dados real (como Firebase ou Supabase) no lugar do localStorage.

Adicionar funcionalidade de exportação de relatórios em PDF/Excel.
