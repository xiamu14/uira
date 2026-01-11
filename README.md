```tsx
import {cn,cva} from '@uira/utility'

function Demo() {
  return <div className={}>
    <Button size='sm'></Button>
    <p className={`bg-red m-2 p-2 
      border-1 border-red-300
      flex flex-row jusitify-center items-center
      text-red-300 text-14px
      hover:(bg-red)`}>hello word</p>
  </div>
}

```

```ts
// uira.config.ts
import {createConfig} from '@uira/css'

export default createConfig({})

````

@uira/css
@uira/ui

`bunx @uira/ui add button select`

```ts
import {Button} from '@src/component/uira/ui'
import {cva} from '@uira/utility'

...
```
