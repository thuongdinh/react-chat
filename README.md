
# Chat App (chat-app)

> Chat Application with React.js, flux & Firebase

## Vagrant up

Vagrant help development envs are the same with all machines. First you need setup virtualbox & vagrant, to start, run: 

```bash
$ vagrant up
$ vagrant ssh # access to the vagrant env
```


## Running your project

The generated project includes a live-reloading static server on port `8080` (you can change the port in the `gulpfile.js` config), which will build, launch, and rebuild the app whenever you change application code. To start the server, run:

```bash
$ npm start
```

If you prefer to just build without the live reload and build-on-each-change watcher, run:

```bash
$ npm run build
```


## Generating Additional Code

You can add additional functionality to your application by invoking the subgenerators included in the Flux Generator. You can add components using the following commands:

#### Components
```bash
$ yo flux:component ComponentName
```

#### Actions
```bash
$ yo flux:action ActionCreatorName
```

#### Stores
```bash
$ yo flux:store StoreName
```
