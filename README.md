# ![LOGO](logo.png) City Context **flow**ground Connector

## Description

A generated **flow**ground connector for the City Context API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/citycontext.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:39:58+03:00

## API Description

City Context provides a straightforward API to access UK Open Data: crime statistics, schools, demographics and more.

## Authorization

Supported authorization schemes:
- API Key
## Actions

### Query by coordinates (SRID 4326 - decimal degrees)

*Tags:* `citycontext`

#### Input Parameters
* `lat` - _required_ - Latitude
* `lon` - _required_ - Longitude
* `school_search_radius` - _optional_ - Search radius for schools, in metres, between 100 and 4000
* `park_search_radius` - _optional_ - Search radius for parks, in metres, between 100 and 2000

### Query by postcode

*Tags:* `citycontext`

#### Input Parameters
* `postcode` - _required_ - Postcode
* `school_search_radius` - _optional_ - Search radius for schools, in metres, between 100 and 4000
* `park_search_radius` - _optional_ - Search radius for parks, in metres, between 100 and 2000

### Get usage in current month

*Tags:* `citycontext`

## License

**flow**ground :- Telekom iPaaS / citycontext-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
