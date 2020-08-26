## Overview
Account lockout mechanisms are used to mitigate brute force password guessing attacks. Accounts are typically locked after 3 to 5 unsuccessful login attempts and can only be unlocked after a predetermined period of time, via a self-service unlock mechanism, or intervention by an administrator. Account lockout mechanisms require a balance between protecting accounts from unauthorized access and protecting users from being denied authorized access.

## Testing
[steps]

## Conclusion
Apply account unlock mechanisms depending on the risk level. In order from lowest to highest assurance:

- Time-based lockout and unlock.
- Self-service unlock (sends unlock email to registered email address).
- Manual administrator unlock.
- Manual administrator unlock with positive user identification.

## Reference
- https://kennel209.gitbooks.io/owasp-testing-guide-v4/en/web_application_security_testing/testing_for_weak_lock_out_mechanism_otg-authn-003.html

- https://github.com/synack/wstg/blob/master/document/4-Web_Application_Security_Testing/04-Authentication_Testing/07-Testing_for_Weak_Password_Policy.md
