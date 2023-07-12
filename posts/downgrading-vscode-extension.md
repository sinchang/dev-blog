---
title: How to downgrade VSCode extension
description: downgrade the VSCode extension to a specific version in two steps.
date: 2023-07-12
tags:
  - VSCode
layout: layouts/post.njk
---
Sometimes, we may need to downgrade the VSCode extension to a specific version if a bug cannot be fixed immediately.

To complete that, follow these steps:

1. Wisit the webpage for the extension (e.g. https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components). Then, navigate to the `Version History` tab and download the desired version.

  ![image](https://github.com/sinchang/dev-blog/assets/3297859/b0ff7008-5ad8-4b11-85e1-de7d53618dfe)

2. To install the file you downloaded, open VSCode and press `CTRL+SHIFT+P`. In the command line, type `vsix` and select the downloaded file.

  ![image](https://github.com/sinchang/dev-blog/assets/3297859/cc644e96-8646-4ab9-af09-d484f1a5e46f)
