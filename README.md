# FUTURE_CS_02 - Phishing Email Detection & Awareness System

## Future Interns Cyber Security Internship

### Task 2: Phishing Email Detection & Awareness System

**Name:** Satyakiran Mynam  
**Internship:** Future Interns - Cyber Security  
**Task:** FUTURE_CS_02

## Objective

The objective of this task is to identify phishing indicators in suspicious emails, classify emails as Safe, Suspicious, or Phishing, and provide security awareness and prevention guidelines.

## Tools Used

- Kali Linux
- Linux Terminal
- Python
- Email analysis techniques
- URL analysis
- `xfce4-screenshooter`
- Markdown/PDF documentation

## Methodology

The simulated phishing email was analyzed by examining:

1. Sender address
2. Sender domain
3. Subject line
4. Email content
5. URLs
6. Use of urgency
7. Account verification requests
8. HTTP/HTTPS usage

## Sample Analysis

The sample email impersonates Microsoft Account Security and asks the recipient to verify an account through a suspicious link.

### Classification

**PHISHING**

### Indicators Identified

- Sender impersonation
- Suspicious domain
- Typosquatting (`micros0ft`)
- Urgent account suspension message
- Suspicious verification link
- Unsolicited account verification request
- HTTP connection instead of HTTPS

## Evidence

Evidence screenshots are available in the `evidence/` directory.

## Prevention Guidelines

- Verify the sender's email address carefully.
- Do not click suspicious links.
- Check domains for spelling variations and typosquatting.
- Avoid responding to unexpected account verification requests.
- Access important accounts through their official website or application.
- Report suspected phishing emails to the appropriate security team.
- Enable multi-factor authentication where available.
- Provide regular phishing awareness training to users.

## Disclaimer

The email analyzed in this project is a simulated/test phishing sample created for cybersecurity education and internship documentation. It is not a real Microsoft communication and should not be used to target real users.

## Conclusion

The analysis demonstrates how common phishing indicators can be identified through sender, domain, content, URL, and social-engineering analysis. Recognizing these indicators can help users reduce the risk of credential theft and account compromise.
