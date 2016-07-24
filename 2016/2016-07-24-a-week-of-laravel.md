# A week of Laravel #15 (17-24 July 2016)

> **Updates:** "Updates: laravel/framework [master, 5.2, 5.1], laravel/laravel [develop], laravel/installer [master], laravel/docs [master, 5.2], laravel/socialite [2.0], laravel/elixir [master], laravel/echo [master], Podcasts: The Laracasts Snippet, Laracasts, Larajobs"

> **Published:** July 24, 2016

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-07-17}...master@{2016-07-24})
- [9046e48](https://github.com/laravel/framework/commit/9046e484ead543f05b733741f486e817c4e9e222): remove php 7 type hint [@taylorotwell](https://github.com/taylorotwell) 
- [810e96e](https://github.com/laravel/framework/commit/810e96ef1a2ad80cecd7d03f770b72acac3587f2): fix typo [@taylorotwell](https://github.com/taylorotwell) 
- [49b4741](https://github.com/laravel/framework/commit/49b4741943260e48127ba3795e4624aefa35f9a5): clean up sync error handling [@taylorotwell](https://github.com/taylorotwell) 
- [9ee856e](https://github.com/laravel/framework/commit/9ee856e865afdbe9debc4a653b0baeb6fa8d00b3): cleanup throwable handling [@taylorotwell](https://github.com/taylorotwell) 
- [8021540](https://github.com/laravel/framework/commit/8021540aaf020f1a2e2fafccba89a4783a9fc262): fix tests for php 7 [@taylorotwell](https://github.com/taylorotwell) 
- [a5b537b](https://github.com/laravel/framework/commit/a5b537b3624e228cecd255341edc4314ebceb416): remove throwable type hints [@taylorotwell](https://github.com/taylorotwell) 
- [300da12](https://github.com/laravel/framework/commit/300da122815c857eae039c982be90c0f87c08fba): rename variable [@taylorotwell](https://github.com/taylorotwell) 
- [2a48f90](https://github.com/laravel/framework/commit/2a48f901100fcd77af23fe96e6583a1e3e4c7846): This help screen is almost never helpful. Mainly a [@taylorotwell](https://github.com/taylorotwell) 
- [d593151](https://github.com/laravel/framework/commit/d593151a3304a0bfb65a97e5f1f25a8da0014af2): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [f1e43d1](https://github.com/laravel/framework/commit/f1e43d1e55453126bc21747762a7e528a1e1a23b): Remove unneeded code. [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-07-17}...5.2@{2016-07-24})
- [f6a4db4](https://github.com/laravel/framework/commit/f6a4db472ca9013e56d8a7065c9fd64383a3d4d4): Fix PDO connection on HHVM with the default "class [@vlakoff](https://github.com/vlakoff) 
- [ceccdf7](https://github.com/laravel/framework/commit/ceccdf75ddbcb4c0e9bcfd01f5c4b3e5587ad411): [5.2] Added release notes for v5.2.40 and v5.2.41  [@tillkruss](https://github.com/tillkruss) 
- [bf064f5](https://github.com/laravel/framework/commit/bf064f5bd38b1993ef5096cd1b7fe9d9d149dbf1): rollback index change [@taylorotwell](https://github.com/taylorotwell) 
- [9d853b9](https://github.com/laravel/framework/commit/9d853b9b2db24849b68ce219d80fc68165807810): Allow the detach method to accept a collection (#1 [@arjasco](https://github.com/arjasco) 
- [be43de2](https://github.com/laravel/framework/commit/be43de2b67889941feee76070f0181d58e1ddd98): [5.2] Optimize Filesystem moveDirectory (#14362)*  [@BePsvPT](https://github.com/BePsvPT) 
- [1657abd](https://github.com/laravel/framework/commit/1657abd3a7b0bf0d61782c1eb2801517d619868e): Fixed issue with UrlGenerator and /index.php urls. [@neochief](https://github.com/neochief) 
- [615b47a](https://github.com/laravel/framework/commit/615b47adfd35883e19b6ca9cbbaecd71ac710e41): fix comments [@taylorotwell](https://github.com/taylorotwell) 
- [2e22e71](https://github.com/laravel/framework/commit/2e22e71f4e1bd1103bcb6a6d3ebf42f3990fca4f): [5.2] Avoid introducing breaking backward compatib [@crynobone](https://github.com/crynobone) 
- [1047748](https://github.com/laravel/framework/commit/1047748ccb4407fc7c297981a3494e280e51605d): Doc block fixed (#14411) [@dan-har](https://github.com/dan-har) 
- [bca07b0](https://github.com/laravel/framework/commit/bca07b0b5234fc261f4ac7b65f84f6bff01cc74b): fix #14397 [@jhdxr](https://github.com/jhdxr) 
- [29ba2e3](https://github.com/laravel/framework/commit/29ba2e310cfeb42ab6545bcd81ff4c2ec1f6b5c2): increment version [@taylorotwell](https://github.com/taylorotwell) 
- [7dfb945](https://github.com/laravel/framework/commit/7dfb945c2813bc7f965792f1f83ea9decb856ca1): moved up collectGarbage call to run it even when t [@JeroenVanOort](https://github.com/JeroenVanOort) 
- [6c553a7](https://github.com/laravel/framework/commit/6c553a7c1226d3927eed3775d77cc0071cccf551): Fixes input order issue (#14381) [@amonger](https://github.com/amonger) 
- [4835c0a](https://github.com/laravel/framework/commit/4835c0a7b2954220e399de5984b00dcca146e2d7): fix #14387 pagination issue in the newest release  [@themsaid](https://github.com/themsaid) 
- [6195211](https://github.com/laravel/framework/commit/6195211140ed0881e89d79a296f893abc56987be): increment version [@taylorotwell](https://github.com/taylorotwell) 
- [153af5c](https://github.com/laravel/framework/commit/153af5cf27aaae42b21776633258b39677ab3865): fix #14367 by removing double URL encoding (#14370 [@themsaid](https://github.com/themsaid) 
- [d059f90](https://github.com/laravel/framework/commit/d059f904aaacf9cf7486c7f8d8443aa07f084709): Remove un-needed method overwrites (#14372) [@themsaid](https://github.com/themsaid) 
- [83d3ce2](https://github.com/laravel/framework/commit/83d3ce2eca7f69edb88b228807d52edd2d4071a2): [5.2] Fix return type of some validation methods ( [@themsaid](https://github.com/themsaid) 
- [4314e53](https://github.com/laravel/framework/commit/4314e53b77b377108e3454fe4bccd8b6bfb9d2c8): [5.1] Fix morphTo eager loading (#14191)* Fix morp [@acasar](https://github.com/acasar) 
- [2759219](https://github.com/laravel/framework/commit/2759219bfe9a5dc3861f5f311668258543e9711e): working on code [@taylorotwell](https://github.com/taylorotwell) 
- [a8ca2b7](https://github.com/laravel/framework/commit/a8ca2b7786a6b094a1e26a5ec3044d5737cba40d): code cleaning [@taylorotwell](https://github.com/taylorotwell) 
- [85249be](https://github.com/laravel/framework/commit/85249beed1e4512d71f7ae52474b9a59a80381d2): fix console bug, fix redirect response [@taylorotwell](https://github.com/taylorotwell) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-07-17}...5.1@{2016-07-24})
- [bf064f5](https://github.com/laravel/framework/commit/bf064f5bd38b1993ef5096cd1b7fe9d9d149dbf1): rollback index change [@taylorotwell](https://github.com/taylorotwell) 
- [1657abd](https://github.com/laravel/framework/commit/1657abd3a7b0bf0d61782c1eb2801517d619868e): Fixed issue with UrlGenerator and /index.php urls. [@neochief](https://github.com/neochief) 
- [4314e53](https://github.com/laravel/framework/commit/4314e53b77b377108e3454fe4bccd8b6bfb9d2c8): [5.1] Fix morphTo eager loading (#14191)* Fix morp [@acasar](https://github.com/acasar) 
- [d9ed009](https://github.com/laravel/framework/commit/d9ed009ee0e882933760514aaab9c8406dce11ad): change message [@taylorotwell](https://github.com/taylorotwell) 
- [90f2edd](https://github.com/laravel/framework/commit/90f2eddf24b77351f32253f2d005f7389de95e3e): Do not allow empty cache paths (#14291) [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [develop](https://github.com/laravel/laravel/compare/develop@{2016-07-17}...develop@{2016-07-24})
- [40ae681](https://github.com/laravel/laravel/commit/40ae68102aecd62b550d69875f78f11b83bef80d): tweak variables [@taylorotwell](https://github.com/taylorotwell) 
- [cfb5a68](https://github.com/laravel/laravel/commit/cfb5a68cd427be5d82677eb86b05cf0cbc531394): work on default styling [@taylorotwell](https://github.com/taylorotwell) 
- [1cbbf41](https://github.com/laravel/laravel/commit/1cbbf41c0c168187e1086cfc8ea00e81324bd0f2): Remove some unneeded variables. [@taylorotwell](https://github.com/taylorotwell) 
- [6f2541f](https://github.com/laravel/laravel/commit/6f2541f14fc697519c239e34ff3e97351156257b): new welcome page [@taylorotwell](https://github.com/taylorotwell) 
- [e5cb0a3](https://github.com/laravel/laravel/commit/e5cb0a350a3b82d9b611d909085fb031c0e0c206): working on sass [@taylorotwell](https://github.com/taylorotwell) 
- [467e00d](https://github.com/laravel/laravel/commit/467e00d9d48940cd6e0e8b96574fd5c4673002fc): working on sass [@taylorotwell](https://github.com/taylorotwell) 
- [abe35a0](https://github.com/laravel/laravel/commit/abe35a095c0525afc1b85dc4ccbf4b8b86ba7d2f): working on sass [@taylorotwell](https://github.com/taylorotwell) 
- [f41a400](https://github.com/laravel/laravel/commit/f41a400cfdb4cf7f116b2db1f3da69f6cb63d337): Tweak a few variables. [@taylorotwell](https://github.com/taylorotwell) 
- [24766d4](https://github.com/laravel/laravel/commit/24766d479d6fb978a7b00b838225ead63f983e9a): redirect to home if authed [@taylorotwell](https://github.com/taylorotwell) 
- [592b7a2](https://github.com/laravel/laravel/commit/592b7a2bd9452def0458bf2b41bd5f6cfca27f55): add compiled assets [@taylorotwell](https://github.com/taylorotwell) 
- [3f5da4f](https://github.com/laravel/laravel/commit/3f5da4fb76b69e7738283289445237301bf0ef75): Include the font in the Sass. [@taylorotwell](https://github.com/taylorotwell) 
- [e9fe020](https://github.com/laravel/laravel/commit/e9fe020c0c394775e65a236ae494d9fd88a32f47): sample js component [@taylorotwell](https://github.com/taylorotwell) 
- [eb289b4](https://github.com/laravel/laravel/commit/eb289b417071f3400a1ea6fc0024f8489a3c2724): tweak js bootstrapping [@taylorotwell](https://github.com/taylorotwell) 
- [0699994](https://github.com/laravel/laravel/commit/0699994de0c1894dd3788994482b3ac8485c5261): add files [@taylorotwell](https://github.com/taylorotwell) 
- [3f19733](https://github.com/laravel/laravel/commit/3f197331b6de88f3b2ce1a3470c328b1b5f42f1c): bootstrap vue in app.js [@taylorotwell](https://github.com/taylorotwell) 
- [fd569a3](https://github.com/laravel/laravel/commit/fd569a3785b116a9ca37b75c779ba24bec189b67): Name this option "retry_after" for clarity. [@taylorotwell](https://github.com/taylorotwell) 
- [3cc0388](https://github.com/laravel/laravel/commit/3cc0388ed70ee921d5d3f92a8caf870abba55197): Use expire for consistency. [@taylorotwell](https://github.com/taylorotwell) 
- [ea52a96](https://github.com/laravel/laravel/commit/ea52a963869f6f798ba7d3df995c4f0630775134): Remove mandrill as a default configuration since i [@taylorotwell](https://github.com/taylorotwell) 
- [1cc411d](https://github.com/laravel/laravel/commit/1cc411d17fe8b083ad2f15a3598dbe74bf15dd1d): remove directories. let them be jit created. [@taylorotwell](https://github.com/taylorotwell) 
- [93cdacf](https://github.com/laravel/laravel/commit/93cdacf32c4a4fd9b0bc23c5ab9ba056b3882291): remove word [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/installer](https://github.com/laravel/installer)

### [master](https://github.com/laravel/installer/compare/master@{2016-07-17}...master@{2016-07-24})
- [40a13af](https://github.com/laravel/installer/commit/40a13af9db06a167c919d8e043d53185dc47dafd): Respect the styles given. [@TJSoler](https://github.com/TJSoler) 
- [31a5429](https://github.com/laravel/installer/commit/31a542943f8c10159e474c1771c26881f65fb308): Respect the styles given. [@TJSoler](https://github.com/TJSoler) 
- [86f46b0](https://github.com/laravel/installer/commit/86f46b0cd6f2106f024e3d4ada9b8dee26d8c4fa): Respect --no-ansi optionMakes laravel --no-ansi be [@TJSoler](https://github.com/TJSoler) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-07-17}...master@{2016-07-24})
- [bb98f1c](https://github.com/laravel/docs/commit/bb98f1ca504ba1e36833c2f904b2cc2e0e84e08f): working on queues [@taylorotwell](https://github.com/taylorotwell) 
- [9a767a6](https://github.com/laravel/docs/commit/9a767a6ffa252adc28f9e27126c1d3fee4a928b6): fixing a few things [@taylorotwell](https://github.com/taylorotwell) 
- [4667363](https://github.com/laravel/docs/commit/466736396e3c451546e582b4528ec4c622f71a39): fix typo [@taylorotwell](https://github.com/taylorotwell) 
- [603d070](https://github.com/laravel/docs/commit/603d07016b888cc0c2283940f42ad5b6a7b0b0d3): mail doc editing [@taylorotwell](https://github.com/taylorotwell) 
- [70870f2](https://github.com/laravel/docs/commit/70870f2c02b19491803cfdc64c3e1e9d43f80fa8): first pass at mail docs [@taylorotwell](https://github.com/taylorotwell) 
- [6002222](https://github.com/laravel/docs/commit/600222247c8c62fa4ff76b72d1d0c4cf99a7e520): document directories [@taylorotwell](https://github.com/taylorotwell) 
- [f720681](https://github.com/laravel/docs/commit/f720681d572a82ea18d18f5bf0aff065fe6825c1): a few cleanups [@taylorotwell](https://github.com/taylorotwell) 
- [2e46bd6](https://github.com/laravel/docs/commit/2e46bd69968a7b165551d2b53bb0d19a8541efdb): working on docs [@taylorotwell](https://github.com/taylorotwell) 
- [561a2b0](https://github.com/laravel/docs/commit/561a2b0cef140c7cf6eff5267dea8d96e81233bc): working on helper docs [@taylorotwell](https://github.com/taylorotwell) 
- [e9056c3](https://github.com/laravel/docs/commit/e9056c3b7ba7527c0d831bca2a629d636c7975aa): document storing uploads [@taylorotwell](https://github.com/taylorotwell) 
- [7e8d468](https://github.com/laravel/docs/commit/7e8d468a129f72a66565ceed8b3e3f193efb3eea): file system docs [@taylorotwell](https://github.com/taylorotwell) 
- [4161f2b](https://github.com/laravel/docs/commit/4161f2b47c88e9ec948661910752afeb2f587202): added note to queue docs [@taylorotwell](https://github.com/taylorotwell) 
- [0c9233a](https://github.com/laravel/docs/commit/0c9233a558215a91bdfc2504babed6874175069f): change wording [@taylorotwell](https://github.com/taylorotwell) 
- [bc71300](https://github.com/laravel/docs/commit/bc71300c6d1920050987def575087b2c861a2298): event docs. broadcasting will have its own page [@taylorotwell](https://github.com/taylorotwell) 
- [9ef9ea3](https://github.com/laravel/docs/commit/9ef9ea3a1fc0cb0e4926615c79874ee4d94bbbb3): error docs [@taylorotwell](https://github.com/taylorotwell) 
- [db924ff](https://github.com/laravel/docs/commit/db924ffa2c9199b024b170868e877c4a16f7f4b3): collection docs [@taylorotwell](https://github.com/taylorotwell) 
- [e7d8b27](https://github.com/laravel/docs/commit/e7d8b278bb2aada28fa785d890eb0777d8f18d18): cache docs [@taylorotwell](https://github.com/taylorotwell) 
- [2ad7808](https://github.com/laravel/docs/commit/2ad7808cc7ee60024c8b056435a4b798ad22056f): working on cashier docs [@taylorotwell](https://github.com/taylorotwell) 
- [41f5e6a](https://github.com/laravel/docs/commit/41f5e6a7ccfa016e291f819df0d45cd0a0d4de9e): remove option [@taylorotwell](https://github.com/taylorotwell) 
- [307e9f4](https://github.com/laravel/docs/commit/307e9f41e6f4a27ddfe8c58b7ec72267cf4ccd62): working on artisan docs [@taylorotwell](https://github.com/taylorotwell) 
- [b19da75](https://github.com/laravel/docs/commit/b19da7506105fcc310feb0d8f9bc862d7f6dedd6): continuing work on authorization docs [@taylorotwell](https://github.com/taylorotwell) 
- [e2cbae5](https://github.com/laravel/docs/commit/e2cbae5cd44e01617fe3e74c22084d25c6438ccd): first pass on auth docs [@taylorotwell](https://github.com/taylorotwell) 
- [ffe395b](https://github.com/laravel/docs/commit/ffe395b1a88ed417e36c5f3a6b5ccec6910722d2): fix documentation [@taylorotwell](https://github.com/taylorotwell) 
- [ec722fe](https://github.com/laravel/docs/commit/ec722fe29123ee2eb2ea81cd70da3dd12c35be68): working on authorization docs [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-07-17}...5.2@{2016-07-24})
- [3c96f11](https://github.com/laravel/docs/commit/3c96f11696d6782090c4553b054cc41d0157b33e): Fix return of Defining Abilities example [@felicianopj](https://github.com/felicianopj) 


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-07-17}...2.0@{2016-07-24})
- [307c50c](https://github.com/laravel/socialite/commit/307c50c6cf12ef62797040f952b55a5873c3986f): Missing return value. [@mayoz](https://github.com/mayoz) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-07-17}...master@{2016-07-24})
- [d1e177c](https://github.com/laravel/elixir/commit/d1e177c5ed7069703f7eb06629823abc422ed439): Remove test [@JeffreyWay](https://github.com/JeffreyWay) 
- [6c83be7](https://github.com/laravel/elixir/commit/6c83be7cbb2ead69794fd7fca56e01b24eca2fe7): Fix issue with referencing relative parent dirs -  [@JeffreyWay](https://github.com/JeffreyWay) 
- [4717cd6](https://github.com/laravel/elixir/commit/4717cd624d6be91ff8c7856b493c199da79965aa): Fix combine test [@JeffreyWay](https://github.com/JeffreyWay) 
- [088f0a9](https://github.com/laravel/elixir/commit/088f0a921a24fed2d5a7c1cca848f4e98d0d60d7): Add support for minimal logging - closes #584Run â [@JeffreyWay](https://github.com/JeffreyWay) 


___

## [laravel/echo](https://github.com/laravel/echo)

### [master](https://github.com/laravel/echo/compare/master@{2016-07-17}...master@{2016-07-24})
- [8cf46bc](https://github.com/laravel/echo/commit/8cf46bc6ef6a18a905cb0bd94dd65e2ad2ead8bd): Rename variableSame name as in config defaults [@juukie](https://github.com/juukie) 


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [Just a Detail](http://laracasts.simplecast.fm/34)


___

## [Laracasts](https://laracasts.com)
- [Intro to PDO](https://laracasts.com/series/php-for-beginners/episodes/13)
- [Classes 101](https://laracasts.com/series/php-for-beginners/episodes/12)
- [How Do I Unit Test Eloquent Models?](https://laracasts.com/series/how-do-i/episodes/5)
- [Voting: Part 1](https://laracasts.com/series/hands-on-community-contributions/episodes/10)
- [How Should I Name My Events and Listeners?](https://laracasts.com/series/how-do-i/episodes/4)
- [ES2015 Generators](https://laracasts.com/series/es6-cliffsnotes/episodes/16)
- [Array#find and Array#includes](https://laracasts.com/series/es6-cliffsnotes/episodes/15)


___

## [Larajobs](https://larajobs.com)
- [Developer ](https://larajobs.com/job/553/developer)
- [Support developer](https://larajobs.com/job/552/support-developer)
- [Web Developer - LAMP](https://larajobs.com/job/551/web-developer-lamp)
