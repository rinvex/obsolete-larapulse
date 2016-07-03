---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (01-08 May 2016)
post::title: A week of Laravel (01-08 May 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/laravel [develop], laravel/docs [master], laravel/docs [5.2], laravel/lumen [master], laravel/socialite [2.0], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: May 08, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-05-01}...master@{2016-05-08})
- [4fd04b7](https://github.com/laravel/framework/commit/4fd04b7fa632647a65e84a7d2dc8bc3394f9095e): cleanup [@taylorotwell](https://github.com/taylorotwell)
- [ecf0cbb](https://github.com/laravel/framework/commit/ecf0cbb14c2760ea00a88d13ca206842446e0223): Applied fixes from StyleCI [@taylorotwell](https://github.com/taylorotwell)
- [e74aa9d](https://github.com/laravel/framework/commit/e74aa9d5dc635e3f8a1581ae104193ab4a2fb68b): slight formatting [@taylorotwell](https://github.com/taylorotwell)
- [f35019f](https://github.com/laravel/framework/commit/f35019fe4504344a6b74437d0da7e5e72f5863f2): Fix sqlserver grammar (#13458)Added square bracket [@fhb12345](https://github.com/fhb12345)
- [b880147](https://github.com/laravel/framework/commit/b88014713b2581d6bb443f4a0e8837662267772c): Make SessionGuard::onceUsingId() return user insta [@vlakoff](https://github.com/vlakoff)
- [395ba7c](https://github.com/laravel/framework/commit/395ba7c0c3964c9c590964934da041948355bd39): [5.3] Bind CacheManager to custom driver closure.  [@hskrasek](https://github.com/hskrasek)
- [594e1f5](https://github.com/laravel/framework/commit/594e1f5e94b1ea710357d96d209d94b7fb56cc32): Fix migration tests on windows (#13438) [@vlakoff](https://github.com/vlakoff)
- [d1bbe61](https://github.com/laravel/framework/commit/d1bbe61eb632cddf0999c994f9117192eb346edd): spacing [@taylorotwell](https://github.com/taylorotwell)
- [4219218](https://github.com/laravel/framework/commit/421921874d96aac2e8c3d85e73f30b5888d52e41): fix test for php 32bit (#13440) [@themsaid](https://github.com/themsaid)
- [358ae65](https://github.com/laravel/framework/commit/358ae65b9fb0fb9acf33b00647ce9c8cf91a4435): Ensures MigrationCreator::create receives $create  [@vlakoff](https://github.com/vlakoff)
- [52f2381](https://github.com/laravel/framework/commit/52f2381020d70256afdd35143161b4090a45fe54): add generated columns support to mysql schema gram [@themsaid](https://github.com/themsaid)
- [91efb6d](https://github.com/laravel/framework/commit/91efb6daef37345994c15a6832d9e554f3e4f0a9): fix bug [@taylorotwell](https://github.com/taylorotwell)
- [9b5dfdf](https://github.com/laravel/framework/commit/9b5dfdf3be34e1c729edabae2c9e02d95fe2ab7e): fix config call [@taylorotwell](https://github.com/taylorotwell)
- [7c02b2c](https://github.com/laravel/framework/commit/7c02b2c3299c650ed3d1cda95db185e5cc5ba1e8): spacing and fix default arg [@taylorotwell](https://github.com/taylorotwell)
- [d85fc44](https://github.com/laravel/framework/commit/d85fc44b13a4633e91ae4dedda30c0ae2a68de50): fix confs [@taylorotwell](https://github.com/taylorotwell)
- [a6ddacb](https://github.com/laravel/framework/commit/a6ddacb568c1d4fa2d4b6e9f739830692c055973): Add test for SessionGuard::onceUsingId() (#13408) [@vlakoff](https://github.com/vlakoff)
- [00ad6ed](https://github.com/laravel/framework/commit/00ad6edf4562e54f6b4c24f088e5fac86e990087): [5.2] Added reply_to field for SparkPost API reque [@byron-smith](https://github.com/byron-smith)
- [6c9edd8](https://github.com/laravel/framework/commit/6c9edd86098fbc23cc775a2b145135031eb980be): [5.1] Fixing scheduler switch user with withoutOve [@pulkitjalan](https://github.com/pulkitjalan)
- [a084356](https://github.com/laravel/framework/commit/a08435630ef2b027862099cfaee336f78d9706f5): Order imports by length [@darksaboteur](https://github.com/darksaboteur)
- [555a091](https://github.com/laravel/framework/commit/555a0911d4d823992f12ec4946e47a8325936340): Import Exception [@darksaboteur](https://github.com/darksaboteur)
- [6dc5c7c](https://github.com/laravel/framework/commit/6dc5c7c9edb9a9aa9ea031b80b4b0c832eea78bb): Fix style issues with previous commit [@darksaboteur](https://github.com/darksaboteur)
- [415ddd9](https://github.com/laravel/framework/commit/415ddd96e97e62c85af5c41df673aee157fbe91a): Work around lack of lastInsertId() for ODBC with P [@darksaboteur](https://github.com/darksaboteur)


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-05-01}...5.2@{2016-05-08})
- [4fd04b7](https://github.com/laravel/framework/commit/4fd04b7fa632647a65e84a7d2dc8bc3394f9095e): cleanup [@taylorotwell](https://github.com/taylorotwell)
- [ecf0cbb](https://github.com/laravel/framework/commit/ecf0cbb14c2760ea00a88d13ca206842446e0223): Applied fixes from StyleCI [@taylorotwell](https://github.com/taylorotwell)
- [e74aa9d](https://github.com/laravel/framework/commit/e74aa9d5dc635e3f8a1581ae104193ab4a2fb68b): slight formatting [@taylorotwell](https://github.com/taylorotwell)
- [f35019f](https://github.com/laravel/framework/commit/f35019fe4504344a6b74437d0da7e5e72f5863f2): Fix sqlserver grammar (#13458)Added square bracket [@fhb12345](https://github.com/fhb12345)
- [594e1f5](https://github.com/laravel/framework/commit/594e1f5e94b1ea710357d96d209d94b7fb56cc32): Fix migration tests on windows (#13438) [@vlakoff](https://github.com/vlakoff)
- [d1bbe61](https://github.com/laravel/framework/commit/d1bbe61eb632cddf0999c994f9117192eb346edd): spacing [@taylorotwell](https://github.com/taylorotwell)
- [4219218](https://github.com/laravel/framework/commit/421921874d96aac2e8c3d85e73f30b5888d52e41): fix test for php 32bit (#13440) [@themsaid](https://github.com/themsaid)
- [358ae65](https://github.com/laravel/framework/commit/358ae65b9fb0fb9acf33b00647ce9c8cf91a4435): Ensures MigrationCreator::create receives $create  [@vlakoff](https://github.com/vlakoff)
- [52f2381](https://github.com/laravel/framework/commit/52f2381020d70256afdd35143161b4090a45fe54): add generated columns support to mysql schema gram [@themsaid](https://github.com/themsaid)
- [a6ddacb](https://github.com/laravel/framework/commit/a6ddacb568c1d4fa2d4b6e9f739830692c055973): Add test for SessionGuard::onceUsingId() (#13408) [@vlakoff](https://github.com/vlakoff)
- [00ad6ed](https://github.com/laravel/framework/commit/00ad6edf4562e54f6b4c24f088e5fac86e990087): [5.2] Added reply_to field for SparkPost API reque [@byron-smith](https://github.com/byron-smith)
- [6c9edd8](https://github.com/laravel/framework/commit/6c9edd86098fbc23cc775a2b145135031eb980be): [5.1] Fixing scheduler switch user with withoutOve [@pulkitjalan](https://github.com/pulkitjalan)
- [a084356](https://github.com/laravel/framework/commit/a08435630ef2b027862099cfaee336f78d9706f5): Order imports by length [@darksaboteur](https://github.com/darksaboteur)
- [555a091](https://github.com/laravel/framework/commit/555a0911d4d823992f12ec4946e47a8325936340): Import Exception [@darksaboteur](https://github.com/darksaboteur)
- [6dc5c7c](https://github.com/laravel/framework/commit/6dc5c7c9edb9a9aa9ea031b80b4b0c832eea78bb): Fix style issues with previous commit [@darksaboteur](https://github.com/darksaboteur)
- [415ddd9](https://github.com/laravel/framework/commit/415ddd96e97e62c85af5c41df673aee157fbe91a): Work around lack of lastInsertId() for ODBC with P [@darksaboteur](https://github.com/darksaboteur)
- [d9cc1bd](https://github.com/laravel/framework/commit/d9cc1bdc6c624f81222ca8b467374409ebcd737b): Fix scope nesting (#13413) [@acasar](https://github.com/acasar)
- [61f1afb](https://github.com/laravel/framework/commit/61f1afb0dc7a7e8353fc7d5f7da2c29292fdf068): add test [@taylorotwell](https://github.com/taylorotwell)
- [f356419](https://github.com/laravel/framework/commit/f356419fa6f6b6fbc3322ca587b0bc1e075ba8d2): fromRawAttributes method on pivot [@taylorotwell](https://github.com/taylorotwell)
- [83a4b3f](https://github.com/laravel/framework/commit/83a4b3ffa85097995f0036494141dc4e208178ac): [5.2] Improvements for SessionGuard methods loginU [@vlakoff](https://github.com/vlakoff)
- [9650f4f](https://github.com/laravel/framework/commit/9650f4f9dbb1eb0b6e24a8102912d0a069abd812): Fix using onlyTrashed and withTrashed with whereHa [@acasar](https://github.com/acasar)
- [621412f](https://github.com/laravel/framework/commit/621412f4199966ee7b0d3e7735815eaf0c5a0d8f): fix grouping [@taylorotwell](https://github.com/taylorotwell)


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-05-01}...5.1@{2016-05-08})
- [6c9edd8](https://github.com/laravel/framework/commit/6c9edd86098fbc23cc775a2b145135031eb980be): [5.1] Fixing scheduler switch user with withoutOve [@pulkitjalan](https://github.com/pulkitjalan)


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-05-01}...master@{2016-05-08})
- [382857a](https://github.com/laravel/laravel/commit/382857a8a7b83aba932290908ad09a10dc0c1d4a): Use Bootstrap 3.3Unless there is a reason why not? [@tillkruss](https://github.com/tillkruss)


### [develop](https://github.com/laravel/laravel/compare/develop@{2016-05-01}...develop@{2016-05-08})
- [a97b9e0](https://github.com/laravel/laravel/commit/a97b9e0c7c24aadf84cb620bb0d26ed37bc0120f): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [d68d4dc](https://github.com/laravel/laravel/commit/d68d4dc9cd6013fb3eaa37f8b5726b9ea80c5abe): adds configuration for session cache store [Tom Castleman]
- [382857a](https://github.com/laravel/laravel/commit/382857a8a7b83aba932290908ad09a10dc0c1d4a): Use Bootstrap 3.3Unless there is a reason why not? [@tillkruss](https://github.com/tillkruss)


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-05-01}...master@{2016-05-08})
- [83eacd4](https://github.com/laravel/docs/commit/83eacd4d7750f062d6d0b6f914f3b01956dfc894): fix list [@taylorotwell](https://github.com/taylorotwell)
- [15d97d0](https://github.com/laravel/docs/commit/15d97d0d829ac2d01958ac34a3747e92405113a8): add drivers [@taylorotwell](https://github.com/taylorotwell)
- [0a87a91](https://github.com/laravel/docs/commit/0a87a91f838a767f029f28e1cf865e7768fa515b): update support list [@taylorotwell](https://github.com/taylorotwell)
- [0817f36](https://github.com/laravel/docs/commit/0817f365042fd73f9f9e222ec78daf242058d7f4): Correct bin directory for Composer [@RobGordijn](https://github.com/RobGordijn)
- [8b76c7c](https://github.com/laravel/docs/commit/8b76c7c917173547facc7b61c931f02546c705a4): fix [@taylorotwell](https://github.com/taylorotwell)
- [ceefe20](https://github.com/laravel/docs/commit/ceefe200d3eec33b96b07170dbf134457b2937f9): fix docs [@taylorotwell](https://github.com/taylorotwell)
- [2519bc6](https://github.com/laravel/docs/commit/2519bc608c4112a8dc4a1ced45c7f3e3e594572b): valet docs [@taylorotwell](https://github.com/taylorotwell)


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-05-01}...5.2@{2016-05-08})
- [4bcff1e](https://github.com/laravel/docs/commit/4bcff1e60f0fe8833f99efbdf0e9026e44d9be81): Fixed "Introduction" anchor name [@tillkruss](https://github.com/tillkruss)
- [062c986](https://github.com/laravel/docs/commit/062c986506012118b71d9261e98b6bfcb78185c2): remove comma [@taylorotwell](https://github.com/taylorotwell)
- [48fe60e](https://github.com/laravel/docs/commit/48fe60e89f00fed57e2c4cb00abae98c1dab6257): Update homestead.md [@jaewun](https://github.com/jaewun)
- [83eacd4](https://github.com/laravel/docs/commit/83eacd4d7750f062d6d0b6f914f3b01956dfc894): fix list [@taylorotwell](https://github.com/taylorotwell)
- [15d97d0](https://github.com/laravel/docs/commit/15d97d0d829ac2d01958ac34a3747e92405113a8): add drivers [@taylorotwell](https://github.com/taylorotwell)
- [0a87a91](https://github.com/laravel/docs/commit/0a87a91f838a767f029f28e1cf865e7768fa515b): update support list [@taylorotwell](https://github.com/taylorotwell)
- [0817f36](https://github.com/laravel/docs/commit/0817f365042fd73f9f9e222ec78daf242058d7f4): Correct bin directory for Composer [@RobGordijn](https://github.com/RobGordijn)
- [8b76c7c](https://github.com/laravel/docs/commit/8b76c7c917173547facc7b61c931f02546c705a4): fix [@taylorotwell](https://github.com/taylorotwell)
- [ceefe20](https://github.com/laravel/docs/commit/ceefe200d3eec33b96b07170dbf134457b2937f9): fix docs [@taylorotwell](https://github.com/taylorotwell)
- [2519bc6](https://github.com/laravel/docs/commit/2519bc608c4112a8dc4a1ced45c7f3e3e594572b): valet docs [@taylorotwell](https://github.com/taylorotwell)


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [master](https://github.com/laravel/lumen/compare/master@{2016-05-01}...master@{2016-05-08})
- [bf65376](https://github.com/laravel/lumen/commit/bf653766330a992b28c6c49b2a81ff6dd92ebd24): Add ignore file for file cache directory [@ntzm](https://github.com/ntzm)


___

## [laravel/socialite](https://github.com/laravel/socialite)

### [2.0](https://github.com/laravel/socialite/compare/2.0@{2016-05-01}...2.0@{2016-05-08})
- [88748a2](https://github.com/laravel/socialite/commit/88748a26fa9acf0a309a1b540fc4a916729c82c6): fix comment [@taylorotwell](https://github.com/taylorotwell)
- [8082fd6](https://github.com/laravel/socialite/commit/8082fd61f692e93db3c385a0b24fcb2b2aa3ab17): Use --prefer-dist [@lucasmichot](https://github.com/lucasmichot)
- [32640fa](https://github.com/laravel/socialite/commit/32640fa2c81b22c45a2eb8583e316ac00d75f598): Also tests with PHP >= 5.4 [@lucasmichot](https://github.com/lucasmichot)
- [a2eb7a1](https://github.com/laravel/socialite/commit/a2eb7a1386db9a152a7d9e2287498d5f461157ea): Declaire the user propserty [@lucasmichot](https://github.com/lucasmichot)
- [a5bd63f](https://github.com/laravel/socialite/commit/a5bd63fdfda573d8eadc40b9fefae55d5d6e4bcb): Do not export some files [@lucasmichot](https://github.com/lucasmichot)
- [b9b23c0](https://github.com/laravel/socialite/commit/b9b23c0635be9b2ea032259c42e731031d1300e2): Add an .editorconfig file [@lucasmichot](https://github.com/lucasmichot)
- [b4e3bce](https://github.com/laravel/socialite/commit/b4e3bceb335bf08c3d4ae6dbee7a475bcb228a9c): Some doccblocks style fixes [@lucasmichot](https://github.com/lucasmichot)


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [The Alien](http://laracasts.simplecast.fm/23)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 16: Laravel Valet with Taylor Otwell and Adam Wathan](http://podcast.laravel-news.com/16)
- [LN 15: Misc News and an interview with Mike Bronner about his early experiences with Laravel Spark](http://podcast.laravel-news.com/15)


___

## [Laracasts](https://laracasts.com)
- [Consider Normalizing](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/10)
- [Consider Strategizing](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/9)
- [Template Strings](https://laracasts.com/series/es6-cliffsnotes/episodes/7)
- [Rest and Spread](https://laracasts.com/series/es6-cliffsnotes/episodes/6)
- [Default Parameters](https://laracasts.com/series/es6-cliffsnotes/episodes/5)
