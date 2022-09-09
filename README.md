# textual-emotion-recognition
Textual Emotion Recognition service for SingularityNET
## Welcome
## What’s the point?
The service outputs an emotion label that match to the specified text
## Model details:
The service receives the text in English and then classifies it

available emotion labels:
- "admiration"
- "amusement"
- "anger"
- "annoyance"
- "approval"
- "caring"
- "confusion"
- "curiosity"
- "desire"
- "disappointment"
- "disapproval"
- "disgust"
- "embarrassment"
- "excitement"
- "fear"
- "gratitude"
- "grief"
- "joy"
- "love"
- "nervousness"
- "optimism"
- "pride"
- "realization"
- "relief"
- "remorse"
- "sadness"
- "surprise"
- "neutral"

### The user must provide the following inputs in order to start the service and get a response:
#### Inputs:
`text`: json string

Example of input file content:

`{"text": "the source text"})`

#### Outputs:
`result`: json string

Example of output file content:

`{'emotion': <available emotion>, 'emotion_score': 0.6678475141525269, 'sentiment': <available sentiment>, 'sentiment_score': 0.9970384836196899}`

## What to expect from this service?
Inputs:

`{"text": "I hate cats!"})`

Outputs:

`{'emotion': 'anger', 'emotion_score': 0.6678475141525269, 'sentiment': 'NEGATIVE', 'sentiment_score': 0.9970384836196899}`
