# play-with-neo4j

### What does the devcontainer provide

* zsh!
* a neo4j community instance running at localhost:7474
    * the community version has some limitations like, there is only one db called neo4j, cannot add more. the admin user has to have the name neo4j...
    * well I will try the enterprise edition in k8s
* but for your app to use, pls use neo4j:7687 (its using a protocal called bolt)
* poetry!

### What does the app provide

* a structure where I provide an abstraction layer on neo4j driver, which means we can use other gragh db

### Notes on enterprise edittion