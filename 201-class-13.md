# Code 201: Class 13 - Local Storage

***

## Read: The Past, Present, and Future of Local Storage for Web Applications

Cookies

- Can be used to store up to 4 KB of data
- Slow down page load 
- Uploaded without encryption

HTML5 sought to offer a standardized storage API implemented natively across all browsers without the need for 3rd party plugins

- Known as *Web Storage* 

To check for HTML5 storage:

```js

function supports_html5_storage(){
  try{
    return 'localStorage' in window && window ['localStorage'] !== null;
  } catch (e) {
    return false;
  }
}

```

JavaScript commands

- `setItem()` will write or overwrite previous value
- `getItem()` will return the stored value or null if empty

Storage Limits

- Each origin is alloted 5 megabytes
- all variables are stored as strings
- `Quota_Exceeded_Err` Error announcing that storage limit has been hit

The future of local persistent storage may be IndextedDB, but at the time the article was written it had not been implemented yet.


***

[Return to reading-notes Deployed Site](https://paneks19.github.io/reading-notes/)

[Return to reading-notes Mark Down](https://github.com/paneks19/reading-notes)
