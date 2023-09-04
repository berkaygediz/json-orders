# E-Commerce Application

This example represents a TypeScript-based application that simulates an e-commerce platform. The application manages products, customers, and orders, and calculates the total amount for each order, including KDV (Value Added Tax).

## Table of Contents

- [Introduction](#introduction)
- [Data Structure](#data-structure)
- [Calculating Total Amounts](#calculating-total-amounts)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Introduction

This code example demonstrates the structure of an e-commerce application with TypeScript. It contains data for products, customers, and orders, and it calculates the total amount paid for each order, considering a KDV rate of 20%.

## Data Structure

- **Products:** An array containing product information, including ID, title, URL, and price.

- **Customers:** An array storing customer data, including ID, name, surname, address, district, and city.

- **Sellers:** An array representing seller companies with their respective IDs.

- **Orders:** An array of orders with details such as customer, seller, date, payment method, shipping address, purchased items, and total price.

## Calculating Total Amounts

The code calculates the total amount paid for each order, including KDV. It then displays the results in the console.

### Usage

```bash
cd e-commerce-json
```

```bash
npx ts-node main.ts
```

### Contributing

Contributions to this code example are welcome! Feel free to fork this repository, make improvements, and create a pull request.

### License

This code is licensed under the [Apache License 2.0](LICENSE).
