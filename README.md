✂️ BarberShoop
Este é um projeto desenvolvido para gerenciar uma barbearia, com funcionalidades de agendamento de serviços, gerenciamento de clientes, serviços disponíveis e horários.

🌐 Sistema Hospedado
Você pode acessar o sistema ao vivo no Vercel clicando aqui.

🚀 Tecnologias Utilizadas

Frontend:

React.js, Next.js

Backend:

Node.js, Express.js

Banco de Dados:

PostgreSQL (hospedado no Neon)

ORM:

TypeORM

Outras Ferramentas:

Docker

⚙️ Funcionalidades

🧑‍💼 Cadastro de Clientes

Os clientes podem se cadastrar, editar suas informações e até serem excluídos do sistema.

📅 Agendamento de Serviços

Os clientes podem selecionar serviços disponíveis e agendar horários de atendimento com os profissionais da barbearia.

🔐 Autenticação
Sistema de login seguro com autenticação JWT, garantindo que apenas usuários autorizados possam acessar suas informações.

📊 Dashboard de Gerenciamento
Uma visão geral para os administradores, permitindo o gerenciamento de horários, agendamentos e clientes cadastrados na barbearia.

🛠️ Pré-requisitos
Antes de iniciar, você precisará ter as seguintes ferramentas instaladas em sua máquina:

Git
Node.js
Docker
Além disso, é bom ter um editor para trabalhar com o código, como VSCode.

🔧 Instalação e Execução

Clone o Repositório

git clone https://github.com/CaioSergio93/BarberShoop.git

cd BarberShoop

Configurando o Projeto

Instale as dependências:

npm install
Crie um arquivo .env com as variáveis de ambiente necessárias:

DATABASE_URL=postgres://user:password@<neon-endpoint>:5432/barbershoop
JWT_SECRET=seu_secret_aqui

Substitua <neon-endpoint> pelo endpoint fornecido pelo Neon.

Inicie o Docker para executar os serviços necessários:

docker-compose up -d
Execute as migrações do banco de dados com TypeORM:

npm run typeorm migration:run

🚀 Rodando o Projeto
Para iniciar o servidor localmente:

npm run dev
A aplicação estará disponível em: http://localhost:3000.

✅ Testes
Para executar os testes:

npm run test

🤝 Contribuição
Faça um fork do projeto

Crie uma branch para sua feature (git checkout -b feature/NovaFeature)

Commit suas alterações (git commit -m 'Adiciona nova feature')

Push na sua branch (git push origin feature/NovaFeature)

Abra um Pull Request

📜 Licença
Este projeto está sob a licença MIT. Consulte o arquivo LICENSE para mais informações.


----------------------------------------------------------------------------------------------------------------------------------------------------------------


✂️ BarberShoop
This project was developed to manage a barbershop, with features for service scheduling, client management, available services, and time slots.

🌐 Hosted System
You can access the live system on Vercel by clicking here.

🚀 Technologies Used

Frontend:

React.js, Next.js

Backend:

Node.js, Express.js

Database:

PostgreSQL (hosted on Neon)

ORM:

TypeORM

Other Tools:

Docker

⚙️ Features

🧑‍💼 Client Registration
Clients can register, edit their information, and even be removed from the system.

📅 Service Scheduling
Clients can select available services and schedule appointments with barbershop professionals.

🔐 Authentication
A secure login system with JWT authentication ensures that only authorized users can access their information.

📊 Management Dashboard
An overview for administrators, allowing them to manage schedules, appointments, and registered clients at the barbershop.

🛠️ Prerequisites
Before you start, you need to have the following tools installed on your machine:

Git
Node.js
Docker
Additionally, it’s good to have a code editor, such as VSCode.

🔧 Installation and Execution

git clone https://github.com/CaioSergio93/BarberShoop.git
cd BarberShoop

Project Setup

Install the dependencies:

npm install
Create a .env file with the necessary environment variables:

DATABASE_URL=postgres://user:password@<neon-endpoint>:5432/barbershoop
JWT_SECRET=your_secret_here
Replace <neon-endpoint> with the endpoint provided by Neon.

Start Docker to run the required services:

docker-compose up -d
Run the database migrations with TypeORM:

npm run typeorm migration:run

🚀 Running the Project

To start the server locally:

npm run dev
The application will be available at: http://localhost:3000.

✅ Tests
To run the tests:

npm run test

🤝 Contributing

Fork the project

Create a branch for your feature (git checkout -b feature/NewFeature)

Commit your changes (git commit -m 'Add new feature')

Push to your branch (git push origin feature/NewFeature)

Open a Pull Request

📜 License

This project is licensed under the MIT License. See the LICENSE file for more information.
