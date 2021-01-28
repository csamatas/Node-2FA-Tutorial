[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

[![JavaScript Style Guide](https://img.shields.io/badge/code_style-standard-brightgreen.svg)](https://standardjs.com)

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on (tutorial coming soon).  
Specifically, the project will:

-   Get a phone number from the user
-   Send a verification code to the user's phone
-   Get the verification code from the user
-   Expire the verification code after a set amount of time
-   Verify the code

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Install the required packages

    ```bash
    yarn install
    ```

1. Configure environment variables within the .env file

    | ENV VARIABLE    | DESCRIPTION                                                                                                                                                                                                                                            |
    | --------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
    | ACCOUNT_ID      | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                                                                                         |
    | AUTH_TOKEN      | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                                                                               |
    | FC_PHONE_NUMBER | [FreeClimb Phone number](https://www.freeclimb.com/dashboard/portal/numbers) being used to send verification codes. To learn more, go [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb#section-2-get-a-phone-number) in Dashboard |

## Running the Tutorial

```bash
yarn start
```
