# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [0.1.15](https://github.com/DavidWells/analytics/compare/analytics@0.1.14...analytics@0.1.15) (2019-07-19)

**Note:** Version bump only for package analytics





## [0.1.14](https://github.com/DavidWells/analytics/compare/analytics@0.1.13...analytics@0.1.14) (2019-07-13)

**Note:** Version bump only for package analytics





## [0.1.13](https://github.com/DavidWells/analytics/compare/analytics@0.1.12...analytics@0.1.13) (2019-07-13)

**Note:** Version bump only for package analytics





## [0.1.12](https://github.com/DavidWells/analytics/compare/analytics@0.1.12...analytics@0.1.12) (2019-07-13)


### Bug Fixes

* **core:** disable ‘os’ for node until build fixed ([4610cd0](https://github.com/DavidWells/analytics/commit/4610cd0))
* **core:** expore devtools when debug set to true ([8dd38b7](https://github.com/DavidWells/analytics/commit/8dd38b7))
* **core:** fix campaign event ([8df0eaa](https://github.com/DavidWells/analytics/commit/8df0eaa))
* **core:** fix payload for .once listeners ([4cf07b7](https://github.com/DavidWells/analytics/commit/4cf07b7))
* **core:** remove async keyword ([6446e72](https://github.com/DavidWells/analytics/commit/6446e72))
* **core:** save last event & history ([275e89a](https://github.com/DavidWells/analytics/commit/275e89a))
* **core:** set anonId when setItemEnd occurs for ANON_ID ([5401cda](https://github.com/DavidWells/analytics/commit/5401cda))
* **core plugins:** run .page .track .identify callbacks when no plugins found ([09dfd78](https://github.com/DavidWells/analytics/commit/09dfd78))
* **debug:** support debug enhancer when no dev tools found ([c2a93c7](https://github.com/DavidWells/analytics/commit/c2a93c7))
* **utils:** fix build for node & testing + add iife build ([20a5021](https://github.com/DavidWells/analytics/commit/20a5021))


### Features

* **cli:** add analytics CLI for automate plugin docs & more to come ([297476c](https://github.com/DavidWells/analytics/commit/297476c))
* **core:** add analytics.reset for clean slate ([f30b83d](https://github.com/DavidWells/analytics/commit/f30b83d))
* **core:** add browser tab visible and window mouseout events ([ae65b37](https://github.com/DavidWells/analytics/commit/ae65b37))
* **core:** add debug to plugin action mods ([3c47088](https://github.com/DavidWells/analytics/commit/3c47088))
* **core:** add debug utilities ([daaef87](https://github.com/DavidWells/analytics/commit/daaef87))
* **core:** add deeper event log support for debugging ([5a8e810](https://github.com/DavidWells/analytics/commit/5a8e810))
* **core:** add enable / disable integration ([acc5390](https://github.com/DavidWells/analytics/commit/acc5390))
* **core:** add enable/disable integration by array of providers ([ddf596f](https://github.com/DavidWells/analytics/commit/ddf596f))
* **core:** add getPersistedUserData for initial state ([6620881](https://github.com/DavidWells/analytics/commit/6620881))
* **core:** add network events ([b2e06b6](https://github.com/DavidWells/analytics/commit/b2e06b6))
* **core:** add offline handler ([c4e2b11](https://github.com/DavidWells/analytics/commit/c4e2b11))
* **core:** add querystring API for triggering events + identify calls via utm params ([44d05d5](https://github.com/DavidWells/analytics/commit/44d05d5))
* **core:** add queuing & heartbeat mechanism for handling load loading analytic scripts ([7058b39](https://github.com/DavidWells/analytics/commit/7058b39))
* **core:** add storage constants ([04036a1](https://github.com/DavidWells/analytics/commit/04036a1))
* **core:** add storage middleware to allow for third party plugins to intercept / audit persistance data ([96fb50f](https://github.com/DavidWells/analytics/commit/96fb50f))
* **core:** add timestamp for track, identify, & page calls ([33d8338](https://github.com/DavidWells/analytics/commit/33d8338))
* **core:** add timeZone & locale to context ([d627a52](https://github.com/DavidWells/analytics/commit/d627a52))
* **core:** Expose setItem, removeItem, EVENTS, & CONSTANTS in api ([808b9ae](https://github.com/DavidWells/analytics/commit/808b9ae))
* **core:** listen to window events for future session feature ([4acebc5](https://github.com/DavidWells/analytics/commit/4acebc5))
* **core:** pass state getter to integrations as last arg ([29566d1](https://github.com/DavidWells/analytics/commit/29566d1))
* **core:** queue track, page, & identify calls if browser offline ([41f7f78](https://github.com/DavidWells/analytics/commit/41f7f78))
* **plugin-system:** add new core plugin engine ([e122572](https://github.com/DavidWells/analytics/commit/e122572))
* **plugins:** refactor plugins to allow for hooking into plugin specific events/methods ([c1c5379](https://github.com/DavidWells/analytics/commit/c1c5379))