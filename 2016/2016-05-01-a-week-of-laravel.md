---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (24 April-01 May 2016)
post::title: A week of Laravel (24 April-01 May 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [develop], laravel/docs [5.2], laravel/homestead [master], laravel/lumen-framework [master], laravel/lumen-framework [5.2], laravel/lumen [master], laravel/laravel.com [master], laravel/quickstart-basic [master], laravel/settler [master], laravel/socialite [2.0], laravel/elixir [master], laravel/envoy [master], Laracasts"
post::date: May 01, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-04-24}...master@{2016-05-01})
- [d261581](https://github.com/laravel/framework/commit/d26158103348e60d1581d464186280c397333ffb): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [990b281](https://github.com/laravel/framework/commit/990b2811c5f11367d5f2c9ed8a7997a2c2907f63): [5.2] Return null instead of 0 for a default Belon [@ameliaikeda](https://github.com/ameliaikeda)
- [5fff79b](https://github.com/laravel/framework/commit/5fff79b7e0cfcba13037f73968119d5f50412d26): fix order [@taylorotwell](https://github.com/taylorotwell)
- [d81f3dc](https://github.com/laravel/framework/commit/d81f3dc80b582dd000fe76501c2facdd5be06ff0): Fix docblock [@sadika9](https://github.com/sadika9)
- [d32d6b2](https://github.com/laravel/framework/commit/d32d6b288335d0b7a2cdf86f51e7b10a5f60df03): Bumped min phpunit version [@GrahamCampbell](https://github.com/GrahamCampbell)
- [cf93557](https://github.com/laravel/framework/commit/cf93557d5f8e5ac737396d064bc30cb491ee4b88): Add method to get guest middleware with guard para [@sadika9](https://github.com/sadika9)
- [77e9df9](https://github.com/laravel/framework/commit/77e9df96ded79c6276c48c06ec846efd3a833efc): fix a few things [@taylorotwell](https://github.com/taylorotwell)
- [e2da638](https://github.com/laravel/framework/commit/e2da63875bd44d9359dd69a9aeebcba648e195bf): use request socket if passed [@taylorotwell](https://github.com/taylorotwell)
- [0c2d9a7](https://github.com/laravel/framework/commit/0c2d9a72b36cb9197039fac9fe0977891c2d1fc6): fix test [@taylorotwell](https://github.com/taylorotwell)
- [133492a](https://github.com/laravel/framework/commit/133492a69cab9a38a694c53b2b95beab5fafd7ba): fix file validator test (#13379) [@themsaid](https://github.com/themsaid)
- [cb11bfe](https://github.com/laravel/framework/commit/cb11bfe8f2d1726dc4e761feb5b035ba1f164665): more fixes [@taylorotwell](https://github.com/taylorotwell)
- [dc5d738](https://github.com/laravel/framework/commit/dc5d7383f09a8f17ebd5d97177e6bbab805debd5): working on tests [@taylorotwell](https://github.com/taylorotwell)
- [49f4ce5](https://github.com/laravel/framework/commit/49f4ce54b0e687088996fe0ac0f55eb42afcca98): fix first batch [@taylorotwell](https://github.com/taylorotwell)
- [57c42be](https://github.com/laravel/framework/commit/57c42be2f8c323daad4103753f171f49bb758075): working on code [@taylorotwell](https://github.com/taylorotwell)
- [46fd7dd](https://github.com/laravel/framework/commit/46fd7dd7d794eb5fe6406198880d06a1b33d85e7): Fix Issue #11169 (#13360) [@AdenFraser](https://github.com/AdenFraser)
- [003d445](https://github.com/laravel/framework/commit/003d445b685c48e9caf17fdd7b7ea468604c374f): Fix issue (#13361) [@pochocho](https://github.com/pochocho)
- [2e12e8a](https://github.com/laravel/framework/commit/2e12e8ac272699172bbc928c3f203202dc8fa855): rearrange check order [@taylorotwell](https://github.com/taylorotwell)
- [e4a6afc](https://github.com/laravel/framework/commit/e4a6afcb22223e7188f3ceb46bdd88ededc50801): return inline [@taylorotwell](https://github.com/taylorotwell)
- [3549634](https://github.com/laravel/framework/commit/3549634aeac1dcf324de02b29221f5355d0bca8f): Memcached::OPT_AUTO_EJECT_HOSTS not available in H [Tom Castleman]
- [8820c4b](https://github.com/laravel/framework/commit/8820c4b484de941baa6f3bb651cc9d7deeaa20db): Adds support for persistent connections, sasl auth [Tom Castleman]
- [34c8b93](https://github.com/laravel/framework/commit/34c8b93732302009e9ff4aebc63af1897e660cb7): Closes #13301 by adding a file validation rule [@themsaid](https://github.com/themsaid)
- [ebcaba3](https://github.com/laravel/framework/commit/ebcaba31b95eca9e3f3d519f3ad453ce2a244004): fix #13314 by converting != <> wheres to is not nu [@themsaid](https://github.com/themsaid)
- [3960daf](https://github.com/laravel/framework/commit/3960daf4f8cacd8cb5cd3d7872a30e32a8d42a24): keep working on pusher ideas [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-04-24}...5.2@{2016-05-01})
- [d261581](https://github.com/laravel/framework/commit/d26158103348e60d1581d464186280c397333ffb): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [990b281](https://github.com/laravel/framework/commit/990b2811c5f11367d5f2c9ed8a7997a2c2907f63): [5.2] Return null instead of 0 for a default Belon [@ameliaikeda](https://github.com/ameliaikeda)
- [5fff79b](https://github.com/laravel/framework/commit/5fff79b7e0cfcba13037f73968119d5f50412d26): fix order [@taylorotwell](https://github.com/taylorotwell)
- [d81f3dc](https://github.com/laravel/framework/commit/d81f3dc80b582dd000fe76501c2facdd5be06ff0): Fix docblock [@sadika9](https://github.com/sadika9)
- [cf93557](https://github.com/laravel/framework/commit/cf93557d5f8e5ac737396d064bc30cb491ee4b88): Add method to get guest middleware with guard para [@sadika9](https://github.com/sadika9)
- [133492a](https://github.com/laravel/framework/commit/133492a69cab9a38a694c53b2b95beab5fafd7ba): fix file validator test (#13379) [@themsaid](https://github.com/themsaid)
- [46fd7dd](https://github.com/laravel/framework/commit/46fd7dd7d794eb5fe6406198880d06a1b33d85e7): Fix Issue #11169 (#13360) [@AdenFraser](https://github.com/AdenFraser)
- [003d445](https://github.com/laravel/framework/commit/003d445b685c48e9caf17fdd7b7ea468604c374f): Fix issue (#13361) [@pochocho](https://github.com/pochocho)
- [2e12e8a](https://github.com/laravel/framework/commit/2e12e8ac272699172bbc928c3f203202dc8fa855): rearrange check order [@taylorotwell](https://github.com/taylorotwell)
- [e4a6afc](https://github.com/laravel/framework/commit/e4a6afcb22223e7188f3ceb46bdd88ededc50801): return inline [@taylorotwell](https://github.com/taylorotwell)
- [34c8b93](https://github.com/laravel/framework/commit/34c8b93732302009e9ff4aebc63af1897e660cb7): Closes #13301 by adding a file validation rule [@themsaid](https://github.com/themsaid)
- [ebcaba3](https://github.com/laravel/framework/commit/ebcaba31b95eca9e3f3d519f3ad453ce2a244004): fix #13314 by converting != <> wheres to is not nu [@themsaid](https://github.com/themsaid)
- [e9ec0c1](https://github.com/laravel/framework/commit/e9ec0c18fbe5f4125bed0f6da8c02f89e1fbb49b): working on code formatting [@taylorotwell](https://github.com/taylorotwell)
- [8984ac1](https://github.com/laravel/framework/commit/8984ac1e690ecca34d2999943538f935a62ff55b): Added release notes for v5.2.31 (#13345)* Added re [@tillkruss](https://github.com/tillkruss)
- [2a10a75](https://github.com/laravel/framework/commit/2a10a752bd4bf782af3ff54c7a3fcad92b7a167d): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [50c7e02](https://github.com/laravel/framework/commit/50c7e026db1da8a265482fef4417c92f46cc5b78): increment verison [@taylorotwell](https://github.com/taylorotwell)
- [d023c08](https://github.com/laravel/framework/commit/d023c0833dcbd110cdd0849df27802a0f68afef8): Enable or disable Foreign Key Constraints [@srmklive](https://github.com/srmklive)
- [2fa2797](https://github.com/laravel/framework/commit/2fa2797604bf54b06faf7bb139a9fc0d66826fea): increment version [@taylorotwell](https://github.com/taylorotwell)
- [8fa2438](https://github.com/laravel/framework/commit/8fa2438d0ba4595fd37c3037f14d8fefaa396fa1): code cleaning [@taylorotwell](https://github.com/taylorotwell)
- [8716213](https://github.com/laravel/framework/commit/87162136d9c8841b2e9e91c08fda8ed202e8e4ca): fix message [@taylorotwell](https://github.com/taylorotwell)
- [b6735f7](https://github.com/laravel/framework/commit/b6735f7f064f792cb1d099f18e520a2928f6e9cc): Fix seeAuthenticatedAs when using 2 different user [@sileence](https://github.com/sileence)
- [733ceda](https://github.com/laravel/framework/commit/733ceda42dd0f319596e2bb51524c0f1bb7207b4): [5.2] Database Builder minor change (#13321)Just t [@KennedyTedesco](https://github.com/KennedyTedesco)
- [59525ab](https://github.com/laravel/framework/commit/59525ab14b5c3083db494c65459360ba3338ac6f): remove nested ternary [@taylorotwell](https://github.com/taylorotwell)
- [5e91db0](https://github.com/laravel/framework/commit/5e91db048c380cdb12e080c88858a90ef9643c7b): [5.2] Revert broken changes (#13331)* Revert broke [@GrahamCampbell](https://github.com/GrahamCampbell)
- [3dcd37a](https://github.com/laravel/framework/commit/3dcd37a463060a3b24fcd44974b544e14e6e0eeb): change db driver check [孙建华]


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-04-24}...5.1@{2016-05-01})
- [46fd7dd](https://github.com/laravel/framework/commit/46fd7dd7d794eb5fe6406198880d06a1b33d85e7): Fix Issue #11169 (#13360) [@AdenFraser](https://github.com/AdenFraser)
- [50c7e02](https://github.com/laravel/framework/commit/50c7e026db1da8a265482fef4417c92f46cc5b78): increment verison [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-04-24}...master@{2016-05-01})
- [76b8ef7](https://github.com/laravel/laravel/commit/76b8ef720400b0c0bf4cdab39c354e8addef7dd9): remove post install just in case it causes problem [@taylorotwell](https://github.com/taylorotwell)
- [909f063](https://github.com/laravel/laravel/commit/909f063c28e9c1a9811d8785626da93b04524be5): Add npm scripts [@vinkla](https://github.com/vinkla)


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-04-24}...develop@{2016-05-01})
- [da662e4](https://github.com/laravel/laravel/commit/da662e40ec5b464b64188dbe650b668f08be0b72): working on broadcasting [@taylorotwell](https://github.com/taylorotwell)
- [749528d](https://github.com/laravel/laravel/commit/749528db0c85c69349f8e8af564378cf9457a1d8): remove unneeded trait [@taylorotwell](https://github.com/taylorotwell)
- [76b8ef7](https://github.com/laravel/laravel/commit/76b8ef720400b0c0bf4cdab39c354e8addef7dd9): remove post install just in case it causes problem [@taylorotwell](https://github.com/taylorotwell)
- [909f063](https://github.com/laravel/laravel/commit/909f063c28e9c1a9811d8785626da93b04524be5): Add npm scripts [@vinkla](https://github.com/vinkla)


___

## [laravel/docs](https://github.com/laravel/docs)

### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-04-24}...5.2@{2016-05-01})
- [23c92d5](https://github.com/laravel/docs/commit/23c92d5970646770994ab365285e83d3e6df2d4f): workin gon wording [@taylorotwell](https://github.com/taylorotwell)
- [81cdf56](https://github.com/laravel/docs/commit/81cdf56efb40f86efbb7410d5d4203f932adf27c): specify queue:restart command only stops processMa [@Edgpaez](https://github.com/Edgpaez)
- [4f9933e](https://github.com/laravel/docs/commit/4f9933efb50ad24de78af643d194d78469d48805): fix wording [@srmklive](https://github.com/srmklive)
- [1db305b](https://github.com/laravel/docs/commit/1db305b7ac0753405c72a2cc6f643705b2d9f0a5): change order [@taylorotwell](https://github.com/taylorotwell)
- [46af841](https://github.com/laravel/docs/commit/46af8418165e6d07599a5b11786e0dcca24ddce9): change wording [@taylorotwell](https://github.com/taylorotwell)
- [879dc50](https://github.com/laravel/docs/commit/879dc509459857f01e9c4fa871fdcc71152981b3): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [53f095f](https://github.com/laravel/docs/commit/53f095fae33f187c9437bdada4a22d7437631d86): Documentation to Enable or disable foreign key con [@srmklive](https://github.com/srmklive)
- [b6e4095](https://github.com/laravel/docs/commit/b6e40951cc9e5847a7365174a9db20de8c736857): Update localization.md [@chilion](https://github.com/chilion)
- [63ac935](https://github.com/laravel/docs/commit/63ac9355294e5a083ea78d8abe7c3cfdcf647fe4): Added missing documentation for assertSessionMissi [@jjsee](https://github.com/jjsee)
- [063b8ca](https://github.com/laravel/docs/commit/063b8cabcdfdace4660928bf0e4ee91011b4103d): tweak wording [@taylorotwell](https://github.com/taylorotwell)
- [4de69ae](https://github.com/laravel/docs/commit/4de69ae82fd44abd52b1109d34902c760a5fce51): Adding file visiblity documentation. [@cthos](https://github.com/cthos)
- [2ff15c8](https://github.com/laravel/docs/commit/2ff15c8789ec00a7b256a1416dbb9d78a4edff33): Use Eloquent relationships in intermediate quickst [@ntzm](https://github.com/ntzm)
- [e22beaf](https://github.com/laravel/docs/commit/e22beaf426b2732f8dbdd0861a1cea4b55d014b3): Link to Sentry's Laravel integration [@dcramer](https://github.com/dcramer)
- [93480a7](https://github.com/laravel/docs/commit/93480a72804a1b030f68cb6342aed39e2f324771): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [b45ce80](https://github.com/laravel/docs/commit/b45ce8098899d8b76fc546fd07d63d6435b9fd80): Add explanation of how to get the URL of a given s [@pjmartorell](https://github.com/pjmartorell)
- [2c8e2b0](https://github.com/laravel/docs/commit/2c8e2b0934442233c8210b2d9175bc2a77c0aa3d): Add Cloud filesystem disk explanation [@pjmartorell](https://github.com/pjmartorell)
- [9a68b78](https://github.com/laravel/docs/commit/9a68b78ec4babbc70b04539ad6d490f4d0697cd2): Replaced bash alias with bash functionThere is no  [@mabasic](https://github.com/mabasic)
- [d8547a0](https://github.com/laravel/docs/commit/d8547a0cc48e25fd3daf48b871ffe82c3d09a976): working on wording [@taylorotwell](https://github.com/taylorotwell)
- [4856043](https://github.com/laravel/docs/commit/4856043d21ddbce4a15dc287357f3c4142e6d84c): Update documentation to include mimetypes [@timgws](https://github.com/timgws)


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-04-24}...master@{2016-05-01})
- [4ed2af3](https://github.com/laravel/homestead/commit/4ed2af355b11d310b60878b26a49bb3ec785e115): append privileged to false at afterscript provisio [@justinmoh](https://github.com/justinmoh)


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-04-24}...master@{2016-05-01})
- [b8cfae2](https://github.com/laravel/lumen-framework/commit/b8cfae2187d2722fb38f5c7694e2aa46ed338622): Use fast-route 1.x [@GrahamCampbell](https://github.com/GrahamCampbell)


### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-04-24}...5.2@{2016-05-01})
- [d9186b7](https://github.com/laravel/lumen-framework/commit/d9186b720cbae0d2e12656168161437d789bc034): Clear facades before bootstrapping the appIf facad [@yuloh](https://github.com/yuloh)


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-04-24}...master@{2016-05-01})
- [add7bc8](https://github.com/laravel/laravel.com/commit/add7bc8fa6e42e3b563b8f5558328935cc439e49): PSR2-4LYFE [@kayladnls](https://github.com/kayladnls)


___

## [laravel/settler](https://github.com/laravel/settler)

### [master](https://github.com/laravel/settler/compare/master@{2016-04-24}...master@{2016-05-01})
- [574581b](https://github.com/laravel/settler/commit/574581b2a69e60694ec9bd18515466dae6374bff): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [0016534](https://github.com/laravel/settler/commit/001653413046660f96451d4a73f59a313eaea49f): Fixes composer being very slow due to xdebug being [@jonnywilliamson](https://github.com/jonnywilliamson)
- [e153e33](https://github.com/laravel/settler/commit/e153e338936db471b5e06d943ab5028e909e730b): Re-add xdebug config settings [@jonnywilliamson](https://github.com/jonnywilliamson)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-04-24}...2.0@{2016-05-01})
- [38193be](https://github.com/laravel/socialite/commit/38193be348affd74cd259b3d52059290fafc9990): fix method order [@taylorotwell](https://github.com/taylorotwell)
- [77625d5](https://github.com/laravel/socialite/commit/77625d5800ef7fe78fea3be8e5f79a9cf371da5b): fixed [@apollopy](https://github.com/apollopy)
- [28129b6](https://github.com/laravel/socialite/commit/28129b624354da36116b972e89877339cfa4104d): Allows the caller to set the Client [@apollopy](https://github.com/apollopy)


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-04-24}...master@{2016-05-01})
- [4ec2556](https://github.com/laravel/elixir/commit/4ec2556bddbfbd80d585f058de4fa6bbeaa4f9e9): This missing period is annoying me. [@JeffreyWay](https://github.com/JeffreyWay)
- [e1a732d](https://github.com/laravel/elixir/commit/e1a732d1fae353ab3741300d98acc9d3d8a0c54e): Fix issue where plugins are not loaded properly -  [@JeffreyWay](https://github.com/JeffreyWay)
- [30271c9](https://github.com/laravel/elixir/commit/30271c9d04be1450ca4a5994e6eeee12c2ecca98): Remove mix.rubySassThis had been deprecated for a  [@JeffreyWay](https://github.com/JeffreyWay)
- [4e44c49](https://github.com/laravel/elixir/commit/4e44c496756d9196b03a45a3773225702e6e93e3): Small fixes [@JeffreyWay](https://github.com/JeffreyWay)
- [d75e8d2](https://github.com/laravel/elixir/commit/d75e8d2661d6a8bc12c10a9c4976b4dd4047b95a): Add Sublime files to gitignore [@JeffreyWay](https://github.com/JeffreyWay)
- [7f432c2](https://github.com/laravel/elixir/commit/7f432c2acbafaab6ca2b98d04c9c681c085b1eb9): Remove CoffeeScript testThis is no longer included [@JeffreyWay](https://github.com/JeffreyWay)


___

## [laravel/envoy](https://github.com/laravel/envoy)

### [master](https://github.com/laravel/envoy/compare/master@{2016-04-24}...master@{2016-05-01})
- [ae45ee9](https://github.com/laravel/envoy/commit/ae45ee992fb303416a275f998852009ad6777742): update version [@taylorotwell](https://github.com/taylorotwell)
- [6d90bef](https://github.com/laravel/envoy/commit/6d90bef218abcc4ef8b1a3d46e2b69034920e8de): remove lock file [@taylorotwell](https://github.com/taylorotwell)
- [fc7bc80](https://github.com/laravel/envoy/commit/fc7bc808c9acf8dd6d476abe3501b88c849f74fd): update dependencies [@taylorotwell](https://github.com/taylorotwell)


___

## [Laracasts](https://laracasts.com)
- [Arrows](https://laracasts.com/series/es6-cliffsnotes/episodes/4)
- [To Var, Let, or Const](https://laracasts.com/series/es6-cliffsnotes/episodes/3)
- [ES6 Compilation With Laravel Elixir](https://laracasts.com/series/es6-cliffsnotes/episodes/2)
- [Babel Setup](https://laracasts.com/series/es6-cliffsnotes/episodes/1)
- [Consider Splitting Tasks into Steps](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/8)
