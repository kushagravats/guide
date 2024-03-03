<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style scoped>
    .emoji-container {
      display: inline-block;
    }

    .emoji-container .emoji-image {
      width: 1.375rem;
      height: 1.375rem;
      vertical-align: bottom;
    }
  </style>
  <title>Discord.js Guide Update</title>
</head>

<body>

  <h1>What's New</h1>

  <!-- Discord.js Message Component -->
  <DiscordMessages>
    <DiscordMessage profile="bot">
      <template #interactions>
        <DiscordInteraction profile="user" author="discord.js" :command="true">upgrade</DiscordInteraction>
      </template>
      discord.js v14 has been released, and the guide has been updated!
      <span class="emoji-container">
        <img class="emoji-image" title="tada" alt=":tada:"
          src="https://cdn.jsdelivr.net/gh/twitter/twemoji@v14.0.2/assets/72x72/1f389.png" />
      </span>
      <br />
      This includes additions and changes made in Discord, such as slash commands and message components.
    </DiscordMessage>
  </DiscordMessages>

  <!-- Site Updates -->
  <h2>Site Updates</h2>
  <ul>
    <li>Upgraded to <a href="https://v2.vuepress.vuejs.org/" target="_blank">VuePress v2</a></li>
    <li>New theme made to match the <a href="https://discord.js.org/" target="_blank">discord.js documentation site</a></li>
    <li>Discord message components upgraded to <a href="https://github.com/Danktuary/discord-message-components/blob/main/packages/vue/README.md"
        target="_blank">@discord-message-components/vue</a></li>
    <li>Many fixes in code blocks, grammar, consistency, etc.</li>
  </ul>

  <!-- Pages Updates -->
  <h2>Pages Updates</h2>
  <p>All content has been updated to use discord.js v14 syntax. The v13 version of the guide can be found at <a
      href="https://v13.discordjs.guide/" target="_blank">https://v13.discordjs.guide/</a>.</p>

  <!-- New Content -->
  <h3>New</h3>
  <ul>
    <li><a href="/additional-info/changes-in-v14.md">Updating from v13 to v14</a>: A list of the changes from discord.js
      v13 to v14</li>
    <!-- Add other new content items here -->
  </ul>

  <!-- Updated Content -->
  <h3>Updated</h3>
  <ul>
    <li>Commando: Replaced with <a href="https://sapphirejs.dev/docs/Guide/getting-started/getting-started-with-sapphire"
        target="_blank">Sapphire</a></li>
    <!-- Add other updated content items here -->
  </ul>

  <!-- Discord Messages Component -->
  <DiscordMessages>
    <DiscordMessage profile="bot">
      Thank you to all of those that contributed to the development of discord.js and the guide!
      <span class="emoji-container">
        <img class="emoji-image" title="heart" alt=":heart:"
          src="https://cdn.jsdelivr.net/gh/twitter/twemoji@v14.0.2/assets/72x72/2764.png" />
      </span>
    </DiscordMessage>
  </DiscordMessages>

</body>

</html>
