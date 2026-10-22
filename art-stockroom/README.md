# Art Supply Stockroom

An inventory and shop-management app for an art-materials shop in Bangladesh (prices in Taka ৳).

**Open the live app:** https://claude.ai/artifact/VJddBHXqiF7DgZ3FrTtBCp

## Features

- **Items:** buying price, selling price, profit per unit, stock, reorder level
- **Combos:** sets of items sold at one price. Selling a combo takes each item inside it out of stock
- **Sales:** cash and credit sales with invoice numbers, channels (Shop, Facebook, Instagram, WhatsApp…)
- **Customers:** contacts, purchase history and money owed
- **Receive:** payments from customers against credit sales (Cash, bKash, Nagad, Rocket, Bank, Card)
- **Purchases and Suppliers:** cash or credit bills, supplier balances
- **Payment:** money paid to suppliers
- **Expenses:** rent, delivery, packaging and other running costs
- **Reports:** profit and loss, cash in and out, profit by item
- **Team:** Owner, Manager and Salesperson roles
- **AI assistant:** type what happened in plain words ("Sold 2 sketchbooks to Rina on credit, she paid ৳200") and it updates stock, sales, payments and expenses. The sale form can also fill a whole list of items at once.
- Edit and delete on every record, with stock corrected automatically

## How it runs

The app is a single HTML file published as a Claude artifact. It saves data and uses AI through Claude's artifact runtime (`window.claude`). That means the database and the AI work only when the page is opened from its claude.ai link above. Opened anywhere else, such as from this repository or GitHub Pages, the page loads but can't save data or use the assistant.
