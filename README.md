# OAuth2_Login
Practical assignment for Identification and authentication course of the Master in Cybersecurity from UC3M

## Authentication steps
![oauth](https://user-images.githubusercontent.com/34543261/157105546-8d78833a-946a-46ad-b408-bbee3c210c6f.png)

1. Register a third-party application as a client to the provider:
    * Client receives unique client credentials from the provider.
    * You’ll use these client credentials to authenticate (prove who you are) to the provider later on.
2. The client sends a request to the provider’s authorization URL
3. The provider asks the user to authenticate (prove who they are)
4. The provider asks the user to consent to the client acting on their behalf:
    * Usually this includes limited access, and it’s made clear to the user what the client is asking for.
    * This is like when you have to approve an app on your phone to have access to location or contacts.
5.The provider sends the client a unique authorization code.
6. The client sends the authorization code back to the Provider’s token URL.
7. The provider sends the client tokens to use with other provider URLs on behalf of the user.
