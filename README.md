# OurWebsite stuff downloads
ourWebsite stuff downloads

## Installation
1. press on code and click "download zip"
2. extract files
3. go to the ourWebsite stuff downloads zip and extract it
4. go to the public folder and click on the version of OurGame you want to run
<br>

> *also if you see any bugs create an issue except for the file not found one*

## updates and other stuff

the following OurGame versions might be added at some point:
- 1.5.2
- Beta 1.3
- 1.8.8 (multiplayer version)

## developer guide
#### table of contents
1. [changing password]()
1. changing password
- ok so basically to change the password you have to go to one of the encrypted files and then somewhere in the code it should have this code:
  ```javascript
        function blankScreen() {
        document.body.style.display = "none";
      }

      function restoreScreen() {
        document.body.style.display = "block";
      }
      window.addEventListener("load", function () {
        blankScreen();
        const cPwd = "test123"; // dG8gcmVwbGFjZSB0aGUgcGFzc3dvcmQgcmVwbGFjZSB0aGUgdGVzdDEyMyB0ZXh0IHdpdGggdGhlIHBhc3N3b3JkIHUgd2FudA==
        const tdpPwd = prompt("enter password:");
        if (tdpPwd == cPwd) {
          restoreScreen();
        } else {
          window.location.href = "404.html";
        }
      });
  ```
- basically on this line of code the `cPwd` variable is the password so to change the password just replace test123 with the password u want
```javascript
const cPwd = "test123"; // dG8gcmVwbGFjZSB0aGUgcGFzc3dvcmQgcmVwbGFjZSB0aGUgdGVzdDEyMyB0ZXh0IHdpdGggdGhlIHBhc3N3b3JkIHUgd2FudA==
 ```
