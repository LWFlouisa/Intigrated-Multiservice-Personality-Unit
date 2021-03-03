# Chatbots
A collection of AIML chatbots.

## AI Rulesets called

### Drawing
~~~ruby
WeaverBot::AIDrawing.line
WeaverBot::AIDrawing.square
WeaverBot::AIDrawing.cube
WeaverBot::AIDrawing.hyper
WeaverBot::AIDrawing.image
~~~

### Arithmetic
~~~ruby
WeaverBot::AIRulesets.give_hours
WeaverBot::AIRulesets.tesla_multiplication
WeaverBot::AIRulesets.autonomous_prompting
WeaverBot::AIRulesets.calculate_hyper
WeaverBot::AIRulesets.estimate_digest
~~~

### Creativity
~~~ruby
WeaverBot::AIRulesets.write_renpy_script
WeaverBot::AIRulesets.write_poetry
~~~

## Chatbot Functions
Chatbot functions are built into the AIML script itself, so I'm not hard coding chat structure. This bot will also allow for natural language commands, that are less awkward that simply saying "give_hours".

## Future Divisions
[Ruleset Learning](https://github.com/LWFlouisa/Routine-Creator)

I need a way for it to learn new rulesets automatically without having to use machine learning. Though I may end up having to use Naive Bayes to generate a statistical model for decision making.
