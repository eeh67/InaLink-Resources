# InaLink Work Skin for Ao3

| Without background image                                                                                 | With background image (more similar to InaLink)                                                                                |
| -------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------ |
| <br>![example](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/example1.jpg?raw=true) | <br>![example background](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/example_backrgound1.jpg?raw=true) |

If you need anything, please send a message/ask in Tumblr. My user is [@lazyanon-juju](https://www.tumblr.com/blog/lazyanon-juju). 

This is a throwaway GitHub account (to have this separated from my uni account), so I won't answer to any reported Issues here.

# Credits and Thanks
Full thanks to [this post](https://archive.transformativeworks.org/works/56948686) by noliteobdurae, which I used as a base to make the CSS. There's features there that I haven't used for mine like embedded links, videos, or similar; so if you're looking to do something like that, I recommend taking a look!

Also huge thanks to Mei and their friend, who helped me get the images found here!

# How to use

Please credit me by linking this GitHub if you use it! Thank you!

I decided to use GitHub because I'm able to host the images in an organised way. This isn't a program or anything, so you don't need to download anything.

## Create a Work Skin
If you don't know how to, there's plenty of tutorials, but to keep it short: look into your "Skins" in your Profile settings in Ao3.

Then, under the CSS part, paste the contents from "**InaLink.css**". There's no need to download the file, just click on it in GitHub itself and copy everything in it.

Congrats! You now have a Work Skin!

## Select Work Skin for a fic

Go to Edit the fic you want to use it for or create a new fic. Then, under the language settings of a fic, there's an option to select a Work Skin. Just select it in there, pretty simple!

## Write using the Work Skin

For this part I recommend using the HTML editor of Ao3 instead of the Rich Text one. 

There's an example found in "**HTMLexample.txt**" (again, just copy the contents) that you can just paste into your fic and edit it directly, but here's a tutorial nonetheless.

### Profile pictures
The profile pictures linked in the CSS are the ones found in the "**pfp_margins**" folder. 

To use a specific one **use the *name of the file* without the ".png"**. You'll see where in the next step.

I might add more in the future, but it's significant work to do many at once. Therefore, if you want a specific one you can either: 
- send me a message/ask via Tumblr asking which ones you need (no guarantee that they'll be added any time soon)
- host it yourself somewhere else and edit the CSS accordingly

This is more of a side project for me, so I won't always have the time to keep it updated. I hope you understand!
### HTML explanation

Fast summary:

`<div class="in tenma">` / `<div class="out endou_adult">`:
- "`in`" for incoming texts, "`out`" for outgoing texts
- use the name of the file for the pfp selection (`tenma`, `endou_adult`)
- name above pfp goes between `<dt></dt>`
- messages go between `<dd></dd>`

Actual summary:

| Example image                                                                                                         | Example HTML                                                                                              |
| --------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------------------------- |
| <br>![example simple](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/example_simple.jpg?raw=true) | <br>![example html](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/HTML.png?raw=true) |


Example HTML explained:

![example html](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/HTMLexplained.png?raw=true)
### Background image

As shown in the example, you can also add a background image to make it more similar to InaLink. 

I don't have it by default because the placement of the pictures and the names aren't properly adjusted for it, but you can fiddle with those easily in the CSS.

If you want to add it then add this inside of the `.line .messagebody{}`:

```
background-image: url("https://raw.githubusercontent.com/eeh67/InaLink-Resources/refs/heads/main/other/background_borders.png");
```


### Toast notifications

| Toast notification "Today"                                                                                      | Snippet of HTML                                                                                                   |
| --------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------- |
| ![example toast](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/toast_example.png?raw=true) | ![example toast html](https://github.com/eeh67/InaLink-Resources/blob/main/README_images/toast_html.png?raw=true) |
