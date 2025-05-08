# branchify

A simple CLI tool that creates git branches with standardized naming conventions.

## Installation

```bash
# Clone the repository
git clone https://github.com/mkbaker/branchify.git

# Make the script executable
chmod +x branchify/branchify

# Create a symbolic link to a directory in your PATH
ln -s "$(pwd)/branchify/branchify" ~/bin/branchify
```

## Usage
```
branchify -t TICKET-123 -d "Feature description goes here"
```