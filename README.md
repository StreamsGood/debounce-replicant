# debounce-replicant

[![Greenkeeper badge](https://badges.greenkeeper.io/StreamsGood/debounce-replicant.svg)](https://greenkeeper.io/)
[![Build Status](https://travis-ci.org/StreamsGood/debounce-replicant.svg?branch=master)](https://travis-ci.org/StreamsGood/debounce-replicant)

```sh
bower install StreamsGood/debounce-replicant --save
```

Adds a delay to assigning a Replicant's new local value when a server change is emit.

Personally I use this with frontend assets to prevent showing every character change when I don't want to have manual save buttons.

```html
<debounce-replicant replicant-name="myReplicantName" replicant-bundle="myReplicantBundle" value="{{localValue}}" wait="500"></debounce-replicant>
```
_**wait** in ms_