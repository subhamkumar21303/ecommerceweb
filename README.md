This whiteboard sketch outlines the workflow and UI wireframes for an **internal employee nomination and voting system**, likely for an awards or recognition program.
Here is a breakdown of the three main sections drawn on the board:
### 1. Nomination Submission (Left Side)
This section defines the entry point and business logic for submitting a nomination.
 * **Role Setup:** It specifies that a standard Employee holds the role to submit a nomination.
 * **Validation Rule:** There is a strict constraint written at the top: *"Validation -> Only 1 time in a quarter per category."* This ensures an employee isn't spammed with multiple nominations for the same award in a single period.
 * **Automated Communication:** Once a Nomination Submission is completed, it flows to the Person Nominated. The system must trigger an automated notification (*"Should get Email"*). Below this, there's a note about needing an *"Email Template Draft / Review"* to standardize these messages.
### 2. Panelist/Admin Review Dashboard (Middle)
This represents the UI where reviewers (Panelists or Admins) evaluate the nominations.
 * **Time-Boxed Voting:** A key requirement noted at the top is *"Review -> Only open for Voting for small duration (Configurable & easy to change)."*
 * **Filtering:** The dashboard includes comprehensive filtering options, specifically a Date filter (From Date - To Date) and a Quarter filter (e.g., Q1).
 * **Data Grid:** The main UI is a table displaying the nominations. Row 1 details the required columns:
   * **[PSID]**: The unique employee identifier of the nominee.
   * **[Citation]**: The justification or story behind why they were nominated.
   * **[Y] / [N]**: Action buttons allowing the panelist to cast a Yes or No vote.
### 3. Leaderboard / Results (Right Side)
This is an exclusive view for the Admin to track the outcome of the voting.
 * **Ranking:** It features a LeaderBoard / Results section that lists the top candidates (numbered 1 through 5).
 * **Metrics:** It displays the nominee's ID (PSID) alongside their total No. of Votes to determine the winners for that specific quarter/year.
Are you planning to build this out into a functional prototype, or are you currently just refining the business requirements?
