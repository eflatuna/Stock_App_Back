# Stock API

### ERD:

![ERD](./erdStockAPI.png)

### Folder/File Structure:

```
📦src
 ┣ 📂configs
 ┃ ┗ 📜dbConnection.js
 ┣ 📂controllers
 ┃ ┣ 📜auth.js
 ┃ ┣ 📜firm.js
 ┃ ┣ 📜sale.js
 ┃ ┣ 📜purchase.js
 ┃ ┗ 📜category.js
 ┃ ┗ 📜brand.js
 ┃ ┗ 📜product.js
 ┃ ┗ 📜token.js
 ┃ ┗ 📜user.js
 ┣ 📂errors
 ┃ ┗ 📜customError.js
 ┣ 📂helpers
 ┃ ┣ 📜passwordEncrypt.js
 ┃ ┗ 📜sendMail.js
 ┣ 📂middlewares
 ┃ ┣ 📜authentication.js
 ┃ ┣ 📜errorHandler.js
 ┃ ┣ 📜idValidation.js
 ┃ ┣ 📜logging.js
 ┃ ┣ 📜permissions.js
 ┃ ┣ 📜queryHandler.js
 ┃ ┗ 📜upload.js
 ┣ 📂models
 ┃ ┣ 📜firm.js
 ┃ ┣ 📜sale.js
 ┃ ┣ 📜purchase.js
 ┃ ┗ 📜brand.js
 ┃ ┗ 📜category.js
 ┃ ┗ 📜sale.js
 ┃ ┗ 📜token.js
 ┃ ┗ 📜user.js
 ┗ 📂routes
 ┃ ┣ 📜auth.js
 ┃ ┣ 📜documents.js
 ┃ ┣ 📜firm.js
 ┃ ┣ 📜index.js
 ┃ ┣ 📜sale.js
 ┃ ┣ 📜purchase.js
 ┃ ┗ 📜product.js
 ┃ ┗ 📜token.js
 ┃ ┗ 📜user.js
 ┃ ┗ 📜brand.js
 ┃ ┗ 📜category.js
 ┃ 📂logs
 ┣ 📜.env
 ┣ 📜.env-sample
 ┣ 📜.gitignore
 ┣ 📜erdStockAPI.png
 ┣ 📜index.js
 ┣ 📜package-lock.json
 ┣ 📜package.json
 ┣ 📜readme.md
 ┗ 📜swaggerAutogen.js
```
