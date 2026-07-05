# 🔧 TestForge 測試報告

![Tests](https://img.shields.io/badge/Tests-160_Passed,_145_Failed-red)
![Coverage](https://img.shields.io/badge/Coverage-0%25-red)
![Threshold](https://img.shields.io/badge/Threshold-80%25-red)

> 📅 報告產生時間：2026/7/5 下午11:30:17
> 🔧 由 [TestForge](https://github.com/JeffLin0225/testforge) 自動產生

---

## 📋 測試總覽

| 指標 | 數值 |
| --- | --- |
| 測試檔案數 | 32 |
| 總測試數 | 305 |
| ✅ 通過 | 160 |
| ❌ 失敗 | 145 |
| 通過率 | 52.5% |

## 📄 測試檔案結果

| 檔案名稱 | 狀態 | 通過 | 失敗 | 總數 |
| --- | --- | --- | --- | --- |
| `App.vue.test.ts` | ❌ | 0 | 3 | 3 |
| `ActivityCard.vue.test.ts` | ❌ | 0 | 9 | 9 |
| `ActivityInsert.vue.test.ts` | ❌ | 0 | 18 | 18 |
| `ActivityRows.vue.test.ts` | ✅ | 5 | 0 | 5 |
| `AdminCard.vue.test.ts` | ❌ | 0 | 5 | 5 |
| `AdminRows.vue.test.ts` | ✅ | 5 | 0 | 5 |
| `CouponCard.vue.test.ts` | ❌ | 0 | 9 | 9 |
| `CouponInfo.vue.test.ts` | ✅ | 9 | 0 | 9 |
| `CouponInsert.vue.test.ts` | ❌ | 0 | 19 | 19 |
| `CouponRows.vue.test.ts` | ✅ | 5 | 0 | 5 |
| `OrdersCard.vue.test.ts` | ❌ | 0 | 4 | 4 |
| `OrdersCardDone.vue.test.ts` | ❌ | 0 | 3 | 3 |
| `OrdersRows.vue.test.ts` | ✅ | 5 | 0 | 5 |
| `ProductCard.vue.test.ts` | ❌ | 0 | 6 | 6 |
| `ProductModal.vue.test.ts` | ❌ | 0 | 13 | 13 |
| `ProductRows.vue.test.ts` | ✅ | 6 | 0 | 6 |
| `ProductSelect.vue.test.ts` | ❌ | 6 | 26 | 32 |
| `Home.vue.test.ts` | ✅ | 3 | 0 | 3 |
| `MyNavbar.vue.test.ts` | ❌ | 0 | 0 | 0 |
| `Navigation.vue.test.ts` | ❌ | 0 | 0 | 0 |
| `NotFound.vue.test.ts` | ✅ | 3 | 0 | 3 |
| `Activity.vue.test.ts` | ✅ | 7 | 0 | 7 |
| `Admin.vue.test.ts` | ✅ | 5 | 0 | 5 |
| `Comment.vue.test.ts` | ❌ | 27 | 3 | 30 |
| `Coupon.vue.test.ts` | ✅ | 9 | 0 | 9 |
| `Customerservice.vue.test.ts` | ❌ | 10 | 1 | 11 |
| `Orders.vue.test.ts` | ✅ | 9 | 0 | 9 |
| `USER.vue.test.ts` | ❌ | 8 | 1 | 9 |
| `AdminInfor.vue.test.ts` | ❌ | 4 | 20 | 24 |
| `Product.vue.test.ts` | ✅ | 8 | 0 | 8 |
| `ProductUpload.vue.test.ts` | ❌ | 16 | 5 | 21 |
| `Login.vue.test.ts` | ✅ | 10 | 0 | 10 |

## ❌ 失敗的測試

### `App.vue.test.ts`

- **App.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'resolve')
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/vue-router/dist/vue-router.mjs:2249:23
      at ReactiveEffect.fn (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:994:13)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
      at ComputedRefImpl.get value [as value] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:1006:109)
  ```
- **App.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/App.vue.test.ts:28:40
  ```
- **App.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'resolve')
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/vue-router/dist/vue-router.mjs:2249:23
      at ReactiveEffect.fn (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:994:13)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
      at ComputedRefImpl.get value [as value] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:1006:109)
  ```

### `ActivityCard.vue.test.ts`

- **ActivityCard.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ActivityCard.vue.test.ts:28:40
  ```
