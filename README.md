# osnodejs
Nodejs template to deploy on open shift v3


##Install open shift


2) login to your oc 
    oc login <your openshift account url>

3) git add --all
   git commit -m "nodejs commit"
   git push

4) create an app on os

5) oc project  <project name>

6) oc start-build  <projectname>