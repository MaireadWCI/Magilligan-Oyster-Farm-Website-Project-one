![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)

Welcome USER_NAME,

This is the Code Institute student template for Gitpod. We have preinstalled all of the tools you need to get started. It's perfectly ok to use this template as the basis for your project submissions.

You can safely delete this README.md file or change it for your own project. Please do read it at least once, though! It contains some important information about Gitpod and the extensions we use. Some of this information has been updated since the video content was created. The last update to this file was: **April 26, 2024**

## Gitpod Reminders

To run a frontend (HTML, CSS, Javascript only) application in Gitpod, in the terminal, type:

`python3 -m http.server`

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

To run a backend Python file, type `python3 app.py` if your Python file is named `app.py`, of course.

A blue button should appear to click: _Make Public_,

Another blue button should appear to click: _Open Browser_.

By Default, Gitpod gives you superuser security privileges. Therefore, you do not need to use the `sudo` (superuser do) command in the bash terminal in any of the lessons.

To log into the Heroku toolbelt CLI:

1. Log in to your Heroku account and go to *Account Settings* in the menu under your avatar.
2. Scroll down to the *API Key* and click *Reveal*
3. Copy the key
4. In Gitpod, from the terminal, run `heroku_config`
5. Paste in your API key when asked

You can now use the `heroku` CLI program - try running `heroku apps` to confirm it works. This API key is unique and private to you, so do not share it. If you accidentally make it public, you can create a new one with _Regenerate API Key_.

------

## Release History

We continually tweak and adjust this template to help give you the best experience. Here is the version history:

**April 26 2024:** Update node version to 16

**September 20 2023:** Update Python version to 3.9.17.

**September 1 2021:** Remove `PGHOSTADDR` environment variable.

**July 19 2021:** Remove `font_fix` script now that the terminal font issue is fixed.

**July 2 2021:** Remove extensions that are not available in Open VSX.

**June 30 2021:** Combined the P4 and P5 templates into one file, added the uptime script. See the FAQ at the end of this file.

**June 10 2021:** Added: `font_fix` script and alias to fix the Terminal font issue

**May 10 2021:** Added `heroku_config` script to allow Heroku API key to be stored as an environment variable.

**April 7 2021:** Upgraded the template for VS Code instead of Theia.

**October 21 2020:** Versions of the HTMLHint, Prettier, Bootstrap4 CDN and Auto Close extensions updated. The Python extension needs to stay the same version for now.

**October 08 2020:** Additional large Gitpod files (`core.mongo*` and `core.python*`) are now hidden in the Explorer, and have been added to the `.gitignore` by default.

**September 22 2020:** Gitpod occasionally creates large `core.Microsoft` files. These are now hidden in the Explorer. A `.gitignore` file has been created to make sure these files will not be committed, along with other common files.

**April 16 2020:** The template now automatically installs MySQL instead of relying on the Gitpod MySQL image. The message about a Python linter not being installed has been dealt with, and the set-up files are now hidden in the Gitpod file explorer.

**April 13 2020:** Added the _Prettier_ code beautifier extension instead of the code formatter built-in to Gitpod.

**February 2020:** The initialisation files now _do not_ auto-delete. They will remain in your project. You can safely ignore them. They just make sure that your workspace is configured correctly each time you open it. It will also prevent the Gitpod configuration popup from appearing.

**December 2019:** Added Eventyret's Bootstrap 4 extension. Type `!bscdn` in a HTML file to add the Bootstrap boilerplate. Check out the <a href="https://github.com/Eventyret/vscode-bcdn" target="_blank">README.md file at the official repo</a> for more options.

------

## FAQ about the uptime script

**Why have you added this script?**

It will help us to calculate how many running workspaces there are at any one time, which greatly helps us with cost and capacity planning. It will help us decide on the future direction of our cloud-based IDE strategy.

**How will this affect me?**

For everyday usage of Gitpod, it doesn’t have any effect at all. The script only captures the following data:

- An ID that is randomly generated each time the workspace is started.
- The current date and time
- The workspace status of “started” or “running”, which is sent every 5 minutes.

It is not possible for us or anyone else to trace the random ID back to an individual, and no personal data is being captured. It will not slow down the workspace or affect your work.

**So….?**

We want to tell you this so that we are being completely transparent about the data we collect and what we do with it.

**Can I opt out?**

Yes, you can. Since no personally identifiable information is being captured, we'd appreciate it if you let the script run; however if you are unhappy with the idea, simply run the following commands from the terminal window after creating the workspace, and this will remove the uptime script:

```
pkill uptime.sh
rm .vscode/uptime.sh
```

**Anything more?**

Yes! We'd strongly encourage you to look at the source code of the `uptime.sh` file so that you know what it's doing. As future software developers, it will be great practice to see how these shell scripts work.

---

Happy coding!

23/05/24

https://docs.google.com/document/d/14p_OkuVETSkwAEcmhyA3MSAHjsIHavdmzmFHj7FhHOs/edit?usp=sharing (Spec Doc for project 1)

Boiler plate html added 
index.html added
Favicon unsuccessful add
assets folder created

Favicon issue resolved had to unzip before adding. 
added links for fav icons and formatted doc to links would add nicely 
/workspaces/Magilligan-Oyster-Farm-Website/Assets/Favicon/logo.png

google fonts selected -https://fonts.google.com/

Hero image added to main page and section of reasons added underneath. Audio of wave added to the hero cover text mpeg taken from Pixabay.com. https://pixabay.com/sound-effects/ocean-waves-112906/loop was added to the audio control and hope to hide controls and style with icon that has a call to ation to open the controls. i have worked hard on making hero image fit on all size devices. On small screen still having issues with the top not meeting neetly with the header. 
Hero image is just a place holder at the minute as pixalation is poor. Worried with new image it may through everything I have done so far off. But that is the joys!

Need to learn how to revert to a certain section of code. 

waiting on access to gidpod enterprise. I seem to just have been coding in github this whole time , so would like to start doing it properly so I finish project with more knowlege . Navigation of Gitpod/Github has been tough. Time to master it. 

Site deployed https://maireadwci.github.io/Magilligan-Oyster-Farm-Website/index.html


Testing 
Lighthouse - https://developer.chrome.com/docs/lighthouse/overview/
Page sppeed insights - https://pagespeed.web.dev/

Having alot of issues trying to add the video at the bottom of page one. I know it has to do with the file path but cant figure out what the issue is. I have tested the rest of the code by addind a background colour inplace of the url and that works perfect. After trying another image placed in the video file, I see It is the fact it is a video that I am trying to add as an image. So I am now assuming it needs tp be put in an iframe. After numerous attemps, Video container has finally appeared, although no video yet. think there is still issue with path. 

Finding it hard to get the divs to wrap at the products and services section on page 1. I am thinking I may not be selecting the correct tags. Been at this for a few days so determined to get it sorted today. 