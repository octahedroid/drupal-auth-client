# Drupal Auth Client

## Usage

### import library
```javascript
import drupalAuthClient from "drupal-auth-client"
```

### Using `client_credentials` 
```javascript

const client = drupalAuthClient(
  "https://drupal.site",
  "client_credentials",
  {
    clientId: "client_id",
    clientSecret: "client_secret",
  },
)
```

### Using `password` 
```javascript

const client = drupalAuthClient(
  "https://drupal.site",
  "password",
  {
    username: "username",
    password: "password",
    clientId: "client_id",
    clientSecret: "client_secret",
  },
)
```