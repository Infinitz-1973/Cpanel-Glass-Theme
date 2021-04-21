# Cpanel-Glass-Theme
New Cpanel Glass Theme for Older Versions of Cpanel/whm (Tested with Version 94.0.4)

## Preview
<img src="https://raw.githubusercontent.com/Infinitz-1187/Cpanel-Glass-Theme/main/preview.png">

## Steps To Install :

1.Download the Repo and Go to Icons folder Unzip the .zip File.

3.Now Compress The Repo to .tar.gz or Download from Here : https://infinitz.eu.org/downloads/glass.tar.gz

3.Now Go to your whm UnderCpanel>Customization>Customize style>Upload a style

4.Now Select the .tar.gz File and Click Upload


## To Remove the Sidebar :

1.Login to the Reseller's Cpanel

2.Click on Filemanager Under Files and Go to the Following Diretory "var/cpanel/reseller/includes"

3.Now Open The File called "global_html_head.html.tt" If It's Not there Create One.

4.Now Paste the following CSS In it

```
<style>
#sidebar{
display: none;
}
</style>
```

Now click on Save

Note : The Sidebar can be removed only to The Account's under Reseller to Remove for the Reseller Contact your Provider.
