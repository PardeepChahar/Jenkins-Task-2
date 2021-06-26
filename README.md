This Task (Task 2) is given by Mr. Vimal Daga (LinuxWorld Informatics Pvt. Ltd.) for issuing the certificate for the Research Based Jenkins Training



*********************************************************************************************************



# Task 2, Subtask 1

## Problem:
Create docker container image that has jenkins installed using dockerfile

## Solution:

1. Create a repo in github that has my dockerfile
2. Add an agent system with docker installed
3. Create a job on jenkins(step)
4. Define system on which build to be executed
5. Add github repo
6. Define command to build the docker file


### Lets start with setup
1. Create a repo in github that has my dockerfile

![image](https://user-images.githubusercontent.com/75135128/123519626-2bb5ba80-d6ca-11eb-8a79-ebfe4b858c11.png)

2. Add an agent system with docker installed

![image](https://user-images.githubusercontent.com/75135128/123519657-4f790080-d6ca-11eb-934a-c55cdd05ac41.png)

3. Create a job on jenkins(step)

![image](https://user-images.githubusercontent.com/75135128/123519669-6cadcf00-d6ca-11eb-9a7b-bb7dbd0ced5c.png)

4. Define system on which build to be executed

![image](https://user-images.githubusercontent.com/75135128/123519693-851de980-d6ca-11eb-82d0-6bb1c7c85118.png)

5. Configure SCM (github repo)

![image](https://user-images.githubusercontent.com/75135128/123519717-a979c600-d6ca-11eb-9da7-4bd9095a680b.png)

6. Define command to build the docker file(on every build create image with increased version)

![image](https://user-images.githubusercontent.com/75135128/123519745-c615fe00-d6ca-11eb-95f3-83996b8b9014.png)

Final output of the build

Jenkins job output-

![image](https://user-images.githubusercontent.com/75135128/123519803-10977a80-d6cb-11eb-8ce4-c2dcfea9b19c.png)

Created images on Docker server-

![image](https://user-images.githubusercontent.com/75135128/123519856-60764180-d6cb-11eb-8770-61b6c1154cf4.png)


*********************************************************************************************************

