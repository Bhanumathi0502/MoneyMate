# MoneyMate — Finance & Budget Tracker (MCA Hackathon)

A React Native + Expo prototype built for the RVS College of Arts and Science (Autonomous), SCS-MCA Semester III Mobile App Development major hackathon brief.

## Requirements covered
- Welcome/home with Sign in and Sign up, role selection for Admin and Customer.
- Analysis dashboard available to both roles.
- Customer profile and edit profile with validation.
- Day/week/month transaction filter, search, and income/expense filters.
- Overall categories and category detail pages.
- React Navigation Stack, Bottom Tabs, and Drawer.
- Add/edit transactions with amount/title/date validation and a personalized Alert when transaction data changes.
- Daily, weekly and monthly expense report cards on the dashboard.
- No backend or database; sample transactions are held in memory for the demo.

## Run on Windows (Node 20+)
1. Extract the ZIP.
2. Open Command Prompt in the `MoneyMateExamApp` folder.
3. Run:
   ```bat
   npm install
   npx expo start -c
   ```
4. Scan the QR code using Expo Go that supports your installed Expo SDK, or press `a` if Android Studio emulator is configured.

If your project already has Expo SDK 57, keep your Node installation as-is. This ZIP is configured for Expo `~57.0.31`, React `19.2.3`, and React Native `0.86.3`.

## Demo login
Select Admin or Customer on the welcome screen. Enter any valid email (must contain `@`) and a password of at least 4 characters. This is a local demo login, not real authentication. Customer role shows the Profile drawer item; Admin role hides it.

## Notes
- Data is intentionally in-memory because the examination brief says no backend/database is required. Restarting the app resets sample data.
- Currency shown is INR (₹).
- Design uses a polished navy/indigo financial dashboard style inspired by common finance-app patterns. The supplied Figma URL was not accessible to the web viewer, so exact 75% pixel matching must be checked against the Figma file on your side.
