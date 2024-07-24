# SDK conformance tests

This repository contains the SDK conformance tests for the EnvoyX project. 

```
go install github.com/envoyproxyx/sdk-conformance-tests
```

## Running the tests

Assuming the EnvoyX binary and the shared library named `main` is in the current directory, you can run the tests with the following command:

```
# To run the all the tests
sdk-conformance-tests

# To run a specific test
sdk-conformance-tests --target=TestHelloWorld
```
