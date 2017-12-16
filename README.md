# shamirgenerator
Shamir's Secret Sharing generator

This is a simple, basic html interface for splitting a secret into parts where you define how many parts are needed to recover the original secret.

You can use this to secure bitcoin private keys on paper, for instance printing 3 different keys on 3 different sheets of paper and distributing them to 3 different places. If one gets lost/stolen/destroyed/deleted, use the remaining 2 to recover the private key. Always test out your recovery process first! Do everything at your own risk. 

The project uses secrets.js (https://github.com/amper5and/secrets.js). The library is included in the repository so that the project has no dependencies and can be run in the browser of an offline computer for ultimate security.
