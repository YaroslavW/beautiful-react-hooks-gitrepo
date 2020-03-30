[![Build Status](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks.svg?branch=master)](https://travis-ci.org/beautifulinteractions/beautiful-react-hooks)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![npm](https://img.shields.io/npm/v/beautiful-react-hooks)
![GitHub stars](https://img.shields.io/github/stars/beautifulinteractions/beautiful-react-hooks?style=social)

<div align="center">
  <p align="center">
    <img src="../logo.png" alt="Beautiful React Hooks" width="750px" />
  </p>
</div>
<br />

Коллекция красивых (и, надеюсь, полезных) хитов React для ускорения разработки ваших компонентов и хуков

<div>
  <p align="center">
    <a href="https://beautifulinteractions.github.io/beautiful-react-hooks/" target="_blank">
    🌟 Попробуй их в действии тут 🌟
    </a>
  </p>
</div>

![Usage example](../usage_example.png)

<a href="../README.md">🇬🇧 English</a> | <a href="README.zh-CN.md">🇨🇳 简体中文</a> | <a href="README.it-IT.md">🇮🇹 Italiano</a> |<a href="README.es-ES.md"> 🇪🇸 Español | <a href="README.uk-UA.md">🇺🇦 Ukrainian</a> | <a href="README.pt-BR.md">🇧🇷 Brazilian Portuguese</a> | <a href="README.pl-PL.md">🇵🇱 Polski </a> | <a href="README.ru-RU.md">🇷🇺 Russian </a>

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

- [useGlobalEvent](ru/useGlobalEvent.md)
- [usePreviousValue](ru/usePreviousValue.md)
- [useValueHistory](ru/useValueHistory.md)
- [useValidatedState](ru/useValidatedState.md)
- [useMediaQuery](ru/useMediaQuery.md)
- [useOnlineState](ru/useOnlineState.md)
- [useViewportSpy](ru/useViewportSpy.md)
- [useGeolocation](ru/useGeolocation.md), [useGeolocationState](ru/useGeolocationState.md) and [useGeolocationEvents](ru/useGeolocationEvents.md)
- [useDrag](ru/useDrag.md), [useDragEvents](ru/useDragEvents.md)
- [useMouse](ru/useMouse.md), [useMouseState](ru/useMouseState.md) and [useMouseEvents](ru/useMouseEvents.md)
- [useLifecycle](ru/useLifecycle.md), [useDidMount](ru/useDidMount.md) and [useWillUnmount](ru/useWillUnmount.md)
- [useWindowResize](ru/useWindowResize.md)
- [useWindowScroll](ru/useWindowScroll.md)
- [useRequestAnimationFrame](ru/useRequestAnimationFrame.md)
- [useTimeout](ru/useTimeout.md)
- [useConditionalTimeout](ru/useConditionalTimeout.md)
- [useInterval](ru/useInterval.md)
- [useDebouncedFn](ru/useDebouncedFn.md)
- [useThrottledFn](ru/useThrottledFn.md)
- [useLocalStorage](ru/useLocalStorage.md)

## Вклад.

Вклад очень приветствуется и нужен.

Чтобы отправить свой пользовательский хук, пожалуйста, убедитесь, что вы прочитали наши рекомендации [CONTRIBUTING](../CONTRIBUTING.md).

**Перед отправкой** нового запроса на слияние (merge реквест), пожалуйста, убедитесь:

1. Вы обновили версию `package.json` и сообщили о своих изменениях в файл [CHANGELOG](../CHANGELOG.md).
2. убедитесь, что вы запускаете `npm test` и `npm build` перед отправкой запроса на слияние (merge реквест).
3. убедитесь, что вы добавили документацию для своего пользовательского хука - **вы можете использовать** [HOOK_DOCUMENTATION_TEMPLATE](../HOOK_DOCUMENTATION_TEMPLATE.md) для документирования своего пользовательского хука\*).
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
