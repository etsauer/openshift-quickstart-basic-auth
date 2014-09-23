# Basic Auth Quickstart #

Provides simple Basic Authentication in a Java App for Openshift.

## Instructions ##

```bash
$ rhc create-app basicauthtest jbosseap-6 --from-url=https://github.com/etsauer/openshift-quickstart-basic-auth.git
```

Navigate to your app at basicauthtest-mynamespace.rhcloud.com (or whatever your Openshift server is). You will get a login pop-up. Username/password is demo/demo.
