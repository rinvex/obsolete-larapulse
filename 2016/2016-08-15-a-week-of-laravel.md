# A week of Laravel #18 (08-15 August 2016)

> **Updates:** "Updates: laravel/framework [master, 5.2, 5.1], laravel/laravel [develop], laravel/docs [master, 5.2, 5.1], laravel/lumen [develop], laravel/laravel.com [master], laravel/quickstart-basic [master], laravel/settler [master], laravel/socialite [2.0], laravel/elixir [master], laravel/valet [master], laravel/echo [master], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts, Larajobs"

> **Published:** August 15, 2016

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-08-08}...master@{2016-08-15})
- [a76f601](https://github.com/laravel/framework/commit/a76f60151470887c1258d6a1a3300b845e023381): Protect against empty paths in the view:clear comm [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [f67a06a](https://github.com/laravel/framework/commit/f67a06a7a918e94fbd3c9d6f93e66f2ebd58f790): Update author emailUpdate the author email address [@vinkla](https://github.com/vinkla) 
- [58736c8](https://github.com/laravel/framework/commit/58736c8d416dc95901f94a24b143d21089df374d): Fix export-ignore for phpunit.xmlExport phpunit.xm [@vinkla](https://github.com/vinkla) 
- [99b1f0d](https://github.com/laravel/framework/commit/99b1f0d2fe6a1f029850fecc6c0ece60695eda67): working on methods [@taylorotwell](https://github.com/taylorotwell) 
- [f3f0640](https://github.com/laravel/framework/commit/f3f064043c8e685953ee5f111bd213b5eb7dfa4a): [5.3] Add missing methods (#14800)* Add missing me [@morloderex](https://github.com/morloderex) 
- [a493384](https://github.com/laravel/framework/commit/a49338408eba4f6d339cab25d50ec04aeb582be8): Use KEYS only for redis keys and ARGV for other ar [@halaei](https://github.com/halaei) 
- [538dc80](https://github.com/laravel/framework/commit/538dc80510f595e16e0cb85b535ac19094ad786b): Remove import of a class which doesn't exist. (#14 [@eriktisme](https://github.com/eriktisme) 
- [a9947a1](https://github.com/laravel/framework/commit/a9947a115ff2b8b29b3c01a7e6e182afcbd0a97f): Make mapToAssoc return a collection (#14795) [@JosephSilber](https://github.com/JosephSilber) 
- [7864bef](https://github.com/laravel/framework/commit/7864beff9e6050ad95f1c06e36602d8abcd8ce34): Avoid call_user_func_array in __call functions (#1 [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [4e0d69d](https://github.com/laravel/framework/commit/4e0d69d9cc8959e069ccf6e71eef92663162a78a): fix cons [@taylorotwell](https://github.com/taylorotwell) 
- [73ee91b](https://github.com/laravel/framework/commit/73ee91b55ecc9f8cd027f983bb4b239cb4f2435d): [5.1] Fixed aggregate queries (#14793)* Fixed aggr [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [1c61fc6](https://github.com/laravel/framework/commit/1c61fc6c92bec52caa96d5d01405147de7ffcc4c): inline styles [@taylorotwell](https://github.com/taylorotwell) 
- [d0bc401](https://github.com/laravel/framework/commit/d0bc401b7384ae4b63adcfdaddbd415c4394e3d3): fix queue listen [@taylorotwell](https://github.com/taylorotwell) 
- [35e26f4](https://github.com/laravel/framework/commit/35e26f4cb79aee0bf04ff3e042e0e17b87a86b2e): Adjusting notification template for non-style brow [@kuczmaja](https://github.com/kuczmaja) 
- [91ecede](https://github.com/laravel/framework/commit/91ecedef32c7d4ae66dd5580f312040ad2ceb20a): Add support for checking if an array has multiple  [@ntzm](https://github.com/ntzm) 
- [1de0225](https://github.com/laravel/framework/commit/1de02251ce2c954fb595bea7f5b4f4050cefcb8f): mapToAssoc [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-08-08}...5.2@{2016-08-15})
- [a76f601](https://github.com/laravel/framework/commit/a76f60151470887c1258d6a1a3300b845e023381): Protect against empty paths in the view:clear comm [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [73ee91b](https://github.com/laravel/framework/commit/73ee91b55ecc9f8cd027f983bb4b239cb4f2435d): [5.1] Fixed aggregate queries (#14793)* Fixed aggr [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [8a79d40](https://github.com/laravel/framework/commit/8a79d40a9188129f99549e92f288cf4dcea96bf9): method name change [@taylorotwell](https://github.com/taylorotwell) 
- [df2761f](https://github.com/laravel/framework/commit/df2761f0f3e24e884a9db0271044cff41238b564): [5.2] firstOrCreate will not create new db rows wh [@miscbits](https://github.com/miscbits) 
- [dbd0b5f](https://github.com/laravel/framework/commit/dbd0b5f59cae689f5534a65498121f2e93d884c0): formatting [@taylorotwell](https://github.com/taylorotwell) 
- [092bea0](https://github.com/laravel/framework/commit/092bea01c14f537d3097b4f2df3ddc339b11c29c): code cleaning [@taylorotwell](https://github.com/taylorotwell) 
- [49c6a83](https://github.com/laravel/framework/commit/49c6a83bdc817195ab611b9a9ae5f5ab498e274d): Be super careful with types [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [3b2ae21](https://github.com/laravel/framework/commit/3b2ae21aadcc2b87be714f7445afc5f959b36a38): Fixed the aggregate method [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [a1615a3](https://github.com/laravel/framework/commit/a1615a3995c367afa326f502567842e0a3c9bb8d): Added release notes for v5.2.43 (#14750) [@tillkruss](https://github.com/tillkruss) 
- [fc27c02](https://github.com/laravel/framework/commit/fc27c025d735af56c2c205207bf6fea6a61a288b): Fix ns in docblock [@TheGIBSON](https://github.com/TheGIBSON) 
- [c914a40](https://github.com/laravel/framework/commit/c914a407b7ba006bbc21731cc764952fb002bd17): Improved method description (#14736) [@OskarD](https://github.com/OskarD) 
- [5490b8f](https://github.com/laravel/framework/commit/5490b8f00564bb60839002f86828e27edd1e5610): inc version [@taylorotwell](https://github.com/taylorotwell) 
- [03dfc48](https://github.com/laravel/framework/commit/03dfc48097db4f379b882dd7e0c75e723782a250): increment version [@taylorotwell](https://github.com/taylorotwell) 
- [915cb84](https://github.com/laravel/framework/commit/915cb843981ad434b10709425d968bf2db37cb1a): force integer on inc / dec [@taylorotwell](https://github.com/taylorotwell) 
- [fdb69b6](https://github.com/laravel/framework/commit/fdb69b6557eac9061a5800e835f0929a3f97825e): Fix Request file() return type hint (#14725)`allFi [@cnanney](https://github.com/cnanney) 
- [dad8ca6](https://github.com/laravel/framework/commit/dad8ca6430ead5fcfe1292226232a59c66aefd9e): Support column aliases in chunkByIdReferences #144 [@mzur](https://github.com/mzur) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-08-08}...5.1@{2016-08-15})
- [a76f601](https://github.com/laravel/framework/commit/a76f60151470887c1258d6a1a3300b845e023381): Protect against empty paths in the view:clear comm [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [73ee91b](https://github.com/laravel/framework/commit/73ee91b55ecc9f8cd027f983bb4b239cb4f2435d): [5.1] Fixed aggregate queries (#14793)* Fixed aggr [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [092bea0](https://github.com/laravel/framework/commit/092bea01c14f537d3097b4f2df3ddc339b11c29c): code cleaning [@taylorotwell](https://github.com/taylorotwell) 
- [49c6a83](https://github.com/laravel/framework/commit/49c6a83bdc817195ab611b9a9ae5f5ab498e274d): Be super careful with types [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [3b2ae21](https://github.com/laravel/framework/commit/3b2ae21aadcc2b87be714f7445afc5f959b36a38): Fixed the aggregate method [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [03dfc48](https://github.com/laravel/framework/commit/03dfc48097db4f379b882dd7e0c75e723782a250): increment version [@taylorotwell](https://github.com/taylorotwell) 
- [915cb84](https://github.com/laravel/framework/commit/915cb843981ad434b10709425d968bf2db37cb1a): force integer on inc / dec [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [develop](https://github.com/laravel/laravel/compare/develop@{2016-08-08}...develop@{2016-08-15})
- [f111704](https://github.com/laravel/laravel/commit/f111704314c0204a7ac5999a7a8cc724920ef65e): Fix order [@tillkruss](https://github.com/tillkruss) 
- [3415bea](https://github.com/laravel/laravel/commit/3415beaebb087fdec4b1db669be91cdc4ff7a880): GitIgnore PHPStorm's config directory fromIf you o [@balping](https://github.com/balping) 
- [4ee5172](https://github.com/laravel/laravel/commit/4ee51720a355351f13b678663643cb35c958b576): Use const instead of var in Vue instanceReference  [@donnes](https://github.com/donnes) 
- [6d21a74](https://github.com/laravel/laravel/commit/6d21a74c5da48b36cde147993fe9d0e8154a9457): Use const instead of var in require [@diogoazevedos](https://github.com/diogoazevedos) 
- [afb3e1c](https://github.com/laravel/laravel/commit/afb3e1c93dc889cf99cb9d6dd4030cfc8b269577): Use arrow functions instead of functions [@diogoazevedos](https://github.com/diogoazevedos) 
- [788a648](https://github.com/laravel/laravel/commit/788a648165bd254a403193a84327db427079a7f4): match order to website [@taylorotwell](https://github.com/taylorotwell) 
- [43c2d8e](https://github.com/laravel/laravel/commit/43c2d8ec92547e4ecb83a60338e5f696dc861646): tweak variable [@taylorotwell](https://github.com/taylorotwell) 
- [655dbad](https://github.com/laravel/laravel/commit/655dbadd1eceab8ff17e084b14943db59ddec40a): tweaking default setup [@taylorotwell](https://github.com/taylorotwell) 
- [8a9f89d](https://github.com/laravel/laravel/commit/8a9f89d3cfcaad12cacb74e9cb1a1eef9636811d): fix wording [@taylorotwell](https://github.com/taylorotwell) 
- [530c818](https://github.com/laravel/laravel/commit/530c8187f556d1b39c3a33a403f077a030ac9905): Use double quotes; Remove un-used fonts [@tillkruss](https://github.com/tillkruss) 
- [7e41c61](https://github.com/laravel/laravel/commit/7e41c61835f1f24eb8b6d9f2fd71ba6ba1515af3): rename method [@taylorotwell](https://github.com/taylorotwell) 
- [7b1ab65](https://github.com/laravel/laravel/commit/7b1ab65623185df9d8b04718e64d743359e2dfd6): Delete app/Http/Requests directory [@JosephSilber](https://github.com/JosephSilber) 
- [24d0102](https://github.com/laravel/laravel/commit/24d0102fcccb5a30448d68e75ecccbff13bc3ace): recompile [@taylorotwell](https://github.com/taylorotwell) 
- [54d3f32](https://github.com/laravel/laravel/commit/54d3f325ad8a62f94cda307e437f6f0ac0ea9669): change header [@taylorotwell](https://github.com/taylorotwell) 
- [9c02782](https://github.com/laravel/laravel/commit/9c0278274bcaa7370a9810c4e7d6f791c1d6146d): simplify csrf token retrieval. remove package. [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-08-08}...master@{2016-08-15})
- [40e001b](https://github.com/laravel/docs/commit/40e001bb6d4bd5313c2f37cef782b7fe3f115e20): better wording [@taylorotwell](https://github.com/taylorotwell) 
- [2c24209](https://github.com/laravel/docs/commit/2c24209426d587855937b004dbadfd638ce48754): currency wording [@taylorotwell](https://github.com/taylorotwell) 
- [f327660](https://github.com/laravel/docs/commit/f327660ac356244c4fe62db527d1b906a968a36d): clean up wording [@taylorotwell](https://github.com/taylorotwell) 
- [165fa73](https://github.com/laravel/docs/commit/165fa734f27a554253708accf7ad076d9540a86e): spelling fixes [@garethnic](https://github.com/garethnic) 
- [fe8cd8f](https://github.com/laravel/docs/commit/fe8cd8f69765a9a588cec37bf66ce74ac3f19b40): Missing Semicolon [@poxin13](https://github.com/poxin13) 
- [f327a4c](https://github.com/laravel/docs/commit/f327a4c9f50f70343c18b36d3285d477c3c03ac3): install docs [@taylorotwell](https://github.com/taylorotwell) 
- [7f78058](https://github.com/laravel/docs/commit/7f78058c3140e2a42a4b727c253c20f2b666a3fe): csrf clarification [@taylorotwell](https://github.com/taylorotwell) 
- [1f690b8](https://github.com/laravel/docs/commit/1f690b804c5add1e1d8c6c3dcd8a89a895a04db7): work on list [@taylorotwell](https://github.com/taylorotwell) 
- [3bf4622](https://github.com/laravel/docs/commit/3bf46226dae821c2b5c00dd3d792d50b81438374): Add Cashier currency configuration [@josebailo](https://github.com/josebailo) 
- [68dadb9](https://github.com/laravel/docs/commit/68dadb9d72fd67239877942d92ce2d199a0209dc): Fixing minor typo."where" vs "were". [@danielbaylis](https://github.com/danielbaylis) 
- [39761f3](https://github.com/laravel/docs/commit/39761f35fb3a399bb197e67d1508613a19d8d1d8): csrf notes [@taylorotwell](https://github.com/taylorotwell) 
- [3f07927](https://github.com/laravel/docs/commit/3f0792789de1c8e0d7672f05ae804ea8d493d402): work on docs [@taylorotwell](https://github.com/taylorotwell) 
- [5b67f43](https://github.com/laravel/docs/commit/5b67f43f32fa890ba54607593e943ae3bc78f1fd): tweak sidebar [@taylorotwell](https://github.com/taylorotwell) 
- [b7d0ed8](https://github.com/laravel/docs/commit/b7d0ed8a44196876f63876c4e73c6a6b81df1619): Typo on Calling Policy Methods With Class NamesYou [@akoury](https://github.com/akoury) 
- [4c0c190](https://github.com/laravel/docs/commit/4c0c19081b2f03754e8c051b55e709cb983051c8): move csrf [@taylorotwell](https://github.com/taylorotwell) 
- [d753e4c](https://github.com/laravel/docs/commit/d753e4c10a9397d50954b3cee98a173f331cd2e2): tweak a few sections [@taylorotwell](https://github.com/taylorotwell) 
- [d247dc9](https://github.com/laravel/docs/commit/d247dc922ee15ae44ddace54117c4f657b7314de): section for dev environments [@taylorotwell](https://github.com/taylorotwell) 
- [5d5cddc](https://github.com/laravel/docs/commit/5d5cddc715de522d82272c6ec4befeb4816fe283): note on collection method [@taylorotwell](https://github.com/taylorotwell) 
- [1c4a447](https://github.com/laravel/docs/commit/1c4a4470097b7de840f3809db6103f9ae6473ac5): additional notes on broadcasting [@taylorotwell](https://github.com/taylorotwell) 
- [c728a55](https://github.com/laravel/docs/commit/c728a55f7fbc01cfec4445c1c4e2e177a8748000): wording [@taylorotwell](https://github.com/taylorotwell) 
- [5e1b427](https://github.com/laravel/docs/commit/5e1b427f5cf19df0d2ac6d7d68ac286d8abee350): wording [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-08-08}...5.2@{2016-08-15})
- [dc6cc8f](https://github.com/laravel/docs/commit/dc6cc8f90bd8e09d9b31e71737d6b8f1ba0cb967): Typo [@fduchateau](https://github.com/fduchateau) 
- [9f9dd74](https://github.com/laravel/docs/commit/9f9dd747ca3cc792036f70b66deedcf2e1b29adc): Add in spiel about how you can access exception va [@amonger](https://github.com/amonger) 


### [5.1](https://github.com/laravel/docs/compare/5.1@{2016-08-08}...5.1@{2016-08-15})
- [d5dea25](https://github.com/laravel/docs/commit/d5dea2562262416e5aaafabcf1577a63df7d6b90): Typo [@fduchateau](https://github.com/fduchateau) 


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [develop](https://github.com/laravel/lumen/compare/develop@{2016-08-08}...develop@{2016-08-15})
- [9de9c45](https://github.com/laravel/lumen/commit/9de9c45480c4870d84ed552acfeecc4fe6d6e526): Removed APP_KEY placeholder [@tillkruss](https://github.com/tillkruss) 


___

## [laravel/laravel.com](https://github.com/laravel/laravel.com)

### [master](https://github.com/laravel/laravel.com/compare/master@{2016-08-08}...master@{2016-08-15})
- [04addc9](https://github.com/laravel/laravel.com/commit/04addc93148e6f315d94c0ad6b615c93443b3eae): wording [@taylorotwell](https://github.com/taylorotwell) 
- [8d65ad1](https://github.com/laravel/laravel.com/commit/8d65ad1b4ecd74c1838c36a907f0896a630e9170): change link order [@taylorotwell](https://github.com/taylorotwell) 
- [221647d](https://github.com/laravel/laravel.com/commit/221647d267a3611ea245888706f80f93718ca11d): change title [@taylorotwell](https://github.com/taylorotwell) 
- [bebea21](https://github.com/laravel/laravel.com/commit/bebea211e3815a3aff2647fbc98bef74cb2127ee): condense navbar [@taylorotwell](https://github.com/taylorotwell) 
- [8430123](https://github.com/laravel/laravel.com/commit/8430123b57b41aa557bb162afa0b1460719e7fea): Update build. Use local composer for Sami [@JosephSilber](https://github.com/JosephSilber) 
- [0340178](https://github.com/laravel/laravel.com/commit/034017829966d0084f721a260aa711089d9ead61): Upgrade to Laravel 5.3 [@JosephSilber](https://github.com/JosephSilber) 
- [4aa3d66](https://github.com/laravel/laravel.com/commit/4aa3d6646bc6e8416e313a4ca6506d45c1818379): PSR2 [@JosephSilber](https://github.com/JosephSilber) 
- [fa71249](https://github.com/laravel/laravel.com/commit/fa71249ba3fbd357758866ae3a5617775b79c550): Improved relevance + Refactoring [@maxiloc](https://github.com/maxiloc) 
- [1d79052](https://github.com/laravel/laravel.com/commit/1d79052a4abdcbd4ca1b51c44cc63ebc3b698554): add images [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/quickstart-basic](https://github.com/laravel/quickstart-basic)

### [master](https://github.com/laravel/quickstart-basic/compare/master@{2016-08-08}...master@{2016-08-15})
- [85ddf3b](https://github.com/laravel/quickstart-basic/commit/85ddf3b2c1a87cc8c4fc8791c1ac80b7ac4392a9): Update readme.md [@taylorotwell](https://github.com/taylorotwell) 
- [fc0f7ac](https://github.com/laravel/quickstart-basic/commit/fc0f7ace95d5b5fd37da88e493ec25296ff77858): Update readme.md [@taylorotwell](https://github.com/taylorotwell) 
- [cf09dfb](https://github.com/laravel/quickstart-basic/commit/cf09dfbdf80a17d67a62a9cc0e664b017258643e): restore key, keeping it simple [@EDDYMENS](https://github.com/EDDYMENS) 
- [bb0fce2](https://github.com/laravel/quickstart-basic/commit/bb0fce21b3362869806adc703b68674c5f4e92d0): remove default app key [@EDDYMENS](https://github.com/EDDYMENS) 
- [b49f520](https://github.com/laravel/quickstart-basic/commit/b49f5202a510d84d5d0854bc05c6392cbcc82e27): add more info to readme [@EDDYMENS](https://github.com/EDDYMENS) 


___

## [laravel/settler](https://github.com/laravel/settler)

### [master](https://github.com/laravel/settler/compare/master@{2016-08-08}...master@{2016-08-15})
- [fd68dc5](https://github.com/laravel/settler/commit/fd68dc5d1bb3494d49dd875fc2af7916a0887fdd): 16.04 [@taylorotwell](https://github.com/taylorotwell) 


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-08-08}...2.0@{2016-08-15})
- [5602da7](https://github.com/laravel/socialite/commit/5602da7860dcf6d7897a0cc81ed1acfd193b2633): fixes repeat typo [@legshooter](https://github.com/legshooter) 
- [73c2333](https://github.com/laravel/socialite/commit/73c2333acfd5a51b206a279c4324cac082cdcbff): readme wording [@taylorotwell](https://github.com/taylorotwell) 
- [392e7d0](https://github.com/laravel/socialite/commit/392e7d0f415e2c94f36bf24fcc7ffcf1d8327a73): Add a link to Socialite Providers [@misenhower](https://github.com/misenhower) 


___

## [laravel/elixir](https://github.com/laravel/elixir)

### [master](https://github.com/laravel/elixir/compare/master@{2016-08-08}...master@{2016-08-15})
- [918f35d](https://github.com/laravel/elixir/commit/918f35d896e4f293f6eac2afb925513b7104635a): Pre-release v6.0.0-10 [@JeffreyWay](https://github.com/JeffreyWay) 
- [968f93b](https://github.com/laravel/elixir/commit/968f93b5b59db9a1af78510fe59bdb889b8a9086): Move reporters to own folder [@JeffreyWay](https://github.com/JeffreyWay) 
- [2257608](https://github.com/laravel/elixir/commit/225760832ecee565575646518a41b8c7f44386ba): Make minimal reporter more consistentThe only diff [@JeffreyWay](https://github.com/JeffreyWay) 


___

## [laravel/valet](https://github.com/laravel/valet)

### [master](https://github.com/laravel/valet/compare/master@{2016-08-08}...master@{2016-08-15})
- [15b2ecb](https://github.com/laravel/valet/commit/15b2ecb876c7327b223e0d83c38eba8fa413be46): Update version string [@adamwathan](https://github.com/adamwathan) 
- [b551cbe](https://github.com/laravel/valet/commit/b551cbe7a1d2479c4770a31092b5991a21bf04df): Clean up log commands a bit [@adamwathan](https://github.com/adamwathan) 
- [7458807](https://github.com/laravel/valet/commit/74588070348f273133980e32c1290947890f0b78): Reword unsecure description [@adamwathan](https://github.com/adamwathan) 
- [b175fe2](https://github.com/laravel/valet/commit/b175fe2890c5ce9e1d80bd259b128acafc0120f1): Update version to match release [@jconroy](https://github.com/jconroy) 
- [e88731b](https://github.com/laravel/valet/commit/e88731b17c8937984a9d0ac24295da44127d76fb): Add missing descriptions [@drbyte](https://github.com/drbyte) 
- [7e34426](https://github.com/laravel/valet/commit/7e34426e4a403c6ada008f5600282f801b0fe40c): Allow path parameter for valet park and forgetFixe [@drbyte](https://github.com/drbyte) 


___

## [laravel/echo](https://github.com/laravel/echo)

### [master](https://github.com/laravel/echo/compare/master@{2016-08-08}...master@{2016-08-15})
- [e2dd147](https://github.com/laravel/echo/commit/e2dd14720f7aac749e38e0932df07be2427f0a20): Fixed some type hinting issues and removed a metho [@tlaverdure](https://github.com/tlaverdure) 
- [03bc62e](https://github.com/laravel/echo/commit/03bc62e210d11c4e1ff8764b3c44bc48986db381): Check Vue exists correctly [@mattmcdonald-uk](https://github.com/mattmcdonald-uk) 
- [c97a280](https://github.com/laravel/echo/commit/c97a2800b6cfae3934e08bbc9ef36bb4dcc1326f): tweak socket io presence channel [@taylorotwell](https://github.com/taylorotwell) 
- [e198c18](https://github.com/laravel/echo/commit/e198c18844ab35a1f579100f3b2bada9c3ecba73): 0.1.1 [@taylorotwell](https://github.com/taylorotwell) 
- [1b4a9e6](https://github.com/laravel/echo/commit/1b4a9e697247eea9d57b8c43a569562ff9ee7753): tweak option name [@taylorotwell](https://github.com/taylorotwell) 
- [6fa0b4a](https://github.com/laravel/echo/commit/6fa0b4a62a6ae57a38223c80ff5429ae35d0effa): 0.1.0 [@taylorotwell](https://github.com/taylorotwell) 
- [bdc7d47](https://github.com/laravel/echo/commit/bdc7d4792a4eef1ea1376b15683255427ea19aa7): a few refactorings [@taylorotwell](https://github.com/taylorotwell) 
- [1dfa7d2](https://github.com/laravel/echo/commit/1dfa7d26d20861b08592ba52fa7cc7e54441e9e1): 0.0.28 [@taylorotwell](https://github.com/taylorotwell) 
- [ea3964e](https://github.com/laravel/echo/commit/ea3964e0085ab449e2a5006a2a4ad87beface8f1): load pusher if not loaded [@taylorotwell](https://github.com/taylorotwell) 
- [475ee16](https://github.com/laravel/echo/commit/475ee169cdce0aa781b84c9ee9a00311b5dabbf5): 0.0.27 [@taylorotwell](https://github.com/taylorotwell) 
- [9542680](https://github.com/laravel/echo/commit/9542680180171e7542fb6143d88b8fad4554537c): automatically send X-Socket-ID if using Vue resour [@taylorotwell](https://github.com/taylorotwell) 
- [e85099a](https://github.com/laravel/echo/commit/e85099a6735ce19c6f06b1ee47bacbb7729c21e1): 0.0.26 [@taylorotwell](https://github.com/taylorotwell) 
- [108b0aa](https://github.com/laravel/echo/commit/108b0aa83f1b9ba9b2bcc26098999e1f1e83d3bb): fix bug [@taylorotwell](https://github.com/taylorotwell) 
- [9ccec54](https://github.com/laravel/echo/commit/9ccec54e591ee985ade5bc0839df087bd4d114b7): 0.0.25 [@taylorotwell](https://github.com/taylorotwell) 
- [25a9f3f](https://github.com/laravel/echo/commit/25a9f3f159e56ab7ca8f20abd68ae5a0702af15a): Code cleanup and fixed some type errors. [@tlaverdure](https://github.com/tlaverdure) 
- [7a856a1](https://github.com/laravel/echo/commit/7a856a114392ee89bc6954c06685c8e10d70e4b3): 0.0.24 [@taylorotwell](https://github.com/taylorotwell) 
- [900ced3](https://github.com/laravel/echo/commit/900ced35874d6f427ad414b6b887284d8a4648b3): add abstract method to channel [@taylorotwell](https://github.com/taylorotwell) 
- [753fa2d](https://github.com/laravel/echo/commit/753fa2d1b1191312b519fe39dc586353e8d2cbfa): 0.0.23 [@taylorotwell](https://github.com/taylorotwell) 
- [df4ae43](https://github.com/laravel/echo/commit/df4ae436baab95d5ae19a0e1d3c65fba3c44b758): working on refactor [@taylorotwell](https://github.com/taylorotwell) 
- [567662a](https://github.com/laravel/echo/commit/567662a8bf0380c9a5808bdf1af0b49927e402dd): more refactoring [@taylorotwell](https://github.com/taylorotwell) 
- [340b752](https://github.com/laravel/echo/commit/340b75252f0851c607bc863b1d2edb5c3e9a918e): initial work [@taylorotwell](https://github.com/taylorotwell) 
- [22778da](https://github.com/laravel/echo/commit/22778da6808e8706c1f069362a63a0506f50419e): small tweaks [@taylorotwell](https://github.com/taylorotwell) 


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [Throw it All Out](http://laracasts.simplecast.fm/37)

### [Laravel News Podcast](https://laravel-news.com)
- [The Laracon US Recap Episode](http://podcast.laravel-news.com/23)


___

## [Laracasts](https://laracasts.com)
- [Most Recent or Most Popular](https://laracasts.com/series/hands-on-community-contributions/episodes/13)
- [Make a Router](https://laracasts.com/series/php-for-beginners/episodes/16)
- [Notifications: Database](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/10)
- [Notifications: Email](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/9)
- [Toggle Pivot Table Records](https://laracasts.com/series/whats-new-in-laravel-5-3/episodes/8)
- [How Do I Fetch the Most Recent Reply's Username](https://laracasts.com/series/how-do-i/episodes/7)


___

## [Larajobs](https://larajobs.com)
- [Junior Programmer – Laravel Specialist](https://larajobs.com/job/576/junior-programmer-laravel-specialist)
- [PHP Senior Developer](https://larajobs.com/job/575/php-senior-developer)
- [Programmer](https://larajobs.com/job/574/programmer)
- [Solutions Architect (PHP)](https://larajobs.com/job/573/solutions-architect-php)
- [Backend Web Developer (MVC PHP / MySQL)](https://larajobs.com/job/572/backend-web-developer-mvc-php-mysql)
- [Web Developer](https://larajobs.com/job/571/web-developer)
- [Web Application Developer](https://larajobs.com/job/570/web-application-developer)
- [Senior Developer - 100% Remote Working](https://larajobs.com/job/569/senior-developer-100-remote-working)
- [Senior Product Development Lead - 100% Remote Work](https://larajobs.com/job/568/senior-product-development-lead-100-remote-work)
