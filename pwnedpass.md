---
title: Pwned Pass
img_path: images/contact.jpg
menus:
  main:
    title: Pwned Pass
    weight: 6
layout: post
---

Using the data supplied by Troy Hunt and his Have I been pwned? website Pwned Pass allows you to check to see if any password has appeared in a data breach.

For more details about Have I been pwned? check out <a href="https://haveibeenpwned.com/">haveibeenpwned.com</a> and <a hre="http://www.troyhunt.com/">www.troyhunt.com</a>.

Pwned Pass is a simple Xamarin app that allows you to type in a password and tells you if it has been used in a data breach.

Troy Hunt of <a href="https://haveibeenpwned.com/">Have I Been Pwned?</a> recently added a new API to his website which allows you to search his extensive database of pwned passwords, 306 million of them. I have simply created a Android/UWP frontend to this API.

It should be noted: Do not send any password you actively use to a third-party service – even mine! I don’t log anything that you type into my app and this app makes use of the <a href="https://www.troyhunt.com/ive-just-launched-pwned-passwords-version-2/">k-anonymity</a> feature to avoid transmitting passwords.

As well as using Troy’s new API I also take advantage of his existing API’s. You can search his extensive database of email addresses to see if you have been affected by a data breach all from my android app.

Pwned Pass is now available from the <a href="https://play.google.com/store/apps/details?id=pwnedpasswords.pwnedpasswords">Google Play Store</a> and the <a href="https://www.microsoft.com/en-gb/p/pwned-pass/9nm2whnztnlt">Microsoft Store</a>.