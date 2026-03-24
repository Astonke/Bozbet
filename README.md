# BozBet — README

## Overview

**BozBet** is an online betting platform designed to provide users with a streamlined experience for placing bets, managing accounts, handling transactions, and tracking betting activity. The platform is structured to be simple, fast, and accessible through a clean web interface.

👉 **Main Site:** https://bozbet.free.nf/

---

## Purpose

BozBet allows users to:

- Register and create an account
- Log in securely
- Place and review bets
- Deposit funds into their wallet/account
- Request withdrawals
- Track betting history and transactions
- Manage personal account settings

---

## Key Features

- **User Authentication System**
  - Secure registration and login
  - Session-based access control

- **Betting System**
  - Place bets through the betting interface
  - Review bets before confirming
  - View bet outcomes and history

- **Wallet & Transactions**
  - Deposit funds
  - Withdraw funds
  - Transaction status tracking (success/failure)

- **Account Management**
  - View and update account details
  - Access betting and transaction history

---

## Site Structure (Clean Routes)

The platform uses clean URLs (without `.php` extensions):

### Public Pages
- Home:  
  https://bozbet.free.nf/

### Authentication
- Login:  
  https://bozbet.free.nf/auth/login
- Register:  
  https://bozbet.free.nf/auth/register

### Core Betting
- Place a Bet:  
  https://bozbet.free.nf/bet
- Review Betslip:  
  https://bozbet.free.nf/review-betslip

### Wallet / Transactions
- Deposit Funds:  
  https://bozbet.free.nf/deposit
- Withdraw Funds:  
  https://bozbet.free.nf/withdraw

### User Account
- Account Dashboard:  
  https://bozbet.free.nf/account
- Bet History:  
  https://bozbet.free.nf/bet-history

### Transaction Status
- Withdrawal Success:  
  https://bozbet.free.nf/success-withdraw
- Withdrawal Failed:  
  https://bozbet.free.nf/failed-withdraw

---

## Sitemap

The platform sitemap is structured to help search engines index all important pages efficiently. It prioritizes:

- Homepage (highest priority)
- Authentication pages
- Betting and transaction pages
- User account and history pages

This ensures optimal crawlability and discoverability across the site.

---

## SEO Considerations

BozBet is structured with SEO-friendly URLs and organized page hierarchy to improve:

- Search engine indexing
- Page discoverability
- User navigation experience

Recommended SEO practices for further improvement:

- Add meta titles and descriptions for each page
- Include Open Graph tags for social sharing
- Use structured data (schema markup) where applicable
- Ensure fast page load times
- Maintain mobile responsiveness

---

## Navigation Flow

Typical user journey:

1. Visit the homepage  
   👉 https://bozbet.free.nf/
2. Register or log in  
   👉 /auth/register or /auth/login
3. Deposit funds  
   👉 /deposit
4. Place bets  
   👉 /bet
5. Review betslip  
   👉 /review-betslip
6. Track outcomes  
   👉 /bet-history
7. Withdraw winnings  
   👉 /withdraw

---

## Notes

- All routes are configured without `.php` extensions.
- The backend handles routing internally.
- Users must be authenticated to access restricted pages such as betting, deposits, withdrawals, and account sections.

---

## License / Usage

This project is intended for internal use and demonstration purposes. Modify and extend as needed depending on deployment requirements.

---

## Quick Access

👉 Go directly to the platform:  
https://bozbet.free.nf/
