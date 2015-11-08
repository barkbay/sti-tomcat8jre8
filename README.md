# sti-tomcat8jre8
An attempt to create Tomcat 8 Openshift Image

This work is based on https://github.com/openshift/sti-wildfly maintained by RedHat

Build an image
---------------
```
$ s2i build git://github.com/bparees/openshift-jee-sample barkbay/tomcat8jre8 tomcattest
```

Run the image
-------------

```
$ docker run --rm -p 80:8080 tomcattest 
```

Then point your browser to http://localhost

