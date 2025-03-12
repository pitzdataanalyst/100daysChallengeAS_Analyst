# 🚀 Day 7:Date & Time Functions

✅ TODAY, NOW, YEAR, MONTH, DAY, EOMONTH, DATEDIF, TEXT,NETWORKDAYS,WORKDAYS

📌 Key Functions I Covered:

✅ TODAY() – Returns the current date.

📌 Example: Ensure it gives Today's Date

	  =TODAY() -> 12-03-2015
	
✅ NOW() – Returns the current date & time.

📌 Example: Ensure it gives Current Date & Time

	  =NOW() -> 12-03-2025 11:12

✅ YEAR(), MONTH(), DAY() – Extracts specific parts of a date.

📌 Example: It Results in Year,Month & Day

		Taking the example from this: 12-03-2025 
	  =YEAR() -> 2025
	  =MONTH() -> 03
	  =DAY() -> 12

✅ EOMONTH() – Finds the last day of a given month.

📌 Example: It Results in last day of a given month

		Taking the example from this:  03-Apr-18
	    =EOMONTH(A4,0) -> 30-04-2018

✅ EDATE()- Finds the Exact Date after Specified Month

📌 Example: It Results in Exact Date after Specified Month

		Taking the example from this:  03-Apr-18 
	  =EDATE(A13,1) -> 03-05-2018

✅ NETWORKDAYS()Calculate the number of working days (excluding weekends and optional holidays) between two dates.

📌 Example: It Results in working days

		Taking the example from this:
		Start date - 01-01-2018
		End Date - 31-03-2018
	  =NETWORKDAYS(B20,B21) -> 65 (WITHOUT HOILDAYS)
	  =NETWORKDAYS(B20,B21,E21:E22) -> 63 (WITH HOLIDAYS)
	
✅ WORKDAYS() It Gives the last working days 

📌 Example: It gives the last working day

	  Start date - 01-01-2018
    End Date - 31-03-2018
	  =WORKDAY(B31,B32) -> 28-03-2018

✅ DATEDIF() – Calculates the difference between two dates.

📌 Example: It gives the difference between 2 dates.

		Taking the example from this: 
			Date of Birth
			16-06-2010
			12-03-2025
	  =DATEDIF(A60,A61,"y") -> 14

✅ TEXT() – Formats dates in a custom way.

📌 Example: It gives the date as users want.

		Taking the example from this: 01-01-2020
			TEXT (DAY) =TEXT(A43,"d") ->1	
			TEXT (MONTH) =TEXT(A43,"m") ->1			
			TEXT (YEAR) =TEXT(A43,"y") ->2020

🛠 Real-World Example: Find Employee Tenure

📌 e.g. Calculate how long an employee has worked in a company using DATEDIF.

🔍 Formula: =DATEDIF(A2, TODAY(), "Y") & " years, " & DATEDIF(A2, TODAY(), "YM") & " months"

👉 If A2 contains Joining Date, this formula calculates the total years and months worked!

💡 Date functions are crucial for financial models, project tracking, and HR analytics. 

Have you used them in your work? Let’s discuss in the comments! 👇

#100DaysOfData #ExcelForDataAnalysts #DateFunctions #ExcelTips #SpreadsheetSkills #DataPreparation #BusinessAnalytics #LearnExcel #DataAnalysis #Productivity

🔗 [Detailed Post on LinkedIn](https://www.linkedin.com/posts/priyankataklikar_100daysofdata-excelfordataanalysts-datefunctions-activity-7305314475648155648-lb3J?utm_source=share&utm_medium=member_desktop&rcm=ACoAAB-nGUABJpvbVVs-0wlzvYqfT4t927RgnpI)
