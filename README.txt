FROST PLUGIN v2.0 — Paper 1.21.11 / Java 21

Build using the included .github/workflows/build.yml GitHub Action.
Upload src, build.gradle.kts, settings.gradle.kts, and the workflow once.
GitHub Actions -> Build Frost Plugin -> Run workflow.
Download the resulting artifact, unzip it and put the JAR in the Paper plugins folder.
Remove older versions of PunchSnowball/Frost from plugins to avoid command conflicts.

Commands:
/frost             OP-only weapon collection menu (includes Frozen Shield of Defiance)
/frost config      OP-only in-game settings GUI
/frost trust NAME  Trust another player (one way)
/frost untrust NAME
/frost trusted
/frost reload      OP-only config reload

Frozen Shield of Defiance: sneak + right click with the shield (main or offhand)
to activate 10 seconds of stun immunity. Reflect knockback to a nearby attacker
when actively blocking with your raised shield. 60 second ability cooldown.
Knockback is approximate and terrain-dependent.

When a weapon cooldown expires you will see a chat message only if holding
that weapon in main hand or offhand at the instant it expires.
Change shield/weapon settings via /frost config without rebuilding the plugin.
