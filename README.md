How to get Open AI API Key?

Go to https://platform.openai.com/account/api-keys
Create a new Secret Key
Copy the Secret Key for your use.
How to get PlayHT User ID and PlayHT API Key?

Login to PlayHT - https://play.ht/
Go to https://play.ht/studio/api-access
Copy the User ID
Generate the Secret Key
Copy the Secret Key for your use.

**How to get the existing Voice Clone ID?**
- Go to https://docs.play.ht/reference/api-list-cloned-voices
- In the right side section, select language python
- Enter Authorization as Bearer XY***********AS
- Enter User ID Ac******v1
- Click on Try It you can see the id in the response
- Now you can use that id in the get_payload as value for voice

Adding Secret Variables in Hugging Face Account:

Open your Space
Click on Settings Button
Checkout to Variables and secrets section
Create New Secrets
Note: Make sure to add your below secret keys

OPENAI_API_KEY
PLAY_HT_API_KEY
PLAY_HT_USER_ID
PLAY_HT_VOICE_ID

