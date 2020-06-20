# socks5-proxy-note

## pip via socks5
``` console
pip install --proxy socks5h://127.0.0.1:8080 pytest
```

## git via socks5
``` console
# enable proxy
git config --global http.proxy 'socks5h://127.0.0.1:8080'
git config --global https.proxy 'socks5h://127.0.0.1:8080'
# disable proxy
git config --global --unset http.proxy
git config --global --unset https.proxy
```

## Chrome via socks5

Edit the short cut path
```console
"C:\Program Files (x86)\Google\Chrome\Application\chrome.exe" --proxy-server="socks5://127.0.0.1:8080" --incognito
```

