# B08H51JHS1-5.6-job

# 実行結果

```bash
$ circleci local execute 
Docker image digest: sha256:2c2fd6a4655b259ac40f3c168b82200d4a7cebdc8287c4eb866a348b0191403d
====>> Spin Up Environment
Build-agent version  ()
Docker Engine Version: 20.10.1
Kernel Version: Linux 1508e525ece5 5.4.0-1035-aws #37-Ubuntu SMP Wed Jan 6 21:01:57 UTC 2021 x86_64 Linux
Starting container cimg/node:lts
  image is cached as cimg/node:lts, but refreshing...
lts: Pulling from cimg/node
Digest: sha256:f6ab0eb78b007434b722a3a5b9345010d5a4a0ec5a7aa4acf802aa2d88fb0090
Status: Image is up to date for cimg/node:lts
  using image cimg/node@sha256:f6ab0eb78b007434b722a3a5b9345010d5a4a0ec5a7aa4acf802aa2d88fb0090
====>> Preparing Environment Variables
Using build environment variables:
  BASH_ENV=/tmp/.bash_env-localbuild-1611993320
  CI=true
  CIRCLECI=true
  CIRCLE_BRANCH=
  CIRCLE_BUILD_NUM=
  CIRCLE_JOB=build
  CIRCLE_NODE_INDEX=0
  CIRCLE_NODE_TOTAL=1
  CIRCLE_REPOSITORY_URL=
  CIRCLE_SHA1=
  CIRCLE_SHELL_ENV=/tmp/.bash_env-localbuild-1611993320
  CIRCLE_WORKING_DIRECTORY=~/project


The redacted variables listed above will be masked in run step output.====>> ジョブで定義された環境変数を利用する
  #!/bin/bash -eo pipefail
echo "NODE_ENV is '${NODE_ENV}'"
NODE_ENV is 'production'
====>> ステップで同名の環境変数を定義すると上書きされる
  #!/bin/bash -eo pipefail
echo "NODE_ENV is '${NODE_ENV}'"
NODE_ENV is 'test'
Success!
```