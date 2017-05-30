# Sketch Annotator for Multimodal Collector
This is a simple software to extract and annotate sketched symbols in a sketch stream file generated by our [multimodal collector](https://github.com/ozymaxx/multimodal_collector). 

## Dependencies
* A linux distribution with `canberra-gtk-play` utility (e.g. Ubuntu)
* Python 2.7

## How to use (on bash)
* Open the software: `python run.py`
* Browse a `.sketch` stream file
* You should now see two panes. On the left, there is a drawing canvas, whereby the right one includes entries from the stream file you've selected. If you click on a single entry, then the entire drawing up to this entry will be displayed. If you choose multiple entries, then only the part of the drawing with the selected entries will be displayed.
* Once you've choosen your drawing, press A on the keyboard. Then browse the directory where you'd like to save your symbol, if it's the first time you've pressed this button. Finally, enter the name of the symbol and click OK. The symbol has been successfully saved to **pathyouselected/nameyouentered** if you heard a notification sound. 
* Your symbol is saved in two formats, one in image and one in points table. Please check [this](https://github.com/ozymaxx/sketchfe/) out for more details about points table, which is a way possible to represent a sketched symbol.

## Credits
Ozan Can Altıok (oaltiok15 at ku dot edu dot tr) - [Koç University IUI Laboratory](http://iui.ku.edu.tr)
