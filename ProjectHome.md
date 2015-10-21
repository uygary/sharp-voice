I've ported the [java](http://code.google.com/p/google-voice-java/) library, which is similar to a [python](http://code.google.com/p/pygooglevoice/) library, to C Sharp.

This library (as of August 26th, 2013) is capable of:
  * Initiating calls
  * Sending SMS
  * Retrieving messages
  * Downloading voicemail
  * Login with two-step authentication
  * Saving cookies (login persistence)

## Requires Microsoft .Net Framework 3.5 || Mono (I tested on 2.10.8.1) ##

I recommend downloading the library from [here](https://code.google.com/p/sharp-voice/source/browse/#git%2FSharpVoice%2Fbin%2FDebug)

For linux/mono you may need to execute "[mozroots --import --ask-remove](http://stackoverflow.com/questions/10781279/c-sharp-the-authentication-or-decryption-has-failed-error-while-using-twitt)"