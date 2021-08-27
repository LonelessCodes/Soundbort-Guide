# Changelog

## [0.4.0](https://github.com/LonelessCodes/SoundBort/compare/v0.3.0...v0.4.0) \(2021-08-27\)

#### Features

* improved caching of samples, guild configs and blacklisted users \([341be4b](https://github.com/LonelessCodes/SoundBort/commit/341be4b89cf1334e6f360e8d178e36cab5eb0e17)\), closes [\#5](https://github.com/LonelessCodes/SoundBort/issues/5)
* **metrics command:** add option to specify time window \([e9b9442](https://github.com/LonelessCodes/SoundBort/commit/e9b9442f789dea2a08456b769bcb150e783b3d47)\)
* Upvote the bot to get more sample slots. /vote command \([af71a31](https://github.com/LonelessCodes/SoundBort/commit/af71a31ac6001fb867a5580128c91d8d6d6a79de)\), closes [\#6](https://github.com/LonelessCodes/SoundBort/issues/6)

#### Bug Fixes

* differenciate between custom and standard sample buttons in statistics \([0d4eeae](https://github.com/LonelessCodes/SoundBort/commit/0d4eeaec9af2ff373a764271d78c8d30b5700152)\)
* backport emergency fix from 'stable' 7dd4bdf1d34c9b62bcab770aad928d6370eca035 \([ec222db](https://github.com/LonelessCodes/SoundBort/commit/ec222dbc1ab84e3866841465836d9d4c14b69b22)\)
* trim inputs from string options. \([9f366ec](https://github.com/LonelessCodes/SoundBort/commit/9f366ec616f7700a03c3d8afa1d94698e42cbd70)\)

#### Changes

* add another time window to TimeWindowTable in charts \([05f06e7](https://github.com/LonelessCodes/SoundBort/commit/05f06e76101c8a48cdd7c19bff39ecea156e59c1)\)
* make /metrics command global \([69cf26a](https://github.com/LonelessCodes/SoundBort/commit/69cf26abe2320cb620d3bbb4dc93ce636246b4f8)\)
* move worker-portal.js to be more universal \([db30c96](https://github.com/LonelessCodes/SoundBort/commit/db30c9660810e18c8565c79b8b862bb6daad8f49)\)

## [0.3.0](https://github.com/LonelessCodes/SoundBort/compare/v0.2.1...v0.3.0) \(2021-08-16\)

#### Features

* add metrics/stats command \([da52a69](https://github.com/LonelessCodes/SoundBort/commit/da52a69400f837fd4204d0dd8efac8efdc0bbeb3)\)

#### Bug Fixes

* **Command.ts:** fixed error when replying to deffered interaction \([e31cea7](https://github.com/LonelessCodes/SoundBort/commit/e31cea7e01b3380498c7be46e50ab9a26970a9ab)\)

#### Changes

* added "buttons" fields to all db documents without one, so remove optional flag \([7faf1b9](https://github.com/LonelessCodes/SoundBort/commit/7faf1b91ce2bd37a244fa8e2f9ce942e926c26b8)\)

### [0.2.1](https://github.com/LonelessCodes/SoundBort/compare/v0.2.0...v0.2.1) \(2021-08-14\)

#### Bug Fixes

* fixed wrong repo url in /getting-started command \([23192fe](https://github.com/LonelessCodes/SoundBort/commit/23192fec818b7eabb68c5dcccba274bb9f5b7596)\)

#### Improvements

* better error logging? \([2ef0fe4](https://github.com/LonelessCodes/SoundBort/commit/2ef0fe40419dc46e1a0ec416e5d4210a8456ff76)\)

## [0.2.0](https://github.com/LonelessCodes/SoundBort/compare/v0.1.1...v0.2.0) \(2021-08-14\)

#### Features

* add button to remove sample from soundboard \([c0e7dbd](https://github.com/LonelessCodes/SoundBort/commit/c0e7dbd3afe3b7fbc25865a7fbb43f0c196d9b8d)\)
* import other user's or server's sound samples \([2103d4f](https://github.com/LonelessCodes/SoundBort/commit/2103d4fa48e007939a639430f5c9d5e6a6cf6c45)\)
* **list command:** add option to output only standard soundbort \([bc7b314](https://github.com/LonelessCodes/SoundBort/commit/bc7b3147cda70afa2eb29c265756e737184b3518)\)
* now also include button presses in statistics \([0554ee9](https://github.com/LonelessCodes/SoundBort/commit/0554ee92064fc3fb2052c07cb79ede7021046b0d)\)
* show dialog when clicking delete button \([2fb0a9f](https://github.com/LonelessCodes/SoundBort/commit/2fb0a9fe4d600f446274601ac2ae544de009f764)\)
* support posting server count to top.gg \([8181ad4](https://github.com/LonelessCodes/SoundBort/commit/8181ad49c9f6733c1c6b68fb24e1b26dda207dc1)\)

#### Bug Fixes

* add sample slot limit checks when importing \([7aeadc4](https://github.com/LonelessCodes/SoundBort/commit/7aeadc431c9e388d92f854ca6ac6b2f9a9ebf39d)\)
* add type-fest to package.json, so it isn't imported from ts-node \([8ac4a14](https://github.com/LonelessCodes/SoundBort/commit/8ac4a145391977243ba919bfc1aa156737e336fa)\)
* fixed security bug concerning non-mods deleting server samples \([40864dc](https://github.com/LonelessCodes/SoundBort/commit/40864dc8aba906b8880a8121159b8eba96eca6f1)\)
* make all custom button id fields strings, so that snowflakes won't be treated as numbers \([7938e51](https://github.com/LonelessCodes/SoundBort/commit/7938e51f915ae42fd036a0135a7b6514085c7059)\)
* **remove command:** add missing text to error when not in server \([0956fb6](https://github.com/LonelessCodes/SoundBort/commit/0956fb68c165fc00fde526f9ee4c5ff8f1fce73f)\)
* trim sample name whitespaces when uploading \([0525699](https://github.com/LonelessCodes/SoundBort/commit/052569961723e08a05398bcb1a69664658ee27d5)\)

#### Changes

* change invite url in /getting-started command \([c25261f](https://github.com/LonelessCodes/SoundBort/commit/c25261fa7cd82fb889c31b8f251ed3014e724c62)\)
* display owner commands only in selected guilds \([475ccea](https://github.com/LonelessCodes/SoundBort/commit/475cceadb55b936e12710b434771f2651e1d8ec1)\)

#### Improvements

* add seperate delete button for user and server to delete dialog \([21f55cb](https://github.com/LonelessCodes/SoundBort/commit/21f55cbf00a267f553d792a9e39a92b94b1e168d)\)
* cache json command data generated by command classes \([83f5981](https://github.com/LonelessCodes/SoundBort/commit/83f59817df4c5f662e6f5db3e107aaaa692fd8d9)\)

### [0.1.1](https://github.com/LonelessCodes/SoundBort/compare/v0.1.0...v0.1.1) \(2021-08-11\)

#### Bug Fixes

* fixed guessing mod role by role position \([b108508](https://github.com/LonelessCodes/SoundBort/commit/b1085080553bb0740a6c4c791e27c8633c1f4ab4)\)

## 0.1.0 \(2021-08-11\)

#### Features

* add /getting-started command \([c24f891](https://github.com/LonelessCodes/SoundBort/commit/c24f891e268ccca2e2e1b0083a68de987e1d2813)\)
* add config command and neccessary implementations \([e7f38e9](https://github.com/LonelessCodes/SoundBort/commit/e7f38e926fae7a5bb585bda0930a78cc2719f93e)\)
* add owner command \([f0bb270](https://github.com/LonelessCodes/SoundBort/commit/f0bb2700609f796ac030f8ef27e1c03e624efa45)\)
* allow blacklisting of users \([a89dde8](https://github.com/LonelessCodes/SoundBort/commit/a89dde8174fdfa4725e1f3c02ddc52ad01b735dd)\)
* leave voice channel when moved to empty vc or all members left \([459220e](https://github.com/LonelessCodes/SoundBort/commit/459220e342ce2f9ecbe9f48ba1ebc7ba3e39c5f4)\)
* show sample info and play button after sample upload \([cb12c15](https://github.com/LonelessCodes/SoundBort/commit/cb12c156d851b6a8ff9bab5079ed7a6929d549d0)\)

#### Bug Fixes

* add permissions to owner command \([6814854](https://github.com/LonelessCodes/SoundBort/commit/6814854874d8293aba49a8cc32d6b50d4aa5bb23)\)
* banner file path fixed \([2e35e8f](https://github.com/LonelessCodes/SoundBort/commit/2e35e8fa4d7727bf7324e6a0d53c6e9547890638)\)
* cache not updated when playing sample \([1445881](https://github.com/LonelessCodes/SoundBort/commit/1445881a66253122881695816cc813f0fbeee80b)\)
* default back to default guessed mod role when previous mod role has been deleted \([4f66cfc](https://github.com/LonelessCodes/SoundBort/commit/4f66cfc84fe2f28169534b0c97426d9c2be2ca00)\)
* disallow user not in same voice chat to play samples \([1205978](https://github.com/LonelessCodes/SoundBort/commit/12059782c3244cc918129b9def0ca0edf1cff4e2)\)
* fix embed colors \([3e81ff5](https://github.com/LonelessCodes/SoundBort/commit/3e81ff5f90be90243eb174340f886372f3de44dc)\)
* fix error when /owner delete standard \([f7c4eca](https://github.com/LonelessCodes/SoundBort/commit/f7c4eca60a978ad8dfc8a1d162f13815f3e48041)\)
* fixed from method name \([117e7f7](https://github.com/LonelessCodes/SoundBort/commit/117e7f76a81b5942462fe9bd088e476c20cec9bb)\)
* fixed not loading commands after transpiling \([b3e74fa](https://github.com/LonelessCodes/SoundBort/commit/b3e74fad33b3d1776b416cda62ca2794f6c3e0ce)\)
* maybe fixed permissions for /data and /logs? \([8cdc297](https://github.com/LonelessCodes/SoundBort/commit/8cdc297f0b157d0be7cff74f2f7c59e26b518458)\)
* missing permissions to open package-lock.json in Dockerfile fixed \([d3024a0](https://github.com/LonelessCodes/SoundBort/commit/d3024a0455551a78c02a0adf586cbbabb98bfab3)\)
* now fixed Dockerfile? \([fdcad75](https://github.com/LonelessCodes/SoundBort/commit/fdcad75908c8761f520f13bb73e614e6f5cb42de)\)
* quick fix for failed import \([962dcec](https://github.com/LonelessCodes/SoundBort/commit/962dcecf6dac0b01e0d2bfd6f36d5097ebe8b9ce)\)
* replying to already replied to interaction fixed \([fc6306b](https://github.com/LonelessCodes/SoundBort/commit/fc6306bda827219917c2d1b4a75b691b6751fabf)\)

#### Improvements

* check, to not set admin role again \([99b1cd8](https://github.com/LonelessCodes/SoundBort/commit/99b1cd84bbe7614f9bf88670d54931b2770d3e8f)\)
* improve error logs \([a0d2527](https://github.com/LonelessCodes/SoundBort/commit/a0d25272c5aa318fa94cc350760e4228785d7538)\)
* reduce docker image size \([e340eb4](https://github.com/LonelessCodes/SoundBort/commit/e340eb4ec6de2d86558b4741dfc13aa798a14200)\)

#### Changes

* add play button to info command \([f76b9a4](https://github.com/LonelessCodes/SoundBort/commit/f76b9a4cf528a5c679c7f1b6b541a84d9b0cd643)\)
* change boot-up status \([1bb1dcb](https://github.com/LonelessCodes/SoundBort/commit/1bb1dcbe51537156fd93fc24ffecef6690bcfdba)\)
* change max sample slots to 10 \([81a8f18](https://github.com/LonelessCodes/SoundBort/commit/81a8f18fa8872e8bdf3be123a0525540def18346)\)
* handle moderator checks client-side only \([91b7b32](https://github.com/LonelessCodes/SoundBort/commit/91b7b32c0e0717217d6a2b209d57de79af08a62b)\)
* rename /owner upload-pre command to /owner upload standard \([3e7db37](https://github.com/LonelessCodes/SoundBort/commit/3e7db37f6358696b5bbab27ce92b08f21a5ff028)\)
* run node as root in Dockerfile, since I couldn't resolve permission problems \([4845ffd](https://github.com/LonelessCodes/SoundBort/commit/4845ffd4a5b8ea73919efc66620654cf18d3b68a)\)
* update color palette \([e9c6dfe](https://github.com/LonelessCodes/SoundBort/commit/e9c6dfe2b966782d4294ffe8639824a5271f4bb7)\)

