# challenge-node-concepts
![banner](https://user-images.githubusercontent.com/19713358/85228409-b4b05c80-b3b9-11ea-8f44-a55134eb2b2e.png)
This repository is about Go Stask challenge

## Description

This project is a node API challenge (CRUD) that you can manage your repositories.

| Description | URL | Method |
| --- | --- | --- |
|Create | /repositories | POST
|Update | /repositories/:id | UPDATE
|Delete | /repositories/:id | DELETE
|Add likes | /repositories/:id/like | POST

## Get started

Install and run
```console
npm i

npm run dev
 
```

## Run Tests

Run tests and generate coverage files 
```console
npm run test

npm run test:coverage - generate coverage info
 
```
#### Coverage Info
![coverage](https://user-images.githubusercontent.com/19713358/85227968-f4c21000-b3b6-11ea-90bf-11b540b333d4.png)

## Insominia

Insomnia documentation

```console
npm run insomnia-doc

cd insomnia-documentation

npm run insomnia-run
 
```

Add workspace in your Insomnia

Before install 
<a href="https://insomnia.rest/download/" target="_blank">Insomnia</a>


<a href="https://insomnia.rest/run/?label=challenge-node-concepts&uri=https%3A%2F%2Fchallenge-node-concepts" target="_blank">
  <img src="https://insomnia.rest/images/run.svg" alt="Run in Insomnia">
</a>
