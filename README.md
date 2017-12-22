# The TouchRemix sound theme

![Ubuntu Touch](/banner.jpg)

The TouchRemix sound theme is a proposal for new default system sounds for Ubuntu 18.04. Based on [Jouni Helminen](http://www.helminen.co)'s awesome work for Ubuntu Touch, these sounds use a similar instrumentation. The _desktop-login_ sound is a replication of the ringtone "Ubuntu".

The intention was to create a cohesive set of sounds that will enhance the user experience without getting in the way. 

Enjoy! 
_MadsRH_

---

## How to test it

In order to test this sound theme, click on "clone or download" then "Download Zip". You'll get a zip file with a folder named "TouchRemix-master" inside it. Just put this folder inside `.local/share/sounds/` and rename it `TouchRemix`. After that, to change your current desktop sound theme, you will need `dconf-editor` to change the setting key `/org/gnome/desktop/sound/theme-name/` to `TouchRemix`

### Testing input feedback sounds

In `dconf-editor`, change the key `/org/gnome/desktop/sound/input-feedback-sound` to `true` and enjoy more sounds to test.

---

This project is licensed under CC-BY-SA 3.0.
