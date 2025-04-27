This repo and github page is intended to be used by Moot Court Bailiffs. The design and specifications were made to a user specification.

Features:
1. Able to specify the time alotted for rebuttal
2. Can choose any combination 1 minute, 3 minute, and 5 minute warnings which will be applied to all sections of the argument (Appelle, Appellant, Appelle's rebuttal)
3. Can choose to display the timer for the full duration in white text
  - The default is to hide the timer and only show when starting/when to warn the participants about time remaining
4. At the end of a round a STOP screen will be displayed with a button to press for starting the next round
5. Uses the screen wakelock API to keep screen awake until the end of rebuttal 
6. The return to home button will take you back to the settings and cancel the current timer run
