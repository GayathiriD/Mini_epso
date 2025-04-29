
# Mini EPOS Simulator

A simple Python-based Electronic Point of Sale (EPOS) system simulator built for demonstrating transaction flows, cart management, and payment processing — aligned with real-world retail and hospitality use cases.

## Features

- Display a catalog of products
- Add/remove products from a cart
- Simulate checkout with random payment success/failure
- Generate printed receipts for successful transactions
- Clear the cart after each transaction
- Command-line interface (CLI) based for easy interaction

## Tech Stack

- Python 3.x (no external libraries needed)
- Random module (for payment simulation)
- Sys module (for clean program exit)

## Project Structure

```
mini-epos/
│
├── app.py            # Main application logic
├── README.md         # Project documentation
├── requirements.txt  # (Optional if using external libraries later)
└── tests/             # (Optional folder for future unit tests)
```

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/mini-epos.git
cd mini-epos
```

2. Run the application:

```bash
python app.py
```

3. Follow on-screen instructions:
- Add items by product ID
- Remove items using 'remove [ID]'
- Checkout to simulate payment
- Exit the system when done

## Example Interaction

```plaintext
Available Products:
1. Coffee - £2.50
2. Sandwich - £5.00
3. Cake - £3.00
4. Juice - £2.00
5. Salad - £4.50

Select Product ID to add, 'remove [ID]' to remove, 'checkout' to pay, or 'exit' to quit:
> 1
> 2
> checkout

Processing Payment...
Payment Successful! Transaction ID: TXN97751

----- RECEIPT -----
Coffee - £2.50
Sandwich - £5.00
Total: £7.50
Transaction ID: TXN97751
Thank you for shopping with us!
--------------------
```


## License

This project is licensed under the MIT License - feel free to use and modify it.

## Author

Built by [Gayathiri Yuvaraj] to demonstrate practical application of payment systems, customer transaction flow, and software robustness for modern fintech companies.


