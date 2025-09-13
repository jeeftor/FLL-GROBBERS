# AI Assistance

As we now live in the world of AI its important to know what its good for and what it's bad for. This tutorial will help you make a complicated song in Spike Prime witht he help of AI (maybe)


##

Pick A song you like - maybe the "Darth Vader Theme" or "Indian Jones Theme"

And lets see if the AI can help us out. Make sure to record what and why you chose to use AI in your Engineering Notebook!

## Prompts

When interacting with AI we need to use prompts to ask the AI Questions.

Start wtiht this simple python program: 


```python
from hub import sound
import runloop


async def prompt1():
    print("Playing Song #1")
    # ... Fill out the rest of this function

async def promtp2():
    print("Playing Song #2")
    # ... Fill out the rest of this function

async def prompt3():
    print("Playing Song #3")
    # ... Fill out the rest of this function


async def main():

    # Play the 1st song
    await prompt1()

    #Pause 1 second
    await runloop.sleep_ms(1000)

    await promtp2()

    #Pause 1 second
    await runloop.sleep_ms(1000)

    await prompt3()

runloop.run(main())
```

If you run it it will print something like:

```
6:25:36 PM: Compiled-------------
Playing Song #1
Playing Song #2
Playing Song #3
```

Very boring :)


- "Can you make me a Lego Spike Prime python function that can play XXXXX"

- Can you make me a Lego Spike Prime python function that can play XXXXX. Additionally this link has the information on the SOUND function: 
https://spike.legoeducation.com/essential/help/lls-help-python#lls-help-python-spm-hub-sound-func-beep
"



- https://ringtonesgalore.co.uk


## Reference Materias

An API is an Application Programing Interfaice - and this is the link to the "Sound Beep" function that we would have to use.

https://spike.legoeducation.com/essential/help/lls-help-python#lls-help-python-spm-hub-sound-func-beep


This is a RingTone for Indiana Jones:
https://ringtonesgalore.co.uk/tones/movies/indiana-jones/indiana-jones/

