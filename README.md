# SimpliLearn MEAN Stack Developer Bootcamp (Fourth Project) - Dockerizing Angular Application
Deploy an Angular application on Docker container on an EC2 instance

# Following requirements should be met:  
* Source code should be tracked on GitHub repositories. You need to document the tracked files that are ignored during the final push to the GitHub repository.
* The submission of your GitHub repository link is mandatory in order to track your task.
* The step-by-step process involved in completing this task should be documented.

# You must use the following:
AWS EC2 instance, Docker, Node JS, Angular CLI, GitHub

# Screenshots 
**Run Docker image

<img width="1440" alt="Screen Shot 2022-02-14 at 12 45 38 PM" src="https://user-images.githubusercontent.com/24601296/153847989-86e13112-fbf7-43e6-8a43-013185de65da.png">

**Docker image pull into EC2 intance and run it (terminal interface)

<img width="1440" alt="Screen Shot 2022-02-14 at 12 18 41 PM" src="https://user-images.githubusercontent.com/24601296/153848047-df541649-0ff2-4bf5-ab98-412f660f4418.png">

**App running on EC2 instance 

<img width="1440" alt="Screen Shot 2022-02-14 at 12 18 31 PM" src="https://user-images.githubusercontent.com/24601296/153848106-0e6731b9-2738-425b-8971-d01f1378b316.png">


## Steps to run App
**Type it on terminal!**
1. Pull the App from docker 
       ** ```
        docker pull salwaalhajjaji/dockerizing-angular-ec2
        ```
        
2. Run the docker image 
        ** ```
        docker run –d –p 81:80 salwaalhajjaji/dockerizing-angular-ec
        ```
        
3. Paste this linl on your browser the app will run
    http://localhost:81

