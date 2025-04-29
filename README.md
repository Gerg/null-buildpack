# Cloud Foundry Null Buildpack
Cloud Foundry buildpack that does nothing. Embrace the void!

## Usage

Push an app using the null buildpack:
```
cf push null -b https://github.com/Gerg/null-buildpack.git -c "<start command>"
```

Make sure to supply a start command, because the null buildpack certainly wont.
