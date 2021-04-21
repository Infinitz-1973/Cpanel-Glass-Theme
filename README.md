# Cpanel-Glass-Theme
New Cpanel Glass Theme for Older Versions of Cpanel/whm (Tested with Version 94.0.4)

Steps To Install:
*Download the Repoo and Go to Icons folder Unzip the .zip File.
*Now Compress The Repo to .tar.gz or Download from Here : https://infinitz.eu.org/downloads/glass.tar.gz
*Now Go to your whm UnderCpanel>Customization>Customize style>Upload a style
*Now Select the .tar.gz File and Click Upload


To Remove the Sidebar :

*Login to the Reseller's Cpanel
*Click on Filemanager Under Files and Go to the Following Diretory "var/cpanel/reseller/includes"
*Now Open The File called "global_html_head.html.tt" If It's Not there Create One.
*Now Paste the following CSS In it
<style>
#sidebar{
display: none;
}
</style>
*Now click on Save

Note : The Sidebar can be removed only to The Account's under Reseller to Remove for the Reseller Contact your Provider.
