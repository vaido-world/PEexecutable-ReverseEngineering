# PEexecutable-ReverseEngineering

## Reverse Engineers' Hex Editor | rehex by Daniel Collins (solemnwarning)

For taking notes and learning we need a proper Hex Editor, for this time I will use:  
https://github.com/solemnwarning/rehex/releases/download/0.3.91/rehex-0.3.91-win-x86_64.zip

### Bugs in the rehex
#### Not rendering after opening a file
After opening a file with rehex, there is a need to use  
`Mouse middle button` to `scroll up` and `scroll down` to trigger the proper rendering by rehex.
![reghex-norender-scrollup-bug](https://user-images.githubusercontent.com/21064622/122714988-e5e39700-d270-11eb-9d8b-5f937f0c8f73.gif)


#### Unable to insert **at the end of line** in the ASCII viewer or in the Hex Dump 
Simply press `down key` on the keyboard and it will take you to the last character or at the end of the Hex line.
