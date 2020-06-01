** Context: **

Fraudulent e-mails contain criminally deceptive information, usually with the intent of convincing the recipient to give the sender a large amount of money. Perhaps the best known type of fraudulent e-mails is the Nigerian Letter or “419” Fraud.
Content:

This dataset is a collection of more than 2,500 "Nigerian" Fraud Letters, dating from 1998 to 2007.

These emails are in a single text file. Each e-mail has a header which includes the following information:

    Return-Path: address the email was sent from
    X-Sieve: the X-Sieve host (always cmu-sieve 2.0)
    Message-Id: a unique identifier for each message
    From: the message sender (sometimes blank)
    Reply-To: the email address to which replies will be sent
    To: the email address to which the e-mail was originally set (some are truncated for anonymity)
    Date: Date e-mail was sent
    Subject: Subject line of e-mail
    X-Mailer: The platform the e-mail was sent from
    MIME-Version: The Multipurpose Internet Mail Extension version
    Content-Type: type of content & character encoding
    Content-Transfer-Encoding: encoding in bits
    X-MIME-Autoconverted: the type of autoconversion done
    Status: r (read) and o (opened)

** Acknowledgements: **

If you use this collection of fraud email in your research, please include the following citation in any resulting papers:

```
    Radev, D. (2008), CLAIR collection of fraud email, ACL Data and Code Repository, ADCR2008T001, http://aclweb.org/aclwiki
```

Inspiration:

    This dataset contains fraudulent e-mails sent over a period of years. Has the language used in fraudulent E-mails changed over time?
    Are there any words or phrases that are particularly common in this type of e-mail? (You might compare it with the Enron email corpus, linked below)

Related datasets:

    https://www.kaggle.com/wcukierski/enron-email-dataset
    https://www.kaggle.com/uciml/sms-spam-collection-dataset
