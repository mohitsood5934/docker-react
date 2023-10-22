# travis 

- Tell travis we need a copy of docker running
- Build our image using Dockerfile.dev
- Tell travis how to run our test suite
- Tell travis how to deploy our code to AWS


# Steps we need for automate our deployment
- Push your code from local system to github repo
- As our repo will receive a commit in master/main branch, travis will start the build process
- travis will run tests againt our commit
- if no error is present it will deploy the code to AWS
