# ![LOGO](logo.png) API Discovery Service **flow**ground Connector

## Description

A generated **flow**ground connector for the API Discovery Service API (version v1).

Generated from: https://api.apis.guru/v2/specs/googleapis.com/discovery/v1/swagger.json<br/>
Generated at: 2019-05-23T12:13:19+03:00

## API Description

Provides information about other Google APIs, such as what APIs are available, the resource, and method details for each API.

## Authorization

This API does not require authorization.

## Actions

### Retrieve the list of APIs supported at this endpoint.

*Tags:* `apis`

#### Input Parameters
* `name` - _optional_ - Only include APIs with the given name.
* `preferred` - _optional_ - Return only the preferred version of an API.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

### Retrieve the description of a particular version of an api.

*Tags:* `apis`

#### Input Parameters
* `api` - _required_ - The name of the API.
* `version` - _required_ - The version of the API.
* `key` - _optional_ - API key. Your API key identifies your project and provides you with API access, quota, and reports. Required unless you provide an OAuth 2.0 token.
* `oauth_token` - _optional_ - OAuth 2.0 token for the current user.
* `prettyPrint` - _optional_ - Returns response with indentations and line breaks.
* `quotaUser` - _optional_ - An opaque string that represents a user for quota purposes. Must not exceed 40 characters.
* `userIp` - _optional_ - Deprecated. Please use quotaUser instead.

## License

**flow**ground :- Telekom iPaaS / googleapis-com-discovery-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
