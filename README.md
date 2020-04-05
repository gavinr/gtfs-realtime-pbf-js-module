# GTFS Realtime - PBF JavaScript Module

I took the [published GTFS Realtime .proto schema file](https://developers.google.com/transit/gtfs-realtime/gtfs-realtime-proto) and ran it through the [PBF package](https://www.npmjs.com/package/pbf) and am hosting it on a CDN so you don't have to!

## Use them

### NPM

```
npm i gtfs-realtime-pbf-js-module
```

### CDN

```
<script src="https://unpkg.com/gtfs-realtime-pbf-js-module@1.0.0/gtfs-realtime.browser.proto.js"></script>
```

([example of usage](https://codepen.io/gavinr/pen/XWbzGMW?editors=0010))

## How these were generated

1. Download the [published GTFS Realtime .proto schema file](https://developers.google.com/transit/gtfs-realtime/gtfs-realtime-proto)
2. `npm install pbf -g`
3. `pbf gtfs-realtime.proto > gtfs-realtime.browser.proto.js`
4. `pbf gtfs-realtime.proto --browser > gtfs-realtime.browser.proto.js`
