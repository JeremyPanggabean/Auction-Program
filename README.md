# Auction Program

Welcome to the Auction Program! This is a simple Python program that allows multiple users to place bids in an auction and determines the highest bidder.

## Features

- Collects bids from multiple users
- Determines the highest bid and the winner
- Simple and easy-to-use command-line interface

## How It Works

1. The program starts by displaying a logo.
2. Users are prompted to enter their name and bid amount.
3. The program asks if there are any other bidders.
4. If there are more bidders, the screen is cleared, and the next user can place their bid.
5. Once all bids are collected, the program determines the highest bid and announces the winner.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/JeremyPanggabean/Auction-Program.git
   cd Auction-Program
   ```

2. Run the program:

   ```bash
   python auction_program.py
   ```

3. Follow the on-screen instructions to place bids.

## Example

```plaintext
Welcome to the Auction Program!
What is your name?: Alice
What is your bid?: $100
Are there any other bidders? Type 'yes' or 'no'.
yes

What is your name?: Bob
What is your bid?: $150
Are there any other bidders? Type 'yes' or 'no'.
no

The winner is Bob with a bid of $150.
```
