# ShopHadrien

E-commerce website for demonstration !


## .Env variables

Note pour DTY : Si jamais vous voulez lancer le site en local sur votre ordinateur (le site est néanmoins accessible à l'adresse https://hadrishop.herokuapp.com/), vous devrez créer un file .env et y mettre les configurations suivantes : 

NODE_ENV = development
PORT = 5000
MONGO_URI = l'uri de votre base de données mongodb 
JWT_SECRET = 'abc123'
PAYPAL_CLIENT_ID = une id de client paypal 

## Installer les dépendances 
npm install
cd frontend
npm install

## Lancer le site 
npm run dev 
