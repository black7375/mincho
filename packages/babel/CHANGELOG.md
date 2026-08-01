# @mincho-js/babel

## 0.2.0

### Minor Changes

- [#219](https://github.com/mincho-js/mincho/pull/219) [`90cde80`](https://github.com/mincho-js/mincho/commit/90cde801cc0133649869bfed9c2e053aa600f6db) Thanks [@black7375](https://github.com/black7375)! - **Compatibility**
  - Separate vanilla extract API to `./compat` entry point for backward compatibility.

- [#344](https://github.com/mincho-js/mincho/pull/344) [`06d761b`](https://github.com/mincho-js/mincho/commit/06d761b260f6fc5610cef26e76b11de661e41d64) Thanks [@black7375](https://github.com/black7375)! - Add optional React JSX `css` prop v2 support through scoped React JSX runtime exports and opt-in `jsxCssProp` transform, integration, Vite, and Esbuild options. Inline object `css` props compile through Mincho CSS-rule extraction, existing class values compile through `cx(...)`, and custom/member/custom-element targets rely on a `className` forwarding contract with runtime guards for missed transforms.

- [#222](https://github.com/mincho-js/mincho/pull/222) [`ee6e517`](https://github.com/mincho-js/mincho/commit/ee6e51736f26effa8bcb72d8d5cd907c2de629d8) Thanks [@black7375](https://github.com/black7375)! - **css**
  - Add `css.multiple()` API

- [#275](https://github.com/mincho-js/mincho/pull/275) [`4504956`](https://github.com/mincho-js/mincho/commit/4504956736658a23a6f0a5d9510bf066a43e614c) Thanks [@black7375](https://github.com/black7375)! - **styled**
  - Add `styled.div` like shorthand API

### Patch Changes

- [#249](https://github.com/mincho-js/mincho/pull/249) [`9699f0d`](https://github.com/mincho-js/mincho/commit/9699f0d9628ec431f49dda9ef329d58516794189) Thanks [@black7375](https://github.com/black7375)! - **package**
  - Achieve all [Are the types wrong](https://github.com/arethetypeswrong/arethetypeswrong.github.io) using [vite-plugin-dts-build's dual mode](https://github.com/black7375/vite-plugin-dts-build#dual-module-support).

## 0.1.0

### Minor Changes

- [#182](https://github.com/mincho-js/mincho/pull/182) [`d840ee2`](https://github.com/mincho-js/mincho/commit/d840ee2979fe23a0ddd97b9e182638b94ccf0d98) Thanks [@black7375](https://github.com/black7375)! - **Big Changes**
  - co-location: [@sangkukbae](https://github.com/sangkukbae)'s work, It's still experimental.
  - packages: `node16` supports
