# Homey.Glue
Homey Glue Lock app support.

*Not a official support.*


## How to get started

The app requires an Auth-key. See the following to 


1. POST https://user-api.gluehome.com/v1/api-keys
Auth: Basic-auth: <username> <password>
                Username: prob. your email
                Password: Your account password.
Body: {
    "name": "HomeyKey",
    "scopes": [
        "events.read",
        "locks.read",
        "locks.write"
    ]
}


When this method succceed, you will receive a Api Key.