# Lotterybarn-Octoventure
prompts for lotterybarn / snap

Note about parentheses in stop sequences: *There shouldn't be parentheses! I had to put parentheses because the markdown was not happy. Remove them when you're using the prompts.*

## Gacha System Prompts
### Gacha
* File: gacha.txt
* Model: Generative
* Stop Sequences: 'Player:', '(<)ask(>)', '(<)/inventory(>)'

### UP! Character + Pulled Character
* File: upchar.txt & newchar.txt, respectively
* Model: Generative
* Stop Sequences: '}'
(Sometimes I use Temp. 1.1 for UpCHar)

## Story Prompts
### Openings
* File: opening.txt
* Model: Generative
* Stop Sequences: 'Player:', '(<)story(>)', '(<)tutorial(>)'
* Options:
  * Temperature: 1.3
