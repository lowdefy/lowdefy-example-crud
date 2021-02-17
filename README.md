# A Lowdefy CRUD Admin Example

This example show patterns to implement a data admin app which allows users to view, create new, edit and delete data records.

The data in this example contains a set of brands, and a set of products saved in a MongoDB database. A one-to-many relation exists between brands and products. Each product is related to one brand, and a brand can be related to many products.

This Lowdefy application consists of four pages.

## Running this example

- Clone this repository
- Set up a MongoDB Atlas database and create a connection uri.
- Create `.env` file and set the connection uri secret to `LOWDEFY_SECRET_EXAMPLES_MDB`. (Make sure to never commit your secrets to your code repository.)
- Run the Lowdefy CLI from the cloned repository.

## Deploying this example

This simplest solution is to deploy this example to [Netlify](https://netlify.com). See [the Netlify Deployment instructions](https://docs.lowdefy.com/deployment) for more detail on how to deploy a Lowdefy app to Netlify.

### More Lowdefy resources

- Getting started with Lowdefy - https://docs.lowdefy.com/tutorial-setup
- Lowdefy docs - https://docs.lowdefy.com
- Lowdefy website - https://lowdefy.com

## Licence: MIT

See the LICENSE.md file for license rights and limitations.
