# TelsaClone
# Setting up the tailwindcss
1. create an src folder and run command ``` $npm init ```
1. now run the command
   ```
       $npm install -D tailwindcss
   ```
1. now run the command ```$npm tailwindcss init```
1. create a file with name input.css and place
   ```
      @tailwind base;
      @tailwind components;
      @tailwind utilities;
   ```
1. now run the command below command. It will create a folder name dist and output.css file.
    ```
       npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
   ```
3. Now in the index.html place the below snippet
     ```
        <link rel="stylesheet" href="../dist/output.css">
     ```
    
