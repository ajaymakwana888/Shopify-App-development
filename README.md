# Shopify App development Process


1) Create partner account
   https://partners.shopify.com/

 2) Create App 
    https://partners.shopify.com/1652513/apps/new

     - Public App
     - App Name  
     - API contact email
     - App URL    (backend Laravel App URL) => https://laravel-app.test/
     - Redirection URL     => https://shop-app.test/authenticate

 3) Create Stores
     https://partners.shopify.com/1652513/stores
     - store type => Development store
     - Store name
     - Store URL
     - Login, Password
     - Store address, purpose

     Created: https://laravel-store.myshopify.com


 4) Setup Laravel Project
  - setup fresh laravel project
  - Imlement `osiset/laravel-shopify` package
      - https://github.com/osiset/laravel-shopify

   - add .env variables from Shopify account  (https://partners.shopify.com/1652513/apps/4140243)
     - SHOPIFY_API_KEY   (from shopify App setup)
     - SHOPIFY_API_SECRET
     - SHOPIFY_API_VERSION


 5) Open Login page 
   - https://shop-loyalty.test/login

   - Enter Shop url
       echo-app-store.myshopify.com
       
   - Its redirect to Store account & Install App


 6) For Locally Test
    - Go to App details
    - Test your app
      - Select store
      - Install App


 7) After Installed App
     - go inside App
     - there New Interface from Backend App
      Like - Manage Customers, Subscription plan etc
