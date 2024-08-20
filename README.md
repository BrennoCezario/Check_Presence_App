# PresenceApp

**PresenceApp** é um sistema de controle de presença escolar/trabalho desenvolvido utilizando Laravel no backend e React no frontend. O sistema permite o registro e acompanhamento de entradas e saídas de usuários, oferecendo funcionalidades avançadas de relatórios e gestão de usuários.

## Funcionalidades Principais

- **Autenticação de Usuários**: Login seguro para alunos, funcionários e administradores.
- **Registro de Presença**: Facilita o check-in e check-out de usuários com data e hora automáticas.
- **Dashboard**: Resumo visual das atividades de presença, com gráficos e tabelas.
- **Gestão de Usuários**: Administradores podem gerenciar perfis de usuários, incluindo adição, edição e remoção.
- **Relatórios de Presença**: Geração de relatórios detalhados com filtros personalizáveis para análise de dados de presença.
- **Configurações Globais**: Personalização das regras de presença, horários e outras configurações essenciais.

## Tecnologias Utilizadas

- **Backend**: Laravel
- **Frontend**: React
- **Banco de Dados**: MySQL
- **Estilização**: Tailwind CSS
- **Autenticação**: Laravel Sanctum

## Como Rodar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seuusuario/presence-app.git
   ```
2. Navegue até a pasta do projeto e instale as dependências do backend:
  ```bash
  composer install
  ```
3. Instale as dependências do frontend:
```bash
npm install
```
4. Configure o arquivo .env com as informações do banco de dados e outras variáveis necessárias.
   
5. Crie o banco de dados e execute as migrações:
```bash
php artisan migrate
```
6. Inicie o servidor de desenvolvimento:
```bash
php artisan serve
npm run dev
```

##Contribuições
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou enviar pull requests para melhorar o projeto.

##Licença
Este projeto é licenciado sob a MIT License.
