---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (08-15 May 2016)
post::title: A week of Laravel (08-15 May 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [develop], laravel/docs [master], laravel/docs [5.2], laravel/homestead [master], laravel/lumen-framework [master], laravel/lumen-framework [5.2], laravel/lumen-docs [5.1], laravel/socialite [2.0], laravel/elixir [master], Laracasts "
post::date: May 15, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-05-08}...master@{2016-05-15})
- [738d96f](https://github.com/laravel/framework/commit/738d96f47a5eac923a6e9fa7cbbf3d6ccc46c9f9): Typehint DateTimeInterface instead of DateTime (#1 [@kcjpop](https://github.com/kcjpop)
- [52b3191](https://github.com/laravel/framework/commit/52b319190fa0382890038ad5884b452b4b27af52): rename methods [@taylorotwell](https://github.com/taylorotwell)
- [b5aea44](https://github.com/laravel/framework/commit/b5aea4428e977322f76805e294af681da6f61ff7): reverting PR #13334 (#13532) [@themsaid](https://github.com/themsaid)
- [fb0832b](https://github.com/laravel/framework/commit/fb0832ba010847ef8c0709ea3f9bfdccd3a74f4c): a couple fixes to broadcasting [@taylorotwell](https://github.com/taylorotwell)
- [eedb619](https://github.com/laravel/framework/commit/eedb619baa97105901d7256166df8875afd71c59): one line [@taylorotwell](https://github.com/taylorotwell)
- [c71d168](https://github.com/laravel/framework/commit/c71d16886218b423161ba247d254a17068409947): [5.2] Allow Request::intersect() to accept argumen [@mul14](https://github.com/mul14)
- [e254132](https://github.com/laravel/framework/commit/e254132edd19fea9b7749204de7a714644a53a53): Make MakesHttpRequest methods accept method chaini [@sileence](https://github.com/sileence)
- [9ea735d](https://github.com/laravel/framework/commit/9ea735d9cea87d497146147e2c99c391132e6b1d): tweak code [@taylorotwell](https://github.com/taylorotwell)
- [ec37704](https://github.com/laravel/framework/commit/ec377048d75c69a7e91b3722bacb048540e91ac4): [5.1] Bring back support for Carbon instances to B [@MacWorks](https://github.com/MacWorks)
- [347cbff](https://github.com/laravel/framework/commit/347cbff7cb6227bdec445d1ad24efe035ef67701): [5.2] Add page parameter to the simplePaginate met [@Chimit](https://github.com/Chimit)
- [09ea8e2](https://github.com/laravel/framework/commit/09ea8e2f321195d8518952cdbfa5746c9799cdc1): tweak code style [@taylorotwell](https://github.com/taylorotwell)
- [e164b5e](https://github.com/laravel/framework/commit/e164b5e8e8769a46fbea46f92fd7a3a186da28ad): Fix replacing route default parameters. (#13514) [@butschster](https://github.com/butschster)
- [45fb881](https://github.com/laravel/framework/commit/45fb88125fc931127804c1da111b72798565e9a7): Account for __isset changes in PHP 7Update: this i [@tmiskin](https://github.com/tmiskin)
- [057d26a](https://github.com/laravel/framework/commit/057d26a249b75f42c47b9b309477de3163a5bb53): Updated docblock (#13499) [@srmklive](https://github.com/srmklive)
- [2998e89](https://github.com/laravel/framework/commit/2998e8960b2b8c5ed316fa66e9d70c99d8bb0b68): Fixed phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell)
- [04f8e48](https://github.com/laravel/framework/commit/04f8e48171a0881408028fb1322592607e3d17ee): Fixed docblock [@srmklive](https://github.com/srmklive)
- [bd8d6bc](https://github.com/laravel/framework/commit/bd8d6bce78fbe1c589880de200803dce2bfae80b): Fixed typo [@srmklive](https://github.com/srmklive)
- [67b821d](https://github.com/laravel/framework/commit/67b821dde62e64f94aa7d99f1806ecf03ea323e5): Rename to withCount, auto column names, default se [Barry vd. Heuvel]
- [583e02b](https://github.com/laravel/framework/commit/583e02b5a2d811c8ad630c7ee32f2cf926a41354): added closure based console commands [@taylorotwell](https://github.com/taylorotwell)
- [e86c4a4](https://github.com/laravel/framework/commit/e86c4a472bae7aeefb7f671c2cd8853fd35f8b82): [5.2] Stabilized table aliases for self joins by a [@JeroenVanOort](https://github.com/JeroenVanOort)
- [607a720](https://github.com/laravel/framework/commit/607a720edccf73e040b6e8da236d521f52ddc66b): tweakings [@taylorotwell](https://github.com/taylorotwell)
- [12de64b](https://github.com/laravel/framework/commit/12de64b55af947145a5bccb8ab1b42a627381640): Use SymfonyExceptionHandler@getHtml method to conv [@sadika9](https://github.com/sadika9)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-05-08}...5.2@{2016-05-15})
- [0fecd60](https://github.com/laravel/framework/commit/0fecd603347b74c954d74d8b7c38658a2c344aa7): Fix PHPDoc collection union() return type [@mologie](https://github.com/mologie)
- [d06c52a](https://github.com/laravel/framework/commit/d06c52abf8728d064ac69a29a27c4cbb942b1ba7): use getPdo [@taylorotwell](https://github.com/taylorotwell)
- [c8fbb8e](https://github.com/laravel/framework/commit/c8fbb8e90d93559e9c0239e928e3f62b91f4f5a0): [5.1] Decrement transaction count when beginTransa [@kmfk](https://github.com/kmfk)
- [8c51aa5](https://github.com/laravel/framework/commit/8c51aa5427f90c0bf37e16cbdc2567255e91afac): Removed unneeded slashes [@GrahamCampbell](https://github.com/GrahamCampbell)
- [07177e9](https://github.com/laravel/framework/commit/07177e94983f20d478026dc93278c05f6f18c0dd): fix #13527 (#13537) [@themsaid](https://github.com/themsaid)
- [eedb619](https://github.com/laravel/framework/commit/eedb619baa97105901d7256166df8875afd71c59): one line [@taylorotwell](https://github.com/taylorotwell)
- [c71d168](https://github.com/laravel/framework/commit/c71d16886218b423161ba247d254a17068409947): [5.2] Allow Request::intersect() to accept argumen [@mul14](https://github.com/mul14)
- [e254132](https://github.com/laravel/framework/commit/e254132edd19fea9b7749204de7a714644a53a53): Make MakesHttpRequest methods accept method chaini [@sileence](https://github.com/sileence)
- [9ea735d](https://github.com/laravel/framework/commit/9ea735d9cea87d497146147e2c99c391132e6b1d): tweak code [@taylorotwell](https://github.com/taylorotwell)
- [ec37704](https://github.com/laravel/framework/commit/ec377048d75c69a7e91b3722bacb048540e91ac4): [5.1] Bring back support for Carbon instances to B [@MacWorks](https://github.com/MacWorks)
- [347cbff](https://github.com/laravel/framework/commit/347cbff7cb6227bdec445d1ad24efe035ef67701): [5.2] Add page parameter to the simplePaginate met [@Chimit](https://github.com/Chimit)
- [09ea8e2](https://github.com/laravel/framework/commit/09ea8e2f321195d8518952cdbfa5746c9799cdc1): tweak code style [@taylorotwell](https://github.com/taylorotwell)
- [e164b5e](https://github.com/laravel/framework/commit/e164b5e8e8769a46fbea46f92fd7a3a186da28ad): Fix replacing route default parameters. (#13514) [@butschster](https://github.com/butschster)
- [45fb881](https://github.com/laravel/framework/commit/45fb88125fc931127804c1da111b72798565e9a7): Account for __isset changes in PHP 7Update: this i [@tmiskin](https://github.com/tmiskin)
- [057d26a](https://github.com/laravel/framework/commit/057d26a249b75f42c47b9b309477de3163a5bb53): Updated docblock (#13499) [@srmklive](https://github.com/srmklive)
- [bd8d6bc](https://github.com/laravel/framework/commit/bd8d6bce78fbe1c589880de200803dce2bfae80b): Fixed typo [@srmklive](https://github.com/srmklive)
- [67b821d](https://github.com/laravel/framework/commit/67b821dde62e64f94aa7d99f1806ecf03ea323e5): Rename to withCount, auto column names, default se [Barry vd. Heuvel]
- [e86c4a4](https://github.com/laravel/framework/commit/e86c4a472bae7aeefb7f671c2cd8853fd35f8b82): [5.2] Stabilized table aliases for self joins by a [@JeroenVanOort](https://github.com/JeroenVanOort)
- [607a720](https://github.com/laravel/framework/commit/607a720edccf73e040b6e8da236d521f52ddc66b): tweakings [@taylorotwell](https://github.com/taylorotwell)
- [5bd75c8](https://github.com/laravel/framework/commit/5bd75c855810f898b8fe1919e29c4e42132b1866): fix method name [@taylorotwell](https://github.com/taylorotwell)
- [892f913](https://github.com/laravel/framework/commit/892f913c94a414a61fda52f5561796c10a9ac492): Revert "[5.2] Use SymfonyExceptionHandler@getHtml  [@taylorotwell](https://github.com/taylorotwell)
- [77b813d](https://github.com/laravel/framework/commit/77b813df807df1f53e2eb82dad78c7759658d423): Use SymfonyExceptionHandler@getHtml method to conv [@sadika9](https://github.com/sadika9)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-05-08}...5.1@{2016-05-15})
- [c8fbb8e](https://github.com/laravel/framework/commit/c8fbb8e90d93559e9c0239e928e3f62b91f4f5a0): [5.1] Decrement transaction count when beginTransa [@kmfk](https://github.com/kmfk)
- [ec37704](https://github.com/laravel/framework/commit/ec377048d75c69a7e91b3722bacb048540e91ac4): [5.1] Bring back support for Carbon instances to B [@MacWorks](https://github.com/MacWorks)
- [09ea8e2](https://github.com/laravel/framework/commit/09ea8e2f321195d8518952cdbfa5746c9799cdc1): tweak code style [@taylorotwell](https://github.com/taylorotwell)
- [45fb881](https://github.com/laravel/framework/commit/45fb88125fc931127804c1da111b72798565e9a7): Account for __isset changes in PHP 7Update: this i [@tmiskin](https://github.com/tmiskin)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-05-08}...master@{2016-05-15})
- [da64a01](https://github.com/laravel/laravel/commit/da64a014e749d1d4164b147fe79bfd7d86158aa5): Add language line for image dimensions validation  [@themsaid](https://github.com/themsaid)


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-05-08}...develop@{2016-05-15})
- [e7ff2bf](https://github.com/laravel/laravel/commit/e7ff2bfb4d6ca306f0fcf2b449ab51ce549bbf16): update method [@taylorotwell](https://github.com/taylorotwell)
- [8fc0df1](https://github.com/laravel/laravel/commit/8fc0df14bbdbd19c888da048d875c1d109083904): Add "sslmode" setting for PostgreSQL connectionThe [@scrubmx](https://github.com/scrubmx)
- [f237656](https://github.com/laravel/laravel/commit/f237656c687bec2c53a09c9eefbe9c897aacdf1c): Enabled MySQL "strict" mode by default [@Adam14Four](https://github.com/Adam14Four)
- [59f2d49](https://github.com/laravel/laravel/commit/59f2d49074a76d8863cd9aecfb23edf1c1651fcc): stub out commands method in console kernel [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-05-08}...master@{2016-05-15})
- [0d0f113](https://github.com/laravel/docs/commit/0d0f113c4768ab5568820802a2567624b9966a88): wip [@taylorotwell](https://github.com/taylorotwell)
- [1968a5b](https://github.com/laravel/docs/commit/1968a5b3ef5c458d94fc405980fd2fcf691b6fa4): added bedrock [@taylorotwell](https://github.com/taylorotwell)
- [ad4f69c](https://github.com/laravel/docs/commit/ad4f69c13d6b0c2584feb09248e7e240ec00cef6): securing sites [@taylorotwell](https://github.com/taylorotwell)
- [cce4131](https://github.com/laravel/docs/commit/cce41314541761a68f9055d7b1c72257d01bf362): Fix typo [@lin-lu](https://github.com/lin-lu)
- [49510e3](https://github.com/laravel/docs/commit/49510e3d2439203bf810041933acf30ccbff4e35): valet release notes [@taylorotwell](https://github.com/taylorotwell)
- [3dacba2](https://github.com/laravel/docs/commit/3dacba260c452555f714590bdc0256f4d17ea50c): tweak wording [@taylorotwell](https://github.com/taylorotwell)
- [16bafeb](https://github.com/laravel/docs/commit/16bafebf641823a83f599077a5aa0525d3cc68e7): fix link [@taylorotwell](https://github.com/taylorotwell)
- [8f80f6c](https://github.com/laravel/docs/commit/8f80f6c82be9107f42a8780507bb469fdc3bd3c7): wip [@taylorotwell](https://github.com/taylorotwell)
- [c7ae23d](https://github.com/laravel/docs/commit/c7ae23dae8f6e10a3843d081ad2b315d8a34717a): wip [@taylorotwell](https://github.com/taylorotwell)
- [e51da75](https://github.com/laravel/docs/commit/e51da7569ad84e77be394aa73ae0e1ff7229f88a): wip [@taylorotwell](https://github.com/taylorotwell)
- [acfd8fa](https://github.com/laravel/docs/commit/acfd8fac4df9a1ed45c200c4151e89aba6a999ab): list [@taylorotwell](https://github.com/taylorotwell)
- [2515805](https://github.com/laravel/docs/commit/25158054aa0b97675cc7b9bb88529da28610fcdf): added to supported list [@taylorotwell](https://github.com/taylorotwell)
- [b49a5c2](https://github.com/laravel/docs/commit/b49a5c2eaeaeef76edd755f2b2b6d08e18d3a322): Valet doesn’t use PHP’s built-in server anymor [@miclf](https://github.com/miclf)
- [7318401](https://github.com/laravel/docs/commit/7318401f43164693f8da5b0dc3cbe8c6e3ae07aa): Improved homestead function for daily usageIt no l [@mabasic](https://github.com/mabasic)
- [03da7f7](https://github.com/laravel/docs/commit/03da7f718438c7f080c332992dbf62f75c9f024c): Add instructions for the new dimensions rule [@themsaid](https://github.com/themsaid)
- [f6b5ae8](https://github.com/laravel/docs/commit/f6b5ae8ab8042401e38d215d5b8a531fbfd9b178): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [3667161](https://github.com/laravel/docs/commit/366716193ddb91b6034e236fd258ccd316b36049): working on notes [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-05-08}...5.2@{2016-05-15})
- [0d0f113](https://github.com/laravel/docs/commit/0d0f113c4768ab5568820802a2567624b9966a88): wip [@taylorotwell](https://github.com/taylorotwell)
- [1968a5b](https://github.com/laravel/docs/commit/1968a5b3ef5c458d94fc405980fd2fcf691b6fa4): added bedrock [@taylorotwell](https://github.com/taylorotwell)
- [ad4f69c](https://github.com/laravel/docs/commit/ad4f69c13d6b0c2584feb09248e7e240ec00cef6): securing sites [@taylorotwell](https://github.com/taylorotwell)
- [cce4131](https://github.com/laravel/docs/commit/cce41314541761a68f9055d7b1c72257d01bf362): Fix typo [@lin-lu](https://github.com/lin-lu)
- [49510e3](https://github.com/laravel/docs/commit/49510e3d2439203bf810041933acf30ccbff4e35): valet release notes [@taylorotwell](https://github.com/taylorotwell)
- [3dacba2](https://github.com/laravel/docs/commit/3dacba260c452555f714590bdc0256f4d17ea50c): tweak wording [@taylorotwell](https://github.com/taylorotwell)
- [16bafeb](https://github.com/laravel/docs/commit/16bafebf641823a83f599077a5aa0525d3cc68e7): fix link [@taylorotwell](https://github.com/taylorotwell)
- [8f80f6c](https://github.com/laravel/docs/commit/8f80f6c82be9107f42a8780507bb469fdc3bd3c7): wip [@taylorotwell](https://github.com/taylorotwell)
- [e51da75](https://github.com/laravel/docs/commit/e51da7569ad84e77be394aa73ae0e1ff7229f88a): wip [@taylorotwell](https://github.com/taylorotwell)
- [acfd8fa](https://github.com/laravel/docs/commit/acfd8fac4df9a1ed45c200c4151e89aba6a999ab): list [@taylorotwell](https://github.com/taylorotwell)
- [b49a5c2](https://github.com/laravel/docs/commit/b49a5c2eaeaeef76edd755f2b2b6d08e18d3a322): Valet doesn’t use PHP’s built-in server anymor [@miclf](https://github.com/miclf)
- [7318401](https://github.com/laravel/docs/commit/7318401f43164693f8da5b0dc3cbe8c6e3ae07aa): Improved homestead function for daily usageIt no l [@mabasic](https://github.com/mabasic)
- [03da7f7](https://github.com/laravel/docs/commit/03da7f718438c7f080c332992dbf62f75c9f024c): Add instructions for the new dimensions rule [@themsaid](https://github.com/themsaid)
- [f6b5ae8](https://github.com/laravel/docs/commit/f6b5ae8ab8042401e38d215d5b8a531fbfd9b178): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [3667161](https://github.com/laravel/docs/commit/366716193ddb91b6034e236fd258ccd316b36049): working on notes [@taylorotwell](https://github.com/taylorotwell)
- [22993b4](https://github.com/laravel/docs/commit/22993b4766b938c12c36f956f627f4df5c6d9dd7): 1.1.0 valet docs [@taylorotwell](https://github.com/taylorotwell)
- [97f72dd](https://github.com/laravel/docs/commit/97f72ddf46e4d25368121ea4c069c3a15ceea6e5): tweak wording and sapcing [@taylorotwell](https://github.com/taylorotwell)
- [5f05372](https://github.com/laravel/docs/commit/5f053722c4bb17d6b17f72dddd105e927eeb13de): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [2152fe3](https://github.com/laravel/docs/commit/2152fe3fe6b29f55270e50fda8340c634909753c): remove double via [@taylorotwell](https://github.com/taylorotwell)
- [6b81be6](https://github.com/laravel/docs/commit/6b81be65398d2130e6e6aafa1ecddfd8ea5b4810): Simplify valet docs [@lucasmichot](https://github.com/lucasmichot)
- [6d407f0](https://github.com/laravel/docs/commit/6d407f09ff3ce8e10a2e8cc8767f6088b0e79230): Document the `valet domain` command [@adamwathan](https://github.com/adamwathan)


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-05-08}...master@{2016-05-15})
- [f70ef35](https://github.com/laravel/homestead/commit/f70ef359bbdca5f39165a24b6f0a2d75e72616c2): tweak comment [@taylorotwell](https://github.com/taylorotwell)
- [ad0f938](https://github.com/laravel/homestead/commit/ad0f938a90be2e6267a1316add8828749b42a6b3): tweak a few things when creating sites [@taylorotwell](https://github.com/taylorotwell)
- [900f865](https://github.com/laravel/homestead/commit/900f865ff0d913ab4025989996e640047e1c1227): bindfs support added [@SumonMSelim](https://github.com/SumonMSelim)


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-05-08}...master@{2016-05-15})
- [5b2e8d1](https://github.com/laravel/lumen-framework/commit/5b2e8d15b5aac9c161bc80475703f15a13a83867): change method order [@taylorotwell](https://github.com/taylorotwell)
- [ed23d7b](https://github.com/laravel/lumen-framework/commit/ed23d7bb257e949d5fa1d7fce0002c1154854a69): Add seeHeader method to MakesHttpRequests traitThi [@scrubmx](https://github.com/scrubmx)


### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-05-08}...5.2@{2016-05-15})
- [5b2e8d1](https://github.com/laravel/lumen-framework/commit/5b2e8d15b5aac9c161bc80475703f15a13a83867): change method order [@taylorotwell](https://github.com/taylorotwell)
- [ed23d7b](https://github.com/laravel/lumen-framework/commit/ed23d7bb257e949d5fa1d7fce0002c1154854a69): Add seeHeader method to MakesHttpRequests traitThi [@scrubmx](https://github.com/scrubmx)


___

## [laravel/lumen-docs](https://github.com/laravel/lumen-docs)

### [5.1](https://github.com/laravel/lumen-docs/compare/5.1@{2016-05-08}...5.1@{2016-05-15})
- [046a9f9](https://github.com/laravel/lumen-docs/commit/046a9f9ad1d386d33cd2f3c78f4c9e6a6eb0d888): Fix response function syntax`response()->view()->. [@cydrobolt](https://github.com/cydrobolt)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-05-08}...2.0@{2016-05-15})
- [c6f767b](https://github.com/laravel/socialite/commit/c6f767b56117fba88b65a5561be8d1cf98f0518a): shorten note [@taylorotwell](https://github.com/taylorotwell)
- [bb41fe8](https://github.com/laravel/socialite/commit/bb41fe891835b7702b72affc0dc1ec52c5c746a0): Added a note for contributors [@GrahamCampbell](https://github.com/GrahamCampbell)


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-05-08}...master@{2016-05-15})
- [23bb2d6](https://github.com/laravel/elixir/commit/23bb2d6f52a2fea7def2973327b9bb9a65df8c74): Send Gulp and plugins through to task [@JeffreyWay](https://github.com/JeffreyWay)
- [b42eb4d](https://github.com/laravel/elixir/commit/b42eb4db7eefaf3d4e512a5d6c2265db54e5fef8): Pre-release 6.0.0-2 [@JeffreyWay](https://github.com/JeffreyWay)
- [cb89e29](https://github.com/laravel/elixir/commit/cb89e29e8d9533b6c59919cdc5f598e7e1779f72): Remove unused dependency [@JeffreyWay](https://github.com/JeffreyWay)
- [7ea9b1b](https://github.com/laravel/elixir/commit/7ea9b1bc1e30f2de21c2a49922ea8c547ac8a397): Add initial event hook support [@JeffreyWay](https://github.com/JeffreyWay)
- [597ded9](https://github.com/laravel/elixir/commit/597ded92261331f5c90f454c683ecc32633efad0): Switch to isWatching call [@JeffreyWay](https://github.com/JeffreyWay)
- [e06e980](https://github.com/laravel/elixir/commit/e06e980d38e6c23028eb3d86b8792639cf41c15d): ES6 functions - because reasons [@JeffreyWay](https://github.com/JeffreyWay)
- [0e5cc8a](https://github.com/laravel/elixir/commit/0e5cc8ad24dc4e05a3cd5e0796340f0f82a9ca9a): Little refactor [@JeffreyWay](https://github.com/JeffreyWay)
- [2fb30b0](https://github.com/laravel/elixir/commit/2fb30b083a2368a99a54a92b41af29d26169a5bf): Move methods around [@JeffreyWay](https://github.com/JeffreyWay)
- [6c5a509](https://github.com/laravel/elixir/commit/6c5a509c5bb13203793a6f994f810350a7a38384): Add top-level isWatching method [@JeffreyWay](https://github.com/JeffreyWay)


___

## [Laracasts](https://laracasts.com)
- [Laravel Elixir Extension From Scratch](https://laracasts.com/series/painless-builds-with-laravel-elixir/episodes/15)
- [Introducing Laravel Echo](https://laracasts.com/lessons/introducing-laravel-echo)
- [ES6 Modules](https://laracasts.com/series/es6-cliffsnotes/episodes/10)
- [Bug Fixing Workflow](https://laracasts.com/series/phpunit-testing-in-laravel/episodes/14)
- [Classes](https://laracasts.com/series/es6-cliffsnotes/episodes/9)
- [Awesome Object Enhancements](https://laracasts.com/series/es6-cliffsnotes/episodes/8)
