<!-- how to run tailwindCss -->

# First We have to open our Terminal and Write

<!-- To set up Tailwind CSS for production, you have to execute the below set of commands: -->
### npm init -y


# after that

<!-- This command will initialize the directory as a NodeJS project. -->

### npm install -D tailwindcss postcss autoprefixer vite

<!-- This command will install the required packages. -->

### npx tailwindcss init-p

<!-- The execution of this command will generate the configure file of Tailwind CSS. -->

<ul>
    <li>Create an “Input.css” file</li>
    <li>Add below text to your HTML and edit it with the below piece of content:
        <ul  style="list-style: none;">
            <li>@tailwind base;</li>
            <li>@tailwind components;</li>
            <li>@tailwind utilities;</li>
        </ul>
    </li>
    <li>In the tailwind.config.js file, You have to replace “content: []” with “content: [“*”]”.</li>
    <li>Moreover, You have to add “start”: “vite” to your scripts in package.json.</li>
    <li>Finally, you have to run the npm run start command to start a dev server.</li>


</ul>