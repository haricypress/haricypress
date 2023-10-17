1)
note : for "n" no.of cypress projects, install cypress "n" no.of times

first time install cypress,

1) create empty folder for cypress project
2) open cypress project folder in CMD prompt, follow below commands
    
    project address in local PC   :   D:\cypress_pro\cypress
    location in  CMD  promt        :  D:\cypress_pro\cypress>

3) CMD prompt commands :
command 1 : npm init  ( "package.json"  file will create )
command 2 : npm install cypress  

optional  : to remove or add pluggins based on "package.json" file
command   :  npm install 
"package.json"  file is showing all installed packages

=========================================================================================
2)
if any problem occured in cypress installation,
clear all previously installed cypress, then install latest cypress
run below 3 commands,
in CMD prompt open project folder,
command 1 (to clear all previously installed cypress)  :  npx cypress cache clear
command 2  (to install latest cypress version ) :  npx cypress install
command 3 (to initiate cypress)      :     npm init

===========================================================================================
3)
cypress-xpath  (external pluggin)   :
command to install   :  npm install -D cypress-xpath

add      require('cypress-xpath');      statement in       "project_folder\cypress\support\e2e.js"     file

### Hi there 👋

<!--
**haricypress/haricypress** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
