# JavaScript Interview Questions & Answers

> Click :star:if you like the project. Pull Requests are highly appreciated. Follow me [@SudheerJonna](https://twitter.com/SudheerJonna) for technical updates.

Go to [Coding Exercise](#coding-exercise) for coding specific questions

## Download PDF/Epub formats

You can download the PDF and Epub version of this repository from the latest run on the [actions tab](https://github.com/sudheerj/JavaScript-Interview-Questions/actions).

---

<p align="center">
  <a href=https://zerotomastery.io/?utm_source=github&utm_medium=sponsor&utm_campaign=javascript-interview-questions>
    <img src=https://process.fs.teachablecdn.com/ADNupMnWyR7kCWRvm76Laz/resize=height:70/https://www.filepicker.io/api/file/AKYtjj5SSGyJuyZrkAB2 alt="ZTM Logo">
  </a>
  <p align="center">
    <ol>
    <li>Take this <a href=https://links.zerotomastery.io/jsp_sudheer>JavaScript Projects</a> course to go from a JavaScript beginner to confidently building your own projects</li>
    <li>Take this <a href=https://links.zerotomastery.io/mci_sudheer2>coding interview bootcamp</a> if you’re serious about getting hired and don’t have a CS degree</li>
    <li>Take this <a href=https://links.zerotomastery.io/ajs_sudheer>Advanced JavaScript Course</a> to learn advanced JS concepts and become a top JS developer</li>
    </ol>
  </p>
</p>

---

<div align="center">
    <p>
        <a href="https://www.youtube.com/watch?v=Zb4dPi7CANU">
            JavaScript Interview Questions | Top JavaScript Interview Questions and Answers.
            <div>
                <img src="https://img.youtube.com/vi/Zb4dPi7CANU/0.jpg" width="220" height="150" alt="JavaScript">
            </div>
        </a>
    </p>
</div>

---

### Table of Contents

| No. | Questions                                                                                                                                                         |
| --- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 1   | [JavaScript中创建对象的几种方法](#what-are-the-possible-ways-to-create-objects-in-javascript)                                         |
| 2   | [什么是原型链](#what-is-a-prototype-chain)                                                                                                             |
| 3   | [Call, Apply 和 Bind之间的区别](#what-is-the-difference-between-call-apply-and-bind)                                                        |
| 4   | [什么是JSON 常用操作有哪些](#what-is-json-and-its-common-operations)                                                                                 |
| 5   | [数组的slice方法的用处](#what-is-the-purpose-of-the-array-slice-method)                                                                   |
| 6   | [数组的splice方法的用处](#what-is-the-purpose-of-the-array-splice-method)                                                                 |
| 7   | [slice 和 splice之间的区别](#what-is-the-difference-between-slice-and-splice)                                                               |
| 8   | [比较 Object 和 Map](#how-do-you-compare-object-and-map)                                                                                           |
| 9   | [== 和 === 运算符的区别](#what-is-the-difference-between--and--operators)                                                            |
| 10  | [lambda表达式或者箭头函数是什么](#what-are-lambda-or-arrow-functions)                                                                                         |
| 11  | [什么是头等函数](#what-is-a-first-class-function)                                                                                                 |
| 12  | [什么是first order函数](#what-is-a-first-order-function)                                                                                                 |
| 13  | [什么是高阶函数](#what-is-a-higher-order-function)                                                                                               |
| 14  | [什么是一元函数](#what-is-a-unary-function)                                                                                                             |
| 15  | [什么是柯理化函数](#what-is-the-currying-function)                                                                                                   |
| 16  | [什么是纯函数](#what-is-a-pure-function)                                                                                                               |
| 17  | [let关键字的作用是什么](#what-is-the-purpose-of-the-let-keyword)                                                                                 |
| 18  | [let 和 var之间的区别](#what-is-the-difference-between-let-and-var)                                                                         |
| 19  | [选择let作为关键字的原因](#what-is-the-reason-to-choose-the-name-let-as-a-keyword)                                                 |
| 20  | [如何在switch块中重复声明变量不报错](#how-do-you-redeclare-variables-in-switch-block-without-an-error)                               |
| 21  | [什么是临时性死区](#what-is-the-temporal-dead-zone)                                                                                                 |
| 22  | [什么是IIFE](#what-is-iifeimmediately-invoked-function-expression)                                                     |
| 23  | [JavaScript中如何编码和解码URL?](#how-do-you-decode-or-encode-a-url-in-javascript)                                                              |
| 24  | [什么是记忆化](#what-is-memoization)                                                                                                                       |
| 25  | [什么是提升](#what-is-hoisting)                                                                                                                             |
| 26  | [ES6中的类是什么](#what-are-classes-in-es6)                                                                                                               |
| 27  | [什么是闭包](#what-are-closures)                                                                                                                           |
| 28  | [什么是模块](#what-are-modules)                                                                                                                             |
| 29  | [为什么需要模块](#why-do-you-need-modules)                                                                                                               |
| 30  | [javascript中的作用域是什么](#what-is-scope-in-javascript)                                                                                                       |
| 31  | [什么是service worker](#what-is-a-service-worker)                                                                                                             |
| 32  | [如何通过service worker来操作DOM](#how-do-you-manipulate-dom-using-a-service-worker)                                                             |
| 33  | [如何在service worker重启之间重用信息](#how-do-you-reuse-information-across-service-worker-restarts)                                       |
| 34  | [什么是IndexedDB](#what-is-indexeddb)                                                                                                                           |
| 35  | [什么是web storage](#what-is-web-storage)                                                                                                                       |
| 36  | [什么是post message](#what-is-a-post-message)                                                                                                                 |
| 37  | [什么是cookie](#what-is-a-cookie)                                                                                                                             |
| 38  | [为什么需要Cookie](#why-do-you-need-a-cookie)                                                                                                             |
| 39  | [cookie的可选项是什么](#what-are-the-options-in-a-cookie)                                                                                             |
| 40  | [如何删除cookie](#how-do-you-delete-a-cookie)                                                                                                         |
| 41  | [cookie, local storage 和 session storage之间的区别是什么](#What-are-the-differences-between-cookie-local-storage-and-session-storage)          |
| 42  | [localStorage 和 sessionStorage之间主要的区别是什么](#what-is-the-main-difference-between-localstorage-and-sessionstorage)                       |
| 43  | [如何访问web storage](#how-do-you-access-web-storage)                                                                                                   |
| 44  | [session storage上的可用方法有哪些](#what-are-the-methods-available-on-session-storage)                                                           |
| 45  | [什么是storage event和事件处理器](#what-is-a-storage-event-and-its-event-handler)                                                                   |
| 46  | [为什么需要web storage](#why-do-you-need-web-storage)                                                                                                       |
| 47  | [如何检测浏览器是否支持web storage](#how-do-you-check-web-storage-browser-support)                                                                     |
| 48  | [如何检测浏览器是否支持web workers](#how-do-you-check-web-workers-browser-support)                                                                     |
| 49  | [举个web worker的例子](#give-an-example-of-web-worker)                                                                                                   |
| 50  | [web workers在DOM上的限制是什么](#what-are-the-restrictions-of-web-workers-on-dom)                                                               |
| 51  | [什么是promise](#what-is-a-promise)                                                                                                                           |
| 52  | [为什么需要promise](#why-do-you-need-a-promise)                                                                                                           |
| 53  | [promise的三种状态是什么](#what-are-the-three-states-of-promise)                                                                                     |
| 54  | [什么是回调函数](#what-is-a-callback-function)                                                                                                       |
| 55  | [为什么需要回调](#why-do-we-need-callbacks)                                                                                                             |
| 56  | [什么是回调地狱](#what-is-a-callback-hell)                                                                                                               |
| 57  | [什么是server-sent events](#what-is-server-sent-events)                                                                                                         |
| 58  | [如何接收server-sent event的通知](#how-do-you-receive-server-sent-event-notifications)                                                         |
| 59  | [如何检测浏览器是否支持server-sent events](#how-do-you-check-browser-support-for-server-sent-events)                                               |
| 60  | [对于server sent events可用事件是什么](#what-are-the-events-available-for-server-sent-events)                                                     |
| 61  | [promise的主要规则是什么](#what-are-the-main-rules-of-promise)                                                                                         |
| 62  | [什么是回调中的回调](#what-is-callback-in-callback)                                                                                                     |
| 63  | [什么是promise链](#what-is-promise-chaining)                                                                                                             |
| 64  | [什么是promise.all](#what-is-promise.all)                                                                                                                       |
| 65  | [promise中race方法的作用](#what-is-the-purpose-of-race-method-in-promise)                                                                   |
| 66  | [javascript中的严格模式是什么](#what-is-a-strict-mode-in-javascript)                                                                                       |
| 67  | [为什么需要严格模式](#why-do-you-need-strict-mode)                                                                                                       |
| 68  | [如何声明严格模式](#how-do-you-declare-strict-mode)                                                                                                 |
| 69  | [双重否定的作用](#what-is-the-purpose-of-double-exclamation)                                                                           |
| 70  | [delete操作符的作用](#what-is-the-purpose-of-delete-operator)                                                                                 |
| 71  | [什么是typeof运算符](#what-is-typeof-operator)                                                                                                               |
| 72  | [什么是undefined属性](#what-is-undefined-property)                                                                                                         |
| 73  | [什么是null值](#what-is-null-value)                                                                                                                         |
| 74  | [null 和 undefined之间的区别是什么](#what-is-the-difference-between-null-and-undefined)                                                           |
| 75  | [什么是eval](#What-is-eval)                                                                                                                                     |
| 76  | [window 和 document之间的区别是什么](#what-is-the-difference-between-window-and-document)                                                         |
| 77  | [javascript中如何访问history](#how-do-you-access-history-in-javascript)                                                                               |
| 78  | [如何检测大写开关按键是否开启](#how-do-you-detect-caps-lock-key-turned-on-or-not)                                                             |
| 79  | [什么是isNaN](#what-is-isnan)                                                                                                                                   |
| 80  | [未声明和undefined变量间的区别是什么](#what-are-the-differences-between-undeclared-and-undefined-variables)                       |
| 81  | [什么是全局变量](#what-are-global-variables)                                                                                                           |
| 82  | [全局变量的问题是什么](#what-are-the-problems-with-global-variables)                                                                       |
| 83  | [什么是NaN属性](#what-is-nan-property)                                                                                                                     |
| 84  | [isFinite函数的作用是什么](#what-is-the-purpose-of-isfinite-function)                                                                             |
| 85  | [什么是事件流](#what-is-an-event-flow)                                                                                                                   |
| 86  | [什么是事件冒泡](#what-is-event-bubbling)                                                                                                                 |
| 87  | [什么是事件捕获](#what-is-event-capturing)                                                                                                               |
| 88  | [如何用JavaScript提交表单](#how-do-you-submit-a-form-using-javascript)                                                                           |
| 89  | [如何找到操作系统的详情](#how-do-you-find-operating-system-details)                                                                             |
| 90  | [文档 load 和 DOMContentLoaded事件之间的区别是什么](#what-is-the-difference-between-document-load-and-domcontentloaded-events)             |
| 91  | [原生，宿主和用户对象间的区别是什么](#what-is-the-difference-between-native-host-and-user-objects)                                     |
| 92  | [调试JavaScript代码的工具或技术是什么](#what-are-the-tools-or-techniques-used-for-debugging-javascript-code)                       |
| 93  | [与回调相比promise的优缺点是什么](#what-are-the-pros-and-cons-of-promises-over-callbacks)                                                   |
| 94  | [attribute 和 property之间的区别是什么](#what-is-the-difference-between-an-attribute-and-a-property)                                         |
| 95  | [什么是同源策略](#what-is-same-origin-policy)                                                                                                         |
| 96  | [void 0的作用是什么](#what-is-the-purpose-of-void-0)                                                                                                   |
| 97  | [JavaScript是编译型语言还是解释型语言](#is-javascript-a-compiled-or-interpreted-language)                                                             |
| 98  | [JavaScript是否是大小写敏感的语言](#is-javascript-a-case-sensitive-language)                                                                               |
| 99  | [Java 和 JavaScript间有什么关系吗](#is-there-any-relation-between-java-and-javascript)                                                           |
| 100 | [什么是事件](#what-are-events)                                                                                                                               |
| 101 | [谁发明了javascript](#who-created-javascript)                                                                                                                 |
| 102 | [preventDefault方法的用法是什么](#what-is-the-use-of-preventdefault-method)                                                                             |
| 103 | [stopPropagation方法的用法是什么](#what-is-the-use-of-stoppropagation-method)                                                                           |
| 104 | [return false涉及的步骤是什么](#what-are-the-steps-involved-in-return-false)                                                                       |
| 105 | [什么是BOM](#what-is-bom)                                                                                                                                       |
| 106 | [setTimeout的用处是什么](#what-is-the-use-of-settimeout)                                                                                                   |
| 107 | [setInterval用处是什么](#what-is-the-use-of-setinterval)                                                                                                 |
| 108 | [为什么JavaScript是单线程](#why-is-javascript-treated-as-single-threaded)                                                                     |
| 109 | [什么是事件委托](#what-is-an-event-delegation)                                                                                                       |
| 110 | [什么是ECMAScript](#what-is-ecmascript)                                                                                                                         |
| 111 | [什么是JSON](#what-is-json)                                                                                                                                     |
| 112 | [JSON的规则是什么](#what-are-the-syntax-rules-of-json)                                                                                           |
| 113 | [JSON stringify的目的是什么](#what-is-the-purpose-json-stringify)                                                                                         |
| 114 | [如何解析JSON字符串](#how-do-you-parse-json-string)                                                                                                     |
| 115 | [为什么需要JSON](#why-do-you-need-json)                                                                                                                     |
| 116 | [什么是PWA](#what-are-pwas?)                                                                                                                                  |
| 117 | [clearTimeout方法的作用是什么](#what-is-the-purpose-of-cleartimeout-method)                                                                         |
| 118 | [clearInterval方法的作用是什么](#what-is-the-purpose-of-clearinterval-method)                                                                       |
| 119 | [javascript中如何重定向到新页面](#how-do-you-redirect-new-page-in-javascript)                                                                         |
| 120 | [如何检测字符串是否包含子串](#how-do-you-check-whether-a-string-contains-a-substring)                                                 |
| 121 | [javascript如何校验email](#how-do-you-validate-an-email-in-javascript)                                                                         |
| 122 | [用javascript如何获取当前url](#how-do-you-get-the-current-url-with-javascript)                                                                 |
| 123 | [location对象下的url相关属性都是什么](#what-are-the-various-url-properties-of-location-object)                                                 |
| 124 | [如何用javascript获取查询字符串](#how-do-get-query-string-values-in-javascript)                                                                     |
| 125 | [如何检测键是否存在于对象上](#how-do-you-check-if-a-key-exists-in-an-object)                                                                   |
| 126 | [如何遍历或枚举javascript对象](#how-do-you-loop-through-or-enumerate-javascript-object)                                                 |
| 127 | [如何检测空对象](#how-do-you-test-for-an-empty-object)                                                                                       |
| 128 | [arguments对象是什么](#what-is-an-arguments-object)                                                                                                       |
| 129 | [如何让字符串的首字母大写](#how-do-you-make-first-letter-of-the-string-in-an-uppercase)                                         |
| 130 | [for循环的优缺点是什么](#what-are-the-pros-and-cons-of-for-loop)                                                                                 |
| 131 | [如何用javascript展示当前日期](#how-do-you-display-the-current-date-in-javascript)                                                           |
| 132 | [如何比较两个date对象](#how-do-you-compare-two-date-objects)                                                                                       |
| 133 | [如何检测一个字符串以另一个字符串开头](#how-do-you-check-if-a-string-starts-with-another-string)                                               |
| 134 | [如何用javascript去除字符串中的空格](#how-do-you-trim-a-string-in-javascript)                                                                                 |
| 135 | [如何用javascript添加键值对](#how-do-you-add-a-key-value-pair-in-javascript)                                                                   |
| 136 | ['!--' 符号是否代表特殊的操作符](#is-the-'!--'-notation-represents-a-special-operator)                                                       |
| 137 | [如何给变量指定默认值](#how-do-you-assign-default-values-to-variables)                                                                   |
| 138 | [如何定义多行字符串](#how-do-you-define-multiline-strings)                                                                                       |
| 139 | [什么是app shell模型](#what-is-an-app-shell-model)                                                                                                         |
| 140 | [我们可以为函数定义属性吗](#can-we-define-properties-for-functions)                                                                                 |
| 141 | [找到函数接收参数数量的方法是什么](#what-is-the-way-to-find-the-number-of-parameters-expected-by-a-function)               |
| 142 | [什么是polyfill](#what-is-a-polyfill)                                                                                                                         |
| 143 | [break 和 continue 语句是什么](#what-are-break-and-continue-statements)                                                                                 |
| 144 | [什么是js labels](#what-are-js-labels)                                                                                                                         |
| 145 | [保持声明在最顶部的好处是什么](#what-are-the-benefits-of-keeping-declarations-at-the-top)                                             |
| 146 | [初始化变量的好处是什么](#what-are-the-benefits-of-initializing-variables)                                                               |
| 147 | [创建新对象的推荐方式什么](#what-are-the-recommendations-to-create-new-object)                                                           |
| 148 | [如何定义JSON数组](#how-do-you-define-json-arrays)                                                                                                   |
| 149 | [如何生成随机整数](#how-do-you-generate-random-integers)                                                                                       |
| 150 | [可以写一个在特定范围内打印随机整数的函数吗](#can-you-write-a-random-integers-function-to-print-integers-with-in-a-range)         |
| 151 | [什么是tree shaking](#what-is-tree-shaking)                                                                                                                     |
| 152 | [tree shaking需要什么](#what-is-the-need-of-tree-shaking)                                                                                             |
| 153 | [推荐使用eval吗](#is-it-recommended-to-use-eval)                                                                                                   |
| 154 | [什么是正则表达式](#what-is-a-regular-expression)                                                                                                     |
| 155 | [正则表达式有什么字符串方法](#what-are-the-string-methods-available-in-regular-expression)                                       |
| 156 | [正则表达式中的修饰符是什么](#what-are-modifiers-in-regular-expression)                                                                             |
| 157 | [正则表达式模式什么](#what-are-regular-expression-patterns)                                                                                     |
| 158 | [RegExp对象是什么](#what-is-a-regexp-object)                                                                                                               |
| 159 | [如何用模式查找字符串](#how-do-you-search-a-string-for-a-pattern)                                                                             |
| 160 | [exec方法的作用是什么](#what-is-the-purpose-of-exec-method)                                                                                         |
| 161 | [如何修改HTML元素的样式](#how-do-you-change-style-of-a-html-element)                                                                           |
| 162 | [1+2+'3'的结果是什么](#what-would-be-the-result-of-1+2+'3')                                                                                       |
| 163 | [debugger语句是什么](#what-is-a-debugger-statement)                                                                                                     |
| 164 | [调试中断点的作用是什么](#what-is-the-purpose-of-breakpoints-indebugging)                                                                |
| 165 | [可以使用保留字作为标识符吗](#can-i-use-reserved-words-as-identifiers)                                                                               |
| 166 | [如何检测移动端浏览器](#how-do-you-detect-a-mobile-browser)                                                                                         |
| 167 | [不使用正则如何检测移动端浏览器](#how-do-you-detect-a-mobile-browser-without-regexp)                                                           |
| 168 | [如何用JS获取图片宽高](#how-do-you-get-the-image-width-and-height-using-js)                                                         |
| 169 | [如何发起同步HTTP请求](#how-do-you-make-synchronous-http-request)                                                                             |
| 170 | [如何发起异步HTTP请求](#how-do-you-make-asynchronous-http-request)                                                                           |
| 171 | [如何在javascript中将日期转换成另一个时区](#how-do-you-convert-date-to-another-timezone-in-javascript)                                           |
| 172 | [用来获取窗口大小的属性是什么](#what-are-the-properties-used-to-get-size-of-window)                                                         |
| 173 | [javascript中的条件运算符是什么](#what-is-a-conditional-operator-in-javascript)                                                                     |
| 174 | [你会使用链式条件运算符吗](#Can-you-apply-chaining-on-conditional-operator)                                                                 |
| 175 | [在页面加载完后执行js的方法是什么](#what-are-the-ways-to-execute-javascript-after-page-load)                                               |
| 176 | [proto和prototype的区别是什么](#what-is-the-difference-between-proto-and-prototype)                                                         |
| 177 | [举个需要分号的例子](#give-an-example-where-do-you-really-need-semicolon)                                                         |
| 178 | [freeze方法是什么](#what-is-a-freeze-method)                                                                                                               |
| 179 | [freeze方法的作用是什么](#what-is-the-purpose-of-freeze-method)                                                                                     |
| 180 | [为什么需要使用freeze方法](#why-do-i-need-to-use-freeze-method)                                                                                         |
| 181 | [如何检测浏览器语言偏好](#how-do-you-detect-a-browser-language-preference)                                                               |
| 182 | [如何用js将字符串转换成标题大写](#how-to-convert-string-to-title-case-with-javascript)                                                       |
| 183 | [如何检测页面禁用了js](#how-do-you-detect-javascript-disabled-in-the-page)                                                           |
| 184 | [javascript支持的操作符都是什么](#what-are-various-operators-supported-by-javascript)                                                         |
| 185 | [什么是剩余参数](#what-is-a-rest-parameter)                                                                                                             |
| 186 | [如果不将剩余参数当做最后一个参数会发生什么](#what-happens-if-you-do-not-use-rest-parameter-as-a-last-argument)                             |
| 187 | [javascript中可用的位运算符是什么](#what-are-the-bitwise-operators-available-in-javascript)                                                 |
| 188 | [什么是扩展运算符](#what-is-a-spread-operator)                                                                                                           |
| 189 | [如何判断对象是否被冻结](#how-do-you-determine-whether-object-is-frozen-or-not)                                                     |
| 190 | [如何使用对象判断两个值是否一样](#how-do-you-determine-two-values-same-or-not-using-object)                                             |
| 191 | [使用object的is方法的目的是什么](#what-is-the-purpose-of-using-object-is-method)                                                                   |
| 192 | [如何从一个对象拷贝属性到另一个对象](#how-do-you-copy-properties-from-one-object-to-other)                                                       |
| 193 | [assign方法的应用什么](#what-are-the-applications-of-assign-method)                                                                         |
| 194 | [什么是proxy对象](#what-is-a-proxy-object)                                                                                                                 |
| 195 | [seal方法的作用是什么](#what-is-the-purpose-of-seal-method)                                                                                         |
| 196 | [seal方法的应用什么](#what-are-the-applications-of-seal-method)                                                                             |
| 197 | [freeze和seal方法的区别是什么](#what-are-the-differences-between-freeze-and-seal-methods)                                             |
| 198 | [如何判断一个对象是否封闭](#how-do-you-determine-if-an-object-is-sealed-or-not)                                                         |
| 199 | [如何获得可枚举的键值对](#how-do-you-get-enumerable-key-and-value-pairs)                                                                   |
| 200 | [Object.values 和 Object.entries 方法间的主要区别是什么](#what-is-the-main-difference-between-object.values-and-object.entries-method)       |
| 201 | [如何获得任意对象的键列表](#how-can-you-get-the-list-of-keys-of-any-object)                                                                 |
| 202 | [如何用原型创建一个对象](#how-do-you-create-an-object-with-prototype)                                                                         |
| 203 | [什么是WeakSet](#what-is-a-weakset)                                                                                                                           |
| 204 | [WeakSet 和 Set间的区别是什么](#what-are-the-differences-between-weakset-and-set)                                                             |
| 205 | [列举WeakSet上可用方法的集合](#list-down-the-collection-of-methods-available-on-weakset)                                             |
| 206 | [什么是WeakMap](#what-is-a-weakmap)                                                                                                                           |
| 207 | [WeakMap 和 Map间的区别是什么](#what-are-the-differences-between-weakmap-and-map)                                                             |
| 208 | [列举WeakMap上可用方法的集合](#list-down-the-collection-of-methods-available-on-weakmap)                                             |
| 209 | [uneval的作用是什么](#what-is-the-purpose-of-uneval)                                                                                                   |
| 210 | [如何编码URL](#how-do-you-encode-an-url)                                                                                                             |
| 211 | [如何解码URL](#how-do-you-decode-an-url)                                                                                                             |
| 212 | [如何打印网页内容](#how-do-you-print-the-contents-of-web-page)                                                                           |
| 213 | [uneval 和 eval间的区别是什么](#what-is-the-difference-between-uneval-and-eval)                                                                 |
| 214 | [什么是匿名函数](#what-is-an-anonymous-function)                                                                                                   |
| 215 | [局部变量和全局变量间的优先级顺序是什么](#what-is-the-precedence-order-between-local-and-global-variables)                               |
| 216 | [js访问器是什么](#what-are-javascript-accessors)                                                                                                   |
| 217 | [在Object构造函数上如何定义属性](#how-do-you-define-property-on-object-constructor)                                                             |
| 218 | [get 和 defineProperty间的区别是什么](#what-is-the-difference-between-get-and-defineproperty)                                                   |
| 219 | [Getters 和 Setters的优点是什么](#what-are-the-advantages-of-getters-and-setters)                                                                 |
| 220 | [可以使用defineProperty方法新增getter和setter吗](#can-i-add-getters-and-setters-using-defineproperty-method)                                           |
| 221 | [switch-case的作用是什么](#what-is-the-purpose-of-switch-case)                                                                                         |
| 222 | [swtich case使用需要遵守的约定是什么](#what-are-the-conventions-to-be-followed-for-the-usage-of-swtich-case)                     |
| 223 | [什么是原始数据类型](#what-are-primitive-data-types)                                                                                                   |
| 224 | [访问对象属性的不同方法是什么](#what-are-the-different-ways-to-access-object-properties)                                               |
| 225 | [函数参数规则是什么](#what-are-the-function-parameter-rules)                                                                                   |
| 226 | [什么是error对象](#what-is-an-error-object)                                                                                                               |
| 227 | [什么时候会遇到语法错误](#when-you-get-a-syntax-error)                                                                                                       |
| 228 | [error对象中不同的错误名字都是什么](#what-are-the-different-error-names-from-error-object)                                                     |
| 229 | [错误处理中的语句都是什么](#what-are-the-various-statements-in-error-handling)                                                           |
| 230 | [javascript中两种循环是什么](#what-are-the-two-types-of-loops-in-javascript)                                                                   |
| 231 | [什么是nodejs](#what-is-nodejs)                                                                                                                                 |
| 232 | [什么是Intl对象](#what-is-an-intl-object)                                                                                                                 |
| 233 | [如何执行特定语言的日期和时间格式化](#how-do-you-perform-language-specific-date-and-time-formatting)                                   |
| 234 | [什么是迭代器](#what-is-an-iterator)                                                                                                                       |
| 235 | [同步的迭代如何工作](#how-does-synchronous-iteration-works)                                                                                     |
| 236 | [什么是事件循环](#what-is-an-event-loop)                                                                                                                   |
| 237 | [什么是调用栈](#what-is-call-stack)                                                                                                                         |
| 238 | [什么是事件队列](#what-is-an-event-queue)                                                                                                                 |
| 239 | [什么是装饰器](#what-is-a-decorator)                                                                                                                       |
| 240 | [Intl对象的属性是什么](#what-are-the-properties-of-intl-object)                                                                                 |
| 241 | [什么是一元运算符](#what-is-an-unary-operator)                                                                                                           |
| 242 | [如何对数组元素排序](#how-do-you-sort-elements-in-an-array)                                                                                     |
| 243 | [对数组排序时compareFunction作用是什么](#what-is-the-purpose-of-comparefunction-while-sorting-arrays)                                       |
| 244 | [如何反转数组](#how-do-you-reversing-an-array)                                                                                                   |
| 245 | [如何在数组中找到最小值和最大值](#how-do-you-find-min-and-max-value-in-an-array)                                                                   |
| 246 | [不使用Math函数如何找到最小值和最大值](#how-do-you-find-min-and-max-values-without--math-functions)                                          |
| 247 | [空语句是什么用处是什么](#what-is-an-empty-statement-and-purpose-of-it)                                                                     |
| 248 | [如何获得一个模块的元信息](#how-do-you-get-meta-data-of-a-module)                                                                                     |
| 249 | [什么是逗号运算符](#what-is-a-comma-operator)                                                                                                             |
| 250 | [逗号运算符的优点是什么](#what-is-the-advantage-of-a-comma-operator)                                                                           |
| 251 | [什么是typescript](#what-is-typescript)                                                                                                                         |
| 252 | [javascript 和 typescript间的区别是什么](#what-are-the-differences-between-javascript-and-typescript)                                         |
| 253 | [与javascript相比typescript的优点是什么](#what-are-the-advantages-of-typescript-over-javascript)                                                   |
| 254 | [什么是对象初始化器](#what-is-an-object-initializer)                                                                                                   |
| 255 | [什么是构造器函数](#what-is-a-constructor-method)                                                                                                     |
| 256 | [如果在类中写了超过一次的构造器会发生什么](#what-happens-if-you-write-constructor-more-than-once-in-a-class)                               |
| 257 | [如何调用父类的构造器](#how-do-you-call-the-constructor-of-a-parent-class)                                                           |
| 258 | [如何获取一个对象的原型](#how-do-you-get-the-prototype-of-an-object)                                                                           |
| 259 | [如果向 getPrototype 方法传递字符串类型会发生什么](#what-happens-if-i-pass-string-type-for-getprototype-method)                                         |
| 260 | [你如何将一个对象的原型设置成另一个对象](#how-do-you-set-prototype-of-one-object-to-another)                                                           |
| 261 | [如何检测对象是否能被扩展](#how-do-you-check-whether-an-object-can-be-extendable-or-not)                                       |
| 262 | [如何避免对象被扩展](#how-do-you-prevent-an-object-to-extend)                                                                                 |
| 263 | [使一个对象不可扩展的不同方法都是什么](#what-are-the-different-ways-to-make-an-object-non-extensible)                                     |
| 264 | [如何在一个对象上定义多个属性](#how-do-you-define-multiple-properties-on-an-object)                                                         |
| 265 | [在javascript中MEAN是什么](#what-is-mean-in-javascript)                                                                                                         |
| 266 | [在javascript中混淆是什么](#what-is-obfuscation-in-javascript)                                                                                           |
| 267 | [为什么需要混淆](#why-do-you-need-obfuscation)                                                                                                       |
| 268 | [什么是压缩](#what-is-minification)                                                                                                                     |
| 269 | [压缩的好处是什么](#what-are-the-advantages-of-minification)                                                                               |
| 270 | [混淆和加密的区别是什么](#what-are-the-differences-between-obfuscation-and-encryption)                                       |
| 271 | [用来压缩的常用工具是什么](#what-are-the-common-tools-used-for-minification)                                                               |
| 272 | [如何使用javascript进行表单校验](#how-do-you-perform-form-validation-using-javascript)                                                       |
| 273 | [不使用javascript如何进行表单校验](#how-do-you-perform-form-validation-without-javascript)                                                   |
| 274 | [DOM上用于约束性校验的方法有什么](#what-are-the-dom-methods-available-for-constraint-validation)                                     |
| 275 | [DOM属性上用于约束性校验的属性是什么](#what-are-the-available-constraint-validation-dom-properties)                                       |
| 276 | [validity属性是什么](#what-are-the-list-of-validity-properties)                                                                             |
| 277 | [举一个rangeOverflow属性用法的例子](#give-an-example-usage-of-rangeoverflow-property)                                                               |
| 278 | [在javascript中是否支持枚举特性](#is-enums-feature-available-in-javascript)                                                                             |
| 279 | [什么是枚举](#What-is-an-enum)                                                                                                                               |
| 280 | [如何列举一个对象的全部属性](#how-do-you-list-all-properties-of-an-object)                                                                       |
| 281 | [如何获得一个对象的属性描述符](#how-do-you-get-property-descriptors-of-an-object)                                                             |
| 282 | [属性描述符提供的属性都是什么](#what-are-the-attributes-provided-by-a-property-descriptor)                                           |
| 283 | [如何扩展类](#how-do-you-extend-classes)                                                                                                           |
| 284 | [不重载页面如何修改url](#how-do-i-modify-the-url-without-reloading-the-page)                                                         |
| 285 | [如何检查数组是否包含一个特定的值](#how-do-you-check-whether-an-array-includes-a-particular-value-or-not)                     |
| 286 | [如何比较标量数组](#how-do-you-compare-scalar-arrays)                                                                                             |
| 287 | [如何从get参数中获得值](#how-to-get-the-value-from-get-parameters)                                                                             |
| 288 | [如何打印用逗号作为千位分隔符的数字](#how-do-you-print-numbers-with-commas-as-thousand-separators)                                       |
| 289 | [java 和 javascript间的区别是什么](#what-is-the-difference-between-java-and-javascript)                                                         |
| 290 | [javascript支持命名空间吗](#does-javascript-supports-namespace)                                                                                         |
| 291 | [如何声明命名空间](#how-do-you-declare-namespace)                                                                                                     |
| 292 | [如何从父页面中调用iframe中的javascrpt代码](#how-do-you-invoke-javascript-code-in-an-iframe-from-parent-page)                               |
| 293 | [如何从日期中获取时差](#how-do-get-the-timezone-offset-from-date)                                                                             |
| 294 | [如何动态加载CSS和JS](#how-do-you-load-css-and-js-files-dynamically)                                                                     |
| 295 | [用DOM找到HTML元素的不同方法是什么](#what-are-the-different-methods-to-find-html-elements-in-dom)                                       |
| 296 | [什么是jQuery](#what-is-jquery)                                                                                                                                 |
| 297 | [什么是V8 JavaScript引擎](#what-is-v8-javascript-engine)                                                                                                     |
| 298 | [为什么把javascript叫动态语言](#why-do-we-call-javascript-as-dynamic-language)                                                                   |
| 299 | [什么是void操作符](#what-is-a-void-operator)                                                                                                               |
| 300 | [如何将光标设置为等待](#how-to-set-the-cursor-to-wait)                                                                                                   |
| 301 | [如何创建一个无限循环](#how-do-you-create-an-infinite-loop)                                                                                         |
| 302 | [为什么需要避免with语句](#why-do-you-need-to-avoid-with-statement)                                                                               |
| 303 | [下边for循环的输出是什么](#what-is-the-output-of-below-for-loops)                                                                                   |
| 304 | [列举一些ES6的特点](#list-down-some-of-the-features-of-es6)                                                                                   |
| 305 | [什么是ES6](#what-is-es6)                                                                                                                                       |
| 306 | [可以重复声明let 和 const变量吗](#can-I-redeclare-let-and-const-variables)                                                                               |
| 307 | [变量会使值不可变吗](#is-const-variable-makes-the-value-immutable)                                                                       |
| 308 | [默认参数是什么](#what-are-default-parameters)                                                                                                       |
| 309 | [什么是模板字面量](#what-are-template-literals)                                                                                                         |
| 310 | [如何用模板字面量写多行字符串](#how-do-you-write-multi-line-strings-in-template-literals)                                             |
| 311 | [什么是嵌套模板](#what-are-nesting-templates)                                                                                                         |
| 312 | [什么是带标签的模板](#what-are-tagged-templates)                                                                                                           |
| 313 | [什么是原始字符串](#what-are-raw-strings)                                                                                                                     |
| 314 | [什么是解构赋值](#what-is-destructuring-assignment)                                                                                             |
| 315 | [结构赋值中的默认值是什么](#what-are-default-values-in-destructuring-assignment)                                                       |
| 316 | [如何用解构赋值来交换变量](#how-do-you-swap-variables-in-destructuring-assignment)                                                   |
| 317 | [什么是增强的对象字面量](#what-are-enhanced-object-literals)                                                                                           |
| 318 | [什么是动态导入](#what-are-dynamic-imports)                                                                                                             |
| 319 | [动态导入的用例是什么](#what-are-the-use-cases-for-dynamic-imports)                                                                         |
| 320 | [什么是类型数组](#what-are-typed-arrays)                                                                                                                   |
| 321 | [模块加载器的优点是什么](#what-are-the-advantages-of-module-loaders)                                                                           |
| 322 | [什么是collation](#what-is-collation)                                                                                                                           |
| 323 | [什么是for...of语句](#what-is-for...of-statement)                                                                                                         |
| 324 | [下边数组的展开运算符的输出是什么](#what-is-the-output-of-below-spread-operator-array)                                                           |
| 325 | [PostMessage安全吗](#is-postmessage-secure)                                                                                                                   |
| 326 | [postmessage的目标源为通配符的问题是什么](#what-are-the-problems-with-postmessage-target-origin-as-wildcard)                             |
| 327 | [如何避免从攻击者处接收postMessages](#how-do-you-avoid-receiving-postmessages-from-attackers)                                                 |
| 328 | [可以完全避免使用postMessages吗](#can-i-avoid-using-postmessages-completely)                                                                           |
| 329 | [postMessages是同步的吗](#is-postmessages-synchronous)                                                                                                       |
| 330 | [Javascript是什么范式](#what-paradigm-is-javascript)                                                                                                       |
| 331 | [内部和外部javascript间的区别是什么](#what-is-the-difference-between-internal-and-external-javascript)                               |
| 332 | [JavaScript比服务端脚本快吗](#is-javascript-faster-than-server-side-script)                                                                     |
| 333 | [如何获得复选框的状态](#how-do-you-get-the-status-of-a-checkbox)                                                                               |
| 334 | [双波浪操作符的作用是什么](#what-is-the-purpose-of-double-tilde-operator)                                                                     |
| 335 | [如何将字符转换成ASCII码](#how-do-you-convert-character-to-ascii-code)                                                                         |
| 336 | [什么是ArrayBuffer](#what-is-arraybuffer)                                                                                                                       |
| 337 | [下边字符串表达式的输出是什么](#what-is-the-output-of-below-string-expression)                                                                   |
| 338 | [Error对象的作用是什么](#what-is-the-purpose-of-error-object)                                                                                       |
| 339 | [EvalError对象的作用是什么](#what-is-the-purpose-of-evalerror-object)                                                                               |
| 340 | [案例中从非严格模式到严格模式抛出的错误是什么](#what-are-the-list-of-cases-error-thrown-from-non-strict-mode-to-strict-mode)       |
| 341 | [所有的对象都有原型吗](#do-all-objects-have-prototypes)                                                                                                 |
| 342 | [形参和实参的区别](#what-is-the-difference-between-a-parameter-and-an-argument)                                         |
| 343 | [数组中some方法的作用是什么](#what-is-the-purpose-of-some-method-in-arrays)                                                                     |
| 344 | [如何合并两个或多个数组](#how-do-you-combine-two-or-more-arrays)                                                                                   |
| 345 | [浅拷贝和深拷贝之间的区别是什么](#what-is-the-difference-between-shallow-and-deep-copy)                                                     |
| 346 | [如何创建特定数量的字符串副本](#how-do-you-create-specific-number-of-copies-of-a-string)                                               |
| 347 | [如何针对正则表达式返回所有匹配的字符串](#how-do-you-return-all-matching-strings-against-a-regular-expression)                       |
| 348 | [如何在开头或结尾去除字符串空格](#how-do-you-trim-a-string-at-the-beginning-or-ending)                                                       |
| 349 | [下边一元运算符的console语句输出是什么](#what-is-the-output-of-below-console-statement-with-unary-operator)                           |
| 350 | [javascript使用mixin吗](#does-javascript-uses-mixins)                                                                                                       |
| 351 | [什么是thunk函数](#what-is-a-thunk-function)                                                                                                             |
| 352 | [什么是异步thunk](#what-are-asynchronous-thunks)                                                                                                     |
| 353 | [下边的函数调用输出是什么](#what-is-the-output-of-below-function-calls)                                                                         |
| 354 | [如何从字符串中移除换行](#how-to-remove-all-line-breaks-from-a-string)                                                                       |
| 355 | [回流和重绘的区别是什么](#what-is-the-difference-between-reflow-and-repaint)                                                           |
| 356 | [对数组取反会发生什么](#what-happens-with-negating-an-array)                                                                                       |
| 357 | [若两数组相加会发生什么](#what-happens-if-we-add-two-arrays)                                                                                           |
| 358 | [在假值前增加额外的运算符的输出是什么](#what-is-the-output-of-prepend-additive-operator-on-falsy-values)                               |
| 359 | [如何使用特殊字符创建self字符串](#how-do-you-create-self-string-using-special-characters)                                                 |
| 360 | [如何移除数组中的假值](#how-do-you-remove-falsy-values-from-an-array)                                                                     |
| 361 | [数组如何去重](#how-do-you-get-unique-values-of-an-array)                                                                             |
| 362 | [什么是解构别名](#what-is-destructuring-aliases)                                                                                                   |
| 363 | [不使用map方法如何对数组值进行映射](#how-do-you-map-the-array-values-without-using-map-method)                                             |
| 364 | [如何清空一个数组](#how-do-you-empty-an-array)                                                                                                           |
| 365 | [你如何将数字四舍五入到某些小数](#how-do-you-rounding-numbers-to-certain-decimals)                                                               |
| 366 | [将数组转换为对象最简单的方法是什么](#what-is-the-easiest-way-to-convert-an-array-to-an-object)                                             |
| 367 | [如何用一些数据来创建数组](#how-do-you-create-an-array-with-some-data)                                                                           |
| 368 | [console对象中的占位符是什么](#what-are-the-placeholders-from-console-object)                                                                   |
| 369 | [是否可以将 CSS 添加到控制台消息](#is-it-possible-to-add-css-to-console-messages)                                                                   |
| 370 | [console对象的dir方法的作用是什么](#what-is-the-purpose-of-dir-method-of-console-object)                                                       |
| 371 | [在控制台中可以调试HTML元素吗](#is-it-possible-to-debug-html-elements-in-console)                                                             |
| 372 | [使用console对象如何用制表符格式展示数据](#how-do-you-display-data-in-a-tabular-format-using-console-object)                             |
| 373 | [如何验证实参是否是数字](#how-do-you-verify-that-an-argument-is-a-number-or-not)                                                   |
| 374 | [如何创建复制到剪贴板按钮](#how-do-you-create-copy-to-clipboard-button)                                                                         |
| 375 | [获得时间戳的快捷方式](#what-is-the-shortcut-to-get-timestamp)                                                                                   |
| 376 | [如何扁平化多维数组](#how-do-you-flattening-multi-dimensional-arrays)                                                                 |
| 377 | [最简单的多条件检测是什么](#what-is-the-easiest-multi-condition-checking)                                                                     |
| 378 | [如何捕获浏览器返回键](#how-do-you-capture-browser-back-button)                                                                                 |
| 379 | [如何禁止网页的右键点击](#how-do-you-disable-right-click-in-the-web-page)                                                                 |
| 380 | [什么是包装对象](#what-are-wrapper-objects)                                                                                                             |
| 381 | [什么是AJAX](#what-is-ajax)                                                                                                                                     |
| 382 | [处理异步代码的不同方法是什么](#what-are-the-different-ways-to-deal-with-asynchronous-code)                                         |
| 383 | [如何取消fetch请求](#how-to-cancel-a-fetch-request)                                                                                                   |
| 384 | [什么是web speech API](#what-is-web-speech-api)                                                                                                                 |
| 385 | [最小的超时延迟](#what-is-minimum-timeout-throttling)                                                                                         |
| 386 | [现代浏览器中如何实现0延迟](#how-do-you-implement-zero-timeout-in-modern-browsers)                                                     |
| 387 | [事件循环中的任务是什么](#what-are-tasks-in-event-loop)                                                                                                     |
| 388 | [什么是微任务](#what-are-microtasks)                                                                                                                       |
| 389 | [不同的事件循环是什么](#what-are-different-event-loops)                                                                                                 |
| 390 | [微任务队列的作用是什么](#what-is-the-purpose-of-queuemicrotask)                                                                                   |
| 391 | [如何在typescript文件中使用javascript库](#how-do-you-use-javascript-libraries-in-typescript-file)                                                 |
| 392 | [promises 和 observables间的区别是什么](#what-are-the-differences-between-promises-and-observables)                                           |
| 393 | [什么是堆](#what-is-heap)                                                                                                                                     |
| 394 | [什么是事件表](#what-is-an-event-table)                                                                                                                 |
| 395 | [什么是微任务队列](#what-is-a-microtask-queue)                                                                                                           |
| 396 | [shim 和 polyfill间的区别是什么](#what-is-the-difference-between-shim-and-polyfill)                                                             |
| 397 | [如何检测原生或非原生值类型](#how-do-you-detect-primitive-or-non-primitive-value-type)                                               |
| 398 | [什么是babel](#what-is-babel)                                                                                                                                   |
| 399 | [Node.js完全是单线程吗](#is-node.js-completely-single-threaded)                                                                                   |
| 400 | [observables通常的用例是什么](#what-are-the-common-use-cases-of-observables)                                                                     |
| 401 | [什么是RxJS](#what-is-rxjs)                                                                                                                                     |
| 402 | [函数构造器和函数声明之间的区别是什么](#what-is-the-difference-between-function-constructor-and-function-declaration)     |
| 403 | [什么是短路条件](#what-is-a-short-circuit-condition)                                                                                           |
| 404 | [调整数组大小最简单的方法是什么](#what-is-the-easiest-way-to-resize-an-array)                                                                         |
| 405 | [什么是可观察对象](#what-is-an-observable)                                                                                                                   |
| 406 | [函数和类声明间的区别是什么](#what-is-the-difference-between-function-and-class-declarations)                                 |
| 407 | [什么是async函数](#what-is-an-async-function)                                                                                                           |
| 408 | [如何避免promises吞错误](#how-do-you-prevent-promises-swallowing-errors)                                                                   |
| 409 | [什么是deno](#what-is-deno)                                                                                                                                     |
| 410 | [如何用javascript使对象可迭代](#how-do-you-make-an-object-iterable-in-javascript)                                                             |
| 411 | [什么是正确的尾调用](#what-is-a-proper-tail-call)                                                                                                         |
| 412 | [如何检测对象是否是promise](#how-do-you-check-an-object-is-a-promise-or-not)                                                                 |
| 413 | [如何检测一个函数是否被当作构造器来调用](#how-to-detect-if-a-function-is-called-as-constructor)                                                     |
| 414 | [arguments对象和剩余参数的区别是什么](#what-are-the-differences-between-arguments-object-and-rest-parameter)                     |
| 415 | [展开运算符和剩余参数的区别是什么](#what-are-the-differences-between-spread-operator-and-rest-parameter)                       |
| 416 | [生成器都有哪些种类](#what-are-the-different-kinds-of-generators)                                                                         |
| 417 | [内置的可迭代对象都是什么](#what-are-the-built-in-iterables)                                                                                               |
| 418 | [for...of 和 for...in 语句间的区别是什么](#what-are-the-differences-between-for...of-and-for...in-statements)                           |
| 419 | [如何定义实例和非实例属性](#how-do-you-define-instance-and-non-instance-properties)                                                 |
| 420 | [isNaN 和 Number.isNaN间的区别是什么?](#what-is-the-difference-between-isnan-and-number.isnan)                                                  |
| 421 | [不使用额外的括号如何调用IIFE?](#how-to-invoke-an-iife-without-any-extra-brackets)                                                            |
| 422 | [在switch case中可以使用表达式吗?](#is-that-possible-to-use-expressions-in-switch-cases)                                                      |
| 423 | [忽略promise错误最简单的方法是什么?](#what-is-the-easiest-way-to-ignore-promise-errors)                                                            |
| 424 | [如何使用CSS给console输出添加样式?](#how-do-style-the-console-output-using-css)                                                                          |
| 425 | [什么是空值合并运算符(??)?](<#what-is-nullish-coalescing-operator-(??)>)                                                                           |
| 426 | [如何分组和嵌套console输出?](#how-do-you-group-and-nest-console-output)                                                                            |
| 427 | [密接和稀疏数组的区别是什么?](#what-is-the-difference-between-dense-and-sparse-arrays)                                                |
| 428 | [创建稀疏数组的不同方法都是什么?](#what-are-the-different-ways-to-create-sparse-arrays)                                                      |
| 429 | [setTimeout, setImmediate 和 process.nextTick间的区别是什么?](#what-is-the-difference-between-set-timeout-,-set-immediate-and-processnext-tick) |
| 430 | [不修改原始数组如何反转数组?](#how-do-you-reverse-an-array-without-modifying-original-array)                                    |
| 431 | [如何创建自定义的HTML元素?](#how-do-you-create-custom-html-element)                                                                                  |
| 432 | [全局执行上下文是什么?](#what-is-global-execution-context)                                                                                            |
| 433 | [函数执行上下文是什么?](#what-is-function-execution-context)                                                                                        |
| 434 | [什么是防抖?](#what-is-debouncing)                                                                                                                        |
| 435 | [什么是节流?](#what-is-throttling)                                                                                                                        |
| 436 | [什么是可选链?](#what-is-optional-chaining)                                                                                                          |

1. ### What are the possible ways to create objects in JavaScript

   		如下所示javascript有许多创建对象的方法

		   1. **Object构造函数:**
		
		      最简单的创建空对象的方法就是使用`Object`构造函数。目前此方法不推荐。
		
		      ```javascript
		      var object = new Object();
		      ```
		
		   2. **Object的create方法:**
		
		      通过向`Object`的`create`方法传入对象的原型来创建新对象
		
		      ```javascript
		      var object = Object.create(null);
		      ```
		
		   3. **Object字面量语法:**
		
		      对象字面量语法（或者对象初始化）是由花括号包裹的由逗号分隔的键值对集合
		
		      ```javascript
		      var object = {
		           name: "Sudheer",
		           age: 34
		      };
		
		      对象字面量的属性值可以是任何数据类型，包括数组，方法和嵌套对象
		      ```
		
		      **注意:** 这是最简单的创建对象的方法
		
		   4. **Function构造函数:**
		
		      创建任意函数，并使用`new`操作符来生成对象实例
		
		      ```javascript
		      function Person(name) {
		        this.name = name;
		        this.age = 21;
		      }
		      var object = new Person("Sudheer");
		      ```
		
		   5. **带原型的Function构造函数:**
		   
		      类似于函数构造器，但是使用原型来声明属性和方法
		
		      ```javascript
		      function Person() {}
		      Person.prototype.name = "Sudheer";
		      var object = new Person();
		      ```
		
		      等价于使用函数原型作为参数调用`Object`的`create`方法创建的实例，然后调用对象实例作为参数的`call`方法
		
		      ```javascript
		      function func(x, y, z) {};
		
		      new func(x, y, z);
		      ```
		
		      **(或者)**
		
		      ```javascript
		      // Create a new instance using function prototype.
		      var newInstance = Object.create(func.prototype)
		
		      // Call the function
		      var result = func.call(newInstance, x, y, z),
		
		      // If the result is a non-null object then use it otherwise just use the new instance.
		      console.log(result && typeof result === 'object' ? result : newInstance);
		      ```
		
		   6. **ES6 Class 语法:**
		
		      ES6引入了创建对象的类特性
		
		      ```javascript
		      class Person {
		        constructor(name) {
		          this.name = name;
		        }
		      }
		
		      var object = new Person("Sudheer");
		      ```
		
		   7. **单例模式:**
		
		      单例是只能被实例化一次的对象。重复调用对象的构造函数也只会返回同一个实例，这种方法能够保证不会意外创建多个实例
		
		      ```javascript
		      var object = new (function () {
		        this.name = "Sudheer";
		      })();
		      ```

      **[⬆ Back to Top](#table-of-contents)**

2. ### What is a prototype chain

   **原型链继承** 用于在已存在的对象类型上构建新的类型。类似于基于类的编程语言中的继承

   对象实例的原型可通过**Object.getPrototypeOf(object)** 或者 \***\*proto\*\*** 属性访问，而构造函数的原型则是通过**Object.prototype**访问

   ![Screenshot](images/prototype_chain.png)

   **[⬆ Back to Top](#table-of-contents)**

3. ### What is the difference between Call, Apply and Bind

   `Call`, `Apply`和`Bind`可被如下例子解释

   **Call:** call()方法调用一个给定`this`和多个参数的函数

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   invite.call(employee1, "Hello", "How are you?"); // Hello John Rodson, How are you?
   invite.call(employee2, "Hello", "How are you?"); // Hello Jimmy Baily, How are you?
   ```

   **Apply:** 调用一个给定`this`并允许传入数组作为参数的函数

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   invite.apply(employee1, ["Hello", "How are you?"]); // Hello John Rodson, How are you?
   invite.apply(employee2, ["Hello", "How are you?"]); // Hello Jimmy Baily, How are you?
   ```

   **bind:** 返回一个函数，允许传入任意数量的参数

   ```javascript
   var employee1 = { firstName: "John", lastName: "Rodson" };
   var employee2 = { firstName: "Jimmy", lastName: "Baily" };

   function invite(greeting1, greeting2) {
     console.log(
       greeting1 + " " + this.firstName + " " + this.lastName + ", " + greeting2
     );
   }

   var inviteEmployee1 = invite.bind(employee1);
   var inviteEmployee2 = invite.bind(employee2);
   inviteEmployee1("Hello", "How are you?"); // Hello John Rodson, How are you?
   inviteEmployee2("Hello", "How are you?"); // Hello Jimmy Baily, How are you?
   ```

   `Call`和`Apply`可互相替换. 两者都立即执行当前函数. 使用者只需决定是传入数组方便还是逗号分隔的参数列表方便. 你只需记住`Call`是 **逗号** (分隔的列表) 而 `Apply` 是 **数组**.

   而`Bind`创建一个将`this`绑定到传入bind()中的第一个参数中的新函数.

   **[⬆ Back to Top](#table-of-contents)**

4. ### What is JSON and its common operations

   **JSON** 是`Douglas Crockford`创建的遵循JavaScript对象语法的基于文本的一种数据格式. 用于通过网络传输数据，基本上是后缀名是`.json`且`MIME`类型是`application/json`的文本文件

   **Parsing(解析):** 将字符串转换为原生对象

   ```javascript
   JSON.parse(text);
   ```

   **Stringification(序列化):** 将原生对象转换为字符串以便能够通过网络传输

   ```javascript
   JSON.stringify(object);
   ```

   **[⬆ Back to Top](#table-of-contents)**

5. ### What is the purpose of the array slice method

   **slice()** 方法返回一个数组中选定元素的新的数组对象. 选择从给定的start参数开始，到可选的end参数为止，不包括最后一个元素. 如果不传第二个参数则选择直到最后.

   此方法的一些例子

   ```javascript
   let arrayIntegers = [1, 2, 3, 4, 5];
   let arrayIntegers1 = arrayIntegers.slice(0, 2); // returns [1,2]
   let arrayIntegers2 = arrayIntegers.slice(2, 3); // returns [3]
   let arrayIntegers3 = arrayIntegers.slice(4); //returns [5]
   ```

   **注意:** Slice 方法不会修改原始数组，会返回子集作为一个新的数组.

   **[⬆ Back to Top](#table-of-contents)**

6. ### What is the purpose of the array splice method

   **splice()** 方法用来向数组中添加或者删除元素并返回删除的元素. 第一个参数指定了数组中插入或者删除的位置，而第二个可选参数代表删除元素的个数. 剩余的每个额外的参数会添加到数组中.

   Some of the examples of this method are,

   ```javascript
   let arrayIntegersOriginal1 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal2 = [1, 2, 3, 4, 5];
   let arrayIntegersOriginal3 = [1, 2, 3, 4, 5];

   let arrayIntegers1 = arrayIntegersOriginal1.splice(0, 2); // returns [1, 2]; original array: [3, 4, 5]
   let arrayIntegers2 = arrayIntegersOriginal2.splice(3); // returns [4, 5]; original array: [1, 2, 3]
   let arrayIntegers3 = arrayIntegersOriginal3.splice(3, 1, "a", "b", "c"); //returns [4]; original array: [1, 2, 3, "a", "b", "c", 5]
   ```

   **注意:** Splice 方法修改原始数组并返回删除的数组.

   **[⬆ Back to Top](#table-of-contents)**

7. ### What is the difference between slice and splice

   下表是一些主要的不同

   |          Slice           |         Splice             |
   | ------------------------ | -------------------------- |
   | 不会修改原始素组(immutable) |  修改原始数组(mutable)       |
   | 返回原始数组的子集          |  将删除的元素作为数组返回      |
   | 用于从数组中选择元素        |  数组中插入或者删除元素        |

   **[⬆ Back to Top](#table-of-contents)**

8. ### How do you compare Object and Map

   **Objects** 和 **Maps** 类似，都可以让你设置键值, 检索值，删除键，检测键中是否存在某个值. 由于这个原因，历史上Objects被用作Maps. 但有非常重要的区别，要在某些特定的情形下使用Map.

   1. Object的键是String或者Symbol，而Map中的键可以是任何值，包括函数，对象和任何原始值.
   2. Map中的键是有序的，而Object的不是. 因此遍历Map对象时返回插入的键顺序.
   3. 通过size属性可以很容易地获取Map的大小，而Object的属性数量必须要人工确定.
   4. Map是可迭代的因此可以直接遍历，而遍历Object需要以某种形式获得键的集合然后才能遍历.
   5. Object有原型，所以有默认的键，如果你不小心则会产生冲突. 在ES5中可以使用map = Object.create(null)来绕过，但很少这么干.
   6. Map在频繁增加或删除键值对的情形下性能可能更好.

   **[⬆ Back to Top](#table-of-contents)**

9. ### What is the difference between == and === operators

   
   JavaScript提供严格相等（===，!==）和类型转换相等（==， !=）的比较。严格等于符号考虑变量的类型，而非严格等于符号在变量值的基础上进行类型校准/转换。严格相等符号对于不同的类型遵循以下条件

   1. 当两个字符串有相同的字符序列，相同的长度，并且对应位置是相同的字符时就是严格相等
   2. 当两个数字是数字上相等时就是严格相等。比如，有相同的数字值
      有两种特殊情况
      1. NaN不和任何东西相等，包括NaN本身
      2. 正0和负0彼此相等
   3. 两个布尔操作数同为true或者同为false时严格相等
   4. 两个对象如果引用同一个Object即是严格相等
   5. Null 和 Undefined 不严格相等（===）, 但是可以 ==. 比如,
      null===undefined --> false but null==undefined --> true

   一些涵盖上边情形的例子：

   ```javascript
   0 == false   // true
   0 === false  // false
   1 == "1"     // true
   1 === "1"    // false
   null == undefined // true
   null === undefined // false
   '0' == false // true
   '0' === false // false
   []==[] or []===[] //false, refer different objects in memory
   {}=={} or {}==={} //false, refer different objects in memory
   ```

   **[⬆ Back to Top](#table-of-contents)**

10. ### What are lambda or arrow functions

    An arrow function is a shorter syntax for a function expression and does not have its own **this, arguments, super, or new.target**. These functions are best suited for non-method functions, and they cannot be used as constructors.
    箭头函数是函数表达式的简化写法，没有自己本身的 **this, arguments, super, 或者 new.target**。这些函数适用于非方法的函数（不是类或原型的方法），并且不能被用作构造函数

    **[⬆ Back to Top](#table-of-contents)**

11. ### What is a first class function

    在JavaScript中，函数是头等对象。头等函数意味着编程语言中的函数可以被当做任意其他变量对待

    例如，在这种编程语言中，函数可以被当做参数传递给其他函数，可以被其他函数返回，可以赋值给变量。比如，下边的例子就是handler函数被赋值给了listener（监听器）

    ```javascript
    const handler = () => console.log("This is a click handler function");
    document.addEventListener("click", handler);
    ```

    **[⬆ Back to Top](#table-of-contents)**

12. ### What is a first order function

    First-order函数不能接收其他函数作为参数也不能返回函数
    
    ```javascript
    const firstOrder = () => console.log("I am a first order function!");
    ```

    **[⬆ Back to Top](#table-of-contents)**

13. ### What is a higher order function

    高阶函数可以接收另一个函数作为参数，或者返回一个函数，或者同时满足两者

    ```javascript
    const firstOrderFunc = () =>
      console.log("Hello, I am a First order function");
    const higherOrder = (ReturnFirstOrderFunc) => ReturnFirstOrderFunc();
    higherOrder(firstOrderFunc);
    ```

    **[⬆ Back to Top](#table-of-contents)**

14. ### What is a unary function

    Unary function (i.e. monadic) is a function that accepts exactly one argument. It stands for a single argument accepted by a function.
    一元函数（如monad）仅接收一个参数。代表被一个函数接收的单一参数。

    让我们举个一元函数的例子

    ```javascript
    const unaryFunction = (a) => console.log(a + 10); // Add 10 to the given argument and display the value
    ```

    **[⬆ Back to Top](#table-of-contents)**

15. ### What is the currying function

    柯理化是将接收多个参数的函数转化成一系列只有一个参数的函数的过程。柯理化是根据数学家**Haskell Curry**命名的。柯理化可以将一个任意数量参数的函数转化成一个一元函数。

    让我们举个接收多个参数函数的例子看看如何进行柯理化

    ```javascript
    const multiArgFunction = (a, b, c) => a + b + c;
    console.log(multiArgFunction(1, 2, 3)); // 6

    const curryUnaryFunction = (a) => (b) => (c) => a + b + c;
    curryUnaryFunction(1); // returns a function: b => c =>  1 + b + c
    curryUnaryFunction(1)(2); // returns a function: c => 3 + c
    curryUnaryFunction(1)(2)(3); // returns the number 6
    ```

    柯理化后函数能极大提高 **代码复用性** 和 **复合函数**.

    **[⬆ Back to Top](#table-of-contents)**

16. ### What is a pure function

    **纯函数（Pure function）** 返回值仅仅由没有副作用的参数决定. 比如, 如果用相同参数调用函数多次，函数总会返回同样的值.

    让我们举例子看看纯函数和非纯函数的区别

    ```javascript
    //Impure
    let numberArray = [];
    const impureAddNumber = (number) => numberArray.push(number);
    //Pure
    const pureAddNumber = (number) => (argNumberArray) =>
      argNumberArray.concat([number]);

    //Display the results
    console.log(impureAddNumber(6)); // returns 1
    console.log(numberArray); // returns [6]
    console.log(pureAddNumber(7)(numberArray)); // returns [6, 7]
    console.log(numberArray); // returns [6]
    ```

    如上边的代码片段所示，**Push**函数不是纯函数，因为会修改数组并返回添加元素后数组的新长度值。而**Concat**函数则没有副作用，会连接另一个数组后生成一个新的数组，返回值是连接后的新数组

    记住纯函数因为没有副作用对简化单元测试很重要。能避免强耦合并使你的应用更健壮。这些原则与ES6中的**不可变性（Immutability）**一样，优先使用**const** 胜过 **let**

    **[⬆ Back to Top](#table-of-contents)**

17. ### What is the purpose of the let keyword

    `let` 声明了**块级作用域内的局部变量**。因此用let关键字定义的变量只能用在块作用域，语句或表达式中。而`var`声明的变量作用于全局或者函数体内的非块作用域的局部

    Let's take an example to demonstrate the usage,

    ```javascript
    let counter = 30;
    if (counter === 30) {
      let counter = 31;
      console.log(counter); // 31
    }
    console.log(counter); // 30 (because the variable in if block won't exist here)
    ```

    **[⬆ Back to Top](#table-of-contents)**

18. ### What is the difference between let and var

    下表列出了不同

    | var                      | let                         |
    | -------------------------| --------------------------- |
    | JavaScript诞生开始就使用的 | ES6中才引入的                 |
    | 函数作用域                | 块级作用域                    |
    | 变量会被提升（hoisted）      | 提升但未初始化 |

    Let's take an example to see the difference,

    ```javascript
    function userDetails(username) {
      if (username) {
        console.log(salary); // undefined due to hoisting
        console.log(age); // ReferenceError: Cannot access 'age' before initialization
        let age = 30;
        var salary = 10000;
      }
      console.log(salary); //10000 (accessible to due function scope)
      console.log(age); //error: age is not defined(due to block scope)
    }
    userDetails("John");
    ```

    **[⬆ Back to Top](#table-of-contents)**

19. ### What is the reason to choose the name let as a keyword

    `let` 是早期编程语言像**Scheme** 和 **Basic**中采纳的数学语句. 从其他很多种已经将`let`作为传统关键字的语言中借用，以尽可能接近`var`

    **[⬆ Back to Top](#table-of-contents)**

20. ### How do you redeclare variables in switch block without an error

    如果试图在`switch 块`中重新声明变量会引起错误，因为只有一个块. 比如下边的例子代码块会抛出语法错误

    ```javascript
    let counter = 1;
    switch (x) {
      case 0:
        let name;
        break;

      case 1:
        let name; // SyntaxError for redeclaration.
        break;
    }
    ```

    为避免这个错误，你可以在case子句中创建一个嵌套的块，在词法环境中创建一个新的块级作用域
    

    ```javascript
    let counter = 1;
    switch (x) {
      case 0: {
        let name;
        break;
      }
      case 1: {
        let name; // No SyntaxError for redeclaration.
        break;
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

21. ### What is the Temporal Dead Zone

    JavaScript中用let和const关键字会产生临时性死区（TDZ），而用var不会。在ES6中，在`let`或`const`声明变量（作用域内部）之前访问时会引起`引用错误（ReferenceError）` 这段跨越于绑定变量的创建和声明之间的时机就叫做临时性死区
    让我们用例子来说明该行为

    ```javascript
    function somemethod() {
      console.log(counter1); // undefined
      console.log(counter2); // ReferenceError
      var counter1 = 1;
      let counter2 = 2;
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

22. ### What is IIFE(Immediately Invoked Function Expression)

    IIFE（立即执行函数表达式）是定义即执行的JavaScript函数。函数签名如下

    ```javascript
    (function () {
      // logic here
    })();
    ```

    使用IIFE的主要原因是能够保证数据隐私性，因为在IIFE内部声明的变量无法在外部访问。比如，当你试图访问IIFE内部的变量时，会抛出如下的错误

    ```javascript
    (function () {
      var message = "IIFE";
      console.log(message);
    })();
    console.log(message); //Error: message is not defined
    ```

    **[⬆ Back to Top](#table-of-contents)**

23. ### How do you decode or encode a URL in JavaScript?

    `encodeURI()` 函数用来编码URL。此函数需要URL字符串作为参数并返回编码后的字符串
    `decodeURI()` 函数用来解码URL。此函数需要编码后的URL字符串作为参数，并返回解码后的字符串

    **注意:** 若想编码如下字符 `/ ? : @ & = + $ #` 则需要使用 `encodeURIComponent()`.

    ```javascript
    let uri = "employeeDetails?name=john&occupation=manager";
    let encoded_uri = encodeURI(uri);
    let decoded_uri = decodeURI(encoded_uri);
    ```

    **[⬆ Back to Top](#table-of-contents)**

24. ### What is memoization

    记忆化是通过缓存之前计算好的结果来提高函数性能的一种编程技术。每当记忆化的函数调用时，参数被用于索引缓存。如果数据存在，则不需要执行整个函数便可直接返回。否则执行函数并缓存结果
    让我们看一个向函数中添加记忆功能的例子

    ```javascript
    const memoizAddition = () => {
      let cache = {};
      return (value) => {
        if (value in cache) {
          console.log("Fetching from cache");
          return cache[value]; // Here, cache.value cannot be used as property name starts with the number which is not a valid JavaScript  identifier. Hence, can only be accessed using the square bracket notation.
        } else {
          console.log("Calculating result");
          let result = value + 20;
          cache[value] = result;
          return result;
        }
      };
    };
    // returned function from memoizAddition
    const addition = memoizAddition();
    console.log(addition(20)); //output: 40 calculated
    console.log(addition(20)); //output: 40 cached
    ```

    **[⬆ Back to Top](#table-of-contents)**

25. ### What is Hoisting

    提升（Hoisting）在JavaScript中就是变量，函数和类声明在代码执行前被移动到它们所属作用域顶部的一种机制。记住JavaScript只提升声明不提升初始化
    让我们看一个变量提升的简单例子

    ```javascript
    console.log(message); //output : undefined
    var message = "The variable Has been hoisted";
    ```

    对解释器来说，上边的代码看上去像下边一样

    ```javascript
    var message;
    console.log(message);
    message = "The variable Has been hoisted";
    ```

    同理，函数声明也被提升

    ```javascript
    message("Good morning"); //Good morning

    function message(name) {
      console.log(name);
    }
    ```

    函数提升能够使函数在声明前可以安全地使用

    **[⬆ Back to Top](#table-of-contents)**

26. ### What are classes in ES6

    ES6中，JavaScript类主要是已存在的原型继承的语法糖

    例如，下边是函数表达式写法的原型继承

    ```javascript
    function Bike(model, color) {
      this.model = model;
      this.color = color;
    }

    Bike.prototype.getDetails = function () {
      return this.model + " bike has" + this.color + " color";
    };
    ```

    而ES6的类是一种替代写法

    ```javascript
    class Bike {
      constructor(color, model) {
        this.color = color;
        this.model = model;
      }

      getDetails() {
        return this.model + " bike has" + this.color + " color";
      }
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

27. ### What are closures

    闭包是函数声明内部词法环境和函数的组合。也就是说，它就是一个能访问外部或者封闭函数变量的内部函数。闭包有三个作用域链

    1. 在花括号之间变量定义处的自身作用域
    2. 外部的函数变量
    3. 全局变量

    让我们看下闭包概念的例子

    ```javascript
    function Welcome(name) {
      var greetingInfo = function (message) {
        console.log(message + " " + name);
      };
      return greetingInfo;
    }
    var myFunction = Welcome("John");
    myFunction("Welcome "); //Output: Welcome John
    myFunction("Hello Mr."); //output: Hello Mr.John
    ```

    按照上边的代码，内部函数（即greetingInfo）甚至能够在外部函数返回后访问外部函数的作用域（即Welcome）

    **[⬆ Back to Top](#table-of-contents)**

28. ### What are modules

    模块指独立的，可复用的小的单位，也可用于许多JavaScript设计模式的基础。多数JavaScript模块导出一个对象字面量，函数或者构造函数

    **[⬆ Back to Top](#table-of-contents)**

29. ### Why do you need modules

    下边是在javascript生态系统中使用模块的优点列表

    1. 可维护性
    2. 可复用性
    3. 命名空间

    **[⬆ Back to Top](#table-of-contents)**

30. ### What is scope in javascript

    作用域是在代码运行时的特定部分对变量，函数和对象的可访问性。换句话说，作用域决定变量可见性和代码其他地方资源的可见性

    **[⬆ Back to Top](#table-of-contents)**

31. ### What is a service worker

    Serfice worker就是运行在后台的脚本（JS文件），独立于网页并提供不需要网页或用户交互的功能。service worker的一些主要特性是丰富的离线体验（以离线为主的网页应用开发），周期性的后台同步，推送通知和侦听并处理网络请求并以编程方式管理响应缓存

    **[⬆ Back to Top](#table-of-contents)**

32. ### How do you manipulate DOM using a service worker

   	 Service worker无法直接访问DOM，但是可以通过控制的网页向`postMessage`接口发送的数据进行响应来通信，网页可以操作DOM
    

    **[⬆ Back to Top](#table-of-contents)**

33. ### How do you reuse information across service worker restarts

    service worker的问题是当没有被使用时会被终止，下次需要时会重启，所以不能依赖service worker的`onfetch`和`onmessage`handler的全局状态。在这种情形下，service worker在多次重启期间能够访问IndexedDB API来进行持久化和重用

    **[⬆ Back to Top](#table-of-contents)**

34. ### What is IndexedDB

    IndexedDB是用户客户端大量结构化数据存储的低级API，包括文件/blob。该API使用索引来开启高性能数据搜索。

    **[⬆ Back to Top](#table-of-contents)**

35. ### What is web storage

    Web storage是浏览器提供的一种机制，能够在用户浏览器本地存储键/值对，比使用cookies更直观。web storage对在客户端存储数据提供了两种机制

    1. **Local storage:** 为同源站点存储没有超时日期的数据
    2. **Session storage:** 为会话（session）存储数据，当浏览器tab关闭时数据销毁

    **[⬆ Back to Top](#table-of-contents)**

36. ### What is a post message

    Post message是一个为跨域Window对象间开启通信的方法（即在页面和它产生的弹出窗口之间，或在页面和嵌入的iframe之间）。通常来说，不同页面的脚本仅在遵守同源策略时才允许互相访问（即页面同协议，同端口且同主机）

    **[⬆ Back to Top](#table-of-contents)**

37. ### What is a Cookie

    cookie是存储在你计算机上且能被浏览器访问的数据片段。cookie被保存为键/值对。
    	 例如，你可以像下边一样创建一个名字为username的cookie

    ```javascript
    document.cookie = "username=John";
    ```

    ![Screenshot](images/cookie.png)

    **[⬆ Back to Top](#table-of-contents)**

38. ### Why do you need a Cookie

    Cookies are used to remember information about the user profile(such as username). It basically involves two steps,
    cookies被用于记录用户资料（如用户名）。基本上包括两步

    1. 用户访问网页时，用户信息可以被存储为cookie。
    2. 该用户下次访问网页，cookie记住了这个用户资料

    **[⬆ Back to Top](#table-of-contents)**

39. ### What are the options in a cookie

    cookie有几个选项

    1. 默认情况下浏览器关闭时cookie被删除，但是你可以通过设置超时日期（UTC时间）来改变此行为

    ```javascript
    document.cookie = "username=John; expires=Sat, 8 Jun 2019 12:00:00 UTC";
    ```

    1. 默认情况下cookie属于当前页面。但是你可以通过path参数告诉浏览器cookie属于哪个路径

    ```javascript
    document.cookie = "username=John; path=/services";
    ```

    **[⬆ Back to Top](#table-of-contents)**

40. ### How do you delete a cookie

    可以通过设置超时日期来删除cookie。此种情况你不必指定cookie值
    	 例如，如下所示你可以在当前页删除username的cookie

    ```javascript
    document.cookie =
      "username=; expires=Fri, 07 Jun 2019 00:00:00 UTC; path=/;";
    ```

    **注意:** 你应当指定cookie的path来确保删除正确的cookie. 有些浏览器不指顶path参数不允许删除cookie

    **[⬆ Back to Top](#table-of-contents)**

41. ### What are the differences between cookie, local storage and session storage

    下边是cookie local storage 和 session storage间的一些区别

    | 特性     | Cookie        | Local storage    | Session storage     |
    | -------- | ------------- | ---------------- | ------------------- |
    | 客户端或服务端可访问性 | 客户端和服务端都能访问     | 只在客户端 | 只在客户端    |
    | 声明周期            | 使用Expires选项配置 | 直到手动删除    | 直到tab关闭 |
    | SSL支持            | 支持      | 不支持    | 不支持       |
    | 数据最大容量       | 4KB        | 5 MB             | 5MB                 |

    **[⬆ Back to Top](#table-of-contents)**

42. ### What is the main difference between localStorage and sessionStorage

    LocalStorage和SessionStorage一样但是即是关闭浏览器重新打开数据也会存在（即没有过期时间）而sessionStorage的数据在网页会话结束时就会被清除

    **[⬆ Back to Top](#table-of-contents)**

43. ### How do you access web storage

    Window对象实现了`WindowLocalStorage` 和 `WindowSessionStorage`对象，即对应属性方法`localStorage`(window.localStorage)和`sessionStorage`(window.sessionStorage)。这些属性创建了Storage对象的实例，通过这些属性可以更新，获得和删除指定域名和相应存储类型（session或local）的数据
    例如，你可以像下边一样读写local storage

    ```javascript
    localStorage.setItem("logo", document.getElementById("logo").value);
    localStorage.getItem("logo");
    ```

    **[⬆ Back to Top](#table-of-contents)**

44. ### What are the methods available on session storage

    session storage提供了读 写 清除会话数据的方法

    ```javascript
    // Save data to sessionStorage
    sessionStorage.setItem("key", "value");

    // Get saved data from sessionStorage
    let data = sessionStorage.getItem("key");

    // Remove saved data from sessionStorage
    sessionStorage.removeItem("key");

    // Remove all saved data from sessionStorage
    sessionStorage.clear();
    ```

    **[⬆ Back to Top](#table-of-contents)**

45. ### What is a storage event and its event handler

    StorageEvent是在另一个文档上下文存储区域发生改变时触发的事件。而onstorage属性是为处理存储事件的EventHandler（注：当前页面使用的 storage 被其他页面修改时会触发 StorageEvent 事件）
    语法如下

    ```javascript
    window.onstorage = functionRef;
    ```

    让我们看一个记录存储键和值onstorage事件处理器得用法事例

    ```javascript
    window.onstorage = function (e) {
      console.log(
        "The " +
          e.key +
          " key has been changed from " +
          e.oldValue +
          " to " +
          e.newValue +
          "."
      );
    };
    ```

    **[⬆ Back to Top](#table-of-contents)**

46. ### Why do you need web storage

    Web storage更安全，可以本地存储大量数据并且不影响网站性能。信息也不会传输到服务端。因此与Cookies相比更推荐使用

    **[⬆ Back to Top](#table-of-contents)**

47. ### How do you check web storage browser support

    在使用web storage前你需要检测浏览器是否支持localStorage和sessionStorage

    ```javascript
    if (typeof Storage !== "undefined") {
      // Code for localStorage/sessionStorage.
    } else {
      // Sorry! No Web Storage support..
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

48. ### How do you check web workers browser support

    在使用web worker前你需要检测浏览器是否支持

    ```javascript
    if (typeof Worker !== "undefined") {
      // code for Web worker support.
    } else {
      // Sorry! No Web Worker support..
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

49. ### Give an example of a web worker

    开始web worker计数器的例子需要遵照以下步骤

    1. 创建Web Worker文件：需要写一个脚本来自增计数器。命名为counter.js

    ```javascript
    let i = 0;

    function timedCount() {
      i = i + 1;
      postMessage(i);
      setTimeout("timedCount()", 500);
    }

    timedCount();
    ```

    这里的postMessage()方法用来向HTML页面回传数据

    1. 创建Web Worke人对象：通过检测浏览器是否支持来创建一个 web worker对象。让我们将文件命名为web_worker_example.js

    ```javascript
    if (typeof w == "undefined") {
      w = new Worker("counter.js");
    }
    ```

    我们可以接收来自web worker中的信息

    ```javascript
    w.onmessage = function (event) {
      document.getElementById("message").innerHTML = event.data;
    };
    ```

    1. 终止Web Worker:
       Web worker会在终止前持续监听信息（即使外部脚本已经执行完了）。可以使用terminate()方法来终止监听信息
       

    ```javascript
    w.terminate();
    ```

    1. 复用Web Worker: 若设置worker为undefined则可以复用代码

    ```javascript
    w = undefined;
    ```

    **[⬆ Back to Top](#table-of-contents)**

50. ### What are the restrictions of web workers on DOM

    由于Web Workers在外部文件中定义，因此无法访问以下js对象

    1. Window对象
    2. Document对象
    3. Parent对象

    **[⬆ Back to Top](#table-of-contents)**

51. ### What is a promise

    promise是可能在未来某个时间产生值的对象，要么是解析后的值，要么是未解析的原因（例如网络错误）。会是三种状态之一：fulfilled rejected 或 pending

    创建Promise的语法如下

    ```javascript
    const promise = new Promise(function (resolve, reject) {
      // promise description
    });
    ```

    promise的使用如下

    ```javascript
    const promise = new Promise(
      (resolve) => {
        setTimeout(() => {
          resolve("I'm a Promise!");
        }, 5000);
      },
      (reject) => {}
    );

    promise.then((value) => console.log(value));
    ```

    promise的运作流程如下
    

    ![Screenshot](images/promises.png)

    **[⬆ Back to Top](#table-of-contents)**

52. ### Why do you need a promise

    Promises用于处理异步操作。提供了能减少回调地狱的可选方法并能写整洁干净的代码

    **[⬆ Back to Top](#table-of-contents)**

53. ### What are the three states of promise

    Promises有三种状态

    1. **Pending:** 操作开始前的初始状态
    2. **Fulfilled:** 该状态表明指定的操作已经完成
    3. **Rejected:** 该状态表明操作未完成。此种情况会抛出错误值

    **[⬆ Back to Top](#table-of-contents)**

54. ### What is a callback function

    回调函数是作为参数传给另一个函数的函数。此函数会被在外部函数的内部调用从而完成操作。
       让我们看看使用回调函数的一个简单例子

    ```javascript
    function callbackFunction(name) {
      console.log("Hello " + name);
    }

    function outerFunction(callback) {
      let name = prompt("Please enter your name.");
      callback(name);
    }

    outerFunction(callbackFunction);
    ```

    **[⬆ Back to Top](#table-of-contents)**

55. ### Why do we need callbacks

    因为js是一个事件驱动的语言所以我们需要回调。这就意味着js在监听其他事件时会一直执行而非等待事件响应
    让我们看一个例子，第一个函数调用了一个API（setTimeout模拟）并且下一个函数记录了信息

    ```javascript
    function firstFunction() {
      // Simulate a code delay
      setTimeout(function () {
        console.log("First function called");
      }, 1000);
    }
    function secondFunction() {
      console.log("Second function called");
    }
    firstFunction();
    secondFunction();

    Output;
    // Second function called
    // First function called
    ```

    从输出可以观察到，js没有等待第一个函数的响应且剩余的代码块被执行。因此回调被用于能确保确定的代码直到其他代码执行完毕时才执行的地方。

    **[⬆ Back to Top](#table-of-contents)**

56. ### What is a callback hell

    回调地狱是有多层嵌套的反模式，当处理异步逻辑时这会令代码难以阅读和调试。回调地狱看上去像下边一样

    ```javascript
    async1(function(){
        async2(function(){
            async3(function(){
                async4(function(){
                    ....
                });
            });
        });
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

57. ### What are server-sent events

    Server-sent事件（SSE）是服务器推送技术，能够使浏览器无需依赖轮训（polling）通过HTTP连接即可接收到自动更新。这是一种单向通信通道 - 事件只从服务端流向客户端。过去曾用于Facebook/Twitter更新，股票价格更新和信息流等

    **[⬆ Back to Top](#table-of-contents)**

58. ### How do you receive server-sent event notifications

    EventSource对象用来接收SSE通知。例如，你可以像下边一样从服务器端接收消息

    ```javascript
    if (typeof EventSource !== "undefined") {
      var source = new EventSource("sse_generator.js");
      source.onmessage = function (event) {
        document.getElementById("output").innerHTML += event.data + "<br>";
      };
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

59. ### How do you check browser support for server-sent events

    可以像下边一样在使用前执行浏览器支持度检查

    ```javascript
    if (typeof EventSource !== "undefined") {
      // Server-sent events supported. Let's have some code here!
    } else {
      // No server-sent events supported
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

60. ### What are the events available for server sent events

    下边是SSE支持的事件
    
    | 事件 | 描述 |
    |---- | ---------
    | onopen | 用于当与服务端连接打开时 |
    | onmessage | 该事件用于信息接收到时 |
    | onerror | 产生错误时发生|

    **[⬆ Back to Top](#table-of-contents)**

61. ### What are the main rules of promise

    promise必须遵守以下规则

    1. promise是实现了符合标准的`.then()` 方法的对象
    2. pending状态的promise可以过渡到fulfilled或者rejected状态
    3. fulfilled或rejected的promise 已经确定下来，不能再过渡到其他任何状态
    4. 一旦promise确定, 值不能改变

    **[⬆ Back to Top](#table-of-contents)**

62. ### What is callback in callback

    你可以将一个回调嵌套在另一个回调中串行执行指令。这就是回调中的回调

    ```javascript
    loadScript("/script1.js", function (script) {
      console.log("first script is loaded");

      loadScript("/script2.js", function (script) {
        console.log("second script is loaded");

        loadScript("/script3.js", function (script) {
          console.log("third script is loaded");
          // after all scripts are loaded
        });
      });
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

63. ### What is promise chaining

    使用promise一个接一个串行执行一系列异步任务的过程就是Promise链。让我们看一个计算最终结果的promise链

    ```javascript
    new Promise(function (resolve, reject) {
      setTimeout(() => resolve(1), 1000);
    })
      .then(function (result) {
        console.log(result); // 1
        return result * 2;
      })
      .then(function (result) {
        console.log(result); // 2
        return result * 3;
      })
      .then(function (result) {
        console.log(result); // 6
        return result * 4;
      });
    ```

    上边的处理函数中，结果传入了.then()处理函数的链式工作流中

    1. 初始的promise在1秒后解析
    2. 之后 `.then` 的处理函数通过打印result(1) 进行了调用，然后返回该值\* 2 后的一个promise.
    3. 之后值传给了下一个 `.then` 处理器函数并打印了 result(2) 并返回该值\* 3 后的一个promise.
    4. 最后值传给了最后的 `.then` 处理器函数，打印了 result(6) 并返回该值\* 4 后的一个promise.

    **[⬆ Back to Top](#table-of-contents)**

64. ### What is promise.all

    Promise.all 将一个promise数组作为参数输入（可迭代的）, 当全部promise都被解析或者任何一个被拒绝时才会被解析. 例如，promise.all方法的语法如下

    ```javascript
    Promise.all([Promise1, Promise2, Promise3]) .then(result) => {   console.log(result) }) .catch(error => console.log(`Error in promises ${error}`))
    ```

    **注意:** 记住promise的顺序（输出结果）和输入顺序一样
    
    **[⬆ Back to Top](#table-of-contents)**

65. ### What is the purpose of the race method in promise

    Promise.race()方法会返回第一个解析或者拒绝的promise实例. 让我们看一个race() 方法的例子，其中promise2先被解析完

    ```javascript
    var promise1 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 500, "one");
    });
    var promise2 = new Promise(function (resolve, reject) {
      setTimeout(resolve, 100, "two");
    });

    Promise.race([promise1, promise2]).then(function (value) {
      console.log(value); // "two" // Both promises will resolve, but promise2 is faster
    });
    ```

    **[⬆ Back to Top](#table-of-contents)**

66. ### What is a strict mode in javascript

    ECMAScript 5中严格模式是一种新特性，允许你将程序或者函数置于一个"严格的"的操作上下文中。这可以避免特定的操作抛出更多的异常。语法表达式`"use strict";`告诉浏览器在Strict模式中使用JS代码

    **[⬆ Back to Top](#table-of-contents)**

67. ### Why do you need strict mode

    通过将"坏语法"变成实际出现的错误，严格模式可以用来写“安全的”JS。例如，可以通过抛出一个错误来消除不小心创建的全局变量，也可以为不可写属性，只读属性，不存在的属性，不存在的变量或者不存在的对象的赋值抛出一个错误。

    **[⬆ Back to Top](#table-of-contents)**

68. ### How do you declare strict mode

    严格模式通过在脚本或函数的开始添加"use strict"; 来声明
    如果在脚本开头声明，则作用于全局作用域

    ```javascript
    "use strict";
    x = 3.14; // This will cause an error because x is not declared
    ```

    如果在函数内声明，则作用域本地作用域

    ```javascript
    x = 3.14; // This will not cause an error.
    myFunction();

    function myFunction() {
      "use strict";
      y = 3.14; // This will cause an error
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

69. ### What is the purpose of double exclamation

    双重感叹或者否定(!!) 确保结果类型是boolean. 如果是falsey (如 0, null, undefined等.), 就是false, 否则就是true.
    例如，你可以用下边的表达式来检测IE版本

    ```javascript
    let isIE8 = false;
    isIE8 = !!navigator.userAgent.match(/MSIE 8.0/);
    console.log(isIE8); // returns true or false
    ```

    如果不是用这个表达式则会返回原始值

    ```javascript
    console.log(navigator.userAgent.match(/MSIE 8.0/)); // returns either an Array or null
    ```

    **注意:** 表达式 !! 不是操作符, 只是两个 !.

    **[⬆ Back to Top](#table-of-contents)**

70. ### What is the purpose of the delete operator

    delete关键字用于删除属性及对应的值

    ```javascript
    var user = { name: "John", age: 20 };
    delete user.age;

    console.log(user); // {name: "John"}
    ```

    **[⬆ Back to Top](#table-of-contents)**

71. ### What is the typeof operator

    你可以用JavaScript的typeof操作符来发现JS变量的类型. 返回变量或表达式的类型

    ```javascript
    typeof "John Abraham"; // Returns "string"
    typeof (1 + 2); // Returns "number"
    ```

    **[⬆ Back to Top](#table-of-contents)**

72. ### What is undefined property

    undefined属性表明变量没有被赋值，或者根本就没声明。undefined的类型值也是undefined

    ```javascript
    var user; // Value is undefined, type is undefined
    console.log(typeof user); //undefined
    ```

    通过将值设置为undefined任何变量都可以被置空

    ```javascript
    user = undefined;
    ```

    **[⬆ Back to Top](#table-of-contents)**

73. ### What is null value

    null值代表任意的对象值都不存在。它是JS的原始值。null的类型值是object。
       通过将值设置为null可以清空变量


    ```javascript
    var user = null;
    console.log(typeof user); //object
    ```

    **[⬆ Back to Top](#table-of-contents)**

74. ### What is the difference between null and undefined

    null和undefined的主要区别如下

    | Null                                            | Undefined                                          |
    | ----------------------------------------------- | -------------------------------------------------- |
    | 赋值null表明变量不指向任何对象                        | 变量声明但未赋值                                      |
    | null的类型是object                                | undefined的类型是undefined                          |
    | null值是代表null, 空, 或不存在的引用的原始值             | undefined值是当变量未赋值时使用的原始值                 |
    | 表明变量值的缺失                                   | 表明变量本身的缺失                                    |
    | 当执行原始操作时转换成（0）                          | 当执行原始操作时转换成NaN                              |

    **[⬆ Back to Top](#table-of-contents)**

75. ### What is eval

    eval()方法执行字符串形式的JS代码。字符串可以是JS表达式，变量，语句或者一系列语句

    ```javascript
    console.log(eval("1 + 2")); //  3
    ```

    **[⬆ Back to Top](#table-of-contents)**

76. ### What is the difference between window and document

    下边是window和document的主要区别

    | Window                                        | Document                                          |
    | -------------------------------------------- | -------------------------------------------------- |
    | 是网页中根级别的元素                           | window对象的直接子属性. 也叫Document Object Model(DOM) |
    | 默认网页中window对象都可以访问                 | 通过window.document 或者document来访问                  |
    | 有如下方法alert(), confirm() 有如下属性 document, location | 提供像getElementById, getElementsByTagName, createElement 等方法              |

    **[⬆ Back to Top](#table-of-contents)**

77. ### How do you access history in javascript

    window.history对象包含浏览器的访问历史。你可以用back()和forward()方法来加载历史记录中前一个或后一个URL。

    ```javascript
    function goBack() {
      window.history.back();
    }
    function goForward() {
      window.history.forward();
    }
    ```

    **注意:** 可以不适用window前缀来访问history

    **[⬆ Back to Top](#table-of-contents)**

78. ### How do you detect caps lock key turned on or not

    `mouseEvent.getModifierState()` 方法用来返回一个布尔值表明修饰键是否被激活. 像 CapsLock, ScrollLock 和 NumLock 这些按键被点击就会被激活, 再点击就会被停用

    让我们看一个输入框元素中检测CapsLock 开/关的的例子
    

    ```html
    <input type="password" onmousedown="enterInput(event)" />

    <p id="feedback"></p>

    <script>
      function enterInput(e) {
        var flag = e.getModifierState("CapsLock");
        if (flag) {
          document.getElementById("feedback").innerHTML = "CapsLock activated";
        } else {
          document.getElementById("feedback").innerHTML =
            "CapsLock not activated";
        }
      }
    </script>
    ```

    **[⬆ Back to Top](#table-of-contents)**

79. ### What is isNaN

    isNaN()方法用来检测值是否是合法数字（非数字）。即，如果值等于NaN（非数字）该函数返回true否则返回false

    ```javascript
    isNaN("Hello"); //true
    isNaN("100"); //false
    ```

    **[⬆ Back to Top](#table-of-contents)**

80. ### What are the differences between undeclared and undefined variables

    下边是未声明（未定义）和undefined变量之间主要的区别

    | undeclared                                               | undefined                             |
    | ------------------------------------------------------- | -------------------------------------- |
    | 这些变量在程序中不存在也未声明                              | 程序中这些变量声明但是未赋值                |
    | 试图读取未声明变量时会遇到运行时错误                         | 读取undefined变量时, 返回undefined值.      |

    **[⬆ Back to Top](#table-of-contents)**

81. ### What are global variables

    全局变量是没有任何作用域在整个代码都可以访问的变量。var关键词用于声明局部变量但是如果省略则会变成全局变量。

    ```javascript
    msg = "Hello"; // var is missing, it becomes global variable
    ```

    **[⬆ Back to Top](#table-of-contents)**

82. ### What are the problems with global variables

    全局变量的问题是局部作用域和全局作用域变量名字冲突。依赖于全局变量的代码很难调试和测试
    

    **[⬆ Back to Top](#table-of-contents)**

83. ### What is NaN property

    NaN属性是代表“非数字”值的全局属性。也就是说，它表示值不是一个合法的数字。程序中很少用到NaN，但是在个别的情形下可以用作返回值

    ```javascript
    Math.sqrt(-1);
    parseInt("Hello");
    ```

    **[⬆ Back to Top](#table-of-contents)**

84. ### What is the purpose of isFinite function

    The isFinite() function is used to determine whether a number is a finite, legal number. It returns false if the value is +infinity, -infinity, or NaN (Not-a-Number), otherwise it returns true.
    isFinite()函数用于判断一个数字是否是一个合法的有限大小的数字。如果值是+infinity, -infinity, 或 NaN（非数字）则返回false，否则返回true

    ```javascript
    isFinite(Infinity); // false
    isFinite(NaN); // false
    isFinite(-Infinity); // false

    isFinite(100); // true
    ```

    **[⬆ Back to Top](#table-of-contents)**

85. ### What is an event flow

    事件流是网页上接收事件的顺序。当你点击了一个内嵌在很多其他元素中的元素时，在你的点击真正到达目标元素之前，必须在它的每个父元素上先触发点击事件，先从全局的window对象开始。
    有两种事件流

    1. 自顶到下(事件捕获)
    2. 自底向上 (事件冒泡)

    **[⬆ Back to Top](#table-of-contents)**

86. ### What is event bubbling

    事件冒泡是一种事件传播类型，其中事件首先在最里边的目标元素上触发，然后按照目标元素的嵌套层级在祖先（父亲）节点上依次向上触发直到到达最外的DOM元素

    **[⬆ Back to Top](#table-of-contents)**

87. ### What is event capturing

    事件捕获是一种事件传播类型，其中事件首先在最外部的元素上触发，然后按照目标元素的嵌套层级在子孙（孩子）节点上依次向下触发直到到达最里边的DOM元素

    **[⬆ Back to Top](#table-of-contents)**

88. ### How do you submit a form using JavaScript

    你可以使用`document.forms[0].submit()`提交表单. 使用onsubmit事件处理函数所有的表单输入信息都会被提交

    ```javascript
    function submit() {
      document.forms[0].submit();
    }
    ```

    **[⬆ Back to Top](#table-of-contents)**

89. ### How do you find operating system details

    window.navigator 对象包含了用户浏览器操作系统细节信息. 一些OS属性可以在platform属性下访问

    ```javascript
    console.log(navigator.platform);
    ```

    **[⬆ Back to Top](#table-of-contents)**

90. ### What is the difference between document load and DOMContentLoaded events

    `DOMContentLoaded` 事件在初始的HTML文档完全加载和解析完后触发，不用等资源（样式表，图片和子窗口）加载完毕. 而load事件是当整个页面加载完包括全部的依赖资源（样式表，图片）后才触发.

    **[⬆ Back to Top](#table-of-contents)**

91. ### What is the difference between native, host and user objects

    `原生对象` 是由ECMAScript标准定义作为JS语言一部分的对象. 例如，String, Math, RegExp, Object, Function 等在ECMAScript标准中定义的核心对象.
    `宿主对象` 是由浏览器或运行时环境（Node）提供的对象。例如window, XmlHttpRequest, DOM 节点等被当做宿主对象.
    `用户对象` 是在js代码中定义的对象。例如，用来表示用户信息的User对象.

    **[⬆ Back to Top](#table-of-contents)**

92. ### What are the tools or techniques used for debugging JavaScript code

    你可以用以下工具或技术来调试javascript

    1. Chrome Devtools
    2. debugger语句
    3. console.log语句

    **[⬆ Back to Top](#table-of-contents)**

93. ### What are the pros and cons of promises over callbacks

    与回调相比，promise的优缺点如下

    **优点:**

    1. It avoids callback hell which is unreadable避免了不可读的回调地狱
    2. 使用.then()能更容易写顺序的异步代码
    3. 使用Promise.all()更容易写并行的异步代码
    4. 解决了回调普遍的问题(太晚太早以及多次调用回调，吞错误/异常)

    **缺点:**

    1. 代码有点复杂
    2. 如果ES6不支持需要加载polyfill

    **[⬆ Back to Top](#table-of-contents)**

94. ### What is the difference between an attribute and a property

    attribute定义于HTML标签上，而property定义在DOM上。例如，下边的HTML元素有两个attribute，type和alue

    ```javascript
    <input type="text" value="Name:">
    ```

    你可以按照下边方法获得attribute值

    ```javascript
    const input = document.querySelector("input");
    console.log(input.getAttribute("value")); // Good morning
    console.log(input.value); // Good morning
    ```

    修改文本字段的值为 “good evening”后，变成像下边这样

    ```javascript
    console.log(input.getAttribute("value")); // Good evening
    console.log(input.value); // Good evening
    ```

    **[⬆ Back to Top](#table-of-contents)**

95. ### What is same-origin policy

    同源策略是一种防止JavaScript进行跨域名请求的一种策略。源被定义为一个URI scheme，主机名和端口号的组合。如果启用此策略，则可以防止一个页面上的恶意脚本使用文档对象模型（DOM）访问另一个网页上的敏感数据

    **[⬆ Back to Top](#table-of-contents)**

96. ### What is the purpose of void 0

    Void(0) 用于防止页面刷新。对于消除非预期的副作用很有用，因为会返回undefined原始值。通常用于HTML文档，在`<a>`元素内使用 href="JavaScript:Void(0);" . 也就是说，当你点击一个链接时，浏览器加载新页面或者刷新同一个页面。但是使用此表达式会阻止该特性.
    例如，下边的链接无需刷新页面就可以通知消息

    ```javascript
    <a href="JavaScript:void(0);" onclick="alert('Well done!')">
      Click Me!
    </a>
    ```

    **[⬆ Back to Top](#table-of-contents)**

97. ### Is JavaScript a compiled or interpreted language

    JavaScript是一种解释型语言，不是编译型语言。浏览器的解释器读取JS代码，逐行解释并运行。现在的浏览器用一种叫做Just-In-Time(JIT)的编译技术，会在代码要执行时将JS编译为可执行的字节码

    **[⬆ Back to Top](#table-of-contents)**

98. ### Is JavaScript a case-sensitive language

    是的，JS是大小写敏感的语言。语言中的关键字，变量，函数和对象名和其他标识符必须用一致的大写字母输入。

    **[⬆ Back to Top](#table-of-contents)**

99. ### Is there any relation between Java and JavaScript

    没有关系，是完全不相关的两种编程语言。但它们像其他很多语言一样都是面对对象编程（OOP）语言，基本的特性上遵循类似的语法（if, else, for, switch, break, continue等）

    **[⬆ Back to Top](#table-of-contents)**

100. ### What are events

     事件是HTML元素上的“东西”。当HTML页面使用了JS时，JS可以对这些事件作出 “反应”。下边是一些HTML事件的例子

     1. 网页加载完毕
     2. 输入框改变
     3. 按钮被点击

     让我们来描述下按钮元素的点击事件行为

     ```javascript
     <!doctype html>
     <html>
      <head>
        <script>
          function greeting() {
            alert('Hello! Good morning');
          }
        </script>
      </head>
      <body>
        <button type="button" onclick="greeting()">Click me</button>
      </body>
     </html>
     ```

     **[⬆ Back to Top](#table-of-contents)**

101. ### Who created javascript

     Brendan Eich在1995年于Netscape Communications工作期间发明了JavaScript语言。最开始是以 `Mocha` 这个名字来开发的，但是后来被Netscape发布beta版时正式命名为`LiveScript`

     **[⬆ Back to Top](#table-of-contents)**

102. ### What is the use of preventDefault method

     若事件是可以被取消的，preventDefault()方法会取消该事件，意味着属于该事件的默认行为或表现不会发生。例如，一般常用于点击提交按钮时阻止提交，点击超链接时阻止打开页面URL

     ```javascript
     document
       .getElementById("link")
       .addEventListener("click", function (event) {
         event.preventDefault();
       });
     ```

     **注意:** 记住不是所有的事件都是可取消的.

     **[⬆ Back to Top](#table-of-contents)**

103. ### What is the use of stopPropagation method

     stopPropagation方法用于从事件链中阻止向上冒泡。例如，下边带有stopPropagation方法的嵌套div在点击嵌套的div（Div1）时阻止了事件传播
     	   **译注：** 应该是阻止的是整个事件传递过程中，该节点之后的事件传递，而不仅仅是冒泡阶段

     ```javascript
     <p>Click DIV1 Element</p>
     <div onclick="secondFunc()">DIV 2
       <div onclick="firstFunc(event)">DIV 1</div>
     </div>

     <script>
     function firstFunc(event) {
       alert("DIV 1");
       event.stopPropagation();
     }

     function secondFunc() {
       alert("DIV 2");
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

104. ### What are the steps involved in return false usage

     The return false statement in event handlers performs the below steps,
     事件处理器中返回false的语句如下执行

     1. 首先会阻止浏览器的默认行为或表现
     2. 阻止事件从DOM中传播
     3. 阻止回调执行并在调用时立即返回

     **[⬆ Back to Top](#table-of-contents)**

105. ### What is BOM

     浏览器对象模型(BOM) 允许JavaScript与浏览器“对话”. window的子属性有navigator, history, screen, location 和 document对象. BOM不是标准化的，不同浏览器也可能不一样.

     ![Screenshot](images/bom.png)

     **[⬆ Back to Top](#table-of-contents)**

106. ### What is the use of setTimeout

     setTimeout() 方法用于在一个指定的毫秒后调用函数或者执行表达式

     ```javascript
     setTimeout(function () {
       console.log("Good morning");
     }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

107. ### What is the use of setInterval

     setInterval() 方法用于在一个指定的时间间隔（毫秒）调用函数或者执行表达式. 例如，让我们使用setInterval方法间隔两秒打印信息

     ```javascript
     setInterval(function () {
       console.log("Good morning");
     }, 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

108. ### Why is JavaScript treated as Single threaded

     JavaScript是单线程语言。因为语言标准不允许程序员编写代码，以便解释器可以在多个线程或进程中并行运行部分代码。而像java, go, C++等语言可以制作多线程和多进程的程序

     **[⬆ Back to Top](#table-of-contents)**

109. ### What is an event delegation

     事件委托是一种监听事件的技术，你可以将父元素内部所有发生的事件都委托给父元素来监听。
     
	  例如，如果你想检测一个特定表单内的字段改变，你可以使用事件委托技术

     ```javascript
     var form = document.querySelector("#registration-form");

     // Listen for changes to fields inside the form
     form.addEventListener(
       "input",
       function (event) {
         // Log the field that was changed
         console.log(event.target);
       },
       false
     );
     ```

     **[⬆ Back to Top](#table-of-contents)**

110. ### What is ECMAScript

     ECMAScript是构成JavaScript基础的脚本语言。ECMAScript由ECMA国际化标准组织在ECMA-262 和 ECMA-402标准中标准化。ECMAScript第一版在1997年发布

     **[⬆ Back to Top](#table-of-contents)**

111. ### What is JSON

     JSON (JavaScript Object Notation)是用于数据交换的轻量级格式。它基于 JavaScript 语言的一个子集，就像在 JavaScript 中构建对象一样

     **[⬆ Back to Top](#table-of-contents)**

112. ### What are the syntax rules of JSON

     下边是JSON的语法规则

     1. 数据是键/值对
     2. 数据由逗号分隔
     3. 花括号承载对象
     4. 方括号承载数组

     **[⬆ Back to Top](#table-of-contents)**

113. ### What is the purpose JSON stringify

     当向web服务器发送数据时，数据必须是字符串格式。你可以使用stringify()将JSON对象转换为字符串达到此目的

     ```javascript
     var userJSON = { name: "John", age: 31 };
     var userString = JSON.stringify(userJSON);
     console.log(userString); //"{"name":"John","age":31}"
     ```

     **[⬆ Back to Top](#table-of-contents)**

114. ### How do you parse JSON string

     当从web服务器接收数据时，数据总是字符串。但是你可以使用parse()方法将字符串转换为javascript对象

     ```javascript
     var userString = '{"name":"John","age":31}';
     var userJSON = JSON.parse(userString);
     console.log(userJSON); // {name: "John", age: 31}
     ```

     **[⬆ Back to Top](#table-of-contents)**

115. ### Why do you need JSON

     当在浏览器和服务器间交换数据时，数据只能是文本。由于JSON是文本，所以很容易可以从服务器收发数据并被任何编程语言用作一种数据格式。

     **[⬆ Back to Top](#table-of-contents)**

116. ### What are PWAs

     渐进式web应用 (PWAs) 是一种通过web分发的移动应用类型, 由常用的web技术包括HTML，CSS和JavaScript构建. PWA部署到服务器, 通过URL访问，并被搜索引擎索引

     **[⬆ Back to Top](#table-of-contents)**

117. ### What is the purpose of clearTimeout method

     clearTimeout() 方法在js中用于清理之前被setTimeout()函数设置过的计时器。也就是说，setTimeout()函数的返回值存储在一个变量中，并传给clearTimeout()函数来清除计时器

     例如，下边的setTimeout方法用来在3秒后展示信息。计时器可以被clearTimeout()方法清除

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg =setTimeout(greeting, 3000);

     }

     function stop() {
         clearTimeout(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

118. ### What is the purpose of clearInterval method

     clearInterval() 方法在js中用于清理之前被setInterval()函数设置过的间隔计时器。也就是说，setInterval()函数的返回值存储在一个变量中，并传给clearInterval()函数来清除计时器

     例如，下边的setInterval方法用来每隔3秒展示信息。间隔计时器可以被clearInterval()方法清除

     ```javascript
     <script>
     var msg;
     function greeting() {
        alert('Good morning');
     }
     function start() {
       msg = setInterval(greeting, 3000);

     }

     function stop() {
         clearInterval(msg);
     }
     </script>
     ```

     **[⬆ Back to Top](#table-of-contents)**

119. ### How do you redirect new page in javascript

     在原生javascript中，你可以使用 window对象的`location`属性重定向到新的网页。语法如下

     ```javascript
     function redirect() {
       window.location.href = "newPage.html";
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

120. ### How do you check whether a string contains a substring

     有三种可能的方法检测字符串是否包含子串

     1. **使用includes:** ES6 提供了`String.prototype.includes` 方法来检测字符串是否包含一个子串

     ```javascript
     var mainString = "hello",
       subString = "hell";
     mainString.includes(subString);
     ```

     1. **使用indexOf:** 在ES5或更旧的环境中，你可以使用 `String.prototype.indexOf` 返回子串的索引. 如果索引值不为-1则意味着子串存在于字符串中

     ```javascript
     var mainString = "hello",
       subString = "hell";
     mainString.indexOf(subString) !== -1;
     ```

     1. **使用正则RegEx:** 更高级的方法是使用正则表达式的test方法(`RegExp.test`), 允许针对正则表达式进行测试

     ```javascript
     var mainString = "hello",
       regex = /hell/;
     regex.test(mainString);
     ```

     **[⬆ Back to Top](#table-of-contents)**

121. ### How do you validate an email in javascript

     在js中使用正则表达式可以校验邮箱。建议在服务端而不是客户端做校验。因为客户端可能禁用js

     ```javascript
     function validateEmail(email) {
       var re =
         /^(([^<>()\[\]\\.,;:\s@"]+(\.[^<>()\[\]\\.,;:\s@"]+)*)|(".+"))@((\[[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\.[0-9]{1,3}\])|(([a-zA-Z\-0-9]+\.)+[a-zA-Z]{2,}))$/;
       return re.test(String(email).toLowerCase());
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

     The above regular expression accepts unicode characters.

122. ### How do you get the current url with javascript

     可以使用`window.location.href` 表达式获取当前的url路径也可以使用相同的表达式更新URL。如果只用来读取也可以使用 `document.URL`，但是该方案在FF（Firefox）中有问题

     ```javascript
     console.log("location.href", window.location.href); // Returns full URL
     ```

     **[⬆ Back to Top](#table-of-contents)**

123. ### What are the various url properties of location object

     下边的 `Location` 对象属性可以被用于访问页面的URL组件

     1. href - 整个URL
     2. protocol - URL的协议
     3. host - URL的主机名和端口
     4. hostname - URL的主机名
     5. port - URL端口
     6. pathname - URL的路径
     7. search - URL的查询部分
     8. hash - URL的锚点部分

     **[⬆ Back to Top](#table-of-contents)**

124. ### How do get query string values in javascript

     你可以在js中使用URLSearchParams来获得查询字符串。让我们看一个从URL查询字符串中获得clientCode值的例子

     ```javascript
     const urlParams = new URLSearchParams(window.location.search);
     const clientCode = urlParams.get("clientCode");
     ```

     **[⬆ Back to Top](#table-of-contents)**

125. ### How do you check if a key exists in an object

     你可以使用三种方法检测键是否存在于对象上

     1. **使用in操作符:** 你可以使用in操作符检测键是否存在

     ```javascript
     "key" in obj;
     ```

     如果想检测键不存在，记住要用取反

     ```javascript
     !("key" in obj);
     ```

     1. **使用hasOwnProperty方法:** 特别可以使用 `hasOwnProperty` 来检测属性是否在对象实例上（非继承属性）

     ```javascript
     obj.hasOwnProperty("key"); // true
     ```

     1. **使用undefined比较:** 如果你访问对象不存在的属性，结果就是undefined. 让我们将属性和undefined来决定属性是否存在

     ```javascript
     const user = {
       name: "John",
     };

     console.log(user.name !== undefined); // true
     console.log(user.nickName !== undefined); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

126. ### How do you loop through or enumerate javascript object

     可以使用 `for-in` 循环来遍历js对象。可以使用 `hasOwnProperty` 方法来确保键是对象本身的属性而非来自原型链。

     ```javascript
     var object = {
       k1: "value1",
       k2: "value2",
       k3: "value3",
     };

     for (var key in object) {
       if (object.hasOwnProperty(key)) {
         console.log(key + " -> " + object[key]); // k1 -> value1 ...
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

127. ### How do you test for an empty object

     基于ECMAScript版本有不同的方案

     1. **使用Object entries(ECMA 7+):** Object.entries的length和构造器类型一起用

     ```javascript
     Object.entries(obj).length === 0 && obj.constructor === Object; // Since date object length is 0, you need to check constructor check as well
     ```

     1. **使用Object keys(ECMA 5+):** Object.keys的length和构造器类型一起用

     ```javascript
     Object.keys(obj).length === 0 && obj.constructor === Object; // Since date object length is 0, you need to check constructor check as well
     ```

     1. **结合for-in 和 hasOwnProperty(Pre-ECMA 5):** for-in循环和hasOwnProperty一起用.

     ```javascript
     function isEmpty(obj) {
       for (var prop in obj) {
         if (obj.hasOwnProperty(prop)) {
           return false;
         }
       }

       return JSON.stringify(obj) === JSON.stringify({});
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

128. ### What is an arguments object

     arguments对象是一个在函数内部可访问的类数组对象，包含传给函数的参数值。例如，让我们看看在sum函数中如何使用arguments

     ```javascript
     function sum() {
       var total = 0;
       for (var i = 0, len = arguments.length; i < len; ++i) {
         total += arguments[i];
       }
       return total;
     }

     sum(1, 2, 3); // returns 6
     ```

     **注意:** 你不能对arguments对象使用数组方法。但是你可以像下边一样将它转换为一个数组

     ```javascript
     var argsArray = Array.prototype.slice.call(arguments);
     ```

     **[⬆ Back to Top](#table-of-contents)**

129. ### How do you make first letter of the string in an uppercase

     你可以创建一个使用数组方法链如charAt, toUpperCase 和 slice方法的函数来生成首字母是大写的字符串。

     ```javascript
     function capitalizeFirstLetter(string) {
       return string.charAt(0).toUpperCase() + string.slice(1);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

130. ### What are the pros and cons of for loop

     for循环是javascript中最常用的遍历语法。既有优点也有缺点

     #### 优点

     1. 所有环境都能工作
     2. 可以使用break和continue控制语句流程

     #### 缺点

     1. 太冗长
     2. 太命令式
     3. 可能会面临一个接一个的错误

     **[⬆ Back to Top](#table-of-contents)**

131. ### How do you display the current date in javascript

     你可以使用 `new Date()` 来生成一个包含当前日期和时间的新的Date对象。例如，让我们以mm/dd/yyyy格式来展示当前日期

     ```javascript
     var today = new Date();
     var dd = String(today.getDate()).padStart(2, "0");
     var mm = String(today.getMonth() + 1).padStart(2, "0"); //January is 0!
     var yyyy = today.getFullYear();

     today = mm + "/" + dd + "/" + yyyy;
     document.write(today);
     ```

     **[⬆ Back to Top](#table-of-contents)**

132. ### How do you compare two date objects

     需要使用date.getTime() 方法来比较日期值而不是比较运算符(==, !=, ===, 和 !== 运算符)

     ```javascript
     var d1 = new Date();
     var d2 = new Date(d1);
     console.log(d1.getTime() === d2.getTime()); //True
     console.log(d1 === d2); // False
     ```

     **[⬆ Back to Top](#table-of-contents)**

133. ### How do you check if a string starts with another string

     你可以使用ECMAScript 6的`String.prototype.startsWith()`方法来检查字符串是否以另一个字符串开头。但是不是所有浏览器都支持。让我们看看如何使用

     ```javascript
     "Good morning".startsWith("Good"); // true
     "Good morning".startsWith("morning"); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

134. ### How do you trim a string in javascript

     JavaScript对字符串类型提供了一个trim方法，能够移除出现在字符串开头或者结尾的任何空格

     ```javascript
     "  Hello World   ".trim(); //Hello World
     ```

     如果你的浏览器（<IE9）不支持此方法，可以用以下polyfill

     ```javascript
     if (!String.prototype.trim) {
       (function () {
         // Make sure we trim BOM and NBSP
         var rtrim = /^[\s\uFEFF\xA0]+|[\s\uFEFF\xA0]+$/g;
         String.prototype.trim = function () {
           return this.replace(rtrim, "");
         };
       })();
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

135. ### How do you add a key value pair in javascript

     向对象中添加新的属性有两种犯法。让我们拿一个简单的对象来解释下边的方法

     ```javascript
     var object = {
       key1: value1,
       key2: value2,
     };
     ```

     1. **使用点符号:** 当你知道属性名时此方法很有用

     ```javascript
     object.key3 = "value3";
     ```

     1. **使用方括号:** 当属性名时动态的时候此方法很有用

     ```javascript
     obj["key3"] = "value3";
     ```

     **[⬆ Back to Top](#table-of-contents)**

136. ### Is the !-- notation represents a special operator

     不是一个特殊的操作符。是两个紧挨着的标准操作符的组合

     1. 逻辑非 (!)
     2. 自减前缀 (--)

     首先将值减一，然后看它是否等于零，来决定真值/假值

     **[⬆ Back to Top](#table-of-contents)**

137. ### How do you assign default values to variables

     You can use the logical or operator `||` in an assignment expression to provide a default value. The syntax looks like as below,
     可以在表达式赋值中使用逻辑或运算符`||`来提供默认值。语法如下

     ```javascript
     var a = b || c;
     ```

     按照上边的表述，如果 'b' 是假值（如果是null, false, undefined, 0, 空字符串, 或 NaN）则变量 'a'的值会是 'c' ，否则 'a'的值会是 'b'
     

     **[⬆ Back to Top](#table-of-contents)**

138. ### How do you define multiline strings

     您可以使用 '\\' 字符后跟行终止符来定义多行字符串字面量

     ```javascript
     var str =
       "This is a \
     very lengthy \
     sentence!";
     ```

     但是入果在'\\'字符后有空格，代码看上去一样，实际会产生语法错误。

     **[⬆ Back to Top](#table-of-contents)**

139. ### What is an app shell model

     application shell (or app shell) 架构是一种构建PWA的方法，能够可靠且快速地加载用户的屏幕，类似于原生应用的体验。不需要网络就能获取首屏的初始HTML很有用
     **[⬆ Back to Top](#table-of-contents)**

140. ### Can we define properties for functions

     我们可以为函数定义属性，因为函数也是对象

     ```javascript
     fn = function (x) {
       //Function code goes here
     };

     fn.name = "John";

     fn.profile = function (y) {
       //Profile code goes here
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

141. ### What is the way to find the number of parameters expected by a function

     你可以使用 `function.length` 语法来找出函数预期接收参数的数量。让我们看一个求和函数`sum`的例子

     ```javascript
     function sum(num1, num2, num3, num4) {
       return num1 + num2 + num3 + num4;
     }
     sum.length; // 4 is the number of parameters expected.
     ```

     **[⬆ Back to Top](#table-of-contents)**

142. ### What is a polyfill

     polyfill是一段在无法原生支持新功能的老版浏览器上提供现代化功能的JS代码。例如，Silverlight插件polyfill可以在微软IE7浏览器上用来模仿HTML Canvas元素的功能

     **[⬆ Back to Top](#table-of-contents)**

143. ### What are break and continue statements

     break语句用来 "跳出"循环。即可以中断遍历并继续执行循环后的代码

     ```javascript
     for (i = 0; i < 10; i++) {
       if (i === 5) {
         break;
       }
       text += "Number: " + i + "<br>";
     }
     ```

     continue语句用来 "跳过去" 循环中的一次迭代。即会中断一次迭代（循环中），如果出现指定条件，继续循环中的下一次迭代

     ```javascript
     for (i = 0; i < 10; i++) {
       if (i === 5) {
         continue;
       }
       text += "Number: " + i + "<br>";
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

144. ### What are js labels

     label语句允许我们给JS中的循环和代码块命名。后续我们可以引用这些标签。例如，下边的带label的代码在值相同时可以避免打印数字

     ```javascript
     var i, j;

     loop1: for (i = 0; i < 3; i++) {
       loop2: for (j = 0; j < 3; j++) {
         if (i === j) {
           continue loop1;
         }
         console.log("i = " + i + ", j = " + j);
       }
     }

     // Output is:
     //   "i = 1, j = 0"
     //   "i = 2, j = 0"
     //   "i = 2, j = 1"
     ```

     **[⬆ Back to Top](#table-of-contents)**

145. ### What are the benefits of keeping declarations at the top

     建议将所有的声明都放在每个脚本或函数的顶部。好处是：

     1. 代码更整洁
     2. 只需在一个地方查找局部变量
     3. 容易避免不想要的全局变量
     4. 减少了不想要的重复声明的可能性

     **[⬆ Back to Top](#table-of-contents)**

146. ### What are the benefits of initializing variables

     由于以下好处，建议初始化变量

     1. 代码更整洁
     2. 只在一个地方初始化变量
     3. 避免代码中的undefined值

     **[⬆ Back to Top](#table-of-contents)**

147. ### What are the recommendations to create new object

     建议避免使用 `new Object()`创建新对象. 相反你可以基于类型来创建对象初始化值

     1. 用{} 而非 new Object()
     2. 用 "" 而非 new String()
     3. 用 0 而不是 new Number()
     4. 用 false 而不是 new Boolean()
     5. 用 [] 而不是 new Array()
     6. 用 /()/ 而不是 new RegExp()
     7. 用 function (){} 而不是 new Function()

     你可以像例子一样定义它们

     ```javascript
     var v1 = {};
     var v2 = "";
     var v3 = 0;
     var v4 = false;
     var v5 = [];
     var v6 = /()/;
     var v7 = function () {};
     ```

     **[⬆ Back to Top](#table-of-contents)**

148. ### How do you define JSON arrays

     JSON数组是在方括号中书写的，数组包含js对象。例如，下边是users的JSON数组

     ```javascript
     "users":[
       {"firstName":"John", "lastName":"Abrahm"},
       {"firstName":"Anna", "lastName":"Smith"},
       {"firstName":"Shane", "lastName":"Warn"}
     ]
     ```

     **[⬆ Back to Top](#table-of-contents)**

149. ### How do you generate random integers

     你可以使用Math.random()和 Math.floor() 来返回随机的整数.例如，如果你想在1和10间生成随机整数，乘积应该是10

     ```javascript
     Math.floor(Math.random() * 10) + 1; // returns a random integer from 1 to 10
     Math.floor(Math.random() * 100) + 1; // returns a random integer from 1 to 100
     ```

     **注意:** Math.random() 返回在0（包括）和1（不包括）间的随机数

     **[⬆ Back to Top](#table-of-contents)**

150. ### Can you write a random integers function to print integers with in a range

     可以创建一个在min和max（都包含）间返回随机整数的随机函数

     ```javascript
     function randomInteger(min, max) {
       return Math.floor(Math.random() * (max - min + 1)) + min;
     }
     randomInteger(1, 100); // returns a random integer from 1 to 100
     randomInteger(1, 1000); // returns a random integer from 1 to 1000
     ```

     **[⬆ Back to Top](#table-of-contents)**

151. ### What is tree shaking

     Tree Shaking 是消除无用代码的一种形式。意味着在构建的过程中无用的模块不会被包含进打包后的文件，正因如此，这项技术依赖于ES2015模块化语法的静态结构（即import和export）。最初，这被 ES2015 的模块打包器`rollip`推广

     **[⬆ Back to Top](#table-of-contents)**

152. ### What is the need of tree shaking

     Tree Shaking可以显著减少任何应用的代码包大小。也就是说，我们通过网络发送的代码越少，应用程序的性能就越好。例如，如果我们使用SPA框架来创建一个 "Hello World"应用，会占用大概几MB，但是但是通过树摇可以将大小变成仅仅几百KB。Tree shaking在Rollup和Webpack构建起中实现 

     **[⬆ Back to Top](#table-of-contents)**

153. ### Is it recommended to use eval

     不建议，这会允许任意代码运行可能引起安全问题。正如我们所知，eval()函数用于将文本当作代码运行，在大多数情况下，没必要这么做

     **[⬆ Back to Top](#table-of-contents)**

154. ### What is a Regular Expression

     正则表达式是一个搜索模式的一串字符。你可以使用这种搜索模式在文本中检索数据。可以被用于全部类型的文本查找和文本替换操作。让我们看下语法格式

     ```javascript
     /pattern/modifiers;
     ```

     例如，大小写敏感的用户名的正则表达式或者搜索模式是

     ```javascript
     /John/i;
     ```

     **[⬆ Back to Top](#table-of-contents)**

155. ### What are the string methods available in Regular expression

     正则表达式有两个字符串方法：search()和replace()
     search()方法使用表达式来搜索匹配的值，并返回匹配的位置

     ```javascript
     var msg = "Hello John";
     var n = msg.search(/John/i); // 6
     ```

     replace()方法用于在模式被替换返回修改后的字符串

     ```javascript
     var msg = "Hello John";
     var n = msg.replace(/John/i, "Buttler"); // Hello Buttler
     ```

     **[⬆ Back to Top](#table-of-contents)**

156. ### What are modifiers in regular expression

     修饰符被用于执行大小写和全局检索。让我们列举一些修饰符

     | Modifier | Description                                             |
     | -------- | ------------------------------------------------------- |
     | i        | 不区分大小写的匹配                       |
     | g        | 进行全局匹配而不是在第一次匹配成功后就停止 |
     | m        | 进行多行匹配                             |

     让我们看一个全局修饰符的例子

     ```javascript
     var text = "Learn JS one by one";
     var pattern = /one/g;
     var result = text.match(pattern); // one,one
     ```

     **[⬆ Back to Top](#table-of-contents)**

157. ### What are regular expression patterns

     正则表达式提供了一组模式以匹配字符。基本上分为三种

     1. **括号:** 这些被用于查找一系列字符
        例如下边是一些用例
        1. [abc]: 用来查找括号内的任意字符（a,b,c）
        2. [0-9]: 用来查找括号间的任意数字
        3. (a|b): 用于查找以 | 分隔的其中之一
     2. **元字符:** 这些是有特殊意义的字符
        例如下边是一些用例
        1. \\d: 用于查找数字
        2. \\s: 用于查找空白字符
        3. \\b: 用于查找单词的开头或结尾
     3. **限定符:** 对于定义数量很有用
        例如下边是一些用例
        1. n+: 用于查找任何包含至少一个 n 的字符串的匹配项
        2. n\*: 用于查找包含零个或多个 n 的任何字符串的匹配项
        3. n?: 用于查找包含零个或一个 n 的任何字符串的匹配项

     **[⬆ Back to Top](#table-of-contents)**

158. ### What is a RegExp object

     RegExp对象是有预定义属性和方法的正则表达式对象。让我们看下RegExp对象的简单用法

     ```javascript
     var regexp = new RegExp("\\w+");
     console.log(regexp);
     // expected output: /\w+/
     ```

     **[⬆ Back to Top](#table-of-contents)**

159. ### How do you search a string for a pattern

     你可以使用正则表达式的test()方法来按模式搜索字符串，并依赖结果返回true或false

     ```javascript
     var pattern = /you/;
     console.log(pattern.test("How are you?")); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

160. ### What is the purpose of exec method

     exec方法的作用类似于test方法，但是它是为一个明确的字符串执行检索匹配并返回结果数组或者null而不是返回true/false

     ```javascript
     var pattern = /you/;
     console.log(pattern.exec("How are you?")); //["you", index: 8, input: "How are you?", groups: undefined]
     ```

     **[⬆ Back to Top](#table-of-contents)**

161. ### How do you change the style of a HTML element

     可以使用js改变HTML元素的内联样式或者classname

     1. **使用 style 属性:** 可以使用style属性修改内联样式

     ```javascript
     document.getElementById("title").style.fontSize = "30px";
     ```

     1. **使用ClassName属性:** 使用className属性很容易修改元素类名

     ```javascript
     document.getElementById("title").className = "custom-title";
     ```

     **[⬆ Back to Top](#table-of-contents)**

162. ### What would be the result of 1+2+'3'

     输出是 `33`。由于`1` 和 `2`是数字值，前两个数字的结果就是数字值 `3`。下一个数字是字符串类型的值，因为数字值 `3` 和字符串类型值 `3` 的加法将成为连接后的值 `33`

     **[⬆ Back to Top](#table-of-contents)**

163. ### What is a debugger statement

     调试器语句调用任何可用的调试功能，如设置断点。如果没有可用的调试功能，该语句会不起作用
     例如，下边的函数中插入了一个调试语句。所以执行会像脚本源码中的断点一样在调试语句处暂停

     ```javascript
     function getProfile() {
       // code goes here
       debugger;
       // code goes here
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

164. ### What is the purpose of breakpoints in debugging

     调试器语句被执行并弹出调试器窗口后，您可以在 javascript 代码中设置断点。每个断点处，js会停止执行，让你检查JS的值。检查过后你可以使用play按钮恢复执行

     **[⬆ Back to Top](#table-of-contents)**

165. ### Can I use reserved words as identifiers

     你不可以使用保留的关键字作为变量，标签，对象或者函数名。让我们看一个简单的例子

     ```javascript
     var else = "hello"; // Uncaught SyntaxError: Unexpected token else
     ```

     **[⬆ Back to Top](#table-of-contents)**

166. ### How do you detect a mobile browser

     你可以使用正则返回true或者false来判断用户是否正在使用移动设备浏览

     ```javascript
     window.mobilecheck = function () {
       var mobileCheck = false;
       (function (a) {
         if (
           /(android|bb\d+|meego).+mobile|avantgo|bada\/|blackberry|blazer|compal|elaine|fennec|hiptop|iemobile|ip(hone|od)|iris|kindle|lge |maemo|midp|mmp|mobile.+firefox|netfront|opera m(ob|in)i|palm( os)?|phone|p(ixi|re)\/|plucker|pocket|psp|series(4|6)0|symbian|treo|up\.(browser|link)|vodafone|wap|windows ce|xda|xiino/i.test(
             a
           ) ||
           /1207|6310|6590|3gso|4thp|50[1-6]i|770s|802s|a wa|abac|ac(er|oo|s\-)|ai(ko|rn)|al(av|ca|co)|amoi|an(ex|ny|yw)|aptu|ar(ch|go)|as(te|us)|attw|au(di|\-m|r |s )|avan|be(ck|ll|nq)|bi(lb|rd)|bl(ac|az)|br(e|v)w|bumb|bw\-(n|u)|c55\/|capi|ccwa|cdm\-|cell|chtm|cldc|cmd\-|co(mp|nd)|craw|da(it|ll|ng)|dbte|dc\-s|devi|dica|dmob|do(c|p)o|ds(12|\-d)|el(49|ai)|em(l2|ul)|er(ic|k0)|esl8|ez([4-7]0|os|wa|ze)|fetc|fly(\-|_)|g1 u|g560|gene|gf\-5|g\-mo|go(\.w|od)|gr(ad|un)|haie|hcit|hd\-(m|p|t)|hei\-|hi(pt|ta)|hp( i|ip)|hs\-c|ht(c(\-| |_|a|g|p|s|t)|tp)|hu(aw|tc)|i\-(20|go|ma)|i230|iac( |\-|\/)|ibro|idea|ig01|ikom|im1k|inno|ipaq|iris|ja(t|v)a|jbro|jemu|jigs|kddi|keji|kgt( |\/)|klon|kpt |kwc\-|kyo(c|k)|le(no|xi)|lg( g|\/(k|l|u)|50|54|\-[a-w])|libw|lynx|m1\-w|m3ga|m50\/|ma(te|ui|xo)|mc(01|21|ca)|m\-cr|me(rc|ri)|mi(o8|oa|ts)|mmef|mo(01|02|bi|de|do|t(\-| |o|v)|zz)|mt(50|p1|v )|mwbp|mywa|n10[0-2]|n20[2-3]|n30(0|2)|n50(0|2|5)|n7(0(0|1)|10)|ne((c|m)\-|on|tf|wf|wg|wt)|nok(6|i)|nzph|o2im|op(ti|wv)|oran|owg1|p800|pan(a|d|t)|pdxg|pg(13|\-([1-8]|c))|phil|pire|pl(ay|uc)|pn\-2|po(ck|rt|se)|prox|psio|pt\-g|qa\-a|qc(07|12|21|32|60|\-[2-7]|i\-)|qtek|r380|r600|raks|rim9|ro(ve|zo)|s55\/|sa(ge|ma|mm|ms|ny|va)|sc(01|h\-|oo|p\-)|sdk\/|se(c(\-|0|1)|47|mc|nd|ri)|sgh\-|shar|sie(\-|m)|sk\-0|sl(45|id)|sm(al|ar|b3|it|t5)|so(ft|ny)|sp(01|h\-|v\-|v )|sy(01|mb)|t2(18|50)|t6(00|10|18)|ta(gt|lk)|tcl\-|tdg\-|tel(i|m)|tim\-|t\-mo|to(pl|sh)|ts(70|m\-|m3|m5)|tx\-9|up(\.b|g1|si)|utst|v400|v750|veri|vi(rg|te)|vk(40|5[0-3]|\-v)|vm40|voda|vulc|vx(52|53|60|61|70|80|81|83|85|98)|w3c(\-| )|webc|whit|wi(g |nc|nw)|wmlb|wonu|x700|yas\-|your|zeto|zte\-/i.test(
             a.substr(0, 4)
           )
         )
           mobileCheck = true;
       })(navigator.userAgent || navigator.vendor || window.opera);
       return mobileCheck;
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

167. ### How do you detect a mobile browser without regexp

     你可以通过简单地遍历一些设备列表检查useragent是否匹配来判断是否是移动端浏览器。这是正则方法的可替代方案

     ```javascript
     function detectmob() {
       if (
         navigator.userAgent.match(/Android/i) ||
         navigator.userAgent.match(/webOS/i) ||
         navigator.userAgent.match(/iPhone/i) ||
         navigator.userAgent.match(/iPad/i) ||
         navigator.userAgent.match(/iPod/i) ||
         navigator.userAgent.match(/BlackBerry/i) ||
         navigator.userAgent.match(/Windows Phone/i)
       ) {
         return true;
       } else {
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

168. ### How do you get the image width and height using JS

     你可以用js的编程方法获取图片并检查维度（宽和高）

     ```javascript
     var img = new Image();
     img.onload = function () {
       console.log(this.width + "x" + this.height);
     };
     img.src = "http://www.google.com/intl/en_ALL/images/logo.gif";
     ```

     **[⬆ Back to Top](#table-of-contents)**

169. ### How do you make synchronous HTTP request

     Browsers provide an XMLHttpRequest object which can be used to make synchronous HTTP requests from JavaScript
     浏览器提供了一个XMLHttpRequest对象可以用于在JS中发送同步HTTP请求

     ```javascript
     function httpGet(theUrl) {
       var xmlHttpReq = new XMLHttpRequest();
       xmlHttpReq.open("GET", theUrl, false); // false for synchronous request
       xmlHttpReq.send(null);
       return xmlHttpReq.responseText;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

170. ### How do you make asynchronous HTTP request

     通过将第三个参数设置为true，浏览器提供了一个XMLHttpRequest对象可以用于在JS中发送异步HTTP请求


     ```javascript
     function httpGetAsync(theUrl, callback) {
       var xmlHttpReq = new XMLHttpRequest();
       xmlHttpReq.onreadystatechange = function () {
         if (xmlHttpReq.readyState == 4 && xmlHttpReq.status == 200)
           callback(xmlHttpReq.responseText);
       };
       xmlHttp.open("GET", theUrl, true); // true for asynchronous
       xmlHttp.send(null);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

171. ### How do you convert date to another timezone in javascript

     你可以使用toLocaleString()方法将日期从一个时区转换为另一个时区。例如，让我们像下边一样将当前日期转换为英国时区

     ```javascript
     console.log(event.toLocaleString("en-GB", { timeZone: "UTC" })); //29/06/2019, 09:56:00
     ```

     **[⬆ Back to Top](#table-of-contents)**

172. ### What are the properties used to get size of window

     你可以使用window对象，document元素和document.body对象上的innerWidth, innerHeight, clientWidth, clientHeight这些属性来获取窗口的大小。让我们结合这些属性来计算窗口或文档的大小

     ```javascript
     var width =
       window.innerWidth ||
       document.documentElement.clientWidth ||
       document.body.clientWidth;

     var height =
       window.innerHeight ||
       document.documentElement.clientHeight ||
       document.body.clientHeight;
     ```

     **[⬆ Back to Top](#table-of-contents)**

173. ### What is a conditional operator in javascript

     条件 (三元) 运算符是唯一一个采用三个操作数作为 if 语句的快捷方式的 JavaScript 运算符

     ```javascript
     var isAuthenticated = false;
     console.log(
       isAuthenticated ? "Hello, welcome" : "Sorry, you are not authenticated"
     ); //Sorry, you are not authenticated
     ```

     **[⬆ Back to Top](#table-of-contents)**

174. ### Can you apply chaining on conditional operator

     你可以在类似于 if ... else if ... else if ... else 链 的条件运算符上条件运算符链

     ```javascript
     function traceValue(someParam) {
       return condition1
         ? value1
         : condition2
         ? value2
         : condition3
         ? value3
         : value4;
     }

     // The above conditional operator is equivalent to:

     function traceValue(someParam) {
       if (condition1) {
         return value1;
       } else if (condition2) {
         return value2;
       } else if (condition3) {
         return value3;
       } else {
         return value4;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

175. ### What are the ways to execute javascript after page load

     你可以使用许多不同的方法在页面加载完后执行js

     1. **window.onload:**

     ```javascript
     window.onload = function ...
     ```

     1. **document.onload:**

     ```javascript
     document.onload = function ...
     ```

     1. **body onload:**

     ```javascript
     <body onload="script();">
     ```

     **[⬆ Back to Top](#table-of-contents)**

176. ### What is the difference between proto and prototype

    `__proto__` 对象是在查找链中用于解析方法等的实际对象. 而`prototype` 是用于使用 new 创建对象时构建 `__proto__` 的对象，

     ```javascript
     new Employee().__proto__ === Employee.prototype;
     new Employee().prototype === undefined;
     ```

     **[⬆ Back to Top](#table-of-contents)**

177. ### Give an example where do you really need semicolon

     在JS中建议每条语句后使用分号。例如，下边的情形会在运行时由于缺少分号抛出一个错误 ".. 不是一个函数"

     ```javascript
     // define a function
     var fn = (function () {
       //...
     })(
       // semicolon missing at this line

       // then execute some code inside a closure
       function () {
         //...
       }
     )();
     ```

     会被当作下边来解释

     ```javascript
     var fn = (function () {
       //...
     })(function () {
       //...
     })();
     ```

     在此情形下，我们将第二个函数作为一个参数传给了第一个函数，然后尝试调用第一个函数作为函数调用后的结果。因此，第二个函数会以运行时的错误"... is not a function"失败结束。

     **[⬆ Back to Top](#table-of-contents)**

178. ### What is a freeze method

     **freeze()**方法用来冻结对象。冻结对象不允许向对象中添加新属性，防止删除和修改已存在属性的可枚举型，可配置性或可写性

     ```javascript
     const obj = {
       prop: 100,
     };

     Object.freeze(obj);
     obj.prop = 200; // Throws an error in strict mode

     console.log(obj.prop); //100
     ```

     **注意:** 如果传入的参数不是对象会引发TypeError 

     **[⬆ Back to Top](#table-of-contents)**

179. ### What is the purpose of freeze method

     下边是使用freeze方法的主要好处

     1. 用于冻结对象和数组
     2. 用于让对象不可变

     **[⬆ Back to Top](#table-of-contents)**

180. ### Why do I need to use freeze method

     在面对对象范式中，现有 API 包含某些不打算在当前上下文之外扩展、修改或重用的元素。因此它的作用就像许多语言中使用的 `final`关键词一样。
     

     **[⬆ Back to Top](#table-of-contents)**

181. ### How do you detect a browser language preference

     可以像下边一样使用navigator对象检测语言偏好

     ```javascript
     var language =
       (navigator.languages && navigator.languages[0]) || // Chrome / Firefox
       navigator.language || // All browsers
       navigator.userLanguage; // IE <= 10

     console.log(language);
     ```

     **[⬆ Back to Top](#table-of-contents)**

182. ### How to convert string to title case with javascript

     首字母大写就是将每个单词的首字母都变成大写。你可以像下边函数一样将字符串转化首字母大写

     ```javascript
     function toTitleCase(str) {
       return str.replace(/\w\S*/g, function (txt) {
         return txt.charAt(0).toUpperCase() + txt.substr(1).toLowerCase();
       });
     }
     toTitleCase("good morning john"); // Good Morning John
     ```

     **[⬆ Back to Top](#table-of-contents)**

183. ### How do you detect javascript disabled in the page

     你可以使用 `<noscript>` 标签来检测js是否开启。`<noscript>` 内的代码块会在JS被禁用时执行，通常用于在页面是JS生成时展示可选内容

     ```javascript
     <script type="javascript">
         // JS related code goes here
     </script>
     <noscript>
         <a href="next_page.html?noJS=true">JavaScript is disabled in the page. Please click Next Page</a>
     </noscript>
     ```

     **[⬆ Back to Top](#table-of-contents)**

184. ### What are various operators supported by javascript

     操作符能操作（数学和逻辑运算）特定的值或者操作数。如下所示，JS支持很多操作符。

     1. **算数运算符:** 包括 + (加),– (减), \* (乘), / (除), % (取模), ++ (自增) 和 –– (自减)
     2. **比较运算符:** 包括 = =(相等),!= (不相等), ===(类型相等), > (大于),> = (大于等于),< (小于),<= (小于等于)
     3. **逻辑运算符:** 包括 &&(逻辑与),||(逻辑或),!(逻辑非)
     4. **赋值运算符:** 包括 = (赋值运算符), += (加法赋值), –= (减法赋值), \*= (乘法赋值), /= (除法赋值), %= (取模赋值)
     5. **三元运算符:** 包括条件(: ?) 运算符
     6. **typeof运算符:** 用于发现变量类型. 语法看上去像 `typeof variable`

     **[⬆ Back to Top](#table-of-contents)**

185. ### What is a rest parameter

     剩余参数是一种处理函数参数的改进方法，它允许我们将不定数量的参数表示为数组。语法如下

     ```javascript
     function f(a, b, ...theArgs) {
       // ...
     }
     ```

     例如，让我们看一个根据动态参数数量来计算取和的例子

     ```javascript
     function total(…args){
     let sum = 0;
     for(let i of args){
     sum+=i;
     }
     return sum;
     }
     console.log(fun(1,2)); //3
     console.log(fun(1,2,3)); //6
     console.log(fun(1,2,3,4)); //13
     console.log(fun(1,2,3,4,5)); //15
     ```

     **注意:** 剩余参数在ES2015或ES6中加入

     **[⬆ Back to Top](#table-of-contents)**

186. ### What happens if you do not use rest parameter as a last argument

     剩余参数应该是最后一个参数，因为它的工作是将剩余所有的参数收集到一个数组中。例如，如果像下边定义的函数则不会工作并抛出错误

     ```javascript
     function someFunc(a,…b,c){
     //You code goes here
     return;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

187. ### What are the bitwise operators available in javascript

     下边是JS中使用的位逻辑运算符列表

     1. 位运算 与  ( & )
     2. 位运算 或 ( | )
     3. 位运算 异或 ( ^ )
     4. 位运算 非 ( ~ )
     5. 左移 ( << )
     6. 带符号的右移 ( >> )
     7. 填充0的右移 ( >>> )

     **[⬆ Back to Top](#table-of-contents)**

188. ### What is a spread operator

     扩展运算符允许可迭代对象（数组/对象/字符串）扩展为单个参数/元素。让我们看下此行为的例子

     ```javascript
     function calculateSum(x, y, z) {
       return x + y + z;
     }

     const numbers = [1, 2, 3];

     console.log(calculateSum(...numbers)); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

189. ### How do you determine whether object is frozen or not

     Object.isFrozen() 方法用来判断一个对象是否冻结。如果下边条件都是true则该对象就是冻结的

     1. 不可扩展
     2. 所有属性都不可配置
     3. 所有的数据属性都不可写
        用法如下

     ```javascript
     const object = {
       property: "Welcome JS world",
     };
     Object.freeze(object);
     console.log(Object.isFrozen(object));
     ```

     **[⬆ Back to Top](#table-of-contents)**

190. ### How do you determine two values same or not using object

     Object.is()方法用来判断两个值是否是相同值。例如，不同类型的值的用法会是

     ```javascript
     Object.is("hello", "hello"); // true
     Object.is(window, window); // true
     Object.is([], []); // false
     ```

     如果其中之一成立则值相等

     1. 都是undefined
     2. 都是 null
     3. 都是 true 或者都是 false
     4. 都是字符串，长度相同，字符顺序也一样
     5. 同一个对象 (意味着对象有同一个引用)
     6. 都是数字且
        都是 +0
        都是 -0
        都是 NaN
        都非0且都不是NaN且都有一样的值

     **[⬆ Back to Top](#table-of-contents)**

191. ### What is the purpose of using object is method

     下边是object的`is`方法的一些应用
     

     1. 用于比较两个字符串
     2. 用于比较两个数字
     3. 用于比较两个数字的极性
     4. 用于比较两个对象

     **[⬆ Back to Top](#table-of-contents)**

192. ### How do you copy properties from one object to other

     你可以使用Object.assign()方法用来从一个或多个源对象中向目标对象中拷贝属性和值。返回具有从目标对象复制的属性和值的目标对象。语法如下

     ```javascript
     Object.assign(target, ...sources);
     ```

     让我们看一个有一个源和目标对象的例子

     ```javascript
     const target = { a: 1, b: 2 };
     const source = { b: 3, c: 4 };

     const returnedTarget = Object.assign(target, source);

     console.log(target); // { a: 1, b: 3, c: 4 }

     console.log(returnedTarget); // { a: 1, b: 3, c: 4 }
     ```

     如上边代码所示，从源到目标都有属性（`b`）所以值被重写

     **[⬆ Back to Top](#table-of-contents)**

193. ### What are the applications of assign method

     下边是Object.assign()方法的主要应用

     1. 用于拷贝对象
     2. 用于同名属性合并对象

     **[⬆ Back to Top](#table-of-contents)**

194. ### What is a proxy object

     Proxy对象用于定义基本操作的自定义行为，如属性查找，赋值，枚举，函数调用等。语法如下

     ```javascript
     var p = new Proxy(target, handler);
     ```

     Let's take an example of proxy object,

     ```javascript
     var handler = {
       get: function (obj, prop) {
         return prop in obj ? obj[prop] : 100;
       },
     };

     var p = new Proxy({}, handler);
     p.a = 10;
     p.b = null;

     console.log(p.a, p.b); // 10, null
     console.log("c" in p, p.c); // false, 100
     ```

     上边代码中，使用了 `get`处理器，定义了操作发生时的代理行为

     **[⬆ Back to Top](#table-of-contents)**

195. ### What is the purpose of seal method

      **Object.seal()**方法通过防止添加新属性并且标记全部已有的属性为不可配置来封闭一个对象。但是只要已存在属性的值可写则可以被改变。让我们看下面的例子来加深对seal()方法的理解

     ```javascript
     const object = {
       property: "Welcome JS world",
     };
     Object.seal(object);
     object.property = "Welcome to object world";
     console.log(Object.isSealed(object)); // true
     delete object.property; // You cannot delete when sealed
     console.log(object.property); //Welcome to object world
     ```

     **[⬆ Back to Top](#table-of-contents)**

196. ### What are the applications of seal method

     下边是Object.seal()方法的主要应用

     1. 用于封闭对象和数组
     2. 用于使对象不可变

     **[⬆ Back to Top](#table-of-contents)**

197. ### What are the differences between freeze and seal methods

     如果使用Object.freeze()冻结了一个对象，则它的属性变成不可变的，什么都不能改变，而如果使用Object.seal()方法封闭了一个对象，则它的已存在的属性可以发生改变

     **[⬆ Back to Top](#table-of-contents)**

198. ### How do you determine if an object is sealed or not

     Object.isSealed()方法用来判断对象是否被封闭。如果下边的条件都满足则对象被封闭

     1. 如果不可扩展
     2. 如果全部属性都是不可配置的
     3. 但是并非不可写）
        让我们看下用法

     ```javascript
     const object = {
       property: "Hello, Good morning",
     };

     Object.seal(object); // Using seal() method to seal the object

     console.log(Object.isSealed(object)); // checking whether the object is sealed or not
     ```

     **[⬆ Back to Top](#table-of-contents)**

199. ### How do you get enumerable key and value pairs

      Object.entries()方法用于返回给定对象自身可枚举字符串形式的属性的[key, value]对，和for...in循环中的顺序一样。让我们看下例子中object.entries()函数的功能

     ```javascript
     const object = {
       a: "Good morning",
       b: 100,
     };

     for (let [key, value] of Object.entries(object)) {
       console.log(`${key}: ${value}`); // a: 'Good morning'
       // b: 100
     }
     ```

     **Note:** The order is not guaranteed as object defined.

     **[⬆ Back to Top](#table-of-contents)**

200. ### What is the main difference between Object.values and Object.entries method

      Object.values()方法的行为类似于Object.entries()方法，但是会返回值的数组而非[key, value]对

     ```javascript
     const object = {
       a: "Good morning",
       b: 100,
     };

     for (let value of Object.values(object)) {
       console.log(`${value}`); // 'Good morning'
       100;
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

201. ### How can you get the list of keys of any object

     你可以使用`Object.keys()`方法用来返回给定对象自有属性名字的数组，和正常遍历一个顺序。例如，你可以获得user对象的键

     ```javascript
     const user = {
       name: "John",
       gender: "male",
       age: 40,
     };

     console.log(Object.keys(user)); //['name', 'gender', 'age']
     ```

     **[⬆ Back to Top](#table-of-contents)**

202. ### How do you create an object with prototype

     Object.create()方法用来创建指定原型对象和属性的新对象。即，它会用已存在的对象作为新创建对象的原型。会返回指定原型对象和属性的新对象

     ```javascript
     const user = {
       name: "John",
       printInfo: function () {
         console.log(`My name is ${this.name}.`);
       },
     };

     const admin = Object.create(user);

     admin.name = "Nick"; // Remember that "name" is a property set on "admin" but not on "user" object

     admin.printInfo(); // My name is Nick
     ```

     **[⬆ Back to Top](#table-of-contents)**

203. ### What is a WeakSet

     WeakSet用来存储弱（弱引用）持有对象的集合。语法如下

     ```javascript
     new WeakSet([iterable]);
     ```

     让我们看下边例子来解释其行为

     ```javascript
     var ws = new WeakSet();
     var user = {};
     ws.add(user);
     ws.has(user); // true
     ws.delete(user); // removes user from the set
     ws.has(user); // false, user has been removed
     ```

     **[⬆ Back to Top](#table-of-contents)**

204. ### What are the differences between WeakSet and Set

     主要区别是Set中对于对象的引用是强引用而WeakSet中的是弱引用。也就是说，WeakSet中的对象在没有其他引用时会被垃圾回收
     其他区别是

     1. Set可以存储任意值而WeakSet只能存储对象集合
     2. WeakSet不像Set一样，没有set属性
     3. WeakSet没有像clear, keys, values, entries, forEach这些方法
     4. WeakSet不可迭代

     **[⬆ Back to Top](#table-of-contents)**

205. ### List down the collection of methods available on WeakSet

     下边是WeakSet上的可用方法

     1. add(value): 用给定的值向weakset中追加新对象
     2. delete(value): 从WeakSet集合中删除值
     3. has(value): 如果WeakSet集合中存在则返回true，否则返回false

     让我们用例子看下上边方法的作用

     ```javascript
     var weakSetObject = new WeakSet();
     var firstObject = {};
     var secondObject = {};
     // add(value)
     weakSetObject.add(firstObject);
     weakSetObject.add(secondObject);
     console.log(weakSetObject.has(firstObject)); //true
     weakSetObject.delete(secondObject);
     ```

     **[⬆ Back to Top](#table-of-contents)**

206. ### What is a WeakMap

     WeakMap对象是键/值对的集合，其中键是弱引用。其中键必须是对象值可以是任意值。语法如下

     ```javascript
     new WeakMap([iterable]);
     ```

     让我们看下边例子来解释它的行为

     ```javascript
     var ws = new WeakMap();
     var user = {};
     ws.set(user);
     ws.has(user); // true
     ws.delete(user); // removes user from the map
     ws.has(user); // false, user has been removed
     ```

     **[⬆ Back to Top](#table-of-contents)**

207. ### What are the differences between WeakMap and Map

     主要区别在于 Map 中对键对象的引用是强引用，而 WeakMap 中key对象的引用是弱引用。也就是说，WeakMap中的键对象在没有其他引用时可以被垃圾回收
     其他区别是

     1. Map可以存储任意键类型而WeakMap只能存储键对象的集合
     2. WeakMap不像Map一样，没有size属性
     3. WeakMap没有像clear, keys, values, entries, forEach一样的方法
     4. WeakMap不可迭代

     **[⬆ Back to Top](#table-of-contents)**

208. ### List down the collection of methods available on WeakMap

     下边是WeakMap上的可用方法

     1. set(key, value): 在WeakMap对象上为键设置值。返回WeakMap对象
     2. delete(key): 删除键关联的任意值
     3. has(key): 返回WeakMap对象上是否有与键关联的值的布尔判断
     4. get(key): 返回与键关联的值，如果没有返回undefined
        让我们通过例子看下上边方法的功能

     ```javascript
     var weakMapObject = new WeakMap();
     var firstObject = {};
     var secondObject = {};
     // set(key, value)
     weakMapObject.set(firstObject, "John");
     weakMapObject.set(secondObject, 100);
     console.log(weakMapObject.has(firstObject)); //true
     console.log(weakMapObject.get(firstObject)); // John
     weakMapObject.delete(secondObject);
     ```

     **[⬆ Back to Top](#table-of-contents)**

209. ### What is the purpose of uneval

     uneval()是内置的函数用来创建一个代表源代码对象的字符串。它是顶级函数不和任何对象关联。让我们看下边的例子来了解更多用法

     ```javascript
     var a = 1;
     uneval(a); // returns a String containing 1
     uneval(function user() {}); // returns "(function user(){})"
     ```

     **[⬆ Back to Top](#table-of-contents)**

210. ### How do you encode an URL

     encodeURI()函数用来编码整个带特殊字符除了（, / ? : @ & = + $ #）的URI

     ```javascript
     var uri = "https://mozilla.org/?x=шеллы";
     var encoded = encodeURI(uri);
     console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
     ```

     **[⬆ Back to Top](#table-of-contents)**

211. ### How do you decode an URL

     decodeURI()函数用来解码之前由encodeURI()创建的统一资源定位符 (URI)

     ```javascript
     var uri = "https://mozilla.org/?x=шеллы";
     var encoded = encodeURI(uri);
     console.log(encoded); // https://mozilla.org/?x=%D1%88%D0%B5%D0%BB%D0%BB%D1%8B
     try {
       console.log(decodeURI(encoded)); // "https://mozilla.org/?x=шеллы"
     } catch (e) {
       // catches a malformed URI
       console.error(e);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

212. ### How do you print the contents of web page

     window对象提供了一个print()方法用来打印当前窗口的内容。会打开一个打印对话框会让你在不同打印选项中选择。让我们看一个print方法用法的例子

     ```html
     <input type="button" value="Print" onclick="window.print()" />
     ```

     **注意:** 在多数浏览器中，打印对话框打开时会阻塞

     **[⬆ Back to Top](#table-of-contents)**

213. ### What is the difference between uneval and eval

     `uneval`函数返回给定对象的源码；而`eval`函数则相反，会在不同内存区中执行那段源代码。让我们看一个表明区别的例子

     ```javascript
     var msg = uneval(function greeting() {
       return "Hello, Good morning";
     });
     var greeting = eval(msg);
     greeting(); // returns "Hello, Good morning"
     ```

     **[⬆ Back to Top](#table-of-contents)**

214. ### What is an anonymous function

     匿名函数是没有名字的函数！匿名函数通常赋值给一个变量名或者用作回调函数。语法如下

     ```javascript
     function (optionalParameters) {
       //do something
     }

     const myFunction = function(){ //Anonymous function assigned to a variable
       //do something
     };

     [1, 2, 3].map(function(element){ //Anonymous function used as a callback function
       //do something
     });
     ```

     让我们看下上边匿名函数的例子

     ```javascript
     var x = function (a, b) {
       return a * b;
     };
     var z = x(5, 10);
     console.log(z); // 50
     ```

     **[⬆ Back to Top](#table-of-contents)**

215. ### What is the precedence order between local and global variables

     同名的局部变量优先级高于全局变量。让我们看一个例子

     ```javascript
     var msg = "Good morning";
     function greeting() {
       msg = "Good Evening";
       console.log(msg);
     }
     greeting();
     ```

     **[⬆ Back to Top](#table-of-contents)**

216. ### What are javascript accessors

     ECMAScript 5引入了对象访问器或通过getter和setter的计算属性。Getter使用`get`关键字而setter使用`set`关键字

     ```javascript
     var user = {
       firstName: "John",
       lastName : "Abraham",
       language : "en",
       get lang() {
         return this.language;
       }
       set lang(lang) {
       this.language = lang;
       }
     };
     console.log(user.lang); // getter access lang as en
     user.lang = 'fr';
     console.log(user.lang); // setter used to set lang as fr
     ```

     **[⬆ Back to Top](#table-of-contents)**

217. ### How do you define property on Object constructor

     Object.defineProperty()静态方法用来在一个对象上直接定义新属性，或者修改对象上已有的属性，返回该对象。让我们看个例子来学习如何定义属性

     ```javascript
     const newObject = {};

     Object.defineProperty(newObject, "newProperty", {
       value: 100,
       writable: false,
     });

     console.log(newObject.newProperty); // 100

     newObject.newProperty = 200; // It throws an error in strict mode due to writable setting
     ```

     **[⬆ Back to Top](#table-of-contents)**

218. ### What is the difference between get and defineProperty

     除非你使用类，否则两者有类似的结果。如果使用 `get` 属性将在对象的原型上定义，而使用 `Object.defineProperty()` 属性将在它应用到的实例上定义

     **[⬆ Back to Top](#table-of-contents)**

219. ### What are the advantages of Getters and Setters

     下边是getter和setter的好处

     1. 提供了更简单的语法
     2. 用来定义计算属性或者JS中的访问器
     3. 有助于提供属性和方法之间的等价关系
     4. 可以提供更好的数据质量
     5. 有助于使用封装后的逻辑在幕后做事

     **[⬆ Back to Top](#table-of-contents)**

220. ### Can I add getters and setters using defineProperty method

     你可以使用`Object.defineProperty()`方法增加getter和setter。例如，下边的计数器对象使用了increment, decrement, add 和 subtract 属性
     
     ```javascript
     var obj = { counter: 0 };

     // Define getters
     Object.defineProperty(obj, "increment", {
       get: function () {
         this.counter++;
       },
     });
     Object.defineProperty(obj, "decrement", {
       get: function () {
         this.counter--;
       },
     });

     // Define setters
     Object.defineProperty(obj, "add", {
       set: function (value) {
         this.counter += value;
       },
     });
     Object.defineProperty(obj, "subtract", {
       set: function (value) {
         this.counter -= value;
       },
     });

     obj.add = 10;
     obj.subtract = 5;
     console.log(obj.increment); //6
     console.log(obj.decrement); //5
     ```

     **[⬆ Back to Top](#table-of-contents)**

221. ### What is the purpose of switch-case

     JS中的switch case语句用于决策。在只有几个case的情况下，使用switch case语句比if-else语句更方便。语法如下

     ```javascript
     switch (expression)
     {
         case value1:
             statement1;
             break;
         case value2:
             statement2;
             break;
         .
         .
         case valueN:
             statementN;
             break;
         default:
             statementDefault;
     }
     ```

     上边的多路分支语句在表达式值的基础上提供了调度执行不同代码部分的简单方法

     **[⬆ Back to Top](#table-of-contents)**

222. ### What are the conventions to be followed for the usage of switch case

     以下是英注意的注意事项
     

     1. 表达式是数字或字符串类型
     2. 重复的值不能用于表达式
     3. default语句是可选的。如果传给switch的表达式不匹配任何case值，则default中的语句会被执行
     4. break语句用来在switch内部终止语句序列
     5. break语句是可选的。如果忽略，则会在下个case中继续执行

     **[⬆ Back to Top](#table-of-contents)**

223. ### What are primitive data types

     原始数据类型是有原始值（没有属性或方法）的数组。有7种原始数据类型

     1. string
     2. number
     3. boolean
     4. null
     5. undefined
     6. bigint
     7. symbol

     **[⬆ Back to Top](#table-of-contents)**

224. ### What are the different ways to access object properties

     有3中方法访问对象属性

     1. **.符号:** 使用符号.来访问属性

     ```javascript
     objectName.property;
     ```

     2. **方括号符号:** 使用方括号访问属性

     ```javascript
     objectName["property"];
     ```

     3. **表达式符号:** 使用方括号中的表达式

     ```javascript
     objectName[expression];
     ```

     **[⬆ Back to Top](#table-of-contents)**

225. ### What are the function parameter rules

     JS函数参数遵循以下规则

     1. 函数定义不给参数指定数据类型
     2. 传入的参数不进行类型检查
     3. 不检查接收参数的数量
        即下边的函数遵循上边的规则

     ```javascript
     function functionName(parameter1, parameter2, parameter3) {
       console.log(parameter1); // 1
     }
     functionName(1);
     ```

     **[⬆ Back to Top](#table-of-contents)**

226. ### What is an error object

     error对象是内置的错误对象，当产生错误时提供错误信息。有两个属性：name和message。例如，下边的函数打印了错误详情

     ```javascript
     try {
       greeting("Welcome");
     } catch (err) {
       console.log(err.name + "<br>" + err.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

227. ### When you get a syntax error

     当你尝试运行有语法错误时会抛出SyntaxError。例如，下边的函数参数缺少引号会抛出语法错误

     ```javascript
     try {
       eval("greeting('welcome)"); // Missing ' will produce an error
     } catch (err) {
       console.log(err.name);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

228. ### What are the different error names from error object

     从错误对象返回的错误名称有 6 种不同类型
     
     | error名字 | 描述 |
     |---- | ---------
     | EvalError | eval()函数中产生的错误 |
     | RangeError | 数字"越界"时产生的错误 |
     | ReferenceError | 非法引用产生的错误|
     | SyntaxError | 语法错误|
     | TypeError | 类型错误 |
     | URIError | 由encodeURI()产生的错误 |

     **[⬆ Back to Top](#table-of-contents)**

229. ### What are the various statements in error handling

     下边是错误处理中用到的语句

     1. **try:** 此语句用于测试错误的代码块
     2. **catch:** 此语句用于处理错误
     3. **throw:** 此语句用于创建自定义错误
     4. **finally:** 此语句用于在try catch后不管结果如何都执行代码

     **[⬆ Back to Top](#table-of-contents)**

230. ### What are the two types of loops in javascript

     1. **入口控制循环:** 此循环类型中，测试条件在进入循环体前检测。例如，for和while都是这种遍历
     2. **出口控制循环:** 此循环类型中，测试条件在执行完循环体后检测。即循环体无论检测条件是true还是false都会执行至少一次。例如，do-while是这种遍历
 
     **[⬆ Back to Top](#table-of-contents)**

231. ### What is nodejs

     Node.js是建立在Chrome的JavaScript运行时之上的平台，用于能简单地构建快速且可扩展的网络应用。是在Google的V8 JS引擎和libuv库之上的基于事件，非阻塞，异步I/0的运行时

     **[⬆ Back to Top](#table-of-contents)**

232. ### What is an Intl object

     Intl对象是ECMAScript国际化API的命名空间，提供语言敏感的字符串比较、数字格式化以及日期和时间格式化。提供了访问几种构造函数和语言敏感函数的功能

     **[⬆ Back to Top](#table-of-contents)**

233. ### How do you perform language specific date and time formatting

     你可以使用`Intl.DateTimeFormat`对象，它是启用语言敏感日期和时间格式化的对象的构造函数。让我们用例子看下用法

     ```javascript
     var date = new Date(Date.UTC(2019, 07, 07, 3, 0, 0));
     console.log(new Intl.DateTimeFormat("en-GB").format(date)); // 07/08/2019
     console.log(new Intl.DateTimeFormat("en-AU").format(date)); // 07/08/2019
     ```

     **[⬆ Back to Top](#table-of-contents)**

234. ### What is an Iterator

     迭代器是一个定义了一个序列的对象，也是在终止时返回的值。实现了Iterator协议的`next()`方法，会返回有两个属性的对象：`value`（序列中的下一个值）和 `done`（如果序列中的最后一个值被消费掉则是true）。

     **[⬆ Back to Top](#table-of-contents)**

235. ### How does synchronous iteration works

     同步迭代在ES6中引入，由以下组件一起组成工作。

     **Iterable:** 它是一个可以通过键为 Symbol.iterator 的方法进行迭代的对象
     **Iterator:** 它是通过在可迭代对象上调用 `[Symbol.iterator]()` 返回的对象。这个迭代器对象将每个被迭代的元素包装在一个对象中，并通过 `next()` 方法一一返回
     **IteratorResult:** 是由`next()`方法返回的对象。对象包括两个属性；`value` 属性包含一个被迭代的元素，而 `done` 属性确定该元素是否是最后一个元素

     下边让我们用一个数组来解释同步迭代

     ```javascript
     const iterable = ["one", "two", "three"];
     const iterator = iterable[Symbol.iterator]();
     console.log(iterator.next()); // { value: 'one', done: false }
     console.log(iterator.next()); // { value: 'two', done: false }
     console.log(iterator.next()); // { value: 'three', done: false }
     console.log(iterator.next()); // { value: 'undefined, done: true }
     ```

     **[⬆ Back to Top](#table-of-contents)**

236. ### What is an event loop

     事件循环是回调函数的队列。当异步函数执行时，回调函数入队。JavaScript引擎在异步函数执行完代码前不会开始处理事件循环
     **注意:** 即使JS是单线程的也允许Node.js执行非阻塞的I/O操作

     **[⬆ Back to Top](#table-of-contents)**

237. ### What is call stack

     调用栈是js在程序中追踪函数执行（创建执行上下文）的数据结构。主要有两个行为

     1. 无论何时调用函数执行时，会将函数入栈
     2. 无论何时函数执行完毕，此函数都会出栈

     让我们举个例子，它是图表形式的状态表示
     

     ```javascript
     function hungry() {
       eatFruits();
     }
     function eatFruits() {
       return "I'm eating fruits";
     }

     // Invoke the `hungry` function
     hungry();
     ```

     上边代码在调用栈的处理过程如下

     1. 将`hungry()`函数加入调用栈列表并执行代码
     2. 将`eatFruits()`函数加入调用栈列表并执行代码
     3. 从调用栈列表中删除`eatFruits()`函数
     4. 从调用栈列表中删除`hungry()`函数，因此调用栈中没东西了

     ![Screenshot](images/call-stack.png)

     **[⬆ Back to Top](#table-of-contents)**

238. ### What is an event queue

     **[⬆ Back to Top](#table-of-contents)**

239. ### What is a decorator

     装饰器是一个表达式，它等价于一个将目标、名称和装饰器描述符作为参数的函数。此外，它还可以选择返回一个装饰器描述符以安装在目标对象上。让我们在设计时为user类定义admin装饰器

     ```javascript
     function admin(isAdmin) {
        return function(target) {
            target.isAdmin = isAdmin;
        }
     }

     @admin(true)
     class User() {
     }
     console.log(User.isAdmin); //true

      @admin(false)
      class User() {
      }
      console.log(User.isAdmin); //false
     ```

     **[⬆ Back to Top](#table-of-contents)**

240. ### What are the properties of Intl object

     下边是Intl对象上可用的属性

     1. **Collator:** 这些是开启语言敏感的字符串比较的对象
     2. **DateTimeFormat:** 这些是开启语言敏感日期和时间格式化的对象
     3. **ListFormat:** 这些是开启语言敏感列表格式化的对象
     4. **NumberFormat:** 开启语言敏感的数字格式化的对象
     5. **PluralRules:** 启用复数敏感格式和特定​​语言规则的对象
     6. **RelativeTimeFormat:** 开启语言敏感相对时间格式化的对象

     **[⬆ Back to Top](#table-of-contents)**

241. ### What is an Unary operator

     一元（+）运算符用来将变量转换为数字。如果变量不能被转换，则会成为值是NaN的数字。让我们在指令中看下此行为

     ```javascript
     var x = "100";
     var y = +x;
     console.log(typeof x, typeof y); // string, number

     var a = "Hello";
     var b = +a;
     console.log(typeof a, typeof b, b); // string, number, NaN
     ```

     **[⬆ Back to Top](#table-of-contents)**

242. ### How do you sort elements in an array

     sort()方法用来对数组元素进行原地排序并返回排序后的数组。例子用法如下

     ```javascript
     var months = ["Aug", "Sep", "Jan", "June"];
     months.sort();
     console.log(months); //  ["Aug", "Jan", "June", "Sep"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

243. ### What is the purpose of compareFunction while sorting arrays

     compareFunction用于定义排序顺序。如果忽略，则数组元素将被转换成字符串，然后根据每个字符的Unicode码点值进行排序。让我们看个例子的用法

     ```javascript
     let numbers = [1, 2, 5, 3, 4];
     numbers.sort((a, b) => b - a);
     console.log(numbers); // [5, 4, 3, 2, 1]
     ```

     **[⬆ Back to Top](#table-of-contents)**

244. ### How do you reversing an array

     你可以使用reverse()方法来对数组元素进行反转。此方法对于降序数组很有用，让我们看看例子中reverse()方法的用法。

     ```javascript
     let numbers = [1, 2, 5, 3, 4];
     numbers.sort((a, b) => b - a);
     numbers.reverse();
     console.log(numbers); // [1, 2, 3, 4 ,5]
     ```

     **[⬆ Back to Top](#table-of-contents)**

245. ### How do you find min and max value in an array

     你可以对数组变量使用`Math.min` 和 `Math.max`方法找到数组内的最大值和最小值。让我们创建两个找数组中最大值和最小值的函数

     ```javascript
     var marks = [50, 20, 70, 60, 45, 30];
     function findMin(arr) {
       return Math.min.apply(null, arr);
     }
     function findMax(arr) {
       return Math.max.apply(null, arr);
     }

     console.log(findMin(marks));
     console.log(findMax(marks));
     ```

     **[⬆ Back to Top](#table-of-contents)**

246. ### How do you find min and max values without Math functions

     您可以编写循环遍历数组的函数，将每个值与最小值或最大值进行比较，以找到最小值和最大值。让我们创建找最小值和最大值的函数

     ```javascript
     var marks = [50, 20, 70, 60, 45, 30];
     function findMin(arr) {
       var length = arr.length;
       var min = Infinity;
       while (length--) {
         if (arr[length] < min) {
           min = arr[len];
         }
       }
       return min;
     }

     function findMax(arr) {
       var length = arr.length;
       var max = -Infinity;
       while (len--) {
         if (arr[length] > max) {
           max = arr[length];
         }
       }
       return max;
     }

     console.log(findMin(marks));
     console.log(findMax(marks));
     ```

     **[⬆ Back to Top](#table-of-contents)**

247. ### What is an empty statement and purpose of it

     空语句是一个分号（;）表明没有语句要执行，即使JavaScript需要一个。因为空语句没有指令执行你可能认为没啥用，但是空语句在当你创建一个空循环体的循环时有时很有用。例如，你可以像下边一样用0来初始化数组

     ```javascript
     // Initialize an array a
     for(int i=0; i < a.length; a[i++] = 0) ;
     ```

     **[⬆ Back to Top](#table-of-contents)**

248. ### How do you get metadata of a module

     您可以使用 `import.meta` 对象，它是一种将特定上下文的元数据暴露给 JavaScript 模块的元属性。它包含当前模块的信息，例如模块的URL。浏览器中，你可以获得与NodeJS不同的元信息。

     ```javascript
     <script type="module" src="welcome-module.js"></script>;
     console.log(import.meta); // { url: "file:///home/user/welcome-module.js" }
     ```

     **[⬆ Back to Top](#table-of-contents)**

249. ### What is a comma operator

     逗号运算符用于从左到右计算每个操作数并返回最后一个操作数的值。这和数组，对象和函数参数中的逗号完全不一样。例如，数字表达式的用法如下

     ```javascript
     var x = 1;
     x = (x++, x);

     console.log(x); // 2
     ```

     **[⬆ Back to Top](#table-of-contents)**

250. ### What is the advantage of a comma operator

     它通常用于在需要单个表达式的位置包含多个表达式。逗号运算符常见的用法之一是在`for`循环中提供多个参数。例如，下边的循环在一个地方中用逗号表达式使用了多个表达式

     ```javascript
     for (var a = 0, b =10; a <= 10; a++, b--)
     ```

     您还可以在 return 语句中使用逗号运算符，它会在返回之前进行处理

     ```javascript
     function myFunction() {
       var a = 1;
       return (a += 10), a; // 11
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

251. ### What is typescript

	  TypeScript 是由微软创建的 JavaScript 的类型化超集，它添加了可选类型、类、async/await 和许多其他功能，并编译为纯 JavaScript。Angular完全由TypeScript构建并被用作主要语言。你可以像下边一样全局安装
	  
     ```bash
     npm install -g typescript
     ```

     让我们看一个TypeScript用法的简单例子

     ```typescript
     function greeting(name: string): string {
       return "Hello, " + name;
     }

     let user = "Sudheer";

     console.log(greeting(user));
     ```

     greeting方法只允许字符串类型的参数

     **[⬆ Back to Top](#table-of-contents)**

252. ### What are the differences between javascript and typescript

     下边是javascript 和 typescript间一系列差别

     | 特性                 | typescript                            | javascript             |
     | ------------------- | ------------------------------------- | ---------------------- |
     | 语言范式              | 面向对象的编程语言                      | 脚本语言                 |
     | 类型支持              | 支持静态类型                            | 有动态类型              |
     | 模块化                | 支持                                   | 不支持                 |
     | 接口                 | 有接口的概念                             | 不支持接口              |
     | 可选参数               | 函数支持可选参数                        | 函数不支持可选参数        |

     **[⬆ Back to Top](#table-of-contents)**

253. ### What are the advantages of typescript over javascript

     下边是与js相比ts的优点

     1. TypeScript能在开发时期发现编译时错误，能确保更少的运行时错误。而js是解释型语言
     2. TypeScript是强类型或支持静态类型从而在编译期允许检查类型正确性。js没有此功能
     3. TypeScript编译期可以将 .ts 文件编译成ES3,ES4 和 ES5，不像ES6的js功能可能在一些浏览器下不被支持

     **[⬆ Back to Top](#table-of-contents)**

254. ### What is an object initializer

     对象初始化器是描述了一个对象的初始化的表达式。此表达式的语法表示为以逗号分隔的零对或多对属性名称和对象关联值的列表，用花括号 ({}) 括起来。也叫做字面量符号。是创建对象方法之一

     ```javascript
     var initObject = { a: "John", b: 50, c: {} };

     console.log(initObject.a); // John
     ```

     **[⬆ Back to Top](#table-of-contents)**

255. ### What is a constructor method

     构造函数是用于在类内部创建和初始化对象的特殊方法。如果你不指定一个构造函数，默认的构造函数会被使用。下边是构造函数用法的例子

     ```javascript
     class Employee {
       constructor() {
         this.name = "John";
       }
     }

     var employeeObject = new Employee();

     console.log(employeeObject.name); // John
     ```

     **[⬆ Back to Top](#table-of-contents)**

256. ### What happens if you write constructor more than once in a class

     类中的 "constructor" 是一个特殊方法，只应该在类中被定义一次。也就是说，如果在类中书写超过一次构造器函数，会抛出一个语法错误 `SyntaxError`

     ```javascript
      class Employee {
        constructor() {
          this.name = "John";
        }
        constructor() {   //  Uncaught SyntaxError: A class may only have one constructor
          this.age = 30;
        }
      }

      var employeeObject = new Employee();

      console.log(employeeObject.name);
     ```

     **[⬆ Back to Top](#table-of-contents)**

257. ### How do you call the constructor of a parent class

     你可以使用`super`关键字来调用父类的构造函数。记住 `super()` 必须在使用 'this' 引用前调用。否则会引起引用错误。让我们看下用法

     ```javascript
     class Square extends Rectangle {
       constructor(length) {
         super(length, length);
         this.name = "Square";
       }

       get area() {
         return this.width * this.height;
       }

       set area(value) {
         this.area = value;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

258. ### How do you get the prototype of an object

     你可以使用 `Object.getPrototypeOf(obj)` 方法返回指定对象的原型。即内部的 `prototype`属性值。如果没有继承的属性则返回 `null`值

     ```javascript
     const newPrototype = {};
     const newObject = Object.create(newPrototype);

     console.log(Object.getPrototypeOf(newObject) === newPrototype); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

259. ### What happens If I pass string type for getPrototype method

     在ES5中，如果obj参数不是对象会抛出类型错误。而在ES2015中，参数会被强转成一个 `Object`

     ```javascript
     // ES5
     Object.getPrototypeOf("James"); // TypeError: "James" is not an object
     // ES2015
     Object.getPrototypeOf("James"); // String.prototype
     ```

     **[⬆ Back to Top](#table-of-contents)**

260. ### How do you set prototype of one object to another

     你可以使用 `Object.setPrototypeOf()` 方法设置一个指定的对象的原型（即内部的 `prototype` 属性）到另一个对象或null。例如，可以像下边一样将square的对象的原型设置为rectangle对象的原型

     ```javascript
     Object.setPrototypeOf(Square.prototype, Rectangle.prototype);
     Object.setPrototypeOf({}, null);
     ```

     **[⬆ Back to Top](#table-of-contents)**

261. ### How do you check whether an object can be extendable or not

     `Object.isExtensible()`方法用来判断对象是否可扩展。即是否能添加新属性

     ```javascript
     const newObject = {};
     console.log(Object.isExtensible(newObject)); //true
     ```

     **注意:** 默认全部对象都是可扩展的。即可以先加或修改新属性

     **[⬆ Back to Top](#table-of-contents)**

262. ### How do you prevent an object to extend

     `Object.preventExtensions()`方法用来防止新属性添加到对象上。换句话说，他会防止未来对对象的扩展。让我们看下这个属性的用法

     ```javascript
     const newObject = {};
     Object.preventExtensions(newObject); // NOT extendable

     try {
       Object.defineProperty(newObject, "newProperty", {
         // Adding new property
         value: 100,
       });
     } catch (e) {
       console.log(e); // TypeError: Cannot define property newProperty, object is not extensible
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

263. ### What are the different ways to make an object non-extensible

     你可以使用三种方法将对象标记为不可扩展

     1. Object.preventExtensions
     2. Object.seal
     3. Object.freeze

     ```javascript
     var newObject = {};

     Object.preventExtensions(newObject); // Prevent objects are non-extensible
     Object.isExtensible(newObject); // false

     var sealedObject = Object.seal({}); // Sealed objects are non-extensible
     Object.isExtensible(sealedObject); // false

     var frozenObject = Object.freeze({}); // Frozen objects are non-extensible
     Object.isExtensible(frozenObject); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

264. ### How do you define multiple properties on an object

     `Object.defineProperties()`方法用来直接在对象上定义新的或者修改已有属性并返回此对象。让我们在空对象上定义多个属性

     ```javascript
     const newObject = {};

     Object.defineProperties(newObject, {
       newProperty1: {
         value: "John",
         writable: true,
       },
       newProperty2: {},
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

265. ### What is MEAN in javascript

       MEAN（MongoDB、Express、AngularJS 和 Node.js）技术栈是最流行的开源 JavaScript 软件技术堆栈，可用于构建动态 Web 应用程序，可以在其中全都使用JavaScript编写 Web 项目的服务器端和客户端部分

     **[⬆ Back to Top](#table-of-contents)**

266. ### What Is Obfuscation in javascript

     混淆是故意创造人类难以理解的混淆过的 javascript 代码（即源代码或机器代码）的行为。类似于加密，但机器可以理解代码并执行
     下边让我们看一个混淆前的函数

     ```javascript
     function greeting() {
       console.log("Hello, welcome to JS world");
     }
     ```

     代码混淆后，长下边这样

     ```javascript
     eval(
       (function (p, a, c, k, e, d) {
         e = function (c) {
           return c;
         };
         if (!"".replace(/^/, String)) {
           while (c--) {
             d[c] = k[c] || c;
           }
           k = [
             function (e) {
               return d[e];
             },
           ];
           e = function () {
             return "\\w+";
           };
           c = 1;
         }
         while (c--) {
           if (k[c]) {
             p = p.replace(new RegExp("\\b" + e(c) + "\\b", "g"), k[c]);
           }
         }
         return p;
       })(
         "2 1(){0.3('4, 7 6 5 8')}",
         9,
         9,
         "console|greeting|function|log|Hello|JS|to|welcome|world".split("|"),
         0,
         {}
       )
     );
     ```

     **[⬆ Back to Top](#table-of-contents)**

267. ### Why do you need Obfuscation

     下边是需要混淆的几个原因

     1. 减少代码大小。所以服务端和客户端的数据传输会更快
     2. 它向外界隐藏业务逻辑并保护代码免受其他人的影响
     3. 逆向工程会更困难
     4. 减少下载时间

     **[⬆ Back to Top](#table-of-contents)**

268. ### What is Minification

     压缩是删除所有不必要的字符（删除空格）的过程，并且重命名变量而不改变其功能。这也是一种混淆

     **[⬆ Back to Top](#table-of-contents)**

269. ### What are the advantages of minification

     Normally it is recommended to use minification for heavy traffic and intensive requirements of resources. It reduces file sizes with below benefits,
     通常建议使用压缩来处理大流量和密集的资源需求。它减少了文件大小，具有以下好处

     1. 减少网页加载时间
     2. 节省宽带使用

     **[⬆ Back to Top](#table-of-contents)**

270. ### What are the differences between Obfuscation and Encryption

     下边是混淆和加密间的主要区别

     | 特性                          | 混淆                            | 压缩                                                 |
     | ------------------------- ---| ------------------------------- | -------------------------------------------------- |
     | 定义                          | 改变任意数据形式                 | 使用密钥将信息的形式变成不可读的格式                                        |
     | 解码的密钥                     | 不需要密钥就能解码               | 需要密钥                                              |
     | 目标数据格式                   | 会变成更复杂的形式                | 转换成不可读的格式                                     |

     **[⬆ Back to Top](#table-of-contents)**

271. ### What are the common tools used for minification

     有许多在线/离线工具可以压缩js文件

     1. Google's Closure Compiler
     2. UglifyJS2
     3. jsmin
     4. javascript-minifier.com/
     5. prettydiff.com

     **[⬆ Back to Top](#table-of-contents)**

272. ### How do you perform form validation using javascript

     JS可以用来进行HTML表单校验。例如，如果表单字段为空，函数需要通知并返回false来防止表单被提交
    	   让我们用html表单进行用户登录

     ```html
     <form name="myForm" onsubmit="return validateForm()" method="post">
       User name: <input type="text" name="uname" />
       <input type="submit" value="Submit" />
     </form>
     ```

     用户登录的校验如下

     ```javascript
     function validateForm() {
       var x = document.forms["myForm"]["uname"].value;
       if (x == "") {
         alert("The username shouldn't be empty");
         return false;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

273. ### How do you perform form validation without javascript

     不使用js也可以自动进行HTML表单校验。通过应用 `required` 属性启用验证，以防止在输入为空时提交表单

     ```html
     <form method="post">
       <input type="text" name="uname" required />
       <input type="submit" value="Submit" />
     </form>
     ```

     **注意:** 自动化的表单校验在IE9或之前版本不会生效

     **[⬆ Back to Top](#table-of-contents)**

274. ### What are the DOM methods available for constraint validation

     以下 DOM 方法可用于对无效输入进行约束验证

     1. checkValidity(): 如果输入框元素包含合法数据会返回true
     2. setCustomValidity(): It is used to set the validationMessage property of an input element.用于向输入框元素设置validationMessage属性
        让我们使用带有 DOM 验证的用户登录表单

     ```javascript
     function myFunction() {
       var userName = document.getElementById("uname");
       if (!userName.checkValidity()) {
         document.getElementById("message").innerHTML =
           userName.validationMessage;
       } else {
         document.getElementById("message").innerHTML =
           "Entered a valid username";
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

275. ### What are the available constraint validation DOM properties

     下面是一些可用的约束校验 DOM 属性的列表

     1. validity: 提供了一系列与输入框元素有效性相关的布尔属性
     2. validationMessage: 校验为false时展示消息
     3. willValidate: 表明一个输入框元素是否会被校验

     **[⬆ Back to Top](#table-of-contents)**

276. ### What are the list of validity properties

     输入框元素的validity属性提供了一组与数据有效性相关的属性

     1. customError: 如果设置了自定义的有效性消息则返回true
     2. patternMismatch: 若元素的值不匹配pattern属性则返回true
     3. rangeOverflow: 如果元素值大于max属性则返回true
     4. rangeUnderflow: 如果元素值小于min属性则返回true

     5. stepMismatch: 如果元素值根据step属性不合法则返回true
     6. tooLong: 若元素值超出maxLength属性则返回true
     7. typeMismatch: 如果元素值根据type属性不合法则返回true
     8. valueMissing: 如果带required属性的元素没有值则返回true
     9. valid: 如果元素值非法，则返回true

     **[⬆ Back to Top](#table-of-contents)**

277. ### Give an example usage of rangeOverflow property

     如果一个元素值大于它的max属性则rangeOverflow属性会返回true。例如，如果值大于100下边的表单提交会抛出一个错误

     ```html
     <input id="age" type="number" max="100" />
     <button onclick="myOverflowFunction()">OK</button>
     ```

     ```javascript
     function myOverflowFunction() {
       if (document.getElementById("age").validity.rangeOverflow) {
         alert("The mentioned age is not allowed");
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

278. ### Is enums feature available in javascript

     js本身不支持枚举。但是有许多不同的方案来模拟，即使可能不完全等价。例如，你可以freeze或seal一个对象

     ```javascript
     var DaysEnum = Object.freeze({"monday":1, "tuesday":2, "wednesday":3, ...})
     ```

     **[⬆ Back to Top](#table-of-contents)**

279. ### What is an enum

     枚举是一种将变量限制为一组预定义常量中的一个值的类型。 JavaScript 没有枚举，但 typescript 提供内置的枚举支持

     ```javascript
     enum Color {
      RED, GREEN, BLUE
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

280. ### How do you list all properties of an object

     你可以使用`Object.getOwnPropertyNames()`方法返回给定对象上本身拥有的全部属性。让我们用一个例子看下用法

     ```javascript
     const newObject = {
       a: 1,
       b: 2,
       c: 3,
     };

     console.log(Object.getOwnPropertyNames(newObject));
     ["a", "b", "c"];
     ```

     **[⬆ Back to Top](#table-of-contents)**

281. ### How do you get property descriptors of an object

     你可以使用`Object.getOwnPropertyDescriptors()`方法返回给定对象的全部属性描述符。此方法的事例用法如下

     ```javascript
     const newObject = {
       a: 1,
       b: 2,
       c: 3,
     };
     const descriptorsObject = Object.getOwnPropertyDescriptors(newObject);
     console.log(descriptorsObject.a.writable); //true
     console.log(descriptorsObject.a.configurable); //true
     console.log(descriptorsObject.a.enumerable); //true
     console.log(descriptorsObject.a.value); // 1
     ```

     **[⬆ Back to Top](#table-of-contents)**

282. ### What are the attributes provided by a property descriptor

     属性描述符是拥有如下属性的记录

     1. value: 与属性相关联的值
     2. writable: 决定与属性相关的值是否能被改变
     3. configurable: 如果属性描述符可以被改变且属性可以从相应的对象中删除，则返回true
     4. enumerable: 决定在枚举相应对象的属性期间是否出现该属性
     5. set: 提供给此属性的setter函数
     6. get: 提供给此属性的getter函数

     **[⬆ Back to Top](#table-of-contents)**

283. ### How do you extend classes

     `extends` 关键字在类声明/表达式中用于创建一个类，该类是另一个类的子类。它可用于子类化自定义类以及内置对象。语法如下

     ```javascript
     class ChildClass extends ParentClass { ... }
     ```

     让我们看一个从Rectangle父类中继承来的Square子类

     ```javascript
     class Square extends Rectangle {
       constructor(length) {
         super(length, length);
         this.name = "Square";
       }

       get area() {
         return this.width * this.height;
       }

       set area(value) {
         this.area = value;
       }
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

284. ### How do I modify the url without reloading the page

     `window.location.url`属性修改url很有用但是会重载页面。HTML5引入了`history.pushState()`和`history.replaceState()`方法，允许你分别添加和修改历史条目。例如，你可以像下边一样使用pushState

     ```javascript
     window.history.pushState("page2", "Title", "/page2.html");
     ```

     **[⬆ Back to Top](#table-of-contents)**

285. ### How do you check whether an array includes a particular value or not

     `Array#includes()`方法通过返回true或者false用来判断数组是否包含特定的值。让我们看一个在数组内部找到一个元素（数字和字符串）的例子
     
     ```javascript
     var numericArray = [1, 2, 3, 4];
     console.log(numericArray.includes(3)); // true

     var stringArray = ["green", "yellow", "blue"];
     console.log(stringArray.includes("blue")); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

286. ### How do you compare scalar arrays

     你可以使用数组的length和every方法比较两个标量数组（直接使用 ===）。这些表达式的组合可以给出预期的结果

     ```javascript
     const arrayFirst = [1, 2, 3, 4, 5];
     const arraySecond = [1, 2, 3, 4, 5];
     console.log(
       arrayFirst.length === arraySecond.length &&
         arrayFirst.every((value, index) => value === arraySecond[index])
     ); // true
     ```

     如果想比较数组而不考虑顺序，那么应该先对它们进行排序

     ```javascript
     const arrayFirst = [2, 3, 1, 4, 5];
     const arraySecond = [1, 2, 3, 4, 5];
     console.log(
       arrayFirst.length === arraySecond.length &&
         arrayFirst.sort().every((value, index) => value === arraySecond[index])
     ); //true
     ```

     **[⬆ Back to Top](#table-of-contents)**

287. ### How to get the value from get parameters

      `new URL()` 对象接收url字符串，该对象的`searchParams`属性可以用来访问get参数。记住，你需要在老式i浏览器（包括IE）中使用polyfill或者 `window.location`来访问URL

     ```javascript
     let urlString = "http://www.some-domain.com/about.html?x=1&y=2&z=3"; //window.location.href
     let url = new URL(urlString);
     let parameterZ = url.searchParams.get("z");
     console.log(parameterZ); // 3
     ```

     **[⬆ Back to Top](#table-of-contents)**

288. ### How do you print numbers with commas as thousand separators


     你可以使用`Number.prototype.toLocaleString()`方法返回一个带有语言敏感表示的字符串，例如该数字的千位分隔符、货币等

     ```javascript
     function convertToThousandFormat(x) {
       return x.toLocaleString(); // 12,345.679
     }

     console.log(convertToThousandFormat(12345.6789));
     ```

     **[⬆ Back to Top](#table-of-contents)**

289. ### What is the difference between java and javascript

     两者是完全不相关的编程语言，它们之间没有关系。 Java 是静态类型的、编译语言、在它自己的VM上运行。而 Javascript 是在浏览器和 nodejs 环境中动态类型、解释和运行的。让我们用表格格式看看主要区别
     | 特性 | Java | JavaScript |
     |---- | ---- | -----
     | 类型 | 强类型语言 | 动态类型语言 |
     | 范式 | 面对对象编程 | 基于原型的编程 |
     | 作用域 | 块作用域 | 函数作用域 |
     | 并发性 | 基于线程 | 基于事件 |
     | 内存 | 使用更多的内存 | 使用更少的内存。因此被用于网页 |

     **[⬆ Back to Top](#table-of-contents)**

290. ### Does JavaScript supports namespace

     JavaScript默认不支持命名空间。所以如果创建任何元素（函数，方法，对象，变量），则会变成全局的并污染全局命名空间。让我们看一个没有命名空间定义两个函数的例子

     ```javascript
     function func1() {
       console.log("This is a first definition");
     }
     function func1() {
       console.log("This is a second definition");
     }
     func1(); // This is a second definition
     ```

     总是会调用第二个函数定义。此种情况，命名空间会解决名字冲突问题

     **[⬆ Back to Top](#table-of-contents)**

291. ### How do you declare namespace

     尽管JavaScript缺少命名空间，我们可以使用对象，IIEF创建命名空间

     1. **使用对象字面量符号:** 让我们将变量和函数包裹在对象字面量语法中，表现就和命名空间一样。之后就可以使用对象符号来访问

     ```javascript
     var namespaceOne = {
        function func1() {
            console.log("This is a first definition");
        }
     }
     var namespaceTwo = {
          function func1() {
              console.log("This is a second definition");
          }
      }
     namespaceOne.func1(); // This is a first definition
     namespaceTwo.func1(); // This is a second definition
     ```

     1. **使用 IIFE (立即执行函数表达式):** IIFE外层的括号为内部所有代码创建了一个局部作用域，并使得匿名函数成为一个函数表达式。因此，您可以在两个不同的函数表达式中创建相同的函数来充当命名空间

     ```javascript
     (function () {
       function fun1() {
         console.log("This is a first definition");
       }
       fun1();
     })();

     (function () {
       function fun1() {
         console.log("This is a second definition");
       }
       fun1();
     })();
     ```

     1. **使用块和 let/const声明:** 在ECMAScript 6中，你可以简单使用块和let声明将变量的作用域限制到块内

     ```javascript
     {
       let myFunction = function fun1() {
         console.log("This is a first definition");
       };
       myFunction();
     }
     //myFunction(): ReferenceError: myFunction is not defined.

     {
       let myFunction = function fun1() {
         console.log("This is a second definition");
       };
       myFunction();
     }
     //myFunction(): ReferenceError: myFunction is not defined.
     ```

     **[⬆ Back to Top](#table-of-contents)**

292. ### How do you invoke javascript code in an iframe from parent page

     最初需要使用 `document.getElementBy` 或 `window.frames` 访问 iFrame。之后 iFrame 的 `contentWindow` 属性提供了对 targetFunction 的访问权限

     ```javascript
     document.getElementById("targetFrame").contentWindow.targetFunction();
     window.frames[0].frameElement.contentWindow.targetFunction(); // Accessing iframe this way may not work in latest versions chrome and firefox
     ```

     **[⬆ Back to Top](#table-of-contents)**

293. ### How do get the timezone offset from date

     可以使用日期对象的 `getTimezoneOffset` 方法。此方法返回从当前时区（主机系统设置）到 UTC 时区的以分钟为单位的差值

     ```javascript
     var offset = new Date().getTimezoneOffset();
     console.log(offset); // -480
     ```

     **[⬆ Back to Top](#table-of-contents)**

294. ### How do you load CSS and JS files dynamically

     可以在 DOM 中创建链接和脚本元素，并将它们作为子元素append到 head 标签。让我们创建一个函数来添加脚本和样式资源，如下所示

     ```javascript
     function loadAssets(filename, filetype) {
       if (filetype == "css") {
         // External CSS file
         var fileReference = document.createElement("link");
         fileReference.setAttribute("rel", "stylesheet");
         fileReference.setAttribute("type", "text/css");
         fileReference.setAttribute("href", filename);
       } else if (filetype == "js") {
         // External JavaScript file
         var fileReference = document.createElement("script");
         fileReference.setAttribute("type", "text/javascript");
         fileReference.setAttribute("src", filename);
       }
       if (typeof fileReference != "undefined")
         document.getElementsByTagName("head")[0].appendChild(fileReference);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

295. ### What are the different methods to find HTML elements in DOM

     如果想在HTML页面中访问任何元素，需要从访问document对象开始。之后就可以使用下边任意一种方法找到HTML元素

     1. document.getElementById(id): It finds an element by Id
     2. document.getElementsByTagName(name): It finds an element by tag name
     3. document.getElementsByClassName(name): It finds an element by class name

     **[⬆ Back to Top](#table-of-contents)**

296. ### What is jQuery

     jQuery 是一个流行的跨浏览器 JavaScript 库，它通过最小化跨浏览器的差异来提供文档对象模型 (DOM) 遍历、事件处理、动画和 AJAX 交互。它以“Write less, do more”的理念而广为人知。例如，您可以使用 jQuery 在页面加载时显示欢迎消息，如下所示

     ```javascript
     $(document).ready(function () {
       // It selects the document and apply the function on page load
       alert("Welcome to jQuery world");
     });
     ```

     **Note:** You can download it from jquery's official site or install it from CDNs, like google.

     **[⬆ Back to Top](#table-of-contents)**

297. ### What is V8 JavaScript engine

     V8 是 Google Chrome 浏览器使用的开源高性能 JavaScript 引擎，用 C++ 编写。它也被用于 node.js 项目。它实现了 ECMAScript 和 WebAssembly，并在 Windows 7 或更高版本、macOS 10.12+ 以及使用 x64、IA-32、ARM 或 MIPS 处理器的 Linux 系统上运行
     **注意:** 可以独立运行，或者可以被嵌入到任意C++应用中

     **[⬆ Back to Top](#table-of-contents)**

298. ### Why do we call javascript as dynamic language

     JavaScript 是一种松散类型或动态语言，因为 JavaScript 中的变量不直接与任何特定的值类型相关联，并且任何变量都可以分配/重新分配所有类型的值

     ```javascript
     let age = 50; // age is a number now
     age = "old"; // age is a string now
     age = true; // age is a boolean
     ```

     **[⬆ Back to Top](#table-of-contents)**

299. ### What is a void operator

     `void` 运算符对给定表达式求值，然后返回 undefined（即，没有返回值）。语法如下

     ```javascript
     void expression;
     void expression;
     ```

     让我们不用任何重定向或重载展示一条消息

     ```javascript
     <a href="javascript:void(alert('Welcome to JS world'))">
       Click here to see a message
     </a>
     ```

     **注意:** T该运算符通常使用“void(0)”获取undefined原始值，

     **[⬆ Back to Top](#table-of-contents)**

300. ### How to set the cursor to wait

     可以在JavaScript中使用“cursor”属性将光标设置为wait。让我们使用以下函数在页面加载时执行此行为

     ```javascript
     function myFunction() {
       window.document.body.style.cursor = "wait";
     }
     ```

     此函数在页面加载完毕后执行

     ```html
     <body onload="myFunction()"></body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

301. ### How do you create an infinite loop

     你可以使用不带任何表达式的for和while循环来创建无限循环。对于ESLint和代码优化工具而言，for 循环解构或语法是更好的方法

     ```javascript
     for (;;) {}
     while (true) {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

302. ### Why do you need to avoid with statement

     JavaScript的with语句旨在为编写对对象的重复访问提供简写。因此，它可以通过减少重复冗长的对象引用来帮助减小文件大小，而不会降低性能。我们举个例子，它用于在多次访问一个对象时避免冗余

     ```javascript
     a.b.c.greeting = "welcome";
     a.b.c.age = 32;
     ```

     使用 `with` 会变成：

     ```javascript
     with (a.b.c) {
       greeting = "welcome";
       age = 32;
     }
     ```

     但是 `with` 语句会产生性能问题，因为我们无法预测一个参数是引用一个真实的变量还是引用 with 参数中的一个属性

     **[⬆ Back to Top](#table-of-contents)**

303. ### What is the output of below for loops

     ```javascript
     for (var i = 0; i < 4; i++) {
       // global scope
       setTimeout(() => console.log(i));
     }

     for (let i = 0; i < 4; i++) {
       // block scope
       setTimeout(() => console.log(i));
     }
     ```

     上边的for循环输出是 4 4 4 4 和 0 1 2 3

     **解释:** 由于 javascript 的事件队列/循环，在循环执行后会调用 `setTimeout` 回调函数。由于变量 i 是使用 `var` 关键字声明的，因此它成为全局变量，并且在调用 `setTimeout` 函数时迭代值等于 4。因此，第一个循环的输出是`4 4 4 4`

     而在第二个循环中，变量 i 被声明是 `let` 关键字声明的，它成为块级作用域的变量，并且每次迭代都保存一个新值（0, 1, 2, 3）。因此，第一个循环的输出是`0 1 2 3`

     **[⬆ Back to Top](#table-of-contents)**

304. ### List down some of the features of ES6

     下边是一些ES6特性

     1. 支持常量或不可变变量
     2. 支持块级作用域的变量，常量和函数
     3. 箭头函数
     4. 默认函数
     5. 剩余和扩展参数
     6. 模板字面量
     7. 多行字符串
     8. 解构赋值
     9. 增强对象字面量
     10. Promises
     11. 类
     12. 模块

     **[⬆ Back to Top](#table-of-contents)**

305. ### What is ES6

     ES6 是 JavaScript 语言的第六版，于 2015 年 6 月发布。最初称为 ECMAScript 6 (ES6)，后来更名为 ECMAScript 2015。几乎所有现代浏览器都支持 ES6，但对于旧浏览器，有许多转译器，如 Babel.js 等

     **[⬆ Back to Top](#table-of-contents)**

306. ### Can I redeclare let and const variables

     不可以重复声明let和const变量。如果这么做会抛出下边的错误。

     ```bash
     Uncaught SyntaxError: Identifier 'someVariable' has already been declared
     ```

     **解释:** `var` 关键字声明的变量作用在函数作用域，并且由于变量提升特性，该变量被视为在封闭作用域的顶部声明。因此，所有对同一个提升变量的多个声明都不会有任何错误。让我们举一个例子，为 var 和 let/const 变量在同一作用域内重新声明变量

     ```javascript
     var name = "John";
     function myFunc() {
       var name = "Nick";
       var name = "Abraham"; // Re-assigned in the same function block
       alert(name); // Abraham
     }
     myFunc();
     alert(name); // John
     ```

     The block-scoped multi-declaration throws syntax error,

     ```javascript
     let name = "John";
     function myFunc() {
       let name = "Nick";
       let name = "Abraham"; // Uncaught SyntaxError: Identifier 'name' has already been declared
       alert(name);
     }

     myFunc();
     alert(name);
     ```

     **[⬆ Back to Top](#table-of-contents)**

307. ### Is const variable makes the value immutable

     const变量不会使值不可变。但是会禁止接下来的赋值（即可以在声明时赋值但是之后不可以赋另一个值）

     ```javascript
     const userList = [];
     userList.push("John"); // Can mutate even though it can't re-assign
     console.log(userList); // ['John']
     ```

     **[⬆ Back to Top](#table-of-contents)**

308. ### What are default parameters

     在IS5中，我们需要依赖逻辑或运算符处理函数参数的默认值。然而在ES6中，默认的函数参数特性允许在没有值传入或者是undefined时用默认值来初始化。让我们用例子来比较该行为

     ```javascript
     //ES5
     var calculateArea = function (height, width) {
       height = height || 50;
       width = width || 60;

       return width * height;
     };
     console.log(calculateArea()); //300
     ```

     默认参数让初始化更简单

     ```javascript
     //ES6
     var calculateArea = function (height = 50, width = 60) {
       return width * height;
     };

     console.log(calculateArea()); //300
     ```

     **[⬆ Back to Top](#table-of-contents)**

309. ### What are template literals

     模板字面量或者模板字符串是允许嵌入表达式的字符串字面量。这些用反引号 (`) 字符而不是双引号或单引号括起来
     在ES6中，此功能允许使用如下动态表达式

     ```javascript
     var greeting = `Welcome to JS World, Mr. ${firstName} ${lastName}.`;
     ```

     在ES5中，你需要像下边一样分割字符串

     ```javascript
     var greeting = 'Welcome to JS World, Mr. ' + firstName + ' ' + lastName.`
     ```

     **Note:** You can use multi-line strings and string interpolation features with template literals.

     **[⬆ Back to Top](#table-of-contents)**

310. ### How do you write multi-line strings in template literals

     在ES5中，必须使用换行符转义字符（'\\n'）和连接符号（+）才能得到多行字符串

     ```javascript
     console.log("This is string sentence 1\n" + "This is string sentence 2");
     ```

     而在ES6中，无需使用任何换行符

     ```javascript
     console.log(`This is string sentence
     'This is string sentence 2`);
     ```

     **[⬆ Back to Top](#table-of-contents)**

311. ### What are nesting templates

     嵌套模板是模板字面量语法中支持的一项功能，允许在模板内占位符 ${ } 内使用内部反引号。例如，下面的嵌套模板用于根据用户权限显示图标，而外部模板检查平台类型

     ```javascript
     const iconStyles = `icon ${
       isMobilePlatform()
         ? ""
         : `icon-${user.isAuthorized ? "submit" : "disabled"}`
     }`;
     ```

     也可以在不嵌套模板功能的情况下编写上述用例。但是，嵌套模板功能更加紧凑和可读

     ```javascript
     //Without nesting templates
      const iconStyles = `icon ${ isMobilePlatform() ? '' :
       (user.isAuthorized ? 'icon-submit' : 'icon-disabled'}`;
     ```

     **[⬆ Back to Top](#table-of-contents)**

312. ### What are tagged templates

         带标签的模板是模板的高级形式，其中标签允许使用函数解析模板字面量。 tag 函数接受第一个参数作为字符串数组，其余参数作为表达式。此函数还可以返回基于参数的操作字符串。让我们看看组织中 IT 专业技能集的这种标记模板行为的用法

     ```javascript
     var user1 = "John";
     var skill1 = "JavaScript";
     var experience1 = 15;

     var user2 = "Kane";
     var skill2 = "JavaScript";
     var experience2 = 5;

     function myInfoTag(strings, userExp, experienceExp, skillExp) {
       var str0 = strings[0]; // "Mr/Ms. "
       var str1 = strings[1]; // " is a/an "
       var str2 = strings[2]; // "in"

       var expertiseStr;
       if (experienceExp > 10) {
         expertiseStr = "expert developer";
       } else if (skillExp > 5 && skillExp <= 10) {
         expertiseStr = "senior developer";
       } else {
         expertiseStr = "junior developer";
       }

       return `${str0}${userExp}${str1}${expertiseStr}${str2}${skillExp}`;
     }

     var output1 = myInfoTag`Mr/Ms. ${user1} is a/an ${experience1} in ${skill1}`;
     var output2 = myInfoTag`Mr/Ms. ${user2} is a/an ${experience2} in ${skill2}`;

     console.log(output1); // Mr/Ms. John is a/an expert developer in JavaScript
     console.log(output2); // Mr/Ms. Kane is a/an junior developer in JavaScript
     ```

     **[⬆ Back to Top](#table-of-contents)**

313. ### What are raw strings

     ES6 使用 `String.raw()` 方法提供了原始字符串功能，用于获取模板字符串的原始字符串形式。此功能允许您在输入原始字符串时访问它们，而无需处理转义序列。例如，用法如下

     ```javascript
     var calculationString = String.raw`The sum of numbers is \n${
       1 + 2 + 3 + 4
     }!`;
     console.log(calculationString); // The sum of numbers is \\n10!
     ```

     如果不使用原始字符串，换行字符将被显示在多行的输出中

     ```javascript
     var calculationString = `The sum of numbers is \n${1 + 2 + 3 + 4}!`;
     console.log(calculationString);
     // The sum of numbers is
     // 10
     ```

     并且，raw属性可以通过标签函数中的第一个参数访问

     ```javascript
     function tag(strings) {
       console.log(strings.raw[0]);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

314. ### What is destructuring assignment

     解构赋值是一个 JavaScript 表达式，它可以将数组中的值或对象中的属性拆包到不同的变量中
     让我们使用结构赋值从数组中获得月份值

     ```javascript
     var [one, two, three] = ["JAN", "FEB", "MARCH"];

     console.log(one); // "JAN"
     console.log(two); // "FEB"
     console.log(three); // "MARCH"
     ```

     可以使用解构赋值获得对象中的用户属性

     ```javascript
     var { name, age } = { name: "John", age: 32 };

     console.log(name); // John
     console.log(age); // 32
     ```

     **[⬆ Back to Top](#table-of-contents)**

315. ### What are default values in destructuring assignment

     当解构赋值时从数组或对象解包的值为undefined时，可以为变量分配默认值。它有助于避免为每个赋值单独设置默认值。让我们以数组和对象用例为例

     **数组结构:**

     ```javascript
     var x, y, z;

     [x = 2, y = 4, z = 6] = [10];
     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```

     **对象结构:**

     ```javascript
     var { x = 2, y = 4, z = 6 } = { x: 10 };

     console.log(x); // 10
     console.log(y); // 4
     console.log(z); // 6
     ```

     **[⬆ Back to Top](#table-of-contents)**

316. ### How do you swap variables in destructuring assignment

     If you don't use destructuring assignment, swapping two values requires a temporary variable. Whereas using a destructuring feature, two variable values can be swapped in one destructuring expression. Let's swap two number variables in array destructuring assignment,
     如果不使用解构赋值，交换两个变量需要一个临时变量。而使用解构赋值功能，一个结构表达式就可以交换两个变量。

     ```javascript
     var x = 10,
       y = 20;

     [x, y] = [y, x];
     console.log(x); // 20
     console.log(y); // 10
     ```

     **[⬆ Back to Top](#table-of-contents)**

317. ### What are enhanced object literals

     对象字面量通过花括号内的属性很容易快速创建对象。例如，下边为一般的对象属性定义提供了简写语法

     ```javascript
     //ES6
     var x = 10,
       y = 20;
     obj = { x, y };
     console.log(obj); // {x: 10, y:20}
     //ES5
     var x = 10,
       y = 20;
     obj = { x: x, y: y };
     console.log(obj); // {x: 10, y:20}
     ```

     **[⬆ Back to Top](#table-of-contents)**

318. ### What are dynamic imports

     使用 `import()` 函数语法的动态导入允许我们使用 Promise 或 async/await 语法按需加载模块。目前，此功能在[stage4 proposal](https://github.com/tc39/proposal-dynamic-import)。动态导入的主要优点是减少打包后的文件大小，请求的响应的大小/载荷以及在用户体验上的整体改进
     动态导入的语法如下

     ```javascript
     import("./Module").then((Module) => Module.method());
     ```

     **[⬆ Back to Top](#table-of-contents)**

319. ### What are the use cases for dynamic imports

     下边是使用动态导入而非静态导入的一些用例

     1. 按需或有条件地导入一个模块。例如，如果想在老式浏览器中加载polyfill

     ```javascript
     if (isLegacyBrowser()) {
         import(···)
         .then(···);
     }
     ```

     2. 运行时计算模块名字。例如你可以用来进行国际化

     ```javascript
     import(`messages_${getLocale()}.js`).then(···);
     ```

     3. 从常规脚本而非模块中导入模块

     **[⬆ Back to Top](#table-of-contents)**

320. ### What are typed arrays

     类型化数组是ECMAScript 6 API中用于处理二进制数据的类数组对象。JavaScript提供了8种类型化数组类型

     1. Int8Array: 8位有符号整数数组
     2. Int16Array: 16位有符号整数数组
     3. Int32Array: 32位有符号整数数组
     4. Uint8Array: 8位无符号整数数组
     5. Uint16Array: 16位无符号整数数组
     6. Uint32Array: 32位无符号整数数组
     7. Float32Array: 32位浮点型数字数组
     8. Float64Array: 64位浮点型数字数组
 
     例如，可以像下边一样创建一个8位有符号整数数组

     ```javascript
     const a = new Int8Array();
     // You can pre-allocate n bytes
     const bytes = 1024;
     const a = new Int8Array(bytes);
     ```

     **[⬆ Back to Top](#table-of-contents)**

321. ### What are the advantages of module loaders

     模块加载器提供了下边的特性

     1. 动态加载
     2. 状态隔离
     3. 全局命名空间隔离
     4. 编译hooks
     5. 嵌套虚拟化

     **[⬆ Back to Top](#table-of-contents)**

322. ### What is collation

     排序规则用于对一组字符串进行排序并在一组字符串中进行搜索。它由语言环境参数化并知道Unicode。让我们看下比较和排序功能

     1. **比较:**

     ```javascript
     var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(l10nDE.compare("ä", "z") === -1); // true
     console.log(l10nSV.compare("ä", "z") === +1); // true
     ```

     1. **排序:**

     ```javascript
     var list = ["ä", "a", "z"]; // In German,  "ä" sorts with "a" Whereas in Swedish, "ä" sorts after "z"
     var l10nDE = new Intl.Collator("de");
     var l10nSV = new Intl.Collator("sv");
     console.log(list.sort(l10nDE.compare)); // [ "a", "ä", "z" ]
     console.log(list.sort(l10nSV.compare)); // [ "a", "z", "ä" ]
     ```

     **[⬆ Back to Top](#table-of-contents)**

323. ### What is for...of statement

     for...of 语句创建一个循环迭代可迭代对象或元素，例如内置字符串、数组、类数组对象（如arguments或 NodeList）、TypedArray、Map、Set 和用户定义的可迭代对象。数组for...of语句的基本用法如下

     ```javascript
     let arrayIterable = [10, 20, 30, 40, 50];

     for (let value of arrayIterable) {
       value++;
       console.log(value); // 11 21 31 41 51
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

324. ### What is the output of below spread operator array

     ```javascript
     [..."John Resig"];
     ```

     数组的输出是 ['J', 'o', 'h', 'n', '', 'R', 'e', 's', 'i', 'g']
     **解释:** 字符串是可迭代类型，数组中的展开运算符将可迭代的每个字符映射为一个元素。因此，字符串的每个字符都成为数组中的一个元素

     **[⬆ Back to Top](#table-of-contents)**

325. ### Is PostMessage secure

     是的，只要程序员/开发人员仔细检查收到的消息源的源头，postMessages 就可以被认为是非常安全的。但是，如果尝试在未验证其来源的情况下发送/接收消息，则会产生跨站点脚本攻击

     **[⬆ Back to Top](#table-of-contents)**

326. ### What are the problems with postmessage target origin as wildcard

     postMessage 方法的第二个参数指定允许哪个源接收消息。如果您使用通配符 “\*” 作为参数，那么任何源都可以接收消息。在这种情况下，发送者窗口在发送消息时无法知道目标窗口是否是目标源。如果目标窗口已导航到另一个源，则另一个源将接收数据。因此，这可能会导致 XSS 漏洞

     ```javascript
     targetWindow.postMessage(message, "*");
     ```

     **[⬆ Back to Top](#table-of-contents)**

327. ### How do you avoid receiving postMessages from attackers

     由于监听器监听任何消息，因此攻击者可以通过从攻击者的源发送消息来欺骗应用程序，这给人的感觉就是接收者从实际发送者的窗口接收到消息。您可以通过使用 “message.origin” 属性在接收端验证消息的源来避免此问题。例如，让我们在接收方 [www.some-receiver.com](www.some-receiver.com)检查发送方的源[http://www.some-sender.com](http://www.some-sender.com)

     ```javascript
     //Listener on http://www.some-receiver.com/
     window.addEventListener("message", function(message){
         if(/^http://www\.some-sender\.com$/.test(message.origin)){
              console.log('You received the data from valid sender', message.data);
        }
     });
     ```

     **[⬆ Back to Top](#table-of-contents)**

328. ### Can I avoid using postMessages completely

     无法完全（或 100%）避免使用 postMessages。尽管考虑到风险，您的应用程序不使用 postMessage，但许多第三方脚本使用 postMessage 与第三方服务进行通信。因此，您的应用程序可能会在您不知情的情况下使用 postMessage

     **[⬆ Back to Top](#table-of-contents)**

329. ### Is postMessages synchronous

     postMessage在IE8中是同步的但是在IE9和其他现代浏览器（即IE9+, Firefox, Chrome, Safari）是异步的。由于这种异步行为，我们在返回 postMessage 时使用回调机制

     **[⬆ Back to Top](#table-of-contents)**

330. ### What paradigm is Javascript

     JavaScript 是一种多范式语言，支持命令式/过程式编程、面向对象编程和函数式编程。 JavaScript 支持具有原型继承的面向对象编程

     **[⬆ Back to Top](#table-of-contents)**

331. ### What is the difference between internal and external javascript

     **内部JavaScript:** .在script标签中的源代码
     **外部JavaScript:** 存储在外部文件中的源代码(以.js扩展名存储) 并在标签中被引用

     **[⬆ Back to Top](#table-of-contents)**

332. ### Is JavaScript faster than server side script

     是的，JavaScript 比服务器端脚本快。因为 JavaScript 是一个客户端脚本，它的计算或计算不需要任何 Web 服务器的帮助。因此 JavaScript 总是比任何服务器端脚本（如 ASP、PHP 等）都快

     **[⬆ Back to Top](#table-of-contents)**

333. ### How do you get the status of a checkbox

     可以在 DOM 中的选中的复选框上应用 `checked` 属性。如果值为 `True`，则表示复选框已选中，否则未选中。例如，可以使用 javascript 访问下面的 HTML 复选框元素，如下所示

     ```html
     <input type="checkbox" name="checkboxname" value="Agree" /> Agree the
     conditions<br />
     ```

     ```javascript
     console.log(document.getElementById(‘checkboxname’).checked); // true or false
     ```

     **[⬆ Back to Top](#table-of-contents)**

334. ### What is the purpose of double tilde operator

     双波浪号运算符 (~~) 称为双非按位运算符。该运算符将更快地替代 Math.floor()

     **[⬆ Back to Top](#table-of-contents)**

335. ### How do you convert character to ASCII code

     你可以使用 `String.prototype.charCodeAt()` 方法将字符串字符转换为ASCII数字。例如，让我们获取 'ABC' 字符串中第一个字母的ASCII码

     ```javascript
     "ABC".charCodeAt(0); // returns 65
     ```

     而 `String.fromCharCode()` 方法将数字转化成相等的ASCII字符

     ```javascript
     String.fromCharCode(65, 66, 67); // returns 'ABC'
     ```

     **[⬆ Back to Top](#table-of-contents)**

336. ### What is ArrayBuffer

       ArrayBuffer 对象用于表示一个通用的、固定长度的原始二进制数据缓冲区。您可以按如下方式创建它

     ```javascript
     let buffer = new ArrayBuffer(16); // create a buffer of length 16
     alert(buffer.byteLength); // 16
     ```

     为了操作ArrayBuffer，我们需要使用 "视图" 对象

     ```javascript
     //Create a DataView referring to the buffer
     let view = new DataView(buffer);
     ```

     **[⬆ Back to Top](#table-of-contents)**

337. ### What is the output of below string expression

     ```javascript
     console.log("Welcome to JS world"[0]);
     ```

     上边表达式的输出是 "W".
     **解释:** 字符串上具有特定索引的括号标记会返回特定位置的字符。因此，它返回字符串的字符“W”。由于 IE7 及以下版本不支持此功能，您可能需要使用 .charAt() 方法来获得所需的结果

     **[⬆ Back to Top](#table-of-contents)**

338. ### What is the purpose of Error object

     Error 构造函数创建一个错误对象，并在发生运行时错误时抛出错误对象的实例。 Error 对象也可以用作用户自定义异常的基础对象。错误对象的语法如下
     
     ```javascript
     new Error([message[, fileName[, lineNumber]]])
     ```

     可以使用 try...catch 块中的 Error 对象引发用户定义的异常或错误，如下所示

     ```javascript
     try {
       if (withdraw > balance)
         throw new Error("Oops! You don't have enough balance");
     } catch (e) {
       console.log(e.name + ": " + e.message);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

339. ### What is the purpose of EvalError object

     EvalError 对象表示有关全局 `eval()` 函数的错误。尽管 JavaScript 不再抛出此异常，但 EvalError 对象仍保持兼容性。这个表达式的语法如下

     ```javascript
     new EvalError([message[, fileName[, lineNumber]]])
     ```

     You can throw EvalError with in try...catch block as below,

     ```javascript
     try {
       throw new EvalError('Eval function error', 'someFile.js', 100);
     } catch (e) {
       console.log(e.message, e.name, e.fileName);              // "Eval function error", "EvalError", "someFile.js"
     ```

     **[⬆ Back to Top](#table-of-contents)**

340. ### What are the list of cases error thrown from non-strict mode to strict mode

     当你应用 'use strict'; 语法时，下边的一些场景在执行脚本前会抛出语法错误

     1. 当你使用八进制语法时

     ```javascript
     var n = 022;
     ```

     1. 使用 `with` 语句
     2. 当你对变量名使用delete操作符时
     3. 使用eval或arguments作为变量名或者函数参数名
     4. 当使用新保留的关键字时
     5. 当你在一个块中声明函数

     ```javascript
     if (someCondition) {
       function f() {}
     }
     ```

     因此，上述案例中的错误有助于避免开发/生产环境中的错误

     **[⬆ Back to Top](#table-of-contents)**

341. ### Do all objects have prototypes

     不是的。所有对象都有原型，除了由用户创建的基本对象或者由new关键字创建的对象

     **[⬆ Back to Top](#table-of-contents)**

342. ### What is the difference between a parameter and an argument

     形参是函数定义的变量名字，而实参代表函数调用时传给函数的值。让我们用一个简单函数来解释

     ```javascript
     function myFunction(parameter1, parameter2, parameter3) {
       console.log(arguments[0]); // "argument1"
       console.log(arguments[1]); // "argument2"
       console.log(arguments[2]); // "argument3"
     }
     myFunction("argument1", "argument2", "argument3");
     ```

     **[⬆ Back to Top](#table-of-contents)**

343. ### What is the purpose of some method in arrays

     some() 方法用于测试数组中的至少一个元素是否通过了提供的函数实现的测试。该方法返回一个布尔值。让我们举个例子来测试是否有奇数

     ```javascript
     var array = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];

     var odd = (element) => element % 2 !== 0;

     console.log(array.some(odd)); // true (the odd element exists)
     ```

     **[⬆ Back to Top](#table-of-contents)**

344. ### How do you combine two or more arrays

     concat()方法用来拼接两个或多个数组，返回一个包含所有元素的新数组。语法如下

     ```javascript
     array1.concat(array2, array3, ..., arrayX)
     ```

     让我们看一个veggies和fruits数组拼接的例子

     ```javascript
     var veggies = ["Tomato", "Carrot", "Cabbage"];
     var fruits = ["Apple", "Orange", "Pears"];
     var veggiesAndFruits = veggies.concat(fruits);
     console.log(veggiesAndFruits); // Tomato, Carrot, Cabbage, Apple, Orange, Pears
     ```

     **[⬆ Back to Top](#table-of-contents)**

345. ### What is the difference between Shallow and Deep copy

     有两种拷贝对象的方法。

     **浅拷贝:**
     浅拷贝是对象的按位拷贝。创建一个新对象，该对象具有原始对象中值的完整副本。如果对象的任何字段是对其他对象的引用，则仅复制引用地址，即仅复制内存地址

     **例子**

     ```javascript
     var empDetails = {
       name: "John",
       age: 25,
       expertise: "Software Developer",
     };
     ```

     创建一个复本

     ```javascript
     var empDetailsShallowCopy = empDetails; //Shallow copying!
     ```

     如果我们像这样修改复本中的属性值

     ```javascript
     empDetailsShallowCopy.name = "Johnson";
     ```

     由于是浅复制，上边的语句也会修改`empDetails`的name。意味着我们也失去了原始数据

     **深拷贝:**
     深拷贝复制所有字段，并复制字段指向的动态分配内存。当一个对象连同它所引用的对象一起被复制时，就会发生深拷贝

     **例子**

     ```javascript
     var empDetails = {
       name: "John",
       age: 25,
       expertise: "Software Developer",
     };
     ```

     通过将原始对象的属性用于新变量来创建深拷贝

     ```javascript
     var empDetailsDeepCopy = {
       name: empDetails.name,
       age: empDetails.age,
       expertise: empDetails.expertise,
     };
     ```

     现在如果修改 `empDetailsDeepCopy.name`, 只会影响 `empDetailsDeepCopy` 且不会影响 `empDetails`

     **[⬆ Back to Top](#table-of-contents)**

346. ### How do you create specific number of copies of a string

     `repeat()` 方法用于构造并返回一个新字符串，该字符串包含调用它的字符串的指定数量连接在一起的副本。记住此方法已添加到 ECMAScript 2015 规范中
     让我们看一个Hello重复4次的字符串

     ```javascript
     "Hello".repeat(4); // 'HelloHelloHelloHello'
     ```

347. ### How do you return all matching strings against a regular expression

     `matchAll()` 方法可用于返回与正则表达式匹配字符串的所有结果的迭代器。例如，下面的示例返回一个与正则表达式匹配的字符串结果数组

     ```javascript
     let regexp = /Hello(\d?))/g;
     let greeting = "Hello1Hello2Hello3";

     let greetingList = [...greeting.matchAll(regexp)];

     console.log(greetingList[0]); //Hello1
     console.log(greetingList[1]); //Hello2
     console.log(greetingList[2]); //Hello3
     ```

     **[⬆ Back to Top](#table-of-contents)**

348. ### How do you trim a string at the beginning or ending

     字符串原型上的 `trim` 方法用于去除字符串两侧的空白。但是特别如果你想在字符串的开头或结尾进行去除，则可以使用 `trimStart/trimLeft` 和 `trimEnd/trimRight` 方法。让我们看一下greeting消息中这些方法的示例

     ```javascript
     var greeting = "   Hello, Goodmorning!   ";

     console.log(greeting); // "   Hello, Goodmorning!   "
     console.log(greeting.trimStart()); // "Hello, Goodmorning!   "
     console.log(greeting.trimLeft()); // "Hello, Goodmorning!   "

     console.log(greeting.trimEnd()); // "   Hello, Goodmorning!"
     console.log(greeting.trimRight()); // "   Hello, Goodmorning!"
     ```

     **[⬆ Back to Top](#table-of-contents)**

349. ### What is the output of below console statement with unary operator

     让我们看个给出的一元运算符的console语句

     ```javascript
     console.log(+"Hello");
     ```

     上述console.log语句的输出返回 NaN。因为元素以一元运算符为前缀，JavaScript 解释器会尝试将该元素转换为数字类型。由于转换失败，语句的值导致 NaN 值

     **[⬆ Back to Top](#table-of-contents)**

350. ### Does javascript uses mixins

     Mixin 是一个通用的面向对象编程术语 - 是一个包含方法的类，其他类可以使用这些方法而无需从它继承。在 JavaScript 中，我们只能从单个对象继承。即一个对象只能有一个 `[[prototype]]`

     但有时我们需要继承多个，为了克服这个问题，我们可以使用 Mixin 帮助将方法复制到另一个类的原型

     例如，我们有两个类 `User` 和 `CleanRoom`。假设我们需要在 `User` 中添加 `CleanRoom` 功能，以便用户可以按需打扫房间。这就是名为 mixins 的概念出现的地方

     ```javascript
     // mixin
     let cleanRoomMixin = {
       cleanRoom() {
         alert(`Hello ${this.name}, your room is clean now`);
       },
       sayBye() {
         alert(`Bye ${this.name}`);
       },
     };

     // usage:
     class User {
       constructor(name) {
         this.name = name;
       }
     }

     // copy the methods
     Object.assign(User.prototype, cleanRoomMixin);

     // now User can clean the room
     new User("Dude").cleanRoom(); // Hello Dude, your room is clean now!
     ```

     **[⬆ Back to Top](#table-of-contents)**

351. ### What is a thunk function

     thunk 只是一个延迟执行的函数。它不接受任何参数，而是在调用 thunk 时给出值。即，它不用于现在执行，但它将在将来的某个时间执行。我们来看一个同步的例子

     ```javascript
     const add = (x, y) => x + y;

     const thunk = () => add(2, 3);

     thunk(); // 5
     ```

     **[⬆ Back to Top](#table-of-contents)**

352. ### What are asynchronous thunks

     异步 thunk 对发起网络请求很有用。让我们看一个网络请求的例子

     ```javascript
     function fetchData(fn) {
       fetch("https://jsonplaceholder.typicode.com/todos/1")
         .then((response) => response.json())
         .then((json) => fn(json));
     }

     const asyncThunk = function () {
       return fetchData(function getData(data) {
         console.log(data);
       });
     };

     asyncThunk();
     ```

     `getData` 函数不会马上调用，但只有当数据在 API 可用时才会被调用。 setTimeout 函数也用于使我们的代码异步。最好的实时示例是 redux 状态管理库，它使用异步 thunk 来延迟调度指令

     **[⬆ Back to Top](#table-of-contents)**

353. ### What is the output of below function calls

     **代码片段:**

     ```javascript
     const circle = {
       radius: 20,
       diameter() {
         return this.radius * 2;
       },
       perimeter: () => 2 * Math.PI * this.radius,
     };
     ```
     
     ```javascript
     console.log(circle.diameter());
     console.log(circle.perimeter());
     ```

     **输出:**

     输出为 40 和 NaN。记住diameter是常规函数，而perimeter是箭头函数。常规函数周围作用域的 `this` 关键字（即diameter）是一个类（即 Shape 对象）。而周围作用域中 perimeter 函数的 this 关键字是一个window对象。由于窗口对象没有半径属性，它返回一个undefined的值，并且与数字值相乘后返回 NaN 值

     **[⬆ Back to Top](#table-of-contents)**

354. ### How to remove all line breaks from a string

     最简单的方法是使用正则表达式来检测和替换字符串中的换行符。在这种情况下，我们使用替换函数和要替换的字符串，在我们的例子中是一个空字符串。

     ```javascript
     function remove_linebreaks( var message ) {
         return message.replace( /[\r\n]+/gm, "" );
     }
     ```

     上边表达式中，g和m是全局和多行标记

     **[⬆ Back to Top](#table-of-contents)**

355. ### What is the difference between reflow and repaint

     当更改影响元素的可见性但不影响其布局时，会发生 _重绘_ 。这方面的示例包括轮廓、可见性或背景颜色。 _回流_ 涉及影响页面一部分（或整个页面）布局的更改。调整浏览器窗口的大小、更改字体、更改内容（例如用户键入文本）、使用涉及计算样式的 JavaScript 方法、在 DOM 中添加或删除元素以及更改元素的类都是可以触发回流的一些事情。元素的回流会导致所有子元素和祖先元素以及 DOM 中跟随它的任何元素的后续回流

     **[⬆ Back to Top](#table-of-contents)**

356. ### What happens with negating an array

     使用 `!` 字符对数组求反会将数组强制转换为布尔值。由于数组被认为是真值，所以取反会返回 `false`

     ```javascript
     console.log(![]); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

357. ### What happens if we add two arrays

     如果将两个数组相加，会将它们都转换为字符串并将它们连接起来。例如，添加数组的结果如下

     ```javascript
     console.log(["a"] + ["b"]); // "ab"
     console.log([] + []); // ""
     console.log(![] + []); // "false", because ![] returns false.
     ```

     **[⬆ Back to Top](#table-of-contents)**

358. ### What is the output of prepend additive operator on falsy values

     如果在假值（null、undefined、NaN、false、""）上添加加法（+）运算符，则假值将转换为数字值0。让我们在浏览器控制台上显示它们，如下所示

     ```javascript
     console.log(+null); // 0
     console.log(+undefined); // NaN
     console.log(+false); // 0
     console.log(+NaN); // NaN
     console.log(+""); // 0
     ```

     **[⬆ Back to Top](#table-of-contents)**

359. ### How do you create self string using special characters

     字符串可以由 `[]()!+` 字符的组合形成。需要记住以下约定以实现此模式

     1. 由于数组是真值，对数组取反会产生false: ![] === false
     2. 根据 JavaScript 强转规则，将数组加在一起会将它们串起来: [] + [] === ""
     3. 在数组前面加上 + 运算符会将数组转换为 false，否定将使其为 true，最后转换结果将产生值 '1'： +(!(+[])) === 1

     通过应用上述规则，我们可以得出以下条件

     ```javascript
     (![] + [] === "false" + !+[]) === 1;
     ```

     现在字符模式将如下创建

     ```javascript
           s               e               l               f
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^

      (![] + [])[3] + (![] + [])[4] + (![] + [])[2] + (![] + [])[0]
      ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^   ^^^^^^^^^^^^^
     (![] + [])[+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]+!+[]+!+[]] +
     (![] + [])[+!+[]+!+[]] +
     (![] + [])[+[]]
     ^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
     (![]+[])[+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]+!+[]+!+[]]+(![]+[])[+!+[]+!+[]]+(![]+[])[+[]]
     ```

     **[⬆ Back to Top](#table-of-contents)**

360. ### How do you remove falsy values from an array

     可以将Boolean作为参数传递给数组的filter方法。这样就会从数组中删除所有假值（0、undefined、null、false 和 ""）
     

     ```javascript
     const myArray = [false, null, 1, 5, undefined];
     myArray.filter(Boolean); // [1, 5] // is same as myArray.filter(x => x);
     ```

     **[⬆ Back to Top](#table-of-contents)**

361. ### How do you get unique values of an array

     可以使用 `Set` 和 剩余表达式/展开(...) 语法的组合来对数组去重

     ```javascript
     console.log([...new Set([1, 2, 4, 4, 3])]); // [1, 2, 4, 3]
     ```

     **[⬆ Back to Top](#table-of-contents)**

362. ### What is destructuring aliases

     有时你希望有一个名称与属性名称不同的解构变量。在这种情况下，可以使用 `:newName` 来指定变量的名称。这个过程称为解构别名

     ```javascript
     const obj = { x: 1 };
     // Grabs obj.x as as { otherName }
     const { x: otherName } = obj;
     ```

     **[⬆ Back to Top](#table-of-contents)**

363. ### How do you map the array values without using map method

     只需使用 Array 的 `from` 方法就可以在不使用 `map` 方法的情况下映射数组值。让我们从Countries数组中映射城市名称

     ```javascript
     const countries = [
       { name: "India", capital: "Delhi" },
       { name: "US", capital: "Washington" },
       { name: "Russia", capital: "Moscow" },
       { name: "Singapore", capital: "Singapore" },
       { name: "China", capital: "Beijing" },
       { name: "France", capital: "Paris" },
     ];

     const cityNames = Array.from(countries, ({ capital }) => capital);
     console.log(cityNames); // ['Delhi, 'Washington', 'Moscow', 'Singapore', 'Beijing', 'Paris']
     ```

     **[⬆ Back to Top](#table-of-contents)**

364. ### How do you empty an array

     可以通过将数组length设置为0来快速清空数组

     ```javascript
     let cities = ["Singapore", "Delhi", "London"];
     cities.length = 0; // cities becomes []
     ```

     **[⬆ Back to Top](#table-of-contents)**

365. ### How do you rounding numbers to certain decimals

     可以使用原生 javascript 中的 `toFixed` 方法将数字四舍五入到一定的小数位数

     ```javascript
     let pie = 3.141592653;
     pie = pie.toFixed(3); // 3.142
     ```

     **[⬆ Back to Top](#table-of-contents)**

366. ### What is the easiest way to convert an array to an object

     你可以将同样的数据使用展开（...）运算符将对象转换为数组

     ```javascript
     var fruits = ["banana", "apple", "orange", "watermelon"];
     var fruitsObject = { ...fruits };
     console.log(fruitsObject); // {0: "banana", 1: "apple", 2: "orange", 3: "watermelon"}
     ```

     **[⬆ Back to Top](#table-of-contents)**

367. ### How do you create an array with some data

     可以使用 `fill` 方法创建包含一些数据的数组或具有相同值的数组

     ```javascript
     var newArray = new Array(5).fill("0");
     console.log(newArray); // ["0", "0", "0", "0", "0"]
     ```

     **[⬆ Back to Top](#table-of-contents)**

368. ### What are the placeholders from console object

     下边是console对象中可用的一些占位符。

     1. %o — 表示对象,
     2. %s — 表示字符串,
     3. %d — 表示十进制或整数
        这些占位符可以在 console.log 中表示，如下所示

     ```javascript
     const user = { name: "John", id: 1, city: "Delhi" };
     console.log(
       "Hello %s, your details %o are available in the object form",
       "John",
       user
     ); // Hello John, your details {name: "John", id: 1, city: "Delhi"} are available in object
     ```

     **[⬆ Back to Top](#table-of-contents)**

369. ### Is it possible to add CSS to console messages

     你可以像网页中的html文本一样将css样式引用到console消息中

     ```javascript
     console.log(
       "%c The text has blue color, with large font and red background",
       "color: blue; font-size: x-large; background: red"
     );
     ```

     文本会像下边一样展示
     ![Screenshot](images/console-css.png)

     **注意:** 所有的CSS样式都可以被应用到console消息上

     **[⬆ Back to Top](#table-of-contents)**

370. ### What is the purpose of dir method of console object

     `console.dir()` 用于将指定 JavaScript 对象作为JSON展示属性的交互式列表

     ```javascript
     const user = { name: "John", id: 1, city: "Delhi" };
     console.dir(user);
     ```

     user对象以JSON形式展示
     ![Screenshot](images/console-dir.png)

     **[⬆ Back to Top](#table-of-contents)**

371. ### Is it possible to debug HTML elements in console

     是的，可以在控制台中获取和调试 HTML 元素，就像检查元素一样

     ```javascript
     const element = document.getElementsByTagName("body")[0];
     console.log(element);
     ```

     在console中打印了HTML元素

     ![Screenshot](images/console-html.png)

     **[⬆ Back to Top](#table-of-contents)**

372. ### How do you display data in a tabular format using console object

     `console.table()` 用于在控制台中以表格格式显示数据，以可视化展示复杂的数组或对象

     ```js
     const users = [
       { name: "John", id: 1, city: "Delhi" },
       { name: "Max", id: 2, city: "London" },
       { name: "Rod", id: 3, city: "Paris" },
     ];
     console.table(users);
     ```

     数据以表格格式可视化

     ![Screenshot](images/console-table.png)
     **注意:** 记住IE不支持 `console.table()`

     **[⬆ Back to Top](#table-of-contents)**

373. ### How do you verify that an argument is a Number or not

     IsNaN 和 isFinite 方法的结合用于确认实参是否为数字

     ```javascript
     function isNumber(n) {
       return !isNaN(parseFloat(n)) && isFinite(n);
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

374. ### How do you create copy to clipboard button

     你需要选择输入元素的内容（使用 .select() 方法）并使用 execCommand 执行复制命令（即 execCommand('copy')）。还可以执行其他系统命令，例如剪切和粘贴

     ```javascript
     document.querySelector("#copy-button").onclick = function () {
       // Select the content
       document.querySelector("#copy-input").select();
       // Copy to the clipboard
       document.execCommand("copy");
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

375. ### What is the shortcut to get timestamp

     可以使用 `new Date().getTime()` 获得当前时间戳. 也有别的快捷方式获得该值

     ```javascript
     console.log(+new Date());
     console.log(Date.now());
     ```

     **[⬆ Back to Top](#table-of-contents)**

376. ### How do you flattening multi dimensional arrays

     使用展开运算符扁平化二维数组很简单

     ```javascript
     const biDimensionalArr = [11, [22, 33], [44, 55], [66, 77], 88, 99];
     const flattenArr = [].concat(...biDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```

     但是你也可以通过递归调用使得多维数组也起作用

     ```javascript
     function flattenMultiArray(arr) {
       const flattened = [].concat(...arr);
       return flattened.some((item) => Array.isArray(item))
         ? flattenMultiArray(flattened)
         : flattened;
     }
     const multiDimensionalArr = [11, [22, 33], [44, [55, 66, [77, [88]], 99]]];
     const flatArr = flattenMultiArray(multiDimensionalArr); // [11, 22, 33, 44, 55, 66, 77, 88, 99]
     ```

     **[⬆ Back to Top](#table-of-contents)**

377. ### What is the easiest multi condition checking

     可以使用 `indexOf` 将输入与多个值进行比较，而不是检查每个值作为一个条件

     ```javascript
     // Verbose approach
     if (
       input === "first" ||
       input === 1 ||
       input === "second" ||
       input === 2
     ) {
       someFunction();
     }
     // Shortcut
     if (["first", 1, "second", 2].indexOf(input) !== -1) {
       someFunction();
     }
     ```

     **[⬆ Back to Top](#table-of-contents)**

378. ### How do you capture browser back button

     `window.onbeforeunload` 方法用于捕获浏览器后退按钮事件。这有助于警告用户将要丢失当前数据

     ```javascript
     window.onbeforeunload = function () {
       alert("You work will be lost");
     };
     ```

     **[⬆ Back to Top](#table-of-contents)**

379. ### How do you disable right click in the web page

     可以通过在 body 元素的 `oncontextmenu` 属性中返回 false 来禁用页面上的右键单击
    

     ```html
     <body oncontextmenu="return false;"></body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

380. ### What are wrapper objects

     像字符串、数字和布尔值这样的原始值没有属性和方法，但是当您尝试对其执行操作时，它们会被临时转换或强制转换为对象（包装对象）。例如，如果对原始字符串值应用 toUpperCase() 方法，它不会抛出错误，而是返回字符串的大写

     ```javascript
     let name = "john";

     console.log(name.toUpperCase()); // Behind the scenes treated as console.log(new String(name).toUpperCase());
     ```

     也就是说，除了null和undefined的原始值都有包装对象，包装对象有String,Number,Boolean,Symbol 和 BigInt

     **[⬆ Back to Top](#table-of-contents)**

381. ### What is AJAX

     AJAX 代表异步 JavaScript 和 XML，它是一组用于异步显示数据的相关技术（HTML、CSS、JavaScript、XMLHttpRequest API 等）。即我们可以向服务器发送数据并从服务器获取数据，而无需重新加载网页

     **[⬆ Back to Top](#table-of-contents)**

382. ### What are the different ways to deal with Asynchronous Code

     下边是处理异步代码的不同方法

     1. 回调
     2. Promises
     3. Async/await
     4. 第三方库例如async.js,bluebird等

     **[⬆ Back to Top](#table-of-contents)**

383. ### How to cancel a fetch request

     直到几天前，原生 Promise 的一个缺点是无法直接取消 fetch 请求。但是 js 规范中的新 `AbortController` 允许您使用signal中止一个或多个 fetch 调用
     取消fetch请求的基本流程如下
     

     1. 创建一个 `AbortController` 实例
     2. 获取实例的signal属性并将signal作为信号的fetch选项传递
     3. 调用 AbortController 的 abort 属性以取消使用该信号的所有fetch
        例如，让我们将相同的signal传递给多个 fetch 调用,将取消所有带有该信号的请求

     ```javascript
     const controller = new AbortController();
     const { signal } = controller;

     fetch("http://localhost:8000", { signal })
       .then((response) => {
         console.log(`Request 1 is complete!`);
       })
       .catch((e) => {
         if (e.name === "AbortError") {
           // We know it's been canceled!
         }
       });

     fetch("http://localhost:8000", { signal })
       .then((response) => {
         console.log(`Request 2 is complete!`);
       })
       .catch((e) => {
         if (e.name === "AbortError") {
           // We know it's been canceled!
         }
       });

     // Wait 2 seconds to abort both requests
     setTimeout(() => controller.abort(), 2000);
     ```

     **[⬆ Back to Top](#table-of-contents)**

384. ### What is web speech API

     Web speech API 用于使现代浏览器能够识别和合成语音（即语音数据到 Web 应用程序中）。该 API 由 W3C 社区于 2012 年推出。它有两个主要部分

     1. **语音识别 (异步语音识别或语音转文本):** 它提供了从音频输入中识别语音上下文并做出相应响应的能力。这是由 `SpeechRecognition` 接口访问的
        下边的例子展示了如何使用这个API从语音中获得文本

     ```javascript
     window.SpeechRecognition =
       window.webkitSpeechRecognition || window.SpeechRecognition; // webkitSpeechRecognition for Chrome and SpeechRecognition for FF
     const recognition = new window.SpeechRecognition();
     recognition.onresult = (event) => {
       // SpeechRecognitionEvent type
       const speechToText = event.results[0][0].transcript;
       console.log(speechToText);
     };
     recognition.start();
     ```

     这个API中，浏览器会向你请求使用麦克风的权限

     1. **SpeechSynthesis (Text-to-Speech):** 它提供了从音频输入中识别语音上下文并做出响应的能力。这是由 `SpeechSynthesis` 接口访问的
        例如，以下代码用于从文本中获取语音/发音

     ```javascript
     if ("speechSynthesis" in window) {
       var speech = new SpeechSynthesisUtterance("Hello World!");
       speech.lang = "en-US";
       window.speechSynthesis.speak(speech);
     }
     ```

     上面的例子可以在 chrome(33+) 浏览器的开发者控制台上测试
     **注意:** 这个 API 仍然是一个工作草案，只在 Chrome 和 Firefox 浏览器中可用（当然 Chrome 只实现了规范）

     **[⬆ Back to Top](#table-of-contents)**

385. ### What is minimum timeout throttling

     浏览器和 NodeJS的javascript 环境都会以大于 0 毫秒的最小延迟进行节流。这意味着即使设置 0ms 的延迟也不会立即发生
     **浏览器:** 最小延迟为 4 毫秒。当由于回调嵌套（一定深度）或在一定数量的连续间隔之后触发连续调用时，会发生此限制
     注意: 老式浏览器最小延时为10ms
     **Nodejs:** 最小延迟为 1 毫秒。 当延迟大于 2147483647 或小于 1 时会发生此限制
     解释此超时限制行为的最佳示例是以下代码片段的顺序

     ```javascript
     function runMeFirst() {
       console.log("My script is initialized");
     }
     setTimeout(runMeFirst, 0);
     console.log("Script loaded");
     ```

     输出是

     ```cmd
     Script loaded
     My script is initialized
     ```

     如果不使用 `setTimeout`, 输出顺序会是串行的

     ```javascript
     function runMeFirst() {
       console.log("My script is initialized");
     }
     runMeFirst();
     console.log("Script loaded");
     ```

     输出是,

     ```cmd
     My script is initialized
     Script loaded
     ```

     **[⬆ Back to Top](#table-of-contents)**

386. ### How do you implement zero timeout in modern browsers

     由于最小延迟大于 0 毫秒，你不能使用 setTimeout(fn, 0) 立即执行代码。但是您可以使用 window.postMessage() 来实现此行为

     **[⬆ Back to Top](#table-of-contents)**

387. ### What are tasks in event loop

     任务是由标准机制安排好运行的任何 javascript 代码/程序，例如最初开始运行程序、运行事件回调或触发间隔或超时。所有这些任务都安排在一个任务队列中
     下边是一些将任务添加到任务队列中用例

     1. 当一个新的 javascript 程序直接从控制台执行或由 `<script>` 元素运行时，该任务将被添加到任务队列中
     2. 当事件触发时，事件回调被添加到任务队列中
     3. 当达到 setTimeout 或 setInterval 时，将相应的回调添加到任务队列

     **[⬆ Back to Top](#table-of-contents)**

388. ### What is microtask

     微任务是当前执行的任务/微任务完成后需要立即执行的javascript代码。它们本质上是一种阻塞。即，主线程将被阻塞，直到微任务队列为空。
     微任务的主要来源是 Promise.resolve、Promise.reject、MutationObservers、IntersectionObservers 等

     **注意:** 所有这些微任务都在事件循环的同一轮中处理
     **[⬆ Back to Top](#table-of-contents)**

389. ### What are different event loops

     **[⬆ Back to Top](#table-of-contents)**

390. ### What is the purpose of queueMicrotask

     **[⬆ Back to Top](#table-of-contents)**

391. ### How do you use javascript libraries in typescript file

     众所周知，并非所有 JavaScript 库或框架都有 TypeScript 声明文件。但是，如果您仍想在我们的 TypeScript 文件中使用库或框架而不会出现编译错误，唯一的解决方案是 `declare` 关键字和变量声明。例如，假设您有一个名为“customLibrary”的库，它没有 TypeScript 声明，并且在全局命名空间中有一个名为“customLibrary”的命名空间。您可以在打字稿代码中使用此库，如下所示

     ```javascript
     declare var customLibrary;
     ```

     在运行时，typescript 会将类型提供给 `customLibrary` 变量作为 `any` 类型。不使用 declare 关键字的另一种选择如下

     ```javascript
     var customLibrary: any;
     ```

     **[⬆ Back to Top](#table-of-contents)**

392. ### What are the differences between promises and observables

     表格中是一些主要区别

     | Promises                                                           | Observables                                                     |
     | ------------------------------------------| ---------------------------------------------------------------------------------------- |
     |  一次只发出一个值                             | 在一段时间内发出多个值（从 0 到多个值的流） |
     | 天生渴望；他们将立即被执行           | 天生懒惰；需要订阅来执行                                |
     | 即使立即解析promise也总是异步 | 可以是同步或者异步                                     |
     | 不提供任何操作符                                      | 提供像 map, forEach, filter, reduce, retry, 和 retryWhen 等操作符        |
     | 不能被取消                                                 | 使用unsubscribe() 方法取消                                                  |

     **[⬆ Back to Top](#table-of-contents)**

393. ### What is heap

     堆（或内存堆）是我们定义变量时存储对象的内存位置。即，这是所有内存分配和解除分配发生的地方。堆和调用栈都是 JS 运行时的两个容器。
     每当运行时在代码中遇到变量和函数声明时，它将它们存储在堆中。

     ![Screenshot](images/heap.png)

     **[⬆ Back to Top](#table-of-contents)**

394. ### What is an event table

     事件表是一种数据结构，用于存储和跟踪所有将异步执行的事件，例如在某个时间间隔之后或在某些 API 请求解决之后。即每当您调用 setTimeout 函数或调用异步操作时，它都会添加到事件表中
     它不会自行执行功能。事件表的主要目的是跟踪事件并将它们发送到事件队列，如下图所示

     ![Screenshot](images/event-table.png)

     **[⬆ Back to Top](#table-of-contents)**

395. ### What is a microTask queue

     微任务队列是新的队列，promise 对象初始化的所有任务都在回调队列之前得到处理
     在下一个渲染和绘制作业之前处理微任务队列。但如果这些微任务运行时间很长，则会导致视觉退化

     **[⬆ Back to Top](#table-of-contents)**

396. ### What is the difference between shim and polyfill

     shim 是一个库，它将新 API 引入旧环境，仅使用该环境的方法。它不一定限于 Web 应用程序。例如，es5-shim.js 用于在旧浏览器（主要是 IE9 之前）上模拟 ES5 功能
         而 polyfill 是一段代码（或插件），它提供了您（开发人员）期望浏览器原生提供的技术
     简单来说，polyfill 是浏览器 API 的 shim

     **[⬆ Back to Top](#table-of-contents)**

397. ### How do you detect primitive or non primitive value type

     在 JavaScript 中，原始类型包括 boolean、string、number、BigInt、null、Symbol 和 undefined。而非原始类型包括对象。但是你可以使用以下功能轻松区分它们

     ```javascript
     var myPrimitive = 30;
     var myNonPrimitive = {};
     function isPrimitive(val) {
       return Object(val) !== val;
     }

     isPrimitive(myPrimitive);
     isPrimitive(myNonPrimitive);
     ```

     如果该值是原始数据类型，则 Object 构造函数会为该值创建一个新的包装器对象。但是如果值是非原始数据类型（一个对象），Object构造函数会给出相同的对象

     **[⬆ Back to Top](#table-of-contents)**

398. ### What is babel

     Babel 是一个 JavaScript 转译器，用于将 ECMAScript 2015+ 代码转换为当前和旧版浏览器或环境中向后兼容的 JavaScript 版本。下面列出了一些主要功能

     1. 转译语法
     2. 提供目标环境中缺少的 Polyfill 功能（使用 @babel/polyfill）
     3. 源代码转换（或 codemods）

     **[⬆ Back to Top](#table-of-contents)**

399. ### Is Node.js completely single threaded

     Node 是单线程的，但是 Node.js 标准库中包含的一些函数（例如 fs 模块函数）不是单线程的。即，他们的逻辑在 Node.js 单线程之外运行，以提高程序的速度和性能

     **[⬆ Back to Top](#table-of-contents)**

400. ### What are the common use cases of observables

     一些最常见的 observable 用例是带有推送通知、用户输入更改、重复间隔等的 websocket

     **[⬆ Back to Top](#table-of-contents)**

401. ### What is RxJS

     RxJS（JavaScript 的响应式扩展）是一个使用可观察对象实现响应式编程的库，它可以更轻松地编写异步或基于回调的代码。它还提供了用于创建和使用可观察对象的工具函数

     **[⬆ Back to Top](#table-of-contents)**

402. ### What is the difference between Function constructor and function declaration

     The functions which are created with `Function constructor` do not create closures to their creation contexts but they are always created in the global scope. i.e, the function can access its own local variables and global scope variables only. Whereas function declarations can access outer function variables(closures) too.
     使用`Function构造器`创建的函数不会为其上下文创建闭包，但它们总是在全局范围内创建。即，该函数只能访问其自己的局部变量和全局范围变量。而函数声明也可以访问外部函数变量（闭包）

     Let's see this difference with an example,

     **Function构造器:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return new Function("return a;");
     }
     console.log(createFunction()()); // 100
     ```

     **函数声明:**

     ```javascript
     var a = 100;
     function createFunction() {
       var a = 200;
       return function func() {
         return a;
       };
     }
     console.log(createFunction()()); // 200
     ```

     **[⬆ Back to Top](#table-of-contents)**

403. ### What is a Short circuit condition

     Short circuit conditions are meant for condensed way of writing simple if statements. Let's demonstrate the scenario using an example. If you would like to login to a portal with an authentication condition, the expression would be as below,
     短路条件是用于简化编写简单 if 语句的方式。让我们用一个例子来演示这个场景。如果你想经过身份认证登录门户，则表达式如下

     ```javascript
     if (authenticate) {
       loginToPorta();
     }
     ```

     由于javascript逻辑运算符从左到右进行运算，上述表达式可以被简化成使用&&运算符

     ```javascript
     authenticate && loginToPorta();
     ```

     **[⬆ Back to Top](#table-of-contents)**

404. ### What is the easiest way to resize an array

     数组的length属性对于快速重新调整或清空数组很有用。让我们在数字数组上应用length属性来将元素的数量从 5 调整为 2

     ```javascript
     var array = [1, 2, 3, 4, 5];
     console.log(array.length); // 5

     array.length = 2;
     console.log(array.length); // 2
     console.log(array); // [1,2]
     ```

     数组也可以被清空

     ```javascript
     var array = [1, 2, 3, 4, 5];
     array.length = 0;
     console.log(array.length); // 0
     console.log(array); // []
     ```

     **[⬆ Back to Top](#table-of-contents)**

405. ### What is an observable

     Observable 基本上是一个函数，它可以随时间同步或异步地向观察者返回值的流。消费者可以通过调用 `subscribe()` 方法获取值
     让我们看一个Observable的简单例子

     ```javascript
     import { Observable } from "rxjs";

     const observable = new Observable((observer) => {
       setTimeout(() => {
         observer.next("Message from a Observable!");
       }, 3000);
     });

     observable.subscribe((value) => console.log(value));
     ```

     ![Screenshot](images/observables.png)

     **注意:** Observables 还不是 JavaScript 语言的一部分，但正在提议将它们添加到该语言中

     **[⬆ Back to Top](#table-of-contents)**

406. ### What is the difference between function and class declarations

     函数声明和类声明的主要区别是 `hoisting`。函数声明会被提升但是类声明不会

     **类:**

     ```javascript
     const user = new User(); // ReferenceError

     class User {}
     ```

     **构造函数:**

     ```javascript
     const user = new User(); // No error

     function User() {}
     ```

     **[⬆ Back to Top](#table-of-contents)**

407. ### What is an async function

     async函数是使用 `async` 关键字声明的函数，它通过避免使用promise链，可以以更简洁的方式编写基于承诺的异步行为。这些函数可以包含零个或多个 `await` 表达式

     让我们看下边的async函数例子

     ```javascript
     async function logger() {
       let data = await fetch("http://someapi.com/users"); // pause until fetch returns
       console.log(data);
     }
     logger();
     ```

     基本上是 ES2015 promise和生成器的语法糖

     **[⬆ Back to Top](#table-of-contents)**

408. ### How do you prevent promises swallowing errors

     在使用异步代码时，JavaScript 的 ES6 promise 可以让你的生活变得更轻松，而无需在每一行都进行回调金字塔和错误处理。但是 Promise 有一些陷阱，最大的一个是会默认吞下错误

     假设您希望在以下所有情况下向控制台打印错误

     ```javascript
     Promise.resolve("promised value").then(function () {
       throw new Error("error");
     });

     Promise.reject("error value").catch(function () {
       throw new Error("error");
     });

     new Promise(function (resolve, reject) {
       throw new Error("error");
     });
     ```

     但是有许多现代 JavaScript 环境不会打印任何错误。可以通过不同的方式解决此问题

     1. **在每个链式调用结尾增加catch块:** 将catch块添加到每个promise链结尾

        ```javascript
        Promise.resolve("promised value")
          .then(function () {
            throw new Error("error");
          })
          .catch(function (error) {
            console.error(error.stack);
          });
        ```

        但是对于每个promise链都很难键入并且也很冗长

     2. **增加done方法:** 可以将第一个方案中的then和catch块替换为done方法

        ```javascript
        Promise.resolve("promised value").done(function () {
          throw new Error("error");
        });
        ```

        假设您想使用 HTTP 获取数据，然后对结果数据进行异步处理。您可以如下编写 `done` 块

        ```javascript
        getDataFromHttp()
          .then(function (result) {
            return processDataAsync(result);
          })
          .done(function (processed) {
            displayData(processed);
          });
        ```

        将来，如果处理库 API 更改为同步，那么您可以删除 `done` 块，如下所示

        ```javascript
        getDataFromHttp().then(function (result) {
          return displayData(processDataAsync(result));
        });
        ```

        然后你忘记将 `done` 块添加到 `then` 块会导致静默错误

     3. **Bluebird扩展的ES6 Promise:**

        Bluebird 扩展了 ES6 Promises API 以避免第二个解决方案中的问题。这个库有一个 “默认” 的 onRejection 处理程序，它将从被拒绝的 Promises 中打印所有错误到 st​​derr。在安装后，您可以处理未处理的rejection

        ```javascript
        Promise.onPossiblyUnhandledRejection(function (error) {
          throw error;
        });
        ```

        丢弃rejection，只需用空catch处理它

        ```javascript
        Promise.reject("error value").catch(function () {});
        ```

     **[⬆ Back to Top](#table-of-contents)**

409. ### What is deno

     Deno 是一个简单、现代且安全的 JavaScript 和 TypeScript 运行时，它使用 V8 JavaScript 引擎和 Rust 编程语言

     **[⬆ Back to Top](#table-of-contents)**

410. ### How do you make an object iterable in javascript

     默认情况下，普通对象是不可迭代的。但是您可以通过在对象上定义 `Symbol.iterator` 属性来使对象可迭代

     让我们用例子说明

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]() {
         const values = Object.keys(this);
         let i = 0;
         return {
           next: () => {
             return {
               value: this[values[i++]],
               done: i > values.length,
             };
           },
         };
       },
     };

     const iterator = collection[Symbol.iterator]();

     console.log(iterator.next()); // → {value: 1, done: false}
     console.log(iterator.next()); // → {value: 2, done: false}
     console.log(iterator.next()); // → {value: 3, done: false}
     console.log(iterator.next()); // → {value: undefined, done: true}
     ```

     使用生成器函数可以简化上述过程

     ```javascript
     const collection = {
       one: 1,
       two: 2,
       three: 3,
       [Symbol.iterator]: function* () {
         for (let key in this) {
           yield this[key];
         }
       },
     };
     const iterator = collection[Symbol.iterator]();
     console.log(iterator.next()); // {value: 1, done: false}
     console.log(iterator.next()); // {value: 2, done: false}
     console.log(iterator.next()); // {value: 3, done: false}
     console.log(iterator.next()); // {value: undefined, done: true}
     ```

     **[⬆ Back to Top](#table-of-contents)**

411. ### What is a Proper Tail Call

     首先，在谈论“正确的尾调用”之前，我们应该了解尾调用。尾调用是作为调用函数的最终操作执行的子例程或函数调用。而**正确的尾调用（PTC）**是一种技术，当函数调用是尾调用时，程序或代码不会为递归创建额外的堆栈帧。

     例如，下面的阶乘函数的经典或头递归依赖于每个步骤的堆栈。每一步都需要处理到`n * factorial(n - 1)`

     ```javascript
     function factorial(n) {
       if (n === 0) {
         return 1;
       }
       return n * factorial(n - 1);
     }
     console.log(factorial(5)); //120
     ```

     但是，如果您使用尾递归函数，它们会不断将所需的所有必要数据传递到递归中，而不依赖于堆栈

     ```javascript
     function factorial(n, acc = 1) {
       if (n === 0) {
         return acc;
       }
       return factorial(n - 1, n * acc);
     }
     console.log(factorial(5)); //120
     ```

     上述模式返回与第一个模式相同的输出。但是累加器会跟踪总数作为参数，而不在递归调用中使用堆栈内存

     **[⬆ Back to Top](#table-of-contents)**

412. ### How do you check an object is a promise or not

     如果你不知道一个值是否是一个promise，将这个值包装为`Promise.resolve(value)`，它会返回一个promise

     ```javascript
     function isPromise(object) {
       if (Promise && Promise.resolve) {
         return Promise.resolve(object) == object;
       } else {
         throw "Promise not supported in your environment";
       }
     }

     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     另一个方法是检测`.then()`处理器的类型

     ```javascript
     function isPromise(value) {
       return Boolean(value && typeof value.then === "function");
     }
     var i = 1;
     var promise = new Promise(function (resolve, reject) {
       resolve();
     });

     console.log(isPromise(i)); // false
     console.log(isPromise(promise)); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

413. ### How to detect if a function is called as constructor

     您可以使用 `new.target` 伪属性来检测函数是作为构造函数调用（使用 new 运算符）还是作为常规函数调用

     1. 如果使用new操作符调用了构造器或者函数，new.target 返回该构造器或函数的引用
     2. 对于函数调用，new.target是undefined

     ```javascript
     function Myfunc() {
        if (new.target) {
           console.log('called with new');
        } else {
           console.log('not called with new');
        }
     }

     new Myfunc(); // called with new
     Myfunc(); // not called with new
     Myfunc.call({}); not called with new
     ```

     **[⬆ Back to Top](#table-of-contents)**

414. ### What are the differences between arguments object and rest parameter

     arguments对象和剩余参数的三个主要区别是

     1. arguments对象是类数组而非对象。而剩余参数是数组实例
     2. arguments对象不支持如 sort, map, forEach, 或者 pop. 而这些方法在剩余参数上可用
     3. 剩余参数只是那些没有被赋予单独名称的参数，而 arguments 对象包含传递给函数的所有参数

     **[⬆ Back to Top](#table-of-contents)**

415. ### What are the differences between spread operator and rest parameter

     剩余参数将所有剩余元素收集到一个数组中。而展开运算符允许将迭代（数组/对象/字符串）扩展为单个参数/元素。即，剩余参数与展开运算符相反

     **[⬆ Back to Top](#table-of-contents)**

416. ### What are the different kinds of generators

     有五种生成器

     1. **生成器函数声明:**

        ```javascript
        function* myGenFunc() {
          yield 1;
          yield 2;
          yield 3;
        }
        const genObj = myGenFunc();
        ```

     2. **生成器函数表达式:**

        ```javascript
        const myGenFunc = function* () {
          yield 1;
          yield 2;
          yield 3;
        };
        const genObj = myGenFunc();
        ```

     3. **对象字面量中的生成器方法定义:**

        ```javascript
        const myObj = {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          },
        };
        const genObj = myObj.myGeneratorMethod();
        ```

     4. **类中的生成器方法定义:**

        ```javascript
        class MyClass {
          *myGeneratorMethod() {
            yield 1;
            yield 2;
            yield 3;
          }
        }
        const myObject = new MyClass();
        const genObj = myObject.myGeneratorMethod();
        ```

     5. **作为计算属性的生成器:**

        ```javascript
        const SomeObj = {
          *[Symbol.iterator]() {
            yield 1;
            yield 2;
            yield 3;
          },
        };

        console.log(Array.from(SomeObj)); // [ 1, 2, 3 ]
        ```

     **[⬆ Back to Top](#table-of-contents)**

417. ### What are the built-in iterables

     下边是javascript中内置的可迭代对象

     1. 数组和类型数组
     2. Strings: 迭代每个字符或 Unicode 码点
     3. Maps: 迭代它的键值对
     4. Sets: 迭代它的元素
     5. arguments: 函数中的类数组特殊变量
     6. 像NodeList一样的DOM集合

     **[⬆ Back to Top](#table-of-contents)**

418. ### What are the differences between for...of and for...in statements

     for...in 和 for...of 语句都迭代js数据结构。唯一区别是它们迭代的东西：:

     1. for..in 迭代对象的所有可枚举属性
     2. for..of 迭代可迭代对象的所有值

     让我们用一个例子来解释区别

     ```javascript
     let arr = ["a", "b", "c"];

     arr.newProp = "newVlue";

     // key are the property keys
     for (let key in arr) {
       console.log(key);
     }

     // value are the property values
     for (let value of arr) {
       console.log(value);
     }
     ```

     由于 for..in 循环遍历对象的键，因此第一个循环在遍历数组对象时记录 0、1、2 和 newProp。 for..of 循环遍历 arr 数据结构的值并在控制台中记录 a、b、c

     **[⬆ Back to Top](#table-of-contents)**

419. ### How do you define instance and non-instance properties

     实例属性必须在类方法内部定义。例如，下边name和age属性定义在构造函数内部

     ```javascript
     class Person {
       constructor(name, age) {
         this.name = name;
         this.age = age;
       }
     }
     ```

     但是静态（类）和原型数据属性必须在类声明之外定义。让我们为 Person 类指定age值，如下所示

     ```javascript
     Person.staticAge = 30;
     Person.prototype.prototypeAge = 40;
     ```

     **[⬆ Back to Top](#table-of-contents)**

420. ### What is the difference between isNaN and Number.isNaN?

     1. **isNaN**: 全局函数 `isNaN` 将参数转换为数字，如果结果值为 NaN，则返回 true
     2. **Number.isNaN**: 此方法不转换参数。但当类型为数字且值为 NaN 时返回 true

     Let's see the difference with an example,
     让我们用一个例子看下区别

     ```javascript
     isNaN(‘hello’);   // true
     Number.isNaN('hello'); // false
     ```

     **[⬆ Back to Top](#table-of-contents)**

421. ### How to invoke an IIFE without any extra brackets?

     立即执行函数表达式（IIFE）需要一对圆括号包裹含有一组语句集合的函数

     ```js
     (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     由于IIFE和void操作符都会抛弃表达式的结果，您可以使用 IIFE 的 `void operator` 避免额外的括号，如下所示

     ```js
     void (function (dt) {
       console.log(dt.toLocaleTimeString());
     })(new Date());
     ```

     **[⬆ Back to Top](#table-of-contents)**

422. ### Is that possible to use expressions in switch cases?

     您可能已经看到在 switch 条件中使用的表达式，但也可以通过为 switch 条件分配 true 值来使用 switch case。让我们以基于温度的天气状况为例

     ```js
     const weather = (function getWeather(temp) {
       switch (true) {
         case temp < 0:
           return "freezing";
         case temp < 10:
           return "cold";
         case temp < 24:
           return "cool";
         default:
           return "unknown";
       }
     })(10);
     ```

     **[⬆ Back to Top](#table-of-contents)**

423. ### What is the easiest way to ignore promise errors?

     忽略promise错误最简单和安全的方法就是void错误。这种方法也对ESLint友好

     ```js
     await promise.catch((e) => void e);
     ```

     **[⬆ Back to Top](#table-of-contents)**

424. ### How do style the console output using CSS?

     您可以使用 CSS 格式化内容说明符 %c 将 CSS 样式添加到控制台输出。控制台字符串消息可以附加在另一个参数中的说明符和 CSS 样式之后。让我们使用 console.log 和 CSS 说明符将颜色文本打印成红色，如下所示

     ```js
     console.log("%cThis is a red text", "color:red");
     ```

     也可以为内容添加更多样式。比如上面的文字可以修改font-size

     ```js
     console.log(
       "%cThis is a red text with bigger font",
       "color:red; font-size:20px"
     );
     ```

     **[⬆ Back to Top](#table-of-contents)**

425. ### What is nullish coalescing operator (??)?

     是一个逻辑运算符，当其左侧操作数为null或undefined时返回其右侧操作数，否则返回其左侧操作数。这可以与逻辑 OR (||) 运算符进行对比，如果左侧操作数是任何假值，则返回右侧操作数，而不仅仅是 null 或 undefined

     ```js
     console.log(null ?? true); // true
     console.log(false ?? true); // false
     console.log(undefined ?? true); // true
     ```

     **[⬆ Back to Top](#table-of-contents)**

426. ### How do you group and nest console output?

     `console.group()` 可用于对相关日志消息进行分组，以便能够轻松读取日志并使用 console.groupEnd() 闭合分组。除此之外，您还可以嵌套组，允许以分层方式输出消息

     例如，如果你记录用户的详情

     ```js
     console.group("User Details");
     console.log("name: Sudheer Jonna");
     console.log("job: Software Developer");

     // Nested Group
     console.group("Address");
     console.log("Street: Commonwealth");
     console.log("City: Los Angeles");
     console.log("State: California");

     console.groupEnd();
     ```

     You can also use `console.groupCollapsed()` instead of `console.group()` if you want the groups to be collapsed by default.

     **[⬆ Back to Top](#table-of-contents)**

427. ### What is the difference between dense and sparse arrays?

     从第一个(0) 到 最后一个(array.length - 1) 的每个索引处都包含项目的数组称为密集数组。若任何索引处至少缺少一项，则该数组称为稀疏数组

     让我们看看下边两种数组

     ```js
     const avengers = ["Ironman", "Hulk", "CaptainAmerica"];
     console.log(avengers[0]); // 'Ironman'
     console.log(avengers[1]); // 'Hulk'
     console.log(avengers[2]); // 'CaptainAmerica'
     console.log(avengers.length); // 3

     const justiceLeague = ["Superman", "Aquaman", , "Batman"];
     console.log(justiceLeague[0]); // 'Superman'
     console.log(justiceLeague[1]); // 'Aquaman'
     console.log(justiceLeague[2]); // undefined
     console.log(justiceLeague[3]); // 'Batman'
     console.log(justiceLeague.length); // 4
     ```

     **[⬆ Back to Top](#table-of-contents)**

428. ### What are the different ways to create sparse arrays?

     在JavaScript中有4中不同方法创建稀疏数组

     1. **数组字面量:** 当使用数组字面量时忽略一个值
        ```js
        const justiceLeague = ["Superman", "Aquaman", , "Batman"];
        console.log(justiceLeague); // ['Superman', 'Aquaman', empty ,'Batman']
        ```
     2. **Array()构造器:** 调用 Array(length) 或者 new Array(length)
        ```js
        const array = Array(3);
        console.log(array); // [empty, empty ,empty]
        ```
     3. **delete操作符:** 对数组使用操作符 delete array[index]
        ```js
        const justiceLeague = ["Superman", "Aquaman", "Batman"];
        delete justiceLeague[1];
        console.log(justiceLeague); // ['Superman', empty, ,'Batman']
        ```
     4. **增加length属性:** 增加数组的length属性值
        `js const justiceLeague = ['Superman', 'Aquaman', 'Batman']; justiceLeague.length = 5; console.log(justiceLeague); // ['Superman', 'Aquaman', 'Batman', empty, empty] `
        **[⬆ Back to Top](#table-of-contents)**

429. ### What is the difference between setTimeout, setImmediate and process.nextTick?

     1. **SetTimeout:** setTimeout() 是在延迟毫秒后安排一次回调的执行
     2. **SetImmediate:** setImmediate函数用来在当前事件循环结束后立马执行一个函数
     3. **Process NextTick:** 如果在给定阶段调用 process.nextTick()，则传递给 process.nextTick() 的所有回调将在事件循环继续之前解决。如果 process.nextTick() 被递归调用，这将阻塞事件循环并创建 I/O 饥饿

     **[⬆ Back to Top](#table-of-contents)**

430. ### How do you reverse an array without modifying original array?

     `reverse()` 方法反转数组中元素的顺序，但它会改变原始数组。我们举一个简单的例子来说明

     ```javascript
     const originalArray = [1, 2, 3, 4, 5];
     const newArray = originalArray.reverse();

     console.log(newArray); // [ 5, 4, 3, 2, 1]
     console.log(originalArray); // [ 5, 4, 3, 2, 1]
     ```

     有几个不会修改原始数组的方案。让我们看下

     1. **使用 slice 和 reverse 方法:**
        在这种情况下，只需在数组上调用 `slice()` 方法来创建一个浅拷贝，然后在该拷贝上调用 `reverse()` 方法

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.slice().reverse(); //Slice an array gives a new copy

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     2. **使用展开运算符和reverse方法:**
        在这种情况下，让我们使用展开语法 (...) 创建数组的副本，然后在副本上调用 `reverse()` 方法

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = [...originalArray].reverse();

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     3. **使用 reduce方法 和 展开运算符:**
        这里对数组元素执行reduce函数并使用展开展语法将累积的数组附加到右侧

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduce((accumulator, value) => {
          return [value, ...accumulator];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     4. **使用 reduceRight 方法和展开运算符:**

        这里对数组元素执行一个右侧reducer函数（即reduce方法的相反方向）并使用展开语法将累积的数组附加到左侧

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          return [...accumulator, value];
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     5. **使用 reduceRight 和 push 方法:**
        这里对数组元素执行一个右侧的reducer函数（即reduce方法的相反方向）并将迭代值push到accumulator

        ```javascript
        const originalArray = [1, 2, 3, 4, 5];
        const newArray = originalArray.reduceRight((accumulator, value) => {
          accumulator.push(value);
          return accumulator;
        }, []);

        console.log(originalArray); // [1, 2, 3, 4, 5]
        console.log(newArray); // [ 5, 4, 3, 2, 1]
        ```

     **[⬆ Back to Top](#table-of-contents)**

431. ### How do you create custom HTML element?

     创建自定义HTML元素主要包括两步

     1. **定义你的自定义HTML元素:** 首先，您需要通过扩展 HTMLElement 类来定义一些自定义类
        之后使用 `connectedCallback` 方法定义您的组件属性（样式、文本等）
        **注意:** 浏览器暴露了一个名为 `customElements.define` 的函数，以便重用元素
        ```javascript
        class CustomElement extends HTMLElement {
          connectedCallback() {
            this.innerHTML = "This is a custom element";
          }
        }
        customElements.define("custom-element", CustomElement);
        ```
     2. **像其他HTML元素一样使用自定义的元素:** 像HTML标签一样生情你的自定义元素

     ```javascript
        <body>
             <custom-element>
        </body>
     ```

     **[⬆ Back to Top](#table-of-contents)**

432. ### What is global execution context?

     全局执行上下文是 JavaScript 引擎在执行任何代码之前（即文件首次在浏览器中加载时）创建的默认或第一个执行上下文。所有不在函数或对象内的全局代码都将在这个全局执行上下文中执行。由于 JS 引擎是单线程的，所以只有一个全局环境，并且只有一个全局执行上下文

     例如，除了任何函数或对象中的代码之外的以下代码在全局执行上下文中执行

     ```javascript
     var x = 10;

     function A() {
       console.log("Start function A");

       function B() {
         console.log("In function B");
       }

       B();
     }

     A();

     console.log("GlobalContext");
     ```

     **[⬆ Back to Top](#table-of-contents)**

433. ### What is function execution context?

     每当调用函数时，JavaScript 引擎都会在全局执行上下文 (GEC) 中创建一种不同类型的执行上下文，称为函数执行上下文 (FEC)，以执行该函数中的代码

     **[⬆ Back to Top](#table-of-contents)**

434. ### What is debouncing?

     防抖是一种编程模式，它允许将某些代码的执行延迟到指定时间，以避免不必要的 _CPU 循环、API 调用和提高性能_ 。 debounce 函数确保您的代码仅在每个用户输入时触发一次。常见用例是搜索框建议、文本字段自动保存和消除双击

     假设您想只在完成输入之后显示搜索查询的建议。因此，你在这里编写了一个防抖函数，其中用户在 500 毫秒内继续写入字符，然后使用 `clearTimeout` 清除前一个计时器，并在300毫秒后重新安排 API 调用/DB 查询

     ```js
     function debounce(func, timeout = 500) {
       let timer;
       return (...args) => {
         clearTimeout(timer);
         timer = setTimeout(() => {
           func.apply(this, args);
         }, timeout);
       };
     }
     function fetchResults() {
       console.log("Fetching input suggestions");
     }
     const processChange = debounce(() => fetchResults());
     ```

     _debounce()_ 函数可以被用在Input，button和window事件中

     **Input:**

     ```html
     <input type="text" onkeyup="processChange()" />
     ```

     **Button:**

     ```html
     <button onclick="processChange()">Click me</button>
     ```

     **Windows event:**

     ```html
     window.addEventListener("scroll", processChange);
     ```

     **[⬆ Back to Top](#table-of-contents)**

435. ### What is throttling?

     节流是一种用于限制事件处理函数执行的技术，即使该事件由于用户操作而连续触发也是如此。常见的用例是浏览器调整大小、窗口滚动等

     下面的示例创建一个节流函数，以减少每个微小更改的事件数量，并每 100 毫秒触发一次滚动事件，第一个事件除外

     ```js
     const throttle = (func, limit) => {
       let inThrottle;
       return (...args) => {
         if (!inThrottle) {
           func.apply(this, args);
           inThrottle = true;
           setTimeout(() => (inThrottle = false), limit);
         }
       };
     };
     window.addEventListener("scroll", () => {
       throttle(handleScrollAnimation, 100);
     });
     ```
 
     **[⬆ Back to Top](#table-of-contents)**

436. ### What is optional chaining?

     根据 MDN 官方文档，可选的链式运算符 (?.) 允许读取位于连接对象链深处的属性的值，而无需明确验证链中的每个引用是否有效

     ?.运算符就像 . 链式运算符，除了如果引用为空（null 或undefined）时不会导致错误，表达式会短路并返回undefined值。与函数调用一起使用时，如果给定函数不存在，则返回 undefined

     ```js
      const adventurer = {
        name: 'Alice',
        cat: {
          name: 'Dinah'
        }
      };

      const dogName = adventurer.dog?.name;
      console.log(dogName);
      // expected output: undefined

      console.log(adventurer.someNonExistentMethod?.());
      // expected output: undefined
     ```

### Coding Exercise

#### 1. 下边代码的输出是什么

```javascript
var car = new Vehicle("Honda", "white", "2010", "UK");
console.log(car);

function Vehicle(model, color, year, country) {
  this.model = model;
  this.color = color;
  this.year = year;
  this.country = country;
}
```

- 1: Undefined
- 2: ReferenceError
- 3: null
- 4: {model: "Honda", color: "white", year: "2010", country: "UK"}

<details><summary><b>答案</b></summary>
<p>

##### Answer: 4

函数声明类似任何变量会被提升。所以`Vehicle`函数的位置声明没有什么区别

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 2. What is the output of below code

```javascript
function foo() {
  let x = (y = 0);
  x++;
  y++;
  return x;
}

console.log(foo(), typeof x, typeof y);
```

- 1: 1, undefined and undefined
- 2: ReferenceError: X is not defined
- 3: 1, undefined and number
- 4: 1, number and number

<details><summary><b>答案</b></summary>
<p>

##### Answer: 3

由于自增运算符`foo()`显然会返回1。但是 `let x = y = 0`声明了局部变量x。而y偶然被声明为了全局变量。该语句等价于

```javascript
let x;
window.y = 0;
x = window.y;
```

由于块作用域变量 x 在函数之外是undefined，因此类型也是undefined。而全局变量 `y` 在函数外可用，其值为 0，类型为数字


</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 3. What is the output of below code

```javascript
function main() {
  console.log("A");
  setTimeout(function print() {
    console.log("B");
  }, 0);
  console.log("C");
}
main();
```

- 1: A, B and C
- 2: B, A and C
- 3: A and C
- 4: A, C and B

<details><summary><b>答案</b></summary>
<p>

##### Answer: 4

语句顺序基于事件循环机制。语句的顺序遵循以下顺序

1. 首先，main函数被压入栈中
2. 然后浏览器将main函数的第一个语句（即 A的console.log）压入栈中，执行并立即出栈
3. 但是 `setTimeout` 语句移至浏览器 API 以应用回调延迟
4. 同时，C的console.log加入栈中，执行并出栈
5. `setTimeout`回调从浏览器API进入了消息队列
6. `main`出栈因为没有语句可执行
7. 由于栈是空的，回调从消息队列进入到了栈中
8. B的console.log入栈并在控制台展示

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 4. What is the output of below equality check

```javascript
console.log(0.1 + 0.2 === 0.3);
```

- 1: false
- 2: true

<details><summary><b>答案</b></summary>
<p>

##### Answer: 1

这是由于浮点数学问题。由于浮点数以二进制格式编码，因此对它们的加法运算会导致取舍错误。因此，浮点数的比较不会给出预期的结果
可以在这找到更多的详情 [0.30000000000000004.com/](https://0.30000000000000004.com/)

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 5. What is the output of below code

```javascript
var y = 1;
if (function f() {}) {
  y += typeof f;
}
console.log(y);
```

- 1: 1function
- 2: 1object
- 3: ReferenceError
- 4: 1undefined

<details><summary><b>答案</b></summary>
<p>

##### Answer: 4（不同浏览器表现不一样，有的是1object）

上述代码片段的主要点在于

1. 你可以在 if 语句中看到函数表达式而不是函数声明。所以总会返回true
2. 由于未声明(或赋值) , f 是 undefined typeof f 也是undefined.（译注：不同浏览器表现不一致）

换句话说，它和下边一样

```javascript
var y = 1;
if ("foo") {
  y += typeof f;
}
console.log(y);
```

**注意:** Edge浏览器会返回1object（译注：safari也一样）

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 6. What is the output of below code

```javascript
function foo() {
  return;
  {
    message: "Hello World";
  }
}
console.log(foo());
```

- 1: Hello World
- 2: Object {message: "Hello World"}
- 3: Undefined
- 4: SyntaxError

<details><summary><b>答案</b></summary>
<p>

##### Answer: 3

这是一个分号问题。通常分号在JavaScript中是可选的。如果有任何语句（此例中是return）缺少分号，会自动在后边插入。因此，函数返回undefined

而如果左花括号与 return 关键字一起，则函数将按预期返回

```javascript
function foo() {
  return {
    message: "Hello World",
  };
}
console.log(foo()); // {message: "Hello World"}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 7. What is the output of below code

```javascript
var myChars = ["a", "b", "c", "d"];
delete myChars[0];
console.log(myChars);
console.log(myChars[0]);
console.log(myChars.length);
```

- 1: [empty, 'b', 'c', 'd'], empty, 3
- 2: [null, 'b', 'c', 'd'], empty, 3
- 3: [empty, 'b', 'c', 'd'], undefined, 4
- 4: [null, 'b', 'c', 'd'], undefined, 4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

`delete` 运算符将删除对象属性，但不会重新索引数组或更改其长度。所以数组的数量或元素或长度不会改变
如果你尝试打印 myChars 那么可以观察到它没有设置undefined，而是从数组中删除了该属性。较新版本的 Chrome 使用 `empty` 而不是 `undefined` 以使区别更加清晰

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 8. What is the output of below code in latest Chrome

```javascript
var array1 = new Array(3);
console.log(array1);

var array2 = [];
array2[2] = 100;
console.log(array2);

var array3 = [, , ,];
console.log(array3);
```

- 1: [undefined × 3], [undefined × 2, 100], [undefined × 3]
- 2: [empty × 3], [empty × 2, 100], [empty × 3]
- 3: [null × 3], [null × 2, 100], [null × 3]
- 4: [], [100], []

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

最新的 chrome 版本使用 empty x n 表示法显示“稀疏数组”（它们充满了空洞）。而旧版本是 undefined x n 表示
**注意:** 最新版本的FF展示成 `n empty slots`.

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 9. What is the output of below code

```javascript
const obj = {
  prop1: function () {
    return 0;
  },
  prop2() {
    return 1;
  },
  ["prop" + 3]() {
    return 2;
  },
};

console.log(obj.prop1());
console.log(obj.prop2());
console.log(obj.prop3());
```

- 1: 0, 1, 2
- 2: 0, { return 1 }, 2
- 3: 0, { return 1 }, { return 2 }
- 4: 0, 1, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

ES6为对象提供了函数定义和属性的简写。所以prop2和prop3被当作一般的函数值

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 10. What is the output of below code

```javascript
console.log(1 < 2 < 3);
console.log(3 > 2 > 1);
```

- 1: true, true
- 2: true, false
- 3: SyntaxError, SyntaxError,
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

关键点是如果语句包含襄公的运算符（如<或者>），则会被从左到右计算
第一个语句遵循下边的顺序

1. console.log(1 < 2 < 3);
2. console.log(true < 3);
3. console.log(1 < 3); // True converted as `1` during comparison
4. True

而第二个语句遵守下边的顺序

1. console.log(3 > 2 > 1);
2. console.log(true > 1);
3. console.log(1 > 1); // False converted as `0` during comparison
4. False

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 11. What is the output of below code in non-strict mode

```javascript
function printNumbers(first, second, first) {
  console.log(first, second, first);
}
printNumbers(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

非严格模式下，一般的JavaScript函数允许重名参数。上边的代码片段第一个和第三个形参重名。
第一个参数的值映射到传递给函数的第三个参数。因此，第三个实参覆盖了第一个参数。


**注意:** 严格模式中，重名参数会抛出语法错误

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 12. What is the output of below code

```javascript
const printNumbersArrow = (first, second, first) => {
  console.log(first, second, first);
};
printNumbersArrow(1, 2, 3);
```

- 1: 1, 2, 3
- 2: 3, 2, 3
- 3: SyntaxError: Duplicate parameter name not allowed in this context
- 4: 1, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

不像一般的函数，箭头函数无论在严格或者非严格模式下都不允许重名参数。所以你可以在控制台中看到`SyntaxError`

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 13. What is the output of below code

```javascript
const arrowFunc = () => arguments.length;
console.log(arrowFunc(1, 2, 3));
```

- 1: ReferenceError: arguments is not defined
- 2: 3
- 3: undefined
- 4: null

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

箭头函数没有 `arguments, super, this, or new.target` 绑定。因此，对 `arguments` 变量的任何引用都会尝试解析为词法封闭环境中的绑定。在这个用例中，arguments变量没有在箭头函数外定义。因此，会收到引用错误

而普通函数提供了传给函数的实参的数量

```javascript
const func = function () {
  return arguments.length;
};
console.log(func(1, 2, 3));
```

但是如果你还是想使用箭头函数，实参的剩余运算符会提供预期的arguments

```javascript
const arrowFunc = (...args) => args.length;
console.log(arrowFunc(1, 2, 3));
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 14. What is the output of below code

```javascript
console.log(String.prototype.trimLeft.name === "trimLeft");
console.log(String.prototype.trimLeft.name === "trimStart");
```

- 1: True, False
- 2: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

为了和像`String.prototype.padStart`函数保持一直，移除空格的标准方法名被考虑为 `trimStart`。由于web兼容性原因，旧方法名称“trimLeft”仍然充当“trimStart”的别名。因此，'trimLeft'的原型一直是'trimStart'

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 15. What is the output of below code

```javascript
console.log(Math.max());
```

- 1: undefined
- 2: Infinity
- 3: 0
- 4: -Infinity

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

-Infinity 是初始化的比较值，因为几乎所有其他值都更大。因此，当没有提供参数时，将返回 -Infinity
**注意:** 0个实参是合法用例

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 16. What is the output of below code

```javascript
console.log(10 == [10]);
console.log(10 == [[[[[[[10]]]]]]]);
```

- 1: True, True
- 2: True, False
- 3: False, False
- 4: False, True

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

根据 ECMAScript 规范（ECMA-262）中的比较算法，上面的表达式转换为 JS 如下

```javascript
10 === Number([10].valueOf().toString()); // 10
```

所以不管数字周围有多少括号（[]），总是会转换表达式为数字
</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 17. What is the output of below code

```javascript
console.log(10 + "10");
console.log(10 - "10");
```

- 1: 20, 0
- 2: 1010, 0
- 3: 1010, 10-10
- 4: NaN, NaN

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

连接运算符 (+) 适用于数字和字符串类型。因此，如果任何操作数是字符串类型，则两个操作数都连接为字符串。而减法（-）运算符尝试将操作数转换为数字类型

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 18. What is the output of below code

```javascript
console.log([0] == false);
if ([0]) {
  console.log("I'm True");
} else {
  console.log("I'm False");
}
```

- 1: True, I'm True
- 2: True, I'm False
- 3: False, I'm True
- 4: False, I'm False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

在比较运算符中，表达式 `[0]` 转换为 Number([0].valueOf().toString()) 解析为 false。而 `[0]` 只是变成了一个没有任何转换的真值，因为没有比较运算符

</p>
</details>

#### 19. What is the output of below code

```javascript
console.log([1, 2] + [3, 4]);
```

- 1: [1,2,3,4]
- 2: [1,2][3,4]
- 3: SyntaxError
- 4: 1,23,4

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

+ 运算符不是为数组定义的。所以它将数组转换为字符串并将它们连接起来

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 20. What is the output of below code

```javascript
const numbers = new Set([1, 1, 2, 3, 4]);
console.log(numbers);

const browser = new Set("Firefox");
console.log(browser);
```

- 1: {1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}
- 2: {1, 2, 3, 4}, {"F", "i", "r", "e", "o", "x"}
- 3: [1, 2, 3, 4], ["F", "i", "r", "e", "o", "x"]
- 4: {1, 1, 2, 3, 4}, {"F", "i", "r", "e", "f", "o", "x"}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

由于 `Set` 对象是不重复值的集合，不允许集合中存在重复值。同时，也是大小写敏感的数据结构

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 21. What is the output of below code

```javascript
console.log(NaN === NaN);
```

- 1: True
- 2: False

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

JavaScript 遵循 IEEE 754 规范标准. 根据本规范，浮点数与 NaN 永远不会相等

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 22. What is the output of below code

```javascript
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.indexOf(NaN));
```

- 1: 4
- 2: NaN
- 3: SyntaxError
- 4: -1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

`indexOf` 在内部使用严格相等运算符 (===) 并且 `NaN === NaN` 为 false。由于 indexOf 无法在数组中找到 NaN，因此它总是返回 -1
但是可以使用 `Array.prototype.findIndex` 方法来找出 NaN 在数组中的索引，或者可以使用 `Array.prototype.includes` 来检查 NaN 是否存在于数组中

```javascript
let numbers = [1, 2, 3, 4, NaN];
console.log(numbers.findIndex(Number.isNaN)); // 4

console.log(numbers.includes(NaN)); // true
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 23. What is the output of below code

```javascript
let [a, ...b,] = [1, 2, 3, 4, 5];
console.log(a, b);
```

- 1: 1, [2, 3, 4, 5]
- 2: 1, {2, 3, 4, 5}
- 3: SyntaxError
- 4: 1, [2, 3, 4]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

当使用剩余参数时，尾逗号是不允许的并会抛出语法错误
如果移除尾逗号则会像第一个答案那样显示

```javascript
let [a, ...b] = [1, 2, 3, 4, 5];
console.log(a, b); // 1, [2, 3, 4, 5]
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 25. What is the output of below code

```javascript
async function func() {
  return 10;
}
console.log(func());
```

- 1: Promise {\<fulfilled\>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {\<rejected\>: 10}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

async函数总是返回一个promise。但即使async函数的返回值不是显式的 Promise，它也会被隐式地包装在 promise 中。上面的 async 函数等价于下面的表达式

```javascript
function func() {
  return Promise.resolve(10);
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 26. What is the output of below code

```javascript
async function func() {
  await 10;
}
console.log(func());
```

- 1: Promise {\<fulfilled\>: 10}
- 2: 10
- 3: SyntaxError
- 4: Promise {\<resolved\>: undefined}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

await 表达式返回值 10 并带有 promise 解析，并且每个 await 表达式之后的代码可以被视为存在于 `.then` 回调中。在这种情况下，函数末尾没有返回表达式。因此，`undefined` 的默认返回值作为 promise 的解析返回。上面的 async 函数等价于下面的表达式

```javascript
function func() {
  return Promise.resolve(10).then(() => undefined);
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 27. What is the output of below code

```javascript
function delay() {
  return new Promise(resolve => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function processArray(array) {
  array.forEach(item => {
    await delayedLog(item);
  })
}

processArray([1, 2, 3, 4]);
```

- 1: SyntaxError
- 2: 1, 2, 3, 4
- 3: 4, 4, 4, 4
- 4: 4, 3, 2, 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

即使“processArray”是async函数，我们在 `forEach` 使用的匿名函数也是同步的。如果在同步函数内使用await会抛出语法错误

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 28. What is the output of below code

```javascript
function delay() {
  return new Promise((resolve) => setTimeout(resolve, 2000));
}

async function delayedLog(item) {
  await delay();
  console.log(item);
}

async function process(array) {
  array.forEach(async (item) => {
    await delayedLog(item);
  });
  console.log("Process completed!");
}
process([1, 2, 3, 5]);
```

- 1: 1 2 3 5 and Process completed!
- 2: 5 5 5 5 and Process completed!
- 3: Process completed! and 5 5 5 5
- 4: Process completed! and 1 2 3 5

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

forEach 方法不会等到所有项目都完成后，它只是运行任务并继续下一步。因此，最后一条语句首先显示，然后是一系列promise解析结果

但是你可以使用for...of循环控制数组

```javascript
async function processArray(array) {
  for (const item of array) {
    await delayedLog(item);
  }
  console.log("Process completed!");
}
```

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 29. What is the output of below code

```javascript
var set = new Set();
set.add("+0").add("-0").add(NaN).add(undefined).add(NaN);
console.log(set);
```

- 1: Set(4) {"+0", "-0", NaN, undefined}
- 2: Set(3) {"+0", NaN, undefined}
- 3: Set(5) {"+0", "-0", NaN, undefined, NaN}
- 4: Set(4) {"+0", NaN, undefined, NaN}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

Set 几乎没有相等性检查的例外情况

1. 所有的 NaN 值都相等
2. +0 和 -0 被视作不同的值

</p>
</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 30. What is the output of below code

```javascript
const sym1 = Symbol("one");
const sym2 = Symbol("one");

const sym3 = Symbol.for("two");
const sym4 = Symbol.for("two");

cnsooe.log(sym1 === sym2, sym3 === sym4);
```

- 1: true, true
- 2: true, false
- 3: false, true
- 4: false, false

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

Symbol遵循以下约定

1. 返回的每个symbol值都是唯一的，与可选字符串无关
2. `Symbol.for()` 函数在全局符号注册表列表中创建一个符号。但它不一定在每次调用时都创建一个新符号，它首先检查具有给定键的符号是否已存在于注册表中，如果找到则返回该符号。否则在注册表中创建一个新符号

**注意:** 符号描述对于调试很有用

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 31. What is the output of below code

```javascript
const sym1 = new Symbol("one");
console.log(sym1);
```

- 1: SyntaxError
- 2: one
- 3: Symbol('one')
- 4: Symbol

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

`Symbol`只是一个标准函数而不是一个对象构造器（不像其他原语 new Boolean, new String 和 new Number。所以若尝试用new操作符调用它会导致TyoeError

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 32. What is the output of below code

```javascript
let myNumber = 100;
let myString = "100";

if (!typeof myNumber === "string") {
  console.log("It is not a string!");
} else {
  console.log("It is a string!");
}

if (!typeof myString === "number") {
  console.log("It is not a number!");
} else {
  console.log("It is a number!");
}
```

- 1: SyntaxError
- 2: It is not a string!, It is not a number!
- 3: It is not a string!, It is a number!
- 4: It is a string!, It is a number!

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

`typeof myNumber (或) typeof myString`的返回值总是真值("number" 或者 "string"). 由于 ! 操作符将值转换成boolean值,  `!typeof myNumber 或 !typeof myString`的值总是 false.因此if条件会失败条件控制进入else块中

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 33. What is the output of below code

```javascript
console.log(
  JSON.stringify({ myArray: ["one", undefined, function () {}, Symbol("")] })
);
console.log(
  JSON.stringify({ [Symbol.for("one")]: "one" }, [Symbol.for("one")])
);
```

- 1: {"myArray":['one', undefined, {}, Symbol]}, {}
- 2: {"myArray":['one', null,null,null]}, {}
- 3: {"myArray":['one', null,null,null]}, "{ [Symbol.for('one')]: 'one' }, [Symbol.for('one')]"
- 4: {"myArray":['one', undefined, function(){}, Symbol('')]}, {}

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

symbol有以下约束

1. undefined, Functions, 和 Symbols不是合法JSON值。所以那些值要么被忽略（在对象中）要么被修改成null（在数组中）。因此，数组的值会返回null
2. 所有的symbol的键属性都会被完全忽略。因此返回空对象（{}）

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 34. What is the output of below code

```javascript
class A {
  constructor() {
    console.log(new.target.name);
  }
}

class B extends A {
  constructor() {
    super();
  }
}

new A();
new B();
```

- 1: A, A
- 2: A, B

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

使用构造函数，`new.target` 指的是由 new 直接调用的构造函数（指向被初始化的类的类定义）。这也适用于构造函数在父类中并且是从子构造函数委托的情况

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 35. What is the output of below code

```javascript
const [x, ...y,] = [1, 2, 3, 4];
console.log(x, y);
```

- 1: 1, [2, 3, 4]
- 2: 1, [2, 3]
- 3: 1, [2]
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

抛出语法错误因为剩余元素不应该有尾逗号。总是应该考虑对最后的元素使用剩余运算符

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 36. What is the output of below code

```javascript
const { a: x = 10, b: y = 20 } = { a: 30 };

console.log(x);
console.log(y);
```

- 1: 30, 20
- 2: 10, 20
- 3: 10, undefined
- 4: 30, undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

对象属性遵循以下规则

1. 可以检索对象属性并将其分配给具有不同名称的变量
2. 当获得的值是`undefined`时属性赋予一个默认值

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 37. What is the output of below code

```javascript
function area({ length = 10, width = 20 }) {
  console.log(length * width);
}

area();
```

- 1: 200
- 2: Error
- 3: undefined
- 4: 0

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

如果省略解构对象的右侧赋值，则该函数将在调用时寻找至少提供一个实参。否则将收到错误`Error: Cannot read property 'length' of undefined`，如上所述

你可以改成下边这样来避免错误

1. **至少传入一个空对象:**

```javascript
function area({ length = 10, width = 20 }) {
  console.log(length * width);
}

area({});
```

2. **赋予默认空对象:**

```javascript
function area({ length = 10, width = 20 } = {}) {
  console.log(length * width);
}

area();
```

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 38. What is the output of below code

```javascript
const props = [
  { id: 1, name: "John" },
  { id: 2, name: "Jack" },
  { id: 3, name: "Tom" },
];

const [, , { name }] = props;
console.log(name);
```

- 1: Tom
- 2: Error
- 3: undefined
- 4: John

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

可以将数组和对象解构结合起来。在这种情况下，首先访问数组 props 中的第三个元素，然后是对象中的 name 属性

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 39. What is the output of below code

```javascript
function checkType(num = 1) {
  console.log(typeof num);
}

checkType();
checkType(undefined);
checkType("");
checkType(null);
```

- 1: number, undefined, string, object
- 2: undefined, undefined, string, object
- 3: number, number, string, object
- 4: number, number, number, number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

如果函数参数被隐式设置（不传递参数）或显式设置为undefined，则参数的值是默认参数。而对于其他虚假值（'' 或 null），实参的值会作为形参传递

因此，函数调用的结果分类如下


1. 前两个函数打印了日志数字类型，因为默认值的类型是数字
2. '' 和 null 的值类型分别是字符串和对象

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 40. What is the output of below code

```javascript
function add(item, items = []) {
  items.push(item);
  return items;
}

console.log(add("Orange"));
console.log(add("Apple"));
```

- 1: ['Orange'], ['Orange', 'Apple']
- 2: ['Orange'], ['Apple']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

由于在调用时计算默认参数，因此每次调用函数时都会创建一个新对象。所以在这种情况下，新数组被创建并且一个元素被push到默认的空数组

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 41. What is the output of below code

```javascript
function greet(greeting, name, message = greeting + " " + name) {
  console.log([greeting, name, message]);
}

greet("Hello", "John");
greet("Hello", "John", "Good morning!");
```

- 1: SyntaxError
- 2: ['Hello', 'John', 'Hello John'], ['Hello', 'John', 'Good morning!']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

由于先定义的形参在后边的默认参数中也可以访问，这个代码片段不会抛出任何错误

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 42. What is the output of below code

```javascript
function outer(f = inner()) {
  function inner() {
    return "Inner";
  }
}
outer();
```

- 1: ReferenceError
- 2: Inner

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

在函数体内声明的函数和变量不能被形参默认值初始化引用。如果仍尝试访问，则会抛出一个运行时的引用错误（即 `inner` 未被定义）

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 43. What is the output of below code

```javascript
function myFun(x, y, ...manyMoreArgs) {
  console.log(manyMoreArgs);
}

myFun(1, 2, 3, 4, 5);
myFun(1, 2);
```

- 1: [3, 4, 5], undefined
- 2: SyntaxError
- 3: [3, 4, 5], []
- 4: [3, 4, 5], [undefined]

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

、剩余参数用于承载函数的剩余参数，若实参未提供则会成为空数组。

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 44. What is the output of below code

```javascript
const obj = { key: "value" };
const array = [...obj];
console.log(array);
```

- 1: ['key', 'value']
- 2: TypeError
- 3: []
- 4: ['key']

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

扩展语法只能应用于可迭代对象。默认情况下，对象是不可迭代的，但当它们在数组中使用时，或者与诸如`map()、reduce() 和assign()` 之类的迭代函数一起使用时，它们变得可迭代。如果你仍然尝试这样做，它仍然会抛出 `TypeError: obj is not iterable`

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 45. What is the output of below code

```javascript
function* myGenFunc() {
  yield 1;
  yield 2;
  yield 3;
}
var myGenObj = new myGenFunc();
console.log(myGenObj.next().value);
```

- 1: 1
- 2: undefined
- 3: SyntaxError
- 4: TypeError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

生成器不是可以构造的类型。但是如果你继续这么做，会抛出一个错误 "TypeError: myGenFunc is not a constructor"

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 46. What is the output of below code

```javascript
function* yieldAndReturn() {
  yield 1;
  return 2;
  yield 3;
}

var myGenObj = yieldAndReturn();
console.log(myGenObj.next());
console.log(myGenObj.next());
console.log(myGenObj.next());
```

- 1: { value: 1, done: false }, { value: 2, done: true }, { value: undefined, done: true }
- 2: { value: 1, done: false }, { value: 2, done: false }, { value: undefined, done: true }
- 3: { value: 1, done: false }, { value: 2, done: true }, { value: 3, done: true }
- 4: { value: 1, done: false }, { value: 2, done: false }, { value: 3, done: true }

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

生成器函数中的 return 语句将使生成器结束。如果返回一个值，它将被设置为对象的 value 属性，并且 done 属性为 true。当一个生成器结束后，后续的 next() 调用会返回一个这种格式的对象：`{value: undefined, done: true}`

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 47. What is the output of below code

```javascript
const myGenerator = (function* () {
  yield 1;
  yield 2;
  yield 3;
})();
for (const value of myGenerator) {
  console.log(value);
  break;
}

for (const value of myGenerator) {
  console.log(value);
}
```

- 1: 1,2,3 and 1,2,3
- 2: 1,2,3 and 4,5,6
- 3: 1 and 1
- 4: 1

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

一旦迭代器结束生成器不应该被重复使用。也就是说，上边的循环（结束或者使用break & return），生成器被关闭尝试再次迭代并不会在产生更多的结果。因此，第二个循环不会打印任何值

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 48. What is the output of below code

```javascript
const num = 0o38;
console.log(num);
```

- 1: SyntaxError
- 2: 38

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

如果在八进制字面量中使用了一个非法数字（在0-7之外），JavaScript会抛出语法错误。在ES5中，会将八进制字面量当作十进制

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 49. What is the output of below code

```javascript
const squareObj = new Square(10);
console.log(squareObj.area);

class Square {
  constructor(length) {
    this.length = length;
  }

  get area() {
    return this.length * this.length;
  }

  set area(value) {
    this.area = value;
  }
}
```

- 1: 100
- 2: ReferenceError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

不像函数声明，类声明并不会被提升。也就是说，首先需要声明类然后才能访问，否则会抛出引用错误 "Uncaught ReferenceError: Square is not defined"

**注意:** 类表达式和类声明有相同的提升限制

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 50. What is the output of below code

```javascript
function Person() {}

Person.prototype.walk = function () {
  return this;
};

Person.run = function () {
  return this;
};

let user = new Person();
let walk = user.walk;
console.log(walk());

let run = Person.run;
console.log(run());
```

- 1: undefined, undefined
- 2: Person, Person
- 3: SyntaxError
- 4: Window, Window

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

当调用一个没有 **this** 值的常规或原型方法时，如果该值不是undefined，则这些方法将返回一个初始 this 值。否则将返回全局window对象。在我们的例子中，初始的 `this` 值是未定义的，所以两个方法都返回window对象

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 51. What is the output of below code

```javascript
class Vehicle {
  constructor(name) {
    this.name = name;
  }

  start() {
    console.log(`${this.name} vehicle started`);
  }
}

class Car extends Vehicle {
  start() {
    console.log(`${this.name} car started`);
    super.start();
  }
}

const car = new Car("BMW");
console.log(car.start());
```

- 1: SyntaxError
- 2: BMW vehicle started, BMW car started
- 3: BMW car started, BMW vehicle started
- 4: BMW car started, BMW car started

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

super关键字用于调用父类的方法。不像其他语言super调用不需要时第一个语句。也就是说，语句会按代码相同顺序执行

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 52. What is the output of below code

```javascript
const USER = { age: 30 };
USER.age = 25;
console.log(USER.age);
```

- 1: 30
- 2: 25
- 3: Uncaught TypeError
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

即使我们使用了常量，内容是对象，对象的内容（即属性）也可以被修改。因此，这个用例中修改也是合法的

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 53. What is the output of below code

```javascript
console.log("🙂" === "🙂");
```

- 1: false
- 2: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

Emoji是unicode，且微小符号的unicode是 "U+1F642"。相同emoji的unicode比较和字符串比较一样。因此，输出总是true

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 54. What is the output of below code?

```javascript
console.log(typeof typeof typeof true);
```

- 1: string
- 2: boolean
- 3: NaN
- 4: number

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

任何原始值的typeof操作符都会返回字符串值。所以即使你对返回值应用typeof操作符链，也总是返回字符串

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 55. What is the output of below code?

```javascript
let zero = new Number(0);

if (zero) {
  console.log("If");
} else {
  console.log("Else");
}
```

- 1: If
- 2: Else
- 3: NaN
- 4: SyntaxError

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

1. new Number操作返回的类型总是对象。即new Number(0) --> object
2. if块中的对象总是真值

因此上边的代码块总是会进入if部分

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 55. What is the output of below code in non strict mode?

```javascript
let msg = "Good morning!!";

msg.name = "John";

console.log(msg.name);
```

- 1: ""
- 2: Error
- 3: John
- 4: Undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

非严格模式下返回undefined，严格模式下返回错误。在非严格模式下，将创建包装器对象并获取提到的属性。但是在访问下一行的属性后对象会消失

</p>

</details>

---

**[⬆ Back to Top](#table-of-contents)**

#### 56. What is the output of below code?

```javascript
let count = 10;

(function innerFunc() {
  if (count === 10) {
    let count = 11;
    console.log(count);
  }
  console.log(count);
})();
```

- 1: 11, 10
- 2: 11, 11
- 3: 10, 11
- 4: 10, 10

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 1

11 和 10 被打印到控制台.

innerFunc 是一个闭包，它从外部作用域捕获count变量。即 10。但是条件有另一个局部变量 `count`，它覆盖了我们的 `count` 变量。所以第一个 console.log 显示值 11
而第二个 console.log 通过从外部范围捕获计数变量来记录 10

</p>

</details>

**[⬆ Back to Top](#table-of-contents)**

#### 57. What is the output of below code ?

- 1: console.log(true && 'hi');
- 2: console.log(true && 'hi' && 1);
- 3: console.log(true && '' && 0);

<details><summary><b>Answer</b></summary>
  
 - 1: hi
 - 2: 1
 - 3: ''

 原因：运算符返回从左到右求值时遇到的第一个操作数为假的值，如果都为真则返回最后一个操作数的值

**注意:** 下边的值被当作假值

- 1: 0
- 2: ''
- 3: null
- 4: undefined
- 5: NaN

</p>
</details>

---

#### 58. What is the output of below code ?

```javascript
let arr = [1, 2, 3];
let str = "1,2,3";

console.log(arr == str);
```

- 1: false
- 2: Error
- 3: true

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

数组有自己的 `toString` 方法实现，返回逗号分隔的元素列表。所以上边的代码片段返回true。为了避免数组类型的转换，我们应该使用 === 来比较

</p>

</details>

---

#### 59. What is the output of below code?

```javascript
getMessage();

var getMessage = () => {
  console.log("Good morning");
};
```

- 1: Good morning
- 2: getMessage is not a function
- 3: getMessage is not defined
- 4: Undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 2

提升会将变量和函数移动到作用域的顶部。即使getMessage是一个箭头函数，由于变量声明或赋值上边的函数会被当做一个变量。所以变量在内存中会有undefined值并在代码执行阶段抛出一个错误'`getMessage` is not a function'

</p>

</details>

#### 60. What is the output of below code?

```javascript
let quickPromise = Promise.resolve();

quickPromise.then(() => console.log("promise finished"));

console.log("program finished"); 
```

- 1: program finished
- 2: Cannot predict the order
- 3: program finished, promise finished
- 4: promise finished, program finished

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 3

即使 promise 立即解析，它也不会立即执行，因为它的 **.then/catch/finally** 处理程序或回调（也叫任务）被推入队列。每当 JavaScript 引擎从当前程序中解放出来时，它就会从队列中拉出一个任务并执行它。这就是为什么在 Promise 处理器的输出之前首先打印最后一条语句的原因

**注意:** 我们称上边的队列为 "微任务队列"

</p>

</details>

#### 61. What is the output of below code?

```javascript
console.log('First line')
['a', 'b', 'c'].forEach((element) => console.log(element))
console.log('Third line')
```

- 1: `First line`, then print `a, b, c` in a new line, and finally print `Third line` as next line
- 2: `First line`, then print `a, b, c` in a first line, and  print `Third line` as next line
- 3:  Missing semi-colon error
- 4:  Cannot read properties of undefined

<details><summary><b>Answer</b></summary>
<p>

##### Answer: 4

当 JavaScript 遇到没有分号的换行符时，JavaScript 解析器会根据一组称为“自动分号插入”的规则自动添加分号，该规则决定是否将换行符作为语句的结尾插入分号。但它不假定方括号 [...] 前有分号。所以前两行被认为是一个单一的语句，如下所示

```javascript
console.log('First line')['a', 'b', 'c'].forEach((element) => console.log(element))
```

因此，在 log 函数上应用数组方括号时会出现 **cannot read properties of undefined** 错误

</p>

</details>
---

## Disclaimer

The questions provided in this repository are the summary of frequently asked questions across numerous companies. We cannot guarantee that these questions will actually be asked during your interview process, nor should you focus on memorizing all of them. The primary purpose is for you to get a sense of what some companies might ask — do not get discouraged if you don't know the answer to all of them ⁠— that is ok!
此仓库中提供的问题是众多公司常见问题的摘要。我们不能保证这些问题会在你的面试过程中被问到，你也不应该专注于记住所有这些问题。主要目的是让您了解一些公司可能会问什么——如果你不知道所有问题的答案，不要气馁 ⁠- 没关系！

祝你面试好运 😊

---
