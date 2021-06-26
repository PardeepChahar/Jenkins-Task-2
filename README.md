This Task (Task 2) is given by Mr. Vimal Daga (LinuxWorld Informatics Pvt. Ltd.) for issuing the certificate for the Research Based Jenkins Training



*********************************************************************************************************



# Task 2, Subtask 1

## Problem:
Create docker container image that has jenkins installed using dockerfile

## Solution:

1. Create a repo in github that has my dockerfile
2. Add an agent system with docker installed
3. Create a job on jenkins(step 4-6)
4. Define system on which build to be executed
5. Add github repo
6. Define command to build the docker file


### Lets start with setup
1 Create a repo in github that has my dockerfile

![image](https://user-images.githubusercontent.com/75135128/123519626-2bb5ba80-d6ca-11eb-8a79-ebfe4b858c11.png)

2 Add an agent system with docker installed

![image](https://user-images.githubusercontent.com/75135128/123519657-4f790080-d6ca-11eb-934a-c55cdd05ac41.png)

3 Create a job on jenkins(step)

![image](https://user-images.githubusercontent.com/75135128/123519669-6cadcf00-d6ca-11eb-9a7b-bb7dbd0ced5c.png)

4 Define system on which build to be executed

![image](https://user-images.githubusercontent.com/75135128/123519693-851de980-d6ca-11eb-82d0-6bb1c7c85118.png)

5 Configure SCM (github repo)

![image](https://user-images.githubusercontent.com/75135128/123519717-a979c600-d6ca-11eb-9da7-4bd9095a680b.png)

6 Define command to build the docker file(on every build create image with increased version)

![image](https://user-images.githubusercontent.com/75135128/123519745-c615fe00-d6ca-11eb-95f3-83996b8b9014.png)

Final output of the build

Jenkins job output-

![image](https://user-images.githubusercontent.com/75135128/123519803-10977a80-d6cb-11eb-8ce4-c2dcfea9b19c.png)

Created images on Docker server-

![image](https://user-images.githubusercontent.com/75135128/123519856-60764180-d6cb-11eb-8770-61b6c1154cf4.png)


*********************************************************************************************************

# Task 2, Subtask 2

## Problem:
Launch the container with image created in subtask-1 and start the jenkins service in the container

## Solution:

1. Add an agent system with docker installed and have our image created in subtask-1
3. Create a job on jenkins
4. Define system on which build to be executed
5. Define command to launch jenkins



### Lets start with setup
1 Add an agent system with docker installed and have our image created in subtask-1
![image](https://user-images.githubusercontent.com/75135128/123519657-4f790080-d6ca-11eb-934a-c55cdd05ac41.png)

2 Create a job on jenkins
![image](https://user-images.githubusercontent.com/75135128/123521131-602d7480-d6d2-11eb-96da-f9e2470dc242.png)

3 Define system on which build to be executed
![image](https://user-images.githubusercontent.com/75135128/123519693-851de980-d6ca-11eb-82d0-6bb1c7c85118.png)

4 Define command to launch jenkins(here i use port 8280)
![image](https://user-images.githubusercontent.com/75135128/123521150-85ba7e00-d6d2-11eb-9662-2f88378fb809.png)


Final output of the build

Jenkins job output-
![image](https://user-images.githubusercontent.com/75135128/123521273-45a7cb00-d6d3-11eb-9945-7b3aa3e65c5e.png)

Lets open jenkins on browser(port is 8280)
![image](https://user-images.githubusercontent.com/75135128/123521245-1729f000-d6d3-11eb-9a46-3e17a66879a1.png)
After login-
![image](https://user-images.githubusercontent.com/75135128/123523109-4c3c3f80-d6df-11eb-97c5-9ff6b1417f54.png)


This Task (Task 2) is given by Mr. Vimal Daga (LinuxWorld Informatics Pvt. Ltd.) for issuing the certificate for the Research Based Jenkins Training



*********************************************************************************************************



# Task 2, Subtask 3

## Problem:
Create a job chain of job1, job2, job3, and job4 using build pipeline plugin in jenkins

## Solution:

1. Installl build pipeline plugin
2. Create job 1,2,3 & 4
3. Create a job chain of these 4 jobs 


### Lets start with setup

1 Installl build pipeline plugin
![image](https://user-images.githubusercontent.com/75135128/123524319-04b9b180-d6e7-11eb-8e06-0f667f2ae5c5.png)

2 Create 4 jobes
Check Build after other projects are built (Projects to watch: give job name to be build before this)

![image](https://user-images.githubusercontent.com/75135128/123524253-9674ef00-d6e6-11eb-9c64-b9367b7363fe.png)

job 1
![image](https://user-images.githubusercontent.com/75135128/123524099-adffa800-d6e5-11eb-8b1e-fa5a29fb641e.png)

job 2
![image](https://user-images.githubusercontent.com/75135128/123524111-ba840080-d6e5-11eb-93e9-1aeedf7de6db.png)

job 3
![image](https://user-images.githubusercontent.com/75135128/123524128-c8d21c80-d6e5-11eb-816f-ffb08fc5ec62.png)

job 4
![image](https://user-images.githubusercontent.com/75135128/123524137-d4bdde80-d6e5-11eb-88dc-9a6a585ffd3c.png)

Trigger build pipeline
![image](https://user-images.githubusercontent.com/75135128/123524160-16e72000-d6e6-11eb-99e6-e476f50db9b2.png)


