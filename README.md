# Vue3-elm-admin

## Git 提交规范

|   code   |                             desc                              |
| :------: | :-----------------------------------------------------------: |
|   feat   |                          添加新功能                           |
|   fix    |                           修复 bug                            |
|  style   | 代码格式变动, 不影响代码功能的更改(修改空格/格式化代码等操作) |
|   pref   |                         优化/性能提升                         |
|   docs   |                           修改文档                            |
|   test   |                      新增或修改测试用例                       |
| refactor |     功能重构，指既不是新增功能，也不是修改 bug 的代码变动     |
|  chore   |                    更改脚手架配置相关文件                     |
|  revert  |                           版本回退                            |
|    ui    |           只更新 css 样式，不涉及任何业务功能的修改           |

## Question

### Composition API 下怎么使用在 js 文件中使用 $router/$i18n/$ELEMENT 实例？

参考`src/locales/index.ts` 挂载 $i18n 实例，`src/main.ts`使用 $i18n 实例, 目前使用方式为挂载在 app 实例上获取，有没有更优的办法？
