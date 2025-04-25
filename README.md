```shell
curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh -s -- -y
```

```shell
echo 'export PATH="$HOME/.cargo/bin:$PATH"' >> ~/.bashrc && source ~/.bashrc
```

```shell
rustup self update
```

```shell
rustc --version
```

```shell
rustup show
```

```shell
rustup toolchain install X.XX.X
rustup default X.XX.X
