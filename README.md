# openelis-sso-keyloak

### Running OpenELIS Global2 and KeyCloak

    docker-compose up -d

| Instance     |                   URL                   | credentials (user : password) |
| ------------ | :-------------------------------------: | ----------------------------: |
| Key Cloak    | http://localhost:8080                   |            admin: admin.      |
| OpenELIS     |     https://localhost/                |            admin: adminADMIN! |


### Logging in OpenELIS via Single Sign On with Key Cloak

1. Login page will be https://localhost

1. Identify the Single Sign On Button and click it

1. Fill in username and password below

         jdoe : password


1. You should be redirected to the OpenELIS Global2 home page