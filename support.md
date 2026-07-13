# Climb Support

Climb helps you build a debt payoff plan, understand what to focus on next, confirm payments, and track your progress over time.

## Contact

Support email:

[climbappsupport@gmail.com](mailto:climbappsupport@gmail.com)

## Basic Troubleshooting

If Climb is not behaving as expected, try these steps:

1. Close and reopen the app.
2. Confirm your income, expenses, Debt Attack Budget, and debts are entered correctly.
3. Open the Settings tab and review Manage Debts, Edit Financial Snapshot, or Update Debt Attack Budget.
4. If the app still appears stuck, use Reset Saved Data to clear the local plan and start again.

## Reset Saved Data

Reset Saved Data removes your saved Climb plan, debts, payment history, progress snapshots, and local app state from this device. This can help during testing if you want to start the onboarding flow again.

To reset:

1. Open Climb.
2. Tap the Settings tab.
3. Choose Reset Saved Data.
4. Confirm the reset.

## CSV Import Notes

CSV import supports the Climb CSV template format only. Headers must match the required template exactly.

Required headers:

- Debt Name
- Balance
- APR
- Minimum Payment
- Credit Limit
- Debt Type
- Autopay
- Overdue

Supported debt types:

- CREDIT_CARD
- LINE_OF_CREDIT
- INSTALLMENT
- MORTGAGE

## Climb Plus, Billing, And Ads

Climb Plus subscriptions are handled by Google Play Billing. If pricing or purchases are unavailable, confirm that you are using a Play-distributed build and that the subscription products are available to your tester account.

Free users may see one interstitial ad per app session. Climb Plus users do not see ads.

## Analytics And Stability

Climb uses Firebase Analytics for non-sensitive product and onboarding events, and Firebase Crashlytics to help diagnose crashes. These services do not receive the financial values you enter, such as debt names, balances, APRs, payment amounts, income, expenses, or credit score.

## Payment Reminders

Payment Reminders are optional local notifications. If notification permission is denied, reminders stay off and the rest of the app continues to work.

## Closed Testing Feedback

If you are using Climb through a closed testing track, please report:

- Crashes
- Layout problems
- Confusing wording
- Incorrect payment recommendations
- Billing or subscription issues
- Ad display issues
- CSV import issues
- Steps that are hard to understand

Include your device model, Android version, and the screen where the issue happened when possible.

## Important Note

Climb provides debt planning guidance based on the information you enter. It does not make payments, connect to bank accounts, or provide professional financial advice.
