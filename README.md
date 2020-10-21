# @datapoint/carbon-vue

![logo](./logo.png)

An opinionated Vue implementation of IBM™ [Carbon Design System](http://www.carbondesignsystem.com/) version 10.

See it in action [here](https://datapoint.gitlab.io/carbon-vue/?path=/story/overview--page)

## Project setup

```bash
yarn install
```

### Using storybook for development

```bash
yarn storybook
```

### Compiles and minifies for production

```bash
yarn build
```

### Run your unit tests

```bash
yarn test:unit
```

### Lints and fixes files

```bash
yarn lint
```

## Using Carbon Vue in your project

Add carbon-vue to your project, as a dependency:

```bash
yarn add @datapoint/carbon-vue
```

### Using with Vue

Add the following to your `App.vue` file:

```javascript
import Vue from 'vue'
import CarbonVue from '@datapoint/carbon-vue'
Vue.use(CarbonVue)
```

### Using with Nuxt

Add a `carbon-vue.js` to `/plugins` folder:

```javascript
import Vue from 'vue'
import CarbonVue from '@datapoint/carbon-vue'
Vue.use(CarbonVue)
```

Add your new plugin in `nuxt.config.js`

```javascript
plugins: [
  'carbon-vue.js`
]
```

> you can use any other name for the file.

## Component List

| Component            | Status | Stories | Themes |
|----------------------|:------:|:-------:|:------:|
| Accordion            |    ✔   |    ✔    |    ✔   |
| Breadcrumb           |    ✔   |    ✔    |        |
| Button               |    ✔   |    ✔    |        |
| Checkbox             |    ✔   |    ✔    |        |
| CodeSnippet          |    ✔   |    ✔    |        |
| ComboBox             |    ✔   |    ✔    |    ✔   |
| ContentSwitcher      |        |         |        |
| DataTable            |    ✔   |    ✘    |        |
| DatePicker           |        |         |        |
| Dropdown             |    ✔   |    ✔    |        |
| FileUploader         |        |         |        |
| Form                 |    ✔   |    ✔    |        |
| InlineLoading        |        |         |        |
| InlineNotification   |        |         |        |
| Link                 |    ✔   |    ✔    |        |
| List                 |        |         |        |
| Loading              |    ✔   |    ✔!   |        |
| Modal                |    ✔   |    ✔    |        |
| MultiSelect          |        |         |        |
| NumberInput          |    ✔   |    ✔    |        |
| OverflowMenu         |    ✔   |    ✔    |        |
| Pagination           |    ✔   |    ✔    |        |
| Progress             |    ✔   |    ✔    |        |
| RadioButton          |    ✔   |    ✔    |        |
| Search               |        |         |        |
| Select               |    ✔   |    ✔    |        |
| SkeletonText         |        |         |        |
| Slider               |    ✔   |    ✔    |        |
| StructuredList       |        |         |        |
| Tabs                 |   ✔!   |    ✔    |        |
| Tag                  |    ✔   |    ✔    |        |
| TextArea             |    ✔   |    ✔    |        |
| TextInput            |    ✔   |    ✔!   |        |
| Tile                 |    ✔   |    ✔    |        |
| TimePicker           |    ✔   |    ✔!   |        |
| ToastNotification    |    ✔   |    ✔    |        |
| Toggle               |    ✔   |    ✔    |        |
| Tooltip              |    ✔   |    ✔    |        |
| UIShell              |    ✔   |    ✔    |        |
