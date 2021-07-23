# init build@22ca319

[Permalink](init-build-22ca319.md)

 Showing with **157 additions** and **0 deletions**.

1.  +2 −0 [.gitattributes](init-build-22ca319.md#diff-618cd5b83d62060ba3d027e314a21ceaf75d36067ff820db126642944145393e)
2.  +155 −0 [.gitignore](init-build-22ca319.md#diff-bc37d034bad564583790a46f19d807abfe519c5671395fd494d8cce506c42947)

|  |  | @@ -0,0 +1,2 @@ |
| :--- | :--- | :--- |
|  |  |  \# Auto detect text files and perform LF normalization |
|  |  |  \* text=auto |

|  |  | @@ -0,0 +1,155 @@ |
| :--- | :--- | :--- |
|  |  |  \# Byte-compiled / optimized / DLL files |
|  |  |  \_\_pycache\_\_/ |
|  |  |  \*.py\[cod\] |
|  |  |  \*$py.class |
|  |  |  |
|  |  |  \# C extensions |
|  |  |  \*.so |
|  |  |  |
|  |  |  \# Distribution / packaging |
|  |  |  .Python |
|  |  |  build/ |
|  |  |  develop-eggs/ |
|  |  |  dist/ |
|  |  |  downloads/ |
|  |  |  eggs/ |
|  |  |  .eggs/ |
|  |  |  lib/ |
|  |  |  lib64/ |
|  |  |  parts/ |
|  |  |  sdist/ |
|  |  |  var/ |
|  |  |  wheels/ |
|  |  |  pip-wheel-metadata/ |
|  |  |  share/python-wheels/ |
|  |  |  \*.egg-info/ |
|  |  |  .installed.cfg |
|  |  |  \*.egg |
|  |  |  MANIFEST |
|  |  |  |
|  |  |  \# PyInstaller |
|  |  |  \# Usually these files are written by a python script from a template |
|  |  |  \# before PyInstaller builds the exe, so as to inject date/other infos into it. |
|  |  |  \*.manifest |
|  |  |  \*.spec |
|  |  |  |
|  |  |  \# Installer logs |
|  |  |  pip-log.txt |
|  |  |  pip-delete-this-directory.txt |
|  |  |  |
|  |  |  \# Unit test / coverage reports |
|  |  |  htmlcov/ |
|  |  |  .tox/ |
|  |  |  .nox/ |
|  |  |  .coverage |
|  |  |  .coverage.\* |
|  |  |  .cache |
|  |  |  nosetests.xml |
|  |  |  coverage.xml |
|  |  |  \*.cover |
|  |  |  \*.py,cover |
|  |  |  .hypothesis/ |
|  |  |  .pytest\_cache/ |
|  |  |  |
|  |  |  \# Translations |
|  |  |  \*.mo |
|  |  |  \*.pot |
|  |  |  |
|  |  |  \# Django stuff: |
|  |  |  \*.log |
|  |  |  local\_settings.py |
|  |  |  db.sqlite3 |
|  |  |  db.sqlite3-journal |
|  |  |  |
|  |  |  \# Flask stuff: |
|  |  |  instance/ |
|  |  |  .webassets-cache |
|  |  |  |
|  |  |  \# Scrapy stuff: |
|  |  |  .scrapy |
|  |  |  |
|  |  |  \# Sphinx documentation |
|  |  |  docs/\_build/ |
|  |  |  |
|  |  |  \# PyBuilder |
|  |  |  target/ |
|  |  |  |
|  |  |  \# Jupyter Notebook |
|  |  |  .ipynb\_checkpoints |
|  |  |  |
|  |  |  \# IPython |
|  |  |  profile\_default/ |
|  |  |  ipython\_config.py |
|  |  |  |
|  |  |  \# pyenv |
|  |  |  .python-version |
|  |  |  |
|  |  |  \# pipenv |
|  |  |  \# According to pypa/pipenv\#598, it is recommended to include Pipfile.lock in version control. |
|  |  |  \# However, in case of collaboration, if having platform-specific dependencies or dependencies |
|  |  |  \# having no cross-platform support, pipenv may install dependencies that don't work, or not |
|  |  |  \# install all needed dependencies. |
|  |  |  \#Pipfile.lock |
|  |  |  |
|  |  |  \# Celery stuff |
|  |  |  celerybeat.pid |
|  |  |  \# celery beat schedule file |
|  |  |  celerybeat-schedule |
|  |  |  |
|  |  |  \# SageMath parsed files |
|  |  |  \*.sage.py |
|  |  |  |
|  |  |  \# Environments |
|  |  |  env/ |
|  |  |  .env |
|  |  |  .venv |
|  |  |  env/ |
|  |  |  venv/ |
|  |  |  ENV/ |
|  |  |  env.bak/ |
|  |  |  venv.bak/ |
|  |  |  |
|  |  |  \# Spyder project settings |
|  |  |  .spyderproject |
|  |  |  .spyproject |
|  |  |  |
|  |  |  \# Rope project settings |
|  |  |  .ropeproject |
|  |  |  |
|  |  |  \# mkdocs documentation |
|  |  |  /site |
|  |  |  |
|  |  |  \# mypy |
|  |  |  .mypy\_cache/ |
|  |  |  .dmypy.json |
|  |  |  dmypy.json |
|  |  |  |
|  |  |  \# Pyre type checker |
|  |  |  .pyre/ |
|  |  |  |
|  |  |  kannax/xcache/ |
|  |  |  \# PEP 582; used by e.g. github.com/David-OConnor/pyflow |
|  |  |  \_\_pypackages\_\_/ |
|  |  |  |
|  |  |  \# Celery stuff |
|  |  |  celerybeat.pid |
|  |  |  |
|  |  |  \# KannaX |
|  |  |  .apt/ |
|  |  |  .heroku/ |
|  |  |  .profile.d/ |
|  |  |  vendor/ |
|  |  |  config.env |
|  |  |  .vscode/ |
|  |  |  .idea/ |
|  |  |  \*.session |
|  |  |  unknown\_errors.txt |
|  |  |  logs/ |
|  |  |  kannax/plugins/dev/ |
|  |  |  resources/base\_profile\_pic.jpg |
|  |  |  resources/mdfy\_profile\_pic.jpg |
|  |  |  resources/ProductSans-BoldItalic.ttf |
|  |  |  resources/ProductSans-Light.ttf |
|  |  |  resources/Roboto-Regular.ttf |
|  |  |  resources/font.ttf |
|  |  |  resources/Roboto-Medium.tff |

