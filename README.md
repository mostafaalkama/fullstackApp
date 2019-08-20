# fullstackApp
1 create compte heroko 
2 download heroku cli 
3 create project add addons mysql 
4 heroku login 
5 heroku config --app   alkamaapp
6 get url mysql and password and login  and put it i application.properties 
7 install mysql workbench and 
8 run backend 
9 create file with no extension and add this :: 
web: java $JAVA_OPTS  -jar target/ppmtool-0.0.1-SNAPSHOT.jar -Dserver.port=$PORT $JAR_OPTS
10 go to heroku > myapp > deploy > github and add you project and deploy it 
11 add your app to package.json (https://alkamaapp.herokuapp.com/)
12 create file static inside in resources (backend ) 
13 npm run build and copy the build in static file created in backend push commit and redploy 
14 happy app  
