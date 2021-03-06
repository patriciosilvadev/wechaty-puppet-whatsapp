# Wechaty Puppet Whatsapp

[![NPM Version](https://badge.fury.io/js/wechaty-puppet-whatsapp.svg)](https://badge.fury.io/js/wechaty-puppet-whatsapp)
[![npm (tag)](https://img.shields.io/npm/v/wechaty-puppet-whatsapp/next.svg)](https://www.npmjs.com/package/wechaty-puppet-whatsapp?activeTab=versions)
[![NPM](https://github.com/wechaty/wechaty-puppet-whatsapp/workflows/NPM/badge.svg)](https://github.com/wechaty/wechaty-puppet-whatsapp/actions?query=workflow%3ANPM)

![wechaty puppet whatsapp](docs/images/wechaty-puppet-whatsapp.png)

[![Powered by Wechaty](https://img.shields.io/badge/Powered%20By-Wechaty-brightgreen.svg)](https://github.com/wechaty/wechaty)
[![TypeScript](https://img.shields.io/badge/%3C%2F%3E-TypeScript-blue.svg)](https://www.typescriptlang.org/)

Puppet Whatsapp

## USAGE

### Puppet Whatsapp

```ts
import { Wechaty }   from 'wechaty'
import { PuppetWhatsapp } from 'wechaty-puppet-whatsapp'

const puppet  = new PuppetWhatsapp()
const wechaty = new Wechaty({ puppet })

wechaty.start()
```

## History

### master

### v0.0.1 (Nov, 2020)

Initial version.

1. Kick-off PR from [@univerone](https://github.com/univerone) with ding-dong-bot enabled!

## Creators

1. [@univerone](https://github.com/univerone) Shanshan JIANG
1. [@huan](https://github.com/huan) [Huan LI](http://linkedin.com/in/zixia) \<zixia@zixia.net\>

## COPYRIGHT & LICENSE

* Code & Docs © 2020-now Wechaty Contributors <https://github.com/wechaty>
* Code released under the Apache-2.0 License
* Docs released under Creative Commons
