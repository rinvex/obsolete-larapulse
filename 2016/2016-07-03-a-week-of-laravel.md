# A week of Laravel #12 (26 June-03 July 2016)

> **Updates:** "Updates: laravel/framework [master, 5.2, 5.1], laravel/laravel [master, develop], laravel/docs [master, 5.2], laravel/homestead [master], laravel/cashier [6.0], laravel/elixir [master], laravel/valet [master], Podcasts: The Laravel Podcast, The Laracasts Snippet, Laravel News Podcast, Laracasts, Larajobs"

> **Published:** July 03, 2016

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-06-26}...master@{2016-07-03})
- [0b4f798](https://github.com/laravel/framework/commit/0b4f7985745702fc2e303765a056dd352a7b539c): add pipe function (#13899) [@freekmurze](https://github.com/freekmurze) 
- [cffcd34](https://github.com/laravel/framework/commit/cffcd347901617b19e8eca05be55cda280e0d262): refactoring changes [@taylorotwell](https://github.com/taylorotwell) 
- [015db87](https://github.com/laravel/framework/commit/015db872e2db22ac11919e08d04722c880a2cdc6): format long line [@taylorotwell](https://github.com/taylorotwell) 
- [d54500e](https://github.com/laravel/framework/commit/d54500eb013d23ada07b563420e55e3712ef88ae): Fix MySQL multiple-table DELETE error (#14179)http [@staudenmeir](https://github.com/staudenmeir) 
- [41fd377](https://github.com/laravel/framework/commit/41fd3779c1964a455db2e387baa231912e0c0bef): [5.2] Pagination optimize (#14188)* Add test for E [@mnabialek](https://github.com/mnabialek) 
- [37665f1](https://github.com/laravel/framework/commit/37665f1f4dacbb8ed4f680516c41f88c083cfea6): fix spacing [@taylorotwell](https://github.com/taylorotwell) 
- [5aa3a58](https://github.com/laravel/framework/commit/5aa3a58180ff1dab36347d04ee282418c4b40166): code cleaning [@taylorotwell](https://github.com/taylorotwell) 
- [e2860de](https://github.com/laravel/framework/commit/e2860de36532f24aacbe6f129bf56d78ce703f2a): New methods: SessionStore::increment and SessionSt [@dereckson](https://github.com/dereckson) 
- [917dfbc](https://github.com/laravel/framework/commit/917dfbcf3863c4805e395057fb268d895567fbce): [5.2] add moveDirectory method (#14198)* add moveD [@jordonbrill](https://github.com/jordonbrill) 
- [e6dd517](https://github.com/laravel/framework/commit/e6dd5178062d23e9c26ceb8d2a5ad469faecacf2): Improve code documentation: increment → decremen [@dereckson](https://github.com/dereckson) 
- [8bd23ef](https://github.com/laravel/framework/commit/8bd23efee2d72414be9c68d1a77b40293bcef925): added getKey method [@taylorotwell](https://github.com/taylorotwell) 
- [741f29d](https://github.com/laravel/framework/commit/741f29d4693156192d7dee6f30670e989bdf8a9d): Make getConnectionName Overridable (#14194)Use fun [@bretto36](https://github.com/bretto36) 
- [ee7b8cf](https://github.com/laravel/framework/commit/ee7b8cffb046467d220439b940f983f5dde89d6c): Fix morphTo eager loading [@acasar](https://github.com/acasar) 
- [68a4993](https://github.com/laravel/framework/commit/68a4993372525cb154201ed02592e0086dc70877): Allow easy addition of custom drivers. [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-06-26}...5.2@{2016-07-03})
- [0b4f798](https://github.com/laravel/framework/commit/0b4f7985745702fc2e303765a056dd352a7b539c): add pipe function (#13899) [@freekmurze](https://github.com/freekmurze) 
- [cffcd34](https://github.com/laravel/framework/commit/cffcd347901617b19e8eca05be55cda280e0d262): refactoring changes [@taylorotwell](https://github.com/taylorotwell) 
- [d54500e](https://github.com/laravel/framework/commit/d54500eb013d23ada07b563420e55e3712ef88ae): Fix MySQL multiple-table DELETE error (#14179)http [@staudenmeir](https://github.com/staudenmeir) 
- [41fd377](https://github.com/laravel/framework/commit/41fd3779c1964a455db2e387baa231912e0c0bef): [5.2] Pagination optimize (#14188)* Add test for E [@mnabialek](https://github.com/mnabialek) 
- [37665f1](https://github.com/laravel/framework/commit/37665f1f4dacbb8ed4f680516c41f88c083cfea6): fix spacing [@taylorotwell](https://github.com/taylorotwell) 
- [5aa3a58](https://github.com/laravel/framework/commit/5aa3a58180ff1dab36347d04ee282418c4b40166): code cleaning [@taylorotwell](https://github.com/taylorotwell) 
- [e2860de](https://github.com/laravel/framework/commit/e2860de36532f24aacbe6f129bf56d78ce703f2a): New methods: SessionStore::increment and SessionSt [@dereckson](https://github.com/dereckson) 
- [917dfbc](https://github.com/laravel/framework/commit/917dfbcf3863c4805e395057fb268d895567fbce): [5.2] add moveDirectory method (#14198)* add moveD [@jordonbrill](https://github.com/jordonbrill) 
- [e6dd517](https://github.com/laravel/framework/commit/e6dd5178062d23e9c26ceb8d2a5ad469faecacf2): Improve code documentation: increment → decremen [@dereckson](https://github.com/dereckson) 
- [741f29d](https://github.com/laravel/framework/commit/741f29d4693156192d7dee6f30670e989bdf8a9d): Make getConnectionName Overridable (#14194)Use fun [@bretto36](https://github.com/bretto36) 
- [ee7b8cf](https://github.com/laravel/framework/commit/ee7b8cffb046467d220439b940f983f5dde89d6c): Fix morphTo eager loading [@acasar](https://github.com/acasar) 
- [bf987ea](https://github.com/laravel/framework/commit/bf987ea5306555633a9d5e761ddf6adf069117fa): add additional return types to auth() helper docbl [@ockle](https://github.com/ockle) 
- [a8df2de](https://github.com/laravel/framework/commit/a8df2de122a7940892d5ee8ff41375a86c0f0855): refactor [@taylorotwell](https://github.com/taylorotwell) 
- [a0cd0ae](https://github.com/laravel/framework/commit/a0cd0aea9a475f76baf968ef2f53aeb71fcda4c0): code refactor [@taylorotwell](https://github.com/taylorotwell) 
- [5ffdf9a](https://github.com/laravel/framework/commit/5ffdf9a471278badbdd23b71d78960b0a9f2492e): modify testExtendInstancesArePreserved test (#1415 [@zhuanxuhit](https://github.com/zhuanxuhit) 
- [4ca961b](https://github.com/laravel/framework/commit/4ca961b2196f0a214d4288436572a28002ce9b3b): change order [@taylorotwell](https://github.com/taylorotwell) 
- [504e56e](https://github.com/laravel/framework/commit/504e56eb2bb867f0c0b54f0cfcf66c024f9326e2): Allowing passing along transmission options to Spa [@djtarazona](https://github.com/djtarazona) 
- [bb4021b](https://github.com/laravel/framework/commit/bb4021bc5bfe20fed434ee6bdde629b34cc7d15f): comment [@taylorotwell](https://github.com/taylorotwell) 
- [3c22cbb](https://github.com/laravel/framework/commit/3c22cbbf6d31812135235cd29b3621d694b92726): [5.2] Typos...i think :confused: [@JayBizzle](https://github.com/JayBizzle) 
- [c12e8bf](https://github.com/laravel/framework/commit/c12e8bfff9958e2c6c5f71737ec3d8600a40e26c): Remove optional parameters $true and $false [@DuckThom](https://github.com/DuckThom) 
- [9a925e4](https://github.com/laravel/framework/commit/9a925e45876e40b6fd4cfcdbf3e1abc49c1d627b): [5.2] Properly support PDO::FETCH_CLASS in cursor( [@vlakoff](https://github.com/vlakoff) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-06-26}...5.1@{2016-07-03})
- [d54500e](https://github.com/laravel/framework/commit/d54500eb013d23ada07b563420e55e3712ef88ae): Fix MySQL multiple-table DELETE error (#14179)http [@staudenmeir](https://github.com/staudenmeir) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-06-26}...master@{2016-07-03})
- [cd03204](https://github.com/laravel/laravel/commit/cd032040441787c827aa07c428ae753281b685df): Add language line for file validation rule. [@byCedric](https://github.com/byCedric) 
- [d3aff65](https://github.com/laravel/laravel/commit/d3aff652bdebe006442a575df647d59baddee903): expire jobs after 90 seconds [@halaei](https://github.com/halaei) 


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-06-26}...develop@{2016-07-03})
- [34eb11f](https://github.com/laravel/laravel/commit/34eb11faee2e396a935f8e777e16c24f9931fdc7): [5.3] Password broker would always use notificatio [@crynobone](https://github.com/crynobone) 
- [9575714](https://github.com/laravel/laravel/commit/9575714700fd1c1796f7376a4bdc65d3683409ff): Add notifiable trait to default user. [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-06-26}...master@{2016-07-03})
- [3420e54](https://github.com/laravel/docs/commit/3420e54a251992a5c522b835421bebc523aa5b7e): added period [@taylorotwell](https://github.com/taylorotwell) 
- [dd9a952](https://github.com/laravel/docs/commit/dd9a9526479d799b6b5ecda7bf92dd1f0841e4c6): Add file rule [@mnabialek](https://github.com/mnabialek) 
- [7ecd59a](https://github.com/laravel/docs/commit/7ecd59a869110f010ca22e1ecd89ed86497ca962): tweak wording [@taylorotwell](https://github.com/taylorotwell) 
- [ef66cb3](https://github.com/laravel/docs/commit/ef66cb38678597f16ef9391482608f5dff398f8e): DOCS for migrate:refresh with step option [@srmklive](https://github.com/srmklive) 
- [5da9ade](https://github.com/laravel/docs/commit/5da9ade1e8b7ef37a19b08007071fa452ab3ccbe): slight wording changes [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-06-26}...5.2@{2016-07-03})
- [d9323d0](https://github.com/laravel/docs/commit/d9323d04b21ade66bc6f9c8f90a7acdf3aa8e51f): validation: remove mention of filter_varThe curren [@mfn](https://github.com/mfn) 
- [d98a7df](https://github.com/laravel/docs/commit/d98a7df274228c456c26a68b40d62f157f0bd598): Update homestead.md [@christophrumpel](https://github.com/christophrumpel) 
- [6b52d39](https://github.com/laravel/docs/commit/6b52d39f0ffaa2aad7fdf140264d4c92bb5b20f5): StudlyCase instead of CamelCaseAs there is already [@gauravmak](https://github.com/gauravmak) 
- [3420e54](https://github.com/laravel/docs/commit/3420e54a251992a5c522b835421bebc523aa5b7e): added period [@taylorotwell](https://github.com/taylorotwell) 
- [dd9a952](https://github.com/laravel/docs/commit/dd9a9526479d799b6b5ecda7bf92dd1f0841e4c6): Add file rule [@mnabialek](https://github.com/mnabialek) 
- [5da9ade](https://github.com/laravel/docs/commit/5da9ade1e8b7ef37a19b08007071fa452ab3ccbe): slight wording changes [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/homestead](https://github.com/laravel/homestead)

### [master](https://github.com/laravel/homestead/compare/master@{2016-06-26}...master@{2016-07-03})
- [57afaa9](https://github.com/laravel/homestead/commit/57afaa99701f71ed42c8acf52bc5d17c5c6ecac1): Use MariaDb Xenial PPA [Gustave] 
- [4dd0e0c](https://github.com/laravel/homestead/commit/4dd0e0c72e6d582fd7e6390fa8d39b9966d6fdeb): fix line break [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-06-26}...6.0@{2016-07-03})
- [5e586be](https://github.com/laravel/cashier/commit/5e586be137ae65923ce623e53423e7369dceb84c): update travis [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-06-26}...master@{2016-07-03})
- [3cf1ae4](https://github.com/laravel/elixir/commit/3cf1ae46a6c4a20f441f88849a69e2be36f07ec2): Pre-release v6.0.0-8 [@JeffreyWay](https://github.com/JeffreyWay) 
- [830a7d0](https://github.com/laravel/elixir/commit/830a7d096a718cb006cfa80630d5866aadb7ad5b): Move Browsersync to installable extension [@JeffreyWay](https://github.com/JeffreyWay) 
- [de1be37](https://github.com/laravel/elixir/commit/de1be37a4cfe3dc053e2fa09e55ed70d131fe686): Remove undocumented elixir.json option [@JeffreyWay](https://github.com/JeffreyWay) 
- [e261a04](https://github.com/laravel/elixir/commit/e261a04e9db82c17bd93f31d304a41f77fb49f88): Exit for deprecated recipe call [@JeffreyWay](https://github.com/JeffreyWay) 
- [28092fc](https://github.com/laravel/elixir/commit/28092fc3284bd95dfd812efeb3606aa2003151d5): Lazy load versioning dependencies [@JeffreyWay](https://github.com/JeffreyWay) 
- [c746f3c](https://github.com/laravel/elixir/commit/c746f3cc5b69620c8ef1cc4192ddd28cc21d2247): Move Webpack to its own extension [@JeffreyWay](https://github.com/JeffreyWay) 
- [4239af4](https://github.com/laravel/elixir/commit/4239af494191e05473586a5669503f9656c4c1e6): For Gulp errors, exit with a failure [@JeffreyWay](https://github.com/JeffreyWay) 
- [81e44a2](https://github.com/laravel/elixir/commit/81e44a2e4595763ac2c8efaf75e34b7d39ef05d4): Exit immediately [@JeffreyWay](https://github.com/JeffreyWay) 
- [7067ad8](https://github.com/laravel/elixir/commit/7067ad8a3559d76f591fb16c19bfb7843500927b): Call task dependencies method if defined [@JeffreyWay](https://github.com/JeffreyWay) 
- [83a4b03](https://github.com/laravel/elixir/commit/83a4b039b7c920d72b279972abc8afbe7cb6e63f): Remove unnecessary step [@JeffreyWay](https://github.com/JeffreyWay) 
- [6c90f27](https://github.com/laravel/elixir/commit/6c90f27c89e99fe7ee50d2a277de41d579fedd56): Allow for passing options to initSourceMaps [@JeffreyWay](https://github.com/JeffreyWay) 
- [983c983](https://github.com/laravel/elixir/commit/983c983b8d9e2bb5f8ce7e261aa47f7885b6b590): Load local and official external dependencies [@JeffreyWay](https://github.com/JeffreyWay) 
- [1b3d392](https://github.com/laravel/elixir/commit/1b3d392056155e2443c1a81105bdb180d906cdc1): Use faster source map option [@JeffreyWay](https://github.com/JeffreyWay) 
- [4876668](https://github.com/laravel/elixir/commit/487666852a8f3d0141192148556db418bb7b761e): v6.0.0-6 [@JeffreyWay](https://github.com/JeffreyWay) 
- [f87df52](https://github.com/laravel/elixir/commit/f87df5271a43956a711f9629548b840f4d44bb1c): Return mix.scripts() to old behavior. - ImportantF [@JeffreyWay](https://github.com/JeffreyWay) 
- [79a4d2a](https://github.com/laravel/elixir/commit/79a4d2a9b3c9ce472ded1414b0b7765dd01ce0ec): Remove babel from config [@JeffreyWay](https://github.com/JeffreyWay) 
- [b05c91d](https://github.com/laravel/elixir/commit/b05c91df0dd87557ea6f0ec4cc36f216d40da98e): Don't dump file watchers [@JeffreyWay](https://github.com/JeffreyWay) 
- [521be4d](https://github.com/laravel/elixir/commit/521be4d9186c3a4c4600d5041b1ecdb903e7f84e): Pre-release 6.0.0-5 [@JeffreyWay](https://github.com/JeffreyWay) 
- [ff82b10](https://github.com/laravel/elixir/commit/ff82b1036ae48f40e10e67e2cfa8789e5931e476): Allow for configuring Webpack babel presets [@JeffreyWay](https://github.com/JeffreyWay) 
- [c9be574](https://github.com/laravel/elixir/commit/c9be574899ef829ce32ebbc7725b28dc89194f3f): Allow for copying to destination directories with  [@JeffreyWay](https://github.com/JeffreyWay) 
- [b1785c8](https://github.com/laravel/elixir/commit/b1785c8a1b4589670ed4803bb6cd3f8d6f4a4f1e): Add option muted [@ricardogobbosouza](https://github.com/ricardogobbosouza) 
- [de37dfe](https://github.com/laravel/elixir/commit/de37dfef0a1132c8f3e6c0d010827ce8e01889a2): Fix `scriptsIn` issue (options not defined error) [@teriu](https://github.com/teriu) 
- [19eccf4](https://github.com/laravel/elixir/commit/19eccf4b8c5163406c60ea6f1fc6392818544ab2): Add option muted [@ricardogobbosouza](https://github.com/ricardogobbosouza) 
- [9a84046](https://github.com/laravel/elixir/commit/9a84046bcbf1e1af0474963e0cfb9f3e3ca8f740): Copy src directories with dots in them - closes #5 [@JeffreyWay](https://github.com/JeffreyWay) 
- [a327fdd](https://github.com/laravel/elixir/commit/a327fddf28bfe6399fb118263e879385bb35817a): No need to check task length [@ricardogobbosouza](https://github.com/ricardogobbosouza) 


___

## [laravel/valet](https://github.com/laravel/valet)

### [master](https://github.com/laravel/valet/compare/master@{2016-06-26}...master@{2016-07-03})
- [68ff17a](https://github.com/laravel/valet/commit/68ff17aa595f6983434302151c98eec4e63b94d5): Added valet support for Symfony < 3.0 (#87)* Added [@xyNNN](https://github.com/xyNNN) 
- [d2f7d57](https://github.com/laravel/valet/commit/d2f7d57fec64187171f2a7da2efc5de3b3e35b54): fix for the empty $name issue (#94)fix for the emp [@vitr](https://github.com/vitr) 


___

## Podcasts

### [The Laravel Podcast](http://laravel.com)
- [Episode 46: Laracon & Books Jeffrey Hasn't Read](http://www.laravelpodcast.com/episodes/41169-episode-46-laracon-books-jeffrey-hasn-t-read)

### [The Laracasts Snippet](http://laracasts.audio)
- [Two Hours, Two Times](http://laracasts.simplecast.fm/31)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 20: With special guest Adam Wathan](http://podcast.laravel-news.com/20)


___

## [Laracasts](https://laracasts.com)
- [How Do I Distribute an NPM Package Written With ES2015](https://laracasts.com/series/how-do-i/episodes/2)
- [Step 6: Understanding Arrays](https://laracasts.com/series/php-for-beginners/episodes/6)
- [Step 5: Separate PHP Logic From Presentation](https://laracasts.com/series/php-for-beginners/episodes/5)
- [Step 4: PHP and HTML](https://laracasts.com/series/php-for-beginners/episodes/4)
- [Step 3: Variables](https://laracasts.com/series/php-for-beginners/episodes/3)
- [Step 2: Install a Proper Code Editor](https://laracasts.com/series/php-for-beginners/episodes/2)
- [Step 1: Get PHP Installed](https://laracasts.com/series/php-for-beginners/episodes/1)
- [How Do I Restrict Access With Nginx](https://laracasts.com/series/how-do-i/episodes/1)
- [VarDumper](https://laracasts.com/series/discover-symfony-components/episodes/3)
- [VideoJS Events and AJAX Requests](https://laracasts.com/series/how-to-use-html5-video-and-videojs/episodes/5)


___

## [Larajobs](https://larajobs.com)
- [Web Developer](https://larajobs.com/job/537/web-developer)
- [Senior Front End Web Application Engineer](https://larajobs.com/job/536/senior-front-end-web-application-engineer)
- [Senior PHP Engineer ](https://larajobs.com/job/535/senior-php-engineer)
- [PHP/Web Developer](https://larajobs.com/job/534/phpweb-developer)
- [PHP/Laravel developer full-time on site in Wilmington, NC](https://larajobs.com/job/533/phplaravel-developer-full-time-on-site-in-wilmington-nc)
- [Junior Software Engineer](https://larajobs.com/job/532/junior-software-engineer)
- [Info Systems/Business Analyst -Web Developer](https://larajobs.com/job/531/info-systemsbusiness-analyst-web-developer)
- [Full Stack Software Engineer](https://larajobs.com/job/530/full-stack-software-engineer)
