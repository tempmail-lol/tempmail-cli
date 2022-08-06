# tempmail-cli

TempMail CLI program for Bash

## Depends
- `curl`
- `jq`
- `bash`
- (optional) `lynx`

## Installation

```bash
sudo curl -L https://github.com/tempmail-lol/tempmail-cli/releases/latest/download/tempmail -o /usr/local/bin/tempmail
sudo chmod a+rx /usr/local/bin/tempmail
```

Distro-specific packages coming soon<sub>ish</sub>

## Usage

Parameters:
- `--help`
  - Display the help menu.
- `--rush` or `-r`
  - Use Rush Mode (alternative TLD) emails.
- `--verbose` or `-v`
  - Enable verbose mode (good for debugging).
- `--lynx` or `-l`
  - Render emails sent in HTML using Lynx.

Press `q` to quit.  CTRL + C will not quit.
