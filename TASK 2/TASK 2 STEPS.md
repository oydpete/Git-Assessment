# **TASK 2**

## Team Collaboration (Pair Programming)**

### Step 1

One student should create a new repository and invite a team member as a collaborator.

 * The Colaborator is [Daniel](https://github.com/Daniel4000-dev/team-collaboration)

 * The Invite was recieved

   ![alt text](<../>) 


### Step 2

The owner should create an `index.html` file and push it to `main`. 

Here is the owner's 'Index.html' file [Link here](https://github.com/Daniel4000-dev/team-collaboration/blob/main/index.html)


### Step 3 

The collaborator should clone the repo, create a new branch (`update-styles`), and modify `index.html` by adding a `<style>` section.


 code :    
 
           git clone http            #clone Repo
 
           git status                #Be sure the Repo is there  
           
           git checkout -b update-styles


## Modify Htmml


## From            
               <!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <meta name="description" content="" />
        <title>Welcome to Nexascale</title>
    </head>
    <body>
        <header>
            <h1>Welcome to Nexascale</h1>
        </header>
        <main>
            <div>
                <p>This is a DevSecOps Team Collaboration Project</p>
            </div>
        </main>
        <footer></footer>
    </body>
</html>







## To

              <!DOCTYPE html>
         <html lang="en">
            <head>
              <meta charset="UTF-8">
              <meta http-equiv="X-UA-Compatible" content="IE=edge">
              <meta name="viewport" content="width=device-width, initial-scale=1.0">
              <meta name="description" content="" />
           <style>
            body {
                background-color: rgb(226, 234, 236);
                font-family: Trebuchet, sans-serif;
            }
            header h1 {
                color: rgb(211, 15, 25);
                text-align: center;
                font-family: Trebuchet;

                }
            main p {
                font-size: 1.3em;
                text-align: center;
                font-family: sans-serif;
            }
        </style>
        <title>Welcome to Nexascale</title>
    </head>
    <body>
        <header>
            <h1>Welcome to Nexascale</h1>
        </header>
        <main>
            <div>
                <p>This is a DevSecOps Team Collaboration Project</p>
            </div>
        </main>
        <footer></footer>
    </body>
</html>


### Step 4

The collaborator should commit and push the changes, then open a PR.
 
### Step 5 

The repository owner should review, approve, and merge the PR.

### Step 6

Both students should pull the latest changes to their local machines
