
# Arkade Explorer
**Proto-explorer for Arkade / Fulmine.**
<br>Build with LLM.
<br>Working but not yet reviewed.
<br>An example at https://resources.davidcoen.it/arkexplorer/


## Overview

Arkade Explorer is a web-based tool that allows users to explore and query Arkade addresses (not yet implemented), scripts, and transaction IDs. It provides detailed information about vTXOs and enables users to group and filter results.

## Features

- **Address, Script, and Transaction Search**: Users can enter an Ark address (not yet implemented), script, or transaction ID to query the Arkd server data.
  
- **Spendable vTXOs Filter**: Enables filtering of vTXOs to show only those that are spendable.

- **Group by Commitment Transaction**: Users can group the results by commitment transactions, allowing for a more organized view of related entries.

- **Collapsible Groups**: Commitment transaction groups are collapsible, providing a cleaner interface that users can expand as needed.

- **Link to External Resources**: The tool provides links to view onchain transactions on external platforms like mempool.space.

## Usage

1. **Search**: Enter a transaction ID, script, or Ark address (not yet implemented) in the search box and click "Search".

2. **Filter Options**: 
   - Use the "Only spendable" checkbox to filter the results to show only spendable vTXOs.
   - Use the "Group by commitment transaction" checkbox to organize results by their commitment transaction.

3. **View Results**: 
   - If grouped by commitment, click on the chevron next to each commitment transaction to expand or collapse the group.
   - Click on linked transaction IDs to view detailed transaction information on mempool.space.

## Requirements

- A modern web browser with JavaScript enabled.

## How It Works

Upon entering a query, the tool fetches relevant data based on the type of input (address, script, or transaction ID). It pulls information from an API and calculates the balance and status of relevant vTXOs, displaying them in a user-friendly format. The interface allows for easy exploration and interaction with the data.

## Installation

No installation is needed. Simply clone the repository and open the `index.html` file in your web browser.

## Contribution

Contributions are welcome, especially if you consider that this is a just-for-fun project, made with the help of LLMs. Please submit issues or pull requests through the GitHub repository.

## License

This project is open source and available under the MIT License.
