# git-summary-basic
Basics about git you should start with it .
## Table of Content

 -  what is git and github
 - why is that useful in our case 
 -  alternative for github
-   git sheet
> "all important commands"
- CICD
- agile board 
- github actions "devops"
-   **git flow** 
-   pull requests  

> "how to deal with it"

-   conflicts 

> "mostly common thing happen with developers "

-   contributes 

> " how to be a great developer"

-   readme file
 

## why is that useful ?
we faced many cases in our projects like nettinghub , internal projects

**Version Control**
we found that web have many versions (version_2 ,version_3 ,CICD , Portal ..)
each one take a storage on our server and With the passage of time we will forget what happen in this versions or even how we can take some code from version_3 to version_2 or in internal projects 
**no more for** 
`login_internal_1.php , login_internal_2.php , register_customer_1 , register_customer_last.php , register_customer_last_last.php`  

**Collaboration**
keeps recording how did what and when.
i need to know what fixes any one made before in this function or even get back to previous code and get some logic from it 

**Documentation**
i need for any new developer understand the work quickly and keep on track with other team .

**Features**

 - all team can work in same project and know what happen to the code .
 - we can create new features without worrying about production or mobile app crashing
 - we will have a backup if any thing happen we can get back to last stable version any time
 - github have devops tools like you can upload the code each time you add code ,you don't need to deploy to server each time it's called github actions
 - any one can see the project status 
 


## What is gitflow
![enter image description here](https://expressus.io/uploads/beautiful-gitflow-workflow-diagram.png)

we have a default branches like 
master => the production branch
hotfix => if you have any emergency fixes get from master -> edit ->push to master -> develop git from it before release
release => new stable testable version that ready to pushed to master
develop => dev team work on it pull and push
feature => dev team how worked in a new feature after finished it push to master
so we have organised project we can keep track with all project

> there is alot of branching strategy like github flow,gitlab flow and trunk flow each one has his pros and cons so you can check them . 

  
