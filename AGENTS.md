# Skyfall / Foundry Campaign Notes

This workspace is a lightweight notes and working area for TTRPG campaign support, especially Foundry VTT work for the campaign currently called Skyfall.

## Foundry Host

- Preferred SSH target: `jdipaolo@clawdius`
- Legacy/direct target: `jdipaolo@100.103.211.98`
- Connectivity checked on 2026-06-27 with:
  `ssh jdipaolo@clawdius`
- SSH should work without a password.
- Passwordless `sudo` for the remote user was verified on 2026-06-27.
- Foundry files live under `/srv`.

## Foundry Instances

- Test instance:
  - Service: `foundryvtt@foundry.service`
  - Status checked active on 2026-06-27.
  - Foundry install: `/srv/foundry`
  - Data path: `/srv/foundry-data`
  - Test world: `/srv/foundry-data/Data/worlds/foundry-test`
- Production Skyfall instance:
  - Service: `foundryvtt@starfall.service`
  - Status checked active on 2026-06-27.
  - Foundry install: `/srv/starfall`
  - Data path: `/srv/starfall-data`
  - Campaign world: `/srv/starfall-data/Data/worlds/starfall`
- The production service, install folder, data folder, and world are still named `starfall`, but the campaign was renamed to Skyfall.
- Shared Foundry service template:
  `/etc/systemd/system/foundryvtt@.service`
- The service template runs `/opt/node-v22/bin/node /srv/%i/resources/app/main.js --dataPath=/srv/%i-data`.

Default workflow:

1. Make and validate changes in the test instance at `/srv/foundry` with data in `/srv/foundry-data`.
2. Once the change is ready, copy or promote it to the production instance at `/srv/starfall` with data in `/srv/starfall-data`.
3. Treat production changes as deliberate operations. Prefer checking current files and making backups before replacing campaign data.

Useful remote commands:

- `ssh jdipaolo@clawdius`
- `sudo systemctl status foundryvtt@foundry.service`
- `sudo systemctl status foundryvtt@starfall.service`
- `sudo systemctl restart foundryvtt@foundry.service`
- `sudo systemctl restart foundryvtt@starfall.service`

## Local Reference Files

- Local Daggerheart rulebook PDF:
  `Daggerheart_Core_Full_Art_and_Printer_Friendly_Cards_-_9-09-25.pdf`

## Remote Reference Files

Found in the remote home folder:

- `/home/jdipaolo/Daggerheart_Core_Full_Art_and_Printer_Friendly_Cards_-_9-09-25.pdf`
- `/home/jdipaolo/Daggerheart - Ritual Magic Rules.pdf`

If another Daggerheart reference is needed later, check the remote home folder first.
