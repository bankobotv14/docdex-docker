# docdexdocker
Docker images for [PiggyPiglet/DocDex](https://github.com/PiggyPiglet/DocDex/)
DocDex license: https://github.com/PiggyPiglet/DocDex/blob/master/LICENSE.md

# Setup
- Clone this repo
- Download Docs and extract them to `doc-mirror/` folder (see [here](#doc-downloads))
- Adjust `config.json`
- Run `docker-compose up -d`

# Doc mirror server
To avoid getting ipblocked from doc sites (because of multiple concurrent requests) a mirror sserver is running at `http://mirror:8080` within the Docker container.
You can modify that servers files in the `doc-mirror` directory

# Images
Docker images can be found here: https://github.com/orgs/bankobotv14/packages/container/package/docdexdocker

# Doc Downloads:
JDK: https://stackoverflow.com/a/6987039/10234040

Spigot: https://hub.spigotmc.org/nexus/content/repositories/snapshots/org/spigotmc/spigot-api/1.16.5-R0.1-SNAPSHOT/

JDA: https://jcenter.bintray.com/net/dv8tion/JDA/4.2.0_227/JDA-4.2.0_227-javadoc.jar