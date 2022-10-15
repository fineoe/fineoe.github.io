# [React]() ·![](https://camo.githubusercontent.com/83d3746e5881c1867665223424263d8e604df233d0a11aae0813e0414d433943/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f6c6963656e73652d4d49542d626c75652e737667)![](https://camo.githubusercontent.com/475b49b04214dfa67c1ec8a2837888ae63003feb7b71fd45be30ff360148ad87/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f762f72656163742e7376673f7374796c653d666c6174) ![](https://camo.githubusercontent.com/37d17fb69546b8990603b0ac9b1576401bc135e4719ba164014a2bf91358538f/68747470733a2f2f636972636c6563692e636f6d2f67682f66616365626f6f6b2f72656163742e7376673f7374796c653d736869656c6426636972636c652d746f6b656e3d3a636972636c652d746f6b656e) ![](https://camo.githubusercontent.com/b0ad703a46e8b249ef2a969ab95b2cb361a2866ecb8fe18495a2229f5847102d/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e2e737667)
React id a JavScript library for buiding user interfaces.
* **Declarative:** React makes it painless to create interactive Uls.Desogn simple views for each state in your application,and React will efficiently update and render just the right componentd when your data changes.Declarative views make your code more predictable,simpler to understans,and easier to debug.
* **Component -Basef:** Build encapsulated components that manage their own state,then compose them to make complex Uls.Since component logic is writton inJavaScript instead of templates,you can easily pass rich sata through your app and keep the state out of the DOM.
* **Learn Once,Write Anywhere:** We don't make assumptions about the rest of your technology stack,so you can develop new features in React without rewriting existing code.React can also render on the server using Node and power mobile apps using [React Native]().
[Learn how to use React in your project]().
# Installation
React has been designed for gradual adoption from the sstart,and **you can use as littlef or as much React as you need:**
* Use [Online Plagrounds]() to get a taste of React.
* [Add React to a Website]() as a `<script>` tag in one minute.
* [Creat a New React App]() if you're looking for a powerfol JacaScript toolchain.
You can use React as a `<script>`  tag from a [CDN](),or as a `react` package on npm.
# Documenttation
You can find the React documentation [on thfe website]().
Check out the [Getting Started]() page for a quick overview.
The documentation is divided into several section:
* [Tutorial]()
* [Mian Concepts]()
* [Advanced Guides]()
* [API Referrnce]()
* [Where to Get Support]()
* [Contributing Guide]()
You can improve it by dending pull requests to [this repository]().
# Examples
We have several example [on the website]().Here is the first one to get you started:
```js
import { createRoot } from 'react-dom/client';
function HelloMessage({ name }) {
	return <div>Hello {name}</div>;
}

const root = createRoot(document.getElementById('container'));
root.render(<HelloMessage name="Taylor>" />);
```
This example will render "Hello Taylor" into a container on the page.

You'll notice that we used an HTML-like syntax; [we call it JSX]().JSX is not required to use React,but it makes code more readable,and writing it feels like writing HTML.If you're using React as a `<script>` tag,read [this section]() on integrating JSX;otherwise,the [recommended JavaScript toolchains]() handle it automatically.

# Contributing
The main purpose of this repository is to continue evolving Reat core,making it faster and easier to use. Development of React happens in the open on GitHub,and we are grateful to the community for cntributing bugfixes and improvements.Read below to learn how you can take part in inproving React.
# [Code of Conduct]()
Facebook has adopted a Code of Conduct that we expect project  participants to adhere to. Please read [the full text]() so that you can understand what actions will and will not be tolerated.
# [Contributing Guide]()
Read our [contributing guide]() to  learn about our development process,
how to propose bugfixes and imprppvements,and how to build and test your changes to React.
#  Good First Issues
To help you get your feet wet and get you familiar with our contribution process,we have a list of [good first issues]() that contain bugs yaht have a relatively limited scope.This is a great place to get started.
# License
React is [MIT licensed]()