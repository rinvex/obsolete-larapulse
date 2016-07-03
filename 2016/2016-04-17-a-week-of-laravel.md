---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (10-17 April 2016)
post::title: A week of Laravel (10-17 April 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [5.1], laravel/installer [master], laravel/docs [5.2], laravel/homestead [master], laravel/lumen [master], laravel/lumen-installer [master], laravel/laravel.com [master], laravel/settler [master], laravel/socialite [2.0], laravel/envoy [master], Podcasts: The Laravel Podcast, The Laracasts Snippet, Laracasts"
post::date: April 17, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-04-10}...master@{2016-04-17})
- [d08b708](https://github.com/laravel/framework/commit/d08b70838e39ae1f558b435ab4e21f3321dd39c8): Synced with stringy 2.3.1 [@GrahamCampbell](https://github.com/GrahamCampbell)
- [40ccd57](https://github.com/laravel/framework/commit/40ccd57d151a73f06bbf9d1ba19e355f9062628c): Correct order [@GrahamCampbell](https://github.com/GrahamCampbell)
- [b45df80](https://github.com/laravel/framework/commit/b45df80eca0d6cbe9e78600b2db31a03f3fe8fb5): Added missing debug dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [913487a](https://github.com/laravel/framework/commit/913487a021365f07447d2ff8cfba22c88c393076): Intersect Method for Illuminate Request (#13167) [@AdenFraser](https://github.com/AdenFraser)
- [8444190](https://github.com/laravel/framework/commit/8444190a742d7d77818f3938b214a95a4585ea35): Remove extra space [@TheGIBSON](https://github.com/TheGIBSON)
- [4dc5626](https://github.com/laravel/framework/commit/4dc56266c4b8a95976bef7f6c37bb3dce7a6b06d): code tweaking. [@taylorotwell](https://github.com/taylorotwell)
- [4c370cf](https://github.com/laravel/framework/commit/4c370cf6f9dd288751799dbc32b6fc67b11e02b3): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [522ab43](https://github.com/laravel/framework/commit/522ab43872f3f5c107e5a7114f9476084498ff60): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [537e861](https://github.com/laravel/framework/commit/537e8613d806a6aaae93d5f2735bd2842d984f03): Add makeHidden method to the Eloquent collection c [@JosephSilber](https://github.com/JosephSilber)
- [ebe8bd6](https://github.com/laravel/framework/commit/ebe8bd68a597540769b3fe4111e626575be59ebe): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [93e41ea](https://github.com/laravel/framework/commit/93e41eabaf6dd7e5c7ec90ca5e4b1f7e4da50553): Allow "on" clauses on cross joins [@raphaelsaunier](https://github.com/raphaelsaunier)
- [9cdcb39](https://github.com/laravel/framework/commit/9cdcb39ced461e34a94bcf6cd00dd8d26c3d3b65): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [77d4ef7](https://github.com/laravel/framework/commit/77d4ef79f3ccea95f00702db031e432a518d6200): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [fbcf444](https://github.com/laravel/framework/commit/fbcf44403bfa651e4e624922411c6339399c30bf): fix documentation typo (#13149)is() calls currentR [@lukeb](https://github.com/lukeb)
- [83d370d](https://github.com/laravel/framework/commit/83d370d742d0d18f976ac8aadf67874acfdf9bca): Update helpers.phpFix docblocks. [@fire015](https://github.com/fire015)
- [848326a](https://github.com/laravel/framework/commit/848326aa6cdb286e71595d1a8686c12bfecf1fa9): add comment [@taylorotwell](https://github.com/taylorotwell)
- [d80cd3a](https://github.com/laravel/framework/commit/d80cd3a13b4e5d8e8b21d7ee89781144ead10054): rename method [@taylorotwell](https://github.com/taylorotwell)
- [cd21d82](https://github.com/laravel/framework/commit/cd21d824846ad8be983ca97a7a627df993bbacf6): Add the ability to get routes keyed by method [@TheGIBSON](https://github.com/TheGIBSON)
- [30f3ce7](https://github.com/laravel/framework/commit/30f3ce73ae9c4d2fcaf7da1d2447375694d97852): Fixed some phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-04-10}...5.2@{2016-04-17})
- [cf7f46d](https://github.com/laravel/framework/commit/cf7f46db94a9203c6880505366262df99c846107): [5.2] Add a View test from compiling to rendering  [@mark86092](https://github.com/mark86092)
- [d08b708](https://github.com/laravel/framework/commit/d08b70838e39ae1f558b435ab4e21f3321dd39c8): Synced with stringy 2.3.1 [@GrahamCampbell](https://github.com/GrahamCampbell)
- [40ccd57](https://github.com/laravel/framework/commit/40ccd57d151a73f06bbf9d1ba19e355f9062628c): Correct order [@GrahamCampbell](https://github.com/GrahamCampbell)
- [b45df80](https://github.com/laravel/framework/commit/b45df80eca0d6cbe9e78600b2db31a03f3fe8fb5): Added missing debug dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [913487a](https://github.com/laravel/framework/commit/913487a021365f07447d2ff8cfba22c88c393076): Intersect Method for Illuminate Request (#13167) [@AdenFraser](https://github.com/AdenFraser)
- [8444190](https://github.com/laravel/framework/commit/8444190a742d7d77818f3938b214a95a4585ea35): Remove extra space [@TheGIBSON](https://github.com/TheGIBSON)
- [537e861](https://github.com/laravel/framework/commit/537e8613d806a6aaae93d5f2735bd2842d984f03): Add makeHidden method to the Eloquent collection c [@JosephSilber](https://github.com/JosephSilber)
- [ebe8bd6](https://github.com/laravel/framework/commit/ebe8bd68a597540769b3fe4111e626575be59ebe): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [93e41ea](https://github.com/laravel/framework/commit/93e41eabaf6dd7e5c7ec90ca5e4b1f7e4da50553): Allow "on" clauses on cross joins [@raphaelsaunier](https://github.com/raphaelsaunier)
- [9cdcb39](https://github.com/laravel/framework/commit/9cdcb39ced461e34a94bcf6cd00dd8d26c3d3b65): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [77d4ef7](https://github.com/laravel/framework/commit/77d4ef79f3ccea95f00702db031e432a518d6200): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [fbcf444](https://github.com/laravel/framework/commit/fbcf44403bfa651e4e624922411c6339399c30bf): fix documentation typo (#13149)is() calls currentR [@lukeb](https://github.com/lukeb)
- [83d370d](https://github.com/laravel/framework/commit/83d370d742d0d18f976ac8aadf67874acfdf9bca): Update helpers.phpFix docblocks. [@fire015](https://github.com/fire015)
- [848326a](https://github.com/laravel/framework/commit/848326aa6cdb286e71595d1a8686c12bfecf1fa9): add comment [@taylorotwell](https://github.com/taylorotwell)
- [d80cd3a](https://github.com/laravel/framework/commit/d80cd3a13b4e5d8e8b21d7ee89781144ead10054): rename method [@taylorotwell](https://github.com/taylorotwell)
- [cd21d82](https://github.com/laravel/framework/commit/cd21d824846ad8be983ca97a7a627df993bbacf6): Add the ability to get routes keyed by method [@TheGIBSON](https://github.com/TheGIBSON)
- [30f3ce7](https://github.com/laravel/framework/commit/30f3ce73ae9c4d2fcaf7da1d2447375694d97852): Fixed some phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)
- [5801a7b](https://github.com/laravel/framework/commit/5801a7b9ddb17611aff9153a6324c12cd2f8ad0c): Update PostgresGrammar.php (#13132) [@filipeaclima](https://github.com/filipeaclima)
- [02319da](https://github.com/laravel/framework/commit/02319dacb670c74ab13e09f44f7fc95ad1f617d0): [5.2] Test chainability of $query->when() (#13134) [@vlakoff](https://github.com/vlakoff)
- [5740581](https://github.com/laravel/framework/commit/57405810e2470832003cc6409a6940ddffa925a1): Add prefix to the table name before querying a col [@willrowe](https://github.com/willrowe)
- [fbb4bda](https://github.com/laravel/framework/commit/fbb4bda9639461a7533eb811b88b961804c167be): dont limit columns selection while chunking by id  [@themsaid](https://github.com/themsaid)
- [3079175](https://github.com/laravel/framework/commit/307917505bbc1ef9f8e3b9442c92bbbf79cafa45): Fix bug in listener generation.This prevents the f [@taylorotwell](https://github.com/taylorotwell)
- [6e9a6a2](https://github.com/laravel/framework/commit/6e9a6a250bdae4f4c84877eb90f59afcc6359379): Fix docblock (#13129) [@mustafaaloko](https://github.com/mustafaaloko)
- [fcf49d4](https://github.com/laravel/framework/commit/fcf49d427c59de237c2e71190d8a235efe656eee): small typo [@themsaid](https://github.com/themsaid)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-04-10}...5.1@{2016-04-17})
- [b45df80](https://github.com/laravel/framework/commit/b45df80eca0d6cbe9e78600b2db31a03f3fe8fb5): Added missing debug dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [9cdcb39](https://github.com/laravel/framework/commit/9cdcb39ced461e34a94bcf6cd00dd8d26c3d3b65): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)
- [77d4ef7](https://github.com/laravel/framework/commit/77d4ef79f3ccea95f00702db031e432a518d6200): Added missing suggested dependency [@GrahamCampbell](https://github.com/GrahamCampbell)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [5.1](https://github.com/laravel/laravel/compare/5.1@{2016-04-10}...5.1@{2016-04-17})
- [2c834ad](https://github.com/laravel/laravel/commit/2c834ad59c63535ea6e22c659ede67c0ddce1874): Respect PSR-2 [@GrahamCampbell](https://github.com/GrahamCampbell)


___

## [laravel/installer](https://github.com/laravel/installer)

### [master](https://github.com/laravel/installer/compare/master@{2016-04-10}...master@{2016-04-17})
- [b0e87ee](https://github.com/laravel/installer/commit/b0e87ee601bdd1132da42054d9462b9546ba5882): increment version [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/docs](https://github.com/laravel/docs)

### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-04-10}...5.2@{2016-04-17})
- [1a22326](https://github.com/laravel/docs/commit/1a223262769129ea94299c673d05911b14183030): fix spelling mistake [@taylorotwell](https://github.com/taylorotwell)
- [32aa983](https://github.com/laravel/docs/commit/32aa98333744e0506cb2dfdf85a73d35ecb5e79e): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [6157798](https://github.com/laravel/docs/commit/6157798c952ae1d7d7d57f15dc796908b5150eda): Add SQLite section and indicate .env configuration [@mpavel](https://github.com/mpavel)
- [3c35d9c](https://github.com/laravel/docs/commit/3c35d9c7d5d91e190d57c9cbda50207d8ba95cb1): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [61dbf68](https://github.com/laravel/docs/commit/61dbf68eea758d922a0441c3132550c85f3379f4): update wording [@taylorotwell](https://github.com/taylorotwell)
- [4241e87](https://github.com/laravel/docs/commit/4241e87d97502fbd6b3e13d0fa866b9a31d40e9f): Fix wordingRemove a duplicate 'to' [@elphia](https://github.com/elphia)
- [820106d](https://github.com/laravel/docs/commit/820106df66319d832ab946891bc3c06ddd3bc266): added doc for wherePivot() and wherePivotIn() [@hamedmehryar](https://github.com/hamedmehryar)
- [248830f](https://github.com/laravel/docs/commit/248830f26436db4cf958c8c5a5ba775c29e19c54): Fix wordingChanged "passing Closure" to "passing a [@elphia](https://github.com/elphia)
- [43e8aea](https://github.com/laravel/docs/commit/43e8aea4234340c084f619bd0b2b917889026857): Add Public Driver explanation [@barryvdh](https://github.com/barryvdh)
- [0e29052](https://github.com/laravel/docs/commit/0e2905269f37374eecd1f1e028614afcfdb6553e): Fix coding style (in code block)So that it matches [@kiaking](https://github.com/kiaking)
- [af6ff15](https://github.com/laravel/docs/commit/af6ff15efccbd79d6653bc7f8621fa26361c425b): Fix wordingRemove a duplicate "the" [@elphia](https://github.com/elphia)


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-04-10}...master@{2016-04-17})
- [2dac29d](https://github.com/laravel/homestead/commit/2dac29d8bab4792add96a3e249adec70e7b764ec): add hostupdater support in localized vagrant [@gperdomor](https://github.com/gperdomor)


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [master](https://github.com/laravel/lumen/compare/master@{2016-04-10}...master@{2016-04-17})
- [1239256](https://github.com/laravel/lumen/commit/1239256de8ec6d37a8df3471aa1f8cc46b27a456): Applied fixes from StyleCI [@GrahamCampbell](https://github.com/GrahamCampbell)
- [ab5efb8](https://github.com/laravel/lumen/commit/ab5efb847e05a508070c83de617492c0d9ff9b55): Update DatabaseSeeder.phpLet's make it consistent  [@howlowck](https://github.com/howlowck)


___

## [laravel/lumen-installer](https://github.com/laravel/lumen-installer)

### [master](https://github.com/laravel/lumen-installer/compare/master@{2016-04-10}...master@{2016-04-17})
- [79f0656](https://github.com/laravel/lumen-installer/commit/79f0656b2499744eac82f662caf091a210340705): increment version [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-04-10}...master@{2016-04-17})
- [a7c17a1](https://github.com/laravel/laravel.com/commit/a7c17a148f1f05f7ee9ebdb5ad6930eee0b2b12c): fix typo [@taylorotwell](https://github.com/taylorotwell)
- [ec50131](https://github.com/laravel/laravel.com/commit/ec50131ff07caed88716b6a1aeef8a0341795382): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [c0d1c1c](https://github.com/laravel/laravel.com/commit/c0d1c1cc5252bc6427cf044df991c6417bc103e4): wip [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/settler](https://github.com/laravel/settler)

### [master](https://github.com/laravel/settler/compare/master@{2016-04-10}...master@{2016-04-17})
- [b90b50f](https://github.com/laravel/settler/commit/b90b50f4e1fa13a3d0c9fd849dac29de5fa3b343): Execute under vagrant user instead of rootThis to  [@ibrahimmomani](https://github.com/ibrahimmomani)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-04-10}...2.0@{2016-04-17})
- [e0fbc71](https://github.com/laravel/socialite/commit/e0fbc71969b6fdb9ca20199104f2d986a53505b8): Update Facebook Graph API version to v2.6 [@SammyK](https://github.com/SammyK)


___

## [laravel/envoy](https://github.com/laravel/envoy)

### [master](https://github.com/laravel/envoy/compare/master@{2016-04-10}...master@{2016-04-17})
- [e40ee15](https://github.com/laravel/envoy/commit/e40ee1519a32b90fbcc7a823c42da11f257b632c): Fixes dependency conflicts.When installing globall [@irazasyed](https://github.com/irazasyed)


___

## Podcasts

### [The Laravel Podcast](http://laravel.com)
- [Episode 44: I Like The CranApple](http://www.laravelpodcast.com/episodes/35051-episode-44-i-like-the-cranapple)

### [The Laracasts Snippet](http://laracasts.audio)
- [8 Marketing Tips for Developers That Cost Nothing](http://laracasts.simplecast.fm/21)


___

## [Laracasts](https://laracasts.com)
- [Graphs and AJAX](https://laracasts.com/series/charting-and-you/episodes/7)
- [God Object Cleanup #2: Traits and Socks ](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/5)
- [Accessing the Current Team](https://laracasts.com/series/laravel-spark/episodes/4)
- [Intro to Team Billing](https://laracasts.com/series/laravel-spark/episodes/3)
- [God Object Cleanup #1: Pass-Through](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/4)
- [How to Configure Your New App](https://laracasts.com/series/laravel-spark/episodes/2)
- [What is Spark?](https://laracasts.com/series/laravel-spark/episodes/1)
- [Render Monthly Revenue](https://laracasts.com/series/charting-and-you/episodes/6)
