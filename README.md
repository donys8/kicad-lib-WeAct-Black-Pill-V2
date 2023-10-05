# kicad-lib-WeAct-Black-Pill-V2

## Install
1. Copy files to your favorite folder of your local PC.  
  `$ cd <YourPath>`  
  `$ git clone https://github.com/donys8/kicad-lib-WeAct-Black-Pill-V2.git`  
  or just  
  Download and place files (`STM32F411_Black_Pill.kicad_mod`, `WeAct_Black_Pill_V2.0.kicad_sym`)  
2. Symbol
  Open KiCAD's "Preferences"->"Manage Symbol Libraries"  
  Add line to "Global Libraries"  
  Nickname=WeAct_Black_Pill_V2.0, LibraryPath=<PathToYourFolder>/kicad-lib-WeAct-Black-Pill-V2/WeAct_Black_Pill_V2.0.kicad_sym, PluginType=Legacy

3. Footprint
  Open KiCAD's "Preference"->"Manage Footprint Libraries"  
  Add line to "Global Libraries"  
  Nickname=WeAct_Black_Pill_V2.0, LibraryPath=<PathToYourFolder>kicad-lib-WeAct-Black-Pill-V2/STM32F411_Black_Pill.kicad_mod, PluginType=KiCad

### Symbol
![](images/STM32F411_Blacx_Pill_Symbol.png)  

### Footprint
![](images/STM32F411_Blacx_Pill_Footprint.png)  

