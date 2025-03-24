# [2.0.0-beta.8](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.7...v2.0.0-beta.8) (2023-02-06)


## v2.0.0


### 🚀 Enhancements

- Items limit ([b00a84a](https://github.com/nfpocket/vue-virtual-scroller/commit/b00a84a))
- Add before-container slot to RecycleList ([f875df0](https://github.com/nfpocket/vue-virtual-scroller/commit/f875df0))
- **RecycleList:** Hidden event ([960ff1c](https://github.com/nfpocket/vue-virtual-scroller/commit/960ff1c))
- Hover class for item views ([#90](https://github.com/nfpocket/vue-virtual-scroller/pull/90))
- ScrollToBottom ([8506be9](https://github.com/nfpocket/vue-virtual-scroller/commit/8506be9))
- **demo:** Test chat ([8b665c4](https://github.com/nfpocket/vue-virtual-scroller/commit/8b665c4))
- **DynamicScroller:** Support simple arrays, closes #108 ([#108](https://github.com/nfpocket/vue-virtual-scroller/issues/108))
- Throw error if key is null or undefined ([7223dbb](https://github.com/nfpocket/vue-virtual-scroller/commit/7223dbb))
- Resize observer + undefinedSizes cleaner code ([11546d8](https://github.com/nfpocket/vue-virtual-scroller/commit/11546d8))
- Add skipHover prop to deactive the hover detection ([#752](https://github.com/nfpocket/vue-virtual-scroller/pull/752))
- Update event provide range of the visible items ([#115](https://github.com/nfpocket/vue-virtual-scroller/pull/115))
- Adds configurable list/item tags for semantic html ([#203](https://github.com/nfpocket/vue-virtual-scroller/pull/203))
- Throw error when key field does not exist in item ([#265](https://github.com/nfpocket/vue-virtual-scroller/pull/265))
- Custom classes for list wrapper and list items. ([#397](https://github.com/nfpocket/vue-virtual-scroller/pull/397))
- Add an empty slot ([#398](https://github.com/nfpocket/vue-virtual-scroller/pull/398))
- Emit events for scroll to begin and end of list ([#364](https://github.com/nfpocket/vue-virtual-scroller/pull/364))
- GridItems prop ([#27](https://github.com/nfpocket/vue-virtual-scroller/pull/27))
- ItemSecondarySize ([43d311c](https://github.com/nfpocket/vue-virtual-scroller/commit/43d311c))
- Allow throttling update calls ([#764](https://github.com/nfpocket/vue-virtual-scroller/pull/764))
- Items ref ([#789](https://github.com/nfpocket/vue-virtual-scroller/pull/789))
- New `disableTransform` prop to use top/left instead of translate ([#138](https://github.com/nfpocket/vue-virtual-scroller/pull/138))

### 🔥 Performance

- SkipHover: don't add event listeners ([6b623b5](https://github.com/nfpocket/vue-virtual-scroller/commit/6b623b5))
- Small code changes to maximize performance ([3b4dbf3](https://github.com/nfpocket/vue-virtual-scroller/commit/3b4dbf3))
- Unnecessary loop ([86d0d07](https://github.com/nfpocket/vue-virtual-scroller/commit/86d0d07))

### 🩹 Fixes

- Eslint errors ([aab588f](https://github.com/nfpocket/vue-virtual-scroller/commit/aab588f))
- Eslint errors ([39607a9](https://github.com/nfpocket/vue-virtual-scroller/commit/39607a9))
- Simplify argument ([d7bb1cb](https://github.com/nfpocket/vue-virtual-scroller/commit/d7bb1cb))
- GetScroll polish ([0efa4bd](https://github.com/nfpocket/vue-virtual-scroller/commit/0efa4bd))
- Eslint errors ([7ca02d6](https://github.com/nfpocket/vue-virtual-scroller/commit/7ca02d6))
- Eslint config ([bdab77f](https://github.com/nfpocket/vue-virtual-scroller/commit/bdab77f))
- Eslint errors ([8ff596a](https://github.com/nfpocket/vue-virtual-scroller/commit/8ff596a))
- Browser build ([d217bf8](https://github.com/nfpocket/vue-virtual-scroller/commit/d217bf8))
- Lint before publish ([48460e3](https://github.com/nfpocket/vue-virtual-scroller/commit/48460e3))
- The default target for IOS should be body, closes #73 ([#85](https://github.com/nfpocket/vue-virtual-scroller/pull/85), [#73](https://github.com/nfpocket/vue-virtual-scroller/issues/73))
- Demo double scrollbar on Firefox ([faf8cf3](https://github.com/nfpocket/vue-virtual-scroller/commit/faf8cf3))
- Data not updating, closes #94 ([#114](https://github.com/nfpocket/vue-virtual-scroller/pull/114), [#94](https://github.com/nfpocket/vue-virtual-scroller/issues/94))
- Eslint error ([6ebf8b8](https://github.com/nfpocket/vue-virtual-scroller/commit/6ebf8b8))
- Eslint error ([ae8f507](https://github.com/nfpocket/vue-virtual-scroller/commit/ae8f507))
- Css not being generated ([d7c88c3](https://github.com/nfpocket/vue-virtual-scroller/commit/d7c88c3))
- Better peformance and scroll stability ([c642fa2](https://github.com/nfpocket/vue-virtual-scroller/commit/c642fa2))
- **demo:** Webpack HMR ([c5fa266](https://github.com/nfpocket/vue-virtual-scroller/commit/c5fa266))
- **dynamic scroller:** Update state now depends on id ([947f6db](https://github.com/nfpocket/vue-virtual-scroller/commit/947f6db))
- **DynamicScroller:** Round height, closes #118 ([#118](https://github.com/nfpocket/vue-virtual-scroller/issues/118))
- Use minHeight instead of height on wrapper, closes #92 ([#92](https://github.com/nfpocket/vue-virtual-scroller/issues/92))
- **ssr:** Document could not be defined, closes #112 ([#112](https://github.com/nfpocket/vue-virtual-scroller/issues/112))
- **dynamic scroller:** Invalidate heights instead of clear, closes #130 ([#130](https://github.com/nfpocket/vue-virtual-scroller/issues/130))
- Do not forward keyField prop from DynamicScroller - closes #132 ([#133](https://github.com/nfpocket/vue-virtual-scroller/pull/133), [#132](https://github.com/nfpocket/vue-virtual-scroller/issues/132))
- **DynamicScroller:** Implicit key field ([f70587a](https://github.com/nfpocket/vue-virtual-scroller/commit/f70587a))
- Issue with Vue 2.6 compiler, revert back to 2.5, closes #136 ([#136](https://github.com/nfpocket/vue-virtual-scroller/issues/136))
- Remove getBounds() ([95ce62e](https://github.com/nfpocket/vue-virtual-scroller/commit/95ce62e))
- Missing size ([5fb219e](https://github.com/nfpocket/vue-virtual-scroller/commit/5fb219e))
- Esm bundle fix for Vue external ([#207](https://github.com/nfpocket/vue-virtual-scroller/pull/207))
- ScrollToBottom on Firefox ([8401475](https://github.com/nfpocket/vue-virtual-scroller/commit/8401475))
- Null error when resize observer isn't available ([d72a847](https://github.com/nfpocket/vue-virtual-scroller/commit/d72a847))
- **ie:** Use scrollHeight ([7ffd776](https://github.com/nfpocket/vue-virtual-scroller/commit/7ffd776))
- ScrollToBottom ([dad6b32](https://github.com/nfpocket/vue-virtual-scroller/commit/dad6b32))
- **build:** Rollup deprecated plugins and options ([db85e92](https://github.com/nfpocket/vue-virtual-scroller/commit/db85e92))
- **eslint:** Don't lint css + fix warning ([48fb931](https://github.com/nfpocket/vue-virtual-scroller/commit/48fb931))
- Missing resize-observer css ([3b198c6](https://github.com/nfpocket/vue-virtual-scroller/commit/3b198c6))
- Active value not taking into account scroller active state ([470e480](https://github.com/nfpocket/vue-virtual-scroller/commit/470e480))
- Sort views after scrolling so text selection is correct, closes #359 ([#359](https://github.com/nfpocket/vue-virtual-scroller/issues/359))
- **ssr:** Template mismatch, closes #343 ([#343](https://github.com/nfpocket/vue-virtual-scroller/issues/343))
- **perf:** Skip update if the user hasn't scrolled more than min item height ([cf35b35](https://github.com/nfpocket/vue-virtual-scroller/commit/cf35b35))
- Missing last update scroll position ([f15b1fd](https://github.com/nfpocket/vue-virtual-scroller/commit/f15b1fd))
- Remove text unselect, closes #389 ([#389](https://github.com/nfpocket/vue-virtual-scroller/issues/389))
- Avoid updatingVisibleItems loop ([#392](https://github.com/nfpocket/vue-virtual-scroller/pull/392))
- New views not used immediately ([#391](https://github.com/nfpocket/vue-virtual-scroller/pull/391))
- Unused pool has to be refetched after new view is added ([#393](https://github.com/nfpocket/vue-virtual-scroller/pull/393))
- V is undefined ([cf6315b](https://github.com/nfpocket/vue-virtual-scroller/commit/cf6315b))
- Account for the height of the leading and trailing slots when calculating visible items, fix #685 ([#754](https://github.com/nfpocket/vue-virtual-scroller/pull/754), [#685](https://github.com/nfpocket/vue-virtual-scroller/issues/685))
- **DynamicScrollerItem:** Watch item prop ([#700](https://github.com/nfpocket/vue-virtual-scroller/pull/700))
- Account for the height of the leading and trailing slots when calculating visible items, fix #685 ([#685](https://github.com/nfpocket/vue-virtual-scroller/issues/685))
- Restore scroll in keep-alive ([#724](https://github.com/nfpocket/vue-virtual-scroller/pull/724))
- DynamicScroller should pass its own keyField prop to child RecycleScroller ([#732](https://github.com/nfpocket/vue-virtual-scroller/pull/732))
- Issue with beforeDestroy hook ([#748](https://github.com/nfpocket/vue-virtual-scroller/pull/748))
- Avoid jumping scroll position when upper item size is calculated ([#374](https://github.com/nfpocket/vue-virtual-scroller/pull/374))
- ScrollToItem works with pageMode ([#396](https://github.com/nfpocket/vue-virtual-scroller/pull/396))
- Clamp endIndex if less items than prerender ([#473](https://github.com/nfpocket/vue-virtual-scroller/pull/473))
- Wrap the callback in requestAnimationFrame, fix #516 ([#517](https://github.com/nfpocket/vue-virtual-scroller/pull/517), [#516](https://github.com/nfpocket/vue-virtual-scroller/issues/516))
- Merge ([c8363b1](https://github.com/nfpocket/vue-virtual-scroller/commit/c8363b1))
- Height NaN, fix #757 ([#757](https://github.com/nfpocket/vue-virtual-scroller/issues/757))
- Views incorrectly unused (proxy identity comparison) ([395bbfb](https://github.com/nfpocket/vue-virtual-scroller/commit/395bbfb))
- Improved dynamic scroller resize observer logic ([40f58b3](https://github.com/nfpocket/vue-virtual-scroller/commit/40f58b3))
- Unusing views after non-continuous scroll ([11488b7](https://github.com/nfpocket/vue-virtual-scroller/commit/11488b7))
- Item sizes getting 'disabled' resulting in gaps ([55b4ab1](https://github.com/nfpocket/vue-virtual-scroller/commit/55b4ab1))
- Inconsistent state on reused view ([a14747d](https://github.com/nfpocket/vue-virtual-scroller/commit/a14747d))
- Views map corruption + view not removed from unusedPool ([cef8860](https://github.com/nfpocket/vue-virtual-scroller/commit/cef8860))
- **DynamicScroller:** Gaps caused by DOM reusing not triggering ResizeObserver ([a21e191](https://github.com/nfpocket/vue-virtual-scroller/commit/a21e191))
- Duplicate active views ([1ef796b](https://github.com/nfpocket/vue-virtual-scroller/commit/1ef796b))
- Views not reused correctly ([d5a8d75](https://github.com/nfpocket/vue-virtual-scroller/commit/d5a8d75))
- Sorting views not working, #772 ([#772](https://github.com/nfpocket/vue-virtual-scroller/issues/772))
- View not unused if item no longer present, fix #774 ([#774](https://github.com/nfpocket/vue-virtual-scroller/issues/774))
- **RecycleScroller:** GridItems is undefined when scrollToItem, fix #773 ([#761](https://github.com/nfpocket/vue-virtual-scroller/pull/761), [#773](https://github.com/nfpocket/vue-virtual-scroller/issues/773))
- KeyField issue for class instances, fix #770 ([#771](https://github.com/nfpocket/vue-virtual-scroller/pull/771), [#770](https://github.com/nfpocket/vue-virtual-scroller/issues/770))
- Items not updating if new object reference, fix #690 ([#690](https://github.com/nfpocket/vue-virtual-scroller/issues/690))
- BorderBoxSize not available in older browsers ([8f90971](https://github.com/nfpocket/vue-virtual-scroller/commit/8f90971))
- Index lost, fix #783 ([#784](https://github.com/nfpocket/vue-virtual-scroller/pull/784), [#783](https://github.com/nfpocket/vue-virtual-scroller/issues/783))
- Avoid rendering when slot is unused ([#787](https://github.com/nfpocket/vue-virtual-scroller/pull/787))
- Rewrite view (re-)assignment logic ([#743](https://github.com/nfpocket/vue-virtual-scroller/pull/743))
- **RecycleScroller:** Introduce an item wrapper to reduce re-render ([#742](https://github.com/nfpocket/vue-virtual-scroller/pull/742))
- Flicker issue in ios when scrolling up ([#864](https://github.com/nfpocket/vue-virtual-scroller/pull/864))
- Hide view to avoid overlap when position is set to -9999px; ([#837](https://github.com/nfpocket/vue-virtual-scroller/pull/837))
- Prevent empty gaps on fast scrolling, fix (#863, #882) ([#890](https://github.com/nfpocket/vue-virtual-scroller/pull/890), [#863](https://github.com/nfpocket/vue-virtual-scroller/issues/863), [#882](https://github.com/nfpocket/vue-virtual-scroller/issues/882))

### 💅 Refactors

- Remove Scroller mixin ([dc21471](https://github.com/nfpocket/vue-virtual-scroller/commit/dc21471))
- Direction support ([4327b38](https://github.com/nfpocket/vue-virtual-scroller/commit/4327b38))
- Basic Vue 3 migration ([b8029e5](https://github.com/nfpocket/vue-virtual-scroller/commit/b8029e5))
- Mono-repo scruture ([81032aa](https://github.com/nfpocket/vue-virtual-scroller/commit/81032aa))
- Method renaming ([cf7e24e](https://github.com/nfpocket/vue-virtual-scroller/commit/cf7e24e))

### 📖 Documentation

- Add Patreon link ([8205f15](https://github.com/nfpocket/vue-virtual-scroller/commit/8205f15))
- Spacing ([0818a57](https://github.com/nfpocket/vue-virtual-scroller/commit/0818a57))
- Spacing ([6cf478a](https://github.com/nfpocket/vue-virtual-scroller/commit/6cf478a))
- Improve polyfill warning ([2c93e7e](https://github.com/nfpocket/vue-virtual-scroller/commit/2c93e7e))
- Typos ([bdad833](https://github.com/nfpocket/vue-virtual-scroller/commit/bdad833))
- Update toc and components presentation ([6790ffb](https://github.com/nfpocket/vue-virtual-scroller/commit/6790ffb))
- Video demo link ([ee0daf4](https://github.com/nfpocket/vue-virtual-scroller/commit/ee0daf4))
- Reworked demo links ([9ae0210](https://github.com/nfpocket/vue-virtual-scroller/commit/9ae0210))
- Updated sponsors ([eadd7f7](https://github.com/nfpocket/vue-virtual-scroller/commit/eadd7f7))
- Fix example ([7fcd543](https://github.com/nfpocket/vue-virtual-scroller/commit/7fcd543))
- Add styles for kinetic scrolling on touch device in docs demo ([#100](https://github.com/nfpocket/vue-virtual-scroller/pull/100))
- Updated demo ([2d10f51](https://github.com/nfpocket/vue-virtual-scroller/commit/2d10f51))
- Update sponsors ([1d2b6ff](https://github.com/nfpocket/vue-virtual-scroller/commit/1d2b6ff))
- **demo:** Build ([ce97b64](https://github.com/nfpocket/vue-virtual-scroller/commit/ce97b64))
- Fix DynamicScroller anchor ([#126](https://github.com/nfpocket/vue-virtual-scroller/pull/126))
- **demo:** Dynamic scroller filter example ([3a4fb02](https://github.com/nfpocket/vue-virtual-scroller/commit/3a4fb02))
- **demo:** Simple list ([5ba314a](https://github.com/nfpocket/vue-virtual-scroller/commit/5ba314a))
- KeyField in important notes ([cbb89a4](https://github.com/nfpocket/vue-virtual-scroller/commit/cbb89a4))
- **demo:** Build ([b5e7845](https://github.com/nfpocket/vue-virtual-scroller/commit/b5e7845))
- Clarification and spelling updates ([#202](https://github.com/nfpocket/vue-virtual-scroller/pull/202))
- Fix v-slot usage ([ec24d6d](https://github.com/nfpocket/vue-virtual-scroller/commit/ec24d6d))
- Fix misleading CSS file import instruction ([#260](https://github.com/nfpocket/vue-virtual-scroller/pull/260))
- Chat demo ([b0472bb](https://github.com/nfpocket/vue-virtual-scroller/commit/b0472bb))
- Send multiple messages per frame ([e175f4d](https://github.com/nfpocket/vue-virtual-scroller/commit/e175f4d))
- Build ([60f124d](https://github.com/nfpocket/vue-virtual-scroller/commit/60f124d))
- Build ([5e39654](https://github.com/nfpocket/vue-virtual-scroller/commit/5e39654))
- Update readme ([0ecb2c9](https://github.com/nfpocket/vue-virtual-scroller/commit/0ecb2c9))
- **readme:** Temporary link for Vue 3 version ([1f721da](https://github.com/nfpocket/vue-virtual-scroller/commit/1f721da))
- **readme:** Change sponsor link ([6099542](https://github.com/nfpocket/vue-virtual-scroller/commit/6099542))
- Update sponsors ([fc10557](https://github.com/nfpocket/vue-virtual-scroller/commit/fc10557))
- Update sponsors ([a6e07da](https://github.com/nfpocket/vue-virtual-scroller/commit/a6e07da))
- Update ([332d045](https://github.com/nfpocket/vue-virtual-scroller/commit/332d045))
- Main README ([187a642](https://github.com/nfpocket/vue-virtual-scroller/commit/187a642))
- Update demo URL ([3792abf](https://github.com/nfpocket/vue-virtual-scroller/commit/3792abf))

### 🏡 Chore

- V0.11.8 ([618098a](https://github.com/nfpocket/vue-virtual-scroller/commit/618098a))
- Upgrade deps ([8cbb12c](https://github.com/nfpocket/vue-virtual-scroller/commit/8cbb12c))
- Browserslist ([96bc676](https://github.com/nfpocket/vue-virtual-scroller/commit/96bc676))
- Update demo ([53f7761](https://github.com/nfpocket/vue-virtual-scroller/commit/53f7761))
- V0.12.0 ([99030a2](https://github.com/nfpocket/vue-virtual-scroller/commit/99030a2))
- Comment about global scroll target ([4412b36](https://github.com/nfpocket/vue-virtual-scroller/commit/4412b36))
- Upgrade deps ([c15fd1e](https://github.com/nfpocket/vue-virtual-scroller/commit/c15fd1e))
- V0.12.1 ([0caf6c9](https://github.com/nfpocket/vue-virtual-scroller/commit/0caf6c9))
- Update visibility observer ([6f2980d](https://github.com/nfpocket/vue-virtual-scroller/commit/6f2980d))
- Update demo ([809882d](https://github.com/nfpocket/vue-virtual-scroller/commit/809882d))
- V0.12.2 ([3e5cf5e](https://github.com/nfpocket/vue-virtual-scroller/commit/3e5cf5e))
- V1.0.0-beta.1 ([edafae0](https://github.com/nfpocket/vue-virtual-scroller/commit/edafae0))
- V1.0.0-beta.2 ([8d78718](https://github.com/nfpocket/vue-virtual-scroller/commit/8d78718))
- Upgrade deps ([28c858b](https://github.com/nfpocket/vue-virtual-scroller/commit/28c858b))
- Upgrade deps ([6f70fe9](https://github.com/nfpocket/vue-virtual-scroller/commit/6f70fe9))
- Display url when dev demo ([d103610](https://github.com/nfpocket/vue-virtual-scroller/commit/d103610))
- V1.0.0-beta.3 ([c3b9fcb](https://github.com/nfpocket/vue-virtual-scroller/commit/c3b9fcb))
- Upgrade deps" ([5d8e927](https://github.com/nfpocket/vue-virtual-scroller/commit/5d8e927))
- V1.0.0-beta.4 ([f593b18](https://github.com/nfpocket/vue-virtual-scroller/commit/f593b18))
- Update sponsors ([b283f7d](https://github.com/nfpocket/vue-virtual-scroller/commit/b283f7d))
- **demo:** Deps ([dece681](https://github.com/nfpocket/vue-virtual-scroller/commit/dece681))
- V1.0.0-beta.5 ([b302981](https://github.com/nfpocket/vue-virtual-scroller/commit/b302981))
- **dep:** Update ([e5b5951](https://github.com/nfpocket/vue-virtual-scroller/commit/e5b5951))
- V1.0.0-beta.6 ([6e4d357](https://github.com/nfpocket/vue-virtual-scroller/commit/6e4d357))
- Style ([368f0fe](https://github.com/nfpocket/vue-virtual-scroller/commit/368f0fe))
- V1.0.0-beta.7 ([845a28d](https://github.com/nfpocket/vue-virtual-scroller/commit/845a28d))
- V1.0.0-rc.1 ([2403b3b](https://github.com/nfpocket/vue-virtual-scroller/commit/2403b3b))
- **demo:** Build ([112a66e](https://github.com/nfpocket/vue-virtual-scroller/commit/112a66e))
- V1.0.0-rc.2 ([2194271](https://github.com/nfpocket/vue-virtual-scroller/commit/2194271))
- Update sponsors ([eab88b6](https://github.com/nfpocket/vue-virtual-scroller/commit/eab88b6))
- Update sponsors ([d033c0a](https://github.com/nfpocket/vue-virtual-scroller/commit/d033c0a))
- Esm external deps ([b07377e](https://github.com/nfpocket/vue-virtual-scroller/commit/b07377e))
- Update deps ([c6ba015](https://github.com/nfpocket/vue-virtual-scroller/commit/c6ba015))
- Update deps ([d57af3f](https://github.com/nfpocket/vue-virtual-scroller/commit/d57af3f))
- V1.0.0 ([f91fe0b](https://github.com/nfpocket/vue-virtual-scroller/commit/f91fe0b))
- Exclude vue for es module bundle ([#257](https://github.com/nfpocket/vue-virtual-scroller/pull/257))
- V1.0.1 ([3af5bbd](https://github.com/nfpocket/vue-virtual-scroller/commit/3af5bbd))
- Build demo ([0c33171](https://github.com/nfpocket/vue-virtual-scroller/commit/0c33171))
- Browserlist ([45a7996](https://github.com/nfpocket/vue-virtual-scroller/commit/45a7996))
- V1.0.2 ([9f30d8d](https://github.com/nfpocket/vue-virtual-scroller/commit/9f30d8d))
- V1.0.3 ([68897e8](https://github.com/nfpocket/vue-virtual-scroller/commit/68897e8))
- Build demos ([ae5c2d4](https://github.com/nfpocket/vue-virtual-scroller/commit/ae5c2d4))
- V1.0.4 ([8ecf007](https://github.com/nfpocket/vue-virtual-scroller/commit/8ecf007))
- V1.0.6 ([a92c4b2](https://github.com/nfpocket/vue-virtual-scroller/commit/a92c4b2))
- V1.0.7 ([77a9f65](https://github.com/nfpocket/vue-virtual-scroller/commit/77a9f65))
- **lint:** Fix error ([647c3f6](https://github.com/nfpocket/vue-virtual-scroller/commit/647c3f6))
- V1.0.8 ([fa43694](https://github.com/nfpocket/vue-virtual-scroller/commit/fa43694))
- V1.0.9 ([711ec82](https://github.com/nfpocket/vue-virtual-scroller/commit/711ec82))
- V1.0.10 ([124d85c](https://github.com/nfpocket/vue-virtual-scroller/commit/124d85c))
- Update sponsors ([#424](https://github.com/nfpocket/vue-virtual-scroller/pull/424))
- Lint ([8622b67](https://github.com/nfpocket/vue-virtual-scroller/commit/8622b67))
- Fix build ([dd5038e](https://github.com/nfpocket/vue-virtual-scroller/commit/dd5038e))
- Regen lockfile ([61319d7](https://github.com/nfpocket/vue-virtual-scroller/commit/61319d7))
- Remove dist folder from git ([64dbe27](https://github.com/nfpocket/vue-virtual-scroller/commit/64dbe27))
- Create LICENSE file ([#448](https://github.com/nfpocket/vue-virtual-scroller/pull/448))
- Fix build if no dist folder ([64b920b](https://github.com/nfpocket/vue-virtual-scroller/commit/64b920b))
- **demo:** Update to @faker-js/faker ([71f72b7](https://github.com/nfpocket/vue-virtual-scroller/commit/71f72b7))
- **demo:** Preview port ([7e326c6](https://github.com/nfpocket/vue-virtual-scroller/commit/7e326c6))
- **demo:** Fix duplicate vue versions ([49981d8](https://github.com/nfpocket/vue-virtual-scroller/commit/49981d8))
- Move to pnpm ([1b4046f](https://github.com/nfpocket/vue-virtual-scroller/commit/1b4046f))
- **demo:** Fix >>> warn ([8eda3a4](https://github.com/nfpocket/vue-virtual-scroller/commit/8eda3a4))
- **demo:** Cleanup ([2efded0](https://github.com/nfpocket/vue-virtual-scroller/commit/2efded0))
- Fix scripts ([5df68b9](https://github.com/nfpocket/vue-virtual-scroller/commit/5df68b9))
- Install conventional-changelog-cli ([8cdf258](https://github.com/nfpocket/vue-virtual-scroller/commit/8cdf258))
- Issue templates ([2d3be3f](https://github.com/nfpocket/vue-virtual-scroller/commit/2d3be3f))
- Netlify config ([35cd6d6](https://github.com/nfpocket/vue-virtual-scroller/commit/35cd6d6))
- Fix tag flag ([61d1511](https://github.com/nfpocket/vue-virtual-scroller/commit/61d1511))
- Update sheep ([d7f702c](https://github.com/nfpocket/vue-virtual-scroller/commit/d7f702c))
- Fix changelog ([95b934a](https://github.com/nfpocket/vue-virtual-scroller/commit/95b934a))
- Fix build ([d6a5bf2](https://github.com/nfpocket/vue-virtual-scroller/commit/d6a5bf2))
- Fix cherrypick of rewrite ([c9ccc34](https://github.com/nfpocket/vue-virtual-scroller/commit/c9ccc34))
- Update lockfile ([0f2e362](https://github.com/nfpocket/vue-virtual-scroller/commit/0f2e362))
- Update pnpm + pin pnpm in package.json ([#885](https://github.com/nfpocket/vue-virtual-scroller/pull/885))
- Add pkg.pr.new ([#886](https://github.com/nfpocket/vue-virtual-scroller/pull/886))
- Add test workflow ([#887](https://github.com/nfpocket/vue-virtual-scroller/pull/887))
- Update pnpm and refresh lockfile ([47efc94](https://github.com/nfpocket/vue-virtual-scroller/commit/47efc94))
- Add .eslintcache to .gitignore ([2377699](https://github.com/nfpocket/vue-virtual-scroller/commit/2377699))
- Update lint command to use pnpm in vue-virtual-scroller package.json ([346379d](https://github.com/nfpocket/vue-virtual-scroller/commit/346379d))
- Update repository metadata to reflect new ownership ([ed3edce](https://github.com/nfpocket/vue-virtual-scroller/commit/ed3edce))
- Rename package to @nfpocket/vue-virtual-scroller ([dde6aed](https://github.com/nfpocket/vue-virtual-scroller/commit/dde6aed))

### ✅ Tests

- **lint:** Fix ([c85f07b](https://github.com/nfpocket/vue-virtual-scroller/commit/c85f07b))
- **lint:** Update eslint and use antfu config ([61b9919](https://github.com/nfpocket/vue-virtual-scroller/commit/61b9919))

### 🤖 CI

- Check pr title ([96b0520](https://github.com/nfpocket/vue-virtual-scroller/commit/96b0520))
- Auto release notes ([e0dc562](https://github.com/nfpocket/vue-virtual-scroller/commit/e0dc562))

### ❤️ Contributors

- Norman F <nf@pocket-rocket.io>
- Guillaume Chau ([@Akryum](http://github.com/Akryum))
- Ferflores507 ([@ferflores507](http://github.com/ferflores507))
- KaygNas <597857074@QQ.COM>
- Hobywhan ([@hobywhan](http://github.com/hobywhan))
- Wan Zulsarhan Wan Shaari <zulsarhan.shaari@gmail.com>
- Tatsuyuki Ishi ([@ishitatsuyuki](http://github.com/ishitatsuyuki))
- AousAnwar ([@AousAnwar](http://github.com/AousAnwar))
- Alex Liu ([@Mini-ghost](http://github.com/Mini-ghost))
- Reynaldiaznan123 <reynaldiaznan450@gmail.com>
- Vito ([@liu-lihao](http://github.com/liu-lihao))
- Varun Patil <radialapps@gmail.com>
- Shrey Mahendru ([@shreymahendru](http://github.com/shreymahendru))
- Crs <chris38c28@hotmail.com>
- Billy Rennekamp ([@okwme](http://github.com/okwme))
- David Arico <davidarico87@gmail.com>
- Okhvr <olg.katsalap@gmail.com>
- Michael Mitchell <iamovyerus@gmail.com>
- Vadim Caen <vadimcaen@gmail.com>
- Dominique CLAUSE <dom.clause@gmail.com>
- Damir Miladinov <damir89@gmail.com>
- Katashin <ktsn55@gmail.com>
- Nicolas Ngomai <nicolasn@theodo.fr>
- Alex Regan <alex.joseph.regan@gmail.com>
- CPlusSharp ([@cplussharp](http://github.com/cplussharp))
- Gans-groover ([@gans-groover](http://github.com/gans-groover))
- Varun Devulapalli ([@dsvs12](http://github.com/dsvs12))
- Nico Prat <nicooprat@gmail.com>
- Flyingbirdhub <1825547767@qq.com>
- Daniel Gidman <danatcofo@gmail.com>
- Tony Outis ([@tony-0tis](http://github.com/tony-0tis))
- Olaolu Olawuyi <mrolaolu@gmail.com>
- Tibi Neagu <tibi@f6s.com>
- Claas Augner <github@caugner.de>
- Igor Oleynik <igor.oleynikdp@gmail.com>
- Jürg Rast <juergr@gmail.com>
- Chris Fritz <chrisvfritz@gmail.com>
- Conjee Zou ([@shishiv30](http://github.com/shishiv30))

### Bug Fixes

* borderBoxSize not available in older browsers ([8f90971](https://github.com/Akryum/vue-virtual-scroller/commit/8f9097138d2f90ece8348141ac320c47ff7ab64a))



# [2.0.0-beta.7](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.6...v2.0.0-beta.7) (2022-12-14)


### Bug Fixes

* items not updating if new object reference, fix [#690](https://github.com/Akryum/vue-virtual-scroller/issues/690) ([5b5df8c](https://github.com/Akryum/vue-virtual-scroller/commit/5b5df8cdc231f989e7fc6d6677d02e9ef695d1b9))



# [2.0.0-beta.6](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.5...v2.0.0-beta.6) (2022-12-14)


### Bug Fixes

* keyField issue for class instances, fix [#770](https://github.com/Akryum/vue-virtual-scroller/issues/770) ([#771](https://github.com/Akryum/vue-virtual-scroller/issues/771)) ([1559ca8](https://github.com/Akryum/vue-virtual-scroller/commit/1559ca87e9195b6a1c5bada13de7f7b755a2fb6c))
* **RecycleScroller:** gridItems is undefined when scrollToItem, fix [#773](https://github.com/Akryum/vue-virtual-scroller/issues/773) ([#761](https://github.com/Akryum/vue-virtual-scroller/issues/761)) ([7c809ad](https://github.com/Akryum/vue-virtual-scroller/commit/7c809ad1d612824867490c7bd5ce2861110412eb))
* sorting views not working, [#772](https://github.com/Akryum/vue-virtual-scroller/issues/772) ([0b199d1](https://github.com/Akryum/vue-virtual-scroller/commit/0b199d14c846ecc00b93f989adbe29961dc68aad))
* view not unused if item no longer present, fix [#774](https://github.com/Akryum/vue-virtual-scroller/issues/774) ([bd51403](https://github.com/Akryum/vue-virtual-scroller/commit/bd514031f537978f0343317bb9cee550c5bfd7ad))
* views not reused correctly ([d5a8d75](https://github.com/Akryum/vue-virtual-scroller/commit/d5a8d759090f9af656865dd98648941fb2c71fa2))


### Features

* allow throttling update calls ([#764](https://github.com/Akryum/vue-virtual-scroller/issues/764)) ([9ba57d7](https://github.com/Akryum/vue-virtual-scroller/commit/9ba57d7d84c06d2ad265a266958292081704f218))



# [2.0.0-beta.5](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.4...v2.0.0-beta.5) (2022-12-07)


### Bug Fixes

* duplicate active views ([1ef796b](https://github.com/Akryum/vue-virtual-scroller/commit/1ef796b42143da6d4e74f83b8ac88176128e6d77))
* **DynamicScroller:** gaps caused by DOM reusing not triggering ResizeObserver ([a21e191](https://github.com/Akryum/vue-virtual-scroller/commit/a21e1915d76741a2806abd3a702d450f722879c8))
* inconsistent state on reused view ([a14747d](https://github.com/Akryum/vue-virtual-scroller/commit/a14747d33d75eaf7fe820370436d70e82562939b))
* views map corruption + view not removed from unusedPool ([cef8860](https://github.com/Akryum/vue-virtual-scroller/commit/cef886085c52f62736cf4c404a32f4f4fce6d229))


### Performance Improvements

* unnecessary loop ([86d0d07](https://github.com/Akryum/vue-virtual-scroller/commit/86d0d0776e26542d1b94484ec6ff5410733d3f18))



# [2.0.0-beta.4](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.3...v2.0.0-beta.4) (2022-12-06)


### Bug Fixes

* improved dynamic scroller resize observer logic ([40f58b3](https://github.com/Akryum/vue-virtual-scroller/commit/40f58b3e3a411df36c09d59cc3776719f60d93cf))
* item sizes getting 'disabled' resulting in gaps ([55b4ab1](https://github.com/Akryum/vue-virtual-scroller/commit/55b4ab1df1b4998178f2f03a53c112086a2633f2))
* unusing views after non-continuous scroll ([11488b7](https://github.com/Akryum/vue-virtual-scroller/commit/11488b7d8ffdfe1384fe808e4a49c1ba95ad1383))
* views incorrectly unused (proxy identity comparison) ([395bbfb](https://github.com/Akryum/vue-virtual-scroller/commit/395bbfb73588455795ecc5b144281ce5fda042ff))



# [2.0.0-beta.3](https://github.com/Akryum/vue-virtual-scroller/compare/v2.0.0-beta.2...v2.0.0-beta.3) (2022-10-18)


### Performance Improvements

* small code changes to maximize performance ([3b4dbf3](https://github.com/Akryum/vue-virtual-scroller/commit/3b4dbf39f480745d53e4bb43217c2b35975e4ab6))


### Reverts

* pass key-field prop [#732](https://github.com/Akryum/vue-virtual-scroller/issues/732), fix [#758](https://github.com/Akryum/vue-virtual-scroller/issues/758) ([8d221e6](https://github.com/Akryum/vue-virtual-scroller/commit/8d221e6978e4924ab125337fc91f6b6de7a1f497))



# [2.0.0-beta.2](https://github.com/Akryum/vue-virtual-scroller/compare/v1.1.1...v2.0.0-beta.2) (2022-10-17)

### Bug Fixes

* fix: height NaN, fix [#757](https://github.com/Akryum/vue-virtual-scroller/issues/757)



# [2.0.0-beta.1](https://github.com/Akryum/vue-virtual-scroller/compare/v1.1.0...v2.0.0-beta.1) (2022-10-15)


### Bug Fixes

* Account for the height of the leading and trailing slots when calculating visible items, fix [#685](https://github.com/Akryum/vue-virtual-scroller/issues/685) ([24ab3ba](https://github.com/Akryum/vue-virtual-scroller/commit/24ab3ba773d5819fcbe29f13eab663d48bce73ca))
* avoid jumping scroll position when upper item size is calculated ([#374](https://github.com/Akryum/vue-virtual-scroller/issues/374)) ([fd58a95](https://github.com/Akryum/vue-virtual-scroller/commit/fd58a95392c98b8e67da66235fcf4cac78ea2fd4))
* clamp endIndex if less items than prerender ([#473](https://github.com/Akryum/vue-virtual-scroller/issues/473)) ([f9124aa](https://github.com/Akryum/vue-virtual-scroller/commit/f9124aa81c36b46df339a5f18e0e832ab6e5a580))
* DynamicScroller should pass its own keyField prop to child RecycleScroller ([#732](https://github.com/Akryum/vue-virtual-scroller/issues/732)) ([9673679](https://github.com/Akryum/vue-virtual-scroller/commit/9673679fc174cd6236fae4e19a9b1a3b625e900e))
* **DynamicScrollerItem:** watch item prop ([#700](https://github.com/Akryum/vue-virtual-scroller/issues/700)) ([4d3b956](https://github.com/Akryum/vue-virtual-scroller/commit/4d3b95651610b8396c8dff66af9267407eab8e72))
* issue with beforeDestroy hook ([#748](https://github.com/Akryum/vue-virtual-scroller/issues/748)) ([59f3f1b](https://github.com/Akryum/vue-virtual-scroller/commit/59f3f1b0aee9ab8ea276fee60e204b6dcc0baceb))
* merge ([c8363b1](https://github.com/Akryum/vue-virtual-scroller/commit/c8363b114f691042dbced3b5b79d2ebd7812f481))
* restore scroll in keep-alive ([#724](https://github.com/Akryum/vue-virtual-scroller/issues/724)) ([5011e06](https://github.com/Akryum/vue-virtual-scroller/commit/5011e06f2aa6ef8afa6ecaad804413e56a542c8d))
* scrollToItem works with pageMode ([#396](https://github.com/Akryum/vue-virtual-scroller/issues/396)) ([c9772bf](https://github.com/Akryum/vue-virtual-scroller/commit/c9772bfb9e87672de1480072c4d5dc8024d1e5d1))
* wrap the callback in requestAnimationFrame, fix [#516](https://github.com/Akryum/vue-virtual-scroller/issues/516) ([#517](https://github.com/Akryum/vue-virtual-scroller/issues/517)) ([6f359ab](https://github.com/Akryum/vue-virtual-scroller/commit/6f359abed6cf5d81a05d3760d6b622153f331f01))


### Features

* add an empty slot ([#398](https://github.com/Akryum/vue-virtual-scroller/issues/398)) ([5c2715c](https://github.com/Akryum/vue-virtual-scroller/commit/5c2715c0a2c52b0c27436baabbf982fcb9861131))
* add skipHover prop to deactive the hover detection ([#752](https://github.com/Akryum/vue-virtual-scroller/issues/752)) ([b613318](https://github.com/Akryum/vue-virtual-scroller/commit/b613318a52d4d8f84bda69f0189f27dd51d0aaff))
* adds configurable list/item tags for semantic html ([#203](https://github.com/Akryum/vue-virtual-scroller/issues/203)) ([3d24dc3](https://github.com/Akryum/vue-virtual-scroller/commit/3d24dc31928ec9eabe74294e5d5b3466109e1bc2))
* custom classes for list wrapper and list items. ([#397](https://github.com/Akryum/vue-virtual-scroller/issues/397)) ([32b285d](https://github.com/Akryum/vue-virtual-scroller/commit/32b285d40667870b65c71dc59b02627f97c67ea4))
* Emit events for scroll to begin and end of list ([#364](https://github.com/Akryum/vue-virtual-scroller/issues/364)) ([2a7bfd4](https://github.com/Akryum/vue-virtual-scroller/commit/2a7bfd45e1ee56e82426a67d9f3f3ba5a7839185))
* gridItems prop ([#27](https://github.com/Akryum/vue-virtual-scroller/issues/27)) ([6339e72](https://github.com/Akryum/vue-virtual-scroller/commit/6339e72693c982805648ae3001b7c2957d8aa39e))
* itemSecondarySize ([43d311c](https://github.com/Akryum/vue-virtual-scroller/commit/43d311c2f336de74da4d0ec705b0a3546eeda153))
* throw error when key field does not exist in item ([#265](https://github.com/Akryum/vue-virtual-scroller/issues/265)) ([c63129f](https://github.com/Akryum/vue-virtual-scroller/commit/c63129fdc8264d25c737db1c2ce2891a9b804705))
* update event provide range of the visible items ([#115](https://github.com/Akryum/vue-virtual-scroller/issues/115)) ([f19af6c](https://github.com/Akryum/vue-virtual-scroller/commit/f19af6c15346ff33e5d3c4b9729b02a73d5fe4df))


### Performance Improvements

* skipHover: don't add event listeners ([6b623b5](https://github.com/Akryum/vue-virtual-scroller/commit/6b623b56e4ab481b1e0cde883682df2cc81edf19))



