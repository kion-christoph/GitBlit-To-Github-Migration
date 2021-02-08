# Migration from GitBlit to Github

1. Generate SSH key
2. Copy and paste the generated SSH key (Public) in Gitblit and Github Enterprise cloud
3. Copy GitBlit Repository URL

4. open git Bash and then enter the command 
           `` $ git clone --bare GitBlit_Repo_URL``
5. list the repos
           ``$ ls``
6. Change the directory
          `` $ cd Directory_Name``
7. Create New repository in Github
8. Copy newly created repo URL
9. push cloned repository to GitHub Cloud / server
          ``$ git push –mirror GitHub_Cloud_URL``
10. verify the migrated code