- **ActivityCard.vue 元件應該定義 customOpen 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 元件應該定義 customDelete 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 條件渲染 (activity.discount_percent == null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 條件渲染 (activity.start_at != activity.end_at) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 條件渲染 (activity.created_by!=null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 條件渲染 (activity.updated_by!=null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityCard.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityCard.vue:7:109)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `ActivityInsert.vue.test.ts`

- **ActivityInsert.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ActivityInsert.vue.test.ts:28:40
  ```
- **ActivityInsert.vue 按鈕「按鈕1」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 按鈕「Close」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 按鈕「新增」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 點擊「新增」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 按鈕「修改」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 點擊「修改」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 元件應該定義 customInsert 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 元件應該定義 customUpdate 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 元件應該定義 update:modelValue 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 條件渲染 (isShowInsertButton) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 條件渲染 (!isShowInsertButton) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ActivityInsert.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ActivityInsert.vue:14:73)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `AdminCard.vue.test.ts`

- **AdminCard.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/AdminCard.vue:5:44)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **AdminCard.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/AdminCard.vue.test.ts:28:40
  ```
- **AdminCard.vue 元件應該定義 customOpen 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/AdminCard.vue:5:44)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **AdminCard.vue 元件應該定義 customDelete 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/AdminCard.vue:5:44)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **AdminCard.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/AdminCard.vue:5:44)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `CouponCard.vue.test.ts`

- **CouponCard.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/CouponCard.vue.test.ts:28:40
  ```
- **CouponCard.vue 元件應該定義 customOpen 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 元件應該定義 customDelete 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 條件渲染 (coupon.discount == null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 條件渲染 (coupon.start_at != coupon.end_at) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 條件渲染 (coupon.created_by != null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 條件渲染 (coupon.updated_by != null) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponCard.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponCard.vue:8:55)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `CouponInsert.vue.test.ts`

- **CouponInsert.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/CouponInsert.vue.test.ts:28:40
  ```
- **CouponInsert.vue 按鈕「按鈕1」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 按鈕「Close」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 按鈕「新增」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 點擊「新增」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 按鈕「修改」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 點擊「修改」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 元件應該定義 customInsert 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 元件應該定義 customUpdate 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 元件應該定義 update:modelValue 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 條件渲染 (isShowInsertButton) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 條件渲染 (!isShowInsertButton) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **CouponInsert.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'name')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/CouponInsert.vue:13:71)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `OrdersCard.vue.test.ts`

- **OrdersCard.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'orderid')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/OrdersCard.vue:7:40)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **OrdersCard.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/OrdersCard.vue.test.ts:28:40
  ```
- **OrdersCard.vue 元件應該定義 customOpen 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'orderid')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/OrdersCard.vue:7:40)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **OrdersCard.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'orderid')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/OrdersCard.vue:7:40)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `OrdersCardDone.vue.test.ts`

- **OrdersCardDone.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'orderid')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/OrdersCardDone.vue:7:40)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **OrdersCardDone.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/OrdersCardDone.vue.test.ts:28:40
  ```
- **OrdersCardDone.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'orderid')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/OrdersCardDone.vue:7:40)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `ProductCard.vue.test.ts`

- **ProductCard.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductCard.vue:8:43)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductCard.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductCard.vue.test.ts:28:40
  ```
- **ProductCard.vue 元件應該定義 customOpen 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductCard.vue:8:43)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductCard.vue 元件應該定義 customDelete 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductCard.vue:8:43)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductCard.vue 條件渲染 (product.price!=product.discount_price) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductCard.vue:8:43)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductCard.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductCard.vue:8:43)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `ProductModal.vue.test.ts`

- **ProductModal.vue 應該能正常掛載**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue 掛載後不應有 console 錯誤**
  ```
  AssertionError: expected [Function] to not throw an error but 'TypeError: Cannot read properties of …' was thrown
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1552:16)
      at Proxy.<anonymous> (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/expect/dist/index.js:1156:15)
      at Proxy.methodWrapper (file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/chai/index.js:1700:25)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductModal.vue.test.ts:28:40
  ```
- **ProductModal.vue 按鈕「按鈕1」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue input 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue select 元素應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue 元件應該定義 customUpdate 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue 元件應該定義 update:modelValue 事件**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue 條件渲染 (activity.discount_percent == null || activity.discount_percent ==100) 不同值不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```
- **ProductModal.vue 渲染結果應與快照一致**
  ```
  TypeError: Cannot read properties of undefined (reading 'id')
      at Proxy._sfc_render (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/src/components/ProductModal.vue:12:81)
      at renderComponentRoot (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:886:16)
      at ReactiveEffect.componentUpdateFn [as fn] (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/runtime-core/dist/runtime-core.cjs.js:5080:46)
      at ReactiveEffect.run (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/reactivity/dist/reactivity.cjs.js:181:19)
  ```

