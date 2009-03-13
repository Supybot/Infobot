This plugin is intended to emulate the factoid behavior of the
well-known Infobot IRC bot[0].  If you are familiar with Infobot but
have defected to Supybot or you want a factoid plugin that doesn't
require users to register with the bot, this can be useful for you.

Teaching the bot new factoids is pretty straight-forward:

<jamessan> @42 is the answer to life, the universe, and everything
<bot> 10-4
<jamessan> @42
<bot> Somebody said that 42 is the answer to life, the universe, and
      everything.

There are a few special strings the bot recognizes in factoids:

<reply> - This tells the bot to simply respond with the exact text.

<action> - This tells the bot to perform the following text as an
action instead of saying it.

[0] - http://www.infobot.org/
