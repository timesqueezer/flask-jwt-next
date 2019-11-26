# Changelog

## 1.0.0 (November 26, 2019)

- Fixed a bug where the identity of a user caused an exception when the object is a dictionary.
- Re-build the project for my personal needs

## 0.3.2 (November 3, 2015)

- Fixed an Authorization header conditional bug

## 0.3.1 (October 26, 2015)

- Fix a bug with `auth_request_handler`
- Deprecate `auth_request_handler`

## 0.3.0 (October 15, 2015)

*NOTE:* This release includes many breaking changes

- Fix major implementation issue with encoding/decoding tokens
- Changed new configuration options to align with PyJWT
- Changed `current_user` to `current_identity`

## 0.2.0 (June 10, 2014)

- Fixed an issue where `current_user` was not None
- Added a response handler hook to be able to adjust auth response(s)
- Removed the configurable handlers in favor of decorators
- Removed pyjwt dependency


## 0.1.0 (March 5, 2014)

- Initial release
