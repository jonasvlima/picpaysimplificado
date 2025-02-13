# picpaysimplificado
 
PicPaySimplificado
API simulando uma plataforma de pagamentos, inspirada no PicPay. Desenvolvido para portfólio.

Funcionalidades
Criar usuários (COMUM ou LOJISTA).

Realizar transferências entre usuários.

Validar saldo e regras de negócio (LOJISTA não pode enviar dinheiro).

Tecnologias
Java 17

Spring Boot

Banco de Dados H2 (em memória)

Maven

Insomnia (para testes de API)

Como Executar
Clone o repositório:

bash
Copy
git clone https://github.com/jonasvlima/PicPaySimplificado.git
Navegue até a pasta do projeto:

bash
Copy
cd PicPaySimplificado
Execute o projeto:

bash
Copy
mvn spring-boot:run
Acesse a API em:

http://localhost:8080

Endpoints
POST /users - Cria um usuário.

POST /transactions - Realiza uma transferência.

Melhorias Futuras
Adicionar autenticação.

Implementar notificações (e-mail/SMS).

Usar banco de dados real (MySQL/PostgreSQL).

Contato
Nome: Jonas Lima

GitHub: jonasvlima

LinkedIn: Jonas Lima

Projeto concluído! 🚀
