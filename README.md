## Alexa Skill to Using Google Gemini into Alexa Devices (dot, pop, etc)

## Prerequisites

- An [Amazon Developer account](https://developer.amazon.com/)
- An [Google Gemini API key](https://aistudio.google.com/app/apikey)
##

## Step-by-step tutorial
Log in to your Amazon Developer account and navigate to the [Alexa Developer Console](https://developer.amazon.com/alexa/console/ask).
- Creating the Alexa Skill
- Custome Skill Alexa-hosted (Python) na Alexa: (Create Skill)

- Name your Skill: Choose the name of your skill (ex: MyGemini)
- Choose a primary locale: English (US) or (DE/GB/BR/IN)
- Click Next, Under Experience type select: Other > Custom > Alexa-hosted (Python)
- In Templates : Click Import Skill
Enter the repository address: [https://github.com/Behzad9/Gemini-Alexa.git](https://github.com/Behzad9/Alexa-Gemini.git) and confirm.

## Configuring the Skill
When you finish importing in Invocations > Skill Invocation Name :
- Edit Skill and change Invocation Name . This will be the invocation command for your skill. If it meets the wording requirements and restrictions
- Click Save
- Build the Skill by clicking on Build Skill . When finished, go to the Code tab
- Create a file inside the Lambda folder called **.env** and add the line, adding the generated API key:
##
GOOGLE_API_KEY=your gemini API
##
Click Save and then Deploy

## Test Skill
When you finish deploying , go to the Test tab :
- In Skill testing is enabled in change from Off to Development
- Use the configured activation command to start the Skill, and you're ready to interact with Gemini through Alexa!
- The Skill will now be available on all Alexa devices linked to your account.
