### Usage: [Any Git Command] [foreach \<Any Git Command\>] [clone] [help]

#### gits \<Any Git Command\>
* Run git command for each git repo and print the first 10 lines of result.

#### gits foreach \<Any Git Command\>
* Run git command for each git repo without any limit.

#### gits clone
* Read each line from .gitrepositories and pass it to 'git clone' command as arguments.  
  Create your own .gitrepositories file like this in the root of your project.  
  > git@xx.git # clone git repo  
  > git@yy.git library/LibYY # clone git repo to target dir
