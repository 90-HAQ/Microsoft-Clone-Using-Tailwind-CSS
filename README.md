<p align="center"><a href="https://facebook.com" target="_blank"><img src="https://github.com/90-HAQ/Microsoft-Clone-Using-Tailwind-CSS/blob/master/images/microsoft.svg" width="400">
</a><a href="https://tailwindcss.com/" target="_blank"><img src="https://github.com/90-HAQ/facebook_login_page_tailwind/blob/master/tailwind_css.svg" width="400">
</a></p>


<br><br>

<h1 align="center">Responsive Microsoft Official Home Page Using Tailwind Css</h1>
<h3 align="center">Go through the readme file for the installation of the setup</h3>

<br><br>

## Screenshot

<div align="center"><img align="center" src="https://github.com/90-HAQ/Microsoft-Clone-Using-Tailwind-CSS/blob/master/images/ms_screen%201.png"></div>
<br>
<div align="center"><img  src="https://github.com/90-HAQ/Microsoft-Clone-Using-Tailwind-CSS/blob/master/images/ms_screen%202.png"></div>
<br>
<div align="center"><img align="center" src="https://github.com/90-HAQ/Microsoft-Clone-Using-Tailwind-CSS/blob/master/images/ms_screen%203.png"></div>
<br>

## Requirements

 - Vs Code Editor (https://code.visualstudio.com/)
 - Node Js (https://nodejs.org/en/)


## Project Setup

<ul>
 <li>Create a new Folder / Project and open it in Vscode.</li>
 <li>Create a file <strong> intex.html </strong>.</li>
 <li>To use <strong> Tailwind CSS </strong> you should have <strong> Node JS </strong> . </li>
 <li>Without Node JS you cannot use Tailwind CSS.  </li>
 <li> Installation of Tailwind CSS is gieven below read and implement step by step.</li>
</ul>

## Tailwind CSS Setup

Run 1st command in the terminal, hit enter to install all the <strong> node_modules </strong>.
 
    npm i
 
<br>
 
Run 2nd command in the terminal, hit enter to install <strong> package.json </strong> file.
 
    npm init -y
 
<br>


Run 3rd command in the terminal, hit enter to install <strong> Tailwind CSS Configuration </strong>.
 
    npm install -D tailwindcss postcss autoprefixer
 
<br>

Run 3rd command in the terminal, hit enter to install <strong> Tailwind CSS </strong> in your project.
 
    npm install vite
    
we install vite because we want to start a server that will automatically refresh.
 
<br>

Then goto package.json file, make a change in script section above the devDependencies.
  
    "script": 
    { 
      "start" : "vite" 
    },

<br>

Run 4th command in the terminal, hit enter to install <strong> Tailwind CSS Configuration </strong>.
 
    npx tailwindcss init -p  
    npx tailwindcss init     
 
<br>

After running both above commands goto <strong> tailwind.confing.js <strong> file, make a change in script.

    module.exports = 
    {
      content: ["*"],
      theme: 
      {
       extend: {},
      },
      plugins: [],
    }


 it means that i want to use tailwind in all the content.
 
 <br>
 
 Add the tailwind script in the index.html file.

	<script src="https://cdn.tailwindcss.com"></script>
 
<br>	
 
Run last command in the terminal, hit enter to install <strong> Tailwind CSS Configuration </strong>.
 
    npm run start
 
it will create a localhost server.
 
<br>
	
## Feed Back

If you have any feedback or questions, please reach out to us at hussainhashmi1426@gmail.com

