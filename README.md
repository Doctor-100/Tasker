# Automatic verification code forwarding
# Tasker+Termux+Tencentcloud or twilio
A repository for storing scripts for tasker and termux
运转本项目功能，你需要安装tasker以及termux在你的手机上，请放心，他们是安全且公开的。
从整体上看，本项目提供的是一种将tasker，termux以及腾讯云结合起来使用的思路。
本项目用于将手机接收到的验证码等短信内容进行跳转传输，将这些内容打包后发送到另一个手机号码，此功能面向于那些想和朋友分享自己的账号，却烦恼于需要无时无刻留意手机短信来将接收到的验证码发送给朋友，相信我，你不会喜欢这一幕的，那意味着你需要时刻待在手机面前来将收到的验证码发送给你的朋友，相信很多玩炉石传说或者是其他游戏的朋友都遇到过这一问题，你想将你的账号与朋友分享，或者是你雇佣了专业选手来替你达成游戏中的某些成就，比如说让他帮你打到某个游戏段位，这通常代表着你需要多次手动提供验证码给他们，这真的很麻烦。
为了解决这个麻烦的问题，通过tasker，termux以及腾讯云，我成功实现了短信的全自动转发。
这不仅仅只是单独实现一个验证码的转发功能，事实上，他应该有着更广泛的应用空间？比如说，远程遥控，当你使用你的手机给远在家里的手机发送一个特定信息后，tasker能够检测到该信息并进行下一步操作，比如说发送请求到flask服务器并执行termux的脚本。

To run this project, you need to install tasker and termux on your phone, rest assured that they are safe and open.
On the whole, this project provides a way to use tasker, termux and Tencent Cloud together.
This project is used to transfer the verification code and other SMS content received by the mobile phone, and then send these contents to another mobile phone number after packaging. This function is aimed at those who want to share their account with their friends, but worry about paying attention to the SMS all the time to send the received verification code to their friends. Believe me, you will not like this scene. That means you need to be in front of your phone at all times to send the received verification code to your friends, I believe that many friends who play Hearthstone or other games have encountered this problem, you want to share your account with friends, or you hire a professional player to help you achieve certain achievements in the game, such as asking him to help you beat a certain game stage, This usually means that you need to manually provide the capTCHA to them several times, which is really troublesome.
To solve this troublesome problem, through tasker, termux and Tencent Cloud, I successfully realized the automatic forwarding of SMS.
This is not only to achieve a single verification code forwarding function, in fact, he should have a wider application space. For example, remote control, when you use your phone to send a specific message to a phone at home, tasker can detect the message and take the next step, such as sending a request to the flask server and executing a termux script.


