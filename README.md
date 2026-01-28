# @session.js/file-keyval-storage

Simple persistant storage that stores everything in memory and periodically syncs it with locally stored file in key=value format. `filePath` is optional and defaults to `./storage.db` 

```ts
import { Session } from '@session.js/client'
import { FileKeyvalStorage } from '@session.js/file-keyval-storage'

new Session({ 
  storage: new FileKeyvalStorage({ 
    filePath: 'some-file-path.db' 
  })
})
```

## Made for Session.js

Use Session messenger programmatically with [Session.js](https://git.hloth.dev/session.js/client): Session bots, custom Session clients, and more.

## Donate

[hloth.dev/donate](https://hloth.dev/donate) · Tor: [hlothdevzkti6suoksy7lcy7hmpxnr3msu5waokzaslsi2mnx5ouu4qd.onion/donate](http://hlothdevzkti6suoksy7lcy7hmpxnr3msu5waokzaslsi2mnx5ouu4qd.onion/donate)

## License

[MIT](./LICENSE)