# Java - Create Conference Tutorial

This project serves as a guide to help you build an application with FreeClimb. Specifically, the project will:

- Accept incoming calls
- Receive digits from the caller
- Create conferences
- Add participants to conferences

This application will receive calls and have users enter the conference code of the conference they wish to join. It will then either create the conference or add the caller to an already existant conference.

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://persephony-docs.readme.io/docs/getting-started-with-persephony).

## Setting up the Tutorial

1.  Configure environment variables.

| ENV VARIABLE | DESCRIPTION                                                                                                                               |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------- |
| ACCOUNT_ID   | Account ID which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard           |
| AUTH_TOKEN   | Authentication Token which can be found under [API Keys](https://www.persephony.com/dashboard/portal/account/authentication) in Dashboard |
| HOST         | The host url where your application is hosted (e.g. yourHostedApp.com)                                                                    |

## Building and Runnning the Tutorial

1. Build and run the application using command:

   ```bash
   $ gradle build && java -Dserver.port=3000 -jar build/libs/gs-spring-boot-0.1.0.jar
   ```
