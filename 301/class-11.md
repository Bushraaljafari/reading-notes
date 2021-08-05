# Reading 😏

## [What is OAuth](https://www.csoonline.com/article/3216404/what-is-oauth-how-the-open-authorization-framework-works.html)

What is OAuth?
OAuth is an open-standard authorization protocol or framework that describes how unrelated servers and services can safely allow authenticated access to their assets without actually sharing the initial, related, single logon credential

Give an example of what using OAuth would look like.
it look like aparking car employee

How does OAuth work? What are the steps that it takes to authenticate the user?
What is OpenID?
 OpenID is about authentication: as a commenter on StackOverflow pithily put it: "OpenID is for humans logging into machines

## [Authorization and Authentication flows](https://auth0.com/docs/flows)

What is the difference between authorization and authentication?
authorization is accessing data from machin to machine
authentication is accessing data from user to machine


What is Authorization Code Flow?
it is like a representation  code that will run when OAuth send the authorization, beacuase we can't see the structure of the code itself of this process, for that reason, they were implement the Authorization Code Flow for us.

What is Authorization Code Flow with Proof Key for Code Exchange (PKCE)?
Key to access your authorization
request the APIs.

What is Implicit Flow with Form Post?
for  public clients and for the applications that not secuered untill a certain limit.

What is Client Credentials Flow?
used with machine-to-machine (M2M) applications, such as CLIs, daemons, or services running on your back-end.

What is Device Authorization Flow?
used  with input-constrained devices that connect to the internet.

What is Resource Owner Password Flow?
uesd with highly trusted applications
