# aouth2GithubApp

SpringBoot documentation: https://spring.io/guides/tutorials/spring-boot-oauth2/

Dependencies:

![dependencies.png](src%2Fmain%2Fresources%2Fstatic%2Fdependencies.png)

The web application flow to authorize users for your app is:

- Users are redirected to request their GitHub identity
- Users are redirected back to your site by GitHub
- Your app accesses the API with the user's access token
