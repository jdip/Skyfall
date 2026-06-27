# Foundry Server

## Access

- Preferred SSH target: `jdipaolo@clawdius`
- Legacy/direct target: `jdipaolo@100.103.211.98`
- Server hostname verified on 2026-06-27: `clawdius`
- Foundry files live under `/srv`.
- Passwordless `sudo` for `jdipaolo` was verified on 2026-06-27.

Connect with:

```sh
ssh jdipaolo@clawdius
```

## Instances

### Test

- Service: `foundryvtt@foundry.service`
- Status checked active on 2026-06-27.
- Foundry install: `/srv/foundry`
- Data path: `/srv/foundry-data`
- World path: `/srv/foundry-data/Data/worlds/foundry-test`

### Production Skyfall

- Service: `foundryvtt@starfall.service`
- Status checked active on 2026-06-27.
- Foundry install: `/srv/starfall`
- Data path: `/srv/starfall-data`
- World path: `/srv/starfall-data/Data/worlds/starfall`

The production service, install folder, data folder, and world are still named `starfall`, but the campaign is now called Skyfall.

## Systemd

The shared service template is:

```sh
/etc/systemd/system/foundryvtt@.service
```

The template starts each instance with:

```sh
/opt/node-v22/bin/node /srv/%i/resources/app/main.js --dataPath=/srv/%i-data
```

Useful commands:

```sh
sudo systemctl status foundryvtt@foundry.service
sudo systemctl status foundryvtt@starfall.service
sudo systemctl restart foundryvtt@foundry.service
sudo systemctl restart foundryvtt@starfall.service
```

## Workflow

Make and validate changes against the test instance first:

```sh
/srv/foundry
/srv/foundry-data
```

Promote deliberate, backed-up changes to production:

```sh
/srv/starfall
/srv/starfall-data
```
