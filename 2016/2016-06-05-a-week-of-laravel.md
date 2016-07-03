---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (29 May-05 June 2016)
post::title: A week of Laravel (29 May-05 June 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [develop], laravel/docs [master], laravel/docs [5.2], laravel/docs [5.1], laravel/homestead [master], laravel/lumen-framework [master], laravel/lumen-framework [5.2], laravel/lumen-framework [5.1], laravel/lumen-docs [5.2], laravel/cashier [6.0], laravel/socialite [2.0], laravel/elixir [master], Podcasts: The Laravel Podcast, The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: June 05, 2016
---

## [laravel/framework](https://github.com/laravel/framework) 

### [master](https://github.com/laravel/framework/compare/master@{2016-05-29}...master@{2016-06-05})
- [f795b29](https://github.com/laravel/framework/commit/f795b29f7c30d4d60a0953711b2fa838c3b0a3b4): Fixed incorrect logging error suppression (#13881) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [02390dd](https://github.com/laravel/framework/commit/02390dd99bf90e6beed467efe2b015c20844395a): Updated the allowed random compat version (#13882) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [2813687](https://github.com/laravel/framework/commit/2813687472411e82ef863d9bb10a0e9daa42bc6a): prevent Cache::put() from falling into the forever [@halaei](https://github.com/halaei) 
- [f79332e](https://github.com/laravel/framework/commit/f79332e0c391f85159d33fd6a61dfd595b87335d): docblock fix for ApcStore: put() is a void functio [@halaei](https://github.com/halaei) 
- [52dd727](https://github.com/laravel/framework/commit/52dd727438941cee8c4299bea62c20d44397dc69): Corrected phpdoc [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [a41f1b3](https://github.com/laravel/framework/commit/a41f1b33bc385b21ffa0f290858b229fea08fbd4): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [2b801dc](https://github.com/laravel/framework/commit/2b801dc9cced3fc4c1c1426e8e2f4c45387f9dc1): no return [@taylorotwell](https://github.com/taylorotwell) 
- [25443e3](https://github.com/laravel/framework/commit/25443e3e218cce1121f546b596dd70b5fd2fb619): Fix AuthorizeResources. [@taylorotwell](https://github.com/taylorotwell) 
- [063091c](https://github.com/laravel/framework/commit/063091cdbcc52f6d96ef4e129acbdfbd9dc3e913): wording [@taylorotwell](https://github.com/taylorotwell) 
- [e54e797](https://github.com/laravel/framework/commit/e54e797432a60f165bea2b8c84c62a65fd7f2ca3): add tap helper and test [@taylorotwell](https://github.com/taylorotwell) 
- [7584880](https://github.com/laravel/framework/commit/75848802d85cb34cb585310543dc1d5f7d3d2f3b): slight formatting [@taylorotwell](https://github.com/taylorotwell) 
- [a92651e](https://github.com/laravel/framework/commit/a92651ea76932c4bc79ce9a72ec3b08cfd7790c3): [5.3] Improved the exception handler (#13859)* Imp [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [9545e49](https://github.com/laravel/framework/commit/9545e499a86ec27ed64bf85d8f9663f26c2a3d8e): Updated the validAuthenticationResponse() to look  [@tlaverdure](https://github.com/tlaverdure) 
- [7e07730](https://github.com/laravel/framework/commit/7e07730e7b5781735c9efc916a6349def98c744f): Removed old boot hack (#13856) [@GrahamCampbell](https://github.com/GrahamCampbell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-05-29}...5.2@{2016-06-05})
- [2341879](https://github.com/laravel/framework/commit/234187996f17f95cf9a88164ddd6776bf07ccd44): Minor Builder cleanup (#13884) [@acasar](https://github.com/acasar) 
- [f79332e](https://github.com/laravel/framework/commit/f79332e0c391f85159d33fd6a61dfd595b87335d): docblock fix for ApcStore: put() is a void functio [@halaei](https://github.com/halaei) 
- [2b801dc](https://github.com/laravel/framework/commit/2b801dc9cced3fc4c1c1426e8e2f4c45387f9dc1): no return [@taylorotwell](https://github.com/taylorotwell) 
- [25443e3](https://github.com/laravel/framework/commit/25443e3e218cce1121f546b596dd70b5fd2fb619): Fix AuthorizeResources. [@taylorotwell](https://github.com/taylorotwell) 
- [f2abad5](https://github.com/laravel/framework/commit/f2abad5dc3fc65d59b95f6165c27aa72fc5606d1): use interface [@taylorotwell](https://github.com/taylorotwell) 
- [247b414](https://github.com/laravel/framework/commit/247b414f2e8244af8d35f369d2bd632fdb947177): CS Fixes [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [0b863b8](https://github.com/laravel/framework/commit/0b863b83afa54f29745ee57c274d106a855de4b3): Removed accidently left in method (#13840) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [7bf4336](https://github.com/laravel/framework/commit/7bf43367b263e9e240b800bda91119551f4a8c37): [5.2] Validation of dates - Dealing with DateTime  [@KennedyTedesco](https://github.com/KennedyTedesco) 
- [13c981a](https://github.com/laravel/framework/commit/13c981a1c3cefdf52f0f5301bf828e82ef73e094): [5.2] Add a test for morphTo bad method call (#138 [@acasar](https://github.com/acasar) 
- [4811209](https://github.com/laravel/framework/commit/4811209231b3e20886ddaeafcea78c659be5b4af): Fix morphTo macro calls (#13828) [@acasar](https://github.com/acasar) 
- [bf05d24](https://github.com/laravel/framework/commit/bf05d24b9e300326130c56c438245a945d09a12a): Session now respects the http_only config option ( [@ddmills](https://github.com/ddmills) 
- [c9d9748](https://github.com/laravel/framework/commit/c9d97487c3520ccfda88b7f71100911e7554c189): [5.2] Refactor relations and scopes (#13824)* Refa [@acasar](https://github.com/acasar) 
- [35b4360](https://github.com/laravel/framework/commit/35b43607f381e2b00ff143c9288032df101464c2): rename method [@taylorotwell](https://github.com/taylorotwell) 
- [46d5d14](https://github.com/laravel/framework/commit/46d5d1461e3f0ab2766d74687f6b48a172967f45): less than one min for redis cache (#13810) [@halaei](https://github.com/halaei) 
- [550fe25](https://github.com/laravel/framework/commit/550fe258561e6ef700b5237c1bd1974624542db7): Add a point on suggest (#13808) [@lucasmichot](https://github.com/lucasmichot) 
- [5add162](https://github.com/laravel/framework/commit/5add162fedce647082de5efe6de9d6113c253b93): [5.2] Correct formatting of updatedAt timestamp wh [@jaimemasson](https://github.com/jaimemasson) 
- [8244d24](https://github.com/laravel/framework/commit/8244d2496ecc1bf9c6787632373fdf8204b729db): [5.2] Fix morphTo without SoftDeletes (#13806)* Fi [@acasar](https://github.com/acasar) 
- [4d7eb59](https://github.com/laravel/framework/commit/4d7eb59f9813723bab00b4e42ce9885b54e65778): Show actual handler class names in queue console o [@taylorotwell](https://github.com/taylorotwell) 
- [ace7f04](https://github.com/laravel/framework/commit/ace7f04ae579146ca3adf1c5992256c50ddc05a8): Use events, duh. [@taylorotwell](https://github.com/taylorotwell) 
- [03bbfb8](https://github.com/laravel/framework/commit/03bbfb83247a26799f93adaa679ae626667d9adb): dont serialize collections on 5.2 [@taylorotwell](https://github.com/taylorotwell) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-05-29}...5.1@{2016-06-05})
- [f79332e](https://github.com/laravel/framework/commit/f79332e0c391f85159d33fd6a61dfd595b87335d): docblock fix for ApcStore: put() is a void functio [@halaei](https://github.com/halaei) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-05-29}...master@{2016-06-05})
- [767801a](https://github.com/laravel/laravel/commit/767801a317928ac968bdc34270ccc87b5c41e057): working on formatting [@taylorotwell](https://github.com/taylorotwell) 
- [7259c26](https://github.com/laravel/laravel/commit/7259c265e69221e11c53cccd58a56e3b2db4cc76): Add application log level configurationThis config [@michaeldyrynda](https://github.com/michaeldyrynda) 
- [7a449f8](https://github.com/laravel/laravel/commit/7a449f86b98c0dce844a129ba40d3881c04df586): Make TestCase abstract [@drawmyattention](https://github.com/drawmyattention) 


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-05-29}...develop@{2016-06-05})
- [767801a](https://github.com/laravel/laravel/commit/767801a317928ac968bdc34270ccc87b5c41e057): working on formatting [@taylorotwell](https://github.com/taylorotwell) 
- [7259c26](https://github.com/laravel/laravel/commit/7259c265e69221e11c53cccd58a56e3b2db4cc76): Add application log level configurationThis config [@michaeldyrynda](https://github.com/michaeldyrynda) 
- [7a449f8](https://github.com/laravel/laravel/commit/7a449f86b98c0dce844a129ba40d3881c04df586): Make TestCase abstract [@drawmyattention](https://github.com/drawmyattention) 
- [4f01815](https://github.com/laravel/laravel/commit/4f018159b8865155fff3a47e0b7bb878902328d3): Update can middleware to new namespace [@JosephSilber](https://github.com/JosephSilber) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-05-29}...master@{2016-06-05})
- [eadd02e](https://github.com/laravel/docs/commit/eadd02e31f5328ee15baa377578fb921e51d3101): add semicolon [@taylorotwell](https://github.com/taylorotwell) 
- [38f6e61](https://github.com/laravel/docs/commit/38f6e61c688467621837fd29f490fbe4cb83aa02): fix example [@taylorotwell](https://github.com/taylorotwell) 
- [9d34dae](https://github.com/laravel/docs/commit/9d34dae6deeed84704afdfca4af796bee33b3e1b): fix example [@taylorotwell](https://github.com/taylorotwell) 
- [8558653](https://github.com/laravel/docs/commit/85586538d836288d497acfbfe8c35337c1b3dbb6): update docs for cookie queue [@taylorotwell](https://github.com/taylorotwell) 
- [9f982ff](https://github.com/laravel/docs/commit/9f982ff5d1b6e184e28550757bf019249ba30e50): document attachData [@taylorotwell](https://github.com/taylorotwell) 
- [fb4f857](https://github.com/laravel/docs/commit/fb4f857fb9788b2b678a29fc242a0d8ac23c6c86): Add missing quotation mark [@enderandpeter](https://github.com/enderandpeter) 
- [e45dbe3](https://github.com/laravel/docs/commit/e45dbe3cc5844e4934ee8ab43ab66f13182e2674): update wording [@taylorotwell](https://github.com/taylorotwell) 
- [39111e6](https://github.com/laravel/docs/commit/39111e69c96b4da4c16bd3cd5d56d4bcf4cd1475): Update authentication.mdUpdate Auth::login and Aut [@Quezler](https://github.com/Quezler) 
- [ee45fe4](https://github.com/laravel/docs/commit/ee45fe46c832fa0349834eac8bec8c5566ccc517): fix typo [@taylorotwell](https://github.com/taylorotwell) 
- [5fa397c](https://github.com/laravel/docs/commit/5fa397c4ffc9e4da35a480a13aef8fd1b4242297): Update to @after with variablesAll the code in the [@Tom5om](https://github.com/Tom5om) 
- [dee1cc0](https://github.com/laravel/docs/commit/dee1cc00ee3c04f385fb21770b35028ce79d01a8): Update mail.mdSparkPost support [@jrean](https://github.com/jrean) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-05-29}...5.2@{2016-06-05})
- [ef64ff3](https://github.com/laravel/docs/commit/ef64ff3d44bf5f43d1440bfe9a9b47e7803bb164): Update upgrade.mdGrammer error.  Array name in cod [@akoper](https://github.com/akoper) 
- [cc3b116](https://github.com/laravel/docs/commit/cc3b116dcfd9ff270c439bfe115c83225b09c773): fix wording [@taylorotwell](https://github.com/taylorotwell) 
- [0a298f7](https://github.com/laravel/docs/commit/0a298f741b63591e00e61022e97f3cb6c03a5ec4): Add documentation about configuring the log levelT [@michaeldyrynda](https://github.com/michaeldyrynda) 
- [aa44b9b](https://github.com/laravel/docs/commit/aa44b9b8ac647ac68b328f7989c30d77b3eb8897): more scheduler examples [@taylorotwell](https://github.com/taylorotwell) 
- [eadd02e](https://github.com/laravel/docs/commit/eadd02e31f5328ee15baa377578fb921e51d3101): add semicolon [@taylorotwell](https://github.com/taylorotwell) 
- [38f6e61](https://github.com/laravel/docs/commit/38f6e61c688467621837fd29f490fbe4cb83aa02): fix example [@taylorotwell](https://github.com/taylorotwell) 
- [9d34dae](https://github.com/laravel/docs/commit/9d34dae6deeed84704afdfca4af796bee33b3e1b): fix example [@taylorotwell](https://github.com/taylorotwell) 
- [8558653](https://github.com/laravel/docs/commit/85586538d836288d497acfbfe8c35337c1b3dbb6): update docs for cookie queue [@taylorotwell](https://github.com/taylorotwell) 
- [9f982ff](https://github.com/laravel/docs/commit/9f982ff5d1b6e184e28550757bf019249ba30e50): document attachData [@taylorotwell](https://github.com/taylorotwell) 
- [fb4f857](https://github.com/laravel/docs/commit/fb4f857fb9788b2b678a29fc242a0d8ac23c6c86): Add missing quotation mark [@enderandpeter](https://github.com/enderandpeter) 
- [e45dbe3](https://github.com/laravel/docs/commit/e45dbe3cc5844e4934ee8ab43ab66f13182e2674): update wording [@taylorotwell](https://github.com/taylorotwell) 
- [39111e6](https://github.com/laravel/docs/commit/39111e69c96b4da4c16bd3cd5d56d4bcf4cd1475): Update authentication.mdUpdate Auth::login and Aut [@Quezler](https://github.com/Quezler) 
- [ee45fe4](https://github.com/laravel/docs/commit/ee45fe46c832fa0349834eac8bec8c5566ccc517): fix typo [@taylorotwell](https://github.com/taylorotwell) 
- [5fa397c](https://github.com/laravel/docs/commit/5fa397c4ffc9e4da35a480a13aef8fd1b4242297): Update to @after with variablesAll the code in the [@Tom5om](https://github.com/Tom5om) 
- [dee1cc0](https://github.com/laravel/docs/commit/dee1cc00ee3c04f385fb21770b35028ce79d01a8): Update mail.mdSparkPost support [@jrean](https://github.com/jrean) 


### [5.1](https://github.com/laravel/docs/compare/5.1@{2016-05-29}...5.1@{2016-06-05})
- [b1c5485](https://github.com/laravel/docs/commit/b1c54852fcbb65fa77cf1792f2f2fd51211e43f3): Grammar [@JosephSilber](https://github.com/JosephSilber) 


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-05-29}...master@{2016-06-05})
- [178781e](https://github.com/laravel/homestead/commit/178781ec30deffd719c086faf87cdc652e177b23): Extended the previous "artisan" alias to take in a [@jjsee](https://github.com/jjsee) 


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-05-29}...master@{2016-06-05})
- [c75c8d0](https://github.com/laravel/lumen-framework/commit/c75c8d05ce2dc099d24c8255fd1322d7b440eb50): Updated the allowed random compat version [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [fddbb0a](https://github.com/laravel/lumen-framework/commit/fddbb0a1b86f1c09c77f0793c3db463c471adb83): Improved the exception handler [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [29eef29](https://github.com/laravel/lumen-framework/commit/29eef299852c4184a526cdbb3914f7f1b04c17cf): Allow resolving the validation factory by contract [@yuloh](https://github.com/yuloh) 


### [5.2](https://github.com/laravel/lumen-framework/compare/5.2@{2016-05-29}...5.2@{2016-06-05})
- [9c5387c](https://github.com/laravel/lumen-framework/commit/9c5387ce65eb079e5c446f49e143f9f290441c1f): Fixed incorrect logging error suppression [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [fddbb0a](https://github.com/laravel/lumen-framework/commit/fddbb0a1b86f1c09c77f0793c3db463c471adb83): Improved the exception handler [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [29eef29](https://github.com/laravel/lumen-framework/commit/29eef299852c4184a526cdbb3914f7f1b04c17cf): Allow resolving the validation factory by contract [@yuloh](https://github.com/yuloh) 


### [5.1](https://github.com/laravel/lumen-framework/compare/5.1@{2016-05-29}...5.1@{2016-06-05})
- [313c571](https://github.com/laravel/lumen-framework/commit/313c5711e66ddd622ea4dd524a01f00b9c0373d7): Fixed incorrect logging error suppression [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [1fae118](https://github.com/laravel/lumen-framework/commit/1fae1180263b79c73b646aca6a06c44b2f534f39): Improved the exception handler [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/lumen-docs](https://github.com/laravel/lumen-docs)

### [5.2](https://github.com/laravel/lumen-docs/compare/5.2@{2016-05-29}...5.2@{2016-06-05})
- [6868e12](https://github.com/laravel/lumen-docs/commit/6868e1290e49198610253a4ffa938d91712271df): Add missing space [@chimit](https://github.com/chimit) 
- [bc7aead](https://github.com/laravel/lumen-docs/commit/bc7aead2a320959a78ff568e6cbaf22d3920c193): Update 5.2 upgrade instructionsThe upgrade instruc [@aranw](https://github.com/aranw) 


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-05-29}...6.0@{2016-06-05})
- [ae2a169](https://github.com/laravel/cashier/commit/ae2a16954379ba765b0f7b50e7569f74d721c216): Update contributing.md [@taylorotwell](https://github.com/taylorotwell) 
- [07f8a57](https://github.com/laravel/cashier/commit/07f8a57cf62c1345d64fc8a8f0232bc1b09aee0e): Re-use code for startDate and endDate methods. Mak [@Francismori7](https://github.com/Francismori7) 
- [e300ae5](https://github.com/laravel/cashier/commit/e300ae5a06d2b8555d4790ba885d7189b13ede32): Dates improvedInvoice items now have Carbon versio [@Francismori7](https://github.com/Francismori7) 


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-05-29}...2.0@{2016-06-05})
- [b61d160](https://github.com/laravel/socialite/commit/b61d160ccffa5a75d4cfc02d7a06abc2ee2da0aa): move method [@taylorotwell](https://github.com/taylorotwell) 
- [78d7800](https://github.com/laravel/socialite/commit/78d780094b80b342cdf6d2287da581dc5aa256a1): Also permits phpunit ~5.0 [@lucasmichot](https://github.com/lucasmichot) 
- [ffc0dd2](https://github.com/laravel/socialite/commit/ffc0dd2275af1b51698f9bbbaeeaefb9265cef91): Return \Illuminate\Session\Store [@lucasmichot](https://github.com/lucasmichot) 
- [732d61a](https://github.com/laravel/socialite/commit/732d61a5424743fa3e4cdcb76860d2f50eee87ba): Add pretty badges to the readme [@joecohens](https://github.com/joecohens) 
- [af3c6fb](https://github.com/laravel/socialite/commit/af3c6fb67d2a46c06daa9f756b892731d8734913): Use stricter assertions [@lucasmichot](https://github.com/lucasmichot) 
- [65a4037](https://github.com/laravel/socialite/commit/65a40371fc87726b29bd007eec33e53820b9e22d): Switch to PSR-4 for tests [@lucasmichot](https://github.com/lucasmichot) 
- [3acc2b5](https://github.com/laravel/socialite/commit/3acc2b5404665aafb1d88fccd307f570cf74809b): Sort composer requirements [@lucasmichot](https://github.com/lucasmichot) 
- [09e81f0](https://github.com/laravel/socialite/commit/09e81f07d5f7545b2c5e744aca0a6faff9227582): Prefer Arr calls instead of helpers [@lucasmichot](https://github.com/lucasmichot) 
- [d374055](https://github.com/laravel/socialite/commit/d374055ace4310755b1b6dc55bb57a7782aa89e6): Updated method name [@KerryJones](https://github.com/KerryJones) 
- [f70ba4a](https://github.com/laravel/socialite/commit/f70ba4a03ee8ecd7d27d6309a7cec822f478d4d7): Fixed for StyleCi standards [@KerryJones](https://github.com/KerryJones) 
- [5e5c3f3](https://github.com/laravel/socialite/commit/5e5c3f3d554743f3542d115ba96d64d83bf87936): Added setRedirectUrl method for dynamic URL redire [@KerryJones](https://github.com/KerryJones) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-05-29}...master@{2016-06-05})
- [4b22b1b](https://github.com/laravel/elixir/commit/4b22b1b296bb473f56c184671fd003a132c25752): Refactor task description naming [@JeffreyWay](https://github.com/JeffreyWay) 
- [2d9170d](https://github.com/laravel/elixir/commit/2d9170d7b35b729f0e1b508956d131a6b2296494): Rename task.js to Task.js [@JeffreyWay](https://github.com/JeffreyWay) 
- [f9c026d](https://github.com/laravel/elixir/commit/f9c026df82e4b91622d930181adf468060cb8d69): Export correct class name [@JeffreyWay](https://github.com/JeffreyWay) 
- [e1bc6c3](https://github.com/laravel/elixir/commit/e1bc6c347b9f409bc646d20dd12683169625055e): Change Logger to Log [@JeffreyWay](https://github.com/JeffreyWay) 
- [a0cefa8](https://github.com/laravel/elixir/commit/a0cefa8563dd60d0d26e72ace3a7bfa7383f7db5): Create dedicated class for Gulp builder [@JeffreyWay](https://github.com/JeffreyWay) 
- [53b92d7](https://github.com/laravel/elixir/commit/53b92d74d185eeb6249a3429a2fbd64e7c3fbfbb): Cleaning up a couple things [@JeffreyWay](https://github.com/JeffreyWay) 
- [f1f410e](https://github.com/laravel/elixir/commit/f1f410e9f556c889de659e34b8973aa04b245d15): Simplify method checks [@JeffreyWay](https://github.com/JeffreyWay) 
- [5463887](https://github.com/laravel/elixir/commit/5463887961ce241432ae8f6c800949a20b01e381): Notification methods can be static [@JeffreyWay](https://github.com/JeffreyWay) 
- [7b0201a](https://github.com/laravel/elixir/commit/7b0201ac5413642d4b9ad82f883018f165febe8d): Space after class [@JeffreyWay](https://github.com/JeffreyWay) 
- [2b0332f](https://github.com/laravel/elixir/commit/2b0332f9ae77f2bd2025d6533190dea15416b702): Swap log out with record [@JeffreyWay](https://github.com/JeffreyWay) 
- [0e9f7aa](https://github.com/laravel/elixir/commit/0e9f7aa2015f874138cd28f1b9ab2bb644bdc251): Change heading [@JeffreyWay](https://github.com/JeffreyWay) 
- [8658af2](https://github.com/laravel/elixir/commit/8658af24a7cabebe1333a0eb94c0dc9671ce2bb9): Be more consistent about unhappy path first [@JeffreyWay](https://github.com/JeffreyWay) 
- [3bd3d9a](https://github.com/laravel/elixir/commit/3bd3d9a49e15030f9b8caed8c8cdca4075905bf5): Add console reportingLike this: http://d.pr/i/1kdj [@JeffreyWay](https://github.com/JeffreyWay) 
- [37e901a](https://github.com/laravel/elixir/commit/37e901ad4feb1e621b04bbf001b388d1b4abb058): Fix paths [@JeffreyWay](https://github.com/JeffreyWay) 
- [65249c4](https://github.com/laravel/elixir/commit/65249c408db00aef21c4a01866b46e2a34263d77): Change file name and references [@JeffreyWay](https://github.com/JeffreyWay) 
- [8dc2848](https://github.com/laravel/elixir/commit/8dc28480a7b04c6a051b5732fca942cab9446a7c): Adjusting folder structure [@JeffreyWay](https://github.com/JeffreyWay) 
- [5196fae](https://github.com/laravel/elixir/commit/5196faee8649ee820cfcb5d2737dcfb36eb1ef68): Removed old import [@JeffreyWay](https://github.com/JeffreyWay) 
- [01c89b1](https://github.com/laravel/elixir/commit/01c89b16e871e8c3a39b5db912cb21159a056eb5): Working on prettier loggingLike this: http://d.pr/ [@JeffreyWay](https://github.com/JeffreyWay) 
- [c341461](https://github.com/laravel/elixir/commit/c3414610bb0e9e047a836554d3d45256852800ff): Use "this" [@JeffreyWay](https://github.com/JeffreyWay) 
- [7741dc9](https://github.com/laravel/elixir/commit/7741dc94d4c510105c98d39b36c8fbaa086fcc38): Handle minification errors [@JeffreyWay](https://github.com/JeffreyWay) 
- [dc2ddc2](https://github.com/laravel/elixir/commit/dc2ddc2332afd21852d06cd609c5270a637bcf47): Catch JS minifier errors [@thecrypticace](https://github.com/thecrypticace) 
- [c45c534](https://github.com/laravel/elixir/commit/c45c5348b4cbac0633218018d6e4e77dbb2a30e4): Check for plugin in configuration file as fallback [@JeffreyWay](https://github.com/JeffreyWay) 
- [562c5cb](https://github.com/laravel/elixir/commit/562c5cbdac7809f950d63b655788d08e69cf2959): Fix an issue with gulp watch not running properlyT [@JeffreyWay](https://github.com/JeffreyWay) 
- [a35accc](https://github.com/laravel/elixir/commit/a35accc3fa30f5ef3d5409fb480686c6231d98be): Add CoffeeScript deprecation [@JeffreyWay](https://github.com/JeffreyWay) 
- [c3e3baf](https://github.com/laravel/elixir/commit/c3e3baf75c55de06ff462a0b5d4c7c46baa795da): Update Browserify deprecated message [@JeffreyWay](https://github.com/JeffreyWay) 
- [3b5c62a](https://github.com/laravel/elixir/commit/3b5c62a05a54d8dae0dfb62b408100a17ad49895): Don't override existing extensions [@JeffreyWay](https://github.com/JeffreyWay) 


___

## Podcasts

### [The Laravel Podcast](http://laravel.com)
- [Episode 45: Free Parking](http://www.laravelpodcast.com/episodes/38785-episode-45-free-parking)

### [The Laracasts Snippet](http://laracasts.audio)
- [Permission to Forget](http://laracasts.simplecast.fm/26)

### [Laravel News Podcast](https://laravel-news.com)
- [EP 18: ](http://podcast.laravel-news.com/18)


___

## [Laracasts](https://laracasts.com)
- [Authentication With No Passwords?](https://laracasts.com/series/laravel-authentication-techniques/episodes/1)
- [Useful String Additions](https://laracasts.com/series/es6-cliffsnotes/episodes/14)
- [Adding Featured Content](https://laracasts.com/series/whatcha-working-on/episodes/3)
- [Laravel Valet is the Bomb](https://laracasts.com/lessons/laravel-valet-is-the-bomb)
