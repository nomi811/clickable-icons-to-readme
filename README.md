# How to add clickable icons and images to your Readme file on Github

First you need to get ahold of some icons that you want to use.  Do a Google search for free icons, or make some yourself like I did.

They need to be in a PNG, GIF, JPG, DOCX, PPTX, XLSX, TXT, PDF, or ZIP format.

On your repo that you want to add the icons to, create an issue.  Drag and drop the icon file into the issue window.  Wait for it to download, then it will give you a link.  Copy and paste this link into your Readme file at the location you want the icon to appear. Don't delete the issue after you are done, but you can close it.  

I had mine all in a row with lines on top and bottom. It looks like this:

![screen shot 2016-09-26 at 10 13 02 am](https://cloud.githubusercontent.com/assets/17016297/18839816/fad7e794-83d1-11e6-87e1-b80a316ed1a5.png)


(Psst... this is a screenshot, so it's not clickable. Go to the bottom of the page to try out my clickable icons.)

And the code looks like this:
```
---
[![github](https://cloud.githubusercontent.com/assets/17016297/18839843/0e06a67a-83d2-11e6-993a-b35a182500e0.png)][1][![facebook](https://cloud.githubusercontent.com/assets/17016297/18839836/0a06deb4-83d2-11e6-8078-1d0974af0f63.png)][2][![linkedin](https://cloud.githubusercontent.com/assets/17016297/18839848/0fc7e74e-83d2-11e6-8c6a-277fc9d6e067.png)][3]
---
```

If you break down the code for one icon it is:

`[![github](https://cloud.githubusercontent.com/assets/17016297/18839843/0e06a67a-83d2-11e6-993a-b35a182500e0.png)][1]`

where the content in the first set of square brackets is the link created by dragging and dropping your image file into the repo issue window and the `[1]` at the end corresponds to the numbered link you will create in the next step.

At the bottom of the file, create a numbered list for all your various account links.  I used social media links, but it could be any type of link.  The code will be in this format:

```
[1]: http://www.github.com/your_contact_info
[2]: https://www.linkedin.com/in/your_contact_info
[3]: https://www.facebook.com/your_contact_info
```

The instructions to drag and drop the icon file into a repo issue works the same for any image file you might want to add, including screenshots from your project pages, and test results.

Here's a picture I took in my backyard.

![img_4286a-350x233](https://cloud.githubusercontent.com/assets/17016297/18681463/da12c5c2-7f2d-11e6-8c53-4cb2e8914b3a.jpg)

The code needs to be a tiny bit different. Take off the enclosing square brackets, and no need for the bracketed number at the end. Basically, it is the link generated in the issue without anything added.

`![img_4286a-350x233](https://cloud.githubusercontent.com/assets/17016297/18681463/da12c5c2-7f2d-11e6-8c53-4cb2e8914b3a.jpg)`

Hope this was helpful!!

[1]: http://www.github.com/nomi811
[2]: https://www.linkedin.com/in/nomi-vos-097aa082
[3]: https://www.facebook.com/nomi.vos

---
[![github](https://cloud.githubusercontent.com/assets/17016297/18839843/0e06a67a-83d2-11e6-993a-b35a182500e0.png)][1][![facebook](https://cloud.githubusercontent.com/assets/17016297/18839836/0a06deb4-83d2-11e6-8078-1d0974af0f63.png)][2][![linkedin](https://cloud.githubusercontent.com/assets/17016297/18839848/0fc7e74e-83d2-11e6-8c6a-277fc9d6e067.png)][3]

---
