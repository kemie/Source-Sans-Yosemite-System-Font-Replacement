
Source Sans System Font Replacement for Yosemite
==============================

If you're not crazy about using Helvetica for your UI, this is an easy way to change it to something more suitable. After looking for a bit for alternatives, I found Source Sans to be a very good alternative, closer to Lucida Grande, and with a wide range of weights. 

The idea comes from Jens Jens Kutilek's [Fira Sans Replacement](https://github.com/jenskutilek/FiraSystemFontReplacement) and generated with Thai Pangsakulyanont's [Yosemite System Font Patcher](https://github.com/dtinth/YosemiteSystemFontPatcher).



![Yosemite Source Sans](http://note.io/1uzNWaE)
## How it works
This does not hack or patch your OS in any way. It is a completely non-destructive way to replace the systemfont. It works by modifying the Source Sans font files to set their names to what Yosemite expects Helvetica to be. By placing them in your library/fonts folder, they will be loaded before the actual Helvetica fonts. The original fonts are not modified or replaced. 

## How to install

### Download the font files
You can clone, fork, or download the repo from GitHub.
Once you have the files for **Style Guide Boilerplate**, extract the font files (.ttf) to a temporary place.

### Copy to your library 
In a finder window, choose Go-->Go to folder and type in /Library/Fonts/. Copy the extracted files there. 

### Log out & in
Log out and in from your user for the changes to take effect.


## How to uninstall
Remove the SystemSourceSans* fonts from your /Library/Fonts folder. Log out & in again.

## Licence	  
The **Source Sans Family  ** is licensed under the [SIL Open Font Licence Version 1.1](http://scripts.sil.org/OFL)

##Questions? Comments?
The font set was generated and is maintained by [Kemie Guaida](http://www.monolinea.com/about). It was only tested briefly. So far only minor bugs were discovered, so if you find any, please open an issue. 

If you have questions or suggestions, you can open an issue here at github, or ping me via twitter [@kemie](http://twitter.com/kemie)


