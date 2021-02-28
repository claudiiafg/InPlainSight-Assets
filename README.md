# InPlainSight-Assets

#### Deploy steps

To deploy /public by default, in project directory:

```firebase deploy``` 

or

 
```firebase deploy --only hosting```

```firebase deploy --only hosting:inplainsight-a47da```

Currently, the only service we're using is hosting, so either command is fine
If eventually we use more firebase services we should specify what exactly we're deploying


<br>

#### Setup steps
1. Install tools

    ```npm install -g firebase-tools```

2. Login

    ```firebase login```

3. See all projects

    ```firebase projects:list```

4. pick default project

    ```firebase use <project-name>```
    
    _this project is: **inplainsight-a47da**_

5. deploy  

    ```firebase deploy```


<br>

#### Firebase

Firebase [project URL][URL]


[URL]: https://console.firebase.google.com/u/0/project/inplainsight-a47da/overview
