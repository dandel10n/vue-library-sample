# Test Vue library, built using rollup

- First setup

```bash
yarn install
```

- Production build

```bash
yarn build
```

- Usage example

```js
    <template>
        <lib-component-one />
    </template>

    <script>
    import { LibComponentOne } from '@justeat/f-vue-icons';

    export default {
        components: {
            LibComponentOne
        }
    };
    </script>
```