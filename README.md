# Ecommerce Backend

![License](https://img.shields.io/badge/license-MIT-blue.svg)

## Description

This project was created to be a backend database for a company starting to become an ecommerce platform. This backend allows for users to be able to create new product categories, products, and tags easily!. 

When combined with a well designed and fully functional front end, this project can be the first step into the ecommerce world.

To see the back end in action, please [click here]() to see the video demo utilizing insomnia core.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Questions](#questions)
4. [License](#license)

## Installation

In order to use this backend, you would need to run the following code block,

```
npm i
```

By doing so, you will be installing the following npm packages.

1. eslint
2. nodemon
3. express
4. dotenv
5. mysql2
6. sequelize

In order to fully get this working, please take the .env.EXAMPLE file and rename the file to .env and fill out the file with your user and password for your machine.

```
DB_USER="input your user here"
DB_PW="input your password here"
DB_NAME='ecommerce_db'

```

You would have to run the schema.sql file in mysql through:

```
source schema.sql
```

Then run your seeds through the script:

```
npm run seed
```

With this you are ready to run this backend database.

## Usage

In order to use this backend and see all products/tags/categories, create new products/tags/categories, update products/tags/categproes, or delete products/tags/categories,

If you haven't already, please see my demonstration video linked in the description above in order to see it in action.

[Click here]() to see the video.


## Questions

If you have any questions, please feel free to reach out to me via:

1. Email: dhong0925@gmail.com
2. GitHub: Lunirs

## License

Licensed under the MIT license.

## Credits

Copyright © Daniel Hong All rights reserved.
