# Privacy Policy for AsTrazu

**Last Updated: May 06, 2025**

Thank you for using AsTrazu! This Privacy Policy explains how we collect, use, and protect your data when you interact with our Discord bot, AsTrazu. We are committed to safeguarding your privacy and ensuring transparency in our data practices in compliance with Discord’s Developer Policy.

## What Data Do We Collect?

AsTrazu collects the following data to provide its features and functionality:

- **Message Content**: We process the content of messages in Discord servers to execute prefix commands for moderation (e.g., `timeout`, `kick`, `clear`), gambling (e.g., `blackjack`, `slots`, `khlakhlouk`), and economy (e.g., `cash`, `daily`, `transfer`). For example, in the **Khla Khlouk Dice Game**, the bot reads messages to process user bets (e.g., "ភ្នាល់ ខ្លា 100" meaning "bet tiger 100") on one of six symbols (tiger, crab, fish, cock, gourd, stag), inspired by the traditional Cambodian game played during Khmer New Year. This feature celebrates Cambodian culture and encourages community engagement.
- **User and Server Information**:
  - **Server Members Data**: We access user IDs, usernames, nicknames, and avatars to support features like economy (e.g., `cash`, `transfer`), gambling leaderboards (e.g., for `khlakhlouk`), and moderation actions (e.g., `timeout`, `kick`). This data is also used to verify roles and manage permissions for certain commands.
  - **Server Data**: We collect server IDs to ensure the bot functions correctly within Discord servers and to associate user data with specific servers (e.g., for economy or gambling systems).
- **Command Usage Data**: We temporarily log anonymized command usage (e.g., frequency of command usage) to monitor bot performance and troubleshoot issues. This does not include message content or personally identifiable information.

## How Do We Use Your Data?

The data we collect is used exclusively to provide and improve AsTrazu’s functionality, including:

- **Processing Commands**:
  - **Prefix Commands**: Reading message content to execute commands like `timeout`, `kick`, `clear` for moderation; `blackjack`, `slots`, `khlakhlouk` for gambling; and `cash`, `daily`, `transfer` for economy.
  - **Slash Commands**: Handling administrative commands like `/deleteaccount` for data management and `/togglekhlakhlouk(in feature)` for message content opt-out.
- **Feature Delivery**:
  - Moderation: Managing server safety with commands like `timeout` (e.g., `timeout @user 10` to timeout a user for 10 minutes), `kick`, and `clear`.
  - Gambling: Enabling games like `blackjack`, `slots`, and `khlakhlouk`. The Khla Khlouk Dice Game uses message content to process user bets, roll virtual dice, determine outcomes, and update a leaderboard with Khmer-themed embeds to promote cultural engagement and interaction.
  - Economy: Managing virtual currency with commands like `cash`, `daily`, and `transfer` (e.g., `transfer @user 500` to send 500 coins).
- **Bot Operation**: Using server and user IDs to ensure commands work correctly across servers, especially in over 100 servers within Cambodian Discord communities.
- **Improvement**: Analyzing anonymized command usage to debug and enhance bot performance.

## Do We Store Your Data?

- **Message Content**: We do not store message content. Messages are processed in real-time to execute commands or process bets in the Khla Khlouk Dice Game and are discarded immediately after use.
- **User and Server Data**:
  - We temporarily store user IDs, usernames, nicknames, avatars, and server IDs to support features like economy, gambling leaderboards, and moderation actions.
  - This data is stored off-platform (outside of Discord) for up to 30 days to ensure functionality (e.g., tracking user balances or timeout records).
  - All stored data is encrypted at rest using AES-256 encryption, in compliance with Discord’s Developer Policy.
- **Command Usage Data**: Anonymized usage logs are stored for up to 30 days for debugging purposes and then deleted.
- **Opt-Out Settings**: If you opt out of the Khla Khlouk Dice Game using `/togglekhlakhlouk`, this preference is stored in our database (associated with your user ID) until you request deletion of your data.

## How Can You Request Data Deletion?

You can request the deletion of your data at any time by:

- Running the `/deleteaccount` command in the bot, which will immediately remove all stored data associated with your user ID (e.g., economy balances, gambling records, moderation history, opt-out settings).
- Contacting us via our Discord support server: [https://discord.gg/4vBzJaaVGv](https://discord.gg/4vBzJaaVGv).
- Emailing us at: [senghongly8828@gmail.com](mailto:senghongly8828@gmail.com).

Once deleted, your data cannot be recovered.

## Do We Share Your Data?

We do not share your data with any third parties. All data processing occurs within our systems, and we do not transfer data outside of Discord’s ecosystem except for temporary storage as described above.

## Do We Use Data for AI or Machine Learning?

No, we do not use your data, including message content or user information, to train AI or machine learning models. Your data is only used to provide and improve AsTrazu’s functionality.

## How Can You Opt Out?

- **Message Content**: You can opt out of message content tracking for the Khla Khlouk Dice Game by running the `/togglekhlakhlouk` command, which disables the game feature for your account and prevents the bot from reading your messages for this purpose. Server admins can also disable the game for the entire server using the `/khlakhlouk disable` command. For other prefix commands (e.g., `blackjack`, `transfer`), server admins can restrict the bot’s access to specific channels using Discord’s permission settings, preventing the bot from reading messages in those channels.
- **Server Members Data**: You cannot opt out of server members data processing if you interact with features like economy, gambling, or moderation, as this data is necessary for those features to work. You can request deletion of your data using the `/deleteaccount` command to stop further processing.

## Your Rights

You have the right to:

- Understand how your data is used (as outlined in this policy).
- Request deletion of your data using the `/deleteaccount` command or by contacting us.
- Restrict the bot’s access to your data by adjusting server or channel permissions (via Discord’s settings2010-01-01T00:00:00+00:00settings).
- Opt out of message content tracking for the Khla Khlouk Dice Game using the `/togglekhlakhlouk` command.
- Contact us for more information about your data (see contact details below).

## Security of Your Data

We take security seriously:

- All sensitive user data (e.g., usernames, avatars, economy balances, opt-out settings) stored off-platform is encrypted at rest using AES-256 encryption, ensuring compliance with Discord’s Developer Policy.
- We implement strict access controls to protect your data from unauthorized access.

## Changes to This Privacy Policy

We may update this Privacy Policy as needed. Changes will be reflected on this page, and we will notify users via our Discord support server or through the bot’s `help` command. The latest version is always available at: [https://amjustachillguy.github.io/privacy-policy.github.io/](https://amjustachillguy.github.io/privacy-policy.github.io/).

## Contact Us

If you have questions about this Privacy Policy or how we handle your data, please:

- Join our support server: [https://discord.gg/4vBzJaaVGv](https://discord.gg/4vBzJaaVGv).
- Email us at: [senghongly8828@gmail.com](mailto:senghongly8828@gmail.com).

---

AsTrazu is committed to delivering a fun, engaging experience on Discord while prioritizing your privacy and data security.
