# javascript
Studying for the javaScript

## preventDefault(); vs stopPropagation(); 

- event.preventDefault();

```
preventDefault 는 기본으로 정의된 이벤트를 작동하지 못하게 하는 메서드.
preventDefault() 메서드는 이벤트가 전파되는것(버블링이나 캡처 단계)를 중지시키지는 않음.
```

> 버블링이란?

자식 element에서 발생된 event가 부모 element순으로 전달 되는 현상

> 캡쳐링이란?

부모 element에서 발생된 event가 자식 element순으로 전달 되는 현상


- event.stopPropagation();

```
이벤트가 상위 DOM으로 전달,전파를 하지 않도록 하는 코드.
이벤트 전파를 막아 주지만 기본 이벤트를 막아주진 않음.
```
