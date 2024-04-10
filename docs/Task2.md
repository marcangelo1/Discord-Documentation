# **Setting Up a Server Bot: Creation and Integration**

## Overview
Discord bots are cool helpers that make your chat server more fun and keep things in order. They can tell jokes, run games, or make sure people follow the rules.This section helps you understand Discord bot accounts and guides you through the creation and integration process.

??? Question "What is a Discord bot account and what can you do with it?"

    Think of a Discord bot as a helpful automated program on your server. You'll need a dedicated Discord bot account separate from your user account to control and manage these custom bots.

    - **Manage Your Bot:** Configure its settings, commands, and presence on your server.
    - **Run Pre-Built Bots:** Add and customize many existing bots from online repositories, covering moderation, fun games, and more.
    - **Connect to Self-Coded Bots:** Link the bot account to advanced custom bots you've developed yourself (this does require programming knowledge).


!!! Note
    This guide doesn't cover building or coding the bot's functionality. That's a separate, more technical process often involving programming knowledge.



## Creating Bot Account

**1.** Navigate to the [**Discord Developer Portal website**](https://discord.com/developers/applications){: style="color: #7289DA;"}   

**2.** Enter your login credentials and then click the **"Log In"** button.

<figure markdown="span">
  ![](Assets/Task2 Assets/Login.png){ width="800" }
</figure>

???+ Note "Are you human?"
    If the **Are you human?** prompt appears, click **"Confirm"**. You may also need to check your email to verify your login.

**3.** Click the **"New Application"** button in your screen's top-right corner.

<figure markdown="span">
  ![](Assets/Task2 Assets/NewApplication.png){ width="900" }
</figure>

**4.** Give your bot a creative and descriptive name, then click the **"Create"** button.

<figure markdown="span">
  ![](Assets/Task2 Assets/Create Name.png){ width="400" }
</figure>

??? Tip "Use a descriptive name"
    Choose a name that helps users understand what your bot does or represents. This will make it stand out and easy to find on Discord.
???+ Note
    Agree to the Developer Terms and Policy by clicking the checkbox if prompted to.

**5.** Select the **Bot** tab in the left navigation menu.

<figure markdown="span">
  ![](Assets/Task2 Assets/Bot Tab.png){ width="400" }
</figure>

**6.** Scroll down and you will see the settings to customize your bot's functionality. Customize your bot the way you want. 
<figure markdown="span">
  ![](Assets/Task2 Assets/Customize1.png){ width=900" }
</figure>
<figure markdown="span">
  ![](Assets/Task2 Assets/Customize2.png){ width=900" }
</figure>

<!-- ??? Info "Public bot"

    To allow others to invite your bot, ensure the **Public Bot** option is checked. -->

**7.** When finished customizing, click the **"Save Changes"** Button

<figure markdown="span">
  ![](Assets/Task2 Assets/SaveChanges.png){ width=900" }
</figure>

**8.** Scroll back up until you see the **"Reset Token"** button. Click the **"Reset Token"** button.
<figure markdown="span">
  ![](Assets/Task2 Assets/ResetButton.png){ width=900" }
</figure>

**9.** A warning from discord will pop up. Read it and then click the **"Yes, do it!"** button.
<figure markdown="span">
  ![](Assets/Task2 Assets/yesdoit.png){ width=400" }
</figure>

**10.** A Multi-Factor Authorization window will pop up asking for your password. Enter the password of the account you used to login and then click the **"Submit""** button.
<figure markdown="span">
  ![](Assets/Task2 Assets/Authorization.png){ width=400" }
</figure>

**11.** The **"Copy"** button should now appear. Click the **"Copy"** button to copy your token.
<figure markdown="span">
  ![](Assets/Task2 Assets/CopyButton.png){ width=900" }
</figure>
!!! Warning "Protect your bot token!"
    - **Never share your token!** It's like your bot's password.
    - **Token Leaked?** Click **"Reset Token"**  immediately to create a new, secure token.
    - **Update Your Code:** Ensure your bot uses the new token to function correctly.

Congratulations! 🎉 You've created a bot account. Now you can connect your scripts to your discord bot server.



## How to Add Your Bot to Your Discord Server

<!-- Adding a bot lets its code run on your Discord server. First, you'll invite the bot to your server. Then, you'll grant it specific permissions – these control what the bot can do, such as reading messages, sending messages, or managing roles. Once added, the bot will become active and be able to interact with your server members. -->

**1.** Ensure you're logged in to [**Discord Developer Portal website**](https://discord.com/developers/applications){: style="color: #7289DA;"}  with the account you used to create your bot.  

**2.** Navigate to the applications page. Then, under **My Applications**, select your desired application.  

<figure markdown="span">
  ![](Assets/Task2 Assets/NewApplicationsPage.png){ width="900" }
</figure>

**3.** Click the **OAuth2** tab in the left side navigation panel.  

<figure markdown="span">
  ![](Assets/Task2 Assets/Oath2.png){ width="400" }
</figure>

**4.** Find the **Scopes** section and check the box next to **bot**.  

<figure markdown="span">
  ![](Assets/Task2 Assets/Scope.png){ width="900" }
</figure>

**5.** Within the **Bot Permissions** section, select the permissions you want your bot to have. Once done, click the **"Copy"** button to copy a URL.

<figure markdown="span">
  ![](Assets/Task2 Assets/UrlCopy.png){ width="900" }
</figure>

<!-- **Note:** Your changes will be saved automatically. -->

**6.** Copy the URL, paste it into your browser, and go to the page. Select the server you want to integrate your bot under **ADD TO SERVER** section. Click the **"Continue"** button once done.
<figure markdown="span">
  ![](Assets/Task2 Assets/addToServer.png){ width="400" }
</figure>

**7.** Click the **"Authorize"** button to finalize the integration of your bot to your chosen server.
<figure markdown="span">
  ![](Assets/Task2 Assets/authorizedBot.png){ width="400" }
</figure>

Congratulations! 🎉 Your bot is now on the server. 🤖 Get ready to see it in action!

## Conclusion

By the end of this section, you will have successfully learned the following:

✅ You now grasp what Discord bot accounts are and how they offer exciting ways to interact with your community.  
✅ You've successfully navigated the Developer Portal and created your bot account.  
✅ You've learned how to invite your bot to a server and grant it the necessary permissions for its functions.

**Great job 🤗! Your bot is up and running on Discord!**

