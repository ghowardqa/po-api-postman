# DummyJson example postman project

### Post office API test assessment task

This is a repository that contains postman collection and environment. The collection has tests that verify that the diffferent endpoints are working as expected. I have added a github workflow which will run these tests nightly to verfiy that no API changes have had an adverse affect.

The API used to test is the Carts endpoints on the dummyJSON project
https://dummyjson.com/docs/carts

## Setup

install newman locally

```
cd Project root
npm install -g newman
```

## How to run tests locally

```
npm run test
```

## What's next

Next thing to do on this project to iterate and expand the test coverage. Another improvement would be to include the use of mocks to verify different responses. Performance testing of these would be another addition to include to ensure that the can handle load under stress conditions.
