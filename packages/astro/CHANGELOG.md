# astro

## 2.0.7

### Patch Changes

- [#6149](https://github.com/withastro/astro/pull/6149) [`592386b75`](https://github.com/withastro/astro/commit/592386b75541f3b7f7d95c631f86024b7e2d314d) Thanks [@bloycey](https://github.com/bloycey)! - Moved pagination error to AstroErrorData

- [#6153](https://github.com/withastro/astro/pull/6153) [`1b591a143`](https://github.com/withastro/astro/commit/1b591a1431b44eacd239ed8f76809916cabca1db) Thanks [@torchsmith](https://github.com/torchsmith)! - Respect `vite.build.emptyOutDir` setting during `astro build`

- [#6092](https://github.com/withastro/astro/pull/6092) [`bf8d7366a`](https://github.com/withastro/astro/commit/bf8d7366acb57e1b21181cc40fff55a821d8119e) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Ensure vite config (aliases, custom modules, etc) is respected when loading the content collection config

- [#6111](https://github.com/withastro/astro/pull/6111) [`ec38a8921`](https://github.com/withastro/astro/commit/ec38a8921f02a275949abcababe1b8afdf8184a2) Thanks [@e111077](https://github.com/e111077)! - Implement client:only functionality in Lit and add lit to the client:only warning

- [#6124](https://github.com/withastro/astro/pull/6124) [`f20a85b64`](https://github.com/withastro/astro/commit/f20a85b642994f240d8c94260fc55ffa1fd14294) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Fix outdated error message in `paginate()` function.

- [#6122](https://github.com/withastro/astro/pull/6122) [`9f22ac3d0`](https://github.com/withastro/astro/commit/9f22ac3d097ef2cb3b2bbe5343b8a8a49d83425d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Content collections: Fix accidental "use underscore to ignore" logs for `.DS_Store` files and underscored directory names.

- [#6114](https://github.com/withastro/astro/pull/6114) [`ac7fb04d6`](https://github.com/withastro/astro/commit/ac7fb04d6b162f28a337918138d5737e2c0fffad) Thanks [@bluwy](https://github.com/bluwy)! - Fix sourcemap generation when scanning files

- [#6119](https://github.com/withastro/astro/pull/6119) [`2189170be`](https://github.com/withastro/astro/commit/2189170be523f74f244e84ccab22c655219773ce) Thanks [@matthewp](https://github.com/matthewp)! - Fix hoisted script propagation in content collection pages

- [#6117](https://github.com/withastro/astro/pull/6117) [`32abe49bd`](https://github.com/withastro/astro/commit/32abe49bd073417b480b1b990f432a837c12eb6f) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix polyfills not being available in certain cases

## 2.0.6

### Patch Changes

- [#6107](https://github.com/withastro/astro/pull/6107) [`9bec6bc41`](https://github.com/withastro/astro/commit/9bec6bc410f324a41c67e5d185fa86f78d7625f2) Thanks [@matthewp](https://github.com/matthewp)! - Fixes head contents being placed in body in MDX components

## 2.0.5

### Patch Changes

- [#6052](https://github.com/withastro/astro/pull/6052) [`9793f19ec`](https://github.com/withastro/astro/commit/9793f19ecd4e64cbf3140454fe52aeee2c22c8c9) Thanks [@mayank99](https://github.com/mayank99)! - Error overlay will now show the error's `cause` if available.

- [#6070](https://github.com/withastro/astro/pull/6070) [`f91615f5c`](https://github.com/withastro/astro/commit/f91615f5c04fde36f115dad9110dd75254efd61d) Thanks [@AirBorne04](https://github.com/AirBorne04)! - \* safe guard against TextEncode.encode(HTMLString) [errors on vercel edge]

  - safe guard against html.replace when html is undefined

- [#6064](https://github.com/withastro/astro/pull/6064) [`2fb72c887`](https://github.com/withastro/astro/commit/2fb72c887f71c0a69ab512870d65b8c867774766) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Apply MDX `components` export when rendering as a content collection entry

## 2.0.4

### Patch Changes

- [#6045](https://github.com/withastro/astro/pull/6045) [`41e97158b`](https://github.com/withastro/astro/commit/41e97158ba90d23d346b6e3ff6c7c14b5ecbe903) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Improve error handling when an Astro component is rendered manually

- [#6036](https://github.com/withastro/astro/pull/6036) [`e779c6242`](https://github.com/withastro/astro/commit/e779c6242418d1d4102e683ca5b851b764c89688) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Improve error handling when top-level `return` is present

## 2.0.3

### Patch Changes

- [#6035](https://github.com/withastro/astro/pull/6035) [`b4432cd6b`](https://github.com/withastro/astro/commit/b4432cd6b65bad685a99fe15867710b0663c13b2) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix: Astro component scripts now load in development when using MDX + Content Collections

- [#6024](https://github.com/withastro/astro/pull/6024) [`98a4a914b`](https://github.com/withastro/astro/commit/98a4a914bc47f3da2764b3bdc01577d25fe2e261) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Remove `rawContent()` and `compiledContent()` from MDX import types

- [#6034](https://github.com/withastro/astro/pull/6034) [`071e1dee7`](https://github.com/withastro/astro/commit/071e1dee7e1943be67d1ded39a9af1b7a2aafd02) Thanks [@matthewp](https://github.com/matthewp)! - Ensure CSS injections properly when using multiple layouts

- [#5927](https://github.com/withastro/astro/pull/5927) [`322e059d0`](https://github.com/withastro/astro/commit/322e059d0da9ab0d6a546a111fabda755bd5f1b6) Thanks [@izmttk](https://github.com/izmttk)! - Fix undefined `remarkPluginFrontmatter` after calling `render` method

- [#6006](https://github.com/withastro/astro/pull/6006) [`b994f6f35`](https://github.com/withastro/astro/commit/b994f6f35e29b2d93ff8ddc281a69c0af3cc3edf) Thanks [@tony-sull](https://github.com/tony-sull)! - Makes the `AstroCookies` type available as an import from the main "astro" package

- [#5998](https://github.com/withastro/astro/pull/5998) [`12c68343c`](https://github.com/withastro/astro/commit/12c68343c0aa891037d39d3c9b9378b004be6642) Thanks [@andersk](https://github.com/andersk)! - Update `getCollection()` filter to support type guards _or_ unknown values

## 2.0.2

### Patch Changes

- [#5983](https://github.com/withastro/astro/pull/5983) [`b53e0717b`](https://github.com/withastro/astro/commit/b53e0717b7f6b042baaeec7f87999e99c76c031c) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fixes a dev server edge case where prerender + getStaticPaths would not 404 on an unmatched route

- [#5992](https://github.com/withastro/astro/pull/5992) [`60b32d585`](https://github.com/withastro/astro/commit/60b32d58565d87e87573eb268408293fc28ec657) Thanks [@HiDeoo](https://github.com/HiDeoo)! - Fix `Astro.url.protocol` when using the @astrojs/node SSR adapter with HTTPS

- [#5971](https://github.com/withastro/astro/pull/5971) [`883e0cc29`](https://github.com/withastro/astro/commit/883e0cc29968d51ed6c7515be035a40b28bafdad) Thanks [@JLarky](https://github.com/JLarky)! - improve error message: change @astrojs/solid to @astrojs/solid-js

- [#5970](https://github.com/withastro/astro/pull/5970) [`dabce6b8c`](https://github.com/withastro/astro/commit/dabce6b8c684f851c3535f8acead06cbef6dce2a) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add type guard support to filters on `getCollection()`

- [#5952](https://github.com/withastro/astro/pull/5952) [`aedf23f85`](https://github.com/withastro/astro/commit/aedf23f8582e32a6b94b81ddba9b323831f2b22a) Thanks [@wulinsheng123](https://github.com/wulinsheng123)! - Fix custom theme handling for `<Code>` component

- Updated dependencies [[`7abb1e905`](https://github.com/withastro/astro/commit/7abb1e9056c4b4fd0abfced347df32a41cdfbf28)]:
  - @astrojs/markdown-remark@2.0.1

## 2.0.1

### Patch Changes

- [#5969](https://github.com/withastro/astro/pull/5969) [`f4c71e5eb`](https://github.com/withastro/astro/commit/f4c71e5eb937ce92cc8803d4a6e19400d22ae611) Thanks [@matthewp](https://github.com/matthewp)! - Fix usage of logger in Vercel Edge

  This protects against usage of `process` global in shimmed environments.

- [#5962](https://github.com/withastro/astro/pull/5962) [`46b6e1426`](https://github.com/withastro/astro/commit/46b6e14265f81ffbf1a7511909d5a9954160b504) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Fix Content Collections not loading config file when there are spaces in the folder tree

- [#5972](https://github.com/withastro/astro/pull/5972) [`02549b8ce`](https://github.com/withastro/astro/commit/02549b8ced18bf193efc407a625d908b65b3979f) Thanks [@bluwy](https://github.com/bluwy)! - Correctly detect Node.js version

## 2.0.0

> **Note**
> This is a detailed changelog of all changes in Astro v2.  
> See our [upgrade guide](https://docs.astro.build/en/guides/upgrade-to/v2/) for an overview of steps needed to upgrade an existing project.

### Major Changes

- [#5687](https://github.com/withastro/astro/pull/5687) [`e2019be6f`](https://github.com/withastro/astro/commit/e2019be6ffa46fa33d92cfd346f9ecbe51bb7144) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Give remark and rehype plugins access to user frontmatter via frontmatter injection. This means `data.astro.frontmatter` is now the _complete_ Markdown or MDX document's frontmatter, rather than an empty object.

  This allows plugin authors to modify existing frontmatter, or compute new properties based on other properties. For example, say you want to compute a full image URL based on an `imageSrc` slug in your document frontmatter:

  ```ts
  export function remarkInjectSocialImagePlugin() {
    return function (tree, file) {
      const { frontmatter } = file.data.astro;
      frontmatter.socialImageSrc = new URL(frontmatter.imageSrc, 'https://my-blog.com/').pathname;
    };
  }
  ```

  When using Content Collections, you can access this modified frontmatter using the `remarkPluginFrontmatter` property returned when rendering an entry.

  **Migration instructions**

  Plugin authors should now **check for user frontmatter when applying defaults.**

  For example, say a remark plugin wants to apply a default `title` if none is present. Add a conditional to check if the property is present, and update if none exists:

  ```diff
  export function remarkInjectTitlePlugin() {
    return function (tree, file) {
      const { frontmatter } = file.data.astro;
  +    if (!frontmatter.title) {
        frontmatter.title = 'Default title';
  +    }
    }
  }
  ```

  This differs from previous behavior, where a Markdown file's frontmatter would _always_ override frontmatter injected via remark or reype.

- [#5891](https://github.com/withastro/astro/pull/5891) [`05caf445d`](https://github.com/withastro/astro/commit/05caf445d4d2728f1010aeb2179a9e756c2fd17d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Remove deprecated Markdown APIs from Astro v0.X. This includes `getHeaders()`, the `.astro` property for layouts, and the `rawContent()` and `compiledContent()` error messages for MDX.

- [#5778](https://github.com/withastro/astro/pull/5778) [`49ab4f231`](https://github.com/withastro/astro/commit/49ab4f231c23b34891c3ee86f4b92bf8d6d267a3) Thanks [@bluwy](https://github.com/bluwy)! - Remove proload to load the Astro config. It will now use NodeJS and Vite to load the config only.

- [#5728](https://github.com/withastro/astro/pull/5728) [`8fb28648f`](https://github.com/withastro/astro/commit/8fb28648f66629741cb976bfe34ccd9d8f55661e) Thanks [@natemoo-re](https://github.com/natemoo-re)! - The previously experimental features `--experimental-error-overlay` and `--experimental-prerender`, both added in v1.7.0, are now the default.

  You'll notice that the error overlay during `astro dev` has a refreshed visual design and provides more context for your errors.

  The `prerender` feature is now enabled by default when using `output: 'server'`. To prerender a particular page, add `export const prerender = true` to your frontmatter.

  > **Warning**
  > Integration authors that previously relied on the exact structure of Astro's v1.0 build output may notice some changes to our output file structure. Please test your integrations to ensure compatability.
  > Users that have configured a custom `vite.build.rollupOptions.output.chunkFileNames` should ensure that their Astro project is configured as an ESM Node project. Either include `"type": "module"` in your root `package.json` file or use the `.mjs` extension for `chunkFileNames`.

- [#5782](https://github.com/withastro/astro/pull/5782) [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Remove support for Node 14. Minimum supported Node version is now >=16.12.0

- [#5771](https://github.com/withastro/astro/pull/5771) [`259a539d7`](https://github.com/withastro/astro/commit/259a539d7d70c783330c797794b15716921629cf) Thanks [@matthewp](https://github.com/matthewp)! - Removes support for astroFlavoredMarkdown

  In 1.0 Astro moved the old Astro Flavored Markdown (also sometimes called Components in Markdown) to a legacy feature. This change removes the `legacy.astroFlavoredMarkdown` option completely.

  In 2.0 this feature will not be available in Astro at all. We recommend migration to MDX for those were still using this feature in 1.x.

- [#5941](https://github.com/withastro/astro/pull/5941) [`304823811`](https://github.com/withastro/astro/commit/304823811eddd8e72aa1d8e2d39b40ab5cda3565) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Content collections: Introduce a new `slug` frontmatter field for overriding the generated slug. This replaces the previous `slug()` collection config option from Astro 1.X and the 2.0 beta.

  When present in a Markdown or MDX file, this will override the generated slug for that entry.

  ```diff
  # src/content/blog/post-1.md
  ---
  title: Post 1
  + slug: post-1-custom-slug
  ---
  ```

  Astro will respect this slug in the generated `slug` type and when using the `getEntryBySlug()` utility:

  ```astro
  ---
  import { getEntryBySlug } from 'astro:content';

  // Retrieve `src/content/blog/post-1.md` by slug with type safety
  const post = await getEntryBySlug('blog', 'post-1-custom-slug');
  ---
  ```

  **Migration**

  If you relied on the `slug()` config option, you will need to move all custom slugs to `slug` frontmatter properties in each collection entry.

  Additionally, Astro no longer allows `slug` as a collection schema property. This ensures Astro can manage the `slug` property for type generation and performance. Remove this property from your schema and any relevant `slug()` configuration:

  ```diff
  const blog = defineCollection({
    schema: z.object({
  -   slug: z.string().optional(),
    }),
  - slug({ defaultSlug, data }) {
  -   return data.slug ?? defaultSlug;
  - },
  })
  ```

- [#5753](https://github.com/withastro/astro/pull/5753) [`302e0ef8f`](https://github.com/withastro/astro/commit/302e0ef8f5d5232e3348afe680e599f3e537b5c5) Thanks [@bluwy](https://github.com/bluwy)! - Default preview host to `localhost` instead of `127.0.0.1`. This allows the static server and integration preview servers to serve under ipv6.

- [#5716](https://github.com/withastro/astro/pull/5716) [`dd56c1941`](https://github.com/withastro/astro/commit/dd56c19411b126439b8bc42d681b6fa8c06e8c61) Thanks [@bluwy](https://github.com/bluwy)! - Remove MDX Fragment hack. This was used by `@astrojs/mdx` to access the `Fragment` component, but isn't required anymore since `@astrojs/mdx` v0.12.1.

- [#5584](https://github.com/withastro/astro/pull/5584) [`9963c6e4d`](https://github.com/withastro/astro/commit/9963c6e4d50c392c3d1ac4492237020f15ccb1de) & [#5842](https://github.com/withastro/astro/pull/5842) [`c4b0cb8bf`](https://github.com/withastro/astro/commit/c4b0cb8bf2b41887d9106440bb2e70d421a5f481) Thanks [@wulinsheng123](https://github.com/wulinsheng123) and [@natemoo-re](https://github.com/natemoo-re)! - **Breaking Change**: client assets are built to an `_astro` directory in the build output directory. Previously these were built to various locations, including `assets/`, `chunks/` and the root of build output.

  You can control this location with the new `build` configuration option named `assets`.

- [#5893](https://github.com/withastro/astro/pull/5893) [`be901dc98`](https://github.com/withastro/astro/commit/be901dc98c4a7f6b5536540aa8f7ba5108e939a0) Thanks [@matthewp](https://github.com/matthewp)! - Rename `getEntry` to `getEntryBySlug`

  This change moves `getEntry` to `getEntryBySlug` and accepts a slug rather than an id.

  In order to improve support in `[id].astro` routes, particularly in SSR where you do not know what the id of a collection is. Using `getEntryBySlug` instead allows you to map the `[id]` param in your route to the entry. You can use it like this:

  ```astro
  ---
  import { getEntryBySlug } from 'astro:content';

  const entry = await getEntryBySlug('docs', Astro.params.id);

  if (!entry) {
    return new Response(null, {
      status: 404,
    });
  }
  ---

  <!-- You have an entry! Use it! -->
  ```

- [#5685](https://github.com/withastro/astro/pull/5685) [`f6cf92b48`](https://github.com/withastro/astro/commit/f6cf92b48317a19a3840ad781b77d6d3cae143bb) Thanks [@bluwy](https://github.com/bluwy)! - Upgrade to Vite 4. Please see its [migration guide](https://vitejs.dev/guide/migration.html) for more information.

- [#5724](https://github.com/withastro/astro/pull/5724) [`16c7d0bfd`](https://github.com/withastro/astro/commit/16c7d0bfd49d2b9bfae45385f506bcd642f9444a) Thanks [@bluwy](https://github.com/bluwy)! - Remove outdated Vue info log. Remove `toString` support for `RenderTemplateResult`.

- [#5684](https://github.com/withastro/astro/pull/5684) [`a9c292026`](https://github.com/withastro/astro/commit/a9c2920264e36cc5dc05f4adc1912187979edb0d) & [#5769](https://github.com/withastro/astro/pull/5769) [`93e633922`](https://github.com/withastro/astro/commit/93e633922c2e449df3bb2357b3683af1d3c0e07b) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Refine Markdown and MDX configuration options for ease-of-use.

  - **Markdown**

    - **Replace the `extendDefaultPlugins` option** with a `gfm` boolean and a `smartypants` boolean. These are enabled by default, and can be disabled to remove GitHub-Flavored Markdown and SmartyPants.

    - Ensure GitHub-Flavored Markdown and SmartyPants are applied whether or not custom `remarkPlugins` or `rehypePlugins` are configured. If you want to apply custom plugins _and_ remove Astro's default plugins, manually set `gfm: false` and `smartypants: false` in your config.

  - **Migrate `extendDefaultPlugins` to `gfm` and `smartypants`**

    You may have disabled Astro's built-in plugins (GitHub-Flavored Markdown and Smartypants) with the `extendDefaultPlugins` option. This has now been split into 2 flags to disable each plugin individually:

    - `markdown.gfm` to disable GitHub-Flavored Markdown
    - `markdown.smartypants` to disable SmartyPants

    ```diff
    // astro.config.mjs
    import { defineConfig } from 'astro/config';

    export default defineConfig({
      markdown: {
    -   extendDefaultPlugins: false,
    +   smartypants: false,
    +   gfm: false,
      }
    });
    ```

    Additionally, applying remark and rehype plugins **no longer disables** `gfm` and `smartypants`. You will need to opt-out manually by setting `gfm` and `smartypants` to `false`.

  - **MDX**

    - Support _all_ Markdown configuration options (except `drafts`) from your MDX integration config. This includes `syntaxHighlighting` and `shikiConfig` options to further customize the MDX renderer.

    - Simplify `extendPlugins` to an `extendMarkdownConfig` option. MDX options will default to their equivalent in your Markdown config. By setting `extendMarkdownConfig` to false, you can "eject" to set your own syntax highlighting, plugins, and more.

  - **Migrate MDX's `extendPlugins` to `extendMarkdownConfig`**

    You may have used the `extendPlugins` option to manage plugin defaults in MDX. This has been replaced by 3 flags:

    - `extendMarkdownConfig` (`true` by default) to toggle Markdown config inheritance. This replaces the `extendPlugins: 'markdown'` option.
    - `gfm` (`true` by default) and `smartypants` (`true` by default) to toggle GitHub-Flavored Markdown and SmartyPants in MDX. This replaces the `extendPlugins: 'defaults'` option.

- [#5717](https://github.com/withastro/astro/pull/5717) [`a3a7fc929`](https://github.com/withastro/astro/commit/a3a7fc9298e6d88abb4b7bee1e58f05fa9558cf1) Thanks [@bluwy](https://github.com/bluwy)! - Remove `style.postcss` Astro config. Refactor tailwind integration to configure through `vite` instead. Also disables `autoprefixer` in dev.

- [#5825](https://github.com/withastro/astro/pull/5825) [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Baseline the experimental `contentCollections` flag. You're free to remove this from your astro config!

  ```diff
  import { defineConfig } from 'astro/config';

  export default defineConfig({
  - experimental: { contentCollections: true }
  })

  ```

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove deprecated `Astro` global APIs, including `Astro.resolve`, `Astro.fetchContent`, and `Astro.canonicalURL`.

  - **`Astro.resolve`**

    You can resolve asset paths using `import` instead. For example:

    ```astro
    ---
    import 'style.css';
    import imageUrl from './image.png';
    ---

    <img src={imageUrl} />
    ```

    See the [v0.25 migration guide](https://docs.astro.build/en/migrate/#deprecated-astroresolve) for more information.

  - **`Astro.fetchContent`**

    Use `Astro.glob` instead to fetch markdown files, or migrate to the [Content Collections](https://docs.astro.build/en/guides/content-collections/) feature.

    ```js
    let allPosts = await Astro.glob('./posts/*.md');
    ```

  - **`Astro.canonicalURL`**

    Use `Astro.url` instead to construct the canonical URL.

    ```js
    const canonicalURL = new URL(Astro.url.pathname, Astro.site);
    ```

- [#5608](https://github.com/withastro/astro/pull/5608) [`899214298`](https://github.com/withastro/astro/commit/899214298cee5f0c975c7245e623c649e1842d73) Thanks [@konojunya](https://github.com/konojunya)! - A trailing slash will not be automatically appended to `import.meta.env.SITE`. Instead, it will be the value of the `site` config as is. This may affect usages of `${import.meta.env.SITE}image.png`, which will need to be updated accordingly.

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove `buildConfig` option parameter from integration `astro:build:start` hook in favour of the `build.config` option in the `astro:config:setup` hook.

  ```js
  export default function myIntegration() {
    return {
      name: 'my-integration',
      hooks: {
        'astro:config:setup': ({ updateConfig }) => {
          updateConfig({
            build: {
              client: '...',
              server: '...',
              serverEntry: '...',
            },
          });
        },
      },
    };
  }
  ```

- [#5862](https://github.com/withastro/astro/pull/5862) [`1ca81c16b`](https://github.com/withastro/astro/commit/1ca81c16b8b66236e092e6eb6ec3f73f5668421c) Thanks [@bluwy](https://github.com/bluwy)! - Remove unused exports

### Minor Changes

- [#5901](https://github.com/withastro/astro/pull/5901) [`a342a486c`](https://github.com/withastro/astro/commit/a342a486c2831461e24e6c2f1ca8a9d3e15477b6) Thanks [@bluwy](https://github.com/bluwy)! - The fallback Svelte preprocessor will only be applied if a custom `preprocess` option is not passed to the `svelte()` integration option, or in the `svelte.config.js` file.

  To support IDE autocompletion, or if you're migrating from `@astrojs/svelte` v1, you can create a `svelte.config.js` file with:

  ```js
  import { vitePreprocess } from '@astrojs/svelte';

  export default {
    preprocess: vitePreprocess(),
  };
  ```

  This file will also be generated by `astro add svelte` by default.

- [#5786](https://github.com/withastro/astro/pull/5786) [`c2180746b`](https://github.com/withastro/astro/commit/c2180746b4f6d9ef1b6f86924f21f52cc6ab4e63) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Move generated content collection types to a `.astro` directory. This replaces the previously generated `src/content/types.generated.d.ts` file.

  If you're using Git for version control, we recommend ignoring this generated directory by adding `.astro` to your .gitignore.

  Astro will also generate the [TypeScript reference path](https://www.typescriptlang.org/docs/handbook/triple-slash-directives.html#-reference-path-) to include `.astro` types in your project. This will update your project's `src/env.d.ts` file, or write one if none exists.

- [#5826](https://github.com/withastro/astro/pull/5826) [`840412128`](https://github.com/withastro/astro/commit/840412128b00a04515156e92c314a929d6b94f6d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Allow Zod objects, unions, discriminated unions, intersections, and transform results as content collection schemas.

  #### Migration

  Astro requires a `z.object(...)` wrapper on all content collection schemas. Update your content collections config like so:

  ```diff
  // src/content/config.ts
  import { z, defineCollection } from 'astro:content';

  const blog = defineCollection({
  - schema: {
  + schema: z.object({
    ...
  })
  ```

- [#5823](https://github.com/withastro/astro/pull/5823) [`1f49cddf9`](https://github.com/withastro/astro/commit/1f49cddf9e9ffc651efc171b2cbde9fbe9e8709d) Thanks [@delucis](https://github.com/delucis)! - Generate content types when running `astro check`

- [#5832](https://github.com/withastro/astro/pull/5832) [`2303f9514`](https://github.com/withastro/astro/commit/2303f95142aa740c99213a098f82b99dd37d74a0) Thanks [@HiDeoo](https://github.com/HiDeoo)! - Add support for serving well-known URIs with the @astrojs/node SSR adapter

### Patch Changes

- [#5855](https://github.com/withastro/astro/pull/5855) [`16dc36a87`](https://github.com/withastro/astro/commit/16dc36a870df47a4151a8ed2d91d0bd1bb812458) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Remove legacy compiler error handling

- [#5822](https://github.com/withastro/astro/pull/5822) [`01f3f463b`](https://github.com/withastro/astro/commit/01f3f463bf2918b310d130a9fabbf3ee21d14029) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix edge case with bundle generation by emitting a single chunk for pages

- [#5803](https://github.com/withastro/astro/pull/5803) [`ae8a012a7`](https://github.com/withastro/astro/commit/ae8a012a7b6884a03c50494332ee37b4505c2c3b) Thanks [@bluwy](https://github.com/bluwy)! - Upgrade compiler and handle breaking changes

- [#5840](https://github.com/withastro/astro/pull/5840) [`cf2de5422`](https://github.com/withastro/astro/commit/cf2de5422c26bfdea4c75f76e57b57299ded3e3a) Thanks [@chenxsan](https://github.com/chenxsan)! - Persist CLI flags when restarting the dev server

- [#5884](https://github.com/withastro/astro/pull/5884) [`ce5c5dbd4`](https://github.com/withastro/astro/commit/ce5c5dbd46afbe738b03600758bf5c35113de522) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Add a theme toggle button to the error overlay

- [#5811](https://github.com/withastro/astro/pull/5811) [`ec09bb664`](https://github.com/withastro/astro/commit/ec09bb6642064dbd7d2f3369afb090363ae18de2) Thanks [@bluwy](https://github.com/bluwy)! - Simplify HMR handling

- [#5824](https://github.com/withastro/astro/pull/5824) [`665a2c222`](https://github.com/withastro/astro/commit/665a2c2225e42881f5a9550599e8f3fc1deea0b4) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Better handle content type generation failures:

  - Generate types when content directory is empty
  - Log helpful error when running `astro sync` without a content directory
  - Avoid swallowing `config.ts` syntax errors from Vite

- [#5791](https://github.com/withastro/astro/pull/5791) [`f7aa1ec25`](https://github.com/withastro/astro/commit/f7aa1ec25d1584f7abd421903fbef66b1c050e2a) Thanks [@ba55ie](https://github.com/ba55ie)! - Fix Lit slotted content

- [#5499](https://github.com/withastro/astro/pull/5499) [`4987d6f44`](https://github.com/withastro/astro/commit/4987d6f44cfd0d81d88f21f5c380503403dc1e6a) Thanks [@bluwy](https://github.com/bluwy)! - Handle custom injected entry files during build

- [#5734](https://github.com/withastro/astro/pull/5734) [`55cea0a9d`](https://github.com/withastro/astro/commit/55cea0a9d8c8df91a46590fc04a9ac28089b3432) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix `prerender` when used with `getStaticPaths`

- [#5845](https://github.com/withastro/astro/pull/5845) [`e818cc046`](https://github.com/withastro/astro/commit/e818cc0466a942919ea3c41585e231c8c80cb3d0) Thanks [@bluwy](https://github.com/bluwy)! - Fix importing client-side components with alias

- [#5849](https://github.com/withastro/astro/pull/5849) [`8c100a6fe`](https://github.com/withastro/astro/commit/8c100a6fe6cc652c3799d1622e12c2c969f30510) Thanks [@bluwy](https://github.com/bluwy)! - Handle server restart from Vite plugins

- [#5756](https://github.com/withastro/astro/pull/5756) [`116d8835c`](https://github.com/withastro/astro/commit/116d8835ca9e78f8b5e477ee5a3d737b69f80706) Thanks [@matthewp](https://github.com/matthewp)! - Fix for hoisted scripts in project with spaces in the file path

- [#5917](https://github.com/withastro/astro/pull/5917) [`7325df412`](https://github.com/withastro/astro/commit/7325df412107fc0e65cd45c1b568fb686708f723) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix duplicate CSS in dev mode when `vite.css.devSourcemap` is provided

- [#5743](https://github.com/withastro/astro/pull/5743) [`2a5786419`](https://github.com/withastro/astro/commit/2a5786419599b8674473c699300172b9aacbae2e) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add error location during build for user-generated errors

- [#5773](https://github.com/withastro/astro/pull/5773) [`4a1cabfe6`](https://github.com/withastro/astro/commit/4a1cabfe6b9ef8a6fbbcc0727a0dc6fa300cedaa) Thanks [@bluwy](https://github.com/bluwy)! - Cleanup dependencies

- [#5905](https://github.com/withastro/astro/pull/5905) [`a8d3e7924`](https://github.com/withastro/astro/commit/a8d3e79246605d252dcddad159e358e2d79bd624) Thanks [@bluwy](https://github.com/bluwy)! - Fix CLI node version check

- [#5761](https://github.com/withastro/astro/pull/5761) [`fa8c131f8`](https://github.com/withastro/astro/commit/fa8c131f88ef67d14c62f1c00c97ed74d43a80ac) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add helpful error message when the MDX integration is missing.

- [#5896](https://github.com/withastro/astro/pull/5896) [`64b8082e7`](https://github.com/withastro/astro/commit/64b8082e776b832f1433ed288e6f7888adb626d0) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Update `@astrojs/compiler` to `v1.0.0`

- [#5829](https://github.com/withastro/astro/pull/5829) [`23dc9ea96`](https://github.com/withastro/astro/commit/23dc9ea96a10343852d965efd41fe6665294f1fb) Thanks [@giuseppelt](https://github.com/giuseppelt)! - Fix `Code.astro` shiki css class replace logic

- [#5836](https://github.com/withastro/astro/pull/5836) [`63a6ceb38`](https://github.com/withastro/astro/commit/63a6ceb38d88331451dca64d0034c7c58e3d26f1) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix route matching when path includes special characters

- [#5909](https://github.com/withastro/astro/pull/5909) [`5fd9208d4`](https://github.com/withastro/astro/commit/5fd9208d447f5ab8909a2188b6c2491a0debd49d) Thanks [@jasikpark](https://github.com/jasikpark)! - Update compiler to 1.0.1

- [#5852](https://github.com/withastro/astro/pull/5852) [`3a00ecb3e`](https://github.com/withastro/astro/commit/3a00ecb3eb4bc44be758c064f2bde6e247e8a593) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - Respect `vite.envPrefix` if provided

- [#5872](https://github.com/withastro/astro/pull/5872) [`b66d7195c`](https://github.com/withastro/astro/commit/b66d7195c17a55ea0931bc3744888bd4f5f01ce6) Thanks [@bluwy](https://github.com/bluwy)! - Enable `skipLibCheck` by default

- Updated dependencies [[`93e633922`](https://github.com/withastro/astro/commit/93e633922c2e449df3bb2357b3683af1d3c0e07b), [`e2019be6f`](https://github.com/withastro/astro/commit/e2019be6ffa46fa33d92cfd346f9ecbe51bb7144), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`12f65a4d5`](https://github.com/withastro/astro/commit/12f65a4d55e3fd2993c2f67b18794dd536280c69), [`46ecd5de3`](https://github.com/withastro/astro/commit/46ecd5de34df619e2ee73ccea39a57acd37bc0b8), [`16107b6a1`](https://github.com/withastro/astro/commit/16107b6a10514ef1b563e585ec9add4b14f42b94), [`c55fbcb8e`](https://github.com/withastro/astro/commit/c55fbcb8edca1fe118a44f68c9f9436a4719d171), [`a9c292026`](https://github.com/withastro/astro/commit/a9c2920264e36cc5dc05f4adc1912187979edb0d), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f), [`7572f7402`](https://github.com/withastro/astro/commit/7572f7402238da37de748be58d678fedaf863b53)]:
  - @astrojs/markdown-remark@2.0.0
  - @astrojs/telemetry@2.0.0
  - @astrojs/webapi@2.0.0

## 2.0.0-beta.4

<details>
<summary>See changes in 2.0.0-beta.4</summary>

### Major Changes

- [#5941](https://github.com/withastro/astro/pull/5941) [`304823811`](https://github.com/withastro/astro/commit/304823811eddd8e72aa1d8e2d39b40ab5cda3565) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Content collections: Introduce a new `slug` frontmatter field for overriding the generated slug. This replaces the previous `slug()` collection config option from Astro 1.X and the 2.0 beta.

  When present in a Markdown or MDX file, this will override the generated slug for that entry.

  ```diff
  # src/content/blog/post-1.md
  ---
  title: Post 1
  + slug: post-1-custom-slug
  ---
  ```

  Astro will respect this slug in the generated `slug` type and when using the `getEntryBySlug()` utility:

  ```astro
  ---
  import { getEntryBySlug } from 'astro:content';

  // Retrieve `src/content/blog/post-1.md` by slug with type safety
  const post = await getEntryBySlug('blog', 'post-1-custom-slug');
  ---
  ```

  #### Migration

  If you relied on the `slug()` config option, you will need to move all custom slugs to `slug` frontmatter properties in each collection entry.

  Additionally, Astro no longer allows `slug` as a collection schema property. This ensures Astro can manage the `slug` property for type generation and performance. Remove this property from your schema and any relevant `slug()` configuration:

  ```diff
  const blog = defineCollection({
    schema: z.object({
  -   slug: z.string().optional(),
    }),
  - slug({ defaultSlug, data }) {
  -   return data.slug ?? defaultSlug;
  - },
  })
  ```

### Patch Changes

- [#5499](https://github.com/withastro/astro/pull/5499) [`4987d6f44`](https://github.com/withastro/astro/commit/4987d6f44cfd0d81d88f21f5c380503403dc1e6a) Thanks [@bluwy](https://github.com/bluwy)! - Handle custom injected entry files during build

- [#5917](https://github.com/withastro/astro/pull/5917) [`7325df412`](https://github.com/withastro/astro/commit/7325df412107fc0e65cd45c1b568fb686708f723) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix duplicate CSS in dev mode when `vite.css.devSourcemap` is provided

- [#5905](https://github.com/withastro/astro/pull/5905) [`a8d3e7924`](https://github.com/withastro/astro/commit/a8d3e79246605d252dcddad159e358e2d79bd624) Thanks [@bluwy](https://github.com/bluwy)! - Fix CLI node version check

- [#5909](https://github.com/withastro/astro/pull/5909) [`5fd9208d4`](https://github.com/withastro/astro/commit/5fd9208d447f5ab8909a2188b6c2491a0debd49d) Thanks [@jasikpark](https://github.com/jasikpark)! - Update compiler to 1.0.1

- Updated dependencies [[`46ecd5de3`](https://github.com/withastro/astro/commit/46ecd5de34df619e2ee73ccea39a57acd37bc0b8)]:
  - @astrojs/webapi@2.0.0-beta.1

</details>

## 2.0.0-beta.3

<details>
<summary>See changes in 2.0.0-beta.3</summary>

### Major Changes

- [#5891](https://github.com/withastro/astro/pull/5891) [`05caf445d`](https://github.com/withastro/astro/commit/05caf445d4d2728f1010aeb2179a9e756c2fd17d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Remove deprecated Markdown APIs from Astro v0.X. This includes `getHeaders()`, the `.astro` property for layouts, and the `rawContent()` and `compiledContent()` error messages for MDX.

- [#5893](https://github.com/withastro/astro/pull/5893) [`be901dc98`](https://github.com/withastro/astro/commit/be901dc98c4a7f6b5536540aa8f7ba5108e939a0) Thanks [@matthewp](https://github.com/matthewp)! - Move getEntry to getEntryBySlug

  This change moves `getEntry` to `getEntryBySlug` and accepts a slug rather than an id.

  In order to improve support in `[id].astro` routes, particularly in SSR where you do not know what the id of a collection is. Using `getEntryBySlug` instead allows you to map the `[id]` param in your route to the entry. You can use it like this:

  ```astro
  ---
  import { getEntryBySlug } from 'astro:content';

  const entry = await getEntryBySlug('docs', Astro.params.id);

  if (!entry) {
    return new Response(null, {
      status: 404,
    });
  }
  ---

  <!-- You have an entry! Use it! -->
  ```

- [#5608](https://github.com/withastro/astro/pull/5608) [`899214298`](https://github.com/withastro/astro/commit/899214298cee5f0c975c7245e623c649e1842d73) Thanks [@konojunya](https://github.com/konojunya)! - A trailing slash will not be automatically appended to `import.meta.env.SITE`. Instead, it will be the value of the `site` config as is. This may affect usages of `${import.meta.env.SITE}image.png`, which will need to be updated accordingly.

- [#5862](https://github.com/withastro/astro/pull/5862) [`1ca81c16b`](https://github.com/withastro/astro/commit/1ca81c16b8b66236e092e6eb6ec3f73f5668421c) Thanks [@bluwy](https://github.com/bluwy)! - Remove unused exports

### Minor Changes

- [#5901](https://github.com/withastro/astro/pull/5901) [`a342a486c`](https://github.com/withastro/astro/commit/a342a486c2831461e24e6c2f1ca8a9d3e15477b6) Thanks [@bluwy](https://github.com/bluwy)! - The fallback Svelte preprocessor will only be applied if a custom `preprocess` option is not passed to the `svelte()` integration option, or in the `svelte.config.js` file.

  To support IDE autocompletion, or if you're migrating from `@astrojs/svelte` v1, you can create a `svelte.config.js` file with:

  ```js
  import { vitePreprocess } from '@astrojs/svelte';

  export default {
    preprocess: vitePreprocess(),
  };
  ```

  This file will also be generated by `astro add svelte` by default.

### Patch Changes

- [#5855](https://github.com/withastro/astro/pull/5855) [`16dc36a87`](https://github.com/withastro/astro/commit/16dc36a870df47a4151a8ed2d91d0bd1bb812458) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Remove legacy compiler error handling

- [#5884](https://github.com/withastro/astro/pull/5884) [`ce5c5dbd4`](https://github.com/withastro/astro/commit/ce5c5dbd46afbe738b03600758bf5c35113de522) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Add a theme toggle button to the error overlay

- [#5845](https://github.com/withastro/astro/pull/5845) [`e818cc046`](https://github.com/withastro/astro/commit/e818cc0466a942919ea3c41585e231c8c80cb3d0) Thanks [@bluwy](https://github.com/bluwy)! - Fix importing client-side components with alias

- [#5849](https://github.com/withastro/astro/pull/5849) [`8c100a6fe`](https://github.com/withastro/astro/commit/8c100a6fe6cc652c3799d1622e12c2c969f30510) Thanks [@bluwy](https://github.com/bluwy)! - Handle server restart from Vite plugins

- [#5896](https://github.com/withastro/astro/pull/5896) [`64b8082e7`](https://github.com/withastro/astro/commit/64b8082e776b832f1433ed288e6f7888adb626d0) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Update `@astrojs/compiler` to `v1.0.0`

- [#5852](https://github.com/withastro/astro/pull/5852) [`3a00ecb3e`](https://github.com/withastro/astro/commit/3a00ecb3eb4bc44be758c064f2bde6e247e8a593) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - Respect `vite.envPrefix` if provided

- [#5872](https://github.com/withastro/astro/pull/5872) [`b66d7195c`](https://github.com/withastro/astro/commit/b66d7195c17a55ea0931bc3744888bd4f5f01ce6) Thanks [@bluwy](https://github.com/bluwy)! - Enable `skipLibCheck` by default

</details>

## 2.0.0-beta.2

<details>
<summary>See changes in 2.0.0-beta.2</summary>

### Major Changes

- [#5782](https://github.com/withastro/astro/pull/5782) [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Remove support for Node 14. Minimum supported Node version is now >=16.12.0

- [#5753](https://github.com/withastro/astro/pull/5753) [`302e0ef8f`](https://github.com/withastro/astro/commit/302e0ef8f5d5232e3348afe680e599f3e537b5c5) Thanks [@bluwy](https://github.com/bluwy)! - Default preview host to `localhost` instead of `127.0.0.1`. This allows the static server and integration preview servers to serve under ipv6.

- [#5842](https://github.com/withastro/astro/pull/5842) [`c4b0cb8bf`](https://github.com/withastro/astro/commit/c4b0cb8bf2b41887d9106440bb2e70d421a5f481) Thanks [@natemoo-re](https://github.com/natemoo-re)! - **Breaking Change**: client assets are built to an `_astro` directory in the build output directory. Previously these were built to various locations, including `assets/`, `chunks/` and the root of build output.

  You can control this location with the new `build` configuration option named `assets`.

- [#5825](https://github.com/withastro/astro/pull/5825) [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Baseline the experimental `contentCollections` flag. You're free to remove this from your astro config!

  ```diff
  import { defineConfig } from 'astro/config';

  export default defineConfig({
  - experimental: { contentCollections: true }
  })
  ```

### Minor Changes

- [#5786](https://github.com/withastro/astro/pull/5786) [`c2180746b`](https://github.com/withastro/astro/commit/c2180746b4f6d9ef1b6f86924f21f52cc6ab4e63) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Move generated content collection types to a `.astro` directory. This replaces the previously generated `src/content/types.generated.d.ts` file.

  If you're using Git for version control, we recommend ignoring this generated directory by adding `.astro` to your .gitignore.

  Astro will also generate the [TypeScript reference path](https://www.typescriptlang.org/docs/handbook/triple-slash-directives.html#-reference-path-) to include `.astro` types in your project. This will update your project's `src/env.d.ts` file, or write one if none exists.

- [#5826](https://github.com/withastro/astro/pull/5826) [`840412128`](https://github.com/withastro/astro/commit/840412128b00a04515156e92c314a929d6b94f6d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Allow Zod objects, unions, discriminated unions, intersections, and transform results as content collection schemas.

  #### Migration

  Astro requires a `z.object(...)` wrapper on all content collection schemas. Update your content collections config like so:

  ```diff
  // src/content/config.ts
  import { z, defineCollection } from 'astro:content';

  const blog = defineCollection({
  - schema: {
  + schema: z.object({
    ...
  })
  ```

- [#5823](https://github.com/withastro/astro/pull/5823) [`1f49cddf9`](https://github.com/withastro/astro/commit/1f49cddf9e9ffc651efc171b2cbde9fbe9e8709d) Thanks [@delucis](https://github.com/delucis)! - Generate content types when running `astro check`

- [#5832](https://github.com/withastro/astro/pull/5832) [`2303f9514`](https://github.com/withastro/astro/commit/2303f95142aa740c99213a098f82b99dd37d74a0) Thanks [@HiDeoo](https://github.com/HiDeoo)! - Add support for serving well-known URIs with the @astrojs/node SSR adapter

### Patch Changes

- [#5822](https://github.com/withastro/astro/pull/5822) [`01f3f463b`](https://github.com/withastro/astro/commit/01f3f463bf2918b310d130a9fabbf3ee21d14029) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix edge case with bundle generation by emitting a single chunk for pages

- [#5803](https://github.com/withastro/astro/pull/5803) [`ae8a012a7`](https://github.com/withastro/astro/commit/ae8a012a7b6884a03c50494332ee37b4505c2c3b) Thanks [@bluwy](https://github.com/bluwy)! - Upgrade compiler and handle breaking changes

- [#5840](https://github.com/withastro/astro/pull/5840) [`cf2de5422`](https://github.com/withastro/astro/commit/cf2de5422c26bfdea4c75f76e57b57299ded3e3a) Thanks [@chenxsan](https://github.com/chenxsan)! - Persist CLI flags when restarting the dev server

- [#5811](https://github.com/withastro/astro/pull/5811) [`ec09bb664`](https://github.com/withastro/astro/commit/ec09bb6642064dbd7d2f3369afb090363ae18de2) Thanks [@bluwy](https://github.com/bluwy)! - Simplify HMR handling

- [#5824](https://github.com/withastro/astro/pull/5824) [`665a2c222`](https://github.com/withastro/astro/commit/665a2c2225e42881f5a9550599e8f3fc1deea0b4) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Better handle content type generation failures:

  - Generate types when content directory is empty
  - Log helpful error when running `astro sync` without a content directory
  - Avoid swallowing `config.ts` syntax errors from Vite

- [#5791](https://github.com/withastro/astro/pull/5791) [`f7aa1ec25`](https://github.com/withastro/astro/commit/f7aa1ec25d1584f7abd421903fbef66b1c050e2a) Thanks [@ba55ie](https://github.com/ba55ie)! - Fix Lit slotted content

- [#5773](https://github.com/withastro/astro/pull/5773) [`4a1cabfe6`](https://github.com/withastro/astro/commit/4a1cabfe6b9ef8a6fbbcc0727a0dc6fa300cedaa) Thanks [@bluwy](https://github.com/bluwy)! - Cleanup dependencies

- [#5829](https://github.com/withastro/astro/pull/5829) [`23dc9ea96`](https://github.com/withastro/astro/commit/23dc9ea96a10343852d965efd41fe6665294f1fb) Thanks [@giuseppelt](https://github.com/giuseppelt)! - Fix `Code.astro` shiki css class replace logic

- [#5836](https://github.com/withastro/astro/pull/5836) [`63a6ceb38`](https://github.com/withastro/astro/commit/63a6ceb38d88331451dca64d0034c7c58e3d26f1) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix route matching when path includes special characters

- Updated dependencies [[`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`12f65a4d5`](https://github.com/withastro/astro/commit/12f65a4d55e3fd2993c2f67b18794dd536280c69), [`16107b6a1`](https://github.com/withastro/astro/commit/16107b6a10514ef1b563e585ec9add4b14f42b94), [`c55fbcb8e`](https://github.com/withastro/astro/commit/c55fbcb8edca1fe118a44f68c9f9436a4719d171), [`1f92d64ea`](https://github.com/withastro/astro/commit/1f92d64ea35c03fec43aff64eaf704dc5a9eb30a), [`52209ca2a`](https://github.com/withastro/astro/commit/52209ca2ad72a30854947dcb3a90ab4db0ac0a6f), [`7572f7402`](https://github.com/withastro/astro/commit/7572f7402238da37de748be58d678fedaf863b53)]:
  - @astrojs/telemetry@2.0.0-beta.0
  - @astrojs/markdown-remark@2.0.0-beta.2
  - @astrojs/webapi@2.0.0-beta.0

</details>

## 2.0.0-beta.1

<details>
<summary>See changes in 2.0.0-beta.1</summary>

### Major Changes

- [#5778](https://github.com/withastro/astro/pull/5778) [`49ab4f231`](https://github.com/withastro/astro/commit/49ab4f231c23b34891c3ee86f4b92bf8d6d267a3) Thanks [@bluwy](https://github.com/bluwy)! - Remove proload to load the Astro config. It will now use NodeJS and Vite to load the config only.

- [#5771](https://github.com/withastro/astro/pull/5771) [`259a539d7`](https://github.com/withastro/astro/commit/259a539d7d70c783330c797794b15716921629cf) Thanks [@matthewp](https://github.com/matthewp)! - Removes support for astroFlavoredMarkdown

  In 1.0 Astro moved the old Astro Flavored Markdown (also sometimes called Components in Markdown) to a legacy feature. This change removes the `legacy.astroFlavoredMarkdown` option completely.

  In 2.0 this feature will not be available in Astro at all. We recommend migration to MDX for those were still using this feature in 1.x.

- [#5717](https://github.com/withastro/astro/pull/5717) [`a3a7fc929`](https://github.com/withastro/astro/commit/a3a7fc9298e6d88abb4b7bee1e58f05fa9558cf1) Thanks [@bluwy](https://github.com/bluwy)! - Remove `style.postcss` Astro config. Refactor tailwind integration to configure through `vite` instead. Also disables `autoprefixer` in dev.

### Minor Changes

- [#5769](https://github.com/withastro/astro/pull/5769) [`93e633922`](https://github.com/withastro/astro/commit/93e633922c2e449df3bb2357b3683af1d3c0e07b) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Introduce a `smartypants` flag to opt-out of Astro's default SmartyPants plugin.

  ```js
  {
    markdown: {
      smartypants: false,
    }
  }
  ```

  #### Migration

  You may have disabled Astro's built-in plugins (GitHub-Flavored Markdown and Smartypants) with the `extendDefaultPlugins` option. This has now been split into 2 flags to disable each plugin individually:

  - `markdown.gfm` to disable GitHub-Flavored Markdown
  - `markdown.smartypants` to disable SmartyPants

  ```diff
  // astro.config.mjs
  import { defineConfig } from 'astro/config';

  export default defineConfig({
    markdown: {
  -   extendDefaultPlugins: false,
  +   smartypants: false,
  +   gfm: false,
    }
  });
  ```

### Patch Changes

- [#5734](https://github.com/withastro/astro/pull/5734) [`55cea0a9d`](https://github.com/withastro/astro/commit/55cea0a9d8c8df91a46590fc04a9ac28089b3432) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix `prerender` when used with `getStaticPaths`

- [#5756](https://github.com/withastro/astro/pull/5756) [`116d8835c`](https://github.com/withastro/astro/commit/116d8835ca9e78f8b5e477ee5a3d737b69f80706) Thanks [@matthewp](https://github.com/matthewp)! - Fix for hoisted scripts in project with spaces in the file path

- [#5743](https://github.com/withastro/astro/pull/5743) [`2a5786419`](https://github.com/withastro/astro/commit/2a5786419599b8674473c699300172b9aacbae2e) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add error location during build for user-generated errors

- [#5761](https://github.com/withastro/astro/pull/5761) [`fa8c131f8`](https://github.com/withastro/astro/commit/fa8c131f88ef67d14c62f1c00c97ed74d43a80ac) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add helpful error message when the MDX integration is missing.

- Updated dependencies [[`93e633922`](https://github.com/withastro/astro/commit/93e633922c2e449df3bb2357b3683af1d3c0e07b)]:
  - @astrojs/markdown-remark@2.0.0-beta.1

</details>

## 2.0.0-beta.0

<details>
<summary>See changes in 2.0.0-beta.0</summary>

### Major Changes

- [#5687](https://github.com/withastro/astro/pull/5687) [`e2019be6f`](https://github.com/withastro/astro/commit/e2019be6ffa46fa33d92cfd346f9ecbe51bb7144) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Give remark and rehype plugins access to user frontmatter via frontmatter injection. This means `data.astro.frontmatter` is now the _complete_ Markdown or MDX document's frontmatter, rather than an empty object.

  This allows plugin authors to modify existing frontmatter, or compute new properties based on other properties. For example, say you want to compute a full image URL based on an `imageSrc` slug in your document frontmatter:

  ```ts
  export function remarkInjectSocialImagePlugin() {
    return function (tree, file) {
      const { frontmatter } = file.data.astro;
      frontmatter.socialImageSrc = new URL(frontmatter.imageSrc, 'https://my-blog.com/').pathname;
    };
  }
  ```

  #### Content Collections - new `remarkPluginFrontmatter` property

  We have changed _inject_ frontmatter to _modify_ frontmatter in our docs to improve discoverability. This is based on support forum feedback, where "injection" is rarely the term used.

  To reflect this, the `injectedFrontmatter` property has been renamed to `remarkPluginFrontmatter`. This should clarify this plugin is still separate from the `data` export Content Collections expose today.

  #### Migration instructions

  Plugin authors should now **check for user frontmatter when applying defaults.**

  For example, say a remark plugin wants to apply a default `title` if none is present. Add a conditional to check if the property is present, and update if none exists:

  ```diff
  export function remarkInjectTitlePlugin() {
    return function (tree, file) {
      const { frontmatter } = file.data.astro;
  +    if (!frontmatter.title) {
        frontmatter.title = 'Default title';
  +    }
    }
  }
  ```

  This differs from previous behavior, where a Markdown file's frontmatter would _always_ override frontmatter injected via remark or reype.

- [#5728](https://github.com/withastro/astro/pull/5728) [`8fb28648f`](https://github.com/withastro/astro/commit/8fb28648f66629741cb976bfe34ccd9d8f55661e) Thanks [@natemoo-re](https://github.com/natemoo-re)! - The previously experimental features `--experimental-error-overlay` and `--experimental-prerender`, both added in v1.7.0, are now the default.

  You'll notice that the error overlay during `astro dev` has a refreshed visual design and provides more context for your errors.

  The `prerender` feature is now enabled by default when using `output: 'server'`. To prerender a particular page, add `export const prerender = true` to your frontmatter.

  > **Warning**
  > Integration authors that previously relied on the exact structure of Astro's v1.0 build output may notice some changes to our output file structure. Please test your integrations to ensure compatability.
  > Users that have configured a custom `vite.build.rollupOptions.output.chunkFileNames` should ensure that their Astro project is configured as an ESM Node project. Either include `"type": "module"` in your root `package.json` file or use the `.mjs` extension for `chunkFileNames`.

- [#5716](https://github.com/withastro/astro/pull/5716) [`dd56c1941`](https://github.com/withastro/astro/commit/dd56c19411b126439b8bc42d681b6fa8c06e8c61) Thanks [@bluwy](https://github.com/bluwy)! - Remove MDX Fragment hack. This was used by `@astrojs/mdx` to access the `Fragment` component, but isn't require anymore since `@astrojs/mdx` v0.12.1.

- [#5685](https://github.com/withastro/astro/pull/5685) [`f6cf92b48`](https://github.com/withastro/astro/commit/f6cf92b48317a19a3840ad781b77d6d3cae143bb) Thanks [@bluwy](https://github.com/bluwy)! - Upgrade to Vite 4. Please see its [migration guide](https://vitejs.dev/guide/migration.html) for more information.

- [#5724](https://github.com/withastro/astro/pull/5724) [`16c7d0bfd`](https://github.com/withastro/astro/commit/16c7d0bfd49d2b9bfae45385f506bcd642f9444a) Thanks [@bluwy](https://github.com/bluwy)! - Remove outdated Vue info log. Remove `toString` support for `RenderTemplateResult`.

- [#5684](https://github.com/withastro/astro/pull/5684) [`a9c292026`](https://github.com/withastro/astro/commit/a9c2920264e36cc5dc05f4adc1912187979edb0d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Refine Markdown and MDX configuration options for ease-of-use.

  #### Markdown

  - **Remove `remark-smartypants`** from Astro's default Markdown plugins.
  - **Replace the `extendDefaultPlugins` option** with a simplified `gfm` boolean. This is enabled by default, and can be disabled to remove GitHub-Flavored Markdown.
  - Ensure GitHub-Flavored Markdown is applied whether or not custom `remarkPlugins` or `rehypePlugins` are configured. If you want to apply custom plugins _and_ remove GFM, manually set `gfm: false` in your config.

  #### MDX

  - Support _all_ Markdown configuration options (except `drafts`) from your MDX integration config. This includes `syntaxHighlighting` and `shikiConfig` options to further customize the MDX renderer.
  - Simplify `extendDefaults` to an `extendMarkdownConfig` option. MDX options will default to their equivalent in your Markdown config. By setting `extendMarkdownConfig` to false, you can "eject" to set your own syntax highlighting, plugins, and more.

  #### Migration

  To preserve your existing Markdown and MDX setup, you may need some configuration changes:

  ##### Smartypants manual installation

  [Smartypants](https://github.com/silvenon/remark-smartypants) has been removed from Astro's default setup. If you rely on this plugin, [install `remark-smartypants`](https://github.com/silvenon/remark-smartypants#installing) and apply to your `astro.config.*`:

  ```diff
  // astro.config.mjs
  import { defineConfig } from 'astro/config';
  + import smartypants from 'remark-smartypants';

  export default defineConfig({
    markdown: {
  +   remarkPlugins: [smartypants],
    }
  });
  ```

  ##### Migrate `extendDefaultPlugins` to `gfm`

  You may have disabled Astro's built-in plugins (GitHub-Flavored Markdown and Smartypants) with the `extendDefaultPlugins` option. Since Smartypants has been removed, this has been renamed to `gfm`.

  ```diff
  // astro.config.mjs
  import { defineConfig } from 'astro/config';

  export default defineConfig({
    markdown: {
  -   extendDefaultPlugins: false,
  +   gfm: false,
    }
  });
  ```

  Additionally, applying remark and rehype plugins **no longer disables** `gfm`. You will need to opt-out manually by setting `gfm` to `false`.

  ##### Migrate MDX's `extendPlugins` to `extendMarkdownConfig`

  You may have used the `extendPlugins` option to manage plugin defaults in MDX. This has been replaced by 2 flags:

  - `extendMarkdownConfig` (`true` by default) to toggle Markdown config inheritance. This replaces the `extendPlugins: 'markdown'` option.
  - `gfm` (`true` by default) to toggle GitHub-Flavored Markdown in MDX. This replaces the `extendPlugins: 'defaults'` option.

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove deprecated `Astro` global APIs, including `Astro.resolve`, `Astro.fetchContent`, and `Astro.canonicalURL`.

  #### `Astro.resolve`

  You can resolve asset paths using `import` instead. For example:

  ```astro
  ---
  import 'style.css';
  import imageUrl from './image.png';
  ---

  <img src={imageUrl} />
  ```

  See the [v0.25 migration guide](https://docs.astro.build/en/migrate/#deprecated-astroresolve) for more information.

  #### `Astro.fetchContent`

  Use `Astro.glob` instead to fetch markdown files, or migrate to the [Content Collections](https://docs.astro.build/en/guides/content-collections/) feature.

  ```js
  let allPosts = await Astro.glob('./posts/*.md');
  ```

  #### `Astro.canonicalURL`

  Use `Astro.url` instead to construct the canonical URL.

  ```js
  const canonicalURL = new URL(Astro.url.pathname, Astro.site);
  ```

- [#5707](https://github.com/withastro/astro/pull/5707) [`5eba34fcc`](https://github.com/withastro/astro/commit/5eba34fcc663def20bdf6e0daad02a6a5472776b) Thanks [@bluwy](https://github.com/bluwy)! - Remove `buildConfig` option parameter from integration `astro:build:start` hook in favour of the `build.config` option in the `astro:config:setup` hook.

  ```js
  export default function myIntegration() {
    return {
      name: 'my-integration',
      hooks: {
        'astro:config:setup': ({ updateConfig }) => {
          updateConfig({
            build: {
              client: '...',
              server: '...',
              serverEntry: '...',
            },
          });
        },
      },
    };
  }
  ```

### Patch Changes

- Updated dependencies [[`e2019be6f`](https://github.com/withastro/astro/commit/e2019be6ffa46fa33d92cfd346f9ecbe51bb7144), [`a9c292026`](https://github.com/withastro/astro/commit/a9c2920264e36cc5dc05f4adc1912187979edb0d)]:
  - @astrojs/markdown-remark@2.0.0-beta.0

</details>

## 1.9.2

### Patch Changes

- [#5776](https://github.com/withastro/astro/pull/5776) [`6a31433ed`](https://github.com/withastro/astro/commit/6a31433ed79c7f84fd3ce602005b42ad95007d84) Thanks [@ba55ie](https://github.com/ba55ie)! - Fix Lit slotted content

## 1.9.1

### Patch Changes

- [`adad7e966`](https://github.com/withastro/astro/commit/adad7e96680640e1d0a5ec270cd2516f350c7652) Thanks [@matthewp](https://github.com/matthewp)! - Fix for hoisted scripts in project with spaces in the file path

## 1.9.0

### Minor Changes

- [#5666](https://github.com/withastro/astro/pull/5666) [`bf210f784`](https://github.com/withastro/astro/commit/bf210f7841711439f7db6c2b1f369e54a70b03d3) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Correctly handle spaces and capitalization in `src/content/` file names. This introduces github-slugger for slug generation to ensure slugs are usable by `getStaticPaths`. Changes:
  - Resolve spaces and capitalization: `collection/Entry With Spaces.md` becomes `collection/entry-with-spaces`.
  - Truncate `/index` paths to base URL: `collection/index.md` becomes `collection`

### Patch Changes

- [#5720](https://github.com/withastro/astro/pull/5720) [`fe316be86`](https://github.com/withastro/astro/commit/fe316be86f4dfecff78effbecdc10f7348406d27) Thanks [@umarov](https://github.com/umarov)! - Do not add base path to a hoisted script body

- [#5706](https://github.com/withastro/astro/pull/5706) [`c2844a79c`](https://github.com/withastro/astro/commit/c2844a79c8c94466481f5f3a37af259bb4cbf276) Thanks [@bluwy](https://github.com/bluwy)! - Add preact and sitemap integration to config load external list

- [#5700](https://github.com/withastro/astro/pull/5700) [`3aa3e00a6`](https://github.com/withastro/astro/commit/3aa3e00a63b63ae443f824f11cffde2a194ea4bf) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix `import.meta.env.DEV` always being set to `true` when using Content Collections

## 1.8.0

### Minor Changes

- [#5647](https://github.com/withastro/astro/pull/5647) [`d72da5290`](https://github.com/withastro/astro/commit/d72da529075ccbcfd342bf2308df0e5ce59b1e3f) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add `astro sync` CLI command for type generation

### Patch Changes

- [#5668](https://github.com/withastro/astro/pull/5668) [`9674cf56c`](https://github.com/withastro/astro/commit/9674cf56c561af8f13def0266b0539507a80000d) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Remove stray `console.log` from content collections error message

- [#5652](https://github.com/withastro/astro/pull/5652) [`0b5098758`](https://github.com/withastro/astro/commit/0b50987584120e0c0e549f9ff838dc8879dbfa30) Thanks [@bluwy](https://github.com/bluwy)! - Use acorn to postprocess Astro globs

- [#5648](https://github.com/withastro/astro/pull/5648) [`853081d1c`](https://github.com/withastro/astro/commit/853081d1c857d8ad8a9634c37ed8fd123d32d241) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Prevent relative image paths in `src/content/`

- [#5678](https://github.com/withastro/astro/pull/5678) [`f8f576829`](https://github.com/withastro/astro/commit/f8f57682948a76cad81eef579235ee059578fe91) Thanks [@bluwy](https://github.com/bluwy)! - Fix code generation quotes handling

- [#5635](https://github.com/withastro/astro/pull/5635) [`376f67011`](https://github.com/withastro/astro/commit/376f67011d220de3bf05d3f39779a708992fffd7) Thanks [@SegaraRai](https://github.com/SegaraRai)! - Add `server.headers` typing

- Updated dependencies [[`853081d1c`](https://github.com/withastro/astro/commit/853081d1c857d8ad8a9634c37ed8fd123d32d241), [`2c65b433b`](https://github.com/withastro/astro/commit/2c65b433bf840a1bb93b0a1947df5949e33512ff)]:
  - @astrojs/markdown-remark@1.2.0

## 1.7.2

### Patch Changes

- [#5641](https://github.com/withastro/astro/pull/5641) [`62580ed07`](https://github.com/withastro/astro/commit/62580ed07871606c88051b6a2007b865c636107e) Thanks [@chenxsan](https://github.com/chenxsan)! - Fix "Maximum call stack size exceeded" error in vite-plugin-head-propagation

- [#5644](https://github.com/withastro/astro/pull/5644) [`d5aff85db`](https://github.com/withastro/astro/commit/d5aff85db48ccc9234968071b378829369afba9b) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix static build regression where chunks would not be generated

- [#5639](https://github.com/withastro/astro/pull/5639) [`1ac1ed86e`](https://github.com/withastro/astro/commit/1ac1ed86e9e5ec5468e8bdc40875e05811863138) Thanks [@bluwy](https://github.com/bluwy)! - Fix `client:only` imports with `"importsNotUsedAsValues": "error"` tsconfig

## 1.7.1

### Patch Changes

- [#5617](https://github.com/withastro/astro/pull/5617) [`33dcaa05b`](https://github.com/withastro/astro/commit/33dcaa05bb821ff0c6d0c6021b912855386be340) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix error message when using Content Collections and an out-of-date `@astrojs/mdx` integration

## 1.7.0

### Minor Changes

- [#5297](https://github.com/withastro/astro/pull/5297) [`d2960984c`](https://github.com/withastro/astro/commit/d2960984c59af7b60a3ea472c6c58fb00534a8e6) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Introduces the **experimental** Prerender API.

  > **Note**
  > This API is not yet stable and is subject to possible breaking changes!

  - Deploy an Astro server without sacrificing the speed or cacheability of static HTML.
  - The Prerender API allows you to statically prerender specific `pages/` at build time.

  **Usage**

  - First, run `astro build --experimental-prerender` or enable `experimental: { prerender: true }` in your `astro.config.mjs` file.
  - Then, include `export const prerender = true` in any file in the `pages/` directory that you wish to prerender.

- [#5495](https://github.com/withastro/astro/pull/5495) [`31ec84797`](https://github.com/withastro/astro/commit/31ec8479721a1cd65538ec041458c5ffe8f50ee9) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add a new error overlay designed by @doodlemarks! This new overlay should be much more informative, clearer, astro-y, and prettier than the previous one.

- [#5291](https://github.com/withastro/astro/pull/5291) [`5ec0f6ed5`](https://github.com/withastro/astro/commit/5ec0f6ed55b0a14a9663a90a03428345baf126bd) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Introduce Content Collections experimental API

  - Organize your Markdown and MDX content into easy-to-manage collections.
  - Add type safety to your frontmatter with schemas.
  - Generate landing pages, static routes, and SSR endpoints from your content using the collection query APIs.

- [#5564](https://github.com/withastro/astro/pull/5564) [`dced4a8a2`](https://github.com/withastro/astro/commit/dced4a8a2657887ec569860d9862d20f695dc23a) Thanks [@riywo](https://github.com/riywo)! - Add `server.headers` option

- [#5341](https://github.com/withastro/astro/pull/5341) [`6b156dd3b`](https://github.com/withastro/astro/commit/6b156dd3b467884839a571c53114aadf26fa4b0b) Thanks [@alexpdraper](https://github.com/alexpdraper)! - Allow setting domain when deleting cookies

### Patch Changes

- [#5615](https://github.com/withastro/astro/pull/5615) [`d85ec7484`](https://github.com/withastro/astro/commit/d85ec7484ce14a4c7d3f480da8f38fcb9aff388f) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Sanitize dynamically rendered tags to strip out any attributes

## 1.6.15

### Patch Changes

- [#5572](https://github.com/withastro/astro/pull/5572) [`b2f0210c4`](https://github.com/withastro/astro/commit/b2f0210c400a547d3067fdae6d15663b827be3a6) Thanks [@matthewp](https://github.com/matthewp)! - Include base in 'page' stage injected scripts

- [#5554](https://github.com/withastro/astro/pull/5554) [`02bb0a1cc`](https://github.com/withastro/astro/commit/02bb0a1ccd53e38157eec3a750160731fce64b9c) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Update `@astrojs/compiler` to latest

- [#5577](https://github.com/withastro/astro/pull/5577) [`2bd23e454`](https://github.com/withastro/astro/commit/2bd23e454fc9559aa00b9a493772acd69ba9ce6c) Thanks [@jerzakm](https://github.com/jerzakm)! - Updated magic-string to 0.27.0

## 1.6.14

### Patch Changes

- [#5545](https://github.com/withastro/astro/pull/5545) [`9082a850e`](https://github.com/withastro/astro/commit/9082a850eef4ab0187fc3bfdd5a377f0c7040070) Thanks [@bluwy](https://github.com/bluwy)! - Exclude astro from Vite optimization

- [#5446](https://github.com/withastro/astro/pull/5446) [`4f7f20616`](https://github.com/withastro/astro/commit/4f7f20616ed2b63f94ebf43bc5fdc1be55062a94) Thanks [@jyasskin](https://github.com/jyasskin)! - Fix redirect() typing to allow all redirection status codes.

- [#5511](https://github.com/withastro/astro/pull/5511) [`05915fec0`](https://github.com/withastro/astro/commit/05915fec01a51f27ab5051644f01e6112ecf06bc) Thanks [@matthewp](https://github.com/matthewp)! - Low-level head propagation

  This adds low-level head propagation ability within the Astro runtime. This is not really usable within an Astro app at the moment, but provides the APIs necessary for `renderEntry` to do head propagation.

- [#5553](https://github.com/withastro/astro/pull/5553) [`1aeabe417`](https://github.com/withastro/astro/commit/1aeabe417077505bc0cdb8d2e47366ddbc616072) Thanks [@matthewp](https://github.com/matthewp)! - Fix Astro.params not having values when using base in SSR

- [#5549](https://github.com/withastro/astro/pull/5549) [`795f00f73`](https://github.com/withastro/astro/commit/795f00f73c549727e05d5b7bf0e39cce87add4e7) Thanks [@matthewp](https://github.com/matthewp)! - Use accumulated sort order when order production CSS

- [#5539](https://github.com/withastro/astro/pull/5539) [`2c836b9d1`](https://github.com/withastro/astro/commit/2c836b9d1283a0707128d172e92ee2bba767486c) Thanks [@wulinsheng123](https://github.com/wulinsheng123)! - Error reporting fails on undefined error index

- [#5548](https://github.com/withastro/astro/pull/5548) [`8f3f67c96`](https://github.com/withastro/astro/commit/8f3f67c96aee63be64de77f374293761ff73f6ce) Thanks [@ido-pluto](https://github.com/ido-pluto)! - Removed premature optimization

## 1.6.13

### Patch Changes

- [#5506](https://github.com/withastro/astro/pull/5506) [`f536a34e5`](https://github.com/withastro/astro/commit/f536a34e53121104f87f2ad117a539daf2b7d5ee) Thanks [@bluwy](https://github.com/bluwy)! - Dedupe Astro package when resolving

- [#5506](https://github.com/withastro/astro/pull/5506) [`f536a34e5`](https://github.com/withastro/astro/commit/f536a34e53121104f87f2ad117a539daf2b7d5ee) Thanks [@bluwy](https://github.com/bluwy)! - Refactor Astro compile flow

- [#5533](https://github.com/withastro/astro/pull/5533) [`58188e053`](https://github.com/withastro/astro/commit/58188e053672562dfe4b7703c3e25bb47d71567d) Thanks [@bluwy](https://github.com/bluwy)! - Refactor and remove esbuild dependency

- [#5501](https://github.com/withastro/astro/pull/5501) [`3c44033e4`](https://github.com/withastro/astro/commit/3c44033e4ebafd28472d5c6a43e55c0363c6b555) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Added a warning in build when trying to hydrate an Astro component

## 1.6.12

### Patch Changes

- [#5484](https://github.com/withastro/astro/pull/5484) [`731e99df8`](https://github.com/withastro/astro/commit/731e99df875d40e40f6b33feddd940c3122a5f83) Thanks [@Pimm](https://github.com/Pimm)! - Narrow type of `Params`, as its values cannot be numbers

- [#5480](https://github.com/withastro/astro/pull/5480) [`c13775279`](https://github.com/withastro/astro/commit/c137752797a1af39b758d207af97bf234b3ff08d) Thanks [@sapphi-red](https://github.com/sapphi-red)! - Fix astro preview not working on Windows

- [#5497](https://github.com/withastro/astro/pull/5497) [`ca01a71eb`](https://github.com/withastro/astro/commit/ca01a71eb0937eae3ddc34d48396df8161e830db) Thanks [@bluwy](https://github.com/bluwy)! - Refactor internal plugins code

- [#5460](https://github.com/withastro/astro/pull/5460) [`57888e069`](https://github.com/withastro/astro/commit/57888e06904c48959940fffc5e63ac2e320fd336) Thanks [@bluwy](https://github.com/bluwy)! - Fix linked Astro library style HMR

- [#5477](https://github.com/withastro/astro/pull/5477) [`5e693c214`](https://github.com/withastro/astro/commit/5e693c21438d3a4840cd1906a346d38f05fdb753) Thanks [@bluwy](https://github.com/bluwy)! - Prevent inlining SCSS partials in dev

- [#5498](https://github.com/withastro/astro/pull/5498) [`1a3923da7`](https://github.com/withastro/astro/commit/1a3923da780288e6435fa79ee8fb61e420af344c) Thanks [@bluwy](https://github.com/bluwy)! - Optimize JSX import source detection

## 1.6.11

### Patch Changes

- [#5433](https://github.com/withastro/astro/pull/5433) [`936c1e411`](https://github.com/withastro/astro/commit/936c1e411d77c69b2b60a061c54704200716800a) Thanks [@wtchnm](https://github.com/wtchnm)! - Add missing `fetchpriority` attribute to img, link, script and iframe elements

- [#5437](https://github.com/withastro/astro/pull/5437) [`4b188132e`](https://github.com/withastro/astro/commit/4b188132ef68f8d9951cec86418ef50bb4df4a96) Thanks [@bluwy](https://github.com/bluwy)! - Correctly transform third-party JSX files

- [#5434](https://github.com/withastro/astro/pull/5434) [`f5ed630bc`](https://github.com/withastro/astro/commit/f5ed630bca05ebbfcc6ac994ced3911e41daedcc) Thanks [@matthewp](https://github.com/matthewp)! - Use Vite's resolve to resolve paths for client:only

## 1.6.10

### Patch Changes

- [#5431](https://github.com/withastro/astro/pull/5431) [`1ab505855`](https://github.com/withastro/astro/commit/1ab505855f9942659e3d23cb1ac668f04b98889d) Thanks [@matthewp](https://github.com/matthewp)! - Fix regression with loading .ts in .mjs config

- [#5426](https://github.com/withastro/astro/pull/5426) [`ff35b4759`](https://github.com/withastro/astro/commit/ff35b4759bd0fecfee6c99bf510c2e32d2574992) Thanks [@bluwy](https://github.com/bluwy)! - Fix JSX tagging for anonymous higher-order components default export

- [#5430](https://github.com/withastro/astro/pull/5430) [`b22ba1c03`](https://github.com/withastro/astro/commit/b22ba1c03a3e384dad569feb38fa34ecf7ec3b93) Thanks [@bluwy](https://github.com/bluwy)! - Fix preview --host in Node.js 18

- [#5417](https://github.com/withastro/astro/pull/5417) [`a9f7ff966`](https://github.com/withastro/astro/commit/a9f7ff96676a40b78e22379edc8eb9ce60a29fb8) Thanks [@matthewp](https://github.com/matthewp)! - Prevent dev from crashing when there are errors in template

## 1.6.9

### Patch Changes

- [#5409](https://github.com/withastro/astro/pull/5409) [`9f80a4046`](https://github.com/withastro/astro/commit/9f80a4046ff90e379be68bf03c3c4dd4dd5d6d87) Thanks [@matthewp](https://github.com/matthewp)! - Fix Code component usage in Vercel

- [#5410](https://github.com/withastro/astro/pull/5410) [`3c5cb6948`](https://github.com/withastro/astro/commit/3c5cb69488c76bbf0e9774fff5d948d29990515c) Thanks [@impcyber](https://github.com/impcyber)! - Fix: https://github.com/withastro/astro/issues/5400

- [#5412](https://github.com/withastro/astro/pull/5412) [`a278c7ae6`](https://github.com/withastro/astro/commit/a278c7ae6f2e93cabfe56fc16eb8b82b904ffb3a) Thanks [@matthewp](https://github.com/matthewp)! - Restart dev server on package.json changes

- [#5377](https://github.com/withastro/astro/pull/5377) [`40226dd14`](https://github.com/withastro/astro/commit/40226dd14d9f2d00d943f508dcfc76654c352938) Thanks [@matthewp](https://github.com/matthewp)! - Uses vite to load astro.config.ts files

## 1.6.8

### Patch Changes

- [#5375](https://github.com/withastro/astro/pull/5375) [`f9104354b`](https://github.com/withastro/astro/commit/f9104354b8a2c2457b9cd64405ddf8a832628e26) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix regression causing nested arrays in `getStaticPaths`'s return value to throw an error

- [#5346](https://github.com/withastro/astro/pull/5346) [`f3181b5ad`](https://github.com/withastro/astro/commit/f3181b5adf2c7c9157a59f409962274cda3f77ab) Thanks [@bluwy](https://github.com/bluwy)! - Fix .html.astro file routing in dev

- [#5358](https://github.com/withastro/astro/pull/5358) [`9eee0f016`](https://github.com/withastro/astro/commit/9eee0f0166e678dbcc2f6e4ce18bfa6326c95d7e) Thanks [@matthewp](https://github.com/matthewp)! - Properly support trailingSlash: never with a base

- [#5345](https://github.com/withastro/astro/pull/5345) [`3ae2a961b`](https://github.com/withastro/astro/commit/3ae2a961b77da179d24c44734af54424e76a5049) Thanks [@bluwy](https://github.com/bluwy)! - Respect Vite user config for third-party packages config handling

- [#5371](https://github.com/withastro/astro/pull/5371) [`bee8c14af`](https://github.com/withastro/astro/commit/bee8c14afd475ad053b9fdf78a2d29bebdd86926) Thanks [@matthewp](https://github.com/matthewp)! - Prefer the `base` config rather than site config for creating URLs for links and scripts.

- [#5369](https://github.com/withastro/astro/pull/5369) [`e385076ef`](https://github.com/withastro/astro/commit/e385076efe297f457343275e2e7002f71b35792b) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Upgrade `@astrojs/compiler`, fixes regression with `body` handling when `head` contains a Component node

## 1.6.7

### Patch Changes

- [#5353](https://github.com/withastro/astro/pull/5353) [`b3d936ac2`](https://github.com/withastro/astro/commit/b3d936ac248c0b939ff830023d75694398094341) Thanks [@matthewp](https://github.com/matthewp)! - Updated the CSS naming algorithm to prevent clashes

- [#5294](https://github.com/withastro/astro/pull/5294) [`ae41f25e1`](https://github.com/withastro/astro/commit/ae41f25e10a3fb1e5ad72c979ebe27fe55071de3) Thanks [@mrienstra](https://github.com/mrienstra)! - Consistent Markdown frontmatter typing (`MarkdownAstroData["frontmatter"]` in particular was `object` before)

## 1.6.6

### Patch Changes

- [#5316](https://github.com/withastro/astro/pull/5316) [`a780f2595`](https://github.com/withastro/astro/commit/a780f2595db86a773be0be1fefcbd9cbab2e8fc2) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Improved error messages descriptions and hints to be more informative

- [#5331](https://github.com/withastro/astro/pull/5331) [`688f8e4bc`](https://github.com/withastro/astro/commit/688f8e4bc1d8a284ee3d29f6122dbdebc02310ff) Thanks [@matthewp](https://github.com/matthewp)! - Allow dynamic segments in injected routes

- [#5330](https://github.com/withastro/astro/pull/5330) [`7e19e8b30`](https://github.com/withastro/astro/commit/7e19e8b30d0b411d69eb7d9c1de9dc304f084b37) Thanks [@matthewp](https://github.com/matthewp)! - Prevent jsx throws from hanging server

- [#5328](https://github.com/withastro/astro/pull/5328) [`bcd0f8f8c`](https://github.com/withastro/astro/commit/bcd0f8f8c4c27d19296ec08d7bf7d8f5047d583e) Thanks [@matthewp](https://github.com/matthewp)! - 404 when not using subpath for items in public in dev

  Previously if using a base like `base: '/subpath/` you could load things from the root, which would break in prod. Now you must include the subpath.

- [#5339](https://github.com/withastro/astro/pull/5339) [`03a8f89d5`](https://github.com/withastro/astro/commit/03a8f89d5ff79f43f4025fda0c93fd3c85482412) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Upgrade `@astrojs/compiler` to latest

- [#5327](https://github.com/withastro/astro/pull/5327) [`0dcdc6fb1`](https://github.com/withastro/astro/commit/0dcdc6fb1e6160c8a225a65c4810f565e2b673b5) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Update Astro language-server to 0.28.3

## 1.6.5

### Patch Changes

- [#5326](https://github.com/withastro/astro/pull/5326) [`88c1bbe3a`](https://github.com/withastro/astro/commit/88c1bbe3a71f85e92f42f13d0f310c6b2a264ade) Thanks [@matthewp](https://github.com/matthewp)! - Fix omitted island hydration scripts in slots

- [#5301](https://github.com/withastro/astro/pull/5301) [`a79a37cad`](https://github.com/withastro/astro/commit/a79a37cad549b21f91599ff86899e456d9dcc7df) Thanks [@bluwy](https://github.com/bluwy)! - Improve environment variable handling performance

## 1.6.4

### Patch Changes

- [#5290](https://github.com/withastro/astro/pull/5290) [`b2b291d29`](https://github.com/withastro/astro/commit/b2b291d29143703cece0d12c8e74b2e1151d2061) Thanks [@matthewp](https://github.com/matthewp)! - Handle base configuration in adapters

  This allows adapters to correctly handle `base` configuration. Internally Astro now matches routes when the URL includes the `base`.

  Adapters now also have access to the `removeBase` method which will remove the `base` from a pathname. This is useful to look up files for static assets.

- [#5292](https://github.com/withastro/astro/pull/5292) [`97e2b6ad7`](https://github.com/withastro/astro/commit/97e2b6ad7a6fa23e82be28b2f57cdf3f85fab112) Thanks [@MontelAle](https://github.com/MontelAle)! - Changes slow astro cli imports to dynamic

- [#5293](https://github.com/withastro/astro/pull/5293) [`4af4d8fa0`](https://github.com/withastro/astro/commit/4af4d8fa0035130fbf31c82d72777c3679bc1ca5) Thanks [@matthewp](https://github.com/matthewp)! - Prevent overcaching .astro HMR changes

- [#5314](https://github.com/withastro/astro/pull/5314) [`f6add3924`](https://github.com/withastro/astro/commit/f6add3924d5cd59925a6ea4bf7f2f731709bc893) Thanks [@matthewp](https://github.com/matthewp)! - Fixes regression with config file restarts

- [#5298](https://github.com/withastro/astro/pull/5298) [`247eb7411`](https://github.com/withastro/astro/commit/247eb7411f429317e5cd7d401a6660ee73641313) Thanks [@wulinsheng123](https://github.com/wulinsheng123)! - have not founded style when srcDir was root

## 1.6.3

### Patch Changes

- [#5273](https://github.com/withastro/astro/pull/5273) [`c7b9b14a1`](https://github.com/withastro/astro/commit/c7b9b14a1e8be22c21bd8b2982a340f101993924) Thanks [@matthewp](https://github.com/matthewp)! - Surface astro.config errors to the user

- [#5264](https://github.com/withastro/astro/pull/5264) [`0d27c4a2b`](https://github.com/withastro/astro/commit/0d27c4a2b67e3928cc6f7b5af5faad20926b6cbb) Thanks [@VladCuciureanu](https://github.com/VladCuciureanu)! - Fixed memleak caused by project dir names containing '.md' or '.mdx'

- [#5258](https://github.com/withastro/astro/pull/5258) [`74759cf78`](https://github.com/withastro/astro/commit/74759cf787aefeeccc3fc336fdb0a56b982733bb) Thanks [@bluwy](https://github.com/bluwy)! - Allow 200 response for endpoints in build

- [#5284](https://github.com/withastro/astro/pull/5284) [`126cd8e83`](https://github.com/withastro/astro/commit/126cd8e83fbed8d69320c55cad4bdaa2d6209de9) Thanks [@herteleo](https://github.com/herteleo)! - Include missing `class:list` within `HTMLAttributes` type

- [#5236](https://github.com/withastro/astro/pull/5236) [`1cc067052`](https://github.com/withastro/astro/commit/1cc067052438602d9378bf84dc7754c09afdfbe8) Thanks [@bluwy](https://github.com/bluwy)! - Refactor CSS preprocessing handling

- [#5198](https://github.com/withastro/astro/pull/5198) [`c77a6cbe3`](https://github.com/withastro/astro/commit/c77a6cbe345facbf72c453e2fddc00f20c98983f) Thanks [@matthewp](https://github.com/matthewp)! - HMR - Improved error recovery

  This improves error recovery for HMR. Now when the dev server finds itself in an error state (because a route contained an error), it will recover from that state and refresh the page when the user has corrected the mistake.

## 1.6.2

### Patch Changes

- [#5243](https://github.com/withastro/astro/pull/5243) [`7d678c9ed`](https://github.com/withastro/astro/commit/7d678c9ed05a33380a2153df54abdf87d374f970) Thanks [@matthewp](https://github.com/matthewp)! - Upgrade `@astrojs/compiler` to 0.29.x

- Updated dependencies [[`b6a478f37`](https://github.com/withastro/astro/commit/b6a478f37648491321077750bfca7bddf3cafadd)]:
  - @astrojs/webapi@1.1.1

## 1.6.1

### Patch Changes

- [#5233](https://github.com/withastro/astro/pull/5233) [`7f8987085`](https://github.com/withastro/astro/commit/7f8987085c9c5bdcd39b9a6700303e9b9f76b9f2) Thanks [@bluwy](https://github.com/bluwy)! - Support rendering `@motionone/solid` components

- [#5238](https://github.com/withastro/astro/pull/5238) [`26ff42905`](https://github.com/withastro/astro/commit/26ff429058c6244767276b9fa20ef58987be13ee) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Fix not included file extension in `url` metadata for newly added markdown files

- [#5217](https://github.com/withastro/astro/pull/5217) [`8c83359e3`](https://github.com/withastro/astro/commit/8c83359e385b47fb6e453c023aeac2e01a579f38) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix missing types.d.ts in npm package

- [#5212](https://github.com/withastro/astro/pull/5212) [`a609a8937`](https://github.com/withastro/astro/commit/a609a8937f9f35c46f3c934d38b83c445da425b9) Thanks [@bluwy](https://github.com/bluwy)! - Upgrade Vite to 3.2

- [#5206](https://github.com/withastro/astro/pull/5206) [`d64d5b9b5`](https://github.com/withastro/astro/commit/d64d5b9b52c66ac0b3435b85c92a877f374fb100) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Improve error messages related to CSS and compiler errors

- [#5212](https://github.com/withastro/astro/pull/5212) [`a609a8937`](https://github.com/withastro/astro/commit/a609a8937f9f35c46f3c934d38b83c445da425b9) Thanks [@bluwy](https://github.com/bluwy)! - Allow importing public files in SSR

## 1.6.0

### Minor Changes

- [#5147](https://github.com/withastro/astro/pull/5147) [`0bf0758fb`](https://github.com/withastro/astro/commit/0bf0758fb831a91f6628e10a5baabf02f30f1f41) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Add `astro/types` entrypoint. These utilities can be used for common prop type patterns.

  ## `HTMLAttributes`

  If you would like to extend valid HTML attributes for a given HTML element, you may use the provided `HTMLAttributes` type—it accepts an element name and returns the valid HTML attributes for that element name.

  ```ts
  import { HTMLAttributes } from 'astro/types';
  interface Props extends HTMLAttributes<'a'> {
    myProp?: string;
  }
  ```

- [#5164](https://github.com/withastro/astro/pull/5164) [`4a8a346ca`](https://github.com/withastro/astro/commit/4a8a346ca9a6d6ed8def2fa32329c1db922893d2) Thanks [@MoustaphaDev](https://github.com/MoustaphaDev)! - Add support for markdown files with the following extensions:

  - `.markdown`
  - `.mdown`
  - `.mkdn`
  - `.mkd`
  - `.mdwn`

- [#4917](https://github.com/withastro/astro/pull/4917) [`ddf2f8390`](https://github.com/withastro/astro/commit/ddf2f8390e8dcc64b44636524bdcddae977779f4) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Add support for `--base` CLI argument, which will override the [`base`](https://docs.astro.build/en/reference/configuration-reference/#base) set in your `astro.config.mjs` file.

  ```
  astro --site https://astro.build --base /docs
  ```

### Patch Changes

- [#5203](https://github.com/withastro/astro/pull/5203) [`3d99fdd1e`](https://github.com/withastro/astro/commit/3d99fdd1e7ea563775d86d1b00196c4c0c024500) Thanks [@bluwy](https://github.com/bluwy)! - Improve Astro libraries config handling

## 1.5.3

### Patch Changes

- [#5133](https://github.com/withastro/astro/pull/5133) [`1c477dd8d`](https://github.com/withastro/astro/commit/1c477dd8d9026fcbd533b4e6d11908e167ce7247) Thanks [@bluwy](https://github.com/bluwy)! - Fix `.css?raw` usage

- [#5133](https://github.com/withastro/astro/pull/5133) [`1c477dd8d`](https://github.com/withastro/astro/commit/1c477dd8d9026fcbd533b4e6d11908e167ce7247) Thanks [@bluwy](https://github.com/bluwy)! - Update `@astrojs/compiler` and use the new `resolvePath` option. This allows removing much of the runtime code, which should improve rendering performance for Astro and MDX pages.

- [#5192](https://github.com/withastro/astro/pull/5192) [`8728ee0b9`](https://github.com/withastro/astro/commit/8728ee0b94ef28524900367a06b9fe806babd574) Thanks [@tony-sull](https://github.com/tony-sull)! - `astro add` no longer automatically installs optional peer dependencies

## 1.5.2

### Patch Changes

- [#5119](https://github.com/withastro/astro/pull/5119) [`430e0346c`](https://github.com/withastro/astro/commit/430e0346c9dc0def8af93e0a393dc2847e145d2f) Thanks [@bluwy](https://github.com/bluwy)! - Use `fs.promises.rm` to remove node deprecation warning

- [#5123](https://github.com/withastro/astro/pull/5123) [`9745009ae`](https://github.com/withastro/astro/commit/9745009ae0e7fe8691c75657c5c9586a548bf2e0) Thanks [@matthewp](https://github.com/matthewp)! - Fixes index page with build.format=file

- [#5116](https://github.com/withastro/astro/pull/5116) [`500acb3c1`](https://github.com/withastro/astro/commit/500acb3c117070ee5838a8b567e9bdcf68703227) Thanks [@matthewp](https://github.com/matthewp)! - Throws when using Response.redirect in SSG mode

## 1.5.1

### Patch Changes

- [#5110](https://github.com/withastro/astro/pull/5110) [`0edfdd325`](https://github.com/withastro/astro/commit/0edfdd325932b0b493b2228e3a121d217c38a727) Thanks [@bluwy](https://github.com/bluwy)! - Ensure CLI flags override function-style server config

- [#5106](https://github.com/withastro/astro/pull/5106) [`ef0c54316`](https://github.com/withastro/astro/commit/ef0c5431631665c9f6648ee5daee65a3ebf8e9ee) Thanks [@bluwy](https://github.com/bluwy)! - Support spread parameters for server endpoints

- [#5095](https://github.com/withastro/astro/pull/5095) [`ddfbef5ac`](https://github.com/withastro/astro/commit/ddfbef5acbd4c56d8ce1626a458b5cbb27da47fe) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix `astro add` trying to add lines from extended configurations when adding frameworks

- [#5076](https://github.com/withastro/astro/pull/5076) [`6f9a88b31`](https://github.com/withastro/astro/commit/6f9a88b31ba0881acd56fcb62c4a554c867b14d6) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix jsconfig.json aliases not working anymore after 1.5.0

- [#5080](https://github.com/withastro/astro/pull/5080) [`90b715d5c`](https://github.com/withastro/astro/commit/90b715d5c86810ad1edb013156e4810be3252e55) Thanks [@matthewp](https://github.com/matthewp)! - Fix Astro-in-MDX dashes in slot attr

- [#5098](https://github.com/withastro/astro/pull/5098) [`f684e9d36`](https://github.com/withastro/astro/commit/f684e9d361e3780889ea6e6b3394c0f583bd839a) Thanks [@jkjustjoshing](https://github.com/jkjustjoshing)! - Separate type definitions for built-in HTML elements and custom elements. Helpful when implementing an "as" prop similar to [styled-components](https://styled-components.com/docs/api#as-polymorphic-prop).

- [#5108](https://github.com/withastro/astro/pull/5108) [`ce01225a7`](https://github.com/withastro/astro/commit/ce01225a700aff5b437d46f21161e5f557050e12) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix types not working properly when using `moduleResolution: 'node16'`

- [#5060](https://github.com/withastro/astro/pull/5060) [`5923dd77c`](https://github.com/withastro/astro/commit/5923dd77c17c80747f9fe746ff8270ad4c820003) Thanks [@AirBorne04](https://github.com/AirBorne04)! - api routes: adding cookies to the response, also when returning a simple result

- [#5087](https://github.com/withastro/astro/pull/5087) [`49a8d18b4`](https://github.com/withastro/astro/commit/49a8d18b4993d899a05ee8230fdd012fb633533f) Thanks [@JuanM04](https://github.com/JuanM04)! - Fix `astro add` pnpm command

## 1.5.0

### Minor Changes

- [#5056](https://github.com/withastro/astro/pull/5056) [`e55af8a23`](https://github.com/withastro/astro/commit/e55af8a23233b6335f45b7a04b9d026990fb616c) Thanks [@matthewp](https://github.com/matthewp)! - # Adapter support for `astro preview`

  Adapters are now about to support the `astro preview` command via a new integration option. The Node.js adapter `@astrojs/node` is the first of the built-in adapters to gain support for this. What this means is that if you are using `@astrojs/node` you can new preview your SSR app by running:

  ```shell
  npm run preview
  ```

  ## Adapter API

  We will be updating the other first party Astro adapters to support preview over time. Adapters can opt-in to this feature by providing the `previewEntrypoint` via the `setAdapter` function in `astro:config:done` hook. The Node.js adapter's code looks like this:

  ```diff
  export default function() {
    return {
  		name: '@astrojs/node',
  		hooks: {
  			'astro:config:done': ({ setAdapter, config }) => {
          setAdapter({
            name: '@astrojs/node',
            serverEntrypoint: '@astrojs/node/server.js',
  +          previewEntrypoint: '@astrojs/node/preview.js',
            exports: ['handler'],
          });

          // more here
        }
      }
    };
  }
  ```

  The `previewEntrypoint` is a module in the adapter's package that is a Node.js script. This script is run when `astro preview` is run and is charged with starting up the built server. See the Node.js implementation in `@astrojs/node` to see how that is implemented.

- [#4986](https://github.com/withastro/astro/pull/4986) [`ebd364e39`](https://github.com/withastro/astro/commit/ebd364e392035b379dd00b8f2f15a4cc09ee88e6) Thanks [@bluwy](https://github.com/bluwy)! - ## New properties for API routes

  In API routes, you can now get the `site`, `generator`, `url`, `clientAddress`, `props`, and `redirect` fields on the APIContext, which is the first parameter passed to an API route. This was done to make the APIContext more closely align with the `Astro` global in .astro pages.

  For example, here's how you might use the `clientAddress`, which is the user's IP address, to selectively allow users.

  ```js
  export function post({ clientAddress, request, redirect }) {
    if (!allowList.has(clientAddress)) {
      return redirect('/not-allowed');
    }
  }
  ```

  Check out the docs for more information on the newly available fields: https://docs.astro.build/en/core-concepts/endpoints/#server-endpoints-api-routes

- [#4959](https://github.com/withastro/astro/pull/4959) [`0ea6187f9`](https://github.com/withastro/astro/commit/0ea6187f95f68d1a3ed98ef4d660e71206883bac) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Added support for updating TypeScript settings automatically when using `astro add`

  The `astro add` command will now automatically update your `tsconfig.json` with the proper TypeScript settings needed for the chosen frameworks.

  For instance, typing `astro add solid` will update your `tsconfig.json` with the following settings, per [Solid's TypeScript guide](https://www.solidjs.com/guides/typescript):

  ```json
  {
    "compilerOptions": {
      "jsx": "preserve",
      "jsxImportSource": "solid-js"
    }
  }
  ```

- [#4947](https://github.com/withastro/astro/pull/4947) [`a5e3ecc80`](https://github.com/withastro/astro/commit/a5e3ecc8039c1e115ce5597362e18cd35d04e40b) Thanks [@JuanM04](https://github.com/JuanM04)! - - Added `isRestart` and `addWatchFile` to integration step `isRestart`.

  - Restart dev server automatically when tsconfig changes.

- [#4986](https://github.com/withastro/astro/pull/4986) [`ebd364e39`](https://github.com/withastro/astro/commit/ebd364e392035b379dd00b8f2f15a4cc09ee88e6) Thanks [@bluwy](https://github.com/bluwy)! - ## Support passing a custom status code for Astro.redirect

  New in this minor is the ability to pass a status code to `Astro.redirect`. By default it uses `302` but now you can pass another code as the second argument:

  ```astro
  ---
  // This page was moved
  return Astro.redirect('/posts/new-post-name', 301);
  ---
  ```

- [#5056](https://github.com/withastro/astro/pull/5056) [`e55af8a23`](https://github.com/withastro/astro/commit/e55af8a23233b6335f45b7a04b9d026990fb616c) Thanks [@matthewp](https://github.com/matthewp)! - # New build configuration

  The ability to customize SSR build configuration more granularly is now available in Astro. You can now customize the output folder for `server` (the server code for SSR), `client` (your client-side JavaScript and assets), and `serverEntry` (the name of the entrypoint server module). Here are the defaults:

  ```js
  import { defineConfig } from 'astro/config';

  export default defineConfig({
    output: 'server',
    build: {
      server: './dist/server/',
      client: './dist/client/',
      serverEntry: 'entry.mjs',
    },
  });
  ```

  These new configuration options are only supported in SSR mode and are ignored when building to SSG (a static site).

  ## Integration hook change

  The integration hook `astro:build:start` includes a param `buildConfig` which includes all of these same options. You can continue to use this param in Astro 1.x, but it is deprecated in favor of the new `build.config` options. All of the built-in adapters have been updated to the new format. If you have an integration that depends on this param we suggest upgrading to do this instead:

  ```js
  export default function myIntegration() {
    return {
      name: 'my-integration',
      hooks: {
        'astro:config:setup': ({ updateConfig }) => {
          updateConfig({
            build: {
              server: '...',
            },
          });
        },
      },
    };
  }
  ```

### Patch Changes

- [#5057](https://github.com/withastro/astro/pull/5057) [`baf88ee9e`](https://github.com/withastro/astro/commit/baf88ee9e5e692a94981d7a696fbdcb4cd8ab2a6) Thanks [@bluwy](https://github.com/bluwy)! - Skip JSX tagging for export statements with source

- [#5044](https://github.com/withastro/astro/pull/5044) [`44ea0c6d9`](https://github.com/withastro/astro/commit/44ea0c6d941a26a3c38fc6dc045a8a25215d154a) Thanks [@JuanM04](https://github.com/JuanM04)! - Upgrade Astro compiler to 0.27.1

- [#5059](https://github.com/withastro/astro/pull/5059) [`f7fcdfe62`](https://github.com/withastro/astro/commit/f7fcdfe6210b3cf08cad92c49b64adf169b9e744) Thanks [@bluwy](https://github.com/bluwy)! - Support strict dependency install for libraries with JSX

- [#5047](https://github.com/withastro/astro/pull/5047) [`1e2799243`](https://github.com/withastro/astro/commit/1e27992437aa0371b8550acb3e3f79e62721a506) Thanks [@matthewp](https://github.com/matthewp)! - Update Astro.cookies.set types to allow booleans and numbers

  Note that booleans and numbers were already allowed, they just were not allowed by the type definitions.

## 1.4.7

### Patch Changes

- [#5035](https://github.com/withastro/astro/pull/5035) [`d7bfb144b`](https://github.com/withastro/astro/commit/d7bfb144ba1718d14664ec755adf6e2281a4ab71) Thanks [@AirBorne04](https://github.com/AirBorne04)! - preventing multiple doctype injection into html documents

- [#5015](https://github.com/withastro/astro/pull/5015) [`b1964e9e1`](https://github.com/withastro/astro/commit/b1964e9e1b7f9178036e266b89d3c8b9cbffd1c6) Thanks [@matthewp](https://github.com/matthewp)! - Shared state in Preact components with signals

  This makes it possible to share client state between Preact islands via signals.

  For example, you can create a signals in an Astro component and then pass it to multiple islands:

  ```astro
  ---
  // Component Imports
  import Counter from '../components/Counter';
  import { signal } from '@preact/signals';
  const count = signal(0);
  ---

  <Count count={count} />
  <Count count={count} />
  ```

- [#5036](https://github.com/withastro/astro/pull/5036) [`38fdb4ca6`](https://github.com/withastro/astro/commit/38fdb4ca6f7c6af2fff69fe5bd60bdf2c9d7a6f1) Thanks [@matthewp](https://github.com/matthewp)! - New algorithm for shorter CSS bundle names

## 1.4.6

### Patch Changes

- [#5013](https://github.com/withastro/astro/pull/5013) [`ffbe4e71e`](https://github.com/withastro/astro/commit/ffbe4e71e36f496f6b9f4315c3145d238e46eb7e) Thanks [@matthewp](https://github.com/matthewp)! - Fixes getViteConfig from astro/config

## 1.4.5

### Patch Changes

- [#4981](https://github.com/withastro/astro/pull/4981) [`1f890b336`](https://github.com/withastro/astro/commit/1f890b3363d8ce232571612056b485c13983e5ef) Thanks [@matthewp](https://github.com/matthewp)! - Ensure dynamic tags have their slot instructions yielded

- [#4886](https://github.com/withastro/astro/pull/4886) [`61d26f335`](https://github.com/withastro/astro/commit/61d26f3352bb701ccce04dece4e1879b007f0ccb) Thanks [@yuhang-dong](https://github.com/yuhang-dong)! - Fix: import.meta.env.BASE_URL will be '/' in client loaded component on dev mode

- [#4973](https://github.com/withastro/astro/pull/4973) [`c733d4fb8`](https://github.com/withastro/astro/commit/c733d4fb81ca15efa3316e2b27d8341ddfcab8a3) Thanks [@bluwy](https://github.com/bluwy)! - Support Astro.slots.render for mdx

- [#4918](https://github.com/withastro/astro/pull/4918) [`a6bb2694b`](https://github.com/withastro/astro/commit/a6bb2694b4f7307844995fbb4481a40993d09a0d) Thanks [@bluwy](https://github.com/bluwy)! - Refactor hydration path handling

- [#4977](https://github.com/withastro/astro/pull/4977) [`4f73b98ae`](https://github.com/withastro/astro/commit/4f73b98ae04148412b38b98afa89a6120b600fd3) Thanks [@tony-sull](https://github.com/tony-sull)! - Fixes a bug that logged route cache warnings in `astro dev`

- [#4887](https://github.com/withastro/astro/pull/4887) [`37cb2fc02`](https://github.com/withastro/astro/commit/37cb2fc02a03754d454b243579bc55e55cf72904) Thanks [@Calvin-LL](https://github.com/Calvin-LL)! - fix object styles not escaped

- [#4990](https://github.com/withastro/astro/pull/4990) [`8f9791d84`](https://github.com/withastro/astro/commit/8f9791d840929bebc2b418e5ce3e48b541dc5744) Thanks [@matthewp](https://github.com/matthewp)! - Upgrade Astro compiler to 0.26.0

## 1.4.4

### Patch Changes

- [#4967](https://github.com/withastro/astro/pull/4967) [`e6a881081`](https://github.com/withastro/astro/commit/e6a881081f456b83294e1d85179b20951d7677e9) Thanks [@matthewp](https://github.com/matthewp)! - Final perf fix from 1.3.0 regression

  A regression in rendering perf happened in 1.3.0. This is the final fix for the underlying issue.

## 1.4.3

### Patch Changes

- [#4956](https://github.com/withastro/astro/pull/4956) [`ee8dd424f`](https://github.com/withastro/astro/commit/ee8dd424fda90688ff3f3ed4e736fb6151d9b422) Thanks [@matthewp](https://github.com/matthewp)! - Fix perf regression in SSR

- [#4952](https://github.com/withastro/astro/pull/4952) [`5bcd76e3a`](https://github.com/withastro/astro/commit/5bcd76e3ab3dfaab1d84d0af46d7e5a55a2b6ce2) Thanks [@bluwy](https://github.com/bluwy)! - Refactor ViteConfigWithSSR type

## 1.4.2

### Patch Changes

- [#4932](https://github.com/withastro/astro/pull/4932) [`9898088c0`](https://github.com/withastro/astro/commit/9898088c0a976da2cbf7607d92e5daf5db6a4536) Thanks [@matthewp](https://github.com/matthewp)! - Prevent hydration mismatch in streaming SSR

- [#4939](https://github.com/withastro/astro/pull/4939) [`cf2bba1e4`](https://github.com/withastro/astro/commit/cf2bba1e4a32ff7d424cc1c4954d6328167af8d7) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix MDX error handling, preventing a memory leak

## 1.4.1

### Patch Changes

- [#4928](https://github.com/withastro/astro/pull/4928) [`7690849a8`](https://github.com/withastro/astro/commit/7690849a87a7e192e28119211b75446ddbbc2ae3) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix module definition of Markdown and MDX files not being available outside Astro files

## 1.4.0

### Minor Changes

- [#4907](https://github.com/withastro/astro/pull/4907) [`01c1aaa00`](https://github.com/withastro/astro/commit/01c1aaa00397c7fdc7a3ef7fb0212eb43aad6238) Thanks [@matthewp](https://github.com/matthewp)! - Order Astro styles last, to override imported styles

  This fixes CSS ordering so that imported styles are placed _higher_ than page/component level styles. This means that if you do:

  ```astro
  ---
  import '../styles/global.css';
  ---

  <style>
    body {
      background: limegreen;
    }
  </style>
  ```

  The `<style>` defined in this component will be placed _below_ the imported CSS. When compiled for production this will result in something like this:

  ```css
  /* /src/styles/global.css */
  body {
    background: blue;
  }

  /* /src/pages/index.astro */
  body:where(.astro-12345) {
    background: limegreen;
  }
  ```

  Given Astro's 0-specificity hashing, this change effectively makes it so that Astro styles "win" when they have the same specificity as global styles.

- [#4876](https://github.com/withastro/astro/pull/4876) [`d3091f89e`](https://github.com/withastro/astro/commit/d3091f89e92fcfe1ad48daca74055d54b1c853a3) Thanks [@matthewp](https://github.com/matthewp)! - Adds the Astro.cookies API

  `Astro.cookies` is a new API for manipulating cookies in Astro components and API routes.

  In Astro components, the new `Astro.cookies` object is a map-like object that allows you to get, set, delete, and check for a cookie's existence (`has`):

  ```astro
  ---
  type Prefs = {
    darkMode: boolean;
  };

  Astro.cookies.set<Prefs>(
    'prefs',
    { darkMode: true },
    {
      expires: '1 month',
    }
  );

  const prefs = Astro.cookies.get<Prefs>('prefs').json();
  ---

  <body data-theme={prefs.darkMode ? 'dark' : 'light'}></body>
  ```

  Once you've set a cookie with Astro.cookies it will automatically be included in the outgoing response.

  This API is also available with the same functionality in API routes:

  ```js
  export function post({ cookies }) {
    cookies.set('loggedIn', false);

    return new Response(null, {
      status: 302,
      headers: {
        Location: '/login',
      },
    });
  }
  ```

  See [the RFC](https://github.com/withastro/rfcs/blob/main/proposals/0025-cookie-management.md) to learn more.

### Patch Changes

- [#4897](https://github.com/withastro/astro/pull/4897) [`fd9d323a6`](https://github.com/withastro/astro/commit/fd9d323a68c0f0cbb3b019e0a05e2c33450f3d33) Thanks [@bluwy](https://github.com/bluwy)! - Support Vue JSX

- [#4892](https://github.com/withastro/astro/pull/4892) [`ff7ba0ee0`](https://github.com/withastro/astro/commit/ff7ba0ee0fd652a92f5d06d9b644dd646cebe65c) Thanks [@matthewp](https://github.com/matthewp)! - Prevent multiple rendering of head content

- [#4842](https://github.com/withastro/astro/pull/4842) [`812658ad2`](https://github.com/withastro/astro/commit/812658ad2ab3732a99e35c4fd903e302e723db46) Thanks [@bluwy](https://github.com/bluwy)! - Add missing dependencies, support strict dependency installation (e.g. pnpm)

- [#4891](https://github.com/withastro/astro/pull/4891) [`87a7cf48e`](https://github.com/withastro/astro/commit/87a7cf48e7198ab94aa6310e58e9f30fd234c429) Thanks [@matthewp](https://github.com/matthewp)! - Hoist hydration scripts out of slot templates

- Updated dependencies [[`812658ad2`](https://github.com/withastro/astro/commit/812658ad2ab3732a99e35c4fd903e302e723db46), [`812658ad2`](https://github.com/withastro/astro/commit/812658ad2ab3732a99e35c4fd903e302e723db46)]:
  - @astrojs/markdown-remark@1.1.3
  - @astrojs/telemetry@1.0.1

## 1.3.1

### Patch Changes

- [#4861](https://github.com/withastro/astro/pull/4861) [`42fe8e0c7`](https://github.com/withastro/astro/commit/42fe8e0c7f40ebb9b81f29501a18969c6f335c41) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - use const instead of let for define:vars

- [#4878](https://github.com/withastro/astro/pull/4878) [`90c207299`](https://github.com/withastro/astro/commit/90c2072990952ff0331e8728e74abbcacc355fbf) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - add warning for post routes called when output is not server

- [#4855](https://github.com/withastro/astro/pull/4855) [`49ca9e129`](https://github.com/withastro/astro/commit/49ca9e1291616b0cbe5544ae451ea6d1c79ba93b) Thanks [@matthewp](https://github.com/matthewp)! - Fix TS errors when not using skipLibCheck

- [#4845](https://github.com/withastro/astro/pull/4845) [`3389f0ce9`](https://github.com/withastro/astro/commit/3389f0ce919dad14b15613f9ca24449ae02ab2e0) Thanks [@matthewp](https://github.com/matthewp)! - Prevent the root folder from being deleted during the build

- [#4841](https://github.com/withastro/astro/pull/4841) [`4b092269c`](https://github.com/withastro/astro/commit/4b092269c1f1c11327d7f61a8b543066b178f7ef) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - copy assets even if outDir is out of process.cwd()

- [#4849](https://github.com/withastro/astro/pull/4849) [`ee5fdeffd`](https://github.com/withastro/astro/commit/ee5fdeffddfee32a0d7708bbf6b64cee50e82aa7) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - append .html to the file URL in case build.format says file

- [#4867](https://github.com/withastro/astro/pull/4867) [`03e8b750a`](https://github.com/withastro/astro/commit/03e8b750ada926cca53d755947fc422e77285fb9) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - check if class:list's value is defined before converting

- [#4873](https://github.com/withastro/astro/pull/4873) [`83ed1cc1f`](https://github.com/withastro/astro/commit/83ed1cc1f20411ec876757f199cc0a1f182f2a80) Thanks [@bluwy](https://github.com/bluwy)! - Prevent /undefined catch-all routes in dev

- [#4454](https://github.com/withastro/astro/pull/4454) [`6a1a17dd2`](https://github.com/withastro/astro/commit/6a1a17dd28d884eb23faf2f2894fb66aff86acdc) Thanks [@bluwy](https://github.com/bluwy)! - Allow HMR for internal e2e tests

- [#4712](https://github.com/withastro/astro/pull/4712) [`17dbc6701`](https://github.com/withastro/astro/commit/17dbc670186188ba418a1c8842d9349ee557fa2a) Thanks [@Lifeni](https://github.com/Lifeni)! - Fix slashes for paths containing non-ASCII characters on Windows

- [#4850](https://github.com/withastro/astro/pull/4850) [`edb7bead6`](https://github.com/withastro/astro/commit/edb7bead6e42b463dce0f6837ea78ae733eab88b) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - add support for changing mode via CLI

- [#4868](https://github.com/withastro/astro/pull/4868) [`b99f9902b`](https://github.com/withastro/astro/commit/b99f9902b7ef90f2cb537b0204e41317c9f6ea83) Thanks [@rishi-raj-jain](https://github.com/rishi-raj-jain)! - remove all the ssr generated folders in static build if only empty

- Updated dependencies [[`5e4c5252b`](https://github.com/withastro/astro/commit/5e4c5252bd80cbaf6a7ee4d4503ece007664410f)]:
  - @astrojs/webapi@1.1.0

## 1.3.0

### Minor Changes

- [#4775](https://github.com/withastro/astro/pull/4775) [`b0cc93996`](https://github.com/withastro/astro/commit/b0cc93996169fe8a52a7b1119ce2180ae6101e70) Thanks [@tony-sull](https://github.com/tony-sull)! - Adds a new "astro:build:generated" hook that runs after SSG builds finish but **before** build artifacts are cleaned up. This is a very specific use case, "astro:build:done" is probably what you're looking for.

- [#4669](https://github.com/withastro/astro/pull/4669) [`a961aa3c2`](https://github.com/withastro/astro/commit/a961aa3c2fa946898fd209dfc70a7b5472b60817) Thanks [@aggre](https://github.com/aggre)! - astro-island now correctly passes Uint8Array/Uint16Array/Uint32Array

- [#4832](https://github.com/withastro/astro/pull/4832) [`73f215df7`](https://github.com/withastro/astro/commit/73f215df76d238a5ce0cb0e64543af032f468773) Thanks [@matthewp](https://github.com/matthewp)! - Allows Responses to be passed to set:html

  This expands the abilities of `set:html` to ultimate service this use-case:

  ```astro
  <div set:html={fetch('/legacy-post.html')} />
  ```

  This means you can take a legacy app that has been statically generated to HTML and directly consume that HTML within your templates. As is always the case with `set:html`, this should only be used on trusted content.

  To make this possible, you can also pass several other types into `set:html` now:

  - `Response` objects, since that is what fetch() returns:
    ```astro
    <div
      set:html={new Response('<span>Hello world</span>', {
        headers: { 'content-type': 'text/html' },
      })}
    />
    ```
  - `ReadableStream`s:
    ```astro
    <div
      set:html={new ReadableStream({
        start(controller) {
          controller.enqueue(`<span>read me</span>`);
          controller.close();
        },
      })}
    />
    ```
  - `AsyncIterable`s:
    ```astro
    <div
      set:html={(async function* () {
        for await (const num of [1, 2, 3, 4, 5]) {
          yield `<li>${num}</li>`;
        }
      })()}
    />
    ```
  - `Iterable`s (non-async):
    ```astro
    <div
      set:html={(function* () {
        for (const num of [1, 2, 3, 4, 5]) {
          yield `<li>${num}</li>`;
        }
      })()}
    />
    ```

### Patch Changes

- [#4831](https://github.com/withastro/astro/pull/4831) [`29b29e6a8`](https://github.com/withastro/astro/commit/29b29e6a8a54f6ed764e57bb97f1799657d39be7) Thanks [@yuhang-dong](https://github.com/yuhang-dong)! - Update vite-jsx-plugin for jsx export

- [#4754](https://github.com/withastro/astro/pull/4754) [`baae1b3fd`](https://github.com/withastro/astro/commit/baae1b3fd10cf0a74e880c0e0552ba8d58f24453) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Update `astro check` to latest version of the language server

- [#4509](https://github.com/withastro/astro/pull/4509) [`a0619f086`](https://github.com/withastro/astro/commit/a0619f08699de34f1d4c3da8020ac9a9ad3b9ff9) Thanks [@bluwy](https://github.com/bluwy)! - Refactor server url logs

## 1.2.8

### Patch Changes

- [#4813](https://github.com/withastro/astro/pull/4813) [`be9eaa069`](https://github.com/withastro/astro/commit/be9eaa069287d16ac8efc69e13407a5dfa5e5808) Thanks [@bluwy](https://github.com/bluwy)! - Allow override `vite.build.target`

- [#4817](https://github.com/withastro/astro/pull/4817) [`a49bc2f02`](https://github.com/withastro/astro/commit/a49bc2f02e8fa6c3e26e73d28a1c9c0e40da082a) Thanks [@mohammed-elhaouari](https://github.com/mohammed-elhaouari)! - fix parsing integration names with astro add command

- [#4819](https://github.com/withastro/astro/pull/4819) [`518e8f7e2`](https://github.com/withastro/astro/commit/518e8f7e25e03df7bdc9323cc26ea19c6b5e6d8c) Thanks [@matthewp](https://github.com/matthewp)! - Allow passing promises to set:html

- [#4807](https://github.com/withastro/astro/pull/4807) [`44fa37818`](https://github.com/withastro/astro/commit/44fa378186d711f8efab2135247ffde980e94795) Thanks [@lucacasonato](https://github.com/lucacasonato)! - Remove explicit `Transfer-Encoding: chunked` header from streaming responses

- [#4803](https://github.com/withastro/astro/pull/4803) [`f53d97d56`](https://github.com/withastro/astro/commit/f53d97d56be809a4c4a7f7d7ad79a22b36d8cd28) Thanks [@Enteleform](https://github.com/Enteleform)! - replaces hard-coded `minify` values with `vite.build.minify`

- Updated dependencies [[`df54595a8`](https://github.com/withastro/astro/commit/df54595a8836448a621fceeb38fbaacde1bb27cf)]:
  - @astrojs/markdown-remark@1.1.2

## 1.2.7

### Patch Changes

- [#4802](https://github.com/withastro/astro/pull/4802) [`cf5ed5f3a`](https://github.com/withastro/astro/commit/cf5ed5f3a87ea7b3a7ac6b9dd5a8659e41084ce1) Thanks [@bluwy](https://github.com/bluwy)! - Update Vite 3.1.3

- [#4782](https://github.com/withastro/astro/pull/4782) [`8f9463e07`](https://github.com/withastro/astro/commit/8f9463e07f23f0b617ca420852acf7af5f3d04ef) Thanks [@matthewp](https://github.com/matthewp)! - Fixes client:only CSS in Svelte components

## 1.2.6

### Patch Changes

- [#4771](https://github.com/withastro/astro/pull/4771) [`f3a81d82f`](https://github.com/withastro/astro/commit/f3a81d82f6ab4516cb86bf6b5e3eb01cb3ba39fb) Thanks [@matthewp](https://github.com/matthewp)! - Internal refactor

## 1.2.5

### Patch Changes

- [#4768](https://github.com/withastro/astro/pull/4768) [`9a59e24e0`](https://github.com/withastro/astro/commit/9a59e24e0250617333c1a0fd89b7d52fd1c829de) Thanks [@matthewp](https://github.com/matthewp)! - nsure before-hydration is only loaded when used

- [#4759](https://github.com/withastro/astro/pull/4759) [`fc885eaea`](https://github.com/withastro/astro/commit/fc885eaea1f08429599c0ab4697ab6382f3d7fa4) Thanks [@matthewp](https://github.com/matthewp)! - Read jsxImportSource from tsconfig

## 1.2.4

### Patch Changes

- [#4736](https://github.com/withastro/astro/pull/4736) [`13ca686ea`](https://github.com/withastro/astro/commit/13ca686ea18346a68db6af37348ee6d50719350d) Thanks [@bluwy](https://github.com/bluwy)! - Handle builds with outDir outside of current working directory

- [#4748](https://github.com/withastro/astro/pull/4748) [`c5e134d03`](https://github.com/withastro/astro/commit/c5e134d0358b7548bebe60b5707366b861c2fe28) Thanks [@bluwy](https://github.com/bluwy)! - Fix console.error filtering

- [#4742](https://github.com/withastro/astro/pull/4742) [`cf8a7e933`](https://github.com/withastro/astro/commit/cf8a7e933d26125eee44ce8b4f84d1353cfed957) Thanks [@matthewp](https://github.com/matthewp)! - Allow file uploads in dev server

- [#4752](https://github.com/withastro/astro/pull/4752) [`1bedb9427`](https://github.com/withastro/astro/commit/1bedb9427ebbe92eb74a82fc70cb67a97a250f32) Thanks [@bluwy](https://github.com/bluwy)! - Support Vite 3.1

- [#4755](https://github.com/withastro/astro/pull/4755) [`f1efd88dd`](https://github.com/withastro/astro/commit/f1efd88ddefe078f64901b1754ebfbaf65d36b51) Thanks [@matthewp](https://github.com/matthewp)! - Upgrade to Vite 3.1

- [#4594](https://github.com/withastro/astro/pull/4594) [`005d5bacd`](https://github.com/withastro/astro/commit/005d5bacd9c4dca5635da0759d5f73427df68e50) Thanks [@matthewp](https://github.com/matthewp)! - Allow custom 404 route to handle API route missing methods

## 1.2.3

### Patch Changes

- [#4724](https://github.com/withastro/astro/pull/4724) [`6efafa4b0`](https://github.com/withastro/astro/commit/6efafa4b0e392563d5375ec62ac6e3ac8372ec61) Thanks [@matthewp](https://github.com/matthewp)! - Use import order to sort CSS in the build

## 1.2.2

### Patch Changes

- [#4705](https://github.com/withastro/astro/pull/4705) [`5b6173fd0`](https://github.com/withastro/astro/commit/5b6173fd031b7e85974cbadd39de7fa199075e44) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Properly show an error message when a renderer is not properly configured

- [#4723](https://github.com/withastro/astro/pull/4723) [`0dba3b6f3`](https://github.com/withastro/astro/commit/0dba3b6f3fbd013f922fd11b9d6d977d165a512a) Thanks [@matthewp](https://github.com/matthewp)! - Makes the dev server more resilient to crashes

## 1.2.1

### Patch Changes

- [#4703](https://github.com/withastro/astro/pull/4703) [`d28f7013c`](https://github.com/withastro/astro/commit/d28f7013c2b415cbf6b640f17c9678ef0ac53253) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix: [astro add] Apply fetch polyfill before running

## 1.2.0

### Minor Changes

- [#4682](https://github.com/withastro/astro/pull/4682) [`d1e695914`](https://github.com/withastro/astro/commit/d1e69591479741022eecc122c43afb05985a94fd) Thanks [@bholmesdev](https://github.com/bholmesdev)! - astro add - move configuration updates to final step

- [#4549](https://github.com/withastro/astro/pull/4549) [`255636cc7`](https://github.com/withastro/astro/commit/255636cc7b4ed5f72045f75a2411ebd84a2bdb0d) Thanks [@altano](https://github.com/altano)! - Allow specifying custom encoding when using a non-html route. Only option before was 'utf-8' and now that is just the default.

- [#4578](https://github.com/withastro/astro/pull/4578) [`c706d845e`](https://github.com/withastro/astro/commit/c706d845ebf4786c33d2295954a98df8c5a7f183) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Restart dev server when config file is added, updated, or removed

### Patch Changes

- [#4699](https://github.com/withastro/astro/pull/4699) [`b85d05a84`](https://github.com/withastro/astro/commit/b85d05a841538b6a995808b6422b234f3e746804) Thanks [@matthewp](https://github.com/matthewp)! - Fix missing CSS in client:only in child packages

## 1.1.8

### Patch Changes

- [#4675](https://github.com/withastro/astro/pull/4675) [`63e49c3b6`](https://github.com/withastro/astro/commit/63e49c3b642274835cf99e2c0816a5bb655971c9) Thanks [@matthewp](https://github.com/matthewp)! - Prevent locking up when encountering invalid CSS

- [#4684](https://github.com/withastro/astro/pull/4684) [`919df13b9`](https://github.com/withastro/astro/commit/919df13b91eb561ae939e9be51e5a76ca97d8512) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fixes regression introduced in [#4646](https://github.com/withastro/astro/pull/4646) with better cyclic reference detection

- [#4683](https://github.com/withastro/astro/pull/4683) [`cc242d3af`](https://github.com/withastro/astro/commit/cc242d3af2cc39731cc40b07ac0aa1db687b2920) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix `tsc` compilation errors when `skipLibCheck` wasn't enabled

- [#4667](https://github.com/withastro/astro/pull/4667) [`9290b2414`](https://github.com/withastro/astro/commit/9290b24143d753edd3daf25945990c25a58e5bde) Thanks [@Holben888](https://github.com/Holben888)! - Fix framework components on Vercel Edge

- [#4645](https://github.com/withastro/astro/pull/4645) [`f27ca6ab3`](https://github.com/withastro/astro/commit/f27ca6ab3edbf0ef55e213ffd09aac454ce07995) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix client-side scripts reloads on dev server in windows

## 1.1.7

### Patch Changes

- [#4646](https://github.com/withastro/astro/pull/4646) [`98f242cdc`](https://github.com/withastro/astro/commit/98f242cdcd860679ad787ffb387558cb1dc93b87) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Add cyclic ref detection when serializing props

- [#4656](https://github.com/withastro/astro/pull/4656) [`6d845c353`](https://github.com/withastro/astro/commit/6d845c353d5688f30787c4361f86c605fb638dd9) Thanks [@matthewp](https://github.com/matthewp)! - Fix bug with using `assert` as import identifier

- [#4403](https://github.com/withastro/astro/pull/4403) [`d31e72c3b`](https://github.com/withastro/astro/commit/d31e72c3ba8270d1e8d33c533502b3c4c6390a15) Thanks [@JohnDaly](https://github.com/JohnDaly)! - Fix for components, declared with JSXMemberExpression nodes, that failed to hydrate due to incomplete 'component-export' metadata

## 1.1.6

### Patch Changes

- [#4623](https://github.com/withastro/astro/pull/4623) [`eb1862b4e`](https://github.com/withastro/astro/commit/eb1862b4e68b399eecc7267ea9e0bee36983b0cb) Thanks [@delucis](https://github.com/delucis)! - Improve third-party Astro package support

- [#4643](https://github.com/withastro/astro/pull/4643) [`307b7b97c`](https://github.com/withastro/astro/commit/307b7b97ce79d076ceb4fdc25fd28a27077deb34) Thanks [@matthewp](https://github.com/matthewp)! - Remove regression when there is duplicate client/server CSS

- [#4584](https://github.com/withastro/astro/pull/4584) [`29a5fdc15`](https://github.com/withastro/astro/commit/29a5fdc1535fc389035d8107025f7490bfa976ed) Thanks [@bluwy](https://github.com/bluwy)! - Correctly escape paths in file names

- [#4621](https://github.com/withastro/astro/pull/4621) [`0068afb87`](https://github.com/withastro/astro/commit/0068afb876342ae76154e552dfc5bb6832b665ed) Thanks [@AllanChain](https://github.com/AllanChain)! - Ensure SSR module is loaded before testing if it's CSS in dev

## 1.1.5

### Patch Changes

- [#4603](https://github.com/withastro/astro/pull/4603) [`36dee7169`](https://github.com/withastro/astro/commit/36dee7169be7f595825d3dfecb04e61cea1b2fe4) Thanks [@matthewp](https://github.com/matthewp)! - Fix error when no JSX renderer configured

## 1.1.4

### Patch Changes

- [#4586](https://github.com/withastro/astro/pull/4586) [`16814dc71`](https://github.com/withastro/astro/commit/16814dc718614c0cce46b788470c1bc40b5cc981) Thanks [@bluwy](https://github.com/bluwy)! - Move ast-types as dev dependency

- [#4585](https://github.com/withastro/astro/pull/4585) [`f018e365c`](https://github.com/withastro/astro/commit/f018e365cf22bd6b7235fe956e33b5d80fa059a1) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Add docs link to "missing adapter" error msg

## 1.1.3

### Patch Changes

- [#4574](https://github.com/withastro/astro/pull/4574) [`b92c24f40`](https://github.com/withastro/astro/commit/b92c24f4097f264a458c6f5044528c33fc897f01) Thanks [@delucis](https://github.com/delucis)! - Update `astro add` to list official integrations & adapters with same organisation we use in docs

* [#4566](https://github.com/withastro/astro/pull/4566) [`9ad307a9f`](https://github.com/withastro/astro/commit/9ad307a9fca064dcd9b2f27c3243d09d9154a5dc) Thanks [@bluwy](https://github.com/bluwy)! - Remove unused CSS for `client:load` components

## 1.1.2

### Patch Changes

- [#4519](https://github.com/withastro/astro/pull/4519) [`a2e8e76c3`](https://github.com/withastro/astro/commit/a2e8e76c303e8d6f39c24c122905a10f06907997) Thanks [@JuanM04](https://github.com/JuanM04)! - Upgraded Shiki to v0.11.1

- [#4531](https://github.com/withastro/astro/pull/4531) [`2d2e38e47`](https://github.com/withastro/astro/commit/2d2e38e473166e1e79886d3a9c7854927995dda1) Thanks [@bluwy](https://github.com/bluwy)! - Remove hardcoded Vite middleware handling

- [#4553](https://github.com/withastro/astro/pull/4553) [`2f05f5d30`](https://github.com/withastro/astro/commit/2f05f5d3071f01bf011212b5a91a5ac0c84fcff1) Thanks [@matthewp](https://github.com/matthewp)! - Include trailingSlash in astro:build:done hook

  This change ensures that the `pages` provided in the `astro:build:done` hook conform to the `trailingSlash` and `build.format` configs.

- [#4526](https://github.com/withastro/astro/pull/4526) [`046bfd908`](https://github.com/withastro/astro/commit/046bfd908de8bbfe9d24d1531260f1e6df03e912) Thanks [@bluwy](https://github.com/bluwy)! - Skip clean SSR output if page generation fails

- [#4546](https://github.com/withastro/astro/pull/4546) [`bb71be78d`](https://github.com/withastro/astro/commit/bb71be78db8abfc1a95de26c4508b694894cbcfd) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Update "Add an Adapter" help heading to "Add an SSR Adapter"

- [#4548](https://github.com/withastro/astro/pull/4548) [`69b640b87`](https://github.com/withastro/astro/commit/69b640b87c5d0f346129cd0cbd23efaf366bc8b1) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix "failed to load for SSR" on styles when using tailwind

- [#4535](https://github.com/withastro/astro/pull/4535) [`ca28d7578`](https://github.com/withastro/astro/commit/ca28d7578b7168fbc407132dc9a0c4115e1be878) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add missing `slot` attributes to SVG definitions

- [#4524](https://github.com/withastro/astro/pull/4524) [`d431fbe4e`](https://github.com/withastro/astro/commit/d431fbe4e1b04deba96e10679ebaaeedfcd6a239) - fix import in the config type declarations

- Updated dependencies [[`a2e8e76c3`](https://github.com/withastro/astro/commit/a2e8e76c303e8d6f39c24c122905a10f06907997)]:
  - @astrojs/markdown-remark@1.1.1

## 1.1.1

### Patch Changes

- [#4507](https://github.com/withastro/astro/pull/4507) [`4e1af3f0e`](https://github.com/withastro/astro/commit/4e1af3f0e8f5627cea24e4ec76d711d0387e3176) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix `import-meta.d.ts` not being included in the npm package

## 1.1.0

### Minor Changes

- [#4352](https://github.com/withastro/astro/pull/4352) [`cd154e447`](https://github.com/withastro/astro/commit/cd154e447ba7883531d484deea2fd046898d749b) Thanks [@matthewp](https://github.com/matthewp)! - Make Astro.url match the build.format configuration during the build

* [#4423](https://github.com/withastro/astro/pull/4423) [`d4cd7a59f`](https://github.com/withastro/astro/commit/d4cd7a59fd38d411c442a818cfaab40f74106628) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Update Markdown type signature to match new markdown plugin,and update top-level layout props for better alignment

- [#4474](https://github.com/withastro/astro/pull/4474) [`ac0321824`](https://github.com/withastro/astro/commit/ac03218247763e4782824e220a384fd20ae6d769) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add "extends" to markdown plugin config to preserve Astro defaults

* [#4138](https://github.com/withastro/astro/pull/4138) [`839097c84`](https://github.com/withastro/astro/commit/839097c84e830542c17c18d8337a88de8885c356) Thanks [@gtnbssn](https://github.com/gtnbssn)! - Makes remark-rehype options available in astro.config.mjs

- [#4182](https://github.com/withastro/astro/pull/4182) [`fcc36ac90`](https://github.com/withastro/astro/commit/fcc36ac908429733b1d9e51caddbc7590f9eeea5) Thanks [@Alxandr](https://github.com/Alxandr)! - Make type definitions available through package.json exports

### Patch Changes

- [#4500](https://github.com/withastro/astro/pull/4500) [`9874c7bf4`](https://github.com/withastro/astro/commit/9874c7bf42e48e8da214b77c5eb20c0f0cdce42f) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Update `astro check` to use latest version of the Astro language server

* [#4439](https://github.com/withastro/astro/pull/4439) [`77ce6be30`](https://github.com/withastro/astro/commit/77ce6be30c9cb8054ebf69a4943b984eed90152e) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add tsconfig templates for users to extend from

- [#4499](https://github.com/withastro/astro/pull/4499) [`1f42c0791`](https://github.com/withastro/astro/commit/1f42c0791c342740d3650dc04a15c3610f9ab00a) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix `tsc` not being able to find Vite's import.meta types on Linux

* [#4497](https://github.com/withastro/astro/pull/4497) [`78e06c8ec`](https://github.com/withastro/astro/commit/78e06c8ec01e041e3f78625cb85bcce0cf5be029) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Production build logging - Only log `[code].html` instead of `[code]/index.html` for 404 and 500 routes

* Updated dependencies [[`ac0321824`](https://github.com/withastro/astro/commit/ac03218247763e4782824e220a384fd20ae6d769), [`839097c84`](https://github.com/withastro/astro/commit/839097c84e830542c17c18d8337a88de8885c356)]:
  - @astrojs/markdown-remark@1.1.0

## 1.1.0-next.0

### Minor Changes

- [#4352](https://github.com/withastro/astro/pull/4352) [`cd154e447`](https://github.com/withastro/astro/commit/cd154e447ba7883531d484deea2fd046898d749b) Thanks [@matthewp](https://github.com/matthewp)! - Make Astro.url match the build.format configuration during the build

* [#4423](https://github.com/withastro/astro/pull/4423) [`d4cd7a59f`](https://github.com/withastro/astro/commit/d4cd7a59fd38d411c442a818cfaab40f74106628) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Update Markdown type signature to match new markdown plugin,and update top-level layout props for better alignment

- [#4474](https://github.com/withastro/astro/pull/4474) [`ac0321824`](https://github.com/withastro/astro/commit/ac03218247763e4782824e220a384fd20ae6d769) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add "extends" to markdown plugin config to preserve Astro defaults

* [#4138](https://github.com/withastro/astro/pull/4138) [`839097c84`](https://github.com/withastro/astro/commit/839097c84e830542c17c18d8337a88de8885c356) Thanks [@gtnbssn](https://github.com/gtnbssn)! - Makes remark-rehype options available in astro.config.mjs

- [#4182](https://github.com/withastro/astro/pull/4182) [`fcc36ac90`](https://github.com/withastro/astro/commit/fcc36ac908429733b1d9e51caddbc7590f9eeea5) Thanks [@Alxandr](https://github.com/Alxandr)! - Make type definitions available through package.json exports

### Patch Changes

- [#4439](https://github.com/withastro/astro/pull/4439) [`77ce6be30`](https://github.com/withastro/astro/commit/77ce6be30c9cb8054ebf69a4943b984eed90152e) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Add tsconfig templates for users to extend from

- Updated dependencies [[`ac0321824`](https://github.com/withastro/astro/commit/ac03218247763e4782824e220a384fd20ae6d769), [`839097c84`](https://github.com/withastro/astro/commit/839097c84e830542c17c18d8337a88de8885c356)]:
  - @astrojs/markdown-remark@1.1.0-next.0

## 1.0.9

### Patch Changes

- [#4457](https://github.com/withastro/astro/pull/4457) [`9490f0e22`](https://github.com/withastro/astro/commit/9490f0e2235a61984bc0bba7e2383d2383085cf2) Thanks [@matthewp](https://github.com/matthewp)! - Include styles imported by hoisted scripts

* [#4469](https://github.com/withastro/astro/pull/4469) [`8a2d6958f`](https://github.com/withastro/astro/commit/8a2d6958f1747ddc010464d7d8ccbad2d6838921) Thanks [@kagankan](https://github.com/kagankan)! - Fix load `base` option in build

- [#4451](https://github.com/withastro/astro/pull/4451) [`a38a56829`](https://github.com/withastro/astro/commit/a38a568299e6d23cb05ca2419b4a79e7ef5eef0b) Thanks [@bluwy](https://github.com/bluwy)! - Bump @astrojs/compiler dependency

* [#4473](https://github.com/withastro/astro/pull/4473) [`467108730`](https://github.com/withastro/astro/commit/467108730e4f45e4cd99779a7126b9dbd93d9ce5) Thanks [@bluwy](https://github.com/bluwy)! - Remove optional chaining in astro-island

- [#4475](https://github.com/withastro/astro/pull/4475) [`78334b976`](https://github.com/withastro/astro/commit/78334b9765f3044969b761053382db5fe208ed56) Thanks [@matthewp](https://github.com/matthewp)! - Fixes regression with JSX in Solid library

* [#4458](https://github.com/withastro/astro/pull/4458) [`aa555932b`](https://github.com/withastro/astro/commit/aa555932be9c4805c3dc3008a7edf244090155ea) Thanks [@bluwy](https://github.com/bluwy)! - Support `vite.build.cssCodeSplit: false` option

- [#4422](https://github.com/withastro/astro/pull/4422) [`85646918a`](https://github.com/withastro/astro/commit/85646918acbfe6a96be234ad3e93f60bc74a0b6e) Thanks [@bluwy](https://github.com/bluwy)! - Refactor CSS preprocess and deps HMR

* [#4456](https://github.com/withastro/astro/pull/4456) [`47e71ae8f`](https://github.com/withastro/astro/commit/47e71ae8f8735149facb34ce63d4d582f0dfd32e) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Added an error message when the second argument of Astro.slots.render is not an array

## 1.0.8

### Patch Changes

- [#4330](https://github.com/withastro/astro/pull/4330) [`baa2ddd01`](https://github.com/withastro/astro/commit/baa2ddd0103c269c862258520020395135e823ec) Thanks [@bluwy](https://github.com/bluwy)! - Warn hydration directive for Astro components in JSX

* [#4427](https://github.com/withastro/astro/pull/4427) [`b2e976f39`](https://github.com/withastro/astro/commit/b2e976f39c383eda8de58a2c86e94cbc9b3d678c) Thanks [@cameronmcefee](https://github.com/cameronmcefee)! - Fix config types to allow falsy values in integrations list, to match docs

- [#4385](https://github.com/withastro/astro/pull/4385) [`8164fa6f1`](https://github.com/withastro/astro/commit/8164fa6f1a01152f00542be33baebecd8ac60818) Thanks [@krolebord](https://github.com/krolebord)! - Fix warning when using hooks inside the react components not exported as a function declaration

* [#4445](https://github.com/withastro/astro/pull/4445) [`df4e99928`](https://github.com/withastro/astro/commit/df4e999284ae912b2a3f8a56573598a6ff21aa2a) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Add "waiting for X integration" log for long-running integration hooks

- [#4430](https://github.com/withastro/astro/pull/4430) [`dc42f2c00`](https://github.com/withastro/astro/commit/dc42f2c00fdc0c2f310ba43aa7f6ab15c525f18c) Thanks [@bholmesdev](https://github.com/bholmesdev)! - astro add - Fix third-party npm orgs, i.e. `@example/integration`

* [#4441](https://github.com/withastro/astro/pull/4441) [`ca0c7e8b8`](https://github.com/withastro/astro/commit/ca0c7e8b836b1be2db6a77698c9535a34ada8fe6) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Allow arbitrary strings on the target attribute

- [#4446](https://github.com/withastro/astro/pull/4446) [`27ac6a03a`](https://github.com/withastro/astro/commit/27ac6a03a1b58da836190922304de5645854b49b) Thanks [@matthewp](https://github.com/matthewp)! - Deterministic CSS ordering

  This makes our CSS link order deterministic. It uses CSS depth; that is how deeply a module import the CSS comes from, in order to determine which CSS is page-level vs. component-level CSS.

  This is intended to match dev ordering where, because we do not bundle, the page-level CSS always comes after component-level.

* [#4426](https://github.com/withastro/astro/pull/4426) [`f40065f51`](https://github.com/withastro/astro/commit/f40065f510b4fef40d3d3e069e8dc2d4d9a4edb2) Thanks [@matthewp](https://github.com/matthewp)! - Ensure index pages are generated on paginated results

## 1.0.7

### Patch Changes

- [#4415](https://github.com/withastro/astro/pull/4415) [`39088e11d`](https://github.com/withastro/astro/commit/39088e11db2ab69b370616d7cb369952cd9fd266) Thanks [@bluwy](https://github.com/bluwy)! - Bump Vite to 3.0.9

* [#4362](https://github.com/withastro/astro/pull/4362) [`aa5118e85`](https://github.com/withastro/astro/commit/aa5118e8543bb9ed240681acdabfcc09bdbb5438) Thanks [@joseph-lozano](https://github.com/joseph-lozano)! - Allow user config to set `markdown.drafts` option

- [#4344](https://github.com/withastro/astro/pull/4344) [`500332a42`](https://github.com/withastro/astro/commit/500332a426c8fa43e6534f0e41de5fc902f98ccd) Thanks [@bluwy](https://github.com/bluwy)! - Refactor static build config merge

* [#4364](https://github.com/withastro/astro/pull/4364) [`77b068086`](https://github.com/withastro/astro/commit/77b068086d923e99eb693d1c57b7d6cd906a1e8a) Thanks [@bluwy](https://github.com/bluwy)! - Preserve all error stack lines

- [#4405](https://github.com/withastro/astro/pull/4405) [`a70f69a06`](https://github.com/withastro/astro/commit/a70f69a06c069781c56393289f82efc1251fc37b) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Refactor JSX build plugin, improve performance

* [#4356](https://github.com/withastro/astro/pull/4356) [`beed20be4`](https://github.com/withastro/astro/commit/beed20be4a4dd01a52cff49887420b6a8b92b1a9) Thanks [@delucis](https://github.com/delucis)! - Provide correct MIME type for dynamic endpoint routes in dev

- [#4375](https://github.com/withastro/astro/pull/4375) [`5e82f6c24`](https://github.com/withastro/astro/commit/5e82f6c245be332764fcd5a90be491a430655c87) Thanks [@matthewp](https://github.com/matthewp)! - Fixes race condition between directives being defined

## 1.0.6

### Patch Changes

- [#4324](https://github.com/withastro/astro/pull/4324) [`45fdbc465`](https://github.com/withastro/astro/commit/45fdbc4650610bd8363a05c07f3863cc12391b28) Thanks [@BurntCaramel](https://github.com/BurntCaramel)! - Use TextEncoder instead of Buffer.byteLength() for Deno compatibility

* [#4334](https://github.com/withastro/astro/pull/4334) [`b55f76c1c`](https://github.com/withastro/astro/commit/b55f76c1cafb7918f7087c6df03dd1d59eeaa065) Thanks [@matthewp](https://github.com/matthewp)! - Fix double injecting of head content in md pages

- [#4329](https://github.com/withastro/astro/pull/4329) [`0274b8d47`](https://github.com/withastro/astro/commit/0274b8d47be6ad2f5a503f70e2efdd52e43dc9c4) Thanks [@tony-sull](https://github.com/tony-sull)! - Updates routing logic to allow multiple routes to match the same URL in SSR

* [#4347](https://github.com/withastro/astro/pull/4347) [`166b3b8a5`](https://github.com/withastro/astro/commit/166b3b8a544e6ba8f6a32960cf9c73bbb88c8b34) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Fix MDXLayoutProps type signature for linting

## 1.0.5

### Patch Changes

- [#4302](https://github.com/withastro/astro/pull/4302) [`1d3a0a16f`](https://github.com/withastro/astro/commit/1d3a0a16f33aa88c2b60088d6a497e4beaadb2dc) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Revert "Ensure hydration scripts inside of slots render ASAP (#4288)" to fix Svelte integration bug

* [#4284](https://github.com/withastro/astro/pull/4284) [`73f367c77`](https://github.com/withastro/astro/commit/73f367c77b8311707b1c142e03dd53952f14d934) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Prevent preview if 'output: server' is configured

## 1.0.4

### Patch Changes

- [#4268](https://github.com/withastro/astro/pull/4268) [`f7afdb889`](https://github.com/withastro/astro/commit/f7afdb889fe4e97177958c8ec92f80c5f6e5cb51) Thanks [@bholmesdev](https://github.com/bholmesdev)! - Align MD with MDX on layout props and "glob" import results:
  - Add `Content` to MDX
  - Add `file` and `url` to MDX frontmatter (layout import only)
  - Update glob types to reflect differences (lack of `rawContent` and `compiledContent`)

* [#4265](https://github.com/withastro/astro/pull/4265) [`8f845ca95`](https://github.com/withastro/astro/commit/8f845ca9507965e3898b3c7b70952c849bef310e) Thanks [@matthewp](https://github.com/matthewp)! - Prevents automatic trailingSlash appending on getStaticPaths produced pages

- [#4288](https://github.com/withastro/astro/pull/4288) [`c21810068`](https://github.com/withastro/astro/commit/c218100684c90c2b5c490e73b0687ad59d0c58df) Thanks [@matthewp](https://github.com/matthewp)! - Ensure hydration scripts inside of slots render ASAP

* [#4282](https://github.com/withastro/astro/pull/4282) [`c0992e1fe`](https://github.com/withastro/astro/commit/c0992e1fefc105577e99ac94338d349dbabf38d8) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Fix bug where Astro's server runtime would end up in the browser

- [#4272](https://github.com/withastro/astro/pull/4272) [`24d2f7a6e`](https://github.com/withastro/astro/commit/24d2f7a6e6700c10c863f826f37bb653d70e3a83) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Properly handle hydration for namespaced components

* [#4289](https://github.com/withastro/astro/pull/4289) [`3ca905174`](https://github.com/withastro/astro/commit/3ca905174967d6339ba90aa5bc1756fbe2fafdb0) Thanks [@bholmesdev](https://github.com/bholmesdev)! - [astro add] Set `output: 'server'` when adding adapter

## 1.0.3

### Patch Changes

- [#4239](https://github.com/withastro/astro/pull/4239) [`a9baa45af`](https://github.com/withastro/astro/commit/a9baa45af35abdd3e1930fb49e8b6fb0a4340e2a) Thanks [@bluwy](https://github.com/bluwy)! - Fix Astro client scripts sourcemap 404

* [#4279](https://github.com/withastro/astro/pull/4279) [`42fd6936c`](https://github.com/withastro/astro/commit/42fd6936cdb7106aea3770bed5313e558fc8b6dc) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Handle "not found" imports without throwing an "Invalid URL" error

- [#4273](https://github.com/withastro/astro/pull/4273) [`0022f46b5`](https://github.com/withastro/astro/commit/0022f46b57946f4f71e7f9f6e265081ee4ae1565) Thanks [@Princesseuh](https://github.com/Princesseuh)! - Fix build output adding `/index.html` at the end of endpoints route

* [#4270](https://github.com/withastro/astro/pull/4270) [`7127b1bb3`](https://github.com/withastro/astro/commit/7127b1bb35ca4e8f419e18683e380a4917eca4bb) Thanks [@natemoo-re](https://github.com/natemoo-re)! - Make third-party integration names nicer when using `astro add`

## 1.0.2

### Patch Changes

- [#4247](https://github.com/withastro/astro/pull/4247) [`714a8399e`](https://github.com/withastro/astro/commit/714a8399e20f334d2ba341c98d8ef5d590af9c39) Thanks [@matthewp](https://github.com/matthewp)! - Return 404 status code for 404.astro in SSR

* [#4240](https://github.com/withastro/astro/pull/4240) [`561a34d91`](https://github.com/withastro/astro/commit/561a34d91209c9d4959f74beaa17008edb27ff5d) Thanks [@matthewp](https://github.com/matthewp)! - Properly invalidate Astro modules when a child script updates in HMR

- [#4234](https://github.com/withastro/astro/pull/4234) [`c38e7f189`](https://github.com/withastro/astro/commit/c38e7f1890ba5bc97ddacee91ea196bcfc7652e6) Thanks [@bluwy](https://github.com/bluwy)! - Remove dev server during build

* [#4213](https://github.com/withastro/astro/pull/4213) [`f8e385339`](https://github.com/withastro/astro/commit/f8e3853394c2f2f48fac4b5eb2284e1960e59a13) Thanks [@bluwy](https://github.com/bluwy)! - Bump Vite to 3.0.5

- [#4225](https://github.com/withastro/astro/pull/4225) [`e918b3883`](https://github.com/withastro/astro/commit/e918b3883e156a0de2148517b619a2cf451917d2) Thanks [@mayank99](https://github.com/mayank99)! - `astro add` now supports `-y`

## 1.0.1

### Patch Changes

- [`3a7f2385e`](https://github.com/withastro/astro/commit/3a7f2385eadadb21794a06c86b7fa20b83b2f8f8) Thanks [@FredKSchott](https://github.com/FredKSchott)! - Add rawContent and compiledContent to MD layout props

## 1.0.0

> Astro v1.0 is out! Read the [official announcement post](https://astro.build/blog/astro-1/).

> **Note**
> If you need help migrating an existing Astro project to the new Astro v1.0, check out our updated [Migration Guide](https://docs.astro.build/en/migrate/) and [full documentation website](https://docs.astro.build/).

## 0.X

For older changelog entries -- including all v0.X, v1.0 Beta, and v1.0 Release Candidate versions -- check out [the v0.X changelog](https://github.com/withastro/astro/blob/astro%401.0.0/packages/astro/CHANGELOG.md).
