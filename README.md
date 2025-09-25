# Phishing-Email-Analysis-Assignment-2-
Internship Task 2 – Phishing Email Analysis.  This repository contains a sample phishing email and a detailed report highlighting phishing indicators, suspicious traits, and key takeaways for email threat analysis.
Task 2 – Analyze a Phishing Email Sample

 Objective

The goal of this task is to identify phishing characteristics in a suspicious email sample. By analyzing sender information, headers, links, and language used, we can learn to recognize common phishing tactics.

Sample Phishing Email (fake example)
From: PayPal Support <support@paypa1.com>
To: user@example.com
Subject: Urgent: Verify Your Account Immediately

Dear Customer,

We detected unusual login attempts on your PayPal account.  
To avoid suspension, please verify your account immediately.  

Click here to confirm your identity: http://secure-paypal-login.verify-now.com

Failure to act within 24 hours will result in account termination.  

Thank you,  
PayPal Security Team


Phishing Indicators Found
	1.	Suspicious Sender Address
	•	support@paypa1.com → looks like PayPal but uses number “1” instead of letter “l”.
	2.	Mismatched URLs
	•	Displayed as a PayPal link but actually goes to:
http://secure-paypal-login.verify-now.com (not an official PayPal domain).
	3.	Urgent / Threatening Language
	•	Words like “immediately”, “within 24 hours”, “account termination” are meant to scare the user.
	4.	Header Discrepancies
	•	A header analyzer would show that the email didn’t originate from PayPal’s real mail servers.
	5.	Generic Greeting
	•	“Dear Customer” instead of the recipient’s actual name.
	6.	Tricks in Text / Domain
	•	Example: paypa1.com (number “1” instead of “l”).
  
Report Summary

This phishing email attempts to:
	•	Spoof the sender’s domain to look legitimate.
	•	Embed malicious links disguised as PayPal login pages.
	•	Pressure the recipient with urgent and threatening language.
	•	Bypass user suspicion by using generic greetings.

Conclusion

This is a phishing attempt designed to steal PayPal credentials.
Users should:
	•	Avoid clicking suspicious links.
	•	Report the email.
	•	Delete it immediately.
