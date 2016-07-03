---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (24-29 May 2016)
post::title: A week of Laravel (24-29 May 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [develop], laravel/docs [master], laravel/docs [5.2], laravel/lumen-framework [5.2], laravel/lumen-framework [5.1], laravel/lumen [develop], laravel/cashier-braintree [master], laravel/cashier-braintree [1.0], laravel/cashier [6.0], laravel/socialite [2.0], laravel/elixir [master], Podcasts: The Laracasts Snippet, Laracasts"
post::date: May 29, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-05-24}...master@{2016-05-29})
- [1bd59e5](https://github.com/laravel/framework/commit/1bd59e5df1241349fe9362309b82e86a6a312155): Applied CS fixes from StyleCI [@GrahamCampbell](https://github.com/GrahamCampbell)
- [21123c8](https://github.com/laravel/framework/commit/21123c84c39eb611aa94dad07c375e8ca46a9e2f): merge [@taylorotwell](https://github.com/taylorotwell)
- [5b88244](https://github.com/laravel/framework/commit/5b88244c0afd5febe9f54e8544b0870b55ef6cfd): fix return [@taylorotwell](https://github.com/taylorotwell)
- [e3986a4](https://github.com/laravel/framework/commit/e3986a423e0da04ff14d4ca1bbd870350d898e1d): Use a single chain with a flatMap to perform the s [@phroggyy](https://github.com/phroggyy)
- [8e394fc](https://github.com/laravel/framework/commit/8e394fc8384e88f549d29ec0c8f9829c9e459729): Cast expiration to int (#13708) [@bairdj](https://github.com/bairdj)
- [a5c5dae](https://github.com/laravel/framework/commit/a5c5dae231724d0595e346e3de69537af0754873): method reorder [@taylorotwell](https://github.com/taylorotwell)
- [811cee7](https://github.com/laravel/framework/commit/811cee7858efa381f700c2559c8e31ac8d438a28): Correctly load nested relationships for polymorphi [@phroggyy](https://github.com/phroggyy)
- [d8791b9](https://github.com/laravel/framework/commit/d8791b9da188705daa27181c462062a4b60e42a6): one line [@taylorotwell](https://github.com/taylorotwell)
- [ef736ef](https://github.com/laravel/framework/commit/ef736ef78b8a3e14cd59b63dcb915f25eb2f0baa): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [38acdd8](https://github.com/laravel/framework/commit/38acdd807faec4b85fd47051341ccaf666499551): fix boolean binding for json updates [@taylorotwell](https://github.com/taylorotwell)
- [45fc861](https://github.com/laravel/framework/commit/45fc8617d9c142c7576be2f00fb323c84bdfce76): Added release notes for v5.2.34 (#13734) [@tillkruss](https://github.com/tillkruss)
- [6a26f3b](https://github.com/laravel/framework/commit/6a26f3bb6a6e00c53654a661221643ad1b98e146): version [@taylorotwell](https://github.com/taylorotwell)
- [73695d9](https://github.com/laravel/framework/commit/73695d9766ff341906664c0f101e85189915a516): Remove unnecessary code (#13732) [@phroggyy](https://github.com/phroggyy)
- [d12c4bb](https://github.com/laravel/framework/commit/d12c4bbf8b09ff9cf916a8e54b15e43752f31350): Revert "[5.2] Fix issue #11815" (#13733) [@taylorotwell](https://github.com/taylorotwell)
- [fb546f8](https://github.com/laravel/framework/commit/fb546f8d67a610381ba5ccea6bf873d75d363805): Fix tests and cons [@taylorotwell](https://github.com/taylorotwell)
- [0908679](https://github.com/laravel/framework/commit/090867981d0fab6fbfec0413902d02dd8ab2f9e7): formatting and slight changes [@taylorotwell](https://github.com/taylorotwell)
- [3dfa927](https://github.com/laravel/framework/commit/3dfa927e77606ff3b3246f8e6e470770e3a75311): fix tests [@taylorotwell](https://github.com/taylorotwell)
- [e84b2ac](https://github.com/laravel/framework/commit/e84b2acd4b004fb6b870ed27d35b6436d9b17338): [5.2] Apply constraints to a morphTo relation on e [@phroggyy](https://github.com/phroggyy)
- [5fd23e4](https://github.com/laravel/framework/commit/5fd23e49a0155c04b53dcaf4d5a18e31511c76ab): Change redis ref keys to avoid breaking upgrades ( [@HughNoble](https://github.com/HughNoble)
- [ff176e1](https://github.com/laravel/framework/commit/ff176e10f5b450eba1608307d36c2f3428268ae6): Revert "Revert "[5.1] Improvements to Redis cache  [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-05-24}...5.2@{2016-05-29})
- [f9f115f](https://github.com/laravel/framework/commit/f9f115ffbcde2bc39dc4347d96af44acdf9149f0): Made the retry after check stricter (#13759) [@GrahamCampbell](https://github.com/GrahamCampbell)
- [dbfd364](https://github.com/laravel/framework/commit/dbfd3641c4b2bbfffd8a163ddf98e4347f43c3ce): [5.2] Test for #13242 (#13751)* Using mockery for  [@sebwas](https://github.com/sebwas)
- [35a5d64](https://github.com/laravel/framework/commit/35a5d6487962e4376fdfe568acc27f34b4f63656): Fixed the remaining attempts calculation (#13756) [@GrahamCampbell](https://github.com/GrahamCampbell)
- [710ff13](https://github.com/laravel/framework/commit/710ff13c552bc2f4a29c182cf5045ab79026d63c): [5.2] Container minor change (#13757)Just simplify [@KennedyTedesco](https://github.com/KennedyTedesco)
- [1bd59e5](https://github.com/laravel/framework/commit/1bd59e5df1241349fe9362309b82e86a6a312155): Applied CS fixes from StyleCI [@GrahamCampbell](https://github.com/GrahamCampbell)
- [5b88244](https://github.com/laravel/framework/commit/5b88244c0afd5febe9f54e8544b0870b55ef6cfd): fix return [@taylorotwell](https://github.com/taylorotwell)
- [e3986a4](https://github.com/laravel/framework/commit/e3986a423e0da04ff14d4ca1bbd870350d898e1d): Use a single chain with a flatMap to perform the s [@phroggyy](https://github.com/phroggyy)
- [8e394fc](https://github.com/laravel/framework/commit/8e394fc8384e88f549d29ec0c8f9829c9e459729): Cast expiration to int (#13708) [@bairdj](https://github.com/bairdj)
- [a5c5dae](https://github.com/laravel/framework/commit/a5c5dae231724d0595e346e3de69537af0754873): method reorder [@taylorotwell](https://github.com/taylorotwell)
- [811cee7](https://github.com/laravel/framework/commit/811cee7858efa381f700c2559c8e31ac8d438a28): Correctly load nested relationships for polymorphi [@phroggyy](https://github.com/phroggyy)
- [d8791b9](https://github.com/laravel/framework/commit/d8791b9da188705daa27181c462062a4b60e42a6): one line [@taylorotwell](https://github.com/taylorotwell)
- [38acdd8](https://github.com/laravel/framework/commit/38acdd807faec4b85fd47051341ccaf666499551): fix boolean binding for json updates [@taylorotwell](https://github.com/taylorotwell)
- [45fc861](https://github.com/laravel/framework/commit/45fc8617d9c142c7576be2f00fb323c84bdfce76): Added release notes for v5.2.34 (#13734) [@tillkruss](https://github.com/tillkruss)
- [6a26f3b](https://github.com/laravel/framework/commit/6a26f3bb6a6e00c53654a661221643ad1b98e146): version [@taylorotwell](https://github.com/taylorotwell)
- [73695d9](https://github.com/laravel/framework/commit/73695d9766ff341906664c0f101e85189915a516): Remove unnecessary code (#13732) [@phroggyy](https://github.com/phroggyy)
- [d12c4bb](https://github.com/laravel/framework/commit/d12c4bbf8b09ff9cf916a8e54b15e43752f31350): Revert "[5.2] Fix issue #11815" (#13733) [@taylorotwell](https://github.com/taylorotwell)
- [0908679](https://github.com/laravel/framework/commit/090867981d0fab6fbfec0413902d02dd8ab2f9e7): formatting and slight changes [@taylorotwell](https://github.com/taylorotwell)
- [3dfa927](https://github.com/laravel/framework/commit/3dfa927e77606ff3b3246f8e6e470770e3a75311): fix tests [@taylorotwell](https://github.com/taylorotwell)
- [e84b2ac](https://github.com/laravel/framework/commit/e84b2acd4b004fb6b870ed27d35b6436d9b17338): [5.2] Apply constraints to a morphTo relation on e [@phroggyy](https://github.com/phroggyy)
- [5fd23e4](https://github.com/laravel/framework/commit/5fd23e49a0155c04b53dcaf4d5a18e31511c76ab): Change redis ref keys to avoid breaking upgrades ( [@HughNoble](https://github.com/HughNoble)
- [ff176e1](https://github.com/laravel/framework/commit/ff176e10f5b450eba1608307d36c2f3428268ae6): Revert "Revert "[5.1] Improvements to Redis cache  [@taylorotwell](https://github.com/taylorotwell)
- [797df35](https://github.com/laravel/framework/commit/797df3569068d485a67baa1fe61e12ca74bb8a42): Fixed grammar [@GrahamCampbell](https://github.com/GrahamCampbell)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-05-24}...5.1@{2016-05-29})
- [1bd59e5](https://github.com/laravel/framework/commit/1bd59e5df1241349fe9362309b82e86a6a312155): Applied CS fixes from StyleCI [@GrahamCampbell](https://github.com/GrahamCampbell)
- [3dfa927](https://github.com/laravel/framework/commit/3dfa927e77606ff3b3246f8e6e470770e3a75311): fix tests [@taylorotwell](https://github.com/taylorotwell)
- [5fd23e4](https://github.com/laravel/framework/commit/5fd23e49a0155c04b53dcaf4d5a18e31511c76ab): Change redis ref keys to avoid breaking upgrades ( [@HughNoble](https://github.com/HughNoble)
- [ff176e1](https://github.com/laravel/framework/commit/ff176e10f5b450eba1608307d36c2f3428268ae6): Revert "Revert "[5.1] Improvements to Redis cache  [@taylorotwell](https://github.com/taylorotwell)
- [5945837](https://github.com/laravel/framework/commit/5945837bc61227f21530c8c4455de0842dc18c9a): versoin [@taylorotwell](https://github.com/taylorotwell)
- [c688e5a](https://github.com/laravel/framework/commit/c688e5a16c7185d5cf916288740f3f255de97d70): Use write database connection when validating uniq [@crynobone](https://github.com/crynobone)
- [1c1f2f2](https://github.com/laravel/framework/commit/1c1f2f2d87876be86fc1ce98efa0f2bc1a3670f6): Fix postgres Schema::hastable (#13008) [@themsaid](https://github.com/themsaid)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-05-24}...master@{2016-05-29})
- [9352968](https://github.com/laravel/laravel/commit/9352968734aa339c47218a931ba85b9b0d58fe23): Add missing Mandrill secret keys in config.service [@luqmanrom](https://github.com/luqmanrom)


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-05-24}...develop@{2016-05-29})
- [19f8537](https://github.com/laravel/laravel/commit/19f85378298e81dd227c814ed9e9bbd7f9c0b5da): fix namespace [@taylorotwell](https://github.com/taylorotwell)
- [9450525](https://github.com/laravel/laravel/commit/945052508f6c7a00909fd91e5bb9be14d0cbac53): Use the Authenticate middleware from core [@JosephSilber](https://github.com/JosephSilber)
- [cedde2d](https://github.com/laravel/laravel/commit/cedde2d934750ac38c35b257aad6ddeda15eb923): cleaning up [@taylorotwell](https://github.com/taylorotwell)
- [c332ad9](https://github.com/laravel/laravel/commit/c332ad9582e71d4f77aec018c388ea0239997cd6): fix typo [@taylorotwell](https://github.com/taylorotwell)
- [d26314d](https://github.com/laravel/laravel/commit/d26314de20f4165f7276646b97ff70ae18e096ff): Move the full response logic into the unauthentica [@JosephSilber](https://github.com/JosephSilber)


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-05-24}...master@{2016-05-29})
- [db83baf](https://github.com/laravel/docs/commit/db83baf57814605ac024a3994c047e5f1190e88f): adjust wording [@taylorotwell](https://github.com/taylorotwell)
- [9787dd8](https://github.com/laravel/docs/commit/9787dd862339771f165a3dd4160721ed6e78404f): Add flatten depth example [@JosephSilber](https://github.com/JosephSilber)
- [05a0a42](https://github.com/laravel/docs/commit/05a0a4208b0921715b28a8f3adc12352063e7bb5): Add dateTimeTz,timeTz,timestampTz to avaliable col [@marekr](https://github.com/marekr)
- [1b72bf8](https://github.com/laravel/docs/commit/1b72bf864ed69946697b11b8d64c638ee5d9383b): wording [@taylorotwell](https://github.com/taylorotwell)
- [3214fe5](https://github.com/laravel/docs/commit/3214fe519cf17079bbcb8aaa484a1a4bbdc5f16f): wording [@taylorotwell](https://github.com/taylorotwell)
- [4be4775](https://github.com/laravel/docs/commit/4be47754200feb4941229bb8ed07524b08d94e49): Update eloquent-relationships.md [@barryvdh](https://github.com/barryvdh)
- [e4f616b](https://github.com/laravel/docs/commit/e4f616bc035ab47ce15c73e6480f2806c569574c): Add withCount() documentation. [@barryvdh](https://github.com/barryvdh)
- [2950e6e](https://github.com/laravel/docs/commit/2950e6e4ade5a9ef8c6c35087aa8ac070ea4f802): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [fec308b](https://github.com/laravel/docs/commit/fec308b717db4b33564a9557c9f077cea85c8ba9): On setting number of daily log files allowed.There [@dbilovd](https://github.com/dbilovd)
- [fc374c1](https://github.com/laravel/docs/commit/fc374c1e674c3f7312ce6697526878aee08b75c6): add doc for inRandonOrder [@hamedmehryar](https://github.com/hamedmehryar)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-05-24}...5.2@{2016-05-29})
- [db83baf](https://github.com/laravel/docs/commit/db83baf57814605ac024a3994c047e5f1190e88f): adjust wording [@taylorotwell](https://github.com/taylorotwell)
- [9787dd8](https://github.com/laravel/docs/commit/9787dd862339771f165a3dd4160721ed6e78404f): Add flatten depth example [@JosephSilber](https://github.com/JosephSilber)
- [05a0a42](https://github.com/laravel/docs/commit/05a0a4208b0921715b28a8f3adc12352063e7bb5): Add dateTimeTz,timeTz,timestampTz to avaliable col [@marekr](https://github.com/marekr)
- [1b72bf8](https://github.com/laravel/docs/commit/1b72bf864ed69946697b11b8d64c638ee5d9383b): wording [@taylorotwell](https://github.com/taylorotwell)
- [3214fe5](https://github.com/laravel/docs/commit/3214fe519cf17079bbcb8aaa484a1a4bbdc5f16f): wording [@taylorotwell](https://github.com/taylorotwell)
- [4be4775](https://github.com/laravel/docs/commit/4be47754200feb4941229bb8ed07524b08d94e49): Update eloquent-relationships.md [@barryvdh](https://github.com/barryvdh)
- [e4f616b](https://github.com/laravel/docs/commit/e4f616bc035ab47ce15c73e6480f2806c569574c): Add withCount() documentation. [@barryvdh](https://github.com/barryvdh)
- [2950e6e](https://github.com/laravel/docs/commit/2950e6e4ade5a9ef8c6c35087aa8ac070ea4f802): fix wording [@taylorotwell](https://github.com/taylorotwell)
- [fec308b](https://github.com/laravel/docs/commit/fec308b717db4b33564a9557c9f077cea85c8ba9): On setting number of daily log files allowed.There [@dbilovd](https://github.com/dbilovd)
- [fc374c1](https://github.com/laravel/docs/commit/fc374c1e674c3f7312ce6697526878aee08b75c6): add doc for inRandonOrder [@hamedmehryar](https://github.com/hamedmehryar)


___

## [laravel/cashier-braintree](https://github.com/laravel/cashier-braintree)

### [master](https://github.com/laravel/cashier-braintree/compare/master@{2016-05-24}...master@{2016-05-29})
- [35fa428](https://github.com/laravel/cashier-braintree/commit/35fa42836e83d846e758ce503b47d8ea0fdd0947): fix method [@taylorotwell](https://github.com/taylorotwell)
- [cd666df](https://github.com/laravel/cashier-braintree/commit/cd666df84586b5a87136f071c64acb28d214cccc): comma [@taylorotwell](https://github.com/taylorotwell)
- [1b9687e](https://github.com/laravel/cashier-braintree/commit/1b9687e35efa2be52068c157341a6b564226c1d5): comma [@taylorotwell](https://github.com/taylorotwell)
- [b618e11](https://github.com/laravel/cashier-braintree/commit/b618e11cf686307bd929dca5d8ed9ef61d685333): backport change [@taylorotwell](https://github.com/taylorotwell)
- [0917810](https://github.com/laravel/cashier-braintree/commit/091781076e5802755e3137c217b35749271e278d): Use `array_merge` with defaults instead of `array_ [@besologic](https://github.com/besologic)


### [1.0](https://github.com/laravel/cashier-braintree/compare/1.0@{2016-05-24}...1.0@{2016-05-29})
- [35fa428](https://github.com/laravel/cashier-braintree/commit/35fa42836e83d846e758ce503b47d8ea0fdd0947): fix method [@taylorotwell](https://github.com/taylorotwell)
- [cd666df](https://github.com/laravel/cashier-braintree/commit/cd666df84586b5a87136f071c64acb28d214cccc): comma [@taylorotwell](https://github.com/taylorotwell)
- [b618e11](https://github.com/laravel/cashier-braintree/commit/b618e11cf686307bd929dca5d8ed9ef61d685333): backport change [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-05-24}...6.0@{2016-05-29})
- [9cf65cd](https://github.com/laravel/cashier/commit/9cf65cd1a177a35fce69353a2671fdadf4a1be19): cleaning up code. [@taylorotwell](https://github.com/taylorotwell)
- [9e21c77](https://github.com/laravel/cashier/commit/9e21c77e1fff3b89e8543ee635878349d64da1af): Styling again [@Francismori7](https://github.com/Francismori7)
- [2d2f84f](https://github.com/laravel/cashier/commit/2d2f84fb4041637f503c2334c7329f08a859e75d): Changes as per @taylorotwellMethod hasCardOnFile n [@Francismori7](https://github.com/Francismori7)
- [8fbfd80](https://github.com/laravel/cashier/commit/8fbfd80954982f9b077300b2b30dadba9b8873f4): Fix style [@Francismori7](https://github.com/Francismori7)
- [ff30091](https://github.com/laravel/cashier/commit/ff30091f8d26cfa822a49eef0fbac4e68af8e247): Fix default source issue [@Francismori7](https://github.com/Francismori7)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-05-24}...2.0@{2016-05-29})
- [378f056](https://github.com/laravel/socialite/commit/378f056fee40f00fd75a2c5a206feea4417c2abd): Also test with PHP 7 [@lucasmichot](https://github.com/lucasmichot)
- [83f2d18](https://github.com/laravel/socialite/commit/83f2d18006e5d5d2bbf60fa35548614d127a3253): Ensure the $user property can be accessed. [@lucasmichot](https://github.com/lucasmichot)
- [50921bb](https://github.com/laravel/socialite/commit/50921bb08dbb0985b572eb7cc5316793d31e4cb7): wording [@taylorotwell](https://github.com/taylorotwell)
- [1f9335d](https://github.com/laravel/socialite/commit/1f9335dd680a197ab71e28c685e59ee8eab7cbc7): Change scope of [@lucasmichot](https://github.com/lucasmichot)
- [953cc98](https://github.com/laravel/socialite/commit/953cc98ee046c6afe093aa56e97a850cfb219073): Add a note on not including state and response_typ [@hiendv](https://github.com/hiendv)
- [f3e3bdf](https://github.com/laravel/socialite/commit/f3e3bdf9368b96b82635cb88ab02944b7d036669): formatting fixes [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-05-24}...master@{2016-05-29})
- [26115a6](https://github.com/laravel/elixir/commit/26115a690a69443be1ca23aaad51900c9fc00fed): Fix import class [@JeffreyWay](https://github.com/JeffreyWay)
- [8bed054](https://github.com/laravel/elixir/commit/8bed054f495d3af7128f0271ae57d74b7db4cff9): gulp.src('') isn't recommended [@JeffreyWay](https://github.com/JeffreyWay)
- [69d67ff](https://github.com/laravel/elixir/commit/69d67ff316ffd68ede8f5632cb1e8e601af635aa): Use saveAs method [@JeffreyWay](https://github.com/JeffreyWay)
- [46b77a5](https://github.com/laravel/elixir/commit/46b77a50c97fff337d302a9f2119e46e6aed3dca): Remove deprecated method [@JeffreyWay](https://github.com/JeffreyWay)
- [ff3f2b7](https://github.com/laravel/elixir/commit/ff3f2b757c7ce6efeedbbc33c7ce6506a60f98db): Docblocks [@JeffreyWay](https://github.com/JeffreyWay)
- [65fb33f](https://github.com/laravel/elixir/commit/65fb33fafc69fd46a98183988c98c64361d8e453): Move other compilers over to Task subclasses [@JeffreyWay](https://github.com/JeffreyWay)
- [f201410](https://github.com/laravel/elixir/commit/f20141023e3dca440580ea9898f32a50e19b447b): Swap TestingCompiler with Task subclassKept findin [@JeffreyWay](https://github.com/JeffreyWay)
- [b20e61e](https://github.com/laravel/elixir/commit/b20e61e0f4278d7d3a6c85b9ef25bd74c8ee143d): Refactor PHPUnit + PHPSpec tasks [@JeffreyWay](https://github.com/JeffreyWay)
- [48048a5](https://github.com/laravel/elixir/commit/48048a528f2c7799ea8846209152c58370d6eb90): add filter method [@recca0120](https://github.com/recca0120)
- [ae77642](https://github.com/laravel/elixir/commit/ae77642aed9745723398dcaef9180fd4259b9d8b): Minor style guide fix [@JeffreyWay](https://github.com/JeffreyWay)


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [Let's Talk About Introversion](http://laracasts.simplecast.fm/25)


___

## [Laracasts](https://laracasts.com)
- [Elixir Refactoring](https://laracasts.com/series/whatcha-working-on/episodes/2)
- [Promises 101](https://laracasts.com/series/es6-cliffsnotes/episodes/13)
- [Consider Decorating](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/13)
