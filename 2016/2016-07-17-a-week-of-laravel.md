# A week of Laravel #14 (10-17 July 2016)

> **Updates:** "Updates: laravel/framework [master, 5.2, 5.1], laravel/laravel [master, develop], laravel/docs [master, 5.2], laravel/homestead [master], laravel/lumen-framework [master], laravel/laravel.com [master], laravel/cashier-braintree [1.0], laravel/elixir [master], laravel/valet [master], Podcasts: The Laravel Podcast, The Laracasts Snippet, Laravel News Podcast, Laracasts, Larajobs"

> **Published:** July 17, 2016

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-07-10}...master@{2016-07-17})
- [4f49cc5](https://github.com/laravel/framework/commit/4f49cc5fc4adf21c63f3a8bc6cab6b8c41813d5c): tweak layout [@taylorotwell](https://github.com/taylorotwell) 
- [77e89c0](https://github.com/laravel/framework/commit/77e89c08e2254df8f90b67850ec8f9c44e52a736): Revert "[5.3] Fix: flatten should always ignore ke [@taylorotwell](https://github.com/taylorotwell) 
- [9d3dd66](https://github.com/laravel/framework/commit/9d3dd66cf8afbd54d7e4a7889e0a7e0d3770fd05): Make the logout action a POST request instead of G [@sileence](https://github.com/sileence) 
- [901761c](https://github.com/laravel/framework/commit/901761c5e3beee5b6a4fe7c3d3cadeb3a3dfb003): Split exception rendering into different methods ( [@rkgrep](https://github.com/rkgrep) 
- [32d2ddf](https://github.com/laravel/framework/commit/32d2ddf53deae3679b75ef484864c313166dca77): [5.3] Use connection name in determining model equ [@dwightwatson](https://github.com/dwightwatson) 
- [4aa2f9b](https://github.com/laravel/framework/commit/4aa2f9bdfd614b95dd23d8262d838036ef63c101): [5.3] Fix: flatten should always ignore keys (#143 [@JosephSilber](https://github.com/JosephSilber) 
- [a61a731](https://github.com/laravel/framework/commit/a61a7311b0a98f350255ad8f70ea5e97bb8ebd24): [5.3] Session - Use setter to set a new session id [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [664a0bb](https://github.com/laravel/framework/commit/664a0bbfa536d87835af85b40d2b817dc2661fed): [5.3] Session - Minor change (#14302)No need to re [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [8fe1ff6](https://github.com/laravel/framework/commit/8fe1ff6804330d92bae2c376eb8e18e9205c4ca3): Fix auth stub. [@taylorotwell](https://github.com/taylorotwell) 
- [59410ce](https://github.com/laravel/framework/commit/59410ce9270355359ba36b2a4391f05c1076e830): Import Schema facade by default. [@taylorotwell](https://github.com/taylorotwell) 
- [28ad69c](https://github.com/laravel/framework/commit/28ad69c6cb46ebeec092470437ee5341c049a56e): Fix typehints in SendsPasswordResetEmails trait (# [@rkgrep](https://github.com/rkgrep) 
- [be0d3cc](https://github.com/laravel/framework/commit/be0d3cc283409fe3e1ed20d25a27938c48ef3ae3): support for converting facades into mockery spies [@taylorotwell](https://github.com/taylorotwell) 
- [9e68e91](https://github.com/laravel/framework/commit/9e68e91cef5df661cd64217c9242cea998a66883): regenerate session ID on auth changes [@taylorotwell](https://github.com/taylorotwell) 
- [87a9829](https://github.com/laravel/framework/commit/87a982916a1d8b90fb5f4f1ef92944a3d1c3664d): change flash data key [@taylorotwell](https://github.com/taylorotwell) 
- [5f62e4f](https://github.com/laravel/framework/commit/5f62e4fa1e3291e4f2300404eabf7b286f5a3650): Backport HHVM type error fix (#14289) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [d467bdd](https://github.com/laravel/framework/commit/d467bddf7dd11d8aff5abd7684a76f5b58b066b5): Validator::hasRule should be public (#14292) [@aguimaraes](https://github.com/aguimaraes) 
- [9ce5d36](https://github.com/laravel/framework/commit/9ce5d36d36e0ab68a7f079a3c249cbfad63cf6c8): No need to set properties. (#14294) [@lucasmichot](https://github.com/lucasmichot) 
- [94b6ee8](https://github.com/laravel/framework/commit/94b6ee827584e0e58330db38984cb88522809d0d): stop sending outer parens on directives [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-07-10}...5.2@{2016-07-17})
- [5f62e4f](https://github.com/laravel/framework/commit/5f62e4fa1e3291e4f2300404eabf7b286f5a3650): Backport HHVM type error fix (#14289) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [9ce5d36](https://github.com/laravel/framework/commit/9ce5d36d36e0ab68a7f079a3c249cbfad63cf6c8): No need to set properties. (#14294) [@lucasmichot](https://github.com/lucasmichot) 
- [02d2143](https://github.com/laravel/framework/commit/02d2143117b39c70a4a59512bcac241e7cabac2c): CS fix [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [65589c8](https://github.com/laravel/framework/commit/65589c8ee467025eca2dffe9ca85c8ff7d5ab4fa): Allow Blade to recognize '::' in directive names ( [@superamadeus](https://github.com/superamadeus) 
- [9d8b952](https://github.com/laravel/framework/commit/9d8b9527cb504c38be4e278c695b01ae11eb0c7b): [5.2] Fix seeIsSelected for <option> tags without  [@raphaelsaunier](https://github.com/raphaelsaunier) 
- [fe507cb](https://github.com/laravel/framework/commit/fe507cb8baec7c98eb5e45dfd773d071b7f67ec8): Backport pagination fix (#14278) [@GrahamCampbell](https://github.com/GrahamCampbell) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-07-10}...5.1@{2016-07-17})
- [5f62e4f](https://github.com/laravel/framework/commit/5f62e4fa1e3291e4f2300404eabf7b286f5a3650): Backport HHVM type error fix (#14289) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [fe507cb](https://github.com/laravel/framework/commit/fe507cb8baec7c98eb5e45dfd773d071b7f67ec8): Backport pagination fix (#14278) [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-07-10}...master@{2016-07-17})


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-07-10}...develop@{2016-07-17})
- [517d8d4](https://github.com/laravel/laravel/commit/517d8d4f2c526b81795290cc013a2c16224a9930): Remove web config by default. [@taylorotwell](https://github.com/taylorotwell) 
- [76f9ea7](https://github.com/laravel/laravel/commit/76f9ea7e0429da528e3d9bc52ff25f321e271ce1): [5.3] Remove register() from BroadcastServiceProvi [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [cdbbe86](https://github.com/laravel/laravel/commit/cdbbe862ce22c4ca1d2646e60950d3dcffd93533): Jeffrey says stay with web pack. [@taylorotwell](https://github.com/taylorotwell) 
- [203d79f](https://github.com/laravel/laravel/commit/203d79fb2c6a8b1c671896e8c683beb6a235f3f8): Use rollup by default instead of web pack. [@taylorotwell](https://github.com/taylorotwell) 
- [5ccd086](https://github.com/laravel/laravel/commit/5ccd0865529c46cabd09a965dcfb5fe272c9f6f0): Remove aliases. [@taylorotwell](https://github.com/taylorotwell) 
- [dc3d82f](https://github.com/laravel/laravel/commit/dc3d82f03f57a1713cf3fe1b18a444002d6fce32): Add aliases. [@taylorotwell](https://github.com/taylorotwell) 
- [e7a03b4](https://github.com/laravel/laravel/commit/e7a03b45380e97a3a4922c13582ad10f43485b55): Stop aliasing a bunch of classes by default.This i [@taylorotwell](https://github.com/taylorotwell) 
- [7ec26ce](https://github.com/laravel/laravel/commit/7ec26ce9167fae5cabcf8cb120b8a373f73597be): Tweak location of routes files. [@taylorotwell](https://github.com/taylorotwell) 
- [2b05ce3](https://github.com/laravel/laravel/commit/2b05ce3b054593f7622c1be6c4c6aadc1c5a54ae): Just use facades in service providers. [@taylorotwell](https://github.com/taylorotwell) 
- [ebc1be0](https://github.com/laravel/laravel/commit/ebc1be018c591249605ffabceb841e3d5615fa52): update color [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-07-10}...master@{2016-07-17})
- [b5e7d71](https://github.com/laravel/docs/commit/b5e7d719e362a76444a5d15f8b91214db2e3186e): fix spacing [@taylorotwell](https://github.com/taylorotwell) 
- [dcbe49a](https://github.com/laravel/docs/commit/dcbe49abb0cd3e85d4d00a7ef83c808fe9d08228): working on csrf docs [@taylorotwell](https://github.com/taylorotwell) 
- [483da7d](https://github.com/laravel/docs/commit/483da7dfd401db93c9a04f9af6dd744c4f907faf): more work on routing documentation [@taylorotwell](https://github.com/taylorotwell) 
- [40328f1](https://github.com/laravel/docs/commit/40328f1c695228cc0a4244bd946592a631e19d77): cleaning up routing docs [@taylorotwell](https://github.com/taylorotwell) 
- [0e9685d](https://github.com/laravel/docs/commit/0e9685de9f8ab8888330eb015316b970a2700329): wording tweaks [@taylorotwell](https://github.com/taylorotwell) 
- [98813bc](https://github.com/laravel/docs/commit/98813bc3d5f51ae87ea4267a05d21dce5828ac00): tweak docs [@taylorotwell](https://github.com/taylorotwell) 
- [b58a838](https://github.com/laravel/docs/commit/b58a838cf2a48c0e52326421f4334e187939204a): various documentation updates [@taylorotwell](https://github.com/taylorotwell) 
- [ed70422](https://github.com/laravel/docs/commit/ed70422e4332ccccc242529178ad3b2e364400bb): Required field not emplyAdd not empty text to all  [@gauravmak](https://github.com/gauravmak) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-07-10}...5.2@{2016-07-17})
- [7ecd5ae](https://github.com/laravel/docs/commit/7ecd5ae643b6104d3f80ac9cfcc41a31668f8039): fix docs [@taylorotwell](https://github.com/taylorotwell) 
- [ed70422](https://github.com/laravel/docs/commit/ed70422e4332ccccc242529178ad3b2e364400bb): Required field not emplyAdd not empty text to all  [@gauravmak](https://github.com/gauravmak) 


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-07-10}...master@{2016-07-17})
- [4e36e7e](https://github.com/laravel/homestead/commit/4e36e7e5388b60698df096434ee78eb5245b06f3): append `privileged: false` for `afterScript` provi [Djuuu] 
- [29412e4](https://github.com/laravel/homestead/commit/29412e4bd4a3e928e46ce90a518bca3d80a43c21): Add Vagrant.require_version to VagrantfileForces t [@jeremyjousse](https://github.com/jeremyjousse) 


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-07-10}...master@{2016-07-17})
- [719c174](https://github.com/laravel/lumen-framework/commit/719c174770f9a7655cebbc894b3d2ac23c4c5f6b): Make it even happier [@ksassnowski](https://github.com/ksassnowski) 
- [b3a2d26](https://github.com/laravel/lumen-framework/commit/b3a2d26f7385c9893f83f3cb340036dbc24fc23a): Make StyleCI happy [@ksassnowski](https://github.com/ksassnowski) 
- [c0f91db](https://github.com/laravel/lumen-framework/commit/c0f91db4b4be74c6cad203e024a8780f0879a7d5): Add second parameter to withFacades method [@ksassnowski](https://github.com/ksassnowski) 


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-07-10}...master@{2016-07-17})
- [6ab0f3d](https://github.com/laravel/laravel.com/commit/6ab0f3d2b5288ce37e51beeca1805846b8c78915): update styles [@taylorotwell](https://github.com/taylorotwell) 
- [d776150](https://github.com/laravel/laravel.com/commit/d77615023378136e432457bc90b5f2e1077ab156): disable 5.3 docs [@taylorotwell](https://github.com/taylorotwell) 
- [3ef4253](https://github.com/laravel/laravel.com/commit/3ef4253e6a6753719e8e4522df227628bf3559ff): wip [@taylorotwell](https://github.com/taylorotwell) 
- [d43a585](https://github.com/laravel/laravel.com/commit/d43a585a6b01e02ed0ecc52617cdd4b855815597): wip [@taylorotwell](https://github.com/taylorotwell) 
- [76e10d0](https://github.com/laravel/laravel.com/commit/76e10d012c2a9cdabf72dbca30cd654484e8ab87): fix overly assumption javascript method. [@jackmcdade](https://github.com/jackmcdade) 
- [c1f9669](https://github.com/laravel/laravel.com/commit/c1f96698596439a9c6deb85070537eea811887ea): tip color [@taylorotwell](https://github.com/taylorotwell) 
- [85900a0](https://github.com/laravel/laravel.com/commit/85900a0460a16e180bc3aa93e836fce11c5a6a0b): Add those groovy blockquotes baby. [@jackmcdade](https://github.com/jackmcdade) 
- [08067cc](https://github.com/laravel/laravel.com/commit/08067cca7afa9a38e7be5be94e22ea943179d5aa): add version [@taylorotwell](https://github.com/taylorotwell) 
- [309e36c](https://github.com/laravel/laravel.com/commit/309e36c30f4600314b19f39608a0ed2fcb2e23a9): update doc syncing [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/cashier-braintree](https://github.com/laravel/cashier-braintree)

### [1.0](https://github.com/laravel/cashier-braintree/compare/1.0@{2016-07-10}...1.0@{2016-07-17})
- [186d11c](https://github.com/laravel/cashier-braintree/commit/186d11c4a4ed94d3508f007978d66a9d04c8168d): Make API more safe by defining keysAdd array keys  [@agentzzk](https://github.com/agentzzk) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-07-10}...master@{2016-07-17})
- [48152e6](https://github.com/laravel/elixir/commit/48152e6d2a49059d3759f0b832a56a3ef61a1141): mix.combine() should only concat the files [@JeffreyWay](https://github.com/JeffreyWay) 
- [8badfcb](https://github.com/laravel/elixir/commit/8badfcb104e2145f51d443418b342a19fb6cad3a): Add Stylus to install instructions [@JeffreyWay](https://github.com/JeffreyWay) 
- [c11322f](https://github.com/laravel/elixir/commit/c11322f5b7cb8f57fab1c79376b98cbaad4c1206): Automatically set NODE_ENV if gulp --production -  [@JeffreyWay](https://github.com/JeffreyWay) 


___

## [laravel/valet](https://github.com/laravel/valet)

### [master](https://github.com/laravel/valet/compare/master@{2016-07-10}...master@{2016-07-17})
- [60dc951](https://github.com/laravel/valet/commit/60dc951513f58dcf7ab6ebb200a08c4b9b5545ec): Redirect wp-admin to wp-admin/ (#96)When attemptin [@tlaverdure](https://github.com/tlaverdure) 


___

## Podcasts

### [The Laravel Podcast](http://laravel.com)
- [Episode 47: Musical Routes](http://www.laravelpodcast.com/episodes/42491-episode-47-musical-routes)

### [The Laracasts Snippet](http://laracasts.audio)
- [Victims of Our Curiosity](http://laracasts.simplecast.fm/33)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 21: Laracon, Laravel 5.3 Advanced Where, October CMS, Canvas](http://podcast.laravel-news.com/21)


___

## [Laracasts](https://laracasts.com)
- [How Do I Use Iterators](https://laracasts.com/series/how-do-i/episodes/3)
- [MySQL 101](https://laracasts.com/series/php-for-beginners/episodes/11)
- [Pagination and Channel Filtering](https://laracasts.com/series/hands-on-community-contributions/episodes/9)
- [Form Objects and Touching Timestamps](https://laracasts.com/series/hands-on-community-contributions/episodes/8)
- [Flash Messaging and Modals](https://laracasts.com/series/hands-on-community-contributions/episodes/7)


___

## [Larajobs](https://larajobs.com)
- [Senior / Lead Developer (m/f) in Berlin](https://larajobs.com/job/550/senior-lead-developer-mf-in-berlin)
- [Mid - Senior Front End Developer](https://larajobs.com/job/545/mid-senior-front-end-developer)
- [Mid - Senior Larvel Expert](https://larajobs.com/job/544/mid-senior-larvel-expert)
- [Back End Developer](https://larajobs.com/job/543/back-end-developer)
- [Full Stack Developer](https://larajobs.com/job/542/full-stack-developer)
