Flask-Kickstart
=================

|build-status| |coverage|



推荐工作环境
------------------

- pycharm
- macOS
- python3.5+
- docker


注意事项
-----------

* 我们不对python3.5以下版本提供支持
* 项目保留名称： **lego** 、 **hive** 、
  请不要将项目命名为此名称，后续我们可能会开源相关的组件，以减少冲突。


快速开始
----------


快速预览
^^^^^^^^^^^^
需要占用5000端口

.. code-block::

    docker-compose up -d
    curl http://127.0.0.1:5000


本地预览
^^^^^^^^^^^^

请安装 `requirements.dev.txt` ,并按照 `docker-compose.yml` 及上层依赖中的环境变量配置。




.. |build-status| image:: https://secure.travis-ci.org/wangwenpei/flask-kickstart.png?branch=master
    :alt: Build status
    :target: https://travis-ci.org/wangwenpei/flask-kickstart

.. |coverage| image:: https://codecov.io/github/wangwenpei/flask-kickstart/coverage.svg?branch=master
    :target: https://codecov.io/github/wangwenpei/flask-kickstart?branch=master

