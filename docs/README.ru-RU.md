![logo](img/logo.png)

Коллекция красивых (и, надеюсь, полезных) хитов React для ускорения разработки ваших компонентов и хуков

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Попробуй их в действии тут 🌟
    </a>
  </p>
</div>

![Usage example](img/usage_example.png)

🇬🇧 English | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.zh-CN.md">🇨🇳 简体中文</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.it-IT.md">🇮🇹 Italiano</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.es-ES.md"> 🇪🇸 Español </a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.uk-UA.md">🇺🇦 Ukrainian</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.pt-BR.md">🇧🇷 Brazilian Portuguese</a> | <a href="https://github.com/beautifulinteractions/beautiful-react-hooks/blob/master/docs/README.pl-PL.md">🇵🇱 Polski </a> | <a href="https://github.com/YaroslavW/beautiful-react-hooks-gitrepo/blob/master/docs/README.ru-RU.md">🇷🇺 Russian </a>

<!-- change on site -->

## 💡 Зачем?

Пользовательские React-хуки позволяют абстрагировать бизнес-логику компонентов в отдельные функции многократного использования. <br />
До сих пор мы обнаружили, что большинство хуков, которые мы создали и поэтому разделяли между нашими внутренними проектами, довольно часто
аналогичны по сути, которая включает в себя ссылки на обратный вызов, события и жизненный цикл компонентов. <br />
По этой причине мы постарались обобщить эту суть в `"beautiful-react-hooks"`: набор (_надеюсь_) полезных хуков, чтобы помочь другим компаниям и специалистам ускорить процесс разработки. <br /> <br />
Кроме того, мы создали лаконичный, но конкретный API, с точки зрения читабельности кода, с целью держать кривую изучения столь низкой, насколько это возможно, поэтому это может быть использовано и распространено в больших командах.

**-Пожалуйста, перед использованием любого хука, прочитайте его документацию!-**

## ☕️ Характеристики

- Краткий API
- Маленький размер и легкость
- Легко учить
- Функциональный подход
- Полностью написан на JS (хотя поддерживаются типы TS)

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Попробуй их в действии тут 🌟
    </a>
  </p>
</div>

## 🕺 Установка

Используя `npm`:

```bash
$ npm install beautiful-react-hooks
```

Используя `yarn`:

```bash
$ yarn add beautiful-react-hooks
```

## 🎨 Hooks

- [useGlobalEvent](docs/ru/useGlobalEvent.md)
- [usePreviousValue](docs/ru/usePreviousValue.md)
- [useValueHistory](docs/ru/useValueHistory.md)
- [useValidatedState](docs/ru/useValidatedState.md)
- [useMediaQuery](docs/ru/useMediaQuery.md)
- [useOnlineState](docs/ru/useOnlineState.md)
- [useViewportSpy](docs/ru/useViewportSpy.md)
- [useGeolocation](docs/ru/useGeolocation.md), [useGeolocationState](docs/ru/useGeolocationState.md) and [useGeolocationEvents](docs/ru/useGeolocationEvents.md)
- [useDrag](docs/ru/useDrag.md), [useDragEvents](docs/ru/useDragEvents.md)
- [useMouse](docs/ru/useMouse.md), [useMouseState](docs/ru/useMouseState.md) and [useMouseEvents](docs/ru/useMouseEvents.md)
- [useLifecycle](docs/ru/useLifecycle.md), [useDidMount](docs/ru/useDidMount.md) and [useWillUnmount](docs/ru/useWillUnmount.md)
- [useWindowResize](docs/ru/useWindowResize.md)
- [useWindowScroll](docs/ru/useWindowScroll.md)
- [useRequestAnimationFrame](docs/ru/useRequestAnimationFrame.md)
- [useTimeout](docs/ru/useTimeout.md)
- [useConditionalTimeout](docs/ru/useConditionalTimeout.md)
- [useInterval](docs/ru/useInterval.md)
- [useDebouncedFn](docs/ru/useDebouncedFn.md)
- [useThrottledFn](docs/ru/useThrottledFn.md)
- [useLocalStorage](docs/ru/useLocalStorage.md)

## Вклад.

Вклад очень приветствуется и нужен.

Чтобы отправить свой пользовательский хук, пожалуйста, убедитесь, что вы прочитали наши рекомендации [CONTRIBUTING](./CONTRIBUTING.md).

**Перед отправкой** нового запроса на слияние (merge реквест), пожалуйста, убедитесь:

1. Вы обновили версию `package.json` и сообщили о своих изменениях в файл [CHANGELOG] (./ CHANGELOG.md).
2. убедитесь, что вы запускаете `npm test` и `npm build` перед отправкой запроса на слияние (merge реквест).
3. убедитесь, что вы добавили документацию для своего пользовательского хука (_вы можете использовать [HOOK_DOCUMENTATION_TEMPLATE] (./ HOOK_DOCUMENTATION_TEMPLATE.md) для документирования своего пользовательского хука_).
4. убедитесь, что вы обновили файл `index.d.ts` с вашими типами хуков.

### При содействии:

- [React](https://reactjs.org/)
- [Mocha](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
- [@testing-library/react](https://testing-library.com/docs/react-testing-library/intro)
- [@testing-library/react-hooks](https://react-hooks-testing-library.com/)

### Спонсорство

Эта библиотека предоставлена и спонсируется:

<div>
  <p>
    <a href="https://beautifulinteractions.com/">
      <img src="https://beautifulinteractions.com/img/logo-colorful.svg" alt="Beautiful interactions" width="140px" />
    </a>
  </p>
</div>

В рамках нашего обязательства по поддержке и содействии опенсорс сообщества.

---

Значок сделан [Freepik](https://www.flaticon.com/authors/freepik) from [www.flaticon.com](https://www.flaticon.com/free-icon/hook_1081812)
