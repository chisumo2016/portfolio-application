### INSTALATION
    - composer require laravel/breeze --dev
    - php artisan breeze:install vue
    - php artisan migrate
    - npm install
    - npm run dev

## Resources
    https://tailwindcomponents.com/
    https://tailwindui.com/
    https://flowbite.com/
    https://daisyui.com/
    https://merakiui.com/
    https://tailwind-kit.com/
    https://tailgrids.com/
    https://hyperui.com/
    https://colorhunt.co/palettes/popular



## Create Sections components
    1.Hero section
    2.About
    3.Call to action
    4.Portifolio
    5.Skills section
    6.Services section
    7.Contact section
 ## Contact Mail
 ## Contact Controller


### CUSTOMIZING THE TAILWINDCSS
    https://tailwindcss.com/docs/configuration
    - Open the tailwind.config.js
         fontFamily:{
            primary: "Playfair Display",
            body: "work Sans"
        }
    - Use the google font 
    - Add in app.css OR
    - Add in app.css

## CREATE A LAYOUT  (HEADER / NAV)
    - create a new FrontEnd.vue
            resources/js/Layouts/FrontEnd.vue
    - Create a folder called Frontend inside Components
            resources/js/Components/FrontEnd
    - Create a file called Header.vue
            https://flowbite.com/docs/components/navbar/
    - Add into welcome page
            resources/js/Pages/Welcome.vue

##  CREATE THE FOOTER
    - Create a new file inside the FrondEnd Component called Footer
    - Design the  footer UI with tailwindcss
    - Add inside the Layout/Frondend.vue

## HERO SECTION 
    - Creete a Hero component 
    - Design Hero compoonent with  with tailwindcss
    - Add the hero component in welcome.vue

## PROMOTE SECTION
    - Creete a promote component 
    - Design promote compoonent with  with tailwindcss
    - Add the promote component in welcome.vue

## ABOUT SECTION
    - Creete a about component 
    - Design about compoonent with  with tailwindcss
    - Add the about component in welcome.vue

## SKILLS SECTION
    - we need to get the skills from database .
    - Create the welcome controller
            php artisan make:controller WelcomeController
    - Add the web route
    - Add the logic inside the welcome controller to render the page
    - Open the welcome page.vue and define Props
    - Create skills file  component 
    - pass the props in the skills.vue
    - loop tthrough skills.vue
    - Design skills compoonent with  with tailwindcss
    - Add the about component in welcome.vue

## PORTFOLIO SECTION
     - Creete Portfolio file  component
     - In portifolio/project we need the skills as well
     - Load the projects in the welcome controller with relationship
     - We need to define the projects as props in welcome page
     - pass the props into components of Portiolio
     - Open the Portfolio  file and define the props
     - Design Portfolio compoonent with  with tailwindcss
     - Create a new component called Projects.vue
     - Filtter the projects based on skills
     - Loop through skills and projects in projects
     - Add the Projects component in welcome.vue
     - Pass the props inside the component
     - Add a new  single component called Project.vue and design
     - Pass the props
     - Attach the single project.vue into Projects.vue file

## FILTERING
    - Open the Projects.vue file
    - create const for props
    - define  const filteredProjects = ref(props.projects.data)
    - Show the buttton 

## SERVICES SECTION
    - Creete a services component 
    - Design promote compoonent with  with tailwindcss
    - Add the promote component in welcome.vue











