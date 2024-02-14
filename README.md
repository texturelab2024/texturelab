# texturelab

Hello, here are some tips on how to run the project and to understand it.

    //How to run
    1. Run npm i to generate packgage-lock.json
    2. Run project with npm start

    //Tips
    1. Project is made with sass so to code need to be translated from scss to css
    2. To do that some scripts are written in the package.json file.
    3. Basically what is does. it creates an public folder used only on production which contains a copy of the index.html in the src and css file.
    4. All the changes made in the src are automatically copied to the public folder.
