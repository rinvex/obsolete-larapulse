---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (05-12 June 2016)
post::title: A week of Laravel (05-12 June 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [develop], laravel/docs [master], laravel/docs [5.2], laravel/docs [5.1], laravel/lumen-framework [master], laravel/lumen-framework [5.2], laravel/lumen-framework [5.1], laravel/lumen-docs [master], laravel/lumen-docs [5.2], laravel/quickstart-intermediate [master], laravel/cashier-braintree [1.0], laravel/settler [master], laravel/socialite [2.0], laravel/elixir [master], laravel/envoy [master], Podcasts: The Laracasts Snippet, Laracasts"
post::date: June 12, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-06-05}...master@{2016-06-12})
- [43808e3](https://github.com/laravel/framework/commit/43808e3b54973e9c18de01b7390f7d137fa38762): Make Model::fresh convert multiple args into array [@themsaid](https://github.com/themsaid) 
- [4c4313c](https://github.com/laravel/framework/commit/4c4313c59fcf9fe1da5cdd9848e9fa1629f1acf1): Fix possible key overlap in cache of Str::snake (# [@vlakoff](https://github.com/vlakoff) 
- [62348b3](https://github.com/laravel/framework/commit/62348b3a46f48b8f3f7b5cd255e8ef58c0cc2fe8): formatting [@taylorotwell](https://github.com/taylorotwell) 
- [daa4983](https://github.com/laravel/framework/commit/daa49838d9557c526e28abd75f1825f8c05dd998): rewrite redis job to one json_decode() [@evsign](https://github.com/evsign) 
- [7817197](https://github.com/laravel/framework/commit/781719746271098ed5049023921c084392494102): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [bb59455](https://github.com/laravel/framework/commit/bb594556eef784b642f6ed460a09739c1b513b90): [5.1] Yet another attempt to fix Swift Mailer rela [@schanzel](https://github.com/schanzel) 
- [526f9ff](https://github.com/laravel/framework/commit/526f9ff22f0fe3d7f10a08ad2da96a70b31e3fc3): add loop variable to forelse loops (#13945) [@themsaid](https://github.com/themsaid) 
- [312b587](https://github.com/laravel/framework/commit/312b587f85ad2f7a94ed9c400925b67c25ab55d3): remove dup [@taylorotwell](https://github.com/taylorotwell) 
- [6bbc6d1](https://github.com/laravel/framework/commit/6bbc6d1227a113135c4ecde7cb57966dd0ad1675): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [bf19903](https://github.com/laravel/framework/commit/bf199036b0e222a27e2133d841aee0d4238f804d): version [@taylorotwell](https://github.com/taylorotwell) 
- [00f4cab](https://github.com/laravel/framework/commit/00f4cab7b65a85314204d800a47c669b1689a26c): fixing session expiration [@taylorotwell](https://github.com/taylorotwell) 
- [6784875](https://github.com/laravel/framework/commit/67848753f16a639da6d0871019ae792111941933): version [@taylorotwell](https://github.com/taylorotwell) 
- [0831312](https://github.com/laravel/framework/commit/0831312aec47d904a65039e07574f41ab7492418): Fix session expiration on several drivers. [@taylorotwell](https://github.com/taylorotwell) 
- [0797d83](https://github.com/laravel/framework/commit/0797d83280744e63bda4f5c89ace7d80324072f9): Proper database session expiration handling. [@taylorotwell](https://github.com/taylorotwell) 
- [61ad10c](https://github.com/laravel/framework/commit/61ad10ce8f301c9ce17effcd537475018c3bf36d): Properly handle lifetime expiration on file sessio [@taylorotwell](https://github.com/taylorotwell) 
- [453f504](https://github.com/laravel/framework/commit/453f504c449af9aa77b8b5a13fb065a7d7f06952): fix expiration on cookie sessions [@taylorotwell](https://github.com/taylorotwell) 
- [3dbfc87](https://github.com/laravel/framework/commit/3dbfc8710e895d921ead647561f907348573e9ab): fix remaining to make more sense [@taylorotwell](https://github.com/taylorotwell) 
- [ce607cb](https://github.com/laravel/framework/commit/ce607cb2ef549e9b8513aee98c792790792f3ba1): formatting [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-06-05}...5.2@{2016-06-12})
- [7a4a022](https://github.com/laravel/framework/commit/7a4a0226f8a00d35af0765a3fb2be46841d843fa): Added release notes for v5.2.37 (#13953) [@tillkruss](https://github.com/tillkruss) 
- [43808e3](https://github.com/laravel/framework/commit/43808e3b54973e9c18de01b7390f7d137fa38762): Make Model::fresh convert multiple args into array [@themsaid](https://github.com/themsaid) 
- [4c4313c](https://github.com/laravel/framework/commit/4c4313c59fcf9fe1da5cdd9848e9fa1629f1acf1): Fix possible key overlap in cache of Str::snake (# [@vlakoff](https://github.com/vlakoff) 
- [7817197](https://github.com/laravel/framework/commit/781719746271098ed5049023921c084392494102): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [bb59455](https://github.com/laravel/framework/commit/bb594556eef784b642f6ed460a09739c1b513b90): [5.1] Yet another attempt to fix Swift Mailer rela [@schanzel](https://github.com/schanzel) 
- [bf19903](https://github.com/laravel/framework/commit/bf199036b0e222a27e2133d841aee0d4238f804d): version [@taylorotwell](https://github.com/taylorotwell) 
- [00f4cab](https://github.com/laravel/framework/commit/00f4cab7b65a85314204d800a47c669b1689a26c): fixing session expiration [@taylorotwell](https://github.com/taylorotwell) 
- [6784875](https://github.com/laravel/framework/commit/67848753f16a639da6d0871019ae792111941933): version [@taylorotwell](https://github.com/taylorotwell) 
- [0831312](https://github.com/laravel/framework/commit/0831312aec47d904a65039e07574f41ab7492418): Fix session expiration on several drivers. [@taylorotwell](https://github.com/taylorotwell) 
- [ce607cb](https://github.com/laravel/framework/commit/ce607cb2ef549e9b8513aee98c792790792f3ba1): formatting [@taylorotwell](https://github.com/taylorotwell) 
- [437d781](https://github.com/laravel/framework/commit/437d781b3549d63f244706927606311b6ec501ce): working on formatting [@taylorotwell](https://github.com/taylorotwell) 
- [5757f48](https://github.com/laravel/framework/commit/5757f48f27a55dddd27c814e40f50de3bab17597): Fix phpdocs [@kevinsimard](https://github.com/kevinsimard) 
- [3cc7023](https://github.com/laravel/framework/commit/3cc7023989bc3a548b08a67583c4096b61c2b2b3): Fix phpdocs [@kevinsimard](https://github.com/kevinsimard) 
- [10fad9a](https://github.com/laravel/framework/commit/10fad9a000b2b25d0274abacd6d7dae52cc4ddfe): Add failed job ID when dispatching a JobFailed eve [@kevinsimard](https://github.com/kevinsimard) 
- [01b6596](https://github.com/laravel/framework/commit/01b6596a748ec61422f28e1e2a6baa8db6ea620c): [5.2] Command - Added hasArgument() and hasOption( [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [60eb682](https://github.com/laravel/framework/commit/60eb682f535a907fe413bb597b7565a525996508): Added release notes for v5.2.36 (#13898) [@tillkruss](https://github.com/tillkruss) 
- [30d113e](https://github.com/laravel/framework/commit/30d113ecda2f8181a22121f24e7ad59a7026f2e8): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [ecf782a](https://github.com/laravel/framework/commit/ecf782a2eef21380ae40b1462f0a792ccfaac060): version [@taylorotwell](https://github.com/taylorotwell) 
- [236d7c0](https://github.com/laravel/framework/commit/236d7c0c5b67a2348ac7831391031d93000de3ab): version [@taylorotwell](https://github.com/taylorotwell) 
- [b5503d5](https://github.com/laravel/framework/commit/b5503d5695c7540cd7168bbb7bac61f7b321ee11): Auth::id() don't get $id from Recaller (#13769) [@apollopy](https://github.com/apollopy) 
- [2805df8](https://github.com/laravel/framework/commit/2805df870a18464d203472247dc92211f4bbb2a9): formatting [@taylorotwell](https://github.com/taylorotwell) 
- [0973bfa](https://github.com/laravel/framework/commit/0973bfabe26e16ae194310f379ba3e87887835a6): Revert "Revert "Fix postgres Schema::hastable (#13 [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [b9b1d2b](https://github.com/laravel/framework/commit/b9b1d2bec4bfea3cf033aa67fe228485bdec6f3f): formatting [@taylorotwell](https://github.com/taylorotwell) 
- [9e7df97](https://github.com/laravel/framework/commit/9e7df974abb31e3c2d1a0ef2035d12bcf1f68424): [5.2] Rename method (#13894)Renamed a method as di [@acasar](https://github.com/acasar) 
- [dea4f37](https://github.com/laravel/framework/commit/dea4f375ebc6f15929f2a11fab7e94731b9856f9): Revert "Revert "Fix postgres Schema::hastable (#13 [@GrahamCampbell](https://github.com/GrahamCampbell) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-06-05}...5.1@{2016-06-12})
- [4c4313c](https://github.com/laravel/framework/commit/4c4313c59fcf9fe1da5cdd9848e9fa1629f1acf1): Fix possible key overlap in cache of Str::snake (# [@vlakoff](https://github.com/vlakoff) 
- [bb59455](https://github.com/laravel/framework/commit/bb594556eef784b642f6ed460a09739c1b513b90): [5.1] Yet another attempt to fix Swift Mailer rela [@schanzel](https://github.com/schanzel) 
- [6784875](https://github.com/laravel/framework/commit/67848753f16a639da6d0871019ae792111941933): version [@taylorotwell](https://github.com/taylorotwell) 
- [0831312](https://github.com/laravel/framework/commit/0831312aec47d904a65039e07574f41ab7492418): Fix session expiration on several drivers. [@taylorotwell](https://github.com/taylorotwell) 
- [ecf782a](https://github.com/laravel/framework/commit/ecf782a2eef21380ae40b1462f0a792ccfaac060): version [@taylorotwell](https://github.com/taylorotwell) 
- [b5503d5](https://github.com/laravel/framework/commit/b5503d5695c7540cd7168bbb7bac61f7b321ee11): Auth::id() don't get $id from Recaller (#13769) [@apollopy](https://github.com/apollopy) 
- [0973bfa](https://github.com/laravel/framework/commit/0973bfabe26e16ae194310f379ba3e87887835a6): Revert "Revert "Fix postgres Schema::hastable (#13 [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [023d0a0](https://github.com/laravel/framework/commit/023d0a0f20835d48395c35338908e6338a8f9338): Revert "Fix postgres Schema::hastable (#13008)"Thi [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [develop](https://github.com/laravel/laravel/compare/develop@{2016-06-05}...develop@{2016-06-12})
- [e5dfb05](https://github.com/laravel/laravel/commit/e5dfb052473c93f23dfc951f42afcfabbf4a6d58): message updates [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-06-05}...master@{2016-06-12})
- [ce90581](https://github.com/laravel/docs/commit/ce90581100b9e06292bda49ffd10776cb9aabac1): wording [@taylorotwell](https://github.com/taylorotwell) 
- [43930f4](https://github.com/laravel/docs/commit/43930f4d07fc76ca8559ea8e944cefbc4a6b8c88): DOCS for rolling back migrations with step option. [@srmklive](https://github.com/srmklive) 
- [e9377e2](https://github.com/laravel/docs/commit/e9377e269525e2a78e1334662607548759e9c92a): update wording [@taylorotwell](https://github.com/taylorotwell) 
- [019e109](https://github.com/laravel/docs/commit/019e109ee485bb80ce4d1289c6bb29208788c2ae): Add Cashier-Braintree link to Laravel projects [@samuelsan](https://github.com/samuelsan) 
- [e9344f6](https://github.com/laravel/docs/commit/e9344f6d5c58baca198e0067f2096e454143d8c5): Removed unessesary `!!` [@tillkruss](https://github.com/tillkruss) 
- [8fc2056](https://github.com/laravel/docs/commit/8fc2056e998ae94f9c0f6cee65b703213bb0e73b): remove notice [@taylorotwell](https://github.com/taylorotwell) 
- [0a2c2a5](https://github.com/laravel/docs/commit/0a2c2a5d834828ed9de825f9cf05f9a2a5f2bbc1): clarify note [@taylorotwell](https://github.com/taylorotwell) 
- [8d7f53b](https://github.com/laravel/docs/commit/8d7f53b4caaa81d6b037f67e51a17dcc8b4e4023): wording [@taylorotwell](https://github.com/taylorotwell) 
- [3919ba8](https://github.com/laravel/docs/commit/3919ba8191918066cc3bb97ea106c6653e370db4): Add documentation for exists methodIn line with ch [@michaeldyrynda](https://github.com/michaeldyrynda) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-06-05}...5.2@{2016-06-12})
- [bc551e4](https://github.com/laravel/docs/commit/bc551e44eaed92ca1bbe8292bb4680e65d6f7097): [5.2] Adjust eloquent-relationshipsAdjust `{relati [@lagbox](https://github.com/lagbox) 
- [51624ad](https://github.com/laravel/docs/commit/51624ad9871f29c95743c8cabd6cf17a1dca8dda): add note on arrays [@taylorotwell](https://github.com/taylorotwell) 
- [6e520fe](https://github.com/laravel/docs/commit/6e520fe739d8c7bd49ddcfc0e9d251229dc0a819): change wording [@taylorotwell](https://github.com/taylorotwell) 
- [960d77e](https://github.com/laravel/docs/commit/960d77eef257c41fc72ac24b01649463516b49e5): Added Temporarily Hiding Visible Properties [@johnwheal](https://github.com/johnwheal) 
- [e9377e2](https://github.com/laravel/docs/commit/e9377e269525e2a78e1334662607548759e9c92a): update wording [@taylorotwell](https://github.com/taylorotwell) 
- [019e109](https://github.com/laravel/docs/commit/019e109ee485bb80ce4d1289c6bb29208788c2ae): Add Cashier-Braintree link to Laravel projects [@samuelsan](https://github.com/samuelsan) 
- [e9344f6](https://github.com/laravel/docs/commit/e9344f6d5c58baca198e0067f2096e454143d8c5): Removed unessesary `!!` [@tillkruss](https://github.com/tillkruss) 


### [5.1](https://github.com/laravel/docs/compare/5.1@{2016-06-05}...5.1@{2016-06-12})
- [03961e3](https://github.com/laravel/docs/commit/03961e38628a2a539e199ec443087deaf7fb9552): Update helpers.md [@jsenin](https://github.com/jsenin) 


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-06-05}...master@{2016-06-12})
- [bd9f8e2](https://github.com/laravel/lumen-framework/commit/bd9f8e2ba40d92561dfb6b996cc4862e0a5e244d): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [e9fed18](https://github.com/laravel/lumen-framework/commit/e9fed189e1a20273a3696dfab8b413b2e721d2d9): version [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-06-05}...5.2@{2016-06-12})
- [e9fed18](https://github.com/laravel/lumen-framework/commit/e9fed189e1a20273a3696dfab8b413b2e721d2d9): version [@taylorotwell](https://github.com/taylorotwell) 


### [5.1](https://github.com/laravel/lumen-framework/compare/5.1@{2016-06-05}...5.1@{2016-06-12})
- [105029d](https://github.com/laravel/lumen-framework/commit/105029d56ea0de66a9528100de7acd5cfacf0116): version [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/lumen-docs](https://github.com/laravel/lumen-docs)

### [master](https://github.com/laravel/lumen-docs/compare/master@{2016-06-05}...master@{2016-06-12})
- [b003e09](https://github.com/laravel/lumen-docs/commit/b003e098f349d7191e2172fd300623e8f2396540): wording [@taylorotwell](https://github.com/taylorotwell) 
- [1e588ac](https://github.com/laravel/lumen-docs/commit/1e588ac6c013961397d87055d1c822f798d9cece): Added a note about getting started with redis on l [@GrahamCampbell](https://github.com/GrahamCampbell) 


### [5.2](https://github.com/laravel/lumen-docs/compare/5.2@{2016-06-05}...5.2@{2016-06-12})
- [270038e](https://github.com/laravel/lumen-docs/commit/270038e8ab38da886fc447d43108046219c734b4): Sentence about validator output was misleading [@dusterio](https://github.com/dusterio) 
- [b003e09](https://github.com/laravel/lumen-docs/commit/b003e098f349d7191e2172fd300623e8f2396540): wording [@taylorotwell](https://github.com/taylorotwell) 
- [1e588ac](https://github.com/laravel/lumen-docs/commit/1e588ac6c013961397d87055d1c822f798d9cece): Added a note about getting started with redis on l [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/quickstart-intermediate](https://github.com/laravel/quickstart-intermediate)

### [master](https://github.com/laravel/quickstart-intermediate/compare/master@{2016-06-05}...master@{2016-06-12})
- [aaefce5](https://github.com/laravel/quickstart-intermediate/commit/aaefce51bb18540239224dbae723cdf2020eff48): modified the url to match the routing. [@AmmuJose](https://github.com/AmmuJose) 
- [80ef2e5](https://github.com/laravel/quickstart-intermediate/commit/80ef2e5ae0cc8eb5fafa68ef037b859abc75cacd): Added url function to generate fully qualified URL [@bikalbasnet](https://github.com/bikalbasnet) 


___

## [laravel/cashier-braintree](https://github.com/laravel/cashier-braintree)

### [1.0](https://github.com/laravel/cashier-braintree/compare/1.0@{2016-06-05}...1.0@{2016-06-12})
- [a3b16b3](https://github.com/laravel/cashier-braintree/commit/a3b16b3fc7220cde26b9554acf83f015be20e5e4): Fix spelling mistakes [@samuelsan](https://github.com/samuelsan) 


___

## [laravel/settler](https://github.com/laravel/settler)

### [master](https://github.com/laravel/settler/compare/master@{2016-06-05}...master@{2016-06-12})
- [9ad04c6](https://github.com/laravel/settler/commit/9ad04c61eed8bbb163b567d4f8f9015ad6636a46): Upgrade nodejs to v6 [@simonkberg](https://github.com/simonkberg) 


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-06-05}...2.0@{2016-06-12})
- [07f4aea](https://github.com/laravel/socialite/commit/07f4aeace9fa8375e998eb1332ae170581e13c3b): Add VersionEye dependencies status [@lucasmichot](https://github.com/lucasmichot) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-06-05}...master@{2016-06-12})
- [a0daa5b](https://github.com/laravel/elixir/commit/a0daa5b1adc5a7579259f99a71fed06430ff7270): Normalize paths [@JeffreyWay](https://github.com/JeffreyWay) 
- [4156b0a](https://github.com/laravel/elixir/commit/4156b0a472c4a149fcce7713cf4ce8ecf56e6d36): Update CssTask.js [@ricardogobbosouza](https://github.com/ricardogobbosouza) 
- [b952cb8](https://github.com/laravel/elixir/commit/b952cb85df7ddcf77a516e741511518407f9fefb): Update Task.js [@ricardogobbosouza](https://github.com/ricardogobbosouza) 
- [ac2b290](https://github.com/laravel/elixir/commit/ac2b290743a060231a24537a8d4c1609423f27a5): Clear out all steps after the summary is prepared [@JeffreyWay](https://github.com/JeffreyWay) 
- [02ff9d3](https://github.com/laravel/elixir/commit/02ff9d395ce6184ff2f2ade1d070f4a24010c515): Trigger all tests on "gulp tdd"First time you run  [@JeffreyWay](https://github.com/JeffreyWay) 
- [ecf16fe](https://github.com/laravel/elixir/commit/ecf16fee2fd363be4f6b0c1ee0702a8e90a62388): No need to new up [@JeffreyWay](https://github.com/JeffreyWay) 
- [193a813](https://github.com/laravel/elixir/commit/193a81326bc3c7d51e1b2628f9eb7de53deba7b4): Record steps for version task [@JeffreyWay](https://github.com/JeffreyWay) 
- [cf84f3d](https://github.com/laravel/elixir/commit/cf84f3d42e4e76f586c62b9bc9ed9557ce88365f): Record step instead of log [@JeffreyWay](https://github.com/JeffreyWay) 


___

## [laravel/envoy](https://github.com/laravel/envoy)

### [master](https://github.com/laravel/envoy/compare/master@{2016-06-05}...master@{2016-06-12})
- [6ca254b](https://github.com/laravel/envoy/commit/6ca254bd5c6473016e72f36a84f9b7c05f0ee725): various refactorings and improvements [@taylorotwell](https://github.com/taylorotwell) 
- [9e54b3f](https://github.com/laravel/envoy/commit/9e54b3fb6b305955d8268e56f1f20417f38c8307): pass along vars in import [@taylorotwell](https://github.com/taylorotwell) 
- [c3bd1f5](https://github.com/laravel/envoy/commit/c3bd1f51e2bf321990f2234b0f48aafd78a2459a): add support for imports and parents [@taylorotwell](https://github.com/taylorotwell) 


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [Choose Your Tribe Wisely](http://laracasts.simplecast.fm/27)


___

## [Laracasts](https://laracasts.com)
- [Authentication With GitHub](https://laracasts.com/series/laravel-authentication-techniques/episodes/2)
- [The Console Component](https://laracasts.com/series/discover-symfony-components/episodes/1)
- [Consider Fluent Interfaces](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/14)
