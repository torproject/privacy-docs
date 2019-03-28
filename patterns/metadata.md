# Strip Invisible Metadata #

Categories:
 - metadata
 - minimization
 - exif
 - location
 - media
 - minimize
 - strip

*Strip potentially sensitive metadata*

Metadata are a way to describe data. The prefix *meta* come from ancient Greek and it is translated into English as *about*. So technically metadata are data about data. Metadata serve a purpose, and this purpose defines its form and representation. Metadata can be used to describe some information, to define how this information can be accessed, edited, stored, or to define the structure of this same information (ex: the structure of a book and its chapters and pages).

Metadata are often invisible to users, yet these are automatically attached to their activity. Metadata that services generates include the user's social graph, information about their devices, networks, location data. Metadata can be attached to users generated documents (ex: exif information attached to images)

## Threat model ##

- An attacker wants to access the list of ip addresses that have accessed a certain resource
- An attacker wants to know which devices belong to a user
- An attacker wants to track the user's locations
- An attacker wants to track when a particular user is accessing a service

## User story ##

## Use case ##

## Secondary effects ##

Avoid leaking of personal information. Protect sensible users and vulnerable group by don't storing potentially user identifying data.
