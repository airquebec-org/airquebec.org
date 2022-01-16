# Air Québec

## Introduction

Le site web informationnel de Air Québec, regroupement pour la qualité de l'air du Québec


## Jekflix

Le site web est un fork de Jekflix. La documentation originale est ici: [[JEKFLIX.md]]

## Installation de l'environnement sur Mac OS X


basé sur les dépendances de Github: https://pages.github.com/versions/

```
brew install rbenv
rbenv install 2.7.3
rbenv local 2.7.3
gem install bundler
```

workaround broken libffi dependency:

```
export LDFLAGS="-L/usr/local/opt/libffi/lib"
export CPPFLAGS="-I/usr/local/opt/libffi/include"
export PKG_CONFIG_PATH="/usr/local/opt/libffi/lib/pkgconfig"
gem install ffi -- --enable-system-libffi
```

install

```
bundle install
```

install nvm:

https://github.com/nvm-sh/nvm


install gulp:

```
npm install --global gulp
```
```
