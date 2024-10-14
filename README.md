## 💣 VBScript DDoS Tool 💻

This VBScript-based DDoS tool allows users to launch Distributed Denial of Service (DDoS) attacks for network stress testing purposes. It includes customizable features such as request method (GET or POST), number of requests, custom headers, and advanced modes like **Turbo Mode** and **Fear Mode** for more intense attacks. The tool can also send log messages to a **Discord webhook** for monitoring the attack status.


## ⚠️ Disclaimer

This tool is strictly for educational purposes and legal testing only. Misuse of this tool against unauthorized systems is illegal and could result in severe legal consequences. Use responsibly and only with explicit permission.

## 🔥 Features:

• **Customizable attack parameters**: Modify URL, request count, delay, and headers.

• **Turbo Mode**: Increase the attack speed by sending requests with no delay.

• **Fear Mode**: Send up to 1000 requests per second for intense testing.

• **Request methods**: Supports both GET and POST methods, including sending POST data.

• **Discord logging**: Errors and attack progress are logged to a Discord webhook in real time.

• **Detailed error handling**: Logs any request errors to both Discord and the local log file.

## 🛠️ Installation:

1. Go to the Releases tab of this repository.
2. Download the latest release of the tool (DDoS.vbs).
3. Run the VBScript

   • Simply double-click DDoS.vbs, or
   
   • Execute it from the command line:

   
```bash
cscript DDoS.vbs
```

## 🚀 Usage:

1. **Enter target details**:

• Specify the target URL (default: http://example.com).

• Enter a Discord webhook URL to receive real-time logs.

• Select the HTTP request method (GET or POST).

• Input the number of requests, delay between them, and timeout.

• Optionally enter custom headers and POST data.

 2. **Turbo Mode & Fear Mode**:

• Turbo Mode: Triples the number of requests and removes delay.

• Fear Mode: Sends 1000 requests per second for heavy network stress tests.

3. **Logs**:

• Logs are saved to a text file in the user's Downloads folder and also sent to the Discord webhook.

## 🛑 Legal Notice:

This tool should only be used for **authorized network stress tests**. Unauthorized use is illegal and may lead to serious consequences. Make sure you have proper permission before running the tool.

## 📂 File Structure:

DDoS.vbs: The main VBScript file to launch the DDoS attack.
