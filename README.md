# LUIStoCLUBotFramework
Repo showcasing two bots built in Bot Composer. 

First was built by leveraging the built-in LUIS integration. 

Second was made by exporting the LUIS model from luis.ai, then importing it to language studio and using the HTTP endpoint for intent recognition.

# Usage

1. Import the bot projects to bot composer.
2. Fill in the LUIS information in the LUIS Bot app settings.
3. Run the bot, allow it to create your LUIS model.
4. Go to https://www.luis.ai and export your bot to JSON
5. Import the JSON to a new CLU project in https://language.cognitive.azure.com/. Capture the Ocp-Apim-Subscription-Key and place it in the CLU bot Unknown Intent trigger on the HTTP POST action headers.

# Feedback

Feel free to create an issue if anything is unclear on not working.

Feedback is appreciated.