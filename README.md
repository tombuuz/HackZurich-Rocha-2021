# HackZurich-Rocha-2021

Description:
Botchat service

Please, copy the following code and save as a Python file (.py).
You can replace "message" with your own words.

'''
import requests
url = 'https://rocha-demo.herokuapp.com/webhooks/rest/webhook' 
myobj = {
"message": "Good morning", # Message
"sender": 1,
}
x = requests.post(url, json = myobj)
print(x.text)
'''
