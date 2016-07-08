###Todo:

##Commands

List of current commands and their usage

No parameters required:

!hello

!hayzer

!cunt

!test

!eightball <question text here> - Get advice from the magic 8ball

!roulette - Spin the wheel and see if you get banned



Parameters required:

!wide <text to be widened>

!g <text to search on google>

!ud <text to be searched on UD>

!ub <start word> <goal word> - Use words from the definition of the first word lead to the goal word

!urban_reset - End the current urban battle and reset the start and goal words

##FeatureRequest

##BugReport

##Responses

##Wiki

Message limit responses

Case insensitivity or retry with caps on first

##Karma

##Wiktionary

##Twitter

##Calendar

##Calc

##Wolfram Alpha

##ety

##ud


# Dot
IRC Bot in Node with MongoDB

#Example config
Config lives in setup/config.json.
config.json is in the .gitignore file for this project.
{
  "name": "Dot",
	"server": "irc.foonetic.net",
	"port": "1234"
	"httpPort": "2345"
	"password": "pa55", //oauth key will go here in the case of twitch logins
	"channels": ["#dottest"],
	"admin": ["Lightbot"],
	"debug": true

  "twitter_consumer_key": "xxxxxxxxxxxxxxxxxxxxxxxxx",
  "twitter_consumer_secret": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "twitter_access_token_key": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx",
  "twitter_access_token_secret": "xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx"
 }
