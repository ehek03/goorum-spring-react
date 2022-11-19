```
┌───────────────────────────────────────────────┐
                                       _       
     __ _  ___   ___  _ __ _ __ ___   (_) ___  
    / _` |/ _ \ / _ \| '__| '_ ` _ \  | |/ _ \ 
   | (_| | (_) | (_) | |  | | | | | |_| | (_) |
    \__, |\___/ \___/|_|  |_| |_| |_(_)_|\___/ 
    |___/                                      
			     🌩 𝘼𝙣𝙮𝙤𝙣𝙚 𝙘𝙖𝙣 𝙙𝙚𝙫𝙚𝙡𝙤𝙥!
└───────────────────────────────────────────────┘
```

# goormIDE
Welcome to goormIDE!

goormIDE is a powerful cloud IDE service to maximize productivity for developers and teams.  
**DEVELOP WITH EXCELLENCE**  

`Happy coding! The goormIDE team`

## Spring&React Boilerplate
 * Tech
	* This project uses `Spring Boot` `React`.
 * Target
 	* Job seekers who want to study React and Spring Boot.
    * Students who want to be Full Stack Developer.
    * Those who have specific project ideas. 
 * Description
	* This Project is boilerplate for React and Spring Boot.
    * You can see how to run this project in the following topics.
    * Spring runs on 8080 port and React runs on 3000 port. You can check domain in `PROJECT > Running URL and Port`.
    * Please feel free to use it!
 * Folder Structure
 ```
/back
	/src
        /main
            /java
                /com
                    /example
                        /[name]
                            [nameController].java
                            [nameService].java
                        App.java
            /resources
        /test
    /target
/front
    /public
	/src
        /api
        /components
            [name]
        /config
        App.js
    .env.development
 ```
 
## 🎨 Usage      
1. Check URL and Port
   1. Click `PROJECT > Running URL and Port` on top menu bar.
   2. Check that domain is registered on the 3000 port and 8080 port.
   3. If not, register the domain.
   
2. Check Dependencies.
   1. Check that `front/node_modules` is installed.
   2. If not, `npm install` into terminal.
   
3. Run Project
   * Using script
       * `./start.sh` into terminal.
   * Direct input
       * `cd front && npm run start`
       * `cd back && ./mvnw spring-boot:run`

4. Exit Project
    * Using script
        * `./exit.sh` into terminal
    * Direct input
        * Check port with `netstat -nlp | grep :3000`
        * `kill -9 ${port}`
        * Check port with `netstat -nlp | grep :8080`
        * `kill -9 ${port}`


## 🔧 Tip & Guide

* Command feature
	* You can simply run your script using the shortcut icons on the top right.
	* Check out `PROJECT > Common/Build/Run/Test/Find Command` in the top menu.
	
* Get URL and Port
	* Click `PROJECT > URL/PORT` in top menu bar.
	* You can get default URL/Port and add URL/Port in the top menu.

* Useful shortcut
	
| Shortcuts name     | Command (Mac) | Command (Window) |
| ------------------ | :-----------: | :--------------: |
| Copy in Terminal   | ⌘ + C         | Ctrl + Shift + C |
| Paste in Terminal  | ⌘ + V         | Ctrl + Shift + V |
| Search File        | ⌥ + ⇧ + F     | Alt + Shift + F  |
| Terminal Toggle    | ⌥ + ⇧ + B     | Alt + Shift + B  |
| New Terminal       | ⌥ + ⇧ + T     | Alt + Shift + T  |
| Code Formatting    | ⌥ + ⇧ + P     | Alt + Shift + P  |
| Show All Shortcuts | ⌘ + H         | Ctrl + H         |

## 💬 Support & Documentation

Visit [https://ide.goorm.io](https://ide.goorm.io) to support and learn more about using goormIDE.  
To watch some usage guides, visit [https://help.goorm.io/en/goormide](https://help.goorm.io/en/goormide)
