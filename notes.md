# Automating Workflow with Jenkins:


Jenkins--->Demo


[NodeJs]      [SpringBoot]    feature 
  |              |
  |              |
      [Github]               feature
         |
    [ Merge to main ]  main 
-------  |---------------------
    [   Linting     ]       JenkinsFile
         |
     Unit testing
         |
       Build
         |
       Deploy
         |


macbook-->Souce Code(SpringBoot/nodeJs)
ubuntu(linux)-->server

      ssh
[ ]-------->[ ]

personal     server  
computer
     
# server:

1.setup Jenkins on server
2.Jenkins Dashboard(config)
3.Attach Source code to Jenkins




# Architecture:
                      node

                      Agent  multiple-Executors ->Workspaces
  job
  ---> controller      Agent   
         node      
                      Agent

               
     [  Linux server ]


 
 