# CVE-2024-1561 PoC Script

This is a Proof of Concept (PoC) script for CVE-2024-1561.  

Check the full writeup for the CVE here: https://huntr.com/bounties/4acf584e-2fe8-490e-878d-2d9bf2698338

Affected Version: Gradio 4.12.0

This was fixed in this PR (https://github.com/gradio-app/gradio/pull/6884) and was released in version 4.13.0.

## Usage

1. Clone the repository and Navigate to the directory:

    ```bash
    git clone https://github.com/DiabloHTB/CVE-2024-1561
    cd CVE-2024-1561
    ```

2. Run the script with the following command:

    ```bash
    chmod +x CVE-2024-1561
    ./CVE-2024-1561 -u <URL> -f <FILE>
    ```

    Replace `<URL>` with the target URL and `<FILE>` with the file to be processed.

    Example:

    ```bash
    ./CVE-2024-1561 -u http://127.0.0.1:7860 -f /etc/passwd
    ```


## Options

- `-u, --url`: Specify the URL of the target.
- `-f, --file`: Specify the file.
- `-h, --help`: Help.

## Requirements

- Bash
- curl
- jq (for JSON parsing)

## Disclaimer

This script is a Proof of Concept (PoC) and should be used for educational and testing purposes only. Use it responsibly and at your own risk.


