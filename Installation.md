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

##  Database
    1. Skill
        php artisan make:model Skill -m
    2. Project belongs to skills
        php artisan make:model Project -m

## Mass Assigment and Relationship
    Implemennted the Mass Assigments and Relationships

## Controller and Routes
    Create the controllers for both Models 
        php artisan make:controller SkillController -r
        php artisan make:controller ProjectController -r
    Add the routes  both Projects and Skills

## Add the Links to display pages
    Add link into the AuthenticatedLayout.vue page 
    Add the route name.

## Create Page for Skills
    Create the pages inside the Pages folder called Skills
    Create the components index.vue
      eg resources/js/Pages/Skills/Index.vue
    - Use the dashboard layout to implement to all pages

## Display the Links
    Add the New Skills Button Link to create "New Skill"

## Display the UI Create
    - Display the form and store in database .
    - Let us use the Login.vue file
    - Add the logic in store method inside the skillController
    - Open the filsystems.php  FILESYSTEM_DISK put in env. file

    - Add the logic in store method inside the projectController
            Load the skill as well in create method 
    - Create the UI  for create a projects
    - Add logic insidee the controller

## Display the skills on the table
    - We gonna use the flowbite
        https://flowbite.com/docs/components/tables/
    - Copy the table and paste on skills.index
    - Add the logic inside the index method of skillController
    - Create a skillResource
        php artisan make:resource SkillResource

## Display the Projects on the table
    - We gonna use the flowbite
        https://flowbite.com/docs/components/tables/
    - Copy the table and paste on projects.index
    - Add the logic inside the index method of projectController
    - Create a projectResource
        php artisan make:resource  ProjectResource





## Create Layout and Components
    1. create app layout
    2. navbar
    3. footer

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














