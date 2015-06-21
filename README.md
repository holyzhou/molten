# Molten - Salt API frontend powered by React.js

##Features:

* Full access to all salt clients supported via Rest API
* Simple deployment: no intermediate Python / Node.js application required
* Live updates, i.e. for events
* No page reloads / Single page app 

## ToDo
- Special format for highstate output
- Styling
- Minions, Jobs and Event tab
- ...

## Deployment

* install node modules: `npm install`
* build application bundle: `npm build`
* deploy bundle on salt master/api
* configure salt-api (see samples in dev/salt)

## Development
* install vagrant / virtualbox
* start webpack bundler `npm dev`
* `vagrant up` then connect to 192.168.42.42:8000 as test / molten
