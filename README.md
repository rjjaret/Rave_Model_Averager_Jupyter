Rave Model Averager 

This was built using:
Mac OS Sequoia 15.5
Python 3.12

Git Repository: https://github.com/rjjaret/RaveModelAverager

Adjust parameters in cell 3. 

Some observations:
- If all the parameters can be averaged, the result is a high pitch squeal. When about 1/3 of the params can be averaged, you get a better result. 
- I'm not sure I'd call the result an average of the sounds. In a best case, you may hear some elements of both models in the result, but it's not clear.
  
Some observations:
- If all the parameters can be averaged, the result is a high pitch squeal. When about 1/3 of the params can be averaged, you get a better result. 
- I'm not sure I'd call the result an average of the sounds. In a best case, you may hear some elements of both models in the result, but it's not clear.

- Outstanding questions for interested parties:
- Since it doesn't work well when all params are compatible, are there some params that shouldn't be averaged to keep the resulting model functional?
- Would it make logical sense to reshape the parameters that exist in both models but do not have the same shape so they can be averaged? 
- Anything else that could make this more like an average of two models?
