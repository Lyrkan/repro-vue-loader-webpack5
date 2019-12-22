```
$ yarn
$ yarn webpack

Hash: aba811608c894052995e
Version: webpack 5.0.0-beta.10
Time: 2040ms
Built at: 2019-12-22 16:44:20
  Asset     Size
main.js  245 KiB  [emitted]  [name: main]
Entrypoint main = main.js
./src/index.js 129 bytes [built]
./node_modules/vue/dist/vue.runtime.esm.js 218 KiB [built]
./src/App.vue 1.05 KiB [built]
./src/App.vue?vue&type=template&id=7ba5bd90& 195 bytes [built]
./src/App.vue?vue&type=script&lang=js& 388 bytes [built]
./node_modules/vue-loader/lib/runtime/componentNormalizer.js 2.63 KiB [built]
./node_modules/vue-loader/lib/loaders/templateLoader.js??vue-loader-options!./node_modules/vue-loader/lib??vue-loader-options!./src/App.vue?vue&type=template&id=7ba5bd90& 257 bytes [built]
./node_modules/babel-loader/lib??ruleSet[0].rules[0].use[0]!./node_modules/vue-loader/lib??vue-loader-options!./src/App.vue?vue&type=script&lang=js& 39 bytes [built] [failed] [1 error]
    + 5 hidden modules

ERROR in ./src/App.vue?vue&type=script&lang=js& (./node_modules/babel-loader/lib??ruleSet[0].rules[0].use[0]!./node_modules/vue-loader/lib??vue-loader-options!./src/App.vue?vue&type=script&lang=js&)
Module build failed (from ./node_modules/babel-loader/lib/index.js):
ReferenceError: Unknown option: .url. Check out https://babeljs.io/docs/en/babel-core/#options for more information about options.
 @ ./src/App.vue?vue&type=script&lang=js& 1:0-185 1:201-204 1:206-388 1:206-388
 @ ./src/App.vue 2:0-55 3:0-50 3:0-50 9:2-8
 @ ./src/index.js 2:0-28 7:4-7
```
