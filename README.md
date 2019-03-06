## Cloud UI Take Home Exercise

As the next step in the interview process, we’d like you to complete a take home exercise.

Let's assume `deployments.json` is the API response you want to present to the user of a cloud service. Every day, we work with data similar to what you’ll find in the provided JSON file. It consists of a list of Elasticsearch deployments. Each deployment has a number of properties such as: is the deployment healthy, is its configuration currently being updated, is it a premium cluster, does it have Kibana enabled, and so on.

The task is to create a dashboard presenting the data in the provided JSON in a clear and intuitive manner that allows a user to see everything that is relevant to them, but without overwhelming them either.

You can use this project to set up the environment quickly. Feel free to add what you feel is necessary but please don't spend more than 3 - 4 hours.

You can install the project with

```
yarn
```

and start it with

```
yarn start
```

## About this repo

This app uses [React](https://reactjs.org/) and was generated using [create-react-app](https://github.com/facebook/create-react-app). This is meant to give you a head start so you don't have to worry about app setup. We have also added [React Router](https://github.com/ReactTraining/react-router) so you can easily setup additional routes if you'd like. We've also included the [Elastic UI Framework](https://github.com/elastic/eui) (EUI) for you to use.  The [EUI living style guide](https://elastic.github.io/eui/#/) provides plenty of examples for you to reference.

Feel free to do what you wish with the code from here!
