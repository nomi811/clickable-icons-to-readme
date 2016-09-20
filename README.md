# How to add clickable icons to your Readme file on Github

First you need to download the icons you want.  Do a Google search for free icons.

They need to be in a PNG, GIF, JPG, DOCX, PPTX, XLSX, TXT, PDF, or ZIP format.  I edited mine in Adobe Illustrator to change file type and to size down to 40px square with a surrounding area of 70px square.

On your repo that you want to add the icons to, create an issue.  Drag and drop the icon file into the issue window.  Wait for it to download, then it will give you a link.  Copy and paste this link into your Readme file at the location you want the icon to appear. Don't delete the issue, but you can close it.  

I had mine all in a row with pipe symbols in between and lines on top and bottom. It looks like this:

(PS this is a screenshot, so it's not clickable. Go to the bottom of the page to try out my clickable Github icon.)

![screen shot 2016-09-20 at 10 58 23 am](https://cloud.githubusercontent.com/assets/17016297/18678323/49cdf790-7f21-11e6-9b23-2fe9963df9db.png)

And the code looks like this:
```
---
|[![github](https://cloud.githubusercontent.com/assets/17016297/18654066/e5c135dc-7ea3-11e6-8cf6-6a8f628897bc.png)][1]|[![linkedin](https://cloud.githubusercontent.com/assets/17016297/18654069/e7e21930-7ea3-11e6-89cf-37329de79b36.png)][2]|[![behance](https://cloud.githubusercontent.com/assets/17016297/18654062/e2e79c48-7ea3-11e6-9b5c-3da110b8a2dd.png)][3]|[![facebook](https://cloud.githubusercontent.com/assets/17016297/18654065/e42ed904-7ea3-11e6-94eb-ea5d66dfd191.png)][4]|
---
```

If you break down the code for one icon it is:

`[![github](https://cloud.githubusercontent.com/assets/17016297/18654066/e5c135dc-7ea3-11e6-8cf6-6a8f628897bc.png)][1]`

where the content in the first set of square brackets is the link created by dragging and dropping your image file into the repo issue window and the `[1]` at the end corresponds to the numbered link you will create in the next step.

At the bottom of the file, create a numbered list for all your various account links.  I'm talking about social media links, but it could be any type link.  The code will be in this format:

```
[1]: http://www.github.com/your_contact_info
[2]: https://www.linkedin.com/in/your_contact_info
[3]: https://www.behance.net/your_contact_info
[4]: https://www.facebook.com/your_contact_info
```

The instructions to drag and drop the icon file into a repo issue works the same for any image file you might want to add, including screenshots from your project pages, and test results.

Here's a picture I took in my backyard.

![img_4286a-350x233](https://cloud.githubusercontent.com/assets/17016297/18681463/da12c5c2-7f2d-11e6-8c53-4cb2e8914b3a.jpg)

The code needs to be a tiny bit different.

`![img_4286a-350x233](https://cloud.githubusercontent.com/assets/17016297/18681463/da12c5c2-7f2d-11e6-8c53-4cb2e8914b3a.jpg)`

Hope this was helpful!!

[1]: http://www.github.com/nomi811

[![github](https://cloud.githubusercontent.com/assets/17016297/18654066/e5c135dc-7ea3-11e6-8cf6-6a8f628897bc.png)][1]
