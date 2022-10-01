# kubernetes-yaml-definitions

kubernetes-yaml-definitions and a Sample voting application. 
For information visit the [kubernetes documentation](https://kubernetes.io/docs/home/)


## Here is how to deploy the voting application in this repo.

1. git clone ```https://github.com/vibuverma/kubernetes-yaml-definitions.git```


2. Then, ```cd kubernetes-yaml-definitions```

3. 
  3.1  To appy all at once - ``` kubectl apply -f voting-app/```

  3.2 To apply a specific file - ```cd voting-app```
       then - ```kubectl apply -f <file_name.yaml>```

