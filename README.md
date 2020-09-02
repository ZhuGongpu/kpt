你好！
很冒昧用这样的方式来和你沟通，如有打扰请忽略我的提交哈。我是光年实验室（gnlab.com）的HR，在招Golang开发工程师，我们是一个技术型团队，技术氛围非常好。全职和兼职都可以，不过最好是全职，工作地点杭州。
我们公司是做流量增长的，Golang负责开发SAAS平台的应用，我们做的很多应用是全新的，工作非常有挑战也很有意思，是国内很多大厂的顾问。
如果有兴趣的话加我微信：13515810775  ，也可以访问 https://gnlab.com/，联系客服转发给HR。
<img src="https://storage.googleapis.com/kpt-dev/docs/logo.png" width="50" height="50" />

# KPT

kpt is a toolkit to help you manage, manipulate, customize, and apply Kubernetes Resource configuration data files.

- Fetch, update, and sync configuration files using git.
- Examine and modify configuration files.
- Generate, transform, validate configuration files using containerized functions.
- Apply configuration files to clusters.

## Installation

### Install with Gcloud

The version of kpt installed using `gcloud` may not be the latest released version.

```Shell
gcloud components install kpt
```

### Install with Homebrew

```Shell
brew tap GoogleContainerTools/kpt https://github.com/GoogleContainerTools/kpt.git
brew install kpt
```

### Download latest release

[Latest release][release]

### Install from source

```sh
GO111MODULE=on go get -v github.com/GoogleContainerTools/kpt
```

## Run using Docker image

[gcr.io/kpt-dev/kpt]

```sh
docker run gcr.io/kpt-dev/kpt version
```

### [Documentation][docs]

See the [docs] for more information on how to use `kpt`.

---

[linux]: https://storage.googleapis.com/kpt-dev/latest/linux_amd64/kpt
[darwin]: https://storage.googleapis.com/kpt-dev/latest/darwin_amd64/kpt
[windows]: https://storage.googleapis.com/kpt-dev/latest/windows_amd64/kpt.exe
[docs]: https://googlecontainertools.github.io/kpt
[release]: https://github.com/GoogleContainerTools/kpt/releases/latest
[gcr.io/kpt-dev/kpt]: https://console.cloud.google.com/gcr/images/kpt-dev/GLOBAL/kpt?gcrImageListsize=30
