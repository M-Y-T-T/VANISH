<div align="center">

<br>

```
 __      __  _   _  _  ___ _  _ 
 \ \    / / /_\ | \| || |/ __| || |
  \ \  / / / _ \| .` || |\__ \ __ |
   \_\/_/ /_/ \_\_|\_||_||___/_||_|
```

### VANISHING UI

*the most simple black & white ui library for roblox*

<br>

![roblox](https://img.shields.io/badge/roblox-lua-000000?style=for-the-badge&logo=roblox&logoColor=white)
![size](https://img.shields.io/badge/one%20file-~9kb-000000?style=for-the-badge)
![style](https://img.shields.io/badge/theme-monochrome-000000?style=for-the-badge)
![license](https://img.shields.io/badge/use%20it-freely-000000?style=for-the-badge)

<br>

</div>

<br>

## ABOUT

I made this mostly as a fun way to try and learn how to create UI libs, so you may judge me on it. if you're trying to figure out how tabs, toggles, sliders or dropdowns are put together, it's all in this README file! :) Anyone can use it, fork it, rip parts out of it, whatever, it's completely open source, so do what you want with it.

<br>

## What's in it

<table>
<tr>
<td width="50%" valign="top">

**ELEMENTS**

- tabs
- labels
- buttons
- toggles
- sliders
- textboxes
- dropdowns

</td>
<td width="50%" valign="top">

**Window**

- draggable
- minimize / close
- right shift to hide
- open / close animation
- hover & click tweens on everything

</td>
</tr>
</table>

colors are strictly black, white and greys, there's nothing more to it, since it's made to be kept simple.

<br>

## How to use this

You have to paste the script into whatever you're using, The window will builds itself, then you add tabs and elements at the bottom of the script. You may use a loadstring

```lua
local Main = Tab("Main")

Main.Label("hello")

Main.Button("Click me", function()
    print("clicked")
end)

Main.Toggle("Toggle", false, function(state)
    print(state)
end)

Main.Slider("Slider", 0, 100, 50, function(value)
    print(value)
end)

Main.Textbox("Input", "type here", function(text)
    print(text)
end)

Main.Dropdown("Pick one", {"a", "b", "c"}, function(choice)
    print(choice)
end)
```
<br>

<div align="center">

</div>
