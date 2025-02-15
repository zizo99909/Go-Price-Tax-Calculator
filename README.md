# Go Price Tax Calculator

## Description
Go Price Tax Calculator is a CLI-based application developed in Go that calculates the tax on a list of product prices. It efficiently manages input and output files, processes price data, and applies tax rates to generate detailed result files.

## Features
- Read product prices from input files
- Apply custom tax rates
- Output calculated prices to JSON files
- Modular design with organized packages

## Installation
1. Clone the repository:
    ```
    git clone https://github.com/zizo99909/Go-Price-Tax-Calculator.git
    cd Go-Price-Tax-Calculator
    ```
2. Install dependencies:
    ```
    go mod tidy
    ```

## Usage
1. Ensure your prices are listed in `prices.txt`
2. Run the application:
    ```sh
    go run main.go
    ```
3. Output files (e.g., `result_0.json`) will be generated with calculated tax.

## Contributing
1. Fork the repository.
2. Create a new branch (`feature/new-feature`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Open a pull request.

## License
This project is open source and available under the MIT License.

