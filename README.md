# lyx-templates
Document templates for LaTeX / LyX

This repository contains a collection of templates for the [LyX software](https://www.lyx.org/).
LyX is a document processor that encourages an approach to writing based on the structure of the document (WYSIWYM: What You See Is what You **Mean**) 
rather than on the appearance (WYSIWYG). 

The templates are based on the KOMA-scripts package. 
They include additional configurations for fonts, colors, minimal document structures,
default settings for some programming langages (Java or Matlab), settings for french language...

## Installation

Templates are located in the "templates" directory. Each template corresponds to a LyX file. 

To install a template, it suffices to copy the corresponding LyX file into the appropriate directory:
* For LyX versions previous uo to 2.3.*, the "templates" directory is that of the current LyX installation (typical windows location: `C:\Program Files\LyX-2.3\Resources\templates`, please update to your local configuration).
* from LyX versions 2.4, it is possible to use user directory: `~\AppData\Roaming\LyX2.4\templates`

## Usage

From LyX, simply click on File -> Open With Template... and select the appropriate template. 
Starting from version 2.4, it is possible to filter user templates from system templates.

## List of templates

The templates are organized in a hierarchy of directories that allows to sort them according to the target langauge (english, french...)
and the type of document (articles, reports...).

* en
  * Articles
    * **Article_KOMA-Script_en.lyx**: simple template for a technical note written in english
    * **Article_KOMA-Script_Matlab.lyx**: simple template for a technical note written in english, with Listing configfuration for the Matlab language
  * Reports
    * **Report_KOMA-Script_en.lyx**: simple template for a report written in english
* fr
  * Articles
    * **Article_KOMA-Script_fr.lyx**: simple template for a technical note written in french
    * **Article_KOMA-Script_Java_fr.lyx**: simple template for a technical note written in french, with Listing configfuration for the Java language
  * Reports
    * **Report_KOMA-Script_en.lyx**: simple template for a report written in french

