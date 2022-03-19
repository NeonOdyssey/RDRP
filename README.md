# Red - Roleplay - The only roleplay framework you need for RedM

![RDRP - Banner with spinning wheel](https://github.com/NeonOdyssey/RDRP/blob/main/banner.png)

![](https://img.shields.io/github/languages/code-size/NeonOdyssey/RDRP) ![](https://img.shields.io/github/downloads/NeonOdyssey/RDRP/total) ![](https://img.shields.io/github/v/release/NeonOdyssey/RDRP) ![](https://img.shields.io/github/issues/NeonOdyssey/RDRP)

![](https://img.shields.io/discord/766050580296106045?label=Discord&logo=discord&logoColor=white) ![](https://img.shields.io/github/stars/NeonOdyssey/RDRP)

## 1. Features
- Queue system with priority levels and crash prio.
- Custom loading screen (will display when loading / setting up players charaters)
- Saves character and player data within a mysql database
- DBNO (Down But Not Out) and revive system with health saving on logout
- Support for multiple characters (max of 5) under one player
- Economy with Dollars, Cents and state-wide banks
- Permission groups for staff members and VIP users
- Job system with job levels
- Character inventories with bank lock boxes
- GUI with modular notifications

## 2. Requirements
[mysql-async-temporary](https://github.com/amakuu/mysql-async-temporary) (Must rename to `mysql-async`)

## 3. Installation
For all installation procedures you must have git installed:

- **Linux:** ` sudo apt-get update ; sudo apt-get -y install git-all `

- **Windows:** [Download](https://git-scm.com/download/win)

Once Git is installed you can either follow the indepth tutorial on our docs https://rdrp.pixelperfect.gg/docs/core/install

Or follow the suitable short guide bellow:

### Linux (ubuntu)
1. Open the Linux terminal and navigate to the `server-data/resources` folder

2. ```bash
    $ git clone https://github.com/NeonOdyssey/RDRP [RDRP]
    ```

3. ```bash
    $ ln -s ./[RDRP]/rdrp_resources.cfg rdrp_resources.cfg
    ```

4. Change `set mysql_connection_string "server=localhost;userid=root;password="` in `rdrp_resource.cfg` to your MySQL server login details. `rdrp_db` will install the database and tables automatically.

5. In `server.cfg` make sure you execute the rdrp resource file by writing `exec rdrp_resource.cfg` after the default & main resources.

### Windows (win10)
1. Open your favorite windows terminal and navigate to the `server-data/resources` folder

2. ```bash
    $ git clone https://github.com/NeonOdyssey/RDRP [RDRP]
    ```

3. Move `[RDRP]/rdrp_resources.cfg` to the `server-data` folder

4. Change `set mysql_connection_string "server=localhost;userid=root;password="` in `rdrp_resource.cfg` to your MySQL server login details. `rdrp_db` will install the database and tables automatically.

5. In `server.cfg` make sure you execute the rdrp resource file by writing `exec rdrp_resource.cfg` after the default & main resources.

## 4. Documentation
Any issues with the installation or usage of RDRP scripts please head over to our docs for guidance https://docs.rdrp.gg/

## 5. Credits
Author : [@NeonOdyssey](https://github.com/NeonOdyssey/)
