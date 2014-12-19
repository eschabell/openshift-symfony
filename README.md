Symfony on OpenShift Express
============================
This git repository helps you get up and running quickly w/ a Sympfony installation
on OpenShift Express.


Install with one click
----------------------
[![Click to install OpenShift](http://launch-shifter.rhcloud.com/launch/light/Click to install.svg)](https://openshift.redhat.com/app/console/application_type/custom?&cartridges[]=php-5.3&initial_git_url=https://github.com/eschabell/openshift-symfony.git&name=symfonyphp)


That's it, you can now checkout your application at:

    http://sympfonyphp-$your_domain.rhcloud.com

NOTES:

GIT_ROOT/.openshift/action_hooks/build:
  This has a few lines to ensure that the cache dir exists and is writable for the web server.

Security:
Nothing has been done to secure this installation.
