# React-FDP-1
All the discussions and examples given in the FDP can be seen here.

#  Web Design Using React Js


# Day Wise -01


## What is web design ?
   Creating a website or webpage either static or dynamic is known as Web design


## What is web development ?
   Maintaining the Website and storing the data (can also perform inserting,deleting)
   

## Software Requirement:
    
    1.Text Editor: Sublime Text3,Visual Code Editor
    
    2.Git
    
    3.Node Server or Web Server For Chrome
    
    

## Installation and Importance of Git,GitHub.


**Git Hub**->Git Hub is an distributed Version Control System used to deploy a project and we can also contribute to others project
  Usage: Open Source and contains versions of our project
  
 
 **Git**->Git is a tool used to maintain snapshots of the project,Git Hub Uses Git.
  
  
  Installation : Link please Click Here [GitInstallationlink](https://www.git-scm.com/)
  
  
  After Installing open Git Bash Here 
  
  
  Commands to Synchronize from repository to local folder:
  
  
  1.  **git config --global user.name "name"** -> This Command configures username in git
  
 
  2. **git config --global user.email "mailid"** -> This Command configures mailid in git
  
     **git init** ->Initializes the git
  
  
  3. Open your Git Hub Account and create a New Repository ,make it as public and create a Readme.md file(For documentation in markdown)
  
  
  4. Clone the Repository ->copy the url
  
  
  5. **git clone paste the url** ->This Command will create a folder in your desktop with the same name of your Repository
  
      If you observe your local folder it contains two folders 1..git(hidden file)
                                                               2.Readme.md file
                                                           
  
  6. **ls**->This command will give the list of files
  
 
  7. **touch index.html**->create a file in local folder
  
  
  8. **mkdir css** ->create a folder in local folder
  
 
  9. **mkdir js** ->creates a js folder in local folder
 
 
 10. **mkdir image**->creates a image folder in local folder
 
 
 11. **git status**->Will check the status of the git
 
 
 12. **git add .**->will add all the files from untracking area to tracking
 
 
 13. **git commit -m "commit message"**->will commit the changes that we have done
 

 14. **git remote**->will check the remote(default one is origin)
 
 
 15. **git push remotename master** ->will push the file from local folder to repository
 
 
 # Day Wise -02
 
 
 * Installing Sublime Text Editor 3 : [SublimeText3 Installation Link](https://www.sublimetext.com/3)
 
 
 ## What is Html
    Html stands for Hyper Text Markup language used to create web pages
    For Working with Html we need a Text Editor
 
 * Version of Html is 5
 
 ### Types of Elements in Html5:
                               1. Block-level elements
                               2. In-Line Elements
                               3. Semantic Elements
                               4. Navigation
   
   
   
   #### Block-level Elements: Occupies Complete Width Of The Screen 
                             1. All heading tags(<h1>,...<h6>)
                             
                             2. paragraph Tag(<p>)
                             
                             3. All Semantic Elements
   
   
   #### In-Line Elements: The content will come side by side
                          1. Span Tag
                          
                          2. Image Tag
                          
                          3. Nav Bars
                          
                          4. Form Control Events
                          
   #### Semantic Elements : This Elements are used to divide the Homepage it contains Description
   
                            1. Section
                            
                            2. article
                            
                            3. aside
                            
                            4. header
                            
                            5. footer
                            
                            6. main
                            
                            
 #### Navigation Elements : This Elements are used to navigate or to link the content from one page to another or with in the page.
                          
                          It uses <a, href> Tag.
                          
                          1. In bound
                          
                          2. Out Bound
                          
                          3. Mailto
                          
                          4. tel
                          
                          
 ## CSS : (Cascading Style Sheet)
         * Adds beautification to html page *  
         
 **Syntax** : Selector{Property:value}
 
 
 #### Selector: To add styles we have to select the content for that we need selectors
 
 ##### Types of Selectors:
                          1. Class Selector(.)
                          
                          2. Identifier Selector(#)
                          
                          3. Element or Tag Name Selector
                          
                          4. Descendant Selector
                             .parent #child(Tag)
                             
                          5. Child Combiner
                              .parent > #child(Tag)
                              
### Types of CSS:
                 
                  1. Inline CSS
                  
                  2. Internal CSS
                  
                  3. External CSS
                  


## Daywise-03

#### Flexboxes:
               These are the advanced concepts of css grids.


###### Flex-Properties: 
                       1. display: flex; (primary property)
                       2. flex-direction
                       3. flex-wrap
                       4. justify-content


###### Rules:
              1. we have to create a parent using divison or semantic elements
              2. we should have a child in it.
              
#### Different types of properties and values

## 21-05-2020
____

### Bootstrap : [Download](https://getbootstrap.com/docs/4.5/getting-started/download/)
   * Easy to integrate
      * _We can integrate different parts of project together without any conflict_
   * Responsive design
      * _By using bootstrap, we can design a web page for various screen resolutions_
   * Browser Compatibility
      * _The modern browsers such as Firefox, chrome, opera, Edge, Safari supports this bootstrap_
      
      
### Color codes :
   Color code | Color 
   ------|------
   **Primary** | Blue
   **Secondary** | Grey
   **Danger** | Red
   **Warning** | Orange
   **Success** | Green
   **Info** | Sky blue
   **White** | White
   **dark** | Black
   **light** | Light grey
   **muted** | Disable
   
### Screen resolutions
   * xs
      * eXtra small
   * sm
      * Small
   * md
      * Medium
   * lg
      * Large
   * xl
      * eXtra Large

## 25-05-2020
____

* Map()
* Arrow functions
* Ready states
   * `0`   =>  Request not initialized
   * `1`   =>  Connection between client and server is established
   * `2`   =>  Server received the request
   * `3`   =>  Servers process the request
   * `4`   =>  Ready to respond

* Errors in the communication
   * `1`  =>  Navigational Errors, Ex: 101 destination not found
   * `2`  =>  Success messages, Ex: 200 Ok 
   * `3`  =>  Data errors, Ex: 303 Error at particular line
   * `4`  =>  Client side errors, Ex: 404 Client side errors
   * `5`  =>  Server side errors, 500 Internal server error, 503 Time out

* Promises
   * States in promises:
      * **Pending** : Neither Success Nor Rejected
      * **Success || fulfilled** : Request completed successfully.
      * **Rejected** : Request rejected
      * Examples: Fetch, Cache

## 27-05-2020
____
* Download [nodejs](https://nodejs.org/en/) and install.
   * `node -v`
   * `npm -v`
* Installation procedure for react
   * `npm install create-react-app -g` (Installing react)
   * `create-react-app <project_name>` (Creating a react project)
* File structure of react project
   * node_modules
   * public
      * index.html
      * favicon.ico
      * manifest.json
      * ROBOTS.txt
   * src
      * index.js
      * App.js
      * App.css
      * index.css
      * Test.js
      * settest.js
      * serviceWorker

* Features of **React**
   * Component based library
   * It uses VirtualDOM
   * JSX
   * Performance
   * Simplicity (Leraning curve is high)

* Real DOM vs Virtual DOM

* Class Component
   * class keyword, Component
   * Need to use render method for returning a value
   * stateful component
      * state => Maintains storage area
      * setState => Manipulate the info in the state

* functional componant
   * function keyword
   * stateless component

## 28-05-2020
____
* Composition of Components
* Styling of the components
* States in class components
* `setState()`
* Hooks in functional components
   * `useState`

## 29-05-2020
____
* Props (properties)
   We can pass information from one component to another.
* Props in functional component: We used the parameter along with the property key for getting info.
* Props in class component: We used `this.props.key` for getting information from a component.

Test.js

<img src="props1.png" alt="props" />

Sample.js

<img src="props2.png" alt="props" />
                          
 
 
                             
   
                      
 
 

                                                           
                                
