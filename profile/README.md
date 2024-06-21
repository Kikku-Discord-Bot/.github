# Kikku

Kikku is a versatile and free Discord bot designed to make your server management and moderation tasks easier. Kikku is highly customizable, and you can load modules to enhance its functionality, making it a perfect choice for server administrators and moderators.

## Features

-   Customizable modules to extend functionality
-   Free and open-source
-   Easy-to-use commands
-   Seamless integration with your Discord server

## Documentation

-   [Code Documentation](https://kikku-discord-bot.github.io/)
-   [Discord API Documentation](https://discord.com/developers/docs/intro)

# Before You Begin...

![Alt Text](https://tenor.com/view/mio-%E3%83%9F%E3%82%AA-%E3%82%BC%E3%83%8E%E3%83%96%E3%83%AC%E3%82%A4%E3%83%893-xenoblade3-%E3%82%BC%E3%83%8E%E3%83%96%E3%83%AC%E3%82%A4%E3%83%89-gif-25964961.gif)

## ⚠️ Beware of your commits ⚠️

Improper commits or branch names are either deleted or rebased.

# Branch

Kikku follows a clear branch naming convention:

-   `master`: The main branch, containing the latest stable version of the bot.
-   `dev`: The development branch, with the latest code updates.
-   `feat/`: Branches for new features.
-   `fix/`: Branches for bug fixes.
-   `docs/`: Branches for documentation updates.

Additional branches may be created as needed.

# Commit

Use the following commit format:

```
pr/issue_linked(type)[scope]: description
```

## Commit Types

-   `feat:` : New feature
-   `fix:` : Bug fix
-   `refactor:` : Code refactoring
-   `style:` : Code style
-   `docs:` : Documentation
-   `test:` : Test
-   `other:` : Other changes

## Scope Examples

-   `admin-module` : Changes related to the admin module
-   `moderation-module` : Updates to the moderation module
-   `custom-commands` : Modifications to custom commands

If a commit is not related to a specific part of the code, no scope is needed.

# Installation

To get started with Kikku, follow the steps below:

### Discord Bot

1. Create a new Discord bot on the [Discord Developer Portal](https://discord.com/developers/applications).
2. Copy your bot token.
3. Invite your bot to your Discord server using the following link: `https://discord.com/oauth2/authorize?client_id=YOUR_BOT_CLIENT_ID&scope=bot&permissions=YOUR_PERMISSIONS`.

### Configuration

1. Clone this repository to your local machine.
2. Create a `.env` file in the project root and add your bot token:

   ```
   BOT_TOKEN=YOUR_BOT_TOKEN
   ```

3. Install the required dependencies using npm:

   ```bash
   npm install
   ```

4. Start the bot:

   ```bash
   npm start
   ```

## Authors

-  **Serena Satella** - [TrueBabyChaise](https://github.com/TrueBabyChaise)

Feel free to contribute to the project, report issues, or suggest new features. Happy coding with Kikku!
