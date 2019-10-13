# Project 4
## Static Web Design


***

## Overview
The Code Fellas team was tasked with redesigning a static web site. The site chosen was Professor Dey's [website](http://web.cse.ohio-state.edu/~dey.8/). The app is equipped with Middleman framework (https://middlemanapp.com). 


## Instructions

### To view the redesigned website:
1. Enter the following command in the terminal to check if there is Bundler installed:
  ```
   $ bundle -v
  ```

  If bundler was not appear, you would have to install it:

  ```
   $ gem install bundler
   $ rbenv rehash 
  ```

2. Install gems by using Bundler:

  ```
   $ bundle install # install gems 
  ```

3. Choose one of the following methods to run the application

    - With build folder:

        - Create static files for each file located in your source folder.
        ```
          $ bundle exec middleman build
        ```
        - Open the *build* folder inside the main project folder.

        - Open the *index.html* page in Firefox.

   - With middleman server:
        - start the preview web-server

        ```
          $ bundle exec middleman server
        ```
        - Open  *localhost:4567* in Firefox.
***

## Developers:
* Bowen Li
* Feifan Lin
* Dana Shkokani
* Mengying Xie

##Gems Dependencies:
* middleman >=4.2
* middleman-livereload

