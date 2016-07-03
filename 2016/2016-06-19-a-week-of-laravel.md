---
view::extends: _includes.blog_post_base
view::yields: post_body
pageTitle: - A week of Laravel (12-19 June 2016)
post::title: A week of Laravel (12-19 June 2016)
post::brief: "Updates: laravel/framework [master], laravel/framework [5.2], laravel/framework [5.1], laravel/laravel [master], laravel/docs [master], laravel/docs [5.2], laravel/lumen-framework [master], laravel/lumen [develop], laravel/cashier [6.0], Podcasts: The Laracasts Snippet, Laravel News Podcast, Laracasts"
post::date: June 19, 2016
---

## [laravel/framework](https://github.com/laravel/framework)

### [master](https://github.com/laravel/framework/compare/master@{2016-06-12}...master@{2016-06-19})
- [658d1df](https://github.com/laravel/framework/commit/658d1dfb2af301f6c8b02dfd3b6b9dec6e5bee12): change comment wording [@taylorotwell](https://github.com/taylorotwell) 
- [e97e151](https://github.com/laravel/framework/commit/e97e151412378faf9ff76f08c4304208ed03c58d): [5.2] Add getValidationData method to FormRequest  [@n7olkachev](https://github.com/n7olkachev) 
- [f9ffa61](https://github.com/laravel/framework/commit/f9ffa6129ffbdac9b4497fe7660d0cc9f188477a): [5.1] Deal with cases when the manifest is empty ( [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [ee99882](https://github.com/laravel/framework/commit/ee99882aa3f438e1360deebe4b042f31402b37b3): Adding support for StreamOptions (#13925) [@marvinschroeder](https://github.com/marvinschroeder) 
- [58facd5](https://github.com/laravel/framework/commit/58facd5883e51fc9194ce8172204eb89e70d0db6): working on code [@taylorotwell](https://github.com/taylorotwell) 
- [acc0c96](https://github.com/laravel/framework/commit/acc0c963414c73c264029283cd143218cef63c35): Confirm Ajax request is not Pjax (#14024) [@dwightwatson](https://github.com/dwightwatson) 
- [c042ea7](https://github.com/laravel/framework/commit/c042ea77682633a378ae4ba521027a62979b294f): comment [@taylorotwell](https://github.com/taylorotwell) 
- [c1a29fb](https://github.com/laravel/framework/commit/c1a29fb2204b4104a64464b77f195cb5acee3655): [5.3] Simply delete blade comments (#14029)* Simpl [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [1d52300](https://github.com/laravel/framework/commit/1d52300213e2affabfc85ffef91fa989fb03207f): Add without() method to remove specified eager loa [@JayBizzle](https://github.com/JayBizzle) 
- [01c9e08](https://github.com/laravel/framework/commit/01c9e0811961f2439101bebcf05d1a6da27b9696): fix conflictss [@taylorotwell](https://github.com/taylorotwell) 
- [76d53d6](https://github.com/laravel/framework/commit/76d53d642c36be13b003c5b7d329c364e0a755bc): Move Mockery::close at end of tearDown() (#14019)  [@wicochandra](https://github.com/wicochandra) 
- [d4afdd2](https://github.com/laravel/framework/commit/d4afdd2bbc6bf8692e3b33c0090e88c720bb0d27): [5.1] BeanstalkdJob bury function delete job unexp [@yewjs](https://github.com/yewjs) 
- [7eb0a24](https://github.com/laravel/framework/commit/7eb0a249e6f19d2466227f7ad711e09822394bc8): Fix fullUrlWithQuery inconsistent slash behaviour  [@srmklive](https://github.com/srmklive) 
- [635e911](https://github.com/laravel/framework/commit/635e9117d3e6dea3022d1b375b79b9be21f8818c): Use the getIncrementing method instead of incremen [@kblais](https://github.com/kblais) 
- [49c076e](https://github.com/laravel/framework/commit/49c076ec63026e54fb8f2e85af2fe129f3b44d01): [5.3] Allow value-retrieving callbacks to be passe [@deframe](https://github.com/deframe) 
- [13e84e8](https://github.com/laravel/framework/commit/13e84e8fdb47175901634dab94d0ec392969638f): formatting [@taylorotwell](https://github.com/taylorotwell) 


### [5.2](https://github.com/laravel/framework/compare/5.2@{2016-06-12}...5.2@{2016-06-19})
- [71cd321](https://github.com/laravel/framework/commit/71cd32137b98a1bd64caf552734fb9d83cce93ec): Added missing slash [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [a32f8da](https://github.com/laravel/framework/commit/a32f8dadf2b36b3ee7549e0166d14cd465e89896): code formatting [@taylorotwell](https://github.com/taylorotwell) 
- [0934096](https://github.com/laravel/framework/commit/093409654608daa7b28d7c30933bda6f92935014): remove unnecessary else (#14036) [@greydnls](https://github.com/greydnls) 
- [e368a30](https://github.com/laravel/framework/commit/e368a301b7d0f7178bf28e06d906785669391835): Fix test class name [@themsaid](https://github.com/themsaid) 
- [5c4595a](https://github.com/laravel/framework/commit/5c4595a6727ab9f7b1a8993978a11cdf9de7aacc): change method to protected [@greydnls](https://github.com/greydnls) 
- [6177b9f](https://github.com/laravel/framework/commit/6177b9f5c5c9a1b370410272592f096e157e11af): styling [@greydnls](https://github.com/greydnls) 
- [ea17d24](https://github.com/laravel/framework/commit/ea17d24d5e7387dcc369e2cf910d16c22ea6e53a): styling [@greydnls](https://github.com/greydnls) 
- [f77e1d7](https://github.com/laravel/framework/commit/f77e1d72668d40831128fab55b44811759471411): fix whitespace [@greydnls](https://github.com/greydnls) 
- [c57765d](https://github.com/laravel/framework/commit/c57765d206c68ef76465f54dd3fe0414f08b0e34): ensure encrypter exists [@greydnls](https://github.com/greydnls) 
- [dc36082](https://github.com/laravel/framework/commit/dc3608241f4762b6c3e570ebc1212ff4727ddbbe): Added release notes for v5.2.39 [@tillkruss](https://github.com/tillkruss) 
- [c2a7705](https://github.com/laravel/framework/commit/c2a77050269b4e03bd9a735a9f24e573a7598b8a): fixed legacy handler and conflicts [@taylorotwell](https://github.com/taylorotwell) 
- [555269e](https://github.com/laravel/framework/commit/555269ee07cfe4e966ad16b394c89fa0b586d8b0): versoin [@taylorotwell](https://github.com/taylorotwell) 
- [53c0440](https://github.com/laravel/framework/commit/53c04406baa5f63bbb41127f40afee0a0facadd1): no need to delete [@taylorotwell](https://github.com/taylorotwell) 
- [658d1df](https://github.com/laravel/framework/commit/658d1dfb2af301f6c8b02dfd3b6b9dec6e5bee12): change comment wording [@taylorotwell](https://github.com/taylorotwell) 
- [e97e151](https://github.com/laravel/framework/commit/e97e151412378faf9ff76f08c4304208ed03c58d): [5.2] Add getValidationData method to FormRequest  [@n7olkachev](https://github.com/n7olkachev) 
- [f9ffa61](https://github.com/laravel/framework/commit/f9ffa6129ffbdac9b4497fe7660d0cc9f188477a): [5.1] Deal with cases when the manifest is empty ( [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [ee99882](https://github.com/laravel/framework/commit/ee99882aa3f438e1360deebe4b042f31402b37b3): Adding support for StreamOptions (#13925) [@marvinschroeder](https://github.com/marvinschroeder) 
- [58facd5](https://github.com/laravel/framework/commit/58facd5883e51fc9194ce8172204eb89e70d0db6): working on code [@taylorotwell](https://github.com/taylorotwell) 
- [acc0c96](https://github.com/laravel/framework/commit/acc0c963414c73c264029283cd143218cef63c35): Confirm Ajax request is not Pjax (#14024) [@dwightwatson](https://github.com/dwightwatson) 
- [c042ea7](https://github.com/laravel/framework/commit/c042ea77682633a378ae4ba521027a62979b294f): comment [@taylorotwell](https://github.com/taylorotwell) 
- [1d52300](https://github.com/laravel/framework/commit/1d52300213e2affabfc85ffef91fa989fb03207f): Add without() method to remove specified eager loa [@JayBizzle](https://github.com/JayBizzle) 
- [01c9e08](https://github.com/laravel/framework/commit/01c9e0811961f2439101bebcf05d1a6da27b9696): fix conflictss [@taylorotwell](https://github.com/taylorotwell) 


### [5.1](https://github.com/laravel/framework/compare/5.1@{2016-06-12}...5.1@{2016-06-19})
- [555269e](https://github.com/laravel/framework/commit/555269ee07cfe4e966ad16b394c89fa0b586d8b0): versoin [@taylorotwell](https://github.com/taylorotwell) 
- [53c0440](https://github.com/laravel/framework/commit/53c04406baa5f63bbb41127f40afee0a0facadd1): no need to delete [@taylorotwell](https://github.com/taylorotwell) 
- [f9ffa61](https://github.com/laravel/framework/commit/f9ffa6129ffbdac9b4497fe7660d0cc9f188477a): [5.1] Deal with cases when the manifest is empty ( [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [ee99882](https://github.com/laravel/framework/commit/ee99882aa3f438e1360deebe4b042f31402b37b3): Adding support for StreamOptions (#13925) [@marvinschroeder](https://github.com/marvinschroeder) 
- [76d53d6](https://github.com/laravel/framework/commit/76d53d642c36be13b003c5b7d329c364e0a755bc): Move Mockery::close at end of tearDown() (#14019)  [@wicochandra](https://github.com/wicochandra) 
- [d4afdd2](https://github.com/laravel/framework/commit/d4afdd2bbc6bf8692e3b33c0090e88c720bb0d27): [5.1] BeanstalkdJob bury function delete job unexp [@yewjs](https://github.com/yewjs) 
- [482a7cc](https://github.com/laravel/framework/commit/482a7cc23ebf87e21a68011a7929731c65fde912): fix formatting [@taylorotwell](https://github.com/taylorotwell) 
- [d236b89](https://github.com/laravel/framework/commit/d236b892737e4edd33dafd05b9f0aa675fbd0c48): Make alias resolution recursive [@theofidry](https://github.com/theofidry) 
- [163efce](https://github.com/laravel/framework/commit/163efce8059fbd6a7affde958876e7d1d0908d72): Update MySqlConnector.php (#13930)Sometimes we don [@mixisLv](https://github.com/mixisLv) 
- [cb6c650](https://github.com/laravel/framework/commit/cb6c650cbb25c27fa9a4eddd07c6a78dd87554ea): version [@taylorotwell](https://github.com/taylorotwell) 
- [09b09eb](https://github.com/laravel/framework/commit/09b09ebad480940f2b49f96bbfbea0647783025e): delete record [@taylorotwell](https://github.com/taylorotwell) 
- [285349b](https://github.com/laravel/framework/commit/285349b06055b15ec709c54ab8618e9af4fcd2ff): Model::fresh() returns static [@halaei](https://github.com/halaei) 


___

## [laravel/laravel](https://github.com/laravel/laravel)

### [master](https://github.com/laravel/laravel/compare/master@{2016-06-12}...master@{2016-06-19})
- [a20533c](https://github.com/laravel/laravel/commit/a20533c5116b67db0ba489bc70294cc6f857b88b): List supported drives in cache and broadcasting co [@jerguslejko](https://github.com/jerguslejko) 


___

## [laravel/docs](https://github.com/laravel/docs)

### [master](https://github.com/laravel/docs/compare/master@{2016-06-12}...master@{2016-06-19})
- [3c24ac1](https://github.com/laravel/docs/commit/3c24ac105fa870e24169f91888c443016777d4d0): wording [@taylorotwell](https://github.com/taylorotwell) 
- [70e1902](https://github.com/laravel/docs/commit/70e190212a0b6ddc5fd9b697a839bf697842a664): working on formatting [@taylorotwell](https://github.com/taylorotwell) 
- [571f203](https://github.com/laravel/docs/commit/571f2037629dfb1af3eae18158155d67cc751466): Empty lines also needed hereAnother two empty line [@manniL](https://github.com/manniL) 
- [60eaaed](https://github.com/laravel/docs/commit/60eaaed787be1d2f1acb674f0be4f9fed8230aaf): DOCS for whereDate, whereMonth, whereDay & whereYe [@srmklive](https://github.com/srmklive) 
- [a9fedfc](https://github.com/laravel/docs/commit/a9fedfcdef5aaeb00e875f6a63c9ebba780c51f4): add note for creating multiple factory filesif you [@browner12](https://github.com/browner12) 
- [8cafcc7](https://github.com/laravel/docs/commit/8cafcc7e0c8d28620f87f3c2ef9d565d38a221f9): Add empty line to comply to CommonMark guidelinesA [@manniL](https://github.com/manniL) 
- [5caaa12](https://github.com/laravel/docs/commit/5caaa1236cab33af8bf98186325d70a42b46957c): Collections: fix flatMap example [@RGustBardon](https://github.com/RGustBardon) 


### [5.2](https://github.com/laravel/docs/compare/5.2@{2016-06-12}...5.2@{2016-06-19})
- [d08e10d](https://github.com/laravel/docs/commit/d08e10d022bba2ff7061182248083be121ff15c0): Use `.app` as alternative domain because `.local`  [@besologic](https://github.com/besologic) 
- [3c24ac1](https://github.com/laravel/docs/commit/3c24ac105fa870e24169f91888c443016777d4d0): wording [@taylorotwell](https://github.com/taylorotwell) 
- [571f203](https://github.com/laravel/docs/commit/571f2037629dfb1af3eae18158155d67cc751466): Empty lines also needed hereAnother two empty line [@manniL](https://github.com/manniL) 
- [a9fedfc](https://github.com/laravel/docs/commit/a9fedfcdef5aaeb00e875f6a63c9ebba780c51f4): add note for creating multiple factory filesif you [@browner12](https://github.com/browner12) 
- [8cafcc7](https://github.com/laravel/docs/commit/8cafcc7e0c8d28620f87f3c2ef9d565d38a221f9): Add empty line to comply to CommonMark guidelinesA [@manniL](https://github.com/manniL) 
- [5caaa12](https://github.com/laravel/docs/commit/5caaa1236cab33af8bf98186325d70a42b46957c): Collections: fix flatMap example [@RGustBardon](https://github.com/RGustBardon) 


___

## [laravel/lumen-framework](https://github.com/laravel/lumen-framework)

### [master](https://github.com/laravel/lumen-framework/compare/master@{2016-06-12}...master@{2016-06-19})
- [b4ecc83](https://github.com/laravel/lumen-framework/commit/b4ecc8360b04079f5fe6a29426e7e7207d0d72d6): Support not registering facade aliases [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [b96e6b9](https://github.com/laravel/lumen-framework/commit/b96e6b9f80ae1d85b95392fa22c074ce4a617fef): Added resource path helper [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [f789b99](https://github.com/laravel/lumen-framework/commit/f789b990c78a47523d61e545e97509715a5b7987): Fixed service provider registration [@GrahamCampbell](https://github.com/GrahamCampbell) 
- [92a7d3f](https://github.com/laravel/lumen-framework/commit/92a7d3f05e79203713e1e2cad86e769a9ec726f3): Fixed bad composer merge [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/lumen](https://github.com/laravel/lumen)

### [develop](https://github.com/laravel/lumen/compare/develop@{2016-06-12}...develop@{2016-06-19})
- [335c331](https://github.com/laravel/lumen/commit/335c331317d0596d5402638f208f7676bc786b6d): Updated dependencies for 5.3 [@GrahamCampbell](https://github.com/GrahamCampbell) 


___

## [laravel/cashier](https://github.com/laravel/cashier)

### [6.0](https://github.com/laravel/cashier/compare/6.0@{2016-06-12}...6.0@{2016-06-19})
- [1e5c092](https://github.com/laravel/cashier/commit/1e5c092a14150af194e3ec2d774f07c5b1c4da01): code formatting [@taylorotwell](https://github.com/taylorotwell) 
- [4ed300e](https://github.com/laravel/cashier/commit/4ed300eb82227d5159b164f88761fa3027b811d5): Use the config value when retrieving the Stripe ke [@aaronhuisinga](https://github.com/aaronhuisinga) 


___

## Podcasts

### [The Laracasts Snippet](http://laracasts.audio)
- [30 Days](http://laracasts.simplecast.fm/29)

### [Laravel News Podcast](https://laravel-news.com)
- [LN 19: Laravel 5.3, Laravel Status Board](http://podcast.laravel-news.com/19)


___

## [Laracasts](https://laracasts.com)
- [VideoJS Setup](https://laracasts.com/series/how-to-use-html5-video-and-videojs/episodes/2)
- [HTML5 Video 101](https://laracasts.com/series/how-to-use-html5-video-and-videojs/episodes/1)
- [Hands On Refactoring](https://laracasts.com/series/whip-monstrous-code-into-shape/episodes/15)
- [The Finder Component](https://laracasts.com/series/discover-symfony-components/episodes/2)
