For all of the following examples, the following is considered defined
`Voice v = new Voice("email@domain.com","password");`

Initiating a phone call
```
v.Call("+10001115555","user@gmail.com");// call from gtalk
v.Call("+10001115555","+10003334444");// call from phone
```

Sending an SMS
```
v.SendSMS("15551235555","test message, please ignore");
```

Write SMS to console
```
foreach(SharpVoice.Message msg in v.SMS.Messages){
  Console.WriteLine("[" + msg.type + "] " +msg.displayNumber + ": " + msg.Text);
}
```