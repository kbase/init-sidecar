# init-sidecar
Docker config for the KBase `init-sidecar` and `install` services.

## Current Status

| Branch  | Build                                                              | Coverage                                                                         | LGTM Alerts                                                     |
| ------- | ------------------------------------------------------------------ | -------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| master  | [![KBase SDK Tests](https://github.com/kbase/init-sidecar/workflows/KBase%20SDK%20Tests/badge.svg)](https://github.com/kbase/init-sidecar/actions?query=workflow%3A%22KBase+SDK+Tests%22)  | [![codecov](https://codecov.io/gh/kbase/init-sidecar/branch/master/graph/badge.svg)](https://codecov.io/gh/kbase/init-sidecar)  | [![Total alerts](https://img.shields.io/lgtm/alerts/g/kbase/init-sidecar.svg?logo=lgtm&logoWidth=18)](https://lgtm.com/projects/g/kbase/init-sidecar/alerts/)  |


## Details

### Testing

The tests use data from KBase's CI environment. In `test_local/test.cfg`, set the following:

```
test_token={ci_dev_token}
kbase_endpoint=https://ci.kbase.us/services
auth_service_url=https://ci.kbase.us/services/auth/api/legacy/KBase/Sessions/Login
```
