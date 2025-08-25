# dotfiles

사용중인 tools config를 동기화 시키기 위함.

## Bootstrap

```bash
curl -s https://raw.githubusercontent.com/kisn3089/dotfiles/main/install.sh | bash
```

## brew

### dump

```bash
brew bundle dump --describe
```

### install

```bash
brew bundle install
```

## dotfiles

### 사용법

stow를 통해 심볼링 링크된 파일 및 폴더를 이식할 PC에 똑같이 심볼링 링크를 연결해줘야 한다.

```bash
stow ~/.dotfiles .
```
