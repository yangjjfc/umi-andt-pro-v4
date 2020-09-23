# Ant Design Pro

This project is initialized with [Ant Design Pro](https://pro.ant.design). Follow is the quick guide for how to use.

## Environment Prepare

Install `node_modules`:

```bash
npm install
```

or

```bash
yarn
```

## Provided Scripts

Ant Design Pro provides some useful script to help you quick start and build with web project, code style check and test.

Scripts provided in `package.json`. It's safe to modify or add additional script:

### Start project

```bash
npm start
```

### Build project

```bash
npm run build
```

### Check code style

```bash
npm run lint
```

You can also use script to auto fix some lint error:

```bash
npm run lint:fix
```

### Test code

```bash
npm test
```

## More

You can view full document on our [official website](https://pro.ant.design). And welcome any feedback in our [github](https://github.com/ant-design/ant-design-pro).


├── README.md
├── config
│   ├── config.ts 
│   ├── defaultSettings.ts //全局配置文件
│   └── proxy.ts
├── jest.config.js
├── jsconfig.json
├── mock
│   ├── listTableList.ts
│   ├── notices.ts
│   ├── route.ts
│   └── user.ts
├── package.json
├── public
│   ├── CNAME
│   ├── favicon.ico
│   ├── home_bg.png
│   ├── icons
│   │   ├── icon-128x128.png
│   │   ├── icon-192x192.png
│   │   └── icon-512x512.png
│   └── pro_icon.svg
├── src
│   ├── assets
│   │   └── logo.svg
│   ├── components
│   │   ├── Authorized
│   │   ├── GlobalHeader
│   │   ├── HeaderDropdown
│   │   ├── HeaderSearch
│   │   ├── NoticeIcon
│   │   └── PageLoading
│   ├── e2e
│   │   ├── __mocks__
│   │   └── baseLayout.e2e.js
│   ├── global.less
│   ├── global.tsx
│   ├── layouts
│   │   ├── BasicLayout.tsx
│   │   ├── BlankLayout.tsx
│   │   ├── SecurityLayout.tsx
│   │   ├── UserLayout.less
│   │   └── UserLayout.tsx
│   ├── locales
│   │   ├── en-US
│   │   ├── en-US.ts
│   │   ├── pt-BR
│   │   ├── pt-BR.ts
│   │   ├── zh-CN
│   │   ├── zh-CN.ts
│   │   ├── zh-TW
│   │   └── zh-TW.ts
│   ├── manifest.json
│   ├── models
│   │   ├── connect.d.ts
│   │   ├── global.ts
│   │   ├── login.ts
│   │   ├── setting.ts
│   │   └── user.ts
│   ├── pages
│   │   ├── 404.tsx
│   │   ├── Admin.tsx
│   │   ├── ListTableList
│   │   ├── Welcome.less
│   │   ├── Welcome.tsx
│   │   ├── document.ejs
│   │   └── user
│   ├── service-worker.js
│   ├── services
│   │   ├── login.ts
│   │   └── user.ts
│   ├── typings.d.ts
│   └── utils
│       ├── Authorized.ts
│       ├── authority.ts
│       ├── request.ts
│       ├── utils.less
│       ├── utils.test.ts
│       └── utils.ts
├── tests
│   ├── PuppeteerEnvironment.js
│   ├── beforeTest.js
│   ├── getBrowser.js
│   └── run-tests.js
├── tsconfig.json
└── yarn.lock