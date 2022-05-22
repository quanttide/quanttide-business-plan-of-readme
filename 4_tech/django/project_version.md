# django-project-version库

整理django-project-version的开发建议。

- GIT_REPO_PATH设置成BASE_DIR。
- GIT_TAG可以识别到最新创建的Tag（现在这样也可以，在先发布再部署的逻辑下正好work，可以加文档说明）。
- 解耦get_version模块，方便覆盖单元测试。
- 还可以对Git增加create_at标记版本发布时间。一个commit多个tag，不知道规则是什么样的。感觉是第一个，想要最新的。
