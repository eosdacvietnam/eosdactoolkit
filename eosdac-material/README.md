eosDAC Toolkit GUI

**1. Install Vue-Cli**
```
yarn global add vue-cli
or:
npm install -g vue-cli
```

**2. Install Quasar-Cli**

```
# Node.js >= 8.9.0 is required.
yarn global add quasar-cli
or:
npm install -g quasar-cli
```
**3. Clone Repo**
```
git clone https://github.com/eosdac/eosdactoolkit.git
```
**4. Install modules (on windows yarn is recommended)**
```
# in project directory
yarn install
or:
npm install
```
**5. Copy the config file you want to use (jungle or mainnet)**
```
cp src/statics/config.jungle.json src/statics/config.json
```
**6. Run dev server with material theme**
```
quasar dev
```
[Quasar Docs](https://quasar-framework.org/guide/index.html)
