# Useful Information for Robotics
* [Python Robotics](https://github.com/AtsushiSakai/PythonRobotics)

# Git Pull Request Flow

## clone or checkout
    
    $ git clone https://github.com/utotch/HelloWorld.git

## Make new branch
    
    $ cd HelloWorld
    $ git checkout -b pullreq-practice-blanch1 
    $ git status

## edit files

##  edit files

## test files

## commit to local repository
$ git commit -a -m “add pullreq beginning flow"
$ git status

<!-- -a means add all modified files -->

## push to remote
first push causes error since there are no remote branch to merge
[git push](http://neos21.hatenablog.com/entry/2017/05/10/080000)

we have to use “--set-upstream” or “-u” to create remote branch and merge it.

    $ git push --set-upstream origin pullreq-practice-blanch1

After second time, we don’t need to use “-u”

## add pull request

edit pull request at github site
