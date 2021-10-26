## Viait Linux User Profile

Viait Linux used a slighty modified gnome profile.

On First startup a file at ~/.viait/settings/desktop.default is deleted after /usr/bin/viait-setup is ran on startup. <br>
This file is just a placeholder to set the default Desktop Theme and Extensions and /usr/bin/viait-setup will run on every startup but will only reapply the settings if the ~/.viait/settings/desktop.default file exsists. <br>
Otherwise any custom themes or extentions you enable will persists unless you re-create that file and log back in and out. 
