## Description
Use of the extremely popular JavaScript framework AngularJS is exposing numerous websites to Angular Template Injection. This relatively low profile sibling of server-side template injection can be combined with an Angular sandbox escape to launch cross-site scripting (XSS) attacks on otherwise secure sites.

## Impact
An attacker is able to execute JavaScript in a user's browser under the security context of this domain. They may be able to access data from the user's account via this JavaScript execution, redirect the user to a malicious domain, trigger a drive-by download, or bypass CSRF mitigations.

## Steps to Reproduce
[insert steps here]

## References
- https://portswigger.net/research/xss-without-html-client-side-template-injection-with-angularjs
