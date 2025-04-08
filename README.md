# Ai-Solution-with-AzureCommunicationChat

This project demonstrates how to build a conversational bot using the [Microsoft Bot Framework](https://dev.botframework.com) integrated with [Semantic Kernel](https://github.com/microsoft/semantic-kernel). The bot retrieves and summarizes responses from an internal knowledge base to answer user questions in natural language.

## Project Status

This project is under active development and available for public use. Contributions are welcome.

## Prerequisites

Please follow the below 4 steps in [Add a bot to your chat app](https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/quickstart-botframework-integration#create-and-deploy-a-bot-in-azure)

1. Prerequisites
2. Create and deploy a bot in Azure
3. Get a Communication Services resource
4. Enable the Communication Services Chat channel: please save the Bot ACS Id for later use.

### Steps to deploy this CHATBOT sample
Please follow [the ChatBot Readme](./ChatBot/README.md) to deploy the ChatBot sample to azure.


## How to run the demo
1. Follow the steps in the [Add Chat to your app](https://learn.microsoft.com/en-us/azure/communication-services/quickstarts/chat/get-started?pivots=programming-language-csharp&tabs=windows) quickstart to create a chat app and a User Id.
2. Create a chat thread with 2 participant IDs, the Bot ACS Id created before and the User Id created in step 1. Save the thread id.
3. Access the [ACS Chat Thread UI](https://azure.github.io/communication-ui-library/?path=/story/composites-chatcomposite-join-existing-chat-thread--join-existing-chat-thread)
4. Provide the required information to join an existing Chat Thread. Then you can type the below 3 question. AI will retrieve the data relevant to the semantics of the user's question and provided an answer based on the data.
- My user ID is 110. I bought a laptop several days ago. Could you help to track the delivery?
- I’ve requested a return for my Power Bank. Any updates?
- I bought Bluetooth Earphones 2 days ago, but they haven’t been shipped yet. Why?

## Trademarks

This project may contain trademarks or logos for projects, products, or services. Authorized use of Microsoft 
trademarks or logos is subject to and must follow 
[Microsoft's Trademark & Brand Guidelines](https://www.microsoft.com/en-us/legal/intellectualproperty/trademarks/usage/general).
Use of Microsoft trademarks or logos in modified versions of this project must not cause confusion or imply Microsoft sponsorship.
Any use of third-party trademarks or logos are subject to those third-party's policies.
