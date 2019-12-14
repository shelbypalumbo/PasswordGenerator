# PasswordGenerator
<h2>Description</h2>
This repository contains the files for a random password generator.  
A Bootstrap layout, along with additional external styling was used to style the password generator.
Javascript was used for creating interactive buttons to perform the random password function.

<h2>Usage</h2>
When the "Generate Secure Password" button is clicked, users will be prompted to choose the length of their randomly generated password; betweem 8 and 128 total characters.
<img src="images/interface.png" alt="password generator interface">
After the user submits the length of the password, confirmation boxes will apear that will ask for the specific characterists of the password being generated. <br>
Users will have a choice of:
  <ul><li>Special Characters</li>
      <li>Numbers</li>
      <li>Uppercase Letters</li>
      <li>Lowercase Letters</li></ul>
<img src="images/prompt.png" alt="prompt">
The chosen combinations will trigger the if statement with those parameters, which will then use those parameters when calling the generateFun function.
<img src="images/if_state.png" alt="ifcode"> <br>
After the generateFun function runs, the generated password  will be returned and printed to the text box on screen.
<img src="images/result.png" alt="result">
The "Copy to Clipboard" button allows you to copy the generated password and and alert will appear showing users that the password has been saved!
<img src="images/clipboard.png" alt="clipboard_alert">