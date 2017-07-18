# React With Redux billingCycle
Front End application to show user control and use of react with redux and the use of components.
Made based on the classes of the teacher [Leonardo Moura Leitão](https://www.youtube.com/watch?v=5sMBYBRwJ5Q&list=PLDm7BSK-M5YleJFYqnxvs7DZruSPmCgya).

## Getting Started

Have Installed on your machine:
[NodeJS](https://nodejs.org/en/) and [MongoDB](https://www.mongodb.com/download-center?jmp=nav#community)

### Install

#### Application [Backend API](https://github.com/Cesar-Filho/BackendBillingCycle)
```sh
git clone https://github.com/Cesar-Filho/BackendBillingCycle.git
cd BackendBillingCycle
npm install
mongoD
npm run dev
```
To use create an .env file inside the "src" folder.
Create an AuthSecret for your file, for example:
> Module.exports = {
>
>     AuthSecret: 'skjdhf6 $$% dojkhf ^ (sdkjhf'
>    
>}

and save the file.

#### Application Front End
```sh
git clone https://github.com/Cesar-Filho/ReactReduxCiclodePagamento.git
cd ReactReduxCiclodePagamento
npm install
npm run dev
```

### Remember

The application is using the axios to consume the API. If you want to use the static data go to the "actions" 
files of the components and change the parameters.
It's the files:

[authActions.js](https://github.com/Cesar-Filho/ReactReduxCiclodePagamento/blob/master/src/auth/authActions.js)

[billingCycleActions.jsx](https://github.com/Cesar-Filho/ReactReduxCiclodePagamento/blob/master/src/billingCycle/billingCycleActions.jsx)

[dashboardActions.jsx](https://github.com/Cesar-Filho/ReactReduxCiclodePagamento/blob/master/src/dashboard/dashboardActions.jsx)

If you do not want to use User for application, remove the import of the authOrApp file from the route and place the dashboard as 
the main [route](https://github.com/Cesar-Filho/ReactReduxCiclodePagamento/blob/master/src/main/routes.jsx). Change the route in your [nodejs API](https://github.com/Cesar-Filho/BackendBillingCycle/blob/master/src/config/routes.js) application.

More details in the [react-router](https://github.com/ReactTraining/react-router) documentation

Good Studies!
