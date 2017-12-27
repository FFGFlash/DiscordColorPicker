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
To know that it worked your Discord should turn black

# How to Use
A few functions
```javascript
// By default it is on.
turnOnColorPicker();

// Use to turn of Color Picker, this means that you can't change the color.
turnOffColorPicker();

// Turns on color transitioning, will by default cycle from black to white.
turnOnColorRainbow();

// Turns off color transitioning
turnOffColorRainbow();

// Used to set the color
rgb(red, green, blue);

// Used to set the color offset, used by the Color Rainbow module.
hex(red, green, blue);
```

If you'd like an easy way to get colors and easily set them,

then goto https://www.w3schools.com/colors/colors_picker.asp and pick any color you like.

Once you pick the color, copy the value formatted ``rgb(#, #, #)`` and paste it into the Console.

# Examples
![example_green_discord.png](/examples/green_discord.png?raw=true "")
