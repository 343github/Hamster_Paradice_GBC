# Hamster_Paradice_GBC
Tools to extract text from the gbc game Hamster Paradice  

Rename your ROM as `HP.gbc` put `carthographer.exe` into the folder and execute `extract.bat`  
I also include the extracted scripts if you want to skip this step, you will need to setup atlas  
for the insertion.  

Translating:  
The Scripts folder includes all game scripts with the configuration of the Atlas program.  
You have to add the translated text of each string, keeping the <..> control codes.  
```
Example:  

#W16($53580)  
// すごいわ！ このハムスターは<line>  
// てんじゅを まっとうした<line>  
// <$FB>の うまれかわりよ。<line>  
//<end>  
Wow! This hamster has<line>  
mastered the art of <line>  
standing on its head!<line>  
It's the reincarnation of <$FB> <end>  
```
