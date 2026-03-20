
# DO NOT USE IT, DO NOT WRITE TO ME ABOUT PUBLIC KEYS, I HAVE BAD CODE IN THIS REPOSITORY, THEY CHANGED IT IN THE NEW VERSIONS AND ADDED ATTESTATION



# BsUtils - Brawl Stars Utils
![s](screenshot.jpeg)
BsUtils is a Ruby-based utility tool designed for interacting with Brawl Stars servers (both production and staging). It provides functionalities to boost viewer counts, send friend requests en masse, and create accounts on the servers. 

**Disclaimer**: This content is not affiliated, approved, sponsored or approved specifically by Supercell and Supercell is not responsible for it. For more, see the Supercell Fan Content Policy: www.supercell.com/fan-content-policy

## Features

- **Viewer Count Boosting**: Simulates increased viewer counts on Brawl Stars streams.
- **Friend Request Spamming**: Sends multiple friend requests to targeted users.
- **Account Creation**: Automates the creation of accounts on production and staging servers.
  
## Prerequisites

- Ruby (version 3.0 or higher recommended)
- Basic understanding of Brawl Stars and server interactions

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/FMZNkdv/BsUtils.git
   cd BsUtils
   ```

2. Install ruby 
   ```bash
   sudo apt install ruby-full
   ```

## Configuration

Before using the tool, you need to update the cryptographic key for newer versions of Brawl Stars:

1. Open `stream/peppercrypto.rb`.
2. Replace `'KEY BRAWL STARS'` with the actual encryption key for the target Brawl Stars version.

## Usage

Run the main script:
```bash
ruby main.rb
```

## License

This project is licensed under the **MIT License**. See the [LICENSE](LICENSE) file for details.

## Author
[@FMZNkdv :3](https://t.me/FMZNkdv)
