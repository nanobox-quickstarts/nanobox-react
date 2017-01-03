![React from Scratch](https://guides.nanobox.io/assets/quickstart-icons/react.png)

# React from Scratch

Run an React app locally, install nothing besides nanobox.

<a href="https://nanobox.io/download"><img src="https://guides.nanobox.io/assets/quickstart-icons/download.png" /></a>


## Clone the repo

```bash
# clone the code
git clone https://github.com/nanobox-quickstarts/nanobox-react.git

# cd into the react app
cd nanobox-react
```

## Run the app

```bash
# Add a convenient way to access your app from the browser
nanobox dns add local react.dev

# Add environment variable to set the dev host to 0.0.0.0
nanobox evar add local HOST=0.0.0.0

# Run react as you would normally, with 'nanobox run'
nanobox run yarn start
```

## Check it out
Visit your app at <a href="http://react.dev:3000" target="\_blank">react.dev:3000</a>

## Explore

With Nanobox, you don't have to have anything installed on your machine to run your app:

```bash
# drop into a Nanobox console
nanobox run

# where node is installed,
node -v

# yarn is installed,
yarn --version

# and your code is mounted
ls
```

## Now What?
For more details about running react apps with nanobox visit [guides.nanobox.io/javascript/react/](https://guides.nanobox.io/javascript/react/)

<a href="https://nanobox.io"><img src="https://guides.nanobox.io/assets/quickstart-icons/footer.png" /></a>
