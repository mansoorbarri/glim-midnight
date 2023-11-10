## Glim Midnight

A minimal links page made with Hugo.

## Author:

[Maheen Waris](https://maheenwaris.com)
[Mansoor Barri](https://mansoorbarri.com)

### demo: https://glim-midnight.pages.dev

## Features

- Bootstrap
- Dark
- Minimal
- Responsive

## Screenshot

![Screenshot of the demo site](https://raw.githubusercontent.com/mansoorbarri/glim-midnight/main/images/screenshot.png)

## Installation

### Setup 
- Make a new hugo site
```
hugo new site {sitename}
cd {sitename}
git clone https://github.com/mansoorbarri/coming-soon.git themes/coming-soon
```

- Copy `examplesite/config.toml` files to yours for quick setup
- Open `config.toml` and edit as per your liking. 

### Config.toml
```
baseURL = "http://glim-midnight.pages.dev"
languageCode = "en-us"
theme = "glim-midnight"

[params]
    title = "Glim Midnight"
    phrases = ["Bootstrap", "Dark", "Minimal", "Responsive"]
    links = [
    {name = "Github", url = "https://github.com/mansoorbarri/glim-midnight/"},    
    {name = "Wiki", url = "/wiki"},    
    {name = "Author I", url = "https://maheenwaris.com/"},    
    {name = "Author II", url = "https://mansoorbarri.com/"},    
    {name = "Hugo", url = "https://gohugo.io/"},    
    ] 
    background = "bg.mp4"
```

Variables you should/can change
- `baseURL`: URL of your website
- `title`: this title will be shown as tab name and as `<h1>` on this website
- `phrases`: these are the words which are animated under the main title
- `links`: these are the links you want to add, you have to mention the name & the url where the button will lead to
- `background`: this is the background of the webpage currently, the theme only supports video as a background.

## Performance

Google PageSpeed Insights

![Screenshot of the result](https://raw.githubusercontent.com/mansoorbarri/glim-midnight/main/images/pagespeed.png)

## Licence

This code is licensed under [GNU GPLv3](https://github.com/mansoorbarri/glim-midnight/blob/main/LICENCE)