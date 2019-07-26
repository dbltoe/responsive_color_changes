# responsive_color_changes
 Bringing the Responsive_Classic Color Changes to versions 1.5.x

Version Date
==============
v 2.0.0 07.19.2019 121:52:00

Author
======
dbltoe

Thanks
======
rharbour and picaflor-azul for their work on the responsive_classic template.
haredo for assistance in development of this add-on/modification.
lat9 for the Clone a Template mod

Description
===========
This add-on/modification contains files needed to assist in Responsive Color Changes for Zen Cart Versions 1.5.x.

Zen-Cart Versions
================
1.5.5a
1.5.5b
1.5.5c
1.5.5d
1.5.5e
1.5.5f
1.5.6
1.5.6a
1.5.6b
1.5.6c

Support thread
==============
https://www.zen-cart.com/showthread.php?220487-Support-Thread-Responsive-Color-Changes-for-155

Files and Folders in the Packet
==============
0.  Index.html - Main file with information and instructions
1.  readme.md - This file
2.  license.txt - License Information
3.  quickInstall.txt - Quick Install Instructions (if you just can't wait)
4.  Color Combos - A folder containing the main color combo used with this add-on/modification (10687) and four other examples.
5.  stylesheet_colors_split.css - This stylesheet is meant to replace the existing stylesheet_colors.css
6.  stylesheet_zcustom.css - This stylesheet contains all the color/alignment changes rather than change six other stylesheets.


Affected files
==============
Adds the following stylesheets to your site:
includes/templates/TEMPLATE/css/stylesheet_colors_split.css
includes/templates/YOUR_TEMPLATE/css/stylesheet_zcustom.css


NOTE:  includes/templates/TEMPLATE/css/stylesheet_colors.css should be removed or renamed to stylesheet_colors.### where ### are your initials or some other three-digit combo that you can remember and is not a common file extension.

Affects DB
==========
No

DISCLAIMER
==========
Installation of this contribution is done at your own risk.
Backup your ZenCart includes/templates/YOUR_TEMPLATE/css files before proceeding.

Features:
=========
0. Provides an easier method of Responsive_Classic Color Changes for Zen Cart Versions 1.5.5a to 1.5.6c
1. Includes advanced coloring procedures to include rgba calls with opacity.
2. Includes minor stylesheet adjustments to better the presentation on some mobile devices.

Install:
========
0. Clone the responsive_classic template using lat9's  Clone a Template mod creating a new template for your site (YOUR_TEMPLATE).
1. Unzip the Responsive_Classic Color Changes package to your local hard drive, retaining the folder structure.
2. The Color Combos folder contains the main color theme used with this add-on/modification and four additional optional color combinations.
3. Edit the stylesheet_colors_split.css and stylesheet_zcustom.css to change the existing colors to match those chosen for YOUR_TEMPLATE.  (see the index.html or quickInstall.txt files for details).
4. Upload the two stylesheet files to your includes/templates/YOUR_TEMPLATE/css folder.  This should not overwrite any existing stylesheets.
5. Rename includes/templates/YOUR_TEMPLATE/css/stylesheet_colors.css to includes/templates/TEMPLATE/css/stylesheet_colors.$$$ where $$$ are your initials.

Upgrade:
========
Delete includes/templates/YOUR_TEMPLATE/stylesheet_colors_split.css from your site.
Restore the css folder for your version of Zen Cart to includes/templates/YOUR_TEMPLATE/
Follow the installation instructions starting with item one (1).

Un-Install:
========
1. If you want to go back to responsive_classic (or any other template loaded on your site), simply make the selection in the YourAdmin >> Tools >> Template Selection Menu.

History
=======
v 2.0.0  19.07.2019 14:23   - Initial Version