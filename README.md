project starts now-----
1. Go to github → code - Copy http→Link.
2. Go to jenkins dashboard → New item
item name - project1 → free style project
0K
3. Go to source Code Mgt → Git→ paste repo
URL
4. Go to build→ add build step →Invoke top level maven targets.
→ Goals → clean package.
J- Go to post-build actions → add post-build action
deploy war/Ear to a container
6.War/ear files->column  context path? 
 Target/*. war             myweb
* Add Container → Tomat 9x. Remote.
 but in real-time Tomcat 10. will bethere!.
* credentials → Add → Jenkins→username tomcat
password→ tomcat
→ Telling the credentials like who is tomcat
user to jenkins
* Copy tomcat url & paste it in Jenkins at Tomcat URL till 8080.
* Apply → save.
* Build Now
* Refersh tomcat page
my web → will be there → clickonit
GANA TECH APP VERSION - 21000
display
