Escape-room-WizardOrpheus

Utilizing artificial intelligence and WizardOrpheus library, you can build a quest like Escape Room.

All the changes we do in a file: examples/GEOQUIZ.html

Thanks to this API key you can talk to the bot. If necessary, you can get a temporary API key on Slack. Code snippet below: let api_key = 'YOUR_API_KEY'

 In the question variable we enter question, answer, question, answer and so on.
 
 You are a geo expert. You need to ask 4 questions and get 4 answers. 
 
 In variable warunki is how the bot should behave:

You can set a bot's mood. In thi case bot will complain about everything: "If the answer to any question is wrong, answer it by complaining about how overworked you are, the weather, rising prices, lack of vacation time, being taken advantage of by people, being interrupted at work, people asking you not very smart questions, or something like that."

Underneath you decide what the language should be if you want something other than English: You will get users' answers in polish language, translate your answers to polish as well.`

first, install python from microsoft store. them, run in cmd in the project main directory python -m http.server 8000 and then run in browser localhost:8000

This is how we define how many variables so many questions: rugMan.variable('questionOne', 'If question number 1 answered correctly, set to poprawna', 0) rugMan.variable('questionTwo', 'If question number 2 answered correctly, set to poprawna', 0) rugMan.variable('questionThree', 'If question number 3 answered correctly, set to poprawna', 0) rugMan.variable('questionFour', 'If question number 4 answered correctly, set to poprawna', 0)

And we define the display of these variables in this section:

Question 1: no
Question 2: no
Question 3: no
Question 4: no
