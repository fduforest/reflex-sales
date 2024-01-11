# reflex-sales

Doc : https://reflex.dev/docs/getting-started/installation/
Demo : https://sales.reflex.run/

Reflex is available as a pip package. Install Reflex in your environment:

$ pip install reflex

Installing Reflex also installs the reflex command line tool. Test that the install was successful by running:

```
reflex init
```

https://reflex.dev/docs/getting-started/configuration/

## First initialize the database:

```
reflex db init
```

## Create a .env file with the OpenAI API Key
copy the .env-exemple file, rename it to .env and add your key

## Run the App
You can run this app in development mode:

```
reflex run
```

You should see your app running at http://localhost:3000
