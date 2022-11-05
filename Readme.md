npm init -y : para criar um projeto node

typescript - npm i typescript -D
tsx - para o node compilar automaticamente o typescript (npm i tsx -D)
fastify - como o Express, um servidor javascript (npm i fastify)
prisma - prisma client é para conectar com o banco e o de desenvolvimento é uma ferramenta de linha de comando para editar o banco (npm i prisma -D e npm i @prisma/client)
npx prisma init --datasource-provider SQLite : cria a configuração base do prisma para utilizar o SQLite. Por padrão o prisma usa o postgresql (é um ORM)
npx prisma migrate dev : ele cria a migration e executa para a criação do banco
npx prisma studio : abre uma interface para visualizar e editar o banco

npm i prisma-erd-generator @mermaid-js/mermaid-cli -D : para gerar relacionamentos automaticamente, o mermaid gera o diagrama a partir de código
npx prisma generate : depois de configurar no schema.prisma, ele gera o diagrama

npm i fastify/cors : cors é um mecanismo de segurança que permite dizer quais aplicações estão apitas a consumir os dados do backend.
