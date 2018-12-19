## 使用版本管理器安装Node.js和npm

[原文](https://docs.npmjs.com/getting-started/installing-node#using-a-version-manager-to-install-nodejs-and-npm)

由于npm和node.js产品由不同的实体管理，因此更新和维护可能变得复杂。此外，Node.js安装过程将npm安装在仅具有本地权限的目录中。当您尝试全局运行包时，这可能会导致权限错误。

为了解决这两个问题，许多开发人员选择使用*节点版本管理器*或*nvm*来安装npm。版本管理器将避免权限错误，并将解决更新Node.js和npm的复杂性。

此外，开发人员可以使用nvm在多个版本的npm上测试他们的应用程序。nvm使您可以轻松切换npm以及节点版本。这样可以更轻松地确保您的应用程序适用于大多数用户，即使他们使用的是其他版本的npm。如果您决定安装版本管理器，请使用您选择的版本管理器的说明来学习如何切换版本，并了解如何使用最新版本的npm保持最新。

### 苹果 macOS

单击[此处](https://github.com/creationix/nvm/blob/master/README.md#installation)了解如何为MacO安装**nvm**。

### 微软 Windows

要在Windows上安装和管理npm和Node.js，我们建议使用[nvm-windows](https://github.com/coreybutler/nvm-windows)。

### Linux

单击[此处](https://github.com/creationix/nvm/blob/master/README.md#installation)了解如何安装**nvm** for Linux。



----

建议您使用版本管理器来安装Node.js. 有很多很棒的选择，这里有几个：

* [NVM](https://github.com/creationix/nvm)
* [nodist](https://github.com/marcelklehr/nodist)
* [n](https://github.com/tj/n)
* [nave](https://github.com/isaacs/nave)
* [nodebrew](https://github.com/hokaccha/nodebrew)