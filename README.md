# metamaskVaultDecrypt
## decrypt vault value from Metamask extension storage.

decrypt.js를 전체 복사해서 크롬 콘솔에 붙여넣은 뒤

크롬콘솔에서 

`decrypt(password, vault).then(console.log)` 를 수행하면 암호화된 private key를 복호화해서 볼 수 있습니다.

cf)  

password:  메타마스크 로그인 시 입력했던 비밀번호  

vault: 메타마스크 백그라운드 페이지에서 `chrome.storage.local.get(console.log)` 시 나오는 `data.KeyringController.vault`에 있는 값 (JSON)
