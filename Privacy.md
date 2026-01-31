# Privacy Policy for Bedrock Phone

**Last Updated:** January 21, 2026

**Bedrock Phone** ("the App") is designed with privacy as its core principle. This Privacy Policy explains how your data is handled.

## 1. No Data Collection by the Developer

The developer of Bedrock Phone **does not collect, store, share, or sell any of your personal data**. 
- We have no servers.
- We have no analytics trackers.
- We cannot access your chat history.
- We cannot see your AWS credentials.

## 2. Your Data Stays on Your Device

*   **Chat History**: All conversations are stored locally on your device.
*   **AWS Credentials**: Your Access Key ID and Secret Access Key are stored securely in the **iOS Keychain**, which is encrypted and isolated from other apps.

## 3. Interaction with AWS Bedrock

The App acts as a direct client to **Amazon Web Services (AWS)**. When you send
a message:
1.  Your text/media is sent directly from your device to the AWS Bedrock API endpoint.
2.  Amazon processes this request according to their 
- [AWS Data Privacy FAQ](https://aws.amazon.com/compliance/data-privacy-faq/)
- [AWS Bedrock](https://aws.amazon.com/bedrock/security-compliance/)
3.  **Important**: AWS generally states that they do not use customer data sent to Bedrock to train their base models. However, you should review your own AWS agreement for specifics.

## 4. Voice Data

If you use the voice dictation feature, Bedrock Phone uses Apple's **SFSpeechRecognizer**. Audio data may be sent to Apple for processing to convert speech to text, governed by Apple's Privacy Policy. You can disable this permission in iOS Settings at any time.

## 5. Contact

If you have questions about this policy, please contact the developer.

