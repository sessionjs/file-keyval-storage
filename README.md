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

## Made for session.js

Use Session messenger programmatically with [Session.js](https://github.com/sessionjs/client): Session bots, custom Session clients, and more.

## Donate

[hloth.dev/donate](https://hloth.dev/donate)