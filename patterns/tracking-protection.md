# Protection against tracking #

Categories:
 - Cookies
 - JavaScript
 - Unlinkability
 - Fingerprinting

*Avoid the tracking of visitors of websites.*

Websites collect an incredible amount of information about their visitors via attributes of the browser. This information is shared with third parties and saved in logs. This information can also be involuntarily leaked when accessed by malicious actors or used by advertising and tracking network across the web to reduce the anonymity set or identify individual users.

Individual users are tracked via a technique known as *fingerprinting*. Fingerprinting means accessing device features and behaviors in order to differentiate one user from another. In this case the attacker uses any information that is provided automatically by the browser or implements mechanism involving some specific browser interactions, using JavaScript or cookie-like identifier storage, just to name a few example.

There are also some more advanced fingerprinting techniques trying to capture users' behaviors.

## Threat model ##

- An attacker wants to access user configuration details (i.e. language settings)
- An attacker wants to access information about device and hardware characteristics
- An attacker wants to access information about the operating system and version
- An attacker wants to profile user behaviors by recording their in-site or across-site (network) activity

## User story ##

## Use case ##

## Secondary effects ##

websites load faster

reduce memory leaks

reduce battery consumption
