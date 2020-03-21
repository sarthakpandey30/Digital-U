# Digital-U
(HACKATHON PROJECT
# Authors

* **Sarthak Pandey** - *Initial work* - [sarthakpandey30](https://github.com/sarthakpandey30)
* **Kanishka Jain** - *Initial work* - [jkan2i](https://github.com/jkan2i)
## Built With
* Python
* Open CV
* numpy
* flutter 
* puppeteer

A Whatsapp BOT which can be trained using prev chats and used so that you can be at 2 places at the same time.
Just turn it on whenever you are busy and he will take care of the rest.

We first exported msgs from all of our whatsapp to make a generalized bot, also since most of our whatsapp chats as students have 
emojis and words like lol , we made python scripts to further filter the msgs and trained on around 8000msgs which is very less but 
sufficient for a Minimal Viable Product. Also Whatsapp chats have time stamps and names which we didn't need, so we made scripts to
divide the sender and receiver and removed timestamps from it. 

We created our backend on Nodejs and we faced difficulties while exporting the model but it was successful and we finally used OCR-api
to link the bot to whatsapp web servers using QR Codes.

(For the Python Scripts and bot and steps on how to export the bot model on your own chats) ---> www.kanishkajain.space
