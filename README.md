#### Project Setup
In order to spin up the project, in the root create .env with these two variables, with your own values.

```
MONGO_URI JWT_SECRET
```

After that run this command
```
npm install && npm start
```


Swagger UI

```
/jobs/{id}:
  parameters:
    - in: path
      name: id
      schema:
        type: string
      required: true
      description: the job id
```

![Screen Shot 2022-12-07 at 11 41 12 AM](https://user-images.githubusercontent.com/60779542/206117932-76f8fc33-1f19-4d51-a7c1-885e3d285b60.png)
