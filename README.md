# Instructions

1. Export your [inxi](https://github.com/smxi/inxi/tree/master) / [pinxi](https://github.com/smxi/inxi/tree/inxi-perl) output to a json file:
    ```bash
    inxi -zv8 --output json --output-file /home/user/inxi.json
    ```
2. Move the json file to the root of this repository
3. Upload both files (.html & .json) somewhere (they need to be on a web server)
4. ???
5. Profit

# Setup

There is 1 variable in the JavaScript section that you might be interested in:
- `const jsonPath =` - The path to the json file

Aside from that, you're free to use this code in whatever fashion you see fit. It uses `AlpineJS` (a super simple and lightweight tool) and BulmaCSS.

# Example

![example](https://user-images.githubusercontent.com/1591486/198081556-128ad12d-f636-4f8b-a48d-adb015584dc5.png)

# Credits

- Me <3 ([Phr33d0m](https://github.com/Phr33d0m/inxi-html))
- [sandikata](https://github.com/sandikata) for providing the example .json
