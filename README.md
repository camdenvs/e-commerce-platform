# Challenge 13: E-commerce backend
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
## Description 
The goal of this project was to create an application that allows a manager for an internet retail company that allows them to organize their e-commerce website by creating and viewing products, categories, and tags.

## Installation
View this video to see how to run this application: https://youtu.be/_tU5i1DSsIs

## Usage
To use this application, edit the '.env.EXAMPLE' file to include your login information, and rename the file to just '.env'. Run the schema.sql file found in the db directory in the Mysql shell by using the command 'source db/schema.sql' to create the database on your machine. Next you will need to seed the database, which can be done with 'npm run seed'. The server can now be run with the command 'npm start'. Using the Insomnia Core, you will be able to make requests for categories, products, and tags.

## Credits
- Sequelize: https://www.npmjs.com/package/sequelize 
- Express: https://www.npmjs.com/package/express
- Mysql2: https://www.npmjs.com/package/mysql2 
- Dotenv: https://www.npmjs.com/package/dotenv 

## License
MIT License

Copyright (c) 2022 FarmFreshYeets

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.