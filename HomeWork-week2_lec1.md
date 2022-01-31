- Gross pay depends on the pay rate and the number of hours worked per week.
However, if you work more than 40 hours, you get paid time-and-a-half for all hours worked over 40.
(Pay remains same if work 40 or less than 40 hours) 
Write the algorithm to compute gross pay given pay rate and hours worked

---

Sol<br>
	
	{
	Step 1: Set the value of "hours per week" and "time half hpw" and
		"double time hpw" and "gross pay" and "hourly pay rate" to 0
	
	Step 2: Set the value of continue to true

	Step 3: While continue = true or continue  = y:

	Step 4: Ask user for input on "hours per week" and set it.

	Step 5: Ask user for input on "hourly pay rate" and set it.

	Step 6: If hours_per_week is > 40:

	Step 7: Set "time half hpw" to ("hours per week" – 40)

	Step 8: Set "hours per week" to 40

	Step 9: If "time half hpw > 14:

	Step 10: Set double_time_hpw to time_half_hpw – 14

	Step 11: Set "time half hpw" to 14

	Step 12: Set "gross pay" to ("hourly pay rate" * "hours per week") + 
	("hourly pay rate" * "time half hpw" * 1.5) + ("hourly pay rate" * "double time hpw" * 2)

	Step 13: Display 'Your gross pay this week is: ' + "gross pay" 

	Step 14: Prompt the user 'Type yes if you would like to compute again: '

	Step 15: set input to continue
	
	End 
	}

---
<!--11.Develop an algorithm to compute gross pay. The inputs to your algorithm are hours worked per week and the hourly pay rate. The rule for determining gross pay is to pay the regular pay rate for all hours worked up to 40, time-and-a-half for all hours over 40 up to 54, and double time for all hours over 54. Compute and display the value for al-->
