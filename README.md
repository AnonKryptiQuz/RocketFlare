# RocketFlare: Cloudflare Rocket Loader Vulnerability Scanner

**RocketFlare** is a lightweight and powerful tool designed to scan websites for vulnerabilities in Cloudflare’s Rocket Loader implementation. This vulnerability involves insecure HTML injection, which can pose a significant security risk if not addressed. The tool checks for the presence of this issue, allowing for proactive mitigation.

## **Features**

- **Vulnerability Detection**: Identifies insecure Rocket Loader HTML injection vulnerabilities.
- **Single URL and Bulk Scanning**: Supports both single URL scans and bulk scans from a file.
- **Auto-Completion for File Paths**: Simplifies file path selection for efficient workflow.
- **Detailed Output**: Provides clear and color-coded feedback about vulnerable URLs.
- **Save Results**: Option to save vulnerable URLs to a file for future reference.

## **Prerequisites**

- **Bash Shell** (Linux, macOS, or WSL for Windows)
- **Curl** (for making HTTP requests)
- **Optional**: Text editor for editing URL files.

## **Installation**

1. **Clone the repository:**

   ```bash
   git clone https://github.com/AnonKryptiQuz/RocketFlare.git
   cd RocketFlare
   ```

2. **Give executable permission to the script:**

   ```bash
   chmod +x RocketFlare.sh
   ```

## **Usage**

1. **Run the tool:**

   After giving executable permission to the script, you can run the tool using one of the following commands:

   ```bash
   ./RocketFlare.sh
   ```

   or

   ```bash
   bash RocketFlare.sh
   ```

   The `./` method is preferred if the script has been made executable with `chmod +x`, while `bash` can be used if you prefer to run the script explicitly through the Bash shell.

2. **Follow the prompts** to configure and choose whether to scan a single URL or use a file containing URLs.

3. **After the scan**:
   - Vulnerable URLs will be displayed.
   - You will be prompted to save the results to a file.

## **Disclaimer**

- **Educational Purposes Only**: RocketFlare is intended for educational and research use only. The tool is not intended for malicious or unauthorized use. It is the user's responsibility to ensure compliance with all relevant local laws and regulations before using this tool.

## **Author**

**Created by:** [AnonKryptiQuz](https://AnonKryptiQuz.github.io/)