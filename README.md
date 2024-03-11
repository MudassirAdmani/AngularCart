Steps to Create an ecommerce website:

1. Create project: ng new [project name]
2. install json-server: npm install json-server --save-dev
3. Create a mock data json file.
4. start json server: npx json-server --watch [json file]
5. generate model for products: ng generate class models/product --type=model
6. Define Product attributes and create constructor in product model
7. generate service for products: ng generate service services/product
8. implement functionality in service file to interact with json-server
9. 