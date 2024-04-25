# How to Contribute to This Project
To get started in contributing to this project, install and build the source code by following the instructions here: https://github.com/SP24-CSCE482-capstone/code-submission-documented-code-github-documentation-aheff20/blob/main/docs/Build%20From%20Source.pdf

These instructions take you through the steps of downloading the code, setting the proper envrironment variables, and configuring all the different dependencies. 

With the code base set up, you can begin contributing to the project. Development should occur outside the main branch, so either create a new a branch or work out of the dev branch.

## Finding Issues
There is much that can be expanded upon in this project, such as creating new network configurations, expanding our library to other mainstream SDKs, and integrating into other existing network services. Any of these would help expand our project and further the understanding of post-quantum cryptography in the world. 

## Coding Guidelines
Code provided to this project should follow the structure currently exhibited in the code. The qs509 library should split all the functions into their specific function. For example, all cert functions should exist in cert.go. Any function should also have a corresponding testing file, of which contains functions that test every execution path of the function they test. 

For the client and server applications, the main server.go and client.go files should be kept as minimal as possible. Helping functions or resuable functions should be defined in their own files and then imported to encourage dry coding. 

## Documentation
All future code expansions should feature their own forms of documentation. These should follow the format of the examples shown here: https://github.com/SP24-CSCE482-capstone/code-submission-documented-code-github-documentation-aheff20/tree/main/docs

## Committing Changes
Once your changes have been developed and tested and are ready for commit, please commit them to the dev branch or the branch you are operating out of. These changes will be merged in once approved by an administrator of the repository. 

## Review Process
All changes committed should be reviewed by and confirmed by at least two other developers.

