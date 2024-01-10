# Lowdefy CRUD Admin Example

> [View this example.](https://example-crud.lowdefy.com)

This example shows patterns to implement a data admin app which allows users to view, create new, edit and delete data records.

The data in this very basic example contains a set of brands, and a set of products saved in a MongoDB database. A one-to-many relation exists between brands and products. Each product is related to one brand, and a brand can be related to many products.

This Lowdefy application consists of four pages.

Adding a new brand, editing an existing brand and viewing the saved brands have been split up into separate pages. This implementation is a simpler approach than that of the products. Adding a new product, editing an existing product and viewing the saved products are all done on one page. Drawers are used in order to get this right, which leads to a more complex implementation.

## Running this example

- Create a MongoDB cluster and get a URI connection string:
  - Create a free MongoDB database cluster hosted by [MongoDB Atlas](https://www.mongodb.com/try).
  - Create a new database called `example-crud`.
  - Add two new collections to this database called `brands` and `products`.
  - In the Database access section, create a database user with read access to any database (You can also specify the database as `example-crud`).
  - In the main cluster view, click "connect", then "Connect you application". This will give a MongoDB URI connection string. Use the credentials you just created.
  - You can read more about the [Lowdefy MongoDB connector](https://docs.lowdefy.com/MongoDB).
- Clone this repository.
- Create a `.env` file in your project folder and set your MongoDB database connector URI as a variable in the `.env` file: `LOWDEFY_SECRET_EXAMPLES_MDB="{{ your_mongodb_connection_uri }}"`
- In the command console, navigate to your project folder and run the Lowdefy CLI: `pnpx lowdefy@4 dev`.

## More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues

## Licence

[MIT](https://github.com/lowdefy/lowdefy-example-crud/blob/main/LICENSE)
