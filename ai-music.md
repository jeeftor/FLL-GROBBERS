# When should/can we use AI

As we now live in the world of AI its important to know what its good for and what it's bad for. This tutorial will help you make a complicated song in Spike Prime witht he help of AI (maybe)

Pick A song you like - maybe the "Darth Vader Theme" or "Indian Jones Theme" - and lets see if the AI can help us out. We will explore differnet ways to "prompt" and you will be abel to compare the results - understanding how you can give more information to hopefully get better results.

**Make sure to record what and why you chose to use AI in your Engineering Notebook!**

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


## Prompt 1

So to start lets be a little lazy and just "try" to see if AI can build us something

What are the key things you need to tell the AI:

- What do you want it to make (a program / a funciton / a function call / write some software)
- What language (`Lego Spike Prime Micropython`)

**Please store your prompt in your engineering notebook**

## Prompt 2

Lets refind the results from the 1st prompt. What additional information can we provdie to enhance the results:

- Could we give more details on the `beep` function?
- Perhaps the AI could use the Application Programing Interface: https://spike.legoeducation.com/essential/help/lls-help-python#lls-help-python-spm-hub-sound-func-beep and we could tell it to refer to that for details
- Think about how you can enhance your prompt

**Please store your prompt in your engineering notebook**


## Prompt 3

A long long time ago - before you were born there was something called "Flip Phones". In these olden days - we didn't have fancy music - we had very simple ringtones. They were just tones - and you know what else can make tons LEGO ROBOT. Maye we coudl ask the AI to convert one of these ringtones into Spike Prime format and it might sound good?

You could find a webpage on this website for a song you like at:

- https://ringtonesgalore.co.uk

Then give the AI this and ask it to convert it. Often this is the best way to get sounds to work because somebody alerady figured out how to make the music.
