# 🎩 Monopoly Banker — Realtime

**Live Game Link:** [Monopoly Banker on GitHub Pages](https://manojrajpa.github.io/monopoly/)  

A **realtime, browser-based banking system** for Monopoly.  
No paper money required — track all player balances, bank transactions, and loans online.

---

## 📜 Features
- **Host / Banker System** — 1 player is the Banker by default.
- **Game Code Join** — Host creates a game, shares a 6-character code, others join.
- **Player Management**
  - Add players with nicknames & token names
  - Remove players (Banker only)
- **Transactions**
  - Player ↔ Player
  - Player ↔ Bank
  - Banker can perform all transaction types
  - Prevents fake/self-transactions
- **Loans**
  - Banker can issue loans
  - Players can repay their own loans only
  - Interest tracking and outstanding balance calculation
- **Salary on GO**
  - Banker can give +$200 salary via dropdown
- **Ledger**
  - Shows last 15 transactions with scroll
  - Most recent at the top
- **Assets Calculation**
  - Shows each player’s cash + remaining loans
- **Sticky Cash Display**
  - Cash in hand is always visible at the top

---

## 🎯 How to Play
1. **Host (Banker)**
   - Open the [game link](https://manojrajpa.github.io/monopoly/)
   - Click **Create Game**
   - Share the generated game code with other players

2. **Players**
   - Open the same [game link](https://manojrajpa.github.io/monopoly/)
   - Enter the shared game code
   - Set your nickname & token (can be done only once)

3. **During the Game**
   - Banker manages the bank, loans, salaries
   - Players can only:
     - Send money to other players or the bank
     - Repay their own loans
   - All actions update in realtime for all players

4. **End Game**
   - Banker clicks **End Game**
   - Everyone sees the end screen with final assets
   - Refresh to start a new game

---

## 🛠️ Technology Stack
- **Frontend:** HTML, CSS (Tailwind), JavaScript
- **Backend:** [Supabase](https://supabase.com/) (Database + Realtime API)
- **Hosting:** GitHub Pages

---

## 📌 Notes
- The **Banker role** cannot be changed once the game starts
- “Set Me” for player identity can be done only once per game
- Player names and token names are unique per game
- Loan repayment cannot exceed the outstanding amount
- Player transactions are blocked if they don’t have enough cash

---

## 👨‍💻 Author
Built by **Manoj Raj** — Monopoly lover & tech enthusiast.  

---

### 🎲 Have fun, and may you never land on Boardwalk with a hotel!
