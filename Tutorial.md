
# Introduction #

adt-extentions is en extention to ADT, it provider wizards to new Acitivity,Service,BroadcaseReceiver,ContentProvider in Eclipse.

# Version #
Based on eclipse version.

3.5.0 _(Oct,2011)_ first version.

# Requirement #

  * JDK/JRE 1.5 or higher
  * Eclipse 3.5 or higher(recommend)

Note: Eclipse 3.5 + JDK 1.5 is developer environment.

# Test #

  * jdk 1.5 + eclipse 3.5 Win(32bit) OS
  * jre 1.6 + eclipse 3.6 Linux(64bit) OS


# Install #

## Install online ##
  1. Download update-site archive
  1. Click Help->Install New Software... in eclipse to open install page
  1. Add site or input http://melord.info/eclipse/3.5 directly
  1. Select Adt-extention Feature
  1. Read and accept the license agreements, then click **Finish**.

Note: If you get a security warning saying that the authenticity or validity of the software can't be established, click **OK**.
  1. When the installation completes, restart Eclipse.

## Local Archive ##
  1. Download plugin update site archive
  1. Click **Help->Install New Software...** in eclipse to open install page
  1. Click **Add...** button open add site dialog
  1. Click **Archive...** button to select downloaded .zip file.
  1. Click **OK** back to install page
  1. Select Adt-extention Feature
  1. Read and accept the license agreements, then click **Finish**.

Note: If you get a security warning saying that the authenticity or validity of the software can't be established, click **OK**.
  1. When the installation completes, restart Eclipse.

# Tutorial #
> ## New Activity ##
  * Choose a package right click and select "New->Others" in popups menu.
  * Select New Activity under Android category.(If you work in java perspective, New Activity would be visible popups menu.) to open wizard page.
  * Check "with super suffix" to add super suffix to type name.(such with a Activity suffix)
  * Select methos stubs which you want to create.
  * Click "Add..." to add System action/category
  * Click "Remove..." to remove selected action/category
  * Click "Add custom" in popups to add custom action/category
  * Click "Up/Down" to sort selected action/category
  * Double click to edit seleted action/category
> ## New Provider ##
    * See New Activity steps to open New Provider wizard page
    * Input authorities for provider

More tutorial please click [Screenshot](Screenshot.md)