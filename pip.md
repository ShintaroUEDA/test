### バージョンを確認する
```
$ pip --version
pip 10.0.1 from ~/.pyenv/versions/3.5.3/lib/python3.5/site-packages/pip (python 3.5)
```

### 普通にパッケージをインストールする (例えばFlask)
```
pip install Flask
```

### requirements.txtに定義されたパッケージをインストールする
```
pip install -r requirements.txt
```

### インストール済みのパッケージを表示する
```
pip list
```

### インストール済みのパッケージをrequires.txt形式で表示する
```
pip freeze
```

### インストール済みのパッケージのうち、最新でないものを表示する
```
pip list --outdated
```

### インストール済みのパッケージのうち、最新でないものをアップデートする
```
pip list --outdated | awk 'NR>2 {print $1}' | xargs pip install -U
```

### インストール済みのパッケージを全て削除する
```
pip freeze | xargs pip uninstall -y
```
