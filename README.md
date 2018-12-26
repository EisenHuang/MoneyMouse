# MoneyMouse
Final project for iOS Programming at NYU

1) Download MoneyMouse and open it.

2) Navigate to the main directory of MoneyMouse. Then run the following command line:

pod install

3) Now install carthage (assuming you have homebrew). Homebrew will update automatically when you run this command.

brew install carthage

4) Make sure you have Xcode linked to terminal. Go to Xcode > Preferences > Locations. Click on the "Command Line Tools" bar and click on your version of Xcode that pops up.

5) Run the following command now that we're set up.

carthage update

6) Now run MoneyMouse. Use the iPhone 8 for alignment purposes. You'll be taken to a launch screen and then to the welcome screen. You can sign up with your own info and then you'll be logged in automatically, or use our dummy account – email: 123@gmail.com | password: 123456 – and click login.

7) You should now see a screen with either no budget bars (if you used a new account) or a set of progress bars if you used our dummy account or logged back in.

8) You can sign out by hitting the button in the upper right corner of your screen. The app saves your data when you log out.

9) You are currently navigated to the mouse icon in the lower left (in green).

10) To add an expense, hit the plus-sign-looking mouse icon in the upper left of your screen. You can choose a budget category by scrolling through the options on the bottom of your screen. When you select a category as you scroll, the type of budget towards the top-center of your screen will update to the one you have selected.

11) You can enter a budget amount in the first bar (in dollars) and a name for your budgeting goal in the next one. When you are finished, add your budgeting goal. The app handles trying to enter a negative budget amount.

12) A new budget will pop up on your progress screen if the budget name is new, and will not allow a duplicately named budget to be added.

13) If you want to delete a budget, swipe left and hit delete.

14) To add an expense, tap the charts icon in the lower right, and tap "Add an Expense" in the upper right of your screen.

15) Enter an amount spent in the first bar and the budget you want to attribute that expense to. Hit "Add Expense!" when done. The app handles negative and zero values for "Amount Spent" and also handles if the budget name you have entered does not match and existing budget.

16) When you add an expense, you will be brought back to the main screen.

17) Enjoy using our app!

18) Thank you Uncle Nathan for a great semester!
