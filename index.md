## Добро пожаловать на страницы GitHub

    pip install jupyter-kite
    jupyter labextension install "@kiteco/jupyterlab-kite"
    

**Обновление плагина**

Мы периодически отправляем обновления для плагина Jupyter Lab. В настоящее время вам необходимо вручную обновить плагин с помощью команд терминала. Для этого остановите запущенный процесс Jupyter Lab, а затем выполните две команды:

    pip install --upgrade jupyter-kite
    jupyter labextension update "@kiteco/jupyterlab-kite"


**Поиск проблемы**

Если у вас возникли проблемы с установкой плагина Kite Jupyter Lab, сначала убедитесь, что у вас установлена ​​Jupyter Lab v2..  2 или новее, и что у вас установлено и запущено приложение Kite Engine.

Кроме того, если у вас установлено расширение `jupyterlab-lsp`, вы должны отключить его, чтобы плагин Kite работал.

Если вы соответствуете этим требованиям, пожалуйста, откройте проблему в нашей системе отслеживания проблем и предоставьте следующую информацию:

* Your OS
* Журналы консоли вашего браузера
* Your terminal console output (as much of as possible, not just the first or final line)
* The output of jupyter labextension list and `jupyter serverextension list`
* The output of `pip list`
* If you use `conda`, please share your environment

### Markdown

Markdown - это легкий и простой в использовании синтаксис для стилизации вашего текста. Он включает соглашения для

```markdown
Выделенный синтаксисом блок кода

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/easy5q/djangoProject/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
