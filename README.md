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

