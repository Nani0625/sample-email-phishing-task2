# sample-email-phishing-task2

Objective

To identify and analyze phishing characteristics in a suspicious email sample to understand how phishing attempts operate and how to detect them.

Tools Used

    Email client or plain text editor to open and read the saved email file (.eml format).

    Free online email header analyzer tool (e.g., Mailmodo Email Header Analyzer) for in-depth header examination.

Methodology

    Open and Inspect Email Content

        Examined the email body for suspicious language, urgent calls to action, and unexpected attachments or links.

    Extract and Analyze Email Headers

        Copied full email headers from the email client.

        Pasted header text into the email header analyzer to parse authentication checks and path tracing.

    Evaluate Authentication Results

        Focused on SPF, DKIM, DMARC, and ARC results as key indicators of sender legitimacy.

    Identify Phishing Indicators

        Correlated header anomalies and email content signs to conclude phishing traits.

Phishing Indicators Found

    Failed SPF, DKIM, DMARC, and ARC authentication checks indicating sender identity spoofing.

    Suspicious sender address and domain mismatch not belonging to the legitimate organization.

    Urgency in subject line and email body to trick recipients into quickly taking action.

    Encoded email body (base64 encoding) commonly used to obfuscate malicious content.

    Suspicious or non-official URLs embedded in the message encouraging credential theft or malware download.

    Mismatch between "From" and "Return-Path" addresses indicating spoofing.

    High spam confidence rating from email security filters.

Conclusion

This email sample contains multiple classic phishing characteristics and should be treated as malicious. The analysis highlights important techniques for recognizing phishing attempts based on header checks and message content.
Screenshots and Analysis Reports

Screenshots of the email header analyzer output and detailed analysis are included as part of the deliverables.
