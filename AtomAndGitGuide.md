## Atom Installation and Run Guide

  1. Download Atom ide from [here](https://atom.io/) . Can be installed on different Platforms (linux / Windows)
  2. Create a folder for git in any drive. Install git dependencies by running
    1.  apt-get update
    2.  apt-get install git-core
    3.  git --version ( For Verfication of git install)
  3. Run the command git clone https://github.com/SuprithRamesh/AdvancedSoftwareEngineering.git
  4. Go to Atom -> File -> Add Project Folder -> (Traverse to git folder location) -> Click Ok
  5. Atom with git integration is completed

**Common Git commands**
  1. git clone
  2. git pull ( For getting the latest updates from Origin - Origin is online master git)
  3. git push ( For pushing local contents to Origin )
  4. git commit ( For commiting changes to local git )
  5. git add .  ( For adding files to local git ) or git add {filename}  

**Order of git commands for normal code push**
  - git pull ( keep a backup of your local work and get latest code from Origin )
  - Make code changes in Atom to required files
  - git add .
  - git commit ( Add proper commments and Click Ctrl+X )
  - git push ( You need to put your credentials here)
