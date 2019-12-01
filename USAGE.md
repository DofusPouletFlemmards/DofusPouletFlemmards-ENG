


# USAGE / INSTRUCTIONS

[ [HOME](README.md) ] - [ [SHORTCUTS](#raccourcis) ] - [ [AUTO LOG IN](#autologin) ] - [ [PAIRING](#pairing) ] - [ [AUTO SWITCH](#autoswitch) ] -
[ [AUTO READY](#autoready) ] -  [ [AUTO SKIP](#autoskip) ] - [ [AUTO BUFF(Greed/Fortune)](#autobuff) ]  - [ [1 touche 1 personnage + Bip sonore](#onekey) ] - [ [AUTO TRADE](#trade) ] - [ [NO LOOT](#loot) ]- [ [TIPS](#tips) ] 

## SHORTCUTS <a name="raccourcis"></a>

You can change default shortcuts on DofusPouletFlemmards.
It's not possible to add the functions of a mouse (Click,wheel) as a hotkey from the interface, you have to edit the settings.ini file

- Open **DofusPouletFlemmards**,  [**AUTO**] tab
- **EDIT FILE**
- Look for the function that you want to change in [AUTO] and assign the key you want to use
- Then restart the program ( by default : Alt + & or exit and restart)

**Example**

| CTRL + Left CLICK               	| ALT + Left CLICK             	| WheelUp      	|
|------------------------------------	|------------------------------------	|---------------------	|
| AutoMoveKey=^LButton               	| AutoMoveKey=!LButton               	| AutoMoveKey=WheelUp 	|
| ^ : CTRL                           	| ! : ALT                            	|                     	|


On DofusPouletFlemmards'interface, the hotkey will appear as " Ctrl + " but don't worry, it has correctly been changed

**Exemple 2 - Switch Tab**<a name="tab"></a>

| TAB                	| 
|------------------------------------	|
| SwitchTabKey=TAB               	|


For more information about hotkeys see :
https://www.autohotkey.com/docs/Hotkeys.htm
https://www.autohotkey.com/docs/KeyList.htm#mouse-general

> /!\ I do not recommend using CTRL + Click as a shortcut, on Dofus Ctrl+Click allows you to move a stack of item.
You can use CTRL + Click if and only if you're planning to use auto CtrlClicker which is what I do personally (by default : Alt+C)
Or you could set it as CTRL+M for example and set it on your mouse buttons


## Auto Log In<a name="autologin"></a>

> /!\ If you don't use Auto Log In and start dofus from Ankama Launcher
> make sure that Dofus is set up on 32bit


If you have changed the default installation folder
- When you press Start, It'll ask you to open the Dofus.exe file that is located in your installation folder :
>...\Ankama\zaap\retro\resources\app.asar.unpacked\retroclient

**How to add an account ?**
- Put your ID and password and press ADD
- If you have the same password for each account, you can directly edit the file by clicking on "Edit file" button


Your file must be of this format :

>id:pw  
>id:pw  
>id:pw  

_**(OPTIONAL)**_ To make things easier, check "Keep GUI on top" it'll keep DofusPouletFlemmard on top of every windows

___



## Pairing -> IMPORTANT if you want to use Auto Switch and Invite <a name="pairing"></a>

Il est possible de faire Pairing de deux manières : 

**1st way - Automatic pairing via Auto log in :**

- On DofusPouletFlemmards, go to "Accounts"
- Click on the "Link Char" button 
- Input your character name associated to your account
- Press the "Save" button

![1](https://i.imgur.com/5tynqq2.png)

**2nd way - Semi-automatic pairing in game :**

- On DofusPouletFlemmards : Click Chat Pos [(X,Y)] button and click on any place of the Dofus' Chat
- You must have the green chat enabled for every character

![1](https://i.imgur.com/WabGtYn.png)

___

## Auto Switch<a name="autoswitch"></a> or VIDEO >[CLICK HERE !](https://www.youtube.com/watch?v=C-uG38r7FlI)<

- Log in all your characters, start a challenge and join in with all your characters

**First step :**
- On DofusPouletFlemmards : Click (X1,Y1) button and click at the top left corner of the name displayed on the illustration to signal your turn
-  Click (X2,Y2) button and click at the bottom right corner of the name displayed on the illustration to signal your turn

![1](https://i.imgur.com/Qxqme01.png)

**Second step:**

To take a screenshot :
 **prt scr** key or only available on Windows 10 : **Win+Shift+S**

Still in fight with all characters :
With **Win+Shift+S**
- Press _**Win+Shift+S**_ when the illustration to signal your turn appears and capture the area containing your name
- Open Paint ( Press the WIN key then type Paint)
- _**CTRL-V**_ to paste
- Then click on crop
- Save image file in **\Documents\DofusPourLesFlemmards\Screenshots**, the name must be identical to your character name
- Repeat the process for every character

___

With **prt scr**
- Press _**prt scr**_ when the illustration to signal your turn appears and capture the area containing your name
- Open Paint ( Press the WIN key then type Paint)
- _**CTRL-V**_ to paste
- Then select the area containing the name with the rectangular form and click on crop
- Save image file in **\Documents\DofusPourLesFlemmards\Screenshots**, the name must be identical to your character name
- Repeat the process for every character

___

## Auto Ready<a name="autoready"></a>

- Start a challenge, or a combat
- On DofusPouletFlemmards : Press Ready [(X,Y)] button and click on the ready button on Dofus

![1](https://i.imgur.com/ue8pKTs.png)

**/!\ In a challenge, the position of "Ready" button corresponds to the "Cancel" button**

## Auto Skip<a name="autoskip"></a>

- Match **Skip Key** with your in game skip key

![1](https://i.imgur.com/yigvyog.png)

___

### Auto Buff ( Greed / Fortune )<a name="autobuff"></a>

- Go to  "Auto Buff"
- Set (X1,Y1) and (X2,Y2) position like this : 
- And don't forget to assign your key on DofusPouletFlemmards and on Dofus

![1](https://i.imgur.com/zMmBeEF.png)

## AUTO Buff ( Coffre Ani. ) <a name="chest"></a>

- Go to  "Auto Buff" -> CHEST 
- Set (X1,Y1) et (X2,Y2) like this

![1](https://i.imgur.com/AHjjBZZ.png)

- Don't forget to assign the key on DFP and Dofus
   * Chest Key : key corresponding to your in game animated chest key
   * AnySpell Key : Must be a spell with 1 range and that can be recast each turn ( Hand-to-Hand attack, animated shovel, animated bag)

- Go to Option and check " **Highlight targetable squares** "
![1](https://i.imgur.com/pPmUlFD.png)

___
## 1 key 1 char + Beep <a name="onekey"></a>

- Once you've done the pairing
- Click on the "Chicken Factory" button
- Assign the key you want for a character
- (OPTIONAL) Beep when it's the turn of a character.
- Press the " Save " button

![1](https://i.imgur.com/k4BafzK.png)
___

## Auto Trade <a name="trade"></a>

/!\ Auto switch needs to be activated in order to work

- Trade with one of your character and don't accept yet
- On DPF 2.0, in "Auto 2"
- Configure the position NamePos(X1,Y1) and Name Pos 2 (X2,Y2) like the screen 

![1](https://i.imgur.com/t8eOmoL.png)

- Take a screenshot of the name of the character (Using the snipping tool is easier than using prt scr + paint)

![1](https://i.imgur.com/GrB9JeG.png)


- (IF YOU USE PAINT) Don't forget to the select the area containing the name and crop
- 
Save the image in **\Documents\DofusPourLesFlemmards\Screenshots-ECHANGE**, the filename has to be **IDENTICAL** to the name of your character
![1](https://i.imgur.com/jFwNwFS.png)


- Accept the trade and
- Configure the position AcceptPos(X,Y) like the screen (BLUE DOT)
- Don't take a position contaning a white color ( from the word Accept ), only orange

![1](https://i.imgur.com/9qI4um0.png)

___

## Auto No Loot <a name="loot"></a>

/!\ Auto switch needs to be activated in order to work

- Start a challenge with one of your character, then give up to get the end game result don't close it yet
- On DPF, in "Auto 2"
- Configure the EF.Ind Pos (X1,Y1) and EF.Ind Pos 2(X2,Y2) like the screen ( The blue dot between the inventory and map icon)

![1](https://i.imgur.com/9XX7Er5.png)
___

## WINTER IS COMMING... HOW TO KEEP ONE HAND WARM WHILE PLAYING HAHA <a name="tips"></a>

If you have a mouse with programmable buttons, assign each function to a button

Example of G502 :
![1](https://imgur.com/Fsgapak.png)
