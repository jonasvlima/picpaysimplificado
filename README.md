# PicPaySimplificado

API simulando uma plataforma de pagamentos, inspirada no PicPay. 

## 🚀 Funcionalidades
- Criar usuários (COMUM ou LOJISTA).
- Realizar transferências entre usuários.
- Validar saldo e regras de negócio (LOJISTA não pode enviar dinheiro).

## 🛠 Tecnologias Utilizadas
- **Java 17**
- **Spring Boot**
- **Banco de Dados H2** (em memória)
- **Maven**
- **Insomnia** (para testes de API)

## ▶️ Como Executar

1. Clone o repositório:
   ```bash
   git clone https://github.com/jonasvlima/PicPaySimplificado.git
   ```

2. Acesse a pasta do projeto:
   ```bash
   cd PicPaySimplificado
   ```

3. Execute o projeto:
   ```bash
   mvn spring-boot:run
   ```

4. A API estará disponível em:
   ```
   http://localhost:8080
   ```

## 🔗 Endpoints

- `POST /users` - Cria um novo usuário.
- `POST /transactions` - Realiza uma transferência.

## 🔮 Melhorias Futuras
- Adicionar autenticação.
- Implementar notificações (e-mail/SMS).
- Utilizar um banco de dados real (MySQL/PostgreSQL).

## 📞 Contato
**Nome:** Jonas Lima  
**GitHub:** [jonasvlima](https://github.com/jonasvlima)  
**LinkedIn:** [Jonas Lima](https://www.linkedin.com/in/jonas-lima-212901261/)

🚀 **Projeto concluído!**



