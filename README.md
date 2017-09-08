# NetWarrior - A New Automatization service pen test Vulnerabilities with Nodejs

## Presentation
This is a web service for vulnerability detection and attack testing for penetration testing on a computer network.

It will be divided into two forms of execution:

- The service will be executed inside a server, where some specific pentest tools will be loaded, used of scans, snifers, being registered in a log, that will generate indicators of vulnerabilities.
- The service will be directed and personalized. Your service administrator will be able to schedule the times and tools you will use. In the case of choosing the tools, the administrator can select sources of attack tests, in which they will also be recorded in a log and processed as graphical indicators.


## Structure

Below is the structural hierarchy of the project
- Core: The entries and exits of internal services will be organized and directed
- Internal Services: They are those that interconnect with the Core. These services perform the transfer of information so that tools and other functions are performed.

The structure will work with couplings, that is, the core will be independent and the internal services coupled to it. This will be important for creating new services, adding new tools that work in complex ways, excluding services / tools and updating the entire structure, mainly the core in question.
