# cafe-devops
Café-devops repo... to log our coffee journey

> Anything worth doing is worth overdoing *- Mick Jagger*

## Log format
* One log entry per yaml element
* Ratings are out of 10

### Required attributes for all log entries
* `log:` *type*
* `by:` *loggers name*
* `date:` *just `$ date | pbcopy`*

### Optional attributes for all log entries
* `notes:` *for notes*

### Types of log entries

#### Bean
* When changing the bean in the grinder
* Required attributes:
  * `name:` *The name of the bean used*

#### Tweak
* A change to the brew process such as new filters or grind granularity
* Required attributes:
  * `change:` *describe what was changed* 

#### Taste
* Log a how the coffee tastes
* Required attributes:
  * `coffee:` *the bean used*
  * `roast:` *light / medium / bold / post-apocalyptic* 
  * `bitterness:` *out of 10*
  * `strength:` *out of 10*
  * `flavor:` *out of 10*

#### Tuneup
* For cleaning the machine, calibrating the scale, etc.
* Required attributes:
  * `tuned:` *describe what was tuned*
