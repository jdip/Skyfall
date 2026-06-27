# Skyfall / Foundry Campaign Notes

This workspace is a lightweight notes and working area for TTRPG campaign support, especially Foundry VTT work for the campaign currently called Skyfall.

## Foundry Host

- Remote host: `jdipaolo@100.103.211.98`
- SSH should work without a password.
- The remote user can run `sudo` without a password.

## Foundry Instances

- Test instance: `/srv/foundry`
- Production instance: `/srv/starfall`
- The production folder is still named `starfall`, but the campaign was renamed to Skyfall.

Default workflow:

1. Make and validate changes in the test instance at `/srv/foundry`.
2. Once the change is ready, copy or promote it to the production instance at `/srv/starfall`.
3. Treat production changes as deliberate operations. Prefer checking current files and making backups before replacing campaign data.

## Local Reference Files

- Local Daggerheart rulebook PDF:
  `Daggerheart_Core_Full_Art_and_Printer_Friendly_Cards_-_9-09-25.pdf`

## Remote Reference Files

Found in the remote home folder:

- `/home/jdipaolo/Daggerheart_Core_Full_Art_and_Printer_Friendly_Cards_-_9-09-25.pdf`
- `/home/jdipaolo/Daggerheart - Ritual Magic Rules.pdf`

If another Daggerheart reference is needed later, check the remote home folder first.
