# frida-checklist-guide



a personal repository for help pentesting in mobile assets android/ios with frida tool.



### default scripts for bypass


- SSL -> https://codeshare.frida.re/@pcipolloni/universal-android-ssl-pinning-bypass-with-frida/

- Root -> https://raw.githubusercontent.com/apkunpacker/Root_Bypass/main/HideRoot.js

- Jailbreak -> https://codeshare.frida.re/@DevTraleski/ios-jailbreak-detection-bypass-palera1n/ // pode ser necessario implementar outras verificaces (access,urlscheme,fopen,open...)

- Deep Links -> https://codeshare.frida.re/@leolashkevych/android-deep-link-observer/


Obs: recomendo uma implementacao propria dos scripts de bypass baseado no ambiente encontrado durante seus testes, os scripts acima podem ajudar mas levem apenas como base.


### Tips for frida use



### Android template 

```
Java.perform(function (){
  // ...
});
```


### IOS template (objc)

```
if (ObjC.available) {
  //check if objc is available
}
```
