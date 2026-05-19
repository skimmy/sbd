# What is cybersecurity

The common meaning that is assigned to the world security has to do with how people feel about themselves and their belongings. We can broadly interpret security in terms of
- no *harm* on a person,
- no *theft* or *damage* to person's belongings,
- no *spying* on a person.

These are just some of the way in which we interpret our personal security, but they cover most of the cases (something not directly included is *no identity theft*, unless we see identity as a belonging).

We can also get one step further and replace in the above list person with organization
- no *harm* on an organization,
- no *theft* or *damage* to organization's belongings,
- no *spying* on an organization.

These general ideas of security turn out to work also in cybersecurity, they have been famously encoded in what is now known as the **CIA Triad**

## CIA Triad

To talk about cybersecurity, we need to identify which *goals* we are aiming at. A well established framework to set these goals is known as the **CIA Triad** which, as the name suggests, comprises three goals: **C**onfidentiality, **I**ntegrity, **A**vailability.

### Confidentiality
We don't want people to spy on us when we are having a shower or when we are writing our PIN at the ATM. We care about our *confidentiality* and we implement measures to assure it (use curtains, cover the keypad). We expect the same care from any system managing our data, which we don't want to be accessed by unauthorized actors.

Confidentiality
: The ability of a system to prevent unauthorized actors to access data or to discover resources that are meant to be hidden.

Confidentiality provides an opportunity to show the *security by design* principle in action. The filesystem is used by operating systems to organize data (files) in your drive. For historically and efficiency reasons, data is stored in *plaintext*, without any obfuscation. Thus, a malicious actor gaining access to the drive sees your data. Thats *show to all by default* policy is the opposite of *show to none by default*, which is a *security by design* principle.




