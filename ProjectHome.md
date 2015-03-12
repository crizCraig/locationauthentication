One of the standout attributes of Android applications will be the ability to use and share location.

To alleviate privacy concerns with sharing sensitive location information, a location authentication scheme should be developed that allows users to securely share their location with others as well as securely request the location of others.

The two main components of such a system would be:

> - A public key infrastructure with a certificate authority (C.A.) that links phone numbers and other identification information to public keys.

> - An Android application that communicates with the C.A. to validate others' public keys, handle the communication of location with others, and maintain its own public key.

I'm including a more detailed spec of how I think the communication should work in the Wiki portion of this project. If you're interested, look it over and make edits/suggestions. I want to hash out the conceptual side as much as possible before starting a project of this scale.

One of my main concerns is hiding the private key. Any help in this particular area would be greatly appreciated, as would  help of all kinds ;)

Thanks!