### `ProductSelect.vue.test.ts`

- **ProductSelect.vue 按鈕「×」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'exists')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:41:19
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue 點擊「×」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'trigger')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:47:18
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue 按鈕「清除」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'exists')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:54:19
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue 點擊「清除」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'trigger')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:60:18
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:67:50
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedGender）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:73:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:79:52
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedGender）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:85:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:91:49
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedGender）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:97:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:103:45
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedType）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:109:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:115:45
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedType）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:121:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:127:45
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedType）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:133:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:139:45
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedType）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:145:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:151:45
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedType）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:157:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:163:46
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedStyle）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:169:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:175:46
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedStyle）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:181:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **ProductSelect.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:187:46
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **ProductSelect.vue input 應支援輸入（v-model: selectedStyle）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/components/ProductSelect.vue.test.ts:193:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```

### `Comment.vue.test.ts`

- **Comment.vue 按鈕「確定刪除」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'exists')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/activityPage/Comment.vue.test.ts:103:19
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **Comment.vue 點擊「確定刪除」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'trigger')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/activityPage/Comment.vue.test.ts:109:18
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **Comment.vue input 應支援輸入（v-model: selectedDate）**
  ```
  AssertionError: expected '' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/activityPage/Comment.vue.test.ts:123:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```

### `Customerservice.vue.test.ts`

- **Customerservice.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/activityPage/Customerservice.vue.test.ts:46:59
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```

### `USER.vue.test.ts`

- **USER.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/activityPage/USER.vue.test.ts:34:59
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```

### `AdminInfor.vue.test.ts`

- **AdminInfor.vue 按鈕「更新資料」應該存在**
  ```
  TypeError: Cannot read properties of undefined (reading 'exists')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:35:19
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue 點擊「更新資料」不應崩潰**
  ```
  TypeError: Cannot read properties of undefined (reading 'trigger')
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:41:18
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:48:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.id）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:54:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:60:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.name）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:66:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:72:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.authority）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:78:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:84:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.gender）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:90:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:96:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.birth）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:102:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:108:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.phone）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:114:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:120:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.email）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:126:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:132:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.address）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:138:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```
- **AdminInfor.vue input 元素應該存在**
  ```
  AssertionError: expected false to be true // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:144:44
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:2326:20
  ```
- **AdminInfor.vue input 應支援輸入（v-model: admin.created_at）**
  ```
  Error: Cannot call setValue on an empty DOMWrapper.
      at Object.get (/home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vue/test-utils/dist/vue-test-utils.cjs.js:1482:27)
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/AdminInfor.vue.test.ts:150:14
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:302:11
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:26
  ```

### `ProductUpload.vue.test.ts`

- **ProductUpload.vue input 應支援輸入（v-model: quantity）**
  ```
  AssertionError: expected '' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/ProductUpload.vue.test.ts:72:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```
- **ProductUpload.vue input 應支援輸入（v-model: selectedSize）**
  ```
  AssertionError: expected 'S' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/ProductUpload.vue.test.ts:84:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```
- **ProductUpload.vue input 應支援輸入（v-model: selectedSize）**
  ```
  AssertionError: expected 'M' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/ProductUpload.vue.test.ts:96:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```
- **ProductUpload.vue input 應支援輸入（v-model: selectedSize）**
  ```
  AssertionError: expected 'L' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/ProductUpload.vue.test.ts:108:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```
- **ProductUpload.vue input 應支援輸入（v-model: price）**
  ```
  AssertionError: expected '' to be 'test input value' // Object.is equality
      at /home/runner/work/CLOTH_Front_End/CLOTH_Front_End/__generated_tests__/views/pages/ProductUpload.vue.test.ts:120:52
      at processTicksAndRejections (node:internal/process/task_queues:95:5)
      at file:///home/runner/work/CLOTH_Front_End/CLOTH_Front_End/node_modules/@vitest/runner/dist/chunk-artifact.js:1903:20
  ```

---

> 💡 如果想看詳細的互動式覆蓋率報告，請查看 `coverage/index.html`。
>
> 🔧 此報告由 [TestForge](https://github.com/JeffLin0225/testforge) 自動產生。
