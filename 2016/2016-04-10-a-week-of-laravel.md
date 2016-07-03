---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (03-10 April 2016)
post::title: A week of Laravel (03-10 April 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [5.1], laravel/installer [master], laravel/docs [master], laravel/docs [5.2], laravel/docs [5.1], laravel/lumen-framework [5.2], laravel/lumen [master], laravel/cashier-braintree [1.0], laravel/elixir [master], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: April 10, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-04-03}...master@{2016-04-10})
- [c5b8d93](https://github.com/laravel/framework/commit/c5b8d9375e0a309132e8f3673be8548939bd4d2c): Fixed phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)
- [28e60c2](https://github.com/laravel/framework/commit/28e60c2f5ddfdee35564833ac36d0f13450690e7): remove extra spacing [@taylorotwell](https://github.com/taylorotwell)
- [df939ac](https://github.com/laravel/framework/commit/df939ac8141e70afb18317d6a85351eb77c801f2): code cleaning [@taylorotwell](https://github.com/taylorotwell)
- [16dd3c3](https://github.com/laravel/framework/commit/16dd3c337ababe2d4e05df9e9a20e959ea311e7a): dry up code. [@taylorotwell](https://github.com/taylorotwell)
- [2ca9ca6](https://github.com/laravel/framework/commit/2ca9ca69043230b422d518d7fbc7cf797cc4e2a6): Update SqlServerGrammar.php (#13089)The descriptio [@filipeaclima](https://github.com/filipeaclima)
- [b4f3afc](https://github.com/laravel/framework/commit/b4f3afc038aeb67e74b5165ae73f8c3a0fe23046): slight code cleanup [@taylorotwell](https://github.com/taylorotwell)
- [8535763](https://github.com/laravel/framework/commit/8535763fc00075279b553e8e32289419a7caf90e): fix an issue with fluent uses (#13076) [@themsaid](https://github.com/themsaid)
- [9937493](https://github.com/laravel/framework/commit/9937493de1407aebe3926eda8271fb391df5d1c1): [5.2] Correct phpdoc and complete tests (#13086)*  [@vlakoff](https://github.com/vlakoff)
- [ce36527](https://github.com/laravel/framework/commit/ce36527a2a04af22227d2c9f3382a7d02413ee14): Formatting [@GrahamCampbell](https://github.com/GrahamCampbell)
- [1ba841b](https://github.com/laravel/framework/commit/1ba841b10045b1cb1da1e0028ffbaa784a80843b): formatting and comments [@taylorotwell](https://github.com/taylorotwell)
- [dcef6c5](https://github.com/laravel/framework/commit/dcef6c5f45f37a4ab62a8623b2d0815ec4019de7): [5.1] Quote user-supplied content for use in preg_ [@vlakoff](https://github.com/vlakoff)
- [b18c01e](https://github.com/laravel/framework/commit/b18c01edc8db22d29ce7500b68b6431561489bc9): revert forcing middleware uniqueness (#13075) [@themsaid](https://github.com/themsaid)
- [229c3fa](https://github.com/laravel/framework/commit/229c3fa33e3527f5da775fa62085be9fa03e0daf): [5.2] Allow objects to be passed as pipesAllows fo [@rkgrep](https://github.com/rkgrep)
- [bd06a8c](https://github.com/laravel/framework/commit/bd06a8c0ac19cacc8cfcc12443bd4d54b7f73354): fix conflicts [@taylorotwell](https://github.com/taylorotwell)
- [5b96bfa](https://github.com/laravel/framework/commit/5b96bfa662cb813ea932383726b8fda8b0e81ee8): fix conflicts [@taylorotwell](https://github.com/taylorotwell)
- [0e73cba](https://github.com/laravel/framework/commit/0e73cba565b0ef5b158da62f641dc6770b806102): increment version [@taylorotwell](https://github.com/taylorotwell)
- [de872dc](https://github.com/laravel/framework/commit/de872dcf80d81d6017f567f54c475f3923841e6d): support non numeric keys [@themsaid](https://github.com/themsaid)
- [da62677](https://github.com/laravel/framework/commit/da62677cea29ce3f5e6348c416218f11459ca3d6): Allow numerics for unix timestamps. [@taylorotwell](https://github.com/taylorotwell)
- [8f5ce59](https://github.com/laravel/framework/commit/8f5ce59e72dc73d40147f61e34ffa766a068a2bb): [5.2] Enabling array on method has()* Enabling arr [@urameshibr](https://github.com/urameshibr)
- [61eb2d2](https://github.com/laravel/framework/commit/61eb2d20b224324679135f08a0593c7dac08b67f): [5.2] Combine if statements* Combine if statements [@BrandonSurowiec](https://github.com/BrandonSurowiec)
- [a013eb2](https://github.com/laravel/framework/commit/a013eb251fa20cc8149899cc74fdb4af6217e450): formatting [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-04-03}...5.2@{2016-04-10})
- [2eb5551](https://github.com/laravel/framework/commit/2eb5551b92a89ae2481fbf9aaf2ecee7aa1b4c45): Adding proper alias for FailedJobProviderInterface [@dbpolito](https://github.com/dbpolito)
- [c5b8d93](https://github.com/laravel/framework/commit/c5b8d9375e0a309132e8f3673be8548939bd4d2c): Fixed phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)
- [28e60c2](https://github.com/laravel/framework/commit/28e60c2f5ddfdee35564833ac36d0f13450690e7): remove extra spacing [@taylorotwell](https://github.com/taylorotwell)
- [df939ac](https://github.com/laravel/framework/commit/df939ac8141e70afb18317d6a85351eb77c801f2): code cleaning [@taylorotwell](https://github.com/taylorotwell)
- [16dd3c3](https://github.com/laravel/framework/commit/16dd3c337ababe2d4e05df9e9a20e959ea311e7a): dry up code. [@taylorotwell](https://github.com/taylorotwell)
- [2ca9ca6](https://github.com/laravel/framework/commit/2ca9ca69043230b422d518d7fbc7cf797cc4e2a6): Update SqlServerGrammar.php (#13089)The descriptio [@filipeaclima](https://github.com/filipeaclima)
- [b4f3afc](https://github.com/laravel/framework/commit/b4f3afc038aeb67e74b5165ae73f8c3a0fe23046): slight code cleanup [@taylorotwell](https://github.com/taylorotwell)
- [8535763](https://github.com/laravel/framework/commit/8535763fc00075279b553e8e32289419a7caf90e): fix an issue with fluent uses (#13076) [@themsaid](https://github.com/themsaid)
- [9937493](https://github.com/laravel/framework/commit/9937493de1407aebe3926eda8271fb391df5d1c1): [5.2] Correct phpdoc and complete tests (#13086)*  [@vlakoff](https://github.com/vlakoff)
- [ce36527](https://github.com/laravel/framework/commit/ce36527a2a04af22227d2c9f3382a7d02413ee14): Formatting [@GrahamCampbell](https://github.com/GrahamCampbell)
- [1ba841b](https://github.com/laravel/framework/commit/1ba841b10045b1cb1da1e0028ffbaa784a80843b): formatting and comments [@taylorotwell](https://github.com/taylorotwell)
- [dcef6c5](https://github.com/laravel/framework/commit/dcef6c5f45f37a4ab62a8623b2d0815ec4019de7): [5.1] Quote user-supplied content for use in preg_ [@vlakoff](https://github.com/vlakoff)
- [b18c01e](https://github.com/laravel/framework/commit/b18c01edc8db22d29ce7500b68b6431561489bc9): revert forcing middleware uniqueness (#13075) [@themsaid](https://github.com/themsaid)
- [229c3fa](https://github.com/laravel/framework/commit/229c3fa33e3527f5da775fa62085be9fa03e0daf): [5.2] Allow objects to be passed as pipesAllows fo [@rkgrep](https://github.com/rkgrep)
- [5b96bfa](https://github.com/laravel/framework/commit/5b96bfa662cb813ea932383726b8fda8b0e81ee8): fix conflicts [@taylorotwell](https://github.com/taylorotwell)
- [0e73cba](https://github.com/laravel/framework/commit/0e73cba565b0ef5b158da62f641dc6770b806102): increment version [@taylorotwell](https://github.com/taylorotwell)
- [de872dc](https://github.com/laravel/framework/commit/de872dcf80d81d6017f567f54c475f3923841e6d): support non numeric keys [@themsaid](https://github.com/themsaid)
- [da62677](https://github.com/laravel/framework/commit/da62677cea29ce3f5e6348c416218f11459ca3d6): Allow numerics for unix timestamps. [@taylorotwell](https://github.com/taylorotwell)
- [8f5ce59](https://github.com/laravel/framework/commit/8f5ce59e72dc73d40147f61e34ffa766a068a2bb): [5.2] Enabling array on method has()* Enabling arr [@urameshibr](https://github.com/urameshibr)
- [61eb2d2](https://github.com/laravel/framework/commit/61eb2d20b224324679135f08a0593c7dac08b67f): [5.2] Combine if statements* Combine if statements [@BrandonSurowiec](https://github.com/BrandonSurowiec)
- [a013eb2](https://github.com/laravel/framework/commit/a013eb251fa20cc8149899cc74fdb4af6217e450): formatting [@taylorotwell](https://github.com/taylorotwell)
- [16ada10](https://github.com/laravel/framework/commit/16ada102ea6684b9481652c251c28f6262d3affd): formatting and method order [@taylorotwell](https://github.com/taylorotwell)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-04-03}...5.1@{2016-04-10})
- [ce36527](https://github.com/laravel/framework/commit/ce36527a2a04af22227d2c9f3382a7d02413ee14): Formatting [@GrahamCampbell](https://github.com/GrahamCampbell)
- [dcef6c5](https://github.com/laravel/framework/commit/dcef6c5f45f37a4ab62a8623b2d0815ec4019de7): [5.1] Quote user-supplied content for use in preg_ [@vlakoff](https://github.com/vlakoff)
- [0e73cba](https://github.com/laravel/framework/commit/0e73cba565b0ef5b158da62f641dc6770b806102): increment version [@taylorotwell](https://github.com/taylorotwell)
- [da62677](https://github.com/laravel/framework/commit/da62677cea29ce3f5e6348c416218f11459ca3d6): Allow numerics for unix timestamps. [@taylorotwell](https://github.com/taylorotwell)
- [6676f51](https://github.com/laravel/framework/commit/6676f515a3d44d9603ec2a736b54219cfa5f118e): Added a test to confirm we don't crash [@GrahamCampbell](https://github.com/GrahamCampbell)
- [69f0d2b](https://github.com/laravel/framework/commit/69f0d2b725660d861a03db24a4c1dd8c68b0b0d8): Fix for bad accept headers [@GrahamCampbell](https://github.com/GrahamCampbell)
- [ba0f488](https://github.com/laravel/framework/commit/ba0f488141061f32111b21f60b12463587ef1678): Backport windows scheduling fixes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [5f6c1cf](https://github.com/laravel/framework/commit/5f6c1cf7fe1b77f47e988c16c9a17ebfad936830): revert changes to equals [@taylorotwell](https://github.com/taylorotwell)
- [360bfab](https://github.com/laravel/framework/commit/360bfab90ef63305820dbc608832887af371636d): fix multibyte string functions [@odoveiz](https://github.com/odoveiz)
- [42157b9](https://github.com/laravel/framework/commit/42157b919decb74acf02c554838136ae05346672): increment version [@taylorotwell](https://github.com/taylorotwell)
- [0b8b967](https://github.com/laravel/framework/commit/0b8b96787a220cf8da56179c99594c9555591769): Backport the composer script class [@GrahamCampbell](https://github.com/GrahamCampbell)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-04-03}...master@{2016-04-10})
- [ce25be1](https://github.com/laravel/laravel/commit/ce25be19ebfa73b53972518de629632931e77af7): Tweaked config [@GrahamCampbell](https://github.com/GrahamCampbell)


### [5.1](https://github.com/laravel/laravel/compare/5.1@{2016-04-03}...5.1@{2016-04-10})
- [a6e0a2d](https://github.com/laravel/laravel/commit/a6e0a2d190e1f219069f80434248658a5a0f79fa): Backport the composer script fixes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [2dd40df](https://github.com/laravel/laravel/commit/2dd40dfb40a005094ac50ccf6d1d96a4041807f9): Backport the phpunit fixes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [3a2cfbc](https://github.com/laravel/laravel/commit/3a2cfbc2f4f59e4c602781a8a49931c487d65f55): Backport the better faker default [@GrahamCampbell](https://github.com/GrahamCampbell)
- [2c44698](https://github.com/laravel/laravel/commit/2c446984a12f01952e9df8df1b91687e78dfe200): Backport some env tweaks [@GrahamCampbell](https://github.com/GrahamCampbell)


___

## [laravel/installer](https://github.com/laravel/installer)

### [master](https://github.com/laravel/installer/compare/master@{2016-04-03}...master@{2016-04-10})
- [bd06802](https://github.com/laravel/installer/commit/bd06802b8121e1a5e95b9028d86a2540ad07f5e1): Install into current dir [Roman Sevastyanov]


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-04-03}...master@{2016-04-10})
- [14a060c](https://github.com/laravel/docs/commit/14a060cff8849ee771bc771fd24dc80d7c83c063): remove confusign docs [@taylorotwell](https://github.com/taylorotwell)
- [862b223](https://github.com/laravel/docs/commit/862b223dd35765b4c50416b417a7d41b47819f53): Eloquent models are now unguarded by default [@whoan](https://github.com/whoan)
- [e53ea89](https://github.com/laravel/docs/commit/e53ea8966462c1aded435524c67bb601c1522f85): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [04b6a1d](https://github.com/laravel/docs/commit/04b6a1deb0d7e7a1fd682055a316ad1dc83f83b2): Document crossJoin method [@bmitch](https://github.com/bmitch)
- [f225c62](https://github.com/laravel/docs/commit/f225c62d1c6dc89af65e920a382ea96423e658b5): Tweak wording [@juukie](https://github.com/juukie)
- [a43789f](https://github.com/laravel/docs/commit/a43789f53254222e44a4efaebc09b40557546171): Add missing quote [@ntzm](https://github.com/ntzm)
- [5e5a1a6](https://github.com/laravel/docs/commit/5e5a1a6bdfda5fdca471625ad0214ceb49ba8985): wording [@taylorotwell](https://github.com/taylorotwell)
- [a831d95](https://github.com/laravel/docs/commit/a831d956f0ee62f57db5fb904fb2cd67acf9cca6): Add SparkPost mail driver [@tomswinkels](https://github.com/tomswinkels)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-04-03}...5.2@{2016-04-10})
- [45ecf40](https://github.com/laravel/docs/commit/45ecf4011b505c38f55dedb0b55743d514124c5e): Fixed wordingRemoved a duplicate "then" [@elphia](https://github.com/elphia)
- [3bd89ad](https://github.com/laravel/docs/commit/3bd89ad268a1387ff47d570865e619e4efabadb4): Fix typo in helpers.md [@DanSmith83](https://github.com/DanSmith83)
- [2b112af](https://github.com/laravel/docs/commit/2b112afef31ea390cc2f4f483ccf777d9e4938d8): remind reader where the routes are defined [@mchelen](https://github.com/mchelen)
- [351768f](https://github.com/laravel/docs/commit/351768f7ad39de0372696ef0753b369cfb969285): fix make auth command [@178inaba](https://github.com/178inaba)
- [14a060c](https://github.com/laravel/docs/commit/14a060cff8849ee771bc771fd24dc80d7c83c063): remove confusign docs [@taylorotwell](https://github.com/taylorotwell)
- [862b223](https://github.com/laravel/docs/commit/862b223dd35765b4c50416b417a7d41b47819f53): Eloquent models are now unguarded by default [@whoan](https://github.com/whoan)
- [e53ea89](https://github.com/laravel/docs/commit/e53ea8966462c1aded435524c67bb601c1522f85): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [04b6a1d](https://github.com/laravel/docs/commit/04b6a1deb0d7e7a1fd682055a316ad1dc83f83b2): Document crossJoin method [@bmitch](https://github.com/bmitch)
- [f225c62](https://github.com/laravel/docs/commit/f225c62d1c6dc89af65e920a382ea96423e658b5): Tweak wording [@juukie](https://github.com/juukie)
- [a43789f](https://github.com/laravel/docs/commit/a43789f53254222e44a4efaebc09b40557546171): Add missing quote [@ntzm](https://github.com/ntzm)
- [a831d95](https://github.com/laravel/docs/commit/a831d956f0ee62f57db5fb904fb2cd67acf9cca6): Add SparkPost mail driver [@tomswinkels](https://github.com/tomswinkels)


### [5.1](https://github.com/laravel/docs/compare/5.1@{2016-04-03}...5.1@{2016-04-10})
- [7348cbb](https://github.com/laravel/docs/commit/7348cbb8248851373aebd2a1afb1b29b09982a11): Update migrations.md [@CausaMortis](https://github.com/CausaMortis)
- [087464c](https://github.com/laravel/docs/commit/087464ca1b09a943021126e4319f75d84aad069c): Add dropForeign array notation to 5.1 docs [@CausaMortis](https://github.com/CausaMortis)


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-04-03}...5.2@{2016-04-10})
- [0a74f14](https://github.com/laravel/lumen-framework/commit/0a74f14366fee0a4939746d712dd9eb570c568c0): Fix typo in database migrations trait [@scrubmx](https://github.com/scrubmx)


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [master](https://github.com/laravel/lumen/compare/master@{2016-04-03}...master@{2016-04-10})
- [e50f63c](https://github.com/laravel/lumen/commit/e50f63c019f2d4eb1b46f878d9bb514de61d9a3e): Update the phpunit configSame as https://github.co [@scrubmx](https://github.com/scrubmx)


___

## [laravel/cashier-braintree](https://github.com/laravel/cashier-braintree)

### [1.0](https://github.com/laravel/cashier-braintree/compare/1.0@{2016-04-03}...1.0@{2016-04-10})
- [96b6925](https://github.com/laravel/cashier-braintree/commit/96b69257eeadbba9bd0333fc461565b5d0d767fe): fix finding invoices [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-04-03}...master@{2016-04-10})
- [aac2fd1](https://github.com/laravel/elixir/commit/aac2fd11fe5b7868dfe23a30d54474bfa5c2f33f): Fix notification disabling [@JeffreyWay](https://github.com/JeffreyWay)
- [7401c58](https://github.com/laravel/elixir/commit/7401c581d925f2d5bb1560d91f8c580ccad2ea51): v6rc2 [@JeffreyWay](https://github.com/JeffreyWay)
- [e19a63d](https://github.com/laravel/elixir/commit/e19a63da2d6b4d59515c8daef04b0b72c1bdbe1d): Add test app folder to npmignore [@JeffreyWay](https://github.com/JeffreyWay)
- [9e5eab7](https://github.com/laravel/elixir/commit/9e5eab7476be5009da6ec1a70dc730746f5e1e92): Remove default CoffeeScript supportExtracted to an [@JeffreyWay](https://github.com/JeffreyWay)
- [acc1e3f](https://github.com/laravel/elixir/commit/acc1e3f7509cda35fbeaec1ba8dbba3957e18653): v6 Release Candidate [@JeffreyWay](https://github.com/JeffreyWay)
- [011c260](https://github.com/laravel/elixir/commit/011c260129f19e6e1b23651377f41c4989885399): Prettier formatting [@JeffreyWay](https://github.com/JeffreyWay)
- [f58a83e](https://github.com/laravel/elixir/commit/f58a83e6f878a6634026cbcb74c32f35e361a3e2): Compile on pre-publish [@JeffreyWay](https://github.com/JeffreyWay)
- [d3fffe5](https://github.com/laravel/elixir/commit/d3fffe594c84e085514ec056c8aff6a7f448c1ab): Fix file name [@JeffreyWay](https://github.com/JeffreyWay)
- [b4e3aec](https://github.com/laravel/elixir/commit/b4e3aec0e9ac246add274197be1cbce835fc96aa): Add tests for TaskCollection [@JeffreyWay](https://github.com/JeffreyWay)
- [d7bb8ad](https://github.com/laravel/elixir/commit/d7bb8adf842d58448836d27c0d4d2c588217c594): Add dist/ to gitignore [@JeffreyWay](https://github.com/JeffreyWay)
- [4a73b1e](https://github.com/laravel/elixir/commit/4a73b1ec97d490215f878ed53b9be158ba2e61f9): ES6 conversion work [@JeffreyWay](https://github.com/JeffreyWay)
- [03eb8b7](https://github.com/laravel/elixir/commit/03eb8b70aa3605d5ad3322c3090ad492b447cf75): Add npmignore [@JeffreyWay](https://github.com/JeffreyWay)
- [aaae364](https://github.com/laravel/elixir/commit/aaae364d338b5ef91deba7fe5b781542b6fb04dd): Working on conversion to ES6 [@JeffreyWay](https://github.com/JeffreyWay)


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [You Have To Be Meticulous](http://laracasts.simplecast.fm/20)

### [Laravel News Podcast](https://laravel-news.com)
- [EP13 Still good stuff to talk about before Spark!](http://podcast.laravel-news.com/13)


___

## [Laracasts](https://laracasts.com)
- [Consider Domain Events](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/3)
- [Conclusion](https://laracasts.com/series/laravel-5-from-scratch/episodes/18)
- [Dedicated Graph Vue Components](https://laracasts.com/series/charting-and-you/episodes/5)
- [Dedicated Query String Filtering](https://laracasts.com/series/eloquent-techniques/episodes/4)
