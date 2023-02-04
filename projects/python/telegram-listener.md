
# telegram-listener

[PyGithub docs](https://pygithub.readthedocs.io/en/latest/index.html)
[PyGithub repo](https://github.com/PyGithub/PyGithub)

`telegram-listener` is a tool that listens to an account in a Telegram chat and makes corresponding http calls given the content of the message. This is inspired by [tuixue.online-visa](https://github.com/Trinkle23897/tuixue.online-visa), a tool that periodically checks and publishes US consulate visa appointment availabilities across the world.

A possible application of this tool is to use it to listen to a Telegram bot publishing messages about new visa appointments, and makes http calls to the consulate appointment service to grab the desired spot.
