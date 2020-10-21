# keycloak-alma-theme

An ALMA theme for Keycloak, based on the 
[ALMA UI Guidelines](https://confluence.alma.cl/pages/viewpage.action?spaceKey=ICT&title=ALMA+Web+UI+Guidelines).

See https://www.keycloak.org/docs/latest/server_development/#_themes

## Build
Build with
```
cd .../keycloak-alma-theme ; mvn clean install
```

## Install
Copy the generated jarfile to Keycloak's _standalone/deployments/_
directory.  
You don't need to restart the server.
