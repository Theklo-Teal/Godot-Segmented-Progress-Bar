# Godot-Segmented-Progress-Bar

For Paracortical Initiative, 2025, Diogo "Saliko" Duarte

Other projects:
- [Bluesky for news on any progress I've done](https://bsky.app/profile/diogo-duarte.bsky.social)
- [Itchi.io for my most stable playable projects](https://diogo-duarte.itch.io/)
- [The Github for source codes and portfolio](https://github.com/Theklo-Teal)
- [Ko-fi is where I'll accept donations](https://ko-fi.com/paracortical)



## Description
A progress bar that only deals with integers and displays a StyleBox for each segment.
This is a tool script with class_name of SegmentedProgressBar

## Usage
This is not a Godot Plugin, so don't put it in the addons folder. I recommend placing the ".gd" script in a "modules" folder in your project.
After installation there's not much to say. It's a simple UI widget. You press "Add Child Node..." and select "SegmentedProgressBar".

## Features
There are options for a background, foreground, then the style of empty and filled segments.
This progress bar can be horizontal or vertical, go from right to left, left to right, top to bottom or bottom to top.
Theres's a `value_changed` signal and a `set_value_no_signal()` function, which I'm not sure it's properly implemented.
