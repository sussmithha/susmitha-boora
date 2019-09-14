# TEST PLAN : TEST SCENARIOS AND TEST CASES
1. Installation and Launch testing. 
2. Functional testing.
3. Interrupt testing.
4. Usability testing.
5. Recoverability testing.
6. Security testing.
7. Performance testing.

Installation and Launch testing test cases
1.		(Priority 1) Check that the 'Monefy' app is can be downloaded from both iOS and Android operating systems and gets installed/uninstalled smoothly.	

Functional testing test cases
1.		Check that the home screen of the app displays all the required features.
		a.	(Priority 1) Check that the 'New income', 'New expense', 'New transfer' and the Category icons are displayed and each of them is clickable.
		b.	(Priority 1) Check that the day(/week/month/year <which ever is chosen>), pie chart, expense and balance are displayed correctly.
		c.	(Priority 2) Check that home screen slides horizontally to display the 'expense-income' pie chart and 'balance' of the consequential day/week/month/year.
		d.	(Priority 1) Check that the top left and right corners of the home screen have ellipsis which open up slide menus.
		e.	(Priority 2) Check that each of the slide menus display the required options and each of them is clickable.
2.		Check that every clickable icon or menu option, opens up its respective screen or performs its corresponding action as expected.
		a.	(Priority 1) Check that the 'New income' and 'New expense' icons, when clicked, open up a screen with a keypad to enter an amount and choose a category.
		b.	(Priority 1) Check that when each of the category icon is clicked, opens up the 'New expense' screen to enter an amount in that category.
		c.	(Priority 2) Check that the 'New transfer' icon, when clicked, opens up a screen to enter an amount and toggle between 'card to cash' and 'cash to card' transfers.
		d.	(Priority 2) Check that the 'Balance' icon, when clicked, slides upwards to show a screen with the transaction records of a given time period.
		e.	(Priority 2) Check that the left slide menu has clickable options to toggle between card/cash/both accounts, to choose a time period and to choose a date from calender.
		f.	(Priority 2) Check that when you toggle between the cash/card accounts or when a date or time period is changed, the home screen refreshes itself to display the expense and income accordingly.
		g.	(Priority 1) Check that the right slide menu has clickable sub menu options called 'Categories', 'Accounts', 'Currencies', 'Settings'.
3.		Check that the income and expense calculations are accurate and are correctly displayed in the pie chart and in 'Balance' icon.	
		a.	(Priority 1) Check that income can be added into any of 'Deposits', 'Salary', 'Savings' or any other customized category.
		b.	(Priority 2) Check that when expenses are added to different categories, their share is shown in the pie chart in percentages.
		c.	(Priority 1) Check that balance is calculated accurately and displayed as a  positive or a negative value on the 'Balance' icon.
		d.	(Priority 1) Check that when clicked on a single transaction in the 'Balance' screen, opens up a screen to edit the amount, an option to change the category and a delete icon.
		e.	(Priority 1) Check that as soon as any transaction is made, a notification appears at the bottom of the screen for less than a second, it should have an option to cancel.
		f.	(Priority 1) Check that when clicked on the cancel option in the notification, the transaction is cancelled and expenses, income and balance are restored accordingly.
		g.	(Priority 2) Check that a long press on any transaction record in the 'Balance' screen shows up a 'delete' icon on the top right corner of the home screen.
		h.	(Priority 1) Check that when any expense or income transaction is deleted using the delete icon in the 'Balance' screen, the home screen is refreshed to show the latest status.

Interrupt testing test cases
1.		Check that the app should be suspended and later launched from the place it was stopped without losing unsaved data, when its interrupted by any of the below reasons.	
	 	a.	(Priority 1) Check that the app recovers after either an upcoming call, message, other apps notifications, mail, low memory warning, inserting a cable, etc.
2.		Check that the mobile phone is able to multitask whenever necessary even when the app is up and running.	
	 	a.	(Priority 1) Check that the phone is able to receive calls, messages, notifications when the app is running.
	 	b.	(Priority 2) Check that the accessibility options like wifi, data connection, bluetooth, GPS, hotspot, flashlight, screenshot, power/restart, DND, auto-rotate, alarm etc. work when app is running.

Usability testing test cases
1.		Check that the icons, features and colours are consistent across the screens and sub screens of the app.	
		a.	(Priority 1) Check that the 'expenses' are always red in colour and 'income' is always green in colour in every screen or sub screen through out the app.
		b.	(Priority 1) Check that the 'expenses' are always deduct money and 'income' is always adds money in every screen or sub screen through out the app.
		c.	(Priority 2) Check that look and feel of the app is pleasant and the colours and images of the icons is consistent through our their appearance in the app.
2.		Check that the various accessibility options in 'Settings' sub menu are self-explanatory and easy to use.	
		a.	(Priority 2) Check that three balance view options are available called 'budget mode', 'carry over', 'Future recurring records' and can be selected more than 1 at a time.
		b.	(Priority 2) Check that general settings to change theme, language, currency, passcode are available.
		c.	(Priority 1) Check that the general settings has 'About Monefy' which explains the app and 'Privacy policy' which opens the policy in browser.
		d.	(Priority 2) Check that different data back up options are available and Synchronization options are available with Dropbox and Google drive.
		
Recoverability testing test cases
1.		Check the Crash recovery and transaction interruptions.	
		a.	(Priority 1) Check the validation of the effective application recovery situation post unexpected interruption/crash scenarios.
		b.	(Priority 2) Check how the application handles a transaction during a power failure (i.e. Battery dies or a sudden manual shutdown of the device)
		c.	(Priority 1) Check that the app is minimized or suspended on the event of a call and then whenever the call stops the application is resumed

Security testing test cases
1.		Check the 'Monefy Pro' feature in detail as it involves direct link to users bank/ PayPal account/ credit and debit cards.	
		a.	(Priority 1) Check that the Settings sub menu has the 'Monefy Pro' feature which has an option to purchase the 'Pro' features by linking Paypal or any other payment method.
		b.	(Priority 1) Check that when the user keeps clicking on the back icon of this mobile, navigates him to cancel page when he can click on 'No thanks' to cancel or 'continue' to continue the purchase.
		c.	(Priority 1) Check that if the user whats to continue to purchase the pro features the back account/ paypal account/ card connections are secure and accurate.
		d.	(Priority 2) Check that any of the pro feature when it appears in the settings menu, when clicked navigates the user to the 'Monefy pro' page.

Performance testing test cases
1.		Check the response time of the different features of the app.	
		a.	(Priority 1) Check that all the main menu options like 'New income', 'New expense', 'New transfer', categories, 'Balance' etc respond quick enough as expected.
		b.	(Priority 1) Check that the sub menu options available in 'settings' menu respond quick enough and as expected.
		c.	(Priority 2) Check that the accessibility features like view settings and themes respond quick enough as expected.
2.		(Priority 1) Check the power utilization, memory consumption, switching between apps and memory leakage related issues of the app	
