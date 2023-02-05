# ChatGPT library for UiPath

This is a simple UiPath library for calling ChatGPT api.

Simply call this workflow file with parameters

![image](https://user-images.githubusercontent.com/32192638/214518179-744ef543-9637-4c14-abdd-ce54f45aa70c.png)

In the strAPIKey value textbox, you can get the api key from OpenAI account , see https://beta.openai.com/account/api-keys

It should looks this : "sk-123456789123456789012345678901234567890123456789"    ( this is an expired key )


Below demo shows that the main workflow in UiPath is going to be very simple due to this.

![image](https://user-images.githubusercontent.com/32192638/214518547-b47eed3e-21d9-4baf-b307-6f10bd221809.png)


Where to get this library ? Just download from this github page.
https://github.com/WingsMaker/uipath_chatgpt/blob/main/chatgpt_uipath.xaml


Here is the workflow of the library, the main language in used for code is VB ( visual basic ).

![chatgpt_main](https://user-images.githubusercontent.com/32192638/214519029-2c9aa47c-f435-4ac5-ad8a-88d055c0f19d.jpg)

What does UiPath calls the ChatGPT api in coding aspect ?

It takes payload and headers parameter.

![image](https://user-images.githubusercontent.com/32192638/214522546-59856601-75d9-413b-9b72-4c5945a2cb2d.png)


What other files do I need to create?

Create an excel file called "bot_config.xlsx" with API key stored inside. The main workflow calls Excel library to get the API key.

I am a C# developer, not familiar with VB language. Any similar post for this ?
See  
https://forum.uipath.com/t/how-to-integrate-chatgpt-in-uipath-using-the-http-request-activity/507534


Can I skip the excel file and just hardcode the api key ?

Yes, assigned the API key string value into the parameter strAPIKey directly.
