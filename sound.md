# Sound

This demonstrates how to use Sound with your robot.


```python
from hub import sound
import runloop


async def play_sound():
    await sound.beep(659, 480, 85)
    # Can you add more notes - play with the paramaters



# This is basically required :)
async def main():

    # Could you make this play a few times in a row?
    await play_sound()

    # Can you add a 1 second pause as well?

runloop.run(main())
```