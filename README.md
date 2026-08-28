# Family Cash Flow Forcaster

**Live app:** https://boredofwords.github.io/balance-forecast/

Family Cash Flow Forcaster is a small cash-flow planning app I originally built for myself because a normal monthly budget never answered the question I actually needed answered:

> **Not just “Can I afford this?” but “When can I afford this?”**

Household finances don’t happen neatly once a month. Paychecks arrive on specific dates. Bills hit on different days. One-time expenses pop up. A purchase can be completely affordable on paper and still land at exactly the wrong point between paydays.

I wanted one place where I could see all of that on an actual timeline and answer a much more useful question:

> **What will my balance look like on the day this actually gets charged?**

That’s what this app does.

## What it does

Family Cash Flow Forcaster lets you map income, bills, planned purchases, savings, and other expenses onto the dates when the money actually moves.

It includes:

- A running balance forecast over time
- Income and recurring bills organized by actual dates
- One-time expenses
- A Paycheck Planner for seeing what needs to be covered between pay periods
- A chronological cash-flow timeline
- Savings and financial goals
- The ability to model a planned expense before committing to it
- A reusable, editable Trip Planner for grouping travel costs and seeing them in the context of the rest of the household forecast
- Automatic migration of locally saved data as the app is updated

The Trip Planner currently uses my own Seattle trip as the starter template, but it’s meant to be edited. You can rename the trip, change the dates, and replace my airfare, lodging, rental car, food, activities, and other travel costs with your own.

The useful part is that those expenses aren’t sitting in a separate vacation budget disconnected from everything else. Each charge can be placed on the date it will actually hit, so you can see exactly how the trip affects the rest of your household cash flow.

## Why I built it

Traditional budgets are great at answering questions like:

> “How much do I spend in a month?”

That wasn’t really my problem.

If three large bills come out on the 14th and I get paid on the 15th, a monthly budget can tell me everything balances perfectly while being completely unhelpful about what happens on the 14th.

The reverse is true too. A low balance today doesn’t necessarily mean I can’t afford something that won’t be charged for another three weeks.

I wanted the calendar and the money to exist in the same place.

So I built the tool I wanted.

## If you found this somehow

Hi. :)

This wasn’t originally built as a product. It’s a personal project designed around the way I think about and manage my own household cash flow.

But if this way of looking at money makes sense to your brain too, **you’re welcome to use it.**

The live version is here:

https://boredofwords.github.io/balance-forecast/

You can also fork or download the project and adapt it to your own needs.

Just keep in mind that this is a personal project, not financial software or financial advice. I built it to help visualize cash-flow timing, not to replace your bank records or accounting tools.

## Using the app

The app is a static GitHub Pages site and runs entirely in the browser.

On iPhone, open it in Safari, tap **Share**, then **Add to Home Screen**, and it behaves much more like a standalone app.

Your working data is stored locally in your browser. Use the app’s **Export** feature periodically to keep a backup, particularly before clearing browser data or moving to another device.

## Privacy & bank connections

The current version does **not** connect directly to Plaid, your bank account, or a financial institution.

The financial information you enter is stored locally in your browser rather than being sent to a backend database.

---

Built for myself because **“Can I afford it?” is usually a timing question.**

Shared because maybe it is for you, too.
