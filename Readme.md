<!-- how to run tailwindCss -->

## Setting up Tailwind css is really simple, just Follow This steps :


To set up Tailwind CSS for production, you have to execute the below set of commands: 
```
npm init -y
```

This command will initialize the directory as a NodeJS project. 

``` 
npm install -D tailwindcss postcss autoprefixer vite 
```

This command will install the required packages. 

```
npx tailwindcss init -p
```

<!-- The execution of this command will generate the configure file of Tailwind CSS. -->

### Create an ``` “Input.css” ``` file <br>
#### Add below text to your ``` src/input.css ``` by copying below piece of content:
``` css
@tailwind base;
@tailwind components;
@tailwind utilities;
```
#### In the ``` tailwind.config.js ``` file, <br> You have to replace ``` “content: []” ``` with ``` “content: [“*”]” ```. <br>
Moreover, You have to add following code to your scripts in ``` package.json. ```
```js
"start" : "vite"
```

Finally, you have to run the following command in your Teminal to start a dev server.
```css 
npm run start
```

## All Set now, Start using Tailwind in your HTML
### Make sure your compiled CSS is included in the ``` <head> ``` (your framework might handle this for you), then start using Tailwind’s utility classes to style your content.

```html
<!doctype html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href="/src/input.css" rel="stylesheet">
</head>
<body>
    <h1 class="text-3xl font-bold underline">Hello world!</h1>
</body>
</html>
```

## WELL DONE!🥳 YOU ARE READY TO GO 😊✅ <BR>
``` #HAPPY_CODING ✌️ ```
