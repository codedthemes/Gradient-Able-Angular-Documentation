---
description: Angular CLI + NodeJs + Bootstrap
---

# Quick Installation

{% hint style="info" %}
You **don’t** need to install or configure tools like Webpack or CLI.  
They are configured and hidden so that you can focus on the code.
{% endhint %}

1. First of all it's required to Install [Node](https://nodejs.org/en/) and npm.
2. Update latest [angular-cli](https://cli.angular.io/) global package to Angular 11+ with cli 11.0.2
3. Unzip **gradient-able.zip** file, you will find the `gradient-able/template/skeleton/`project folder. 
4. Open your favorite console/terminal and navigate to the `gradient-able/template/skeleton`folder and **Install packages**

   ```text
   npm install
   ```

5. To run project locally: Below command will run the app in development mode. Open [http://localhost:4200](http://localhost:4200) to view it in the browser.

   ```text
   ng serve -o
   ```

6. The page will automatically reload if you make changes to the code.
7. Now you can use this Angular project for your application development, make the necessary changes.
8. To builds the app for production, below command will create the `dist/` folder inside this project directory .

   ```text
   ng build --prod --aot
   ```

{% hint style="success" %}
The project was built assuming it is hosted at the server root folder of domain/platform   
i.e**`http://example.com`**

### or

to deploy build for sub-folder   
i.e**`http://example.com/folder-name`**  

You also need to set **&lt;base href="/folder-name/"&gt;**
{% endhint %}

