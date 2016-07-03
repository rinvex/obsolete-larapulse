---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (15-24 May 2016)
post::title: A week of Laravel (15-24 May 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/docs [master], laravel/docs [5.2], laravel/homestead [master], laravel/lumen-framework [5.2], laravel/lumen [master], laravel/lumen-docs [master], laravel/lumen-docs [5.2], laravel/cashier [6.0], laravel/elixir [master], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: May 24, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-05-15}...master@{2016-05-24})
- [ef770ed](https://github.com/laravel/framework/commit/ef770edb08f3540aefffd916ae6ef5c8db58f0af): always make use call [@taylorotwell](https://github.com/taylorotwell)
- [4f96023](https://github.com/laravel/framework/commit/4f96023e4f3c06bc14d497192340daf065d39588): fix cons [@taylorotwell](https://github.com/taylorotwell)
- [bf5303f](https://github.com/laravel/framework/commit/bf5303fdc919d9d560df128b92a1891dc64ea488): set user resolver for request in shouldUse [@taylorotwell](https://github.com/taylorotwell)
- [16def48](https://github.com/laravel/framework/commit/16def48d9255af3caafaadd53b9336bc8607354f): [5.2] Add authenticate method to the guards (#1365 [@JosephSilber](https://github.com/JosephSilber)
- [4d4468e](https://github.com/laravel/framework/commit/4d4468e52969c5007fd52da8620749c2ef40b1f9): [5.2] Added missing Symfony UploadedFile class tes [@kboduch](https://github.com/kboduch)
- [1576199](https://github.com/laravel/framework/commit/1576199ffdbcda133b04eaf7c91a980b5c070e64): formatting [@taylorotwell](https://github.com/taylorotwell)
- [3901470](https://github.com/laravel/framework/commit/39014707d0d0018a090ed2aceb95b0c7591a5f60): [5.2] Added support for custom connection in passw [@whoan](https://github.com/whoan)
- [6c18818](https://github.com/laravel/framework/commit/6c188182adfbd067446ab57ab3566e2103542a52): Update FormRequest.php (#13652)Fixed Typo [@anoopmd](https://github.com/anoopmd)
- [5498133](https://github.com/laravel/framework/commit/5498133f8654f8d8ddc2a398f970fa2e5c486c7b): Fix casing in one of RouteCollection's test method [@gnumast](https://github.com/gnumast)
- [2715509](https://github.com/laravel/framework/commit/2715509a2842ee0402fd8ceebc21aab92c6d1f91): move transaction begin to logical method [@taylorotwell](https://github.com/taylorotwell)
- [d76da0c](https://github.com/laravel/framework/commit/d76da0c1a1e9d5a17841291bbf859a6b738dd0c2): fix assertions that check time() against score (#1 [@halaei](https://github.com/halaei)
- [468e890](https://github.com/laravel/framework/commit/468e8902759c585304e29b9ffed9b2b0123fb82a): Laravel Collection's makeVisible method should wor [@aguimaraes](https://github.com/aguimaraes)
- [ed7c6c6](https://github.com/laravel/framework/commit/ed7c6c600219ad32ed204027067b0b23fa82f12f): add tests [@taylorotwell](https://github.com/taylorotwell)
- [4fdd0d2](https://github.com/laravel/framework/commit/4fdd0d2848d6e079939cb3546e69d0a97d1ad7cb): Revert "IDE setting"i push die setting by mistake, [@RTLer](https://github.com/RTLer)
- [1be806a](https://github.com/laravel/framework/commit/1be806aabd79e9ceee8a12b7f1509872ae7261de): code style fix [@RTLer](https://github.com/RTLer)
- [a7091fd](https://github.com/laravel/framework/commit/a7091fd3ba2737565c3c6346b2f230570462a2e3): remove hardcoded connect_timeout and add default c [@RTLer](https://github.com/RTLer)
- [d49e82b](https://github.com/laravel/framework/commit/d49e82bf7278ad558c6fe60a6c0dde259959bab3): add connect_timeout:60 to SparkPostTransport [@RTLer](https://github.com/RTLer)
- [0d9a831](https://github.com/laravel/framework/commit/0d9a831255a4608a2ff63b127f8f9ff9562e3fb3): add connect_timeout:60 to MandrillTransport [@RTLer](https://github.com/RTLer)
- [9fcceb8](https://github.com/laravel/framework/commit/9fcceb8e3febc26441be50f62910abe7a03c86bd): add connect_timeout:60 to MailgunTransport [@RTLer](https://github.com/RTLer)
- [7842c4f](https://github.com/laravel/framework/commit/7842c4fab65e32f23ecb0137b18331a00d195f4c): more tests for isset on eloquent models and relati [@taylorotwell](https://github.com/taylorotwell)
- [38eafa8](https://github.com/laravel/framework/commit/38eafa8a808a8285137f1c3a80ce058c7ea1393c): spacing [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-05-15}...5.2@{2016-05-24})
- [ef770ed](https://github.com/laravel/framework/commit/ef770edb08f3540aefffd916ae6ef5c8db58f0af): always make use call [@taylorotwell](https://github.com/taylorotwell)
- [bf5303f](https://github.com/laravel/framework/commit/bf5303fdc919d9d560df128b92a1891dc64ea488): set user resolver for request in shouldUse [@taylorotwell](https://github.com/taylorotwell)
- [16def48](https://github.com/laravel/framework/commit/16def48d9255af3caafaadd53b9336bc8607354f): [5.2] Add authenticate method to the guards (#1365 [@JosephSilber](https://github.com/JosephSilber)
- [4d4468e](https://github.com/laravel/framework/commit/4d4468e52969c5007fd52da8620749c2ef40b1f9): [5.2] Added missing Symfony UploadedFile class tes [@kboduch](https://github.com/kboduch)
- [1576199](https://github.com/laravel/framework/commit/1576199ffdbcda133b04eaf7c91a980b5c070e64): formatting [@taylorotwell](https://github.com/taylorotwell)
- [3901470](https://github.com/laravel/framework/commit/39014707d0d0018a090ed2aceb95b0c7591a5f60): [5.2] Added support for custom connection in passw [@whoan](https://github.com/whoan)
- [6c18818](https://github.com/laravel/framework/commit/6c188182adfbd067446ab57ab3566e2103542a52): Update FormRequest.php (#13652)Fixed Typo [@anoopmd](https://github.com/anoopmd)
- [5498133](https://github.com/laravel/framework/commit/5498133f8654f8d8ddc2a398f970fa2e5c486c7b): Fix casing in one of RouteCollection's test method [@gnumast](https://github.com/gnumast)
- [2715509](https://github.com/laravel/framework/commit/2715509a2842ee0402fd8ceebc21aab92c6d1f91): move transaction begin to logical method [@taylorotwell](https://github.com/taylorotwell)
- [468e890](https://github.com/laravel/framework/commit/468e8902759c585304e29b9ffed9b2b0123fb82a): Laravel Collection's makeVisible method should wor [@aguimaraes](https://github.com/aguimaraes)
- [ed7c6c6](https://github.com/laravel/framework/commit/ed7c6c600219ad32ed204027067b0b23fa82f12f): add tests [@taylorotwell](https://github.com/taylorotwell)
- [4fdd0d2](https://github.com/laravel/framework/commit/4fdd0d2848d6e079939cb3546e69d0a97d1ad7cb): Revert "IDE setting"i push die setting by mistake, [@RTLer](https://github.com/RTLer)
- [1be806a](https://github.com/laravel/framework/commit/1be806aabd79e9ceee8a12b7f1509872ae7261de): code style fix [@RTLer](https://github.com/RTLer)
- [a7091fd](https://github.com/laravel/framework/commit/a7091fd3ba2737565c3c6346b2f230570462a2e3): remove hardcoded connect_timeout and add default c [@RTLer](https://github.com/RTLer)
- [d49e82b](https://github.com/laravel/framework/commit/d49e82bf7278ad558c6fe60a6c0dde259959bab3): add connect_timeout:60 to SparkPostTransport [@RTLer](https://github.com/RTLer)
- [0d9a831](https://github.com/laravel/framework/commit/0d9a831255a4608a2ff63b127f8f9ff9562e3fb3): add connect_timeout:60 to MandrillTransport [@RTLer](https://github.com/RTLer)
- [9fcceb8](https://github.com/laravel/framework/commit/9fcceb8e3febc26441be50f62910abe7a03c86bd): add connect_timeout:60 to MailgunTransport [@RTLer](https://github.com/RTLer)
- [7842c4f](https://github.com/laravel/framework/commit/7842c4fab65e32f23ecb0137b18331a00d195f4c): more tests for isset on eloquent models and relati [@taylorotwell](https://github.com/taylorotwell)
- [38eafa8](https://github.com/laravel/framework/commit/38eafa8a808a8285137f1c3a80ce058c7ea1393c): spacing [@taylorotwell](https://github.com/taylorotwell)
- [4abb185](https://github.com/laravel/framework/commit/4abb185e5a60148676df2333fe36ed9c31f8f480): Add softDeletesIntegration test for withCount [Barry vd. Heuvel]
- [9d68e54](https://github.com/laravel/framework/commit/9d68e548f50fce67682102fd2470bd23b039f1ed): Switch wheres/constraints, use toBase() instead of [Barry vd. Heuvel]
- [03300b0](https://github.com/laravel/framework/commit/03300b0632d1839b12139022bd0a3aa6055f6ddb): Add test for merged wheres in withCount [Barry vd. Heuvel]
- [356e199](https://github.com/laravel/framework/commit/356e19914614896e0f7ec940468e24848135d552): Add test for merged wheres in withCount [Barry vd. Heuvel]


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-05-15}...5.1@{2016-05-24})
- [7842c4f](https://github.com/laravel/framework/commit/7842c4fab65e32f23ecb0137b18331a00d195f4c): more tests for isset on eloquent models and relati [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-05-15}...master@{2016-05-24})
- [eb122a3](https://github.com/laravel/docs/commit/eb122a3fb9f1210c48548e6f7a28b0d47b506122): wording changes [@taylorotwell](https://github.com/taylorotwell)
- [e55e1bf](https://github.com/laravel/docs/commit/e55e1bf075a7f44d39f58085e5665b358a726802): [5.3] Document join clause changesI documented som [@acasar](https://github.com/acasar)
- [5c2addd](https://github.com/laravel/docs/commit/5c2addd2eb7deab34a38e91d56d5d5b734c6abde): fixes [@taylorotwell](https://github.com/taylorotwell)
- [878916e](https://github.com/laravel/docs/commit/878916efdd35f0296626bf4de19481eab540b774): Fix broken anchor nameMatch dimension validation a [@tomxc](https://github.com/tomxc)
- [e3fd7f6](https://github.com/laravel/docs/commit/e3fd7f6e282df9e63e18d06fba494c860ce40b73): Docs for whereColumn [@bmitch](https://github.com/bmitch)
- [b5b617a](https://github.com/laravel/docs/commit/b5b617a2d7354f81887a1108e6efeeb1709f9590): wording [@taylorotwell](https://github.com/taylorotwell)
- [6505ce4](https://github.com/laravel/docs/commit/6505ce417095631961ab31150d63410839f0967e): Adds localhost server reference to envoy.mdI had t [@underthecocotree](https://github.com/underthecocotree)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-05-15}...5.2@{2016-05-24})
- [36515d9](https://github.com/laravel/docs/commit/36515d9942a5cfb98da2629e06372702e11ebfb4): fix its [@taylorotwell](https://github.com/taylorotwell)
- [2462d6c](https://github.com/laravel/docs/commit/2462d6c9eec7552a1991f77e568b2a5926b2fa2e): Added diffKeys collection method documentation [@Ilyes512](https://github.com/Ilyes512)
- [ea28733](https://github.com/laravel/docs/commit/ea287335afc8af6bbdb8caaec4dc0f0cf692f77b): consistent quotes [@tymondesigns](https://github.com/tymondesigns)
- [71f42c2](https://github.com/laravel/docs/commit/71f42c2bcc4d43edc86600c65f6398645dbb5682): Add missing variable [@krienow](https://github.com/krienow)
- [2c701bd](https://github.com/laravel/docs/commit/2c701bd7fc1b01672698170e6302a7ce0ff48087): wording [@taylorotwell](https://github.com/taylorotwell)
- [b77f09a](https://github.com/laravel/docs/commit/b77f09aba691a42447a9293c694911a97ee80bd0): wording [@taylorotwell](https://github.com/taylorotwell)
- [065f7f6](https://github.com/laravel/docs/commit/065f7f6ff77454b4566297b0190941e3dce5cf5b): Update validation.md [@alexbowers](https://github.com/alexbowers)
- [5c2addd](https://github.com/laravel/docs/commit/5c2addd2eb7deab34a38e91d56d5d5b734c6abde): fixes [@taylorotwell](https://github.com/taylorotwell)
- [878916e](https://github.com/laravel/docs/commit/878916efdd35f0296626bf4de19481eab540b774): Fix broken anchor nameMatch dimension validation a [@tomxc](https://github.com/tomxc)
- [e3fd7f6](https://github.com/laravel/docs/commit/e3fd7f6e282df9e63e18d06fba494c860ce40b73): Docs for whereColumn [@bmitch](https://github.com/bmitch)
- [b5b617a](https://github.com/laravel/docs/commit/b5b617a2d7354f81887a1108e6efeeb1709f9590): wording [@taylorotwell](https://github.com/taylorotwell)
- [6505ce4](https://github.com/laravel/docs/commit/6505ce417095631961ab31150d63410839f0967e): Adds localhost server reference to envoy.mdI had t [@underthecocotree](https://github.com/underthecocotree)


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-05-15}...master@{2016-05-24})
- [4306594](https://github.com/laravel/homestead/commit/430659488844c695b3900013d180d1a1473899d7): Assist syntax highlighters w/Vagrantfile language [@QWp6t](https://github.com/QWp6t)


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [master](https://github.com/laravel/lumen/compare/master@{2016-05-15}...master@{2016-05-24})
- [b97610b](https://github.com/laravel/lumen/commit/b97610b7c60f9eaccd68dcbc1381bcf91ca47a6b): adding post root package install composer script [@michaeljhopkins](https://github.com/michaeljhopkins)


___

## [laravel/lumen-docs](https://github.com/laravel/lumen-docs)

### [master](https://github.com/laravel/lumen-docs/compare/master@{2016-05-15}...master@{2016-05-24})
- [6402e4e](https://github.com/laravel/lumen-docs/commit/6402e4edbd2d91cb11285c321a7b8f6f453497b7): remove some wording [@taylorotwell](https://github.com/taylorotwell)
- [306c790](https://github.com/laravel/lumen-docs/commit/306c7908b19f444a336faac578f0e69005f8b30c): Docs no longer indicate daily log files are create [@benswinburne](https://github.com/benswinburne)


### [5.2](https://github.com/laravel/lumen-docs/compare/5.2@{2016-05-15}...5.2@{2016-05-24})
- [6402e4e](https://github.com/laravel/lumen-docs/commit/6402e4edbd2d91cb11285c321a7b8f6f453497b7): remove some wording [@taylorotwell](https://github.com/taylorotwell)
- [306c790](https://github.com/laravel/lumen-docs/commit/306c7908b19f444a336faac578f0e69005f8b30c): Docs no longer indicate daily log files are create [@benswinburne](https://github.com/benswinburne)


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-05-15}...6.0@{2016-05-24})
- [47726c6](https://github.com/laravel/cashier/commit/47726c607a853261d94e652f264d58104915f065): break long line [@taylorotwell](https://github.com/taylorotwell)
- [428f24b](https://github.com/laravel/cashier/commit/428f24b0b20b45201f45ff9976e3ba2c3934a468): Pass coupon to Stripe API when using withCouponCou [@austinpray](https://github.com/austinpray)
- [1836485](https://github.com/laravel/cashier/commit/18364859f1f826ce99ffe7f32ef599a004257341): Allow email to be set when creating customerUpdate [@kyranb](https://github.com/kyranb)


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-05-15}...master@{2016-05-24})
- [5b0a2cb](https://github.com/laravel/elixir/commit/5b0a2cbbe93d332f24b56018f0307ce5ecc5b808): Cleaning up some things [@JeffreyWay](https://github.com/JeffreyWay)
- [84bcc79](https://github.com/laravel/elixir/commit/84bcc79ab322be63459a492f10c0c2f93a25a869): Revert back to regular function [@JeffreyWay](https://github.com/JeffreyWay)
- [5cef997](https://github.com/laravel/elixir/commit/5cef997bd9a7578e4eade795c568044cf0c14a0a): Needs to be regular function keyword [@JeffreyWay](https://github.com/JeffreyWay)
- [a4dafe9](https://github.com/laravel/elixir/commit/a4dafe967fad2b73d42b06f69b83c7a133e2307e): Formatting [@JeffreyWay](https://github.com/JeffreyWay)
- [84c824b](https://github.com/laravel/elixir/commit/84c824b49d58238f0dd13fa6f1bf4c9a631953dd): Check param name [@JeffreyWay](https://github.com/JeffreyWay)
- [e390bdd](https://github.com/laravel/elixir/commit/e390bdd5c233c2d0d12b0acda68a58dd9982fb3d): Add task name to error message [@JeffreyWay](https://github.com/JeffreyWay)
- [4c50884](https://github.com/laravel/elixir/commit/4c50884823f2c04d7a284b8521539aff7a7e7563): Move method to subclass [@JeffreyWay](https://github.com/JeffreyWay)
- [7355e42](https://github.com/laravel/elixir/commit/7355e426d72c7d9f2b19ffd107339c13075b84f2): Formatting [@JeffreyWay](https://github.com/JeffreyWay)
- [e33ca3b](https://github.com/laravel/elixir/commit/e33ca3b9f61b5078bac585fc2111cfb3ee70bc2d): Pretty formatting matters, yo [@JeffreyWay](https://github.com/JeffreyWay)
- [2513d85](https://github.com/laravel/elixir/commit/2513d851e6ddc44f10fa1204a02a8748200c265a): Add an inProduction prop to main Elixir object [@JeffreyWay](https://github.com/JeffreyWay)
- [6bbec82](https://github.com/laravel/elixir/commit/6bbec8232923d385162a3953a01c2598fe597b07): Remove space [@JeffreyWay](https://github.com/JeffreyWay)
- [c045f27](https://github.com/laravel/elixir/commit/c045f2756787421e008a1291c5ceba8365da332c): Two line breaks between methods [@JeffreyWay](https://github.com/JeffreyWay)
- [870e5af](https://github.com/laravel/elixir/commit/870e5af6a4e45a7bbb2f5b228fef94e40bd6bde8): Formatting [@JeffreyWay](https://github.com/JeffreyWay)
- [3c05ae5](https://github.com/laravel/elixir/commit/3c05ae55d3da3b0c4039dc628bf38b80f76d114e): Remove unused file [@JeffreyWay](https://github.com/JeffreyWay)
- [4bad253](https://github.com/laravel/elixir/commit/4bad253cff72e6a1bd73abf02cd8f0cfbaf2affc): Add CSS and JS compiler classes [@JeffreyWay](https://github.com/JeffreyWay)
- [99f7e22](https://github.com/laravel/elixir/commit/99f7e22fa7764510d9082e97c0bafa03912f57ac): Use Compiler class for common compilers. [@JeffreyWay](https://github.com/JeffreyWay)
- [6be3d70](https://github.com/laravel/elixir/commit/6be3d7093c3adfdf6ca6087fcf0c56c5d38dedcb): Export at bottom [@JeffreyWay](https://github.com/JeffreyWay)
- [afc9252](https://github.com/laravel/elixir/commit/afc925219736b8e00a6714d19491795a15fa2584): Remove some Gulp duplication [@JeffreyWay](https://github.com/JeffreyWay)
- [ca8861a](https://github.com/laravel/elixir/commit/ca8861a31d8e6b18c9bd4b01b6f231e69d42bf93): Make tests green [@JeffreyWay](https://github.com/JeffreyWay)
- [5641ec2](https://github.com/laravel/elixir/commit/5641ec288a13fb1131dc05a167ee41667d0aeec6): Merge mix.combine() and mix.compress()Turns out th [@JeffreyWay](https://github.com/JeffreyWay)
- [075f1af](https://github.com/laravel/elixir/commit/075f1af8cf41763d34b79c9e2f4cbe8b3bfd816a): No need to watch. Webpack will do it. [@JeffreyWay](https://github.com/JeffreyWay)
- [c9f4fba](https://github.com/laravel/elixir/commit/c9f4fba3b0619b70c7636043368b47c704f98d76): mix.compress requires a full output pathThis only  [@JeffreyWay](https://github.com/JeffreyWay)
- [ab04b64](https://github.com/laravel/elixir/commit/ab04b64328fe5a01b4db54e8a8b5cd084b060ee6): Make file parser function globally available [@JeffreyWay](https://github.com/JeffreyWay)
- [991a0ad](https://github.com/laravel/elixir/commit/991a0adc8690b93e0f1f56f13b00a88e072e0114): mix.combine requires an output path. [@JeffreyWay](https://github.com/JeffreyWay)
- [996c91d](https://github.com/laravel/elixir/commit/996c91d21148dafd05571c930c6e5b88cf695767): No need let buble [@ricardogobbosouza](https://github.com/ricardogobbosouza)
- [50ee15b](https://github.com/laravel/elixir/commit/50ee15bde09846913c7429bde2bf8ad726516383): Automatically import webpack.config.js if present. [@JeffreyWay](https://github.com/JeffreyWay)
- [80429d6](https://github.com/laravel/elixir/commit/80429d6b0e7bbe95626aaa0c14b84fc3a9ca0724): Refactor logger [@JeffreyWay](https://github.com/JeffreyWay)
- [aafb354](https://github.com/laravel/elixir/commit/aafb35431e83673389fa9d2631634d76bf1e49ac): Extract method [@JeffreyWay](https://github.com/JeffreyWay)
- [5cd0a6c](https://github.com/laravel/elixir/commit/5cd0a6c567917a6ecd7993e4e4114595b1e78f27): No need to pass Elixir to Task module [@JeffreyWay](https://github.com/JeffreyWay)


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [About Frameworks Being Dead...](http://laracasts.simplecast.fm/24)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 17: Laravel Echo, Valet, and PHP-FIG implosion](http://podcast.laravel-news.com/17)


___

## [Laracasts](https://laracasts.com)
- [Laravel Test Helpers for Selenium](https://laracasts.com/series/whatcha-working-on/episodes/1)
- [Too Many Method Parameters is a Sign](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/12)
- [Module Bundling With Webpack](https://laracasts.com/series/es6-cliffsnotes/episodes/12)
- [Consider View Models](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/11)
- [Module Bundling With Rollup](https://laracasts.com/series/es6-cliffsnotes/episodes/11)
