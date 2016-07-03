---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (17-24 April 2016)
post::title: A week of Laravel (17-24 April 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/docs [master], laravel/docs [5.2], laravel/homestead [master], laravel/lumen-framework [5.2], laravel/lumen-docs [5.2], laravel/laravel.com [master], laravel/cashier [6.0], laravel/settler [master], laravel/socialite [2.0], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: April 24, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-04-17}...master@{2016-04-24})
- [3ecffb9](https://github.com/laravel/framework/commit/3ecffb9dc29c9be946a2fd2dc873c87c3f3e3954): [5.3] groupBy() minor changes (#13185) [@KennedyTedesco](https://github.com/KennedyTedesco)
- [16a5fb3](https://github.com/laravel/framework/commit/16a5fb3fd7a94b1f24f7f0f0cc435c491a8f04be): Allow additional values to be passed to firstOrCre [@JosephSilber](https://github.com/JosephSilber)
- [37e8bfd](https://github.com/laravel/framework/commit/37e8bfd3b96a9000dc8ba5e03b1e596f13af2dfd): bind float as PARAM_INT (#13233) [@themsaid](https://github.com/themsaid)
- [b9aef4f](https://github.com/laravel/framework/commit/b9aef4fc60b6937d764feb4e15f1b29cf9cfb656): Update .gitattributes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [cba62a9](https://github.com/laravel/framework/commit/cba62a90a0856d017f602c546085161e3e774994): Update .gitattributes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [09a793f](https://github.com/laravel/framework/commit/09a793ff026d02ce600791c5d5547b351c4398dc): Added missing superclosure suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [ed7d8a9](https://github.com/laravel/framework/commit/ed7d8a9e4b8166d6cde4c52634b3c2f00e6b6ee4): Added `CHANGELOG.md` (#13228) [@tillkruss](https://github.com/tillkruss)
- [5a52beb](https://github.com/laravel/framework/commit/5a52bebd203bb887e339e588aa75d938ae2d2ed7): Add Collection tests. (#13227) [@bancur](https://github.com/bancur)
- [c54e29b](https://github.com/laravel/framework/commit/c54e29b93cc581056edb4ff15247c5c60f2c151f): fix conflicts [@taylorotwell](https://github.com/taylorotwell)
- [ecfbbfb](https://github.com/laravel/framework/commit/ecfbbfbf96105439cc9a40bc78277bdb0268e34d): version [@taylorotwell](https://github.com/taylorotwell)
- [9dbdc5e](https://github.com/laravel/framework/commit/9dbdc5efe656a907d36094f16db0f453ba3c752b): Remove duplicate "[y/N]" from confirmable console  [@nhowell](https://github.com/nhowell)
- [f13bb7f](https://github.com/laravel/framework/commit/f13bb7f0a3db39c9c9cf8618cb70c0c309a54090): Remove unused parameter (#13206) [@TheGIBSON](https://github.com/TheGIBSON)
- [d0b5291](https://github.com/laravel/framework/commit/d0b5291098d856c3fb07075197feb165efb65c07): Move ability map to a method (#13214) [@JosephSilber](https://github.com/JosephSilber)
- [a37f3cc](https://github.com/laravel/framework/commit/a37f3cc2fb7e8f4ead37ad1966cdd5fee1b2d0ad): Typo [@GrahamCampbell](https://github.com/GrahamCampbell)
- [980ebf9](https://github.com/laravel/framework/commit/980ebf94611930fd526591b27945c56fab6a32da): Return  in the within method to allow method chain [@sileence](https://github.com/sileence)
- [d5dcc44](https://github.com/laravel/framework/commit/d5dcc444bd0d7db3d13dc55f528b9ad545b6b9e1): clean up some code [@taylorotwell](https://github.com/taylorotwell)
- [e0dbdc2](https://github.com/laravel/framework/commit/e0dbdc2892b45db559595383333992faa0951238): Bump min mockery version [@GrahamCampbell](https://github.com/GrahamCampbell)
- [b40fdc5](https://github.com/laravel/framework/commit/b40fdc5ada1ce024e9f27fdf10bec89e79500600): CS [@GrahamCampbell](https://github.com/GrahamCampbell)
- [70c8fd1](https://github.com/laravel/framework/commit/70c8fd1c56e836a93bf3fb3f6555b3cae1fd6853): code method order [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-04-17}...5.2@{2016-04-24})
- [c04159d](https://github.com/laravel/framework/commit/c04159dee4a47b0d7cd508ab720932121927b1b3): [5.2] Added "hasHeader" request method (#13271)* D [@mlantz](https://github.com/mlantz)
- [4219f0a](https://github.com/laravel/framework/commit/4219f0ac29615626be29940a6e20f047cb8204b9): Update saveMany parameter hint (#13257)It works gr [@rkgrep](https://github.com/rkgrep)
- [532c9f8](https://github.com/laravel/framework/commit/532c9f8f4fdffb479a69920b94f290ae1b20ade2): updated (#13260) [@ytake](https://github.com/ytake)
- [771d0ab](https://github.com/laravel/framework/commit/771d0abc0cf1df7468da59f244f8575dc6ac0a96): fix formatting [@taylorotwell](https://github.com/taylorotwell)
- [cb76758](https://github.com/laravel/framework/commit/cb7675845f89a6eca8011c5920e0bd3c62dcd016): Decode app key if it is encoded with base64app key [@sadika9](https://github.com/sadika9)
- [f4c56c8](https://github.com/laravel/framework/commit/f4c56c83afe949eaf43678ecc81f70ad76996ca5): Fix AppNameCommand when setting composer namespace [@leonardoalifraco](https://github.com/leonardoalifraco)
- [a675623](https://github.com/laravel/framework/commit/a675623d68442ceb0730b456d01dc5388b891e1e): make data_set handle non array targets (#13224) [@themsaid](https://github.com/themsaid)
- [c16f026](https://github.com/laravel/framework/commit/c16f02654393798b1b0d2bc37282e5b770aa22c3): [5.2] Use Carbon for everything time related in Da [@annejan](https://github.com/annejan)
- [0d356a6](https://github.com/laravel/framework/commit/0d356a64be51994e3326d35ffda7fc0e928898a7): [5.2] Translation - simplifies the parseLocale() m [@KennedyTedesco](https://github.com/KennedyTedesco)
- [b9aef4f](https://github.com/laravel/framework/commit/b9aef4fc60b6937d764feb4e15f1b29cf9cfb656): Update .gitattributes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [cba62a9](https://github.com/laravel/framework/commit/cba62a90a0856d017f602c546085161e3e774994): Update .gitattributes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [09a793f](https://github.com/laravel/framework/commit/09a793ff026d02ce600791c5d5547b351c4398dc): Added missing superclosure suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [ed7d8a9](https://github.com/laravel/framework/commit/ed7d8a9e4b8166d6cde4c52634b3c2f00e6b6ee4): Added `CHANGELOG.md` (#13228) [@tillkruss](https://github.com/tillkruss)
- [5a52beb](https://github.com/laravel/framework/commit/5a52bebd203bb887e339e588aa75d938ae2d2ed7): Add Collection tests. (#13227) [@bancur](https://github.com/bancur)
- [ecfbbfb](https://github.com/laravel/framework/commit/ecfbbfbf96105439cc9a40bc78277bdb0268e34d): version [@taylorotwell](https://github.com/taylorotwell)
- [9dbdc5e](https://github.com/laravel/framework/commit/9dbdc5efe656a907d36094f16db0f453ba3c752b): Remove duplicate "[y/N]" from confirmable console  [@nhowell](https://github.com/nhowell)
- [f13bb7f](https://github.com/laravel/framework/commit/f13bb7f0a3db39c9c9cf8618cb70c0c309a54090): Remove unused parameter (#13206) [@TheGIBSON](https://github.com/TheGIBSON)
- [d0b5291](https://github.com/laravel/framework/commit/d0b5291098d856c3fb07075197feb165efb65c07): Move ability map to a method (#13214) [@JosephSilber](https://github.com/JosephSilber)
- [a37f3cc](https://github.com/laravel/framework/commit/a37f3cc2fb7e8f4ead37ad1966cdd5fee1b2d0ad): Typo [@GrahamCampbell](https://github.com/GrahamCampbell)
- [980ebf9](https://github.com/laravel/framework/commit/980ebf94611930fd526591b27945c56fab6a32da): Return  in the within method to allow method chain [@sileence](https://github.com/sileence)
- [d5dcc44](https://github.com/laravel/framework/commit/d5dcc444bd0d7db3d13dc55f528b9ad545b6b9e1): clean up some code [@taylorotwell](https://github.com/taylorotwell)
- [e0dbdc2](https://github.com/laravel/framework/commit/e0dbdc2892b45db559595383333992faa0951238): Bump min mockery version [@GrahamCampbell](https://github.com/GrahamCampbell)
- [b40fdc5](https://github.com/laravel/framework/commit/b40fdc5ada1ce024e9f27fdf10bec89e79500600): CS [@GrahamCampbell](https://github.com/GrahamCampbell)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-04-17}...5.1@{2016-04-24})
- [532c9f8](https://github.com/laravel/framework/commit/532c9f8f4fdffb479a69920b94f290ae1b20ade2): updated (#13260) [@ytake](https://github.com/ytake)
- [f4c56c8](https://github.com/laravel/framework/commit/f4c56c83afe949eaf43678ecc81f70ad76996ca5): Fix AppNameCommand when setting composer namespace [@leonardoalifraco](https://github.com/leonardoalifraco)
- [b9aef4f](https://github.com/laravel/framework/commit/b9aef4fc60b6937d764feb4e15f1b29cf9cfb656): Update .gitattributes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [09a793f](https://github.com/laravel/framework/commit/09a793ff026d02ce600791c5d5547b351c4398dc): Added missing superclosure suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [9dbdc5e](https://github.com/laravel/framework/commit/9dbdc5efe656a907d36094f16db0f453ba3c752b): Remove duplicate "[y/N]" from confirmable console  [@nhowell](https://github.com/nhowell)
- [e0dbdc2](https://github.com/laravel/framework/commit/e0dbdc2892b45db559595383333992faa0951238): Bump min mockery version [@GrahamCampbell](https://github.com/GrahamCampbell)
- [712332c](https://github.com/laravel/framework/commit/712332cfb20d0f19b7402f88fb61e752850c77c2): Make sure unguarded() does not change unguarded st [@JeroenNoten](https://github.com/JeroenNoten)


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-04-17}...master@{2016-04-24})
- [05420bb](https://github.com/laravel/docs/commit/05420bb06301c5c4d59618769cf456914a336576): Fix wording [@taylorotwell](https://github.com/taylorotwell)
- [334e2a4](https://github.com/laravel/docs/commit/334e2a4279e4bd304e84c9c1f7e2b2cc33688930): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [945873b](https://github.com/laravel/docs/commit/945873b80da26138d8e3c7b5576b834fda752cda): wip [@taylorotwell](https://github.com/taylorotwell)
- [0b7f7b7](https://github.com/laravel/docs/commit/0b7f7b76d258adb46af1d3aecf127dbdebd183ff): Add missing anchor referenceThis anchor referenced [@Omranic](https://github.com/Omranic)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-04-17}...5.2@{2016-04-24})
- [7a2a718](https://github.com/laravel/docs/commit/7a2a7184633dcbc0ad94eacf93b61b06de604b6e): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [d9fed78](https://github.com/laravel/docs/commit/d9fed782c774594d4a602d6be7328b80f9ff3e7c): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [78087ec](https://github.com/laravel/docs/commit/78087ec435db5906741d715930e5d1f298c574cd): Added 'comment' in Column Modifier sectionAdded co [@paulodealmeida](https://github.com/paulodealmeida)
- [05420bb](https://github.com/laravel/docs/commit/05420bb06301c5c4d59618769cf456914a336576): Fix wording [@taylorotwell](https://github.com/taylorotwell)
- [945873b](https://github.com/laravel/docs/commit/945873b80da26138d8e3c7b5576b834fda752cda): wip [@taylorotwell](https://github.com/taylorotwell)
- [c20b5ef](https://github.com/laravel/docs/commit/c20b5ef9194ab6f2c8c382550a4f3f28789d0884): Change reject to skipLooks like the `reject` metho [@ntzm](https://github.com/ntzm)
- [0b7f7b7](https://github.com/laravel/docs/commit/0b7f7b76d258adb46af1d3aecf127dbdebd183ff): Add missing anchor referenceThis anchor referenced [@Omranic](https://github.com/Omranic)


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-04-17}...master@{2016-04-24})
- [ff4cf9d](https://github.com/laravel/homestead/commit/ff4cf9d33f8a6853ab6bca6586d7a91bbbd62aca): remove from stub [@taylorotwell](https://github.com/taylorotwell)
- [4d56f08](https://github.com/laravel/homestead/commit/4d56f088f1f6bb87ba734f50cf8d34a2ed5413df): Added `CHANGELOG.md` [@tillkruss](https://github.com/tillkruss)


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-04-17}...5.2@{2016-04-24})
- [52c1208](https://github.com/laravel/lumen-framework/commit/52c1208c0fbe062146d4d4697e2aee9da91c8b59): Fixed phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)
- [aced46d](https://github.com/laravel/lumen-framework/commit/aced46d480ab0bb58ae378acfbce83c6e08597b0): Applied fixes from StyleCI [@taylorotwell](https://github.com/taylorotwell)
- [1f28975](https://github.com/laravel/lumen-framework/commit/1f289750156873c6a83c4b63e35bf63c436cc84b): addRoute now accepts multiple methods [@m1](https://github.com/m1)


___

## [laravel/lumen-docs](https://github.com/laravel/lumen-docs)

### [5.2](https://github.com/laravel/lumen-docs/compare/5.2@{2016-04-17}...5.2@{2016-04-24})
- [49ba0b6](https://github.com/laravel/lumen-docs/commit/49ba0b64a8df49ddbbfa3d8120791f63dcc1a586): Fix "Testing JSON APIs" sectionNeed to use $this-> [@deanmraz](https://github.com/deanmraz)


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-04-17}...master@{2016-04-24})
- [9734724](https://github.com/laravel/laravel.com/commit/9734724dda938404d1507082bf674f52cab1a85d): Revert "Add search to 404" [@taylorotwell](https://github.com/taylorotwell)
- [796de36](https://github.com/laravel/laravel.com/commit/796de36430157847afc7ba02c5ed0b0cab135207): Regenerate assets [@mikefrancis](https://github.com/mikefrancis)
- [b2e0ca6](https://github.com/laravel/laravel.com/commit/b2e0ca67a4a92c3f2559e975b69e35cd9273704f): Decouple search from .docs [@mikefrancis](https://github.com/mikefrancis)
- [f508903](https://github.com/laravel/laravel.com/commit/f5089032cfaa92409c772499764ebb17905aef04): Create search partial [@mikefrancis](https://github.com/mikefrancis)


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-04-17}...6.0@{2016-04-24})
- [4680881](https://github.com/laravel/cashier/commit/46808815b5ea71ed9309b0d515c21ceec83cd304): fixing a few things [@taylorotwell](https://github.com/taylorotwell)
- [d427717](https://github.com/laravel/cashier/commit/d4277173e262f3c88f50f108c06bdb8267aa27e0): CS fix [@mlantz](https://github.com/mlantz)
- [722ec17](https://github.com/laravel/cashier/commit/722ec17074f4591c288d8ddc1048283c70bcfa0a): Missed this in refactoring [@mlantz](https://github.com/mlantz)
- [9def40f](https://github.com/laravel/cashier/commit/9def40f39d2e40e6befb9736439ec642c2d20b38): More CS changes [@mlantz](https://github.com/mlantz)
- [133baec](https://github.com/laravel/cashier/commit/133baecadc91b787a80728b2c6be59d6f5aae7a2): CS fixes [@mlantz](https://github.com/mlantz)
- [d81e4c2](https://github.com/laravel/cashier/commit/d81e4c26c46e67e04c4e291bf6202fc4f5836360): Adds refunds to BillableNow you can refund a user [@mlantz](https://github.com/mlantz)
- [51c2d5f](https://github.com/laravel/cashier/commit/51c2d5f1161a1f14e599407cdf82c0461f0fffe5): Adds column to options for subscriptions [@mlantz](https://github.com/mlantz)
- [6846b71](https://github.com/laravel/cashier/commit/6846b7198cbda5d164bab95faea4671274ab3d2a): Adds info to readme for testing [@mlantz](https://github.com/mlantz)


___

## [laravel/settler](https://github.com/laravel/settler)

### [master](https://github.com/laravel/settler/compare/master@{2016-04-17}...master@{2016-04-24})
- [b63da52](https://github.com/laravel/settler/commit/b63da527e20565273915d664b80afca4e2740786): update scriptss [@taylorotwell](https://github.com/taylorotwell)
- [366c18c](https://github.com/laravel/settler/commit/366c18c55620d9f3c165b895dbaecce85c116d7b): Update postgresql to version 9.5 [@EspadaV8](https://github.com/EspadaV8)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-04-17}...2.0@{2016-04-24})
- [ab7a611](https://github.com/laravel/socialite/commit/ab7a6118b126ed3497587abab4c5253618907bb5): fix authcontroller example namespace [@emmanuelgautier](https://github.com/emmanuelgautier)


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [It All Goes Back to a Single Assumption...That Could Be Wrong](http://laracasts.simplecast.fm/22)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 14: Laravel Spark](http://podcast.laravel-news.com/14)


___

## [Laracasts](https://laracasts.com)
- [Vue Mixins](https://laracasts.com/series/learning-vue-step-by-step/episodes/22)
- [Consider Policies](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/7)
- [Kiosk](https://laracasts.com/series/laravel-spark/episodes/6)
- [Dynamic Graphs](https://laracasts.com/series/charting-and-you/episodes/8)
- [API Driven Development](https://laracasts.com/series/laravel-spark/episodes/5)
- [God Object Cleanup #3: Value Objects](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/6)
