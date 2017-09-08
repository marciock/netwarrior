# NetWarrior - A New Automatization service pen test Vulnerabilities with Nodejs

## Presentation
This is a web service for vulnerability detection and attack testing for penetration testing on a computer network.

It will be divided into two forms of execution:

- The service will be executed inside a server, where some specific pentest tools will be loaded, used of scans, snifers, being registered in a log, that will generate indicators of vulnerabilities.
- The service will be directed and personalized. Your service administrator will be able to schedule the times and tools you will use. In the case of choosing the tools, the administrator can select sources of attack tests, in which they will also be recorded in a log and processed as graphical indicators.


## Structure

###Abaixo segue a hieraquia estrutural do projeto
-Núcleo: Serão organizadas e direcionadas as entradas e saídas dos serviços internos 
- Serviços Internos:São os que se interligam com o Core. Esses serviços realizam o translado de informações para que as ferramentas e outras funções sejam executadas. 

A estrutura funcionará com acoplamentos, ou seja, o núcleo será independente e os serviços internos acoplados ao mesmo. Esse procedimento será importante para a criação de novos serviços, adição de novas ferramentas que funcionem de forma complexa, à exclusão de serviços/ferramentas e a atualização de toda a estrutura, principalemente o núcleo em questão.
