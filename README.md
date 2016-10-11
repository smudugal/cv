# CV

Go To <a href="http://samyukta.cfapps.io/" target="_blank">samyukta.cfapps.io</a>.to see my CV!!

This is an app for my curriculum vitae. It is a static file website.

The app is currently hosted on [Pivotal Cloud Foundry](https://pivotal.io/platform) PaaS.

## Template Design

The design for this website comes from [Nathan Brown hosted on wegraphics.net](http://wegraphics.net/downloads/one-a-free-one-page-web-resume-template/)

## Pushing the app onto Cloud Foundry

```
cd HTML
cf push -b staticfile_buildpack APP_NAME
```

### Helpful Links
[How to configure and push a static website?](http://docs.cloudfoundry.org/buildpacks/staticfile/)
