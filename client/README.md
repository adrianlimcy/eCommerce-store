# Steps
1.  npm install
2.  npm audit fix
3.  npm start
4.  npm install apollo-client apollo-link-http react-apollo graphql graphql-tag
5.  npm install apollo-cache-inmemory
    - missing from book, probably an apollo upgrade

# on client side
1.  touch client/src/constants.js
2.  touch client/src/components/Cart/AddToCartButton.js
3.  touch client/src/components/Products/Filter.js

# using JWT
1. had some issues with react-apollo, so had to uninstall it, installed @apollo/client, then uninstalled it, then reinstalled react-apollo ... go figure ... probably some dependancies
2. npm install apollo-link-Context

# Errors
1.  Initial download Button.js had some missing code, affecting button colors and css
2.  Login has issues