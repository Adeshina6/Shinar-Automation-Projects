Workflow Descriptions

1. Price Optimization Agent
What it does: Automatically monitors competitor prices, models demand sensitivity, and uses Claude AI to recommend optimal pricing every 6 hours.
How it works: Pulls competitor pricing data via API, runs it through a demand elasticity model and price simulation engine, then sends the results to Claude for strategic interpretation. Outputs go to Google Sheets and Gmail, with priority alerts for high-impact price gaps.
Business value: Eliminates manual price monitoring. Keeps your pricing competitive and margin-aware in real time, without anyone having to watch the market.

2. Inventory + Demand Agent
What it does: Every Monday morning, it analyzes your sales history, forecasts demand for the week ahead, and flags any products that need restocking before they run out.
How it works: Pulls sales, inventory, and product data from Google Sheets, calculates reorder points and demand trends, then fires alerts to Slack, Telegram, and email for items that need action. Results are logged back to a dashboard and forecast log automatically.
Business value: Prevents stockouts and overordering. Gives operations teams a clean weekly briefing so nothing slips through the cracks.

3. HR Assistant (Dynamic JD)
What it does: Screens job applications the moment they land in Gmail — reads CVs, scores candidates against the job description, and books interviews for the best fits, all without human intervention.
How it works: Triggered by incoming emails, it extracts CV text from PDF or TXT attachments, checks for duplicates, runs a bias-free AI parse and weighted scoring engine, generates tailored interview questions, then sends interview invitations, creates calendar events, and emails recruiters a full candidate report.
Business value: Cuts screening time from days to minutes. Every qualified candidate gets a fast, consistent, documented response — and recruiters only see people who actually fit the role.
