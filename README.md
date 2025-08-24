# expense-tracker
I built this expense-tracking web application to solve a daily problem that my two friends and I often face. We usually eat together and go grocery shopping as a group. The problem is that the payment isn’t always consistent—sometimes I pay, and other times one of them does. This often leads to confusion on money mismatches. This is the solution.
Welcome to Jesmin Khalar Vater Hotel – a simple web app I built to fix a very real (and sometimes annoying 😅) problem:
me (Sayem) and my two buddies (Shovon and Tanvir) often go grocery shopping together, but we don’t always pay together.
Some days I pay, some days Shovon does, and other days Tanvir. By the end of the month, it’s hard to remember who owes what.

So… this app keeps things fair without needing a calculator, mental math, or arguments over “bro, I paid last time.”

✨ Features (a.k.a. Why this is cool)

Add grocery expenses → Date, item/expense name, total amount, and who paid.

Smart validation → Stops you from saving unless amounts actually add up.

Auto settlement → Splits expenses evenly and shows who owes whom.

Monthly filter → Check balances for all-time or a specific month.

Data persistence → Stored in browser’s localStorage (stays even after refresh).

Clear all option → Reset everything if you want a clean slate.

🛠️ How It Works

Open the app in your browser (no server needed, it’s plain HTML + CSS + JS).

Add an expense → e.g., “Groceries, total ৳900, Shovon paid ৳500, Sayem paid ৳200, Tanvir paid ৳200.”

The app calculates each person’s fair share and tracks who’s ahead or behind.

At any time, check the Settlement Summary → it directly tells you “X owes Y ৳Z.”

Done ✅

📂 Project Structure

index.html → Everything (HTML, CSS, and JS) in one file.

Uses vanilla JS (no frameworks, no build tools).

Storage → Browser localStorage.

🤝 Why This Exists

Honestly, just to make grocery shopping fair for the three of us.
Instead of awkwardly reminding each other “bro, you still owe me 200 taka from last week,”
we just log it here and let the app do the talking. 😎

📌 Future Ideas (if I don’t get lazy)

Donno maybe a mobile friendly design??

👨‍💻 Author

Built by Sayem
