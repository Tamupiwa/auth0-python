# Auth0-python

Auth0-python is a custom python wrapper for the Auth0 Management API with automatic token refreshing

## Installation

Use the package manager [pip] Only compatable with python 3
```bash
Available on pypi soon
```

## Dependencies
```
import auth0
import requests

```

## Usage

```python
client_id = os.environ.get('auth0_client_id')
client_secret = os.environ.get('auth0_client_secret')
ath = Auth0ManagmentAPI(client_id, client_secret)
users = ath.list_users()

```

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)
