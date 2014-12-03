
jpa-connectivity
-------------
If you're seeing this you've successfully created a project with skeletor-tomcat-war-archetype.

Make sure you've pushed your app to github.
```
git init
git add .
git commit -m "initial commit"
git remote add origin git@github.groupondev.com/[my group]/[my project].git
git push -u origin master
```

Do a test run to make sure it works:
```
mvn jetty:run
```

Browse to a few urls:

http://localhost:8080/grpn/healthcheck

http://localhost:8080/grpn/status

http://localhost:8080/grpn/git-status


Read the skeletor-tomcat-war-archetype docs for how to configure and deploy your app.
https://github.groupondev.com/skeletor/skeletor-tomcat-war-archetype

Also, checkout the docs on skeletor-servlet and skeletor-core which provide the skeletor functionality:
https://github.groupondev.com/skeletor/skeletor-servlet

https://github.groupondev.com/skeletor/skeletor-core



