# Instructions

1. Export your inxi/pinxi output to a json file:
    ```bash
    pinxi -zv8 --output json --output-file /home/user/pinxi.json
    ```
2. Move the json file to the root of this repository
3. Open the HTML in your browser or upload both files (.html & .json) somewhere
4. ???
5. Profit

# Setup

There are 2 variables in the JavaScript section that you might be interested in:
- `const jsonPath =` - The path to the json file
- `const highlight =` - Bulma CSS class to highlight the data items

# Credits

Me <3