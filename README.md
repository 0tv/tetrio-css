# TETR.IO CSS Collection

This is a repository for me to store my CSS files for use with TETR.IO

> [!IMPORTANT]
> You will need a method of loading the CSS files such as TETR.IO PLUS or a browser extension.

## Available CSS Files

### Off-season ranks
![DAMNNNN](https://0tv.github.io/tetrio-css/off-season-rank-cards/example.png)
#### Note that this DOES NOT display a hidden Tetra League rating, it simply uses the TR the user had when Season 1 ended. There is no guarentee that your opponent is still at the skill level that the badge indicates.
[main.css](https://github.com/0tv/tetrio-css/blob/main/off-season-rank-cards/main.css) (renders the record on the profile card) | [adv-logic.css](https://github.com/0tv/tetrio-css/blob/main/off-season-rank-cards/adv-logic.css) (reads TR from user's season 1 rank badge)


You can load this without pasting all the code into your CSS editor using the following (make sure it's at the top of your code and not below anything else):
```css
@import url("https://0tv.github.io/tetrio-css/off-season-rank-cards/main.css");
@import url("https://0tv.github.io/tetrio-css/off-season-rank-cards/adv-logic.css");
```

## How to Apply Custom CSS

### Using TETR.IO Plus

1. **Obtain TETR.IO Plus**: Ensure you have TETR.IO Plus, which allows for the use of custom CSS.
2. **Load Custom CSS**: 
   - Open the TETR.IO Plus window, this should open when you start TETR.IO for desktop users.
   - Navigate to the option to enable custom CSS and enable it.
   - Press edit, and paste the CSS code into the text box, then save.
3. **Refresh**: Refresh the TETR.IO client to see the changes take effect.

### Using Browser Extensions

If you are using extensions or tools that allow custom CSS:

1. **Choose an Extension**: Install a browser extension or tool that supports custom CSS injection, such as Stylus for Chrome or Firefox.
2. **Apply Custom CSS**:
   - Open the extension’s interface.
   - Create a new style or edit an existing one.
   - Paste the CSS code from the downloaded file or link it directly to the file URL if the extension supports it.
3. **Save and Refresh**: Save your changes and refresh the TETR.IO client to see the custom styles applied.
