nodeJS - GoNode - App GoBarber

yarn init -y // Instalar no diretório

- yarn add express
- yarn add nodemon -D
- yarn add nunjucks
- yarn add eslint -D
- yarn eslint --init
- yarn add sequelize
- yarn add sequelize-cli -D
  - npx sequelize init
- yarn add pg

- docker run --name database -p 5432:5432 -d -t kartoza/postgis

- npx sequelize db:migrate //Realiza a migracao dos dados para o banco da aplicacao

- yarn add bcryptjs
- yarn add multer
- yarn add express-session
- yarn add session-file-store
- yarn add connect-flash
- npx sequelize migration:create --name=create-appointments
- npx sequelize db:migrate
