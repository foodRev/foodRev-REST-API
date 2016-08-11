# foodRev-REST-API

Starting Architecture of the foodRev REST API

https://firebase.google.com/docs/reference/rest/database/

## Request for a Branch + API Key:

* contact gskielian, and request a branch and API keys

## Test out your access:

Once you have your sandboxed branch, go ahead and test out with the following commands:

### GET

#### Get entire branch:

```sh
curl 'https://<firebase-url>.firebaseio.com/<your-branch>.json'
```

#### Get a particular sub-list:

```sh
curl 'https://<firebase-url>.firebaseio.com/<your-branch>/<some-list>.json'
```

### PUT

```sh
curl -X PUT -d '{"value_name" : "sample_value"}' 'https://<firebase-url>.firebaseio.com/<your-branch>.json'
```
