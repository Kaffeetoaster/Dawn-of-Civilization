


## using in other mods
- fix dependencies in screenexternal on RFCUtils.py, i dont know maybe pass down the two extraction methods getUnitCategory() and getBuildingCategory() from CvPediaMainExternal or sth. Done

- keep CvPediaMainExternal Mod independent and import mod specifi cthings. How?
I want to have one file per mod, like modhelper.py, that gets importet, but when?
simply import the coresponding fileß

- also the createcivilopedia should expect a mapListGenerators and a mapScreenFunctions map to call. Each mod is responsible to define those.




# CanDos:

- maybe try to find out what is wrong with the transhumanism tech



## links
- each Pedia entry is responsbile to know ...
    - the link to itself
    - from which widegttype one can get reached
    - for knowing its own id
    - its own previewtext
- so while building the entry in CvPediaMainExternal these infos are gatherd. And in the preprocessing for each button the preview and link is assigned based on the widgettype and id




## preview texts
Expose parseHelp() to python and understand how to call it properly using widgetStruct.
What dose getHelp, getText, getDescription from the CvInfoBase Class do? What is the differnece?
