# Salesforce LWC Codecept Example with Playwright

[More info ](http://localhost:8846/05-01-salesforce-lwc/1-salesforce-lighting-web-components-playwright/)

[![c-selenium.gif](https://i.postimg.cc/d05z9RXg/c-selenium.gif)](https://postimg.cc/B81YSFJC)

## Run Tests

#### Clone

```bash
    git clone git@github.com:gkushang/codeceptjs-bdd.git
```

#### Install

```bash

    cd packages/salesforce-lwc-codecept-example/salesforce-lwc-e2e-playwright
    yarn

```

#### Run Headless

```bash

    yarn acceptance

```

#### Run Non-Headless

```bash

    SHOW=true yarn acceptance

```

#### Run Parallel

```bash

   yarn acceptance:parallels

```

#### Launch HTML Report

```bash

   yarn acceptance:report

```
