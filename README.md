# aria2-docker

A lightweight docker image to run [aria2](https://github.com/aria2/aria2) and [AriaNG](https://github.com/mayswind/AriaNg).

## Usages

```sh
git clone https://github.com/adoyle-h/aria2-docker.git
cd aria2-docker
docker compose up -d
# To visit http://localhost:8080/ in browser
```

## The .env file

See https://docs.docker.com/compose/environment-variables/set-environment-variables/

Example:

```sh
cat <<EOF > .env
IMAGE_VERSION=1.0.0
DOWNLOAD_DIR=./downloads
WEB_PORT=8080
RPC_PORT=6800
EOF
```

## Suggestion, Bug Reporting, Contributing

**Before opening new Issue/Discussion/PR and posting any comments**, please read [Contributing Guidelines](https://gcg.adoyle.me/CONTRIBUTING).

## Copyright and License

Copyright 2023 ADoyle (adoyle.h@gmail.com). Some Rights Reserved.
The project is licensed under the **Apache License Version 2.0**.

See the [LICENSE][] file for the specific language governing permissions and limitations under the License.

See the [NOTICE][] file distributed with this work for additional information regarding copyright ownership.


<!-- Links -->

[LICENSE]: ./LICENSE
[NOTICE]: ./NOTICE
[tags]: https://github.com/adoyle-h/aria2-docker/tags
[issue]: https://github.com/adoyle-h/aria2-docker/issues