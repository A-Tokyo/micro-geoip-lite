# micro-geoip-lite

> 🌍 Small microservice that geo looks up an IP.

[![codecov](https://codecov.io/gh/A-Tokyo/micro-geoip-lite/branch/main/graph/badge.svg)](https://codecov.io/gh/A-Tokyo/micro-geoip-lite)

# Usage

- [https://geoip-lite.now.sh/?ip=207.97.227.239](https://geoip-lite.now.sh/?ip=207.97.227.239)
```js
{
  ip: '207.97.227.239', // if ip param was not provided, this defaults to request.ip
  range: [ 3479298048, 3479300095 ],
  country: 'US',
  region: 'TX',
  eu: '0',
  timezone: 'America/Chicago',
  city: 'San Antonio',
  ll: [ 29.4969, -98.4032 ],
  metro: 641,
  area: 1000,
  error: 'Error text', // only exists if an error happened
}
```

## Automation Note
- This repo is auto maintained by bots. For example: dependabot opens weekly PRs to upgrade dependencies that are auto merged if the tests pass.
- This will keep the repo up to date with minimal human interaction.

# Credits

- [bluesmoon/node-geoip](https://github.com/bluesmoon/node-geoip) 
- [zeit/micro](https://github.com/zeit/micro) 

Proudly hosted on [now](https://zeit.co/now)
