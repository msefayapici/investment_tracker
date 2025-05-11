# Privacy Policy

_Last updated: 2025-05-11_

**Investment Tracker** (“we”, “us”, “our”) built on Notion and yfinance, respects your privacy.  This policy explains:

1. **What data we collect**  
2. **How we use it**  
3. **How we share and secure it**  
4. **Your rights**  

---

## 1. Information We Collect

- **Notion Data**  
  – Ticker symbols, quantities, and any market data you store in your Notion database.  
  – We only read/update the database pages you explicitly share with our integration.

- **OAuth Tokens**  
  – When you authorize our public integration, we store a single `access_token` (encrypted) so we can fetch/update your pages on your behalf.  
  – We do **not** access any other Notion content.

- **Usage Logs**  
  – Timestamped records of when our script runs, for debugging and rate-limit handling.  
  – No personal identifiers (IPs, browser fingerprints) are logged.

---

## 2. How We Use Your Data

- **Fetch & update pricing** from yfinance to keep your portfolio current.  
- **Calculate performance metrics** (1W/1M/1Y changes) and push them back to Notion.  
- **Error reporting**: if a stock symbol fails or our token expires, we’ll log that for you to see.

We **never** sell or share your data with third parties.

---

## 3. Data Sharing & Security

- **Third-party services**:  
  – Notion API (to read/write your database)  
  – yfinance (to fetch market data)  

- **Storage & encryption**:  
  – OAuth tokens are encrypted at rest (AES-256).  
  – Our server (or your local machine) retains **only** the tokens and minimal run logs.

- **Retention**:  
  – We keep your token as long as you have our integration installed.  
  – To revoke at any time, uninstall the integration from your Notion workspace.

---

## 4. Your Rights

- **Access**: see which workspaces you’ve connected under Notion’s “My Integrations.”  
- **Revoke**: remove the integration from your Notion workspace to instantly cut off our access.  
- **Erase**: contact us at mustafasefayapici@gmail.com to request permanent deletion of your token and logs.

---

**Contact**  
If you have any questions or concerns, email us at **mustafasefayapici@gmail.com**.

