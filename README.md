This is the frontend application for the Coffee Shop app, built with Angular. It serves as the user interface for customers to browse products, manage their cart, and place orders. The frontend communicates with backend microservices https://github.com/innahunchenko/coffee-shop-microservices

for local launch go to the CoffeeShop.Client\CoffeeShop.Client\ folder and run:

docker build -t my-angular-app .
docker run -d -p 4200:4200 --name coffee-shop-client my-angular-app
