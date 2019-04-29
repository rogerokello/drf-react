# Application shows how to integrate React with Django rest framework(drf)

## Introduction
This application shows how one could be able to integrate react with django restframework
without necessarily having to create two separate repositories like in a microservice archicture

## Development
I used Django Rest framework's ModelSerializers to ensure I create an endpoint to create and view various leads. 
I then created an entry point into React by creating a separate Django App that loaded a template that was meant to have the React Application injected into it.
I managed to also configure React to also use a tag in the template as an entry point for it.

## Test
Frontend testing framework carrying out the integration tests is cypress

