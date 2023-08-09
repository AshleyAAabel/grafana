# Code Review for grafana/packages/grafana-toolkit/*

--Code Guide: https://github.com/grafana/grafana/blob/main/contribute/style-guides/code-comments.md#add-package-description

## Review for https://github.com/AshleyAAabel/grafana/blob/main/packages/grafana-toolkit/src/cli/index.ts

  While it seems like the code is functional, there are some changes that could be made. As stated in the code guidelines, each package should have an overview explaining the overall responsibility and usage of the package. Adding the @packageDocumentation tag to the beginning of the listed file would help meet this requirement.

## Review for https://github.com/AshleyAAabel/grafana/blob/main/packages/grafana-toolkit/src/cli/tasks/task.ts

  The class Task<TOptions> in this file is well named and the parameters are clear and don't require further explanation. The code here, however, does not meet posted code guidelines. The stability of the API has not been set and should be set to meet requirements. The stability of this API should be denoted in a release tag and placed at the bottom of the code comment.
