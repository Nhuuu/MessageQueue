# Lab: SQS - Message Queues

## Overview

For this lab, you will be creating a few Message Queues and Broadcasters and wiring them through code.

## Feature Tasks

- Create 3 Standard Queues
  - `QueueA`
  - `QueueB`
  - `QueueC`
- Create command line applications in Java that use these queues
  - Queue Publisher
    - Sends a message to a queue, using its ARN or URL
  - Queue Client
    - Receives messages from a Queue (by ARN) and displays them
  - Food for thought …
    - Which library will you choose to connect to the SQS system?
    - How can you librarize your own solution so as not to be esoteric to a single application?

## To Run

- logger: front-end React app
  - npm install
  - npm start
- sqs: back-end Java app
  - ./gradlew build
  - ./gradlew run

## Credits & Contributions

- @Bomi_bear
- Sapana Poudel
- Nicholas Paro
- Jack Kinne
- Matt Stuhring
- Joachen Busch
- Brandon Hurrington
- Travis Cox

https://docs.aws.amazon.com/lambda/latest/dg/with-sqs-create-package.html#with-sqs-example-deployment-pkg-java