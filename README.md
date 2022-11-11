# NLW Copa

 ![GitHub release (latest by date including pre-releases)](https://img.shields.io/github/v/release/dedevillela/nlw-copa?include_prereleases) [![PRs welcome][pr-badge]][pr-link] [![GitHub Lisense][gh-license-badge]][gh-license-link] [![Say Thanks][st-badge]][st-link] [![Views][views-badge]][views-link]

![Wallpaper - 1400x900](https://user-images.githubusercontent.com/3102096/200440974-1ba8df06-b946-4992-acc4-3670be2f2a4e.png)

> The **NLW Copa** is a free online event to take you to the next level, building an exclusive **FIFA World Cup Qatar 2022™** poll application. Extensive use of **Next JS**[^nextjs], **Prisma**[^prisma], **Expo**[^expo] and **Native Base**[^nativebase].

- 💻 [Project Details (Notion)](https://efficient-sloth-d85.notion.site/Trilha-Ignite-82e072f1d683490aa480e4a822357b35)

---

## 🚀 Getting Started

- From your terminal, clone the repository into your local machine, chage your current folder to the project folder you just created, and install the dependencies.

```sh
git clone https://github.com/dedevillela/nlw-copa.git && \
cd nlw-copa && \
npm install
```

- Install dependencies, generate database schema and start the [server development environment](./server/).

```sh
cd server && \
npm install && \
npx prisma migrate dev && \
npm run dev
```

- Install dependencies and start the [web development environment](./web/).

```sh
cd web && \
npm install && \
npm run dev
```

- Install dependencies and start the [mobile development environment](./mobile/).

```sh
cd mobile && \
npm install && \
npx expo start
```

## :memo: License

- [MIT License](LICENSE)

[^nextjs]: [Next JS](https://nextjs.org/)

[^prisma]: [Prisma](https://www.prisma.io/docs/)

[^expo]: [Expo](https://www.expo.io/)

[^nativebase]: [NativeBase](https://nativebase.io/)

[pr-badge]: https://img.shields.io/badge/PRs-welcome-brightgreen.svg

[pr-link]: ./CONTRIBUTING.md

[gh-license-badge]: https://img.shields.io/github/license/dedevillela/nlw-copa

[gh-license-link]: ./LICENSE

[st-badge]: https://img.shields.io/badge/SayThanks.io-%E2%98%BC-1EAEDB

[st-link]: https://saythanks.io/to/dedevillela/

[views-badge]: https://views.whatilearened.today/views/github/dedevillela/nlw-copa.svg

[views-link]: https://github.com/dedevillela/nlw-copa
