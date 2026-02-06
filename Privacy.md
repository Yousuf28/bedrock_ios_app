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

*   **Chat History**: All conversations are stored locally on your device in the App's Documents directory.
*   **AWS Credentials**: Your Access Key ID and Secret Access Key are stored securely in the **iOS Keychain**, which is encrypted and isolated from other apps.

## 3. Interaction with Third-Party AI Service (AWS Bedrock)

To provide AI-generated responses, the App transmits the following data to a third-party service provider, **Amazon Web Services (AWS)**, specifically the **AWS Bedrock** service:

*   **Text Prompts**: The messages you type.
*   **Media**: Images or documents you attach to your messages.

### 3.1 Data Sharing & Processing
When you send a message:
1.  Your data is sent securely (over SSL/TLS) directly from your device to AWS Bedrock API endpoints (e.g., `bedrock-runtime.us-east-1.amazonaws.com`).
2.  **Consent**: You must explicitly consent to this data sharing within the App before using these features.
3.  **Processing**: AWS processes this data to generate the text response.
4.  **Retention & Training**: According to the [AWS Data Privacy FAQ](https://aws.amazon.com/compliance/data-privacy-faq/) and [AWS Bedrock](https://aws.amazon.com/bedrock/security-compliance/), AWS generally does not use content processed by Bedrock to train their base models. However, this is governed by AWS's terms and privacy policies.

By using the App, you agree to this data transmission to AWS.

## 4. Voice Data (Apple)

If you use the voice dictation feature, the App uses Apple's **SFSpeechRecognizer**. Audio data is sent to Apple for processing to convert speech to text. This is governed by [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/). You can disable this permission in your iOS Settings at any time.

## 5. Contact

If you have questions about this policy, please contact the developer.
