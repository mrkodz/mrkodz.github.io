Kodzi - An add-on created to help install Kodi Repositories and Add-ons. What makes Kodzi different, it attempts to install any add-on from any website URL, providing the zip is available on the website page and in a click-able form (is that even a word?). What I mean is, if you can click on the zip and it will download to your computer, then Kodzi can/will attempt to download and install it.

FEATURES:

    - Personal lists of Repositories & Add-ons
    - Install plugins and/or scripts from most websites (obviously provided the conditions explained above are met)
    - No need to enter any https:... just enter the website like you would in a browser
    - gc (Github clone) support, explained abit below
    - Browse GitHub, just like with a browser and install zips


Peronal Lists

The version you need for it to work is it plugin.video.kodzi-1.0.2 and higher
To create your own personal lists, look at the following example:
https://mrkodz.github.io/repo/Example.txt
That's  the structure required. So you can create any text file and follow that convention and upload it, for your lists to be displayed in Kodzi. The kodzi-title and  kodzi-name are needed, and the structure must be the same. But  everything in [""] can be changed. Hope that is clear.
Now go into KodzI and select 'Enter Lists Url', when prompted enter the website above (https://mrkodz.github.io/repo/Example.txt). Now you should see your lists.

gc and gt Support:

Basically gc: (GithubClone) allows you to clone a Github directory (You must see the Green clone button on Github to use this). This is very complicated as you shouldn't need to clone any git, but it's there for the people that need it. I think it's better explaining with example.
Example: Take opensubtitles ; https://github.com/opensubtitles/service.subtitles.opensubtitles_by_opensubtitles
You can clone it by typing in the Kodzi ('Enter Website or Github Url.....') the following
"gc:opensubtitles/service.subtitles.opensubtitles_by_opensubtitles "
Without the (") . Kodzi will clone and install the subtitle add-on. (If you look carefully at the git, you can see there's a zip you can download, so if you enter the whole url, Kodzi will also find the zip)

gt: Deprecated


You can install it by going into your :

    Kodi Settings and selecting File Manager
    Select Add source
    Choose None in the dialog that pop's up
    Enter the following:

    https://mrkodz.github.io

    Press OK and select the field below 'Enter a name for this media source' and type:

    .mrkodz

    Press OK to save the name, then OK again to add the file source
    Go back to the Kodi Main screen and select Add-ons from left.
    Select the Browse icon, the box looking icon.
    Choose Install from zip file
    Find .mrkodz and select it.
    Then select plugin.video.kodzi to install


NOTE: When you open the Add-on for the first time, a window will pop-up with my repository, TheKodz Repository, you can choose to install it or cancel (but then you won't be able to use the add-on). With that being said,
ALWAYS INSTALL FROM A REPOSITORY, SO THE ADD-ON INSTALLS CORRECTLY WITH THE RIGHT DEPENDENCIES. SO USE THIS ADD-ON TO INSTALL REPOSITORIES NOT ADD-ONS (unless you know what you're doing)
