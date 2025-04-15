## How to build and deploy this CHATBOT sample

1. **Open the ChatBot folder in Visual Studio Code.** Ensure you use VS Code, as it supports AAD Authentication in code deployment.
2. **Install the Azure App Service extension in Visual Studio Code**.
3. **Sign in to your Azure account** in Visual Studio Code by clicking the Azure icon in the Activity Bar on the side of the window.
4. **Build the project in Release mode** and output the generated files to the `./bin/Publish` folder within your project directory by running the following command in the integrated terminal. You need to navigate to the specific project folder (which should contain the `.csproj` file) before running the command:
```
dotnet publish -c Release -o ./bin/Publish
```
* This command will generate two folders, "bin" and "obj".
5. **Deploy to Web App** by right-clicking on the newly created `/bin/Publish` folder and selecting "Deploy to Web App."
6. **Choose the Azure App Service web app** you want to deploy the application to and confirm deployment.
7. **Visit your web app's URL** once the deployment is complete. You'll see a notification in Visual Studio Code, and you can visit your web app's URL to see the updated application running live.