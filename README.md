# VBA of Wall Street

## Overview of Project

### Purpose
	
This project is to help Steve with viewing data from a dataset that includes information from the stock market at a set year. Being that code originally was written for a finite amount of stocks, we wanted to make sure it runs for more than a finite amount. Not only that, we want to see if the code runs faster than the original. If the code does, that is great. If not, we will need to see the difference. We will take the original code and tweak it to provide the results we need. This edit as you will, is known as refactoring. The following paragraphs will determine if we succeeded in our refactoring to help Steve.

## Results

### Analysis of Original 2017 Code and Refactored 2017 Code

If we compare the original code with the refactored, a couple of odd things show up. Which may be an issue with the code that was written. The ticker results show the year 2018 instead of the 2017. However, the time result shows the runtime being faster on the original code instead of the refactored. We can take mulitiple things into account. One, we have to consider what computer a person uses. The computer used for this code may have taken longer to execute it. Two, it is going through a lot of data to show results.

![Original 2017 Counter](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/2017%20Original%20With%20Counter.png?raw=true)
![Refactored 2017 Counter](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/2017%20Unformatted%20With%20Counter.png?raw=true)

### Refactored 2017 Formatted Results

The following image will show the results formatted and more appealing to read;

![Formatted 2017](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/VBA_Challenge_2017.png?raw=true)

### Analysis of Original 2018 Code and Refactored 2018 Code

Unlike the comparsion from before, the code seemed to work fine for the year of 2018. The time results however seem to show the same as 2017. The refactored is a little slower, which seems to be the similarity between the two years and the difference in code. The ticker results show the same. If we decided to reformat it, it would also show the same results.

![Original 2018 Counter](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/2018%20Original%20With%20Counter.png?raw=true)
![Refactored 2018 Counter](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/2018%20Unformatted%20With%20Counter.png)

### Refactored 2018 Formatted Results

The following image will show the results formatted and more appealing to read;

![Formatted 2018](https://github.com/Greekman12490/Module_2_Challenge/blob/main/Resources/VBA_Challenge_2018.png?raw=true)


### Challenges and Difficulties Encountered

When the code was written, I would experience a multitude of errors because of how the was code written. All of which were resolved and the code was able to run. The errors that would occur would be overflow errors. Which when we look it up, it is because of a variable would be too small for the contained data. The odd thing about the code when the error occurred, the typical fix would be to change the variable or add additional code such as "CLng". This didn't solve the problem. A more simple solution was needed  to fix the problem. That would be..... spacing. Yes, spacing. Which made the code execute.

## Summary

In conclusion with all you have read, one advantage we can take from this is, you can get the same results with better code. However, the better code may take longer to execute because of more data needed to execute. But, in reality, does that make it better or worse? Since we can see the runtime being longer, we can view that as a disadvantage to our code. If you the run the original code, you can see seem slightly faster than the refactored. However, the original causes faults due to the possiblity of an error in code.  That error could be just a missing line. If you run the code multiples times however, time results will vary. 



		
		

