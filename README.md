# XEdit - edit controls extender
Single line edit controls (ENTRY, COMBO, SPIN) can have 2 additional visual elements: ClearText Cross and Password Eye.
- ClearText Cross removes entered text.
![ClearText Cross](https://github.com/mikeduglas/XEdit/blob/master/cross.png?raw=true)  
- Password Eye toggles password visibility.
![Password Eye 1](https://github.com/mikeduglas/XEdit/blob/master/eye1.png?raw=true)
![Password Eye 2](https://github.com/mikeduglas/XEdit/blob/master/eye2.png?raw=true)  
![Password Eye 1 and Cross](https://github.com/mikeduglas/XEdit/blob/master/eye1cross.png?raw=true)  
![Password Eye 2 and Cross](https://github.com/mikeduglas/XEdit/blob/master/eye2cross.png?raw=true)  

This package contains a set of classes and a template.  
It is fully compatible with [Cue banner](https://github.com/mikeduglas/Cue-Banner).

### Usage in an application
- Register xedit.tpl.
- Add global extension 'Activate XEdit - Edit controls extender'.

That's all.  

### Usage in hand-coded project
Include xedit.inc file:
```
  INCLUDE('xedit.inc'), ONCE
```
Declare an instance of TXEditMgr class:
```
xedtMgr  TXEditMgr
```
After OPEN(Window) add edit controls to the manager, passing control label:
```
  xedtMgr.AddControl(?sUserName)
  xedtMgr.AddControl(?sPsw)
```

That's all.    

### Demo program
The demo can be downloaded [here](https://www.dropbox.com/s/4jbzlficx2d4ood/XEditDemo.zip?dl=0).

### Requirements
- Clarion versions: C8..C11.  **C6.x is not supported.**
- Template chains: ABC, Clarion.
- Multi dll apps supported.
- Windows versions: Vista..Windows 10.  **XP is not supported.**

### Price
$150

### Contacts
mikeduglas@yandex.ru  
mikeduglas66@gmail.com  