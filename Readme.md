# `JWM`配置文件

---

[`JWM` (`Joe's Window Manager`)](https://wiki.archlinux.org/title/JWM)是用[`c`语言](https://en.wikipedia.org/wiki/C_(programming_language))编写的[`Xorg`](https://wiki.archlinux.org/title/Xorg)轻量级[窗口管理器](https://wiki.archlinux.org/title/Window_manager)。 </br>

由[`Joe Wingbermuehle`](https://joewing.net/about.html)积极开发和维护。 </br>

---

## 中文说明：

该仓库为本人根据`antiX`的`jwm`配置文件和`Puppy Linux`的`jwm`配置文件修改而来， </br>

虽已正在使用，但不确定在其他电脑使用该配置是否会有任何异样。 </br>

---

### 使用说明：

- ① 使用如下命令，将该仓库中想使用的`jwm`配置文件复制到`~/`（用户主文件夹）内： </br>
  
  ```shell
  $ cp -rfpv .jwmrc ~/
  ```
  
  > **注意：** </br>
  > 
  > ① 若想使用其他发行版的`jwm`配置文件，需将其他`jwm`配置文件重命名为`.jwmrc`，所有的`jwm`配置文件任选其一即可。 </br>
  > 
  > ② [`.jwmrc-previous-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-previous-puppy-example ".jwmrc-previous-puppy-example")和[`.jwmrc-tray-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-tray-puppy-example ".jwmrc-tray-puppy-example")并非`jwm`主配置文件，这两个配置文件为`Puppy Linux`中`jwm`桌面环境的`previous`和`tray`的配置文件。 </br>
  
- ② 重新启动`jwm`桌面环境，即可使用该配置文件下的`jwm`桌面环境。 </br>
  
- ③ 享受其中吧。 </br>
  

---

### 文件说明：

- [`.jwmrc`](https://github.com/jidro/jwm/blob/master/.jwmrc ".jwmrc")为本人正在使用的`jwm`桌面环境的主配置文件。 </br>
  
- [`.jwmrc-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-antix-example ".jwmrc-antix-example")为`antiX`中`jwm`桌面环境的主配置文件。 </br>
  
- [`.jwmrc-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-puppy-example ".jwmrc-puppy-example")为`Puppy Linux`中`jwm`桌面环境的主配置文件。 </br>
  
- [`.jwmrc-numix-bevel-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-numix-bevel-antix-example ".jwmrc-numix-bevel-antix-example")/[`.jwmrc-numix-square-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-numix-square-antix-example ".jwmrc-numix-square-antix-example") - 这两个配置文件为`antiX`中`jwm`桌面环境`numix`主题的主配置文件。 </br>
  
- [`.jwmrc-papirus-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-papirus-antix-example ".jwmrc-papirus-antix-example")为`antiX`中`jwm`桌面环境`papirus`主题的主配置文件。 </br>
  
- [`.jwmrc-previous-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-previous-puppy-example ".jwmrc-previous-puppy-example")为`Puppy Linux`中`jwm`桌面环境的`previous`的配置文件。 </br>
  
- [`.jwmrc-tray-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-tray-puppy-example ".jwmrc-tray-puppy-example")为`Puppy Linux`中`jwm`桌面环境的`tray`的配置文件。 </br>
  
- `.jwm`文件夹内的所有文件为`jwm`桌面环境的辅配置文件，配合`jwm`桌面环境的主配置文件一起使用。 </br>
  
  - [`.jwm/theme`](https://github.com/jidro/jwm/blob/master/.jwm/theme "theme")为设定`jwm`主题的配置文件。 </br>
    
  - [`.jwm/themes-list`](https://github.com/jidro/jwm/blob/master/.jwm/themes-list "themes-list")为开始菜单中选择`jwm`主题的列表配置文件。 </br>
    
  - [`.jwm/themes`](https://github.com/jidro/jwm/tree/master/.jwm/themes "themes")文件夹为`jwm`可选的所有主题的文件夹。 </br>
    
  - [`.jwm/jwmrc-personal-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal-puppy-example "jwmrc-personal-puppy-example")/[`.jwm/jwmrc-personal2-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal2-puppy-example "jwmrc-personal2-puppy-example")/[`.jwm/jwmrc-personal_old-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal_old-puppy-example "jwmrc-personal_old-puppy-example") - 这三个文件为`Puppy Linux`中`jwm`桌面环境的`personal`配置文件。 </br>
    
  - [`.jwm/personal`](https://github.com/jidro/jwm/blob/master/.jwm/personal "personal")为`antiX`的`personal`配置文件。 </br>
    
  - [`.jwm/jwmrc-theme`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-theme "jwmrc-theme")为`Puppy Linux`中`jwm`桌面环境的主题配置文件。 </br>
    
  - [`.jwm/keys`](https://github.com/jidro/jwm/blob/master/.jwm/keys "keys")为本人根据`antiX`中`jwm`桌面环境快捷键和`Puppy Linux`中`jwm`桌面环境快捷键所配置的`jwm`桌面环境快捷键配置文件。 </br>
    
  - [`.jwm/menu`](https://github.com/jidro/jwm/blob/master/.jwm/menu "menu")为本人根据`antiX`中`jwm`桌面环境菜单和`Puppy Linux`中`jwm`桌面环境菜单所配置的`jwm`桌面环境菜单配置文件。 </br>
    
  - [`.jwm/menuheights`](https://github.com/jidro/jwm/blob/master/.jwm/menuheights "menuheights")为`Puppy Linux`的菜单高亮配置文件。 </br>
    
  - [`.jwm/preferences`](https://github.com/jidro/jwm/blob/master/.jwm/preferences "preferences")为本人根据`antiX`中`jwm`桌面环境`preferences`和`Puppy Linux`中`jwm`桌面环境`preferences`所配置的`jwm`桌面环境`preferences`配置文件。 </br>
    
  - [`.jwm/startup`](https://github.com/jidro/jwm/blob/master/.jwm/startup "startup")为本人所设定的开机自启动软件的配置文件。 </br>
    
  - [`.jwm/tray`](https://github.com/jidro/jwm/blob/master/.jwm/tray "tray")为本人根据`antiX`中`jwm`桌面环境任务栏和`Puppy Linux`中`jwm`桌面环境任务栏所配置的`jwm`桌面环境任务栏配置文件。 </br>
    

---

若喜欢该仓库中的内容，可以留下您的小星星嘛，⭐ </br>

感谢您的喜欢~ </br>

---

### 免责声明：

> 此为本人学习使用。 </br>
> 
> 由此提供对您的网站或计算机造成严重后果的本站概不负责。 </br>
> 
> 此为纯属个人学习使用，禁止任何机构及个人将此系统作为商业用途！ </br>
> 
> 禁止修改并盗用他人名义在网上传播！ </br>
> 
> 请在体验试用24小时之内删除销毁！ </br>
> 
> 若同意以上条款，方可对此进行下载使用！ </br>
> 
> 若已下载此中任何，即视为同意以上条款！ </br>
> 
> 若有侵犯行为，请联系本人删除。 </br>

---

## English description：

**`JWM`** (`Joe's Window Manager`) is a lightweight [window manager](https://wiki.archlinux.org/title/Window_manager "Window manager") for [`Xorg`](https://wiki.archlinux.org/title/Xorg "Xorg") written in [`C`](https://en.wikipedia.org/wiki/C_(programming_language) "wikipedia:C (programming language)"). </br>

It is under active development and maintained by [`Joe Wingbermuehle`](https://joewing.net/about.html). </br>

This repository is modified by me from the `jwm` profile of `antiX` and the `jwm` profile of `Puppy Linux`. </br>

It is already in use, but it is not certain that using this configuration on other computers will be any different. </br>

---

### Instructions：

- ① Use the following command to copy the `jwm` configuration file you want to use in the warehouse to the `~/` (user`s home folder)： </br>
  
  ```shell
  $ cp -rfpv .jwmrc ~/
  ```
  
  > **Be Careful：** </br>
  > 
  > ① If you want to use the `jwm` configuration files of other distributions, you need to rename the other `jwm` configuration files to `. jwmrc`. You can select any of the `jwm` configuration files. </br>
  > 
  > ② [`. jwmrc previous puppet example`](https://github.com/jidro/jwm/blob/master/.jwmrc-previous-puppy-example ".jwmrc-previous-puppy-example") and [`. jwmrc tray puppet example`](https://github.com/jidro/jwm/blob/master/.jwmrc-tray-puppy-example ".jwmrc-tray-puppy-example") are not `jwm` main configuration files. These two configuration files are `previous` and` tray `configuration files of the` jwm `desktop environment in` puppy Linux `. </br>
  
- ② Restart the `jwm` desktop environment to use the `jwm` desktop environment under the configuration file. </br>
  
- ③ Enjoy it. </br>
  

---

### Document description：

- [`.jwmrc`](https://github.com/jidro/jwm/blob/master/.jwmrc ".jwmrc") - It is the main configuration file of the `jwm` desktop environment I am using. </br>
  
- [`.jwmrc-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-antix-example ".jwmrc-antix-example") - It is the main configuration file of the `jwm` desktop environment in `antiX`. </br>
  
- [`.jwmrc-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-puppy-example ".jwmrc-puppy-example")It is the main configuration file of the `jwm` desktop environment in `Puppy Linux`. </br>
  
- [`.jwmrc-numix-bevel-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-numix-bevel-antix-example ".jwmrc-numix-bevel-antix-example")/[`.jwmrc-numix-square-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-numix-square-antix-example ".jwmrc-numix-square-antix-example") - These two configuration files are the main configuration files of the theme `jwm` desktop environment `numix` in `antiX`. </br>
  
- [`.jwmrc-papirus-antix-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-papirus-antix-example ".jwmrc-papirus-antix-example") - It is the main configuration file of the theme `jwm` desktop environment `papirus` in` antiX `. </br>
  
- [`.jwmrc-previous-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-previous-puppy-example ".jwmrc-previous-puppy-example") - It is the `previous` configuration file of the` jwm `desktop environment in` Puppy Linux `. </br>
  
- [`.jwmrc-tray-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwmrc-tray-puppy-example ".jwmrc-tray-puppy-example") - It is the `tray` configuration file of the `jwm` desktop environment in `Puppy Linux`. </br>
  
- `.jwm`folder - All files in the folder are secondary configuration files of the `jwm` desktop environment, which are used together with the main configuration file of the `jwm` desktop environment. </br>
  
  - [`.jwm/theme`](https://github.com/jidro/jwm/blob/master/.jwm/theme "theme") - This is the configuration file for setting the `jwm` theme. </br>
    
  - [`.jwm/themes-list`](https://github.com/jidro/jwm/blob/master/.jwm/themes-list "themes-list") - The list configuration file for selecting the `jwm` theme in the Start menu. </br>
    
  - [`.jwm/themes`](https://github.com/jidro/jwm/tree/master/.jwm/themes "themes")folder - The folder is an optional folder for all topics of `jwm`. </br>
    
  - [`.jwm/jwmrc-personal-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal-puppy-example "jwmrc-personal-puppy-example")/[`.jwm/jwmrc-personal2-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal2-puppy-example "jwmrc-personal2-puppy-example")/[`.jwm/jwmrc-personal_old-puppy-example`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-personal_old-puppy-example "jwmrc-personal_old-puppy-example") - These three files are the `personal` configuration files of the `jwm` desktop environment in `Puppy Linux`. </br>
    
  - [`.jwm/personal`](https://github.com/jidro/jwm/blob/master/.jwm/personal "personal") - It is the `personal` configuration file of `antiX`. </br>
    
  - [`.jwm/jwmrc-theme`](https://github.com/jidro/jwm/blob/master/.jwm/jwmrc-theme "jwmrc-theme") - It is the theme configuration file of the `jwm` desktop environment in `Puppy Linux`. </br>
    
  - [`.jwm/keys`](https://github.com/jidro/jwm/blob/master/.jwm/keys "keys") - It is the `jwm` desktop environment shortcut key configuration file configured according to the `jwm` desktop environment shortcut key in `antiX` and the `jwm` desktop environment shortcut key in `Puppy Linux`. </br>
    
  - [`.jwm/menu`](https://github.com/jidro/jwm/blob/master/.jwm/menu "menu") - It is the `jwm` desktop environment menu configuration file configured for me according to the `jwm` desktop environment menu in `antiX` and the `jwm` desktop environment menu in `Puppy Linux`. </br>
    
  - [`.jwm/menuheights`](https://github.com/jidro/jwm/blob/master/.jwm/menuheights "menuheights") - Highlight the configuration file for the menu of `Puppy Linux`. </br>
    
  - [`.jwm/preferences`](https://github.com/jidro/jwm/blob/master/.jwm/preferences "preferences") - It is the `jwm` desktop environment `preferences` configuration file configured according to` jwm `desktop environment` preferences` in `antiX` and `jwm` desktop environment `preferences` in` Puppy Linux `. </br>
    
  - [`.jwm/startup`](https://github.com/jidro/jwm/blob/master/.jwm/startup "startup") - It is the configuration file of the startup software set by me. </br>
    
  - [`.jwm/tray`](https://github.com/jidro/jwm/blob/master/.jwm/tray "tray") - It is the configuration file of the `jwm` desktop environment task bar configured for me according to the `jwm` desktop environment task bar in `antiX` and the `jwm` desktop environment task bar in `Puppy Linux`. </br>
    

---

If you like the content in the warehouse, you can leave your little star, ⭐ </br>
Thank you for your liking~ </br>

---

### Disclaimer：

> This is for my study and use. </br>
> 
> The website provided herein shall not be responsible for any serious consequences to your website or computer. </br>
> 
> This is for personal use. </br>
> 
> Any organization or individual is prohibited from using this system for commercial use! </br>
> 
> It is forbidden to modify and use the name of others to spread online! </br>
> 
> Please delete and destroy within 24 hours of trial! </br>
> 
> If you agree to the above terms, you can download and use this! </br>
> 
> If you download any of this, you agree to the above terms! </br>
> 
> If there is any violation, please contact me to delete. </br>
