### Getting started


#### Install dependencies

```bash
npm install
```

#### Run the project


```bash
npm start
```

#### Build Docker image


```bash
docker build -t eu.gcr.io/$PROJECT_ID/simple-express:0.0.1 .
```

#### Push the Docker image to Cloud Registry


```bash
docker push eu.gcr.io/$PROJECT_ID/simple-express:0.0.1
```


## Code linting

You can run the linter with:

    npm run lint:fix # This will try to fix errors automatically
