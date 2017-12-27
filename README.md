# DiscordColorPicker
Allows you to change your Discord Look and Feel to any color you want!

# How to Install
First, Open Discord and press ``Ctrl+Shift+I``

Next, Open the Console tab in the Developer Tools Menu

Finally, Paste the following code into the Console
```javascript
function addScript(src) {
  var script = document.createElement("script");
  script.setAttribute("src",src);
  document.head.appendChild(script);
  return script;
}

addScript("https://cdn.rawgit.com/NegativeThree/DiscordColorPicker/master/DiscordColorPicker.js");
```
