# DomainScanner

DomainScanner is a Python tool for scanning and checking the registration status of domains. It's designed to quickly identify the availability of domain names based on specific rules, such as prefix and total length, across different top-level domains (TLDs).

## Features

- **Fast Domain Checking**: Leverages multi-threading to quickly scan through a list of potential domain names.
- **Customizable Searches**: Allows users to specify domain prefixes, desired length, and specific TLDs to tailor the search.
- **WHOIS Integration**: Utilizes WHOIS queries to check domain registration status accurately.
- **Easy to Use**: Simple CLI interface for straightforward operation.

## Installation

Before you begin, ensure you have Python 3.6+ installed on your system. You can install DomainScanner using the following steps:

1. Clone the repository:

```bash
git clone https://github.com/yourusername/DomainScanner.git
```

2.  Navigate to the project directory:
```bash
cd DomainScanner
```
3. Install required dependencies:
```bash
pip install -r requirements.txt
```


## Usage

To use DomainScanner, run the following command from the terminal:
```bash
python scan.py --tld=com --prefix=xx --num=4
```

This command scans for domains that start with "xx", have a total length of 4 characters, and are under the `.com` TLD.

### Arguments

- `--tld`: Specifies the top-level domain to search (e.g., com, net).
- `--prefix`: The beginning characters of the domain names to scan.
- `--num`: Total length of the domain names to check.

## Contributing

Contributions to DomainScanner are welcome! If you have an improvement or bug fix, please feel free to fork the repository and submit a pull request.

## License

DomainScanner is released under the MIT License. See the LICENSE file for more details.
