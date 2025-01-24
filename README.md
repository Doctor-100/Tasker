# Automatic verification code forwarding
# Tasker+Termux+Tencentcloud or twilio
A repository for storing scripts for tasker and termux

To run this project, you need to install tasker and termux on your phone, rest assured that they are safe and open.
On the whole, this project provides a way to use tasker, termux and Tencent Cloud together.
This project is used to transfer the verification code and other SMS content received by the mobile phone, and then send these contents to another mobile phone number after packaging. This function is aimed at those who want to share their account with their friends, but worry about paying attention to the SMS all the time to send the received verification code to their friends. Believe me, you will not like this scene. That means you need to be in front of your phone at all times to send the received verification code to your friends, I believe that many friends who play Hearthstone or other games have encountered this problem, you want to share your account with friends, or you hire a professional player to help you achieve certain achievements in the game, such as asking him to help you beat a certain game stage, This usually means that you need to manually provide the capTCHA to them several times, which is really troublesome.
To solve this troublesome problem, through tasker, termux and Tencent Cloud, I successfully realized the automatic forwarding of SMS.
This is not only to achieve a single verification code forwarding function, in fact, he should have a wider application space. For example, remote control, when you use your phone to send a specific message to a phone at home, tasker can detect the message and take the next step, such as sending a request to the flask server and executing a termux script.


