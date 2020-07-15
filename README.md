# SmartPracticeschool/SBSPS-Challenge-1241-AI-RECRUITER-SHORTLIST-A-SUITABLE-CANDIDATE-FOR-SPECIFIC-ROLE

The typical customer care chatbot can answer simple questions, such as store locations and hours, directions, and maybe even making appointments. When a question falls outside of the scope of the pre-determined question set, the option is typically to tell the customer the question isn’t valid or offer to speak to a real person.

In this project, there will be another option. If the customer question is about the operation of a device, the application shall pass the question onto Watson Discovery Service, which has been pre-loaded with the device’s owners manual. So now, instead of “Would you like to speak to a customer representative?” we can return relevant sections of the owners manual to help solve our customers’ problems.

To take it a step further, the project shall use the Smart Document Understanding feature of Watson Discovery to train it on what text in the owners manual is important and what is not. This will improve the answers returned from the queries.

# Scope of Work:
* Create a customer care dialog skill in Watson Assistant
* Use Smart Document Understanding to build an enhanced Watson Discovery collection
* Create an IBM Cloud Functions web action that allows Watson Assistant to post queries to Watson Discovery
* Build a web application with integration to all these services & deploy the same on IBM Cloud Platform

***The link to the chatbot is:
https://web-chat.global.assistant.watson.cloud.ibm.com/preview.html?region=us-south&integrationID=43456d14-1cef-47e2-8e2b-73226c9afd30&serviceInstanceID=c77d6e19-4365-462e-9605-55c12e2d0460***

