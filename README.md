## Get Started(TBD)

> [简体中文 > 如何开始使用](./README_CN.md#开始使用)

1. Get [OpenAI API Key](https://platform.openai.com/account/api-keys);
2. Click
   [![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new/clone?repository-url=https%3A%2F%2Fgithub.com%2FYidadaa%2FChatGPT-Next-Web&env=OPENAI_API_KEY&env=CODE&project-name=chatgpt-next-web&repository-name=ChatGPT-Next-Web), remember that `CODE` is your page password;
3. Enjoy :)

## FAQ

[简体中文 > 常见问题](./docs/faq-cn.md)

[English > FAQ](./docs/faq-en.md)

### Manually Updating Code

If you want to update instantly, you can check out the [GitHub documentation](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/syncing-a-fork) to learn how to synchronize a forked project with upstream code.

You can star or watch this project or follow author to get release notifications in time.

## Requirements

NodeJS >= 18, Docker >= 20

## Development

> [简体中文 > 如何进行二次开发](./README_CN.md#开发)

Before starting development, you must create a new `.env.local` file at project root, and place your api key into it:

```
OPENAI_API_KEY=<your api key here>

# if you are not able to access openai service, use this BASE_URL
BASE_URL=https://chatgpt1.nextweb.fun/api/proxy
```

### Local Development

```shell
# 1. install nodejs and yarn first
# 2. config local env vars in `.env.local`
# 3. run
yarn install
yarn dev
```

## Deployment

> [简体中文 > 如何部署到私人服务器](./README_CN.md#部署)

## LICENSE

[MIT](https://opensource.org/license/mit/)
