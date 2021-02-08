# Migration from GitBlit to Github

1. Generate SSH key
2. Copy and paste the generated SSH key (Public) in Gitblit and Github Enterprise cloud
3. Copy GitBlit Repository URL
![image_1](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/1.png)
4. open git Bash and then enter the command 
           `` $ git clone --bare GitBlit_Repo_URL``
 ![image_2](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/2.png)     
5. list the repos 
           ``$ ls``<br>
 ![image_3](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/3.png) 
6. Change the directory
          `` $ cd Directory_Name``<br>
  ![image_4](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/4.png)
7. Create New repository in Github
![image_5](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/5.png)
![image_6](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/6.png)
8. Copy newly created repo URL
9. push cloned repository to GitHub Cloud / server
          ``$ git push –mirror GitHub_Cloud_URL``
![image_7](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/7.png)
10. verify the migrated code
![image_8](https://raw.githubusercontent.com/Rajeshcn02/GitBlit-To-Github-Migration/main/images/8.png)
