### Rails, react and graphql

This blog is an exploration exercise to understand two new technologies - GraphQL and Relay. We are using standard rails application together with webpack for handling front-end dependencies.

### Status
Application supports reading and creating data from and on server using GraphQL.

#### Current features
* List posts
* List comments of the posts
* Infinite Scroll - posts and comments
* Show author info, votes and comments count
* Mutations to create comments and votes
* Edit and Update comments
* Create and Delete posts

### Running locally
To run the application, please just clone the repo and run it like so:

```
git clone git@github.com:gauravtiwari/blog-express.git
cd blog-express
bundle install
npm install
./start (from terminal). If you get permission error, just do chmod 777 start
```
