# Info

> [!IMPORTANT]
> [dotfiles](https://github.com/parkgang/dotfiles) `서브모듈` 로 관리됩니다.

## 개요

- 원본 저장소에서 `fork` 되어서 관리됩니다.
- 개인적으로 수정된 내용은 [.tmux.conf.local](./.tmux.conf.local) 에만 반영됩니다.
- `main` 저장소에서 변경 내역을 바로 반영할 수 있도록 `git switch master` 으로 branch 를 변경합니다.

## 적용 방법

```shell
ln -s ~/dotfiles/tmux/.tmux.conf ~
ln -s ~/dotfiles/tmux/.tmux.conf.local ~
```
