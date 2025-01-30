graph TD
  A[Victim receives email from support@milanote.com] -->|Email contains a PDF invoice| B[Victim opens the PDF]
  B -->|PDF contains a link to a fake Milanote page| C[Victim clicks the link]
  C -->|Victim is taken to the fake Milanote page| D[Malicious Milanote page is displayed]
  D -->|Page contains link to actual phishing site| E[Victim clicks phishing link]
  E -->|Redirected to credential-stealing site| F[Phishing page requests login credentials]
  F -->|Victim enters credentials| G[Credentials stolen]
  G -->|Attacker uses credentials for fraud| H[Account compromise, identity theft, financial fraud]
