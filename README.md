# Lubbock Covid Chatbot

## How to Run this Chatbot
This chatbot can be used by utilizing any of the following implementations.

### Implementations
1. Dialogflow Web Demo: https://bot.dialogflow.com/028b0f1d-8ad2-4bb9-a661-8ff7e69172f1
2. Dialogflow Phone Gateway: 605-215-5287
3. Google Assistant: Coming Soon [Under Review by Google]
4. Skype Bot: Coming Soon

## Intents Implemented
1. covid.at_risk
2. covid.cleaning
3. covid.contact
4. covid.goodbye
5. covid.immune
6. covid.incubation
7. covid.mask
8. covid.precautions
9. covid.screening
10. covid.student_mask
11. covid.student_test
12. covid.student_test_positive
13. covid.test_negative
14. covid.test_positive

## Intents Not Implemented
1. Built in screening system
1. COVID-19 Case Count reporting
1. Big Query Integration
1. Maps API Integration

## Example flows
These examples represent a small portion of the intents the agent can respond to. This agent is designed to answer many frequently asked question about COVID-19 in Lubbock. The agent can tell the user either campus or local mask mandates as well as provide reasources for more information.
1. How do I protect myself from Covid?
2. Am I immune from coronavirus?
3. I am a student and need to be tested.
4. I am a student and tested positive.
5. What are the campus mask mandates?
6. Is there a mask mandate in place?
7. How to clean my house?
8. Am I at risk for Covid?
9. What is the incubation period for coronavirus?
10. What does a positive test mean?
11. Can I test negative and test positive later.

## Information
While Google and Verily have published a COVID-19 Virtual Agent (found in the sources), my implemented chatbot has been completely designed from the ground up with information specifically about Lubbock, TX and Texas Tech University. The Virtual Agent created by Google and Verily has been used as inspiration for this project. I have also chosen to use the Google/Verily surfaces and covid-19 entities, however many changes have been made to these entities. Intents, repsonses, and training phrases are custom to this chatbot and trained specifically for Lubbock and Texas Tech. The Lubbock Covid Chatbot utilizes the Dialogflow ML system for determining responses for the user's question, as well as attempting to automatically correct spelling from the user before a query is preformed. The ML system also allows for automatic training of the agent and agent validation.

## Sources
1. Google, Rapidly build and deploy a virtual agent using Dialogflow templates, https://cloud.google.com/dialogflow/es/docs/tutorials/covid19-rapid-response, 20 November 2020.

## Disclaimer
All information provided by this chatbot is designed to be a resource for finding more information related to COVID-19 and presents no medical diagnostics. Please see a medical specialist if you are experiencing any COVID-19 symptoms.
