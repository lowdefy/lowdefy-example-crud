# Lowdefy Admin Example

This example show patterns that can be used to implement an admin app, that allows users to see data records, create new new data records, edit those records and delete those records.

This example will contain a set of brands, and a set of products.

A one-to-many relation will be created between the brands and the products. Each product will be related to one brand, and a brand can be related to many products.

## Running this example
- Clone this repository
- Set up a MongoDB Atlas database and set the connection uri as secret `lowdefy_examples_mdb`.
- Load the sample database into the database.
- Run the Lowdefy CLI from the cloned repository.

## Licence

This example configuration is licensed under the MIT license. See the LICENSE.md file for license rights and limitations.