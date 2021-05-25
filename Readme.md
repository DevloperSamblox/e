Put the contents of "Panel Files" in /var/www/pterodactyl

After you do that, build the panel.  

You can find more information here.

https://themes.pterodox.com/guides/building.html

Instead of doing "Yarn build:production" do this, "rm -r .babel-plugin-macrosrc.js && yarn add @emotion/react && yarn build:production"

If you want to remove the theme just follow the upgrading guide on pterodactyl's website.

If there are issues or you need help please join my discord, https://discord.gg/HYweeZw3zR