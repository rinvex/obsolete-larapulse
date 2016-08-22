# A week of Laravel #19 (15-22 August 2016)

> **Updates:** "Updates: laravel/framework [master, 5.2, 5.1], laravel/laravel [develop], laravel/docs [master, 5.2], laravel/homestead [master], laravel/lumen [develop], laravel/laravel.com [master], laravel/cashier [master], laravel/valet [master], laravel/echo [master], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts, Larajobs"

> **Published:** August 22, 2016

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-08-15}...master@{2016-08-22})
- [99cf673](https://github.com/laravel/framework/commit/99cf673faea7ed8c18f534596685492b4fb615e0): add file class [@taylorotwell](https://github.com/taylorotwell) 
- [eeef441](https://github.com/laravel/framework/commit/eeef4412dde232071afdfdf0803fd645e364b70a): add a few helpers [@taylorotwell](https://github.com/taylorotwell) 
- [e7cebe8](https://github.com/laravel/framework/commit/e7cebe897c792e6c77485124d95c7b7d8aa78de1): Refactor file storage location. [@taylorotwell](https://github.com/taylorotwell) 
- [bd07602](https://github.com/laravel/framework/commit/bd076028a2532bc6b140ff696dba920bab276fdb): Return a more sensible URL if file is in storage/p [@taylorotwell](https://github.com/taylorotwell) 
- [3da3248](https://github.com/laravel/framework/commit/3da3248afee9da06e0e173c2890104183e765cdb): fix a few formatting issues and test [@taylorotwell](https://github.com/taylorotwell) 
- [71040ec](https://github.com/laravel/framework/commit/71040ec51e58d96f521ab5d5ccf600ea3c4305be): Make getTokenForRequest public (#14927)When callin [@malhal](https://github.com/malhal) 
- [3e385d0](https://github.com/laravel/framework/commit/3e385d09f9ef57150d0d4d8f49ff2b856d0ef293): Throw ModelNotFoundException when model bind not f [@malhal](https://github.com/malhal) 
- [28cc111](https://github.com/laravel/framework/commit/28cc111bf15c501413d0303a849d21c278677106): fix ordering [@taylorotwell](https://github.com/taylorotwell) 
- [6c02461](https://github.com/laravel/framework/commit/6c02461685854c490076e32acb4467eec75e4e67): Add optional response data to the NotificationSent [@gregoriohc](https://github.com/gregoriohc) 
- [a9d80be](https://github.com/laravel/framework/commit/a9d80be3df3b52ea9b9866d5ee614e8996f8f294): Mock correct method on NotificationDispatcher (#14 [@viqtor](https://github.com/viqtor) 
- [2ffa69f](https://github.com/laravel/framework/commit/2ffa69f839746d40ccd0b664ded40d07ec25cbcc): The option function only takes on argument [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [654905b](https://github.com/laravel/framework/commit/654905b7028e52b10d540f2c037036158adcce84): Elegant handling of redirect responses (#14899) [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [ade5e7e](https://github.com/laravel/framework/commit/ade5e7ecf94c4921f0c16a1b444b6a8fe7f0f737): fix notification cloning bug [@taylorotwell](https://github.com/taylorotwell) 
- [1eade80](https://github.com/laravel/framework/commit/1eade8052e571cee59e3e9eb89762943e186aa1b): tweak for handled jobs [@taylorotwell](https://github.com/taylorotwell) 
- [c0b0245](https://github.com/laravel/framework/commit/c0b0245894b11cca333f010aa60da6e068d611d2): tweak one thing [@taylorotwell](https://github.com/taylorotwell) 
- [240f538](https://github.com/laravel/framework/commit/240f53872c7d7eb143bd6e71ac5725394d318ac5): toBase should always return a new instance (#14891 [@JosephSilber](https://github.com/JosephSilber) 
- [64b2015](https://github.com/laravel/framework/commit/64b2015f3156ad67fbd4b006efc3b629ec41b989): revert recent changes to key generate. [@taylorotwell](https://github.com/taylorotwell) 
- [9d0487b](https://github.com/laravel/framework/commit/9d0487bd04b8799cb7da3898b1277d6ac32969dc): Remove empty class content. [@daylerees](https://github.com/daylerees) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-08-15}...5.2@{2016-08-22})
- [f6fe8b2](https://github.com/laravel/framework/commit/f6fe8b2492ede0b882607cabc1af40e5765ef133): Revert "[5.2] Wrap APP_KEY in quotes when regenera [@tillkruss](https://github.com/tillkruss) 
- [1a63ac0](https://github.com/laravel/framework/commit/1a63ac08254e0560a3a67bdf8cbff218f98dbc7b): Fixing typo in cached missing event [@lukepolo](https://github.com/lukepolo) 
- [74099ec](https://github.com/laravel/framework/commit/74099ecf433735adc3813689d4be7aa22fd1e4a0): [5.2] Wrap APP_KEY in quotes when regenerating key [@caiquecastro](https://github.com/caiquecastro) 
- [e4e7d51](https://github.com/laravel/framework/commit/e4e7d517368aa74e5fcc9d1924a119c04dcb0188): fix order [@taylorotwell](https://github.com/taylorotwell) 
- [85420ef](https://github.com/laravel/framework/commit/85420ef5dd4e2038350ff0f98f794390e1de5bca): Fixes issue #14877 [@AdenFraser](https://github.com/AdenFraser) 
- [9d63777](https://github.com/laravel/framework/commit/9d637776998fea6ea7958e2012838559b1ba5f8c): adds clearer method and stub names (#14869) [@rsahai91](https://github.com/rsahai91) 
- [afd9c98](https://github.com/laravel/framework/commit/afd9c98dc66661b570e26b65b94d60f061a290db): allow the disable_asserts config value (#14864) [@jasonvarga](https://github.com/jasonvarga) 
- [41b65a5](https://github.com/laravel/framework/commit/41b65a58e14fcc1e9d13219920194823eb41d77e): Cast only one to array. (#14857) [@lucasmichot](https://github.com/lucasmichot) 
- [8c08bed](https://github.com/laravel/framework/commit/8c08bed52712332c750138120e3dfd6851198917): Fix suggestion reason in composer.json - missing ' [@r3oath](https://github.com/r3oath) 
- [60b386f](https://github.com/laravel/framework/commit/60b386f302e1b74481e7c5125a5cc7448c10e3a8): Convert to array the attributes from makeHidden fu [@j3j5](https://github.com/j3j5) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-08-15}...5.1@{2016-08-22})
- [afd9c98](https://github.com/laravel/framework/commit/afd9c98dc66661b570e26b65b94d60f061a290db): allow the disable_asserts config value (#14864) [@jasonvarga](https://github.com/jasonvarga) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [develop](https://github.com/laravel/laravel/compare/develop@{2016-08-15}...develop@{2016-08-22})
- [cf0875a](https://github.com/laravel/laravel/commit/cf0875a655ad68bdf3204615264086ab462dd9c9): move middleware to route [@taylorotwell](https://github.com/taylorotwell) 
- [3435710](https://github.com/laravel/laravel/commit/3435710575ad1aa9a302cbd3ac7b7a93946bb8c0): Use implicit null instead of explicit [@adamwathan](https://github.com/adamwathan) 
- [792dcd4](https://github.com/laravel/laravel/commit/792dcd48c8ad9887f08db6ad9efd0890603ddd53): Compute hash only once and store in static variabl [@adamwathan](https://github.com/adamwathan) 
- [b041a03](https://github.com/laravel/laravel/commit/b041a0387808bb90ffa56308c70665e1c8d01efd): Use precomputed hash instead of bcrypt in ModelFac [@adamwathan](https://github.com/adamwathan) 
- [aed59d9](https://github.com/laravel/laravel/commit/aed59d9f7ae3d9584094afd12210f840af9e2804): remove brackets [@themsaid](https://github.com/themsaid) 
- [c0b9523](https://github.com/laravel/laravel/commit/c0b95238c9b11287c26808dfecf485a390de6256): Remove defalut auth:api middleware [@themsaid](https://github.com/themsaid) 
- [2689538](https://github.com/laravel/laravel/commit/268953862ff649ccf186e6740cd2e9af40b8906a): fix order [@taylorotwell](https://github.com/taylorotwell) 
- [8998cf5](https://github.com/laravel/laravel/commit/8998cf55337a62f3dbb15ef2f100c37161e09253): Add BROADCAST_DRIVER on .envHaving pusher keys, th [@socieboy](https://github.com/socieboy) 
- [ffd7ad9](https://github.com/laravel/laravel/commit/ffd7ad912e53bc42ec41cfb2710200c7ead2b9a8): Revert recent changes to env file. [@taylorotwell](https://github.com/taylorotwell) 
- [7571f2b](https://github.com/laravel/laravel/commit/7571f2b5b4ecca329cf508ef07dd113e6dbe53fc): Use module name instead of path [@adriaanzon](https://github.com/adriaanzon) 
- [c7a1c7d](https://github.com/laravel/laravel/commit/c7a1c7d773325c3d45fd41e3e009e3c811190d19): Ship a console routes file by default. 🌊 [@taylorotwell](https://github.com/taylorotwell) 
- [6f055a9](https://github.com/laravel/laravel/commit/6f055a9b473ddd164fff688b551c78d3334cfe32): Update server.php email address [@BrandonSurowiec](https://github.com/BrandonSurowiec) 
- [97fde5b](https://github.com/laravel/laravel/commit/97fde5bff9e4086629e58e10d782bbc55743e0d3): Update email address [@BrandonSurowiec](https://github.com/BrandonSurowiec) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-08-15}...master@{2016-08-22})
- [847c722](https://github.com/laravel/docs/commit/847c7220c134fda4a1f9ddf743b8929db2a45006): Arr class doesn't have contains method [Clemir Rondón] 
- [e551c7a](https://github.com/laravel/docs/commit/e551c7ad7025b269cc15f5a65a929551ec32f5df): Fixed spelling mistake [@yesdevnull](https://github.com/yesdevnull) 
- [90a5a5d](https://github.com/laravel/docs/commit/90a5a5dcdfaf51ebb7ae1e92d067e1429081666c): typo fix [@dabernathy89](https://github.com/dabernathy89) 
- [5adb215](https://github.com/laravel/docs/commit/5adb21563282621130da493301de8be5f03116ea): fix wording [@taylorotwell](https://github.com/taylorotwell) 
- [66786f6](https://github.com/laravel/docs/commit/66786f6fb758c12819c31cee768aef9789597d72): clarify [@taylorotwell](https://github.com/taylorotwell) 
- [7138fc3](https://github.com/laravel/docs/commit/7138fc3f3d822acc99209eb9cb6b23d5815e1efb): note on pruning [@taylorotwell](https://github.com/taylorotwell) 
- [80a3b70](https://github.com/laravel/docs/commit/80a3b708888e6f175fc38405e4a5690d3ca01765): fixed path for Relationfixed console error thrown: [@bhosie](https://github.com/bhosie) 
- [259d40a](https://github.com/laravel/docs/commit/259d40a8bd3182955d3041ecdd1a855f97d169c3): Remove hash character [@charlesyapp](https://github.com/charlesyapp) 
- [d00bf71](https://github.com/laravel/docs/commit/d00bf718d4f520a9ea439b8159ede8ac66cd3c63): Fix a link in notifications.md: Introduction [@charlesyapp](https://github.com/charlesyapp) 
- [5585e1e](https://github.com/laravel/docs/commit/5585e1e52cf0e3d3ee8661cdc8f6d2947fad6e66): add secret to docs [@taylorotwell](https://github.com/taylorotwell) 
- [4dcbaa9](https://github.com/laravel/docs/commit/4dcbaa93ac99267496f13a783cac25ae6f2f6e1b): link [@taylorotwell](https://github.com/taylorotwell) 
- [111f629](https://github.com/laravel/docs/commit/111f629b14f892bb61fbc9c9dafd14be13b1f737): link to relevant screencasts [@taylorotwell](https://github.com/taylorotwell) 
- [a06ecf3](https://github.com/laravel/docs/commit/a06ecf3dcd6451700780fdf2190472296f86f584): heading [@taylorotwell](https://github.com/taylorotwell) 
- [8a2d9dc](https://github.com/laravel/docs/commit/8a2d9dc33a90adf2f3c6e081dcb37e72eab8892d): change password [@taylorotwell](https://github.com/taylorotwell) 
- [d567ce3](https://github.com/laravel/docs/commit/d567ce3cc93ab16f40f1e894da4b67a958c2d49e): note on super scopes [@taylorotwell](https://github.com/taylorotwell) 
- [f281b25](https://github.com/laravel/docs/commit/f281b252f50bf2267aa1c04291eea50e10ed0c70): notes on password grant [@taylorotwell](https://github.com/taylorotwell) 
- [1eb0e87](https://github.com/laravel/docs/commit/1eb0e87089e0eb80f272a5684bc97e2455db67af): Fixed command example for worker timeout [@qmcree](https://github.com/qmcree) 
- [cdc57c7](https://github.com/laravel/docs/commit/cdc57c74cefa9e27849f0b1915c7c886521d2c8f): Fixed queue worker doc typo and added clarityFixed [@qmcree](https://github.com/qmcree) 
- [affbdbe](https://github.com/laravel/docs/commit/affbdbef3062672a444190cd86b06faf8170c311): rewrite wording [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-08-15}...5.2@{2016-08-22})
- [d4b3d84](https://github.com/laravel/docs/commit/d4b3d84c1aa2621c15c66b43152385f1bdb60234): fix typo [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-08-15}...master@{2016-08-22})
- [9c8a099](https://github.com/laravel/homestead/commit/9c8a099d81d5ec15a2a881c1352b1ca0fb7414f2): Deprecated method.File.exists? is a deprecated met [@futhr](https://github.com/futhr) 


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [develop](https://github.com/laravel/lumen/compare/develop@{2016-08-15}...develop@{2016-08-22})
- [1e77791](https://github.com/laravel/lumen/commit/1e77791eb03d70f48da341d39d2f73f13a51be64): Added minimum-stability and prefer-stable [@nmfzone](https://github.com/nmfzone) 


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-08-15}...master@{2016-08-22})
- [d781185](https://github.com/laravel/laravel.com/commit/d781185dc9b6753206472e64183515f9c4670bad): Fix for Uncaught AlgoliaSearchError [@pemedina](https://github.com/pemedina) 
- [785c4ee](https://github.com/laravel/laravel.com/commit/785c4ee494c4e92f7a576877a0fd5b6c5fd577eb): fix laravel/docs link [@DearMadMan](https://github.com/DearMadMan) 


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [master](https://github.com/laravel/cashier/compare/master@{2016-08-15}...master@{2016-08-22})
- [029bf05](https://github.com/laravel/cashier/commit/029bf054d7971ac851736c8c0c3cd08ae49ef79e): fix conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [b06c17d](https://github.com/laravel/cashier/commit/b06c17d541f33bed2e4315dda3baa9e16e95a739): update for laravel 5.3 [@taylorotwell](https://github.com/taylorotwell) 
- [80742b4](https://github.com/laravel/cashier/commit/80742b4618586db15a638a436dbc8f625c6abd4d): update branch alias [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/valet](https://github.com/laravel/valet)

### [master](https://github.com/laravel/valet/compare/master@{2016-08-15}...master@{2016-08-22})
- [86d0c6b](https://github.com/laravel/valet/commit/86d0c6b1a75a6fb80380d2ddaba71935680045d7): Increment version [@adamwathan](https://github.com/adamwathan) 
- [cf7911a](https://github.com/laravel/valet/commit/cf7911a0e54fc527b7c669779d97404412cb4f57): Properly replace VALET_HOME_PATH in secure Caddy f [@adamwathan](https://github.com/adamwathan) 


___

## [laravel/echo](https://github.com/laravel/echo)

### [master](https://github.com/laravel/echo/compare/master@{2016-08-15}...master@{2016-08-22})
- [a7c48fa](https://github.com/laravel/echo/commit/a7c48fa311f58060b9825c6c1082178b3efb13d3): move to base class [@taylorotwell](https://github.com/taylorotwell) 
- [d40faff](https://github.com/laravel/echo/commit/d40faff388a8113936c63c1e4a5290d953e8c04f): 0.1.3 [@taylorotwell](https://github.com/taylorotwell) 
- [11ad7ad](https://github.com/laravel/echo/commit/11ad7ad153e2dc4b51631d9599938404cf782cd8): just pass optinos [@taylorotwell](https://github.com/taylorotwell) 


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [You Are Who You Say You Are](http://laracasts.simplecast.fm/38)

### [Laravel News Podcast](https://laravel-news.com)
- [Laracon EU Special Edition]()


___

## [Laracasts](https://laracasts.com)
- [Closure-Based Commands](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/14)
- [How Do I Create Nested Comments](https://laracasts.com/series/how-do-i/episodes/9)
- [Dry Up Your Views](https://laracasts.com/series/php-for-beginners/episodes/17)
- [Laravel Passport](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/13)
- [Super Simple File Uploading](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/12)
- [Send Slack Notifications With Laravel in Minutes](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/11)
- [Help Me Understand When to Use Polymorphic Relations](https://laracasts.com/series/how-do-i/episodes/8)


___

## [Larajobs](https://larajobs.com)
- [Contract Position:  WebRTC Developer / VoIP](https://larajobs.com/job/585/contract-position-webrtc-developer-voip)
- [Remote Laravel devs wanted - (Frontend and Backend opportunities)](https://larajobs.com/job/584/remote-laravel-devs-wanted-frontend-and-backend-opportunities)
- [Senior Backend Developer](https://larajobs.com/job/583/senior-backend-developer)
- [Back End Developer](https://larajobs.com/job/582/back-end-developer)
- [Senior PHP Developer - Remote Position](https://larajobs.com/job/581/senior-php-developer-remote-position)
- [Software Engineer (LAMP/Laravel)](https://larajobs.com/job/580/software-engineer-lamplaravel)
- [Laravel Application Developer](https://larajobs.com/job/577/laravel-application-developer)
- [PHP Web Developer](https://larajobs.com/job/579/php-web-developer)
- [Senior PHP Developer](https://larajobs.com/job/578/senior-php-developer)
