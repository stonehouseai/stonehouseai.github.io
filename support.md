# Interview Proctor - Support Documentation

This document provides the information about the Interview Proctor for users and for the Google Workspace Marketplace review process.

## 1. Overview of the Application

**Application Name:** Interview Proctor

**Primary Function:** Interview Proctor is a tool designed to enhance remote technical and skills-based interviews conducted via Google Meet. It provides Interviewers with a way to observe a Candidate's screen and system environment in real-time to better assess their skills and problem-solving abilities.

**Key Features:**

* **Interviewer Mode:** Allows the interviewer to view a real-time stream of the candidate's screen activity and system information within the Google Meet interface.
* **Candidate Mode:** Guides the candidate through a simple, one-time installation of a temporary Insterview Proctor Agent required for the screen sharing functionality.
* **Interview Proctor Agent:** One Systray app to monitor candidate's activities and report that to the interviewer.
* **Secure Data Transmission:** All data collected during the interview is transmitted directly from the Candidate to the Interviewer via a secure backend server.

## 2. Installation and Usage Guide

This guide provides step-by-step instructions for all users.

### Step 1: Initial Setup (For All Users)

1.  **Install from Marketplace:** Find "Interview Proctor" in the Google Workspace Marketplace and click **Install**.
2.  **Open in Google Meet:** Start or join a Google Meet call. Click the "Activities" icon (typically looks like a puzzle piece) in the call controls and select "Interview Proctor" to open the add-on in the side panel.
3.  **Sign In:** The add-on will require you to sign in. Currently, we only support Google Sign-In.
4.  **Select Your Role:** After signing in, you must select your role for the current session: **"I'm Interviewer"** or **"I'm Candidate"**.

### Step 2: Using Interviewer Mode

1.  After selecting the "I'm Interviewer" role, your setup is complete. No further software installation is required.
2.  Instruct the Candidate to complete the setup steps for "Candidate Mode".
3.  Once the Candidate has launched their Systray App and is connected, a **"Collect Data"** button will become active in your panel. Click this button to begin viewing their screen information.

### Step 3: Using Candidate Mode

#### A. Download and Install the Interview Proctor Agent

1.  After selecting the "I'm Candidate" role, the side panel will direct you to a download page.
2.  Download the correct installation package for your operating system.

**For macOS:** (To be updated after codesign the package)

* Our macOS application is not yet code-signed by Apple. Currently, please follow [this](https://developer.apple.com/documentation/security/disabling-and-enabling-system-integrity-protection) to disable System Integrity Protection (SIP) for a workaround.

Then, double click to install this macOS package: `InterviewProctor-Universal.pkg`.

* **Permissions:** During or after installation, your Mac will prompt you to grant necessary permissions (e.g., **Screen Recording**, **Accessibility**). These are **required** for the app to function. You can manage these permissions in `System Settings > Privacy & Security`.

**For Windows:**

* After downloading the file `InterviewProctor-amd64-setup.exe`, double-click it to run the installer and follow the on-screen prompts.

#### B. Launch the Interview Proctor Agent

1.  Once the installation is complete, return to the Google Meet add-on panel.
2.  Click the **"Launch the Interview Proctor Agent"** button. This will automatically launch the application on your computer and sign you in using the Google account you used for the add-on.
3.  The Interviewer will now be able to start the data collection.

### Step 4: Ending the Session

* **For Interviewers:** Simply close the add-on panel or end the Google Meet call.
* **For Candidates:** To stop sharing, you can close the Google Meet Add-on panel. This will automatically close the Systray application on your computer within 1 minute if the interviewer also close it.

## 3. Privacy and Data Handling

This section summarizes our key data handling practices. A comprehensive Privacy Policy is available to all users.

### What information does Interview Proctor collect?

The application collects specific, limited data from the **Candidate's** computer **only** during an active interview session and **only** with the Candidate's explicit consent upon starting the app. The collected data includes:

* **Screenshots:** Images of the Candidate's screen.
* **Running Processes:** A list of active software applications.
* **User Information:** The local operating system username.
* **Hardware Information:** Basic system details like OS type, Display, whether running on VM, etc.

This data is collectively referred to as "Candidate Data." **The add-on does not collect any data from the Interviewer's computer**, other than standard log and usage data necessary for the app's operation.

### How is this information used?

* **Primary Use:** Candidate Data is used **exclusively** for the purpose of allowing the Interviewer to evaluate the Candidate's skills and engagement during the interview.
* **No Other Uses:** We do not sell, analyze for advertising, or use Candidate Data for any purpose other than facilitating the interview.

### Data Sharing and Disclosure

* **Between Users:** The core function of the app is to share Candidate Data with the designated Interviewer for that specific interview session. This is the only party the specific Candidate Data is shared with.
* **Third Parties:** We do not share personally identifiable information with third parties, except with essential service providers (e.g., backend hosting) who are under strict confidentiality agreements and are authorized to use the information only to provide services to us.
* **Aggregated Data:** We may use aggregated, anonymized usage data to improve our service. This data cannot be used to identify any individual.

### Data Retention and Deletion

* **Real-Time Focus:** Candidate Data is intended for real-time viewing and facilitating the hiring decision.
* **Our Policy:** We do not store Candidate Data on our servers beyond 180 days after the interview session. All session-specific Candidate Data is deleted from our servers within **180 days** of the interview's conclusion to protect Candidate privacy.

### Security Measures

We implement commercially reasonable security measures to protect data, including encryption during transmission (e.g., HTTPS).

## 4. User Support

If you encounter any issues or have questions about Interview Proctor, please contact our support team.

* **Email Support:** For all inquiries, please email us at **support@stonehouseai.com**.
* **Issues:** You can also file a issue on: [https://github.com/stonehouseai/interview-proctor/issues](https://github.com/stonehouseai/interview-proctor/issues).
* **Expected Response Time:** We aim to respond to all support requests within 48 business hours.
* **Troubleshooting:** Before contacting support, please ensure you are using a supported web browser (latest version of Chrome, Firefox, or Edge) and that you have granted the necessary permissions when prompted by Google Meet and your operating system.

---
**This document is intended to provide a clear and transparent overview of the Interview Proctor application for all users and for compliance purposes.**
