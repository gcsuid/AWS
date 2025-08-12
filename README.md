# AmazonLexBot

Created documentation to avoid being charged.

1. configured a new bot, BankerBot. 
2. Under IAM permissions, allowed basic Amazon Lex Permissions, set idle session timeout.
3. Set Intent classification to 0.40 meaning if the bots confidence value would be less than that value, it'll throw FallbackIntent with a defined MessageGroup for variations.
4. Created Welcome Intent with a descriptive closing response

# second session

FOR SLOTS
1. put in restrict values to use user specified values only.
2. added a new intent check balance intent for added verification.

# third session
since chatbot cant stir up stuff, we add lambda
1. lambda is a code server that helps us run any code on cloud, without servers or computers.
2. <img width="302" height="153" alt="image" 
     src="https://github.com/user-attachments/assets/e53f730e-0588-452d-b3e6-491dcf881a04" />

     configured lambda using python3.
3. created a random function in lambda to use this code, this function in python gives random number on go so we pretend as if we have a number.
<img width="310" height="122" alt="image" src="https://github.com/user-attachments/assets/235e09c0-86e0-4508-936c-05b675f43e75" />
4. created an alias "TestbotAlias" for the banking bot, that helps us connect with other aws services 
updating an alias helps to update the usage, instead of updating the application.
5. configured fulfillment in the initial intent, used code hooks(connects application to custom aws services)

# 4th session

1. aim is to define and get rid of monotonous birthday asking function slots such that it doesn't get hooked on to one.
2. Here enters context tag, two types: output and input context tags.
3. <img width="302" height="134" alt="image" src="https://github.com/user-attachments/assets/1cab54f4-efc4-49ba-b4fc-d2c1e07267e7" />
4. New Intent, to follow up after that question.
5. added new slot, for follwoing up to the above intent.
            
# 5th session
1. checked the visual creator that helps us create various workflows that working on our page.
