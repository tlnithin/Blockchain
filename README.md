Please install Metamask google chrome extension.

Follow the below steps to test the blockchain

  1.  Open PowerShell in Administrator Mode
  2.  Type "cd %Path Of FoodSafeContract" , E.g. "cd ..\FoodSafe\FoodSafeContract" 
  3.  Type "truffle compile" 
  4.  Type "truffle development"
  5.  Type "migrate"
  6.  Type "node server.js"
  7.  Now open a browser and Type, "http://localhost:3000" ,If everything goes good,This should open something like below,
      {"contracts":{":FoodSafe":{"assembly":{".code":[{"begin":34,"end":1136,"name":"PUSH","value":"80"},
      {"begin":34,"end":1136,"name":"PUSH","value":"40"},{"begin":34,"end":1136,"name":"MSTORE"},
      {"begin":281,"end":282,"name":"PUSH","value":"0"},{"begin":264,"end":282,"name":"PUSH","value":"1"},
      {"begin":264,"end":282,"name":"PUSH","value":"0"},{"begin":264,"end":282,"name":"PUSH","value":"100"},
      {"begin":264,"end":282,"name":"EXP"},{"begin":264,"end":282,"name":"DUP2"},{"begin":264,"end":282,"name":"SLOAD"},
      {"begin":264,"end":282,"name":"DUP2"},{"begin":264,"end":282,"name":"PUSH","value":"FF"},{"begin":264,"end":282,"name":"MUL"},
      {"begin":264,"end":282,"name":"NOT"},{"begin":264,"end":282,"name":"AND"},{"begin":264,"end":282,"name":"SWAP1"},
      {"begin":264,"end":282,"name":"DUP4"},{"begin":264,"end":282,"name":"PUSH","value":"FF"},{"begin":264,"end":282,"name":"AND"}, ... 
  8.  Now Open another PowerShell terminal.
  9.  Type "cd %Path Of FoodSafeClient" , E.g. "cd ..\FoodSafe\FoodSafeClient"
  10. Type npm run start
  11. This will open a browser.
  12. Click on the Metamask extension and sign in using your blockchain Network.
  13. It will prompt to Give access to this site.
  14. Click on "Create New Contract", Metamask popup will open, click on Confirm.
  15. Contract Address will be Auto-populated.
  16. Enter LocationId, LocationName, Secret, Passphrase and click on "Add New Location".
  17. To know the current location, enter the Contract Address and click on "Get the current Location" .
