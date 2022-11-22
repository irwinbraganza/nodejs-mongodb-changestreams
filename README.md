# nodejs-mongodb-changestreams

node.js with mongo change streams

credits: Lauren Schaefer | https://www.mongodb.com/developer/languages/javascript/nodejs-change-streams-triggers/

# prerequisites

- setup mongo cluster with sample data. ref: https://www.mongodb.com/docs/charts/tutorial/order-data/prerequisites-setup/#load-the-sample-data

- create .env with MONGODB_URI env having connection string from the cluster created above

# install

```
npm i
```

# run

run in seperate terminals

## listening to changeStreams

```
node changeStreams.js
```

## change data in db

```
node changeStreamsTestData.js
```
