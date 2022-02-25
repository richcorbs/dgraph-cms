# Dgraph CMS

This is a simple CMS built on Dgraph.

- The front end is Tailwind CSS and AlpineJS.
- The repo doesn't include any of the built CSS. If you try to use it as it is it will be ugly. You've been warned.
- There are no `@auth` rules built in to the schema.
- To use it you'll need to:
  - Incorporate hook it up to Tailwind via your favorite method.
  - Update the `backendUrl` variable in the javascript with the URL of your Dgraph instance.
  - Copy the contents of schema.graphql into your graphql schema in Dgraph.
  - Use GraphQL to create your first piece of content. After that you can use the UI in index.html.


<img width="1253" alt="Screen Shot 2022-02-19 at 1 43 11 PM" src="https://user-images.githubusercontent.com/437167/155629915-2a17f700-5da0-43e3-a499-31b8e1ea9cf1.png">
