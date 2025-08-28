# ha-dashboard-meshcore-messages
A simple ha automation that will make it possible to read the last 5 messages  off a meshcore companion in a dashboard

To use this automation you need to add 5 helpers in HA
name them:
meshcore_last_message_1
meshcore_last_message_2
meshcore_last_message_3
meshcore_last_message_4
meshcore_last_message_5

They all need to be off type input text and need at least a lenght off 255 

I included a simple markdown card for the view

Adjust the text accordingly to your language for both the markdown as the automation, you need to be carefull in the markdown card text is replaced so if you altered txt in the automation you need to do it in the markdown also
