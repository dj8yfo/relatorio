1. `--no-docker` (no WSL) build on `cargo near new` project

Similar behaviour with [issue](https://github.com/near/cargo-near/issues/188)

![no_docker_no_wsl](./no_docker_no_wsl_err.png)

2. `--no-docker --no-abi` (no WSL) build on `cargo near new` project

Similar behaviour with [issue](https://github.com/near/cargo-near/issues/188)

![no_docker_no_wsl_no_abi_ok](./no_docker_no_wsl_no_abi_ok.png)

3. `--no-docker` (in WSL) build on `cargo near new` project

![wsl_revision.png](./wsl_revision.png)
![no_docker_wsl](no_docker_wsl.png)

<!-- 4. docker build (no WSL) on https://github.com/dj8yfo/sample_workspace/tree/50e63492a8ec4e844b251921824bf26e216832cb -->
