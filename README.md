## Setting up my Git Repository

1. Instruction to set up my local folder to point to Github

    ```BASH

    echo "# colmaracademy" >> README.md  
    git init
    git add README.md
    git commit -m "first commit"
    git branch -M main
    git remote add origin https://github.com/bong033/colmaracademy.git
    git remote -v
    git push -u origin main

    ```

2. In the event remote url is set incorrectly

    ```BASH

    git remote set-url origin https://github.com/bong033/colmaracademy.git
    git remote -v
    git push -u origin main

    ```

