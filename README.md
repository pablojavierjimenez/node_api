# NOdeJS API Tutorial

This is a NodeJS API that intent implement that you need in a real world API at once and and from start.
i try to use common things like: JWT, Redis, Bcrypt,

**Nota:** here we use NodeJS v12.16 or higher

-----

## Steps: 
1. [Init Project](#1-Init-Project)
1. [Init Project](#2-Install-dependencies)

-----

### 1- Init Project
First to all, go to github (bitbucket, gitlab or whatever) and create a new repository, and then clone it to you local machine
to run project you can use the next commands
```bash
# Clonning from new clean remote repo
:~$ git clone git@github.com:myusername/my_my_node_api_project_name_project_name.git
# for V2
:~$ npm init
```
then you can see a new `package.json` file on your project like this:

```JSON
{
  "name": "my_node_ai_project_name",
  "version": "1.0.0",
  "description": "This is my new NodeJS API",
  "main": "index.js",
  "scripts": {
    "test": "echo \"Error: no test specified\" && exit 1"
  },
  "repository": {
    "type": "git",
    "url": "git+https://github.com/myusername/my_node_api_project_name.git"
  },
  "author": "",
  "license": "ISC",
  "bugs": {
    "url": "https://github.com/myusername/my_node_api_project_name/issues"
  },
  "homepage": "https://github.com/myusername/my_node_api_project_name#readme"
}
```

----
### 2- Install Dependencies

```bash
# Node dependencies
:~$ npm install express cors body-parser bcryptjs jsonwebtoken

# Node DEV-dependencies
:~$ npm -D nodemon jest
```




```bash
# for v1
:~$ npm run api:v1
```