# Privacy Policy for Bedrock Phone

**Last Updated:** February 9, 2026

**Bedrock Phone** ("the App") is designed with privacy as its core principle. This Privacy Policy explains how your data is handled, specifically regarding interactions with third-party AI services.

## 1. Data Collection and Usage

While the developer of Bedrock Phone does not maintain private servers to store your data, the App **does collect and transmit** user-generated content to a third-party service provider to function.

### 1.1 Third-Party AI Service (AWS Bedrock)

To provide AI-generated responses, the App transmits the following data to **Amazon Web Services (AWS)**, specifically the **AWS Bedrock** service:

*   **Text Prompts**: The messages you type.
*   **Media**: Images (and potential future file attachments) you add to your messages.

This transmission occurs directly from your device to AWS API endpoints (e.g., `bedrock-runtime.us-east-1.amazonaws.com`).

## 2. Data Sharing & Third-Party Disclosure

In compliance with App Store Guidelines 5.1.1 and 5.1.2:

*   **Who receives the data?**: Amazon Web Services, Inc. (AWS).
*   **What data?**: Text prompts and image attachments.
*   **Purpose**: To process your input and generate an AI response.
*   **Protection**: Your AWS Credentials (Access Keys) are crucial for this interaction. They are stored securely on your device's **iOS Keychain** and are only used to sign requests to AWS.

### 2.1 Data Retention (AWS)

Data processed by AWS Bedrock is governed by the 
- [AWS Service Terms](https://aws.amazon.com/service-terms/)
- [Data Privacy Policies](https://aws.amazon.com/compliance/data-privacy-faq/).
- [AWS Bedrock](https://aws.amazon.com/bedrock/security-compliance/)

*   **Training**: According to AWS, they generally do not use content processed by Bedrock to improve their base models, but you should verify this against your specific AWS account settings and agreement.

## 3. User Consent and Revocation

*   **Consent**: Before using the AI features, you are presented with a disclosure screen where you must explicitly agree to this data transmission.
*   **Revocation**: You may withdraw your consent at any time within the App's **Settings**. Revoking consent will disable AI features until you agree again.
*   **Voice Data**: If you use voice features, audio is processed by Apple's on-device Speech Recognition or sent to Apple servers depending on your device settings, governed by [Apple’s Privacy Policy](https://www.apple.com/legal/privacy/).

## 4. Contact

If you have questions about this policy or data handling, please contact the developer.
