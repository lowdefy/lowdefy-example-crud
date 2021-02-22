# A Lowdefy CRUD Admin Example

[![Netlify Status](https://api.netlify.com/api/v1/badges/f293c299-c9b1-4d57-931b-2e4700e45eae/deploy-status)](https://app.netlify.com/sites/lowdefy-example-crud/deploys)

> [View this example.](https://example-crud.lowdefy.com)

This example shows patterns to implement a data admin app which allows users to view, create new, edit and delete data records.

The data in this very basic example contains a set of brands, and a set of products saved in a MongoDB database. A one-to-many relation exists between brands and products. Each product is related to one brand, and a brand can be related to many products.

This Lowdefy application consists of four pages

## Running this example

- Clone this repository
- Set up a MongoDB Atlas database and create a connection uri.
- Create `.env` file and set the connection uri secret to `LOWDEFY_SECRET_EXAMPLES_MDB`. (Make sure to never commit your secrets to your code repository.)
- Run the Lowdefy CLI from the cloned repository.

## Deploying this example

This simplest solution is to deploy this example to [Netlify](https://netlify.com). See [the Netlify Deployment instructions](https://docs.lowdefy.com/deployment) for more detail on how to deploy a Lowdefy app to Netlify.

## More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-start
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com
- Community forum - https://github.com/lowdefy/lowdefy/discussions
- Bug reports and feature requests - https://github.com/lowdefy/lowdefy/issues

## Licence

[MIT](https://github.com/lowdefy/lowdefy-example-reporting/blob/main/LICENSE)
