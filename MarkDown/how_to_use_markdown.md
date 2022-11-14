<!--사용방법-->
# Markdown 문법
## 1. 헤더
```
# 가장 큰 제목
## 두번째 큰 제목
### 세번째 큰 제목
#### 네번째 큰 제목
##### 다섯번째 큰 제목
###### 여섯번째 큰 제목
```
## 2. 목록
### 순서가 있는 목록은 숫자와 점을 사용합니다.

```
1. 첫번째
2. 두번째
3. 세번째
```
<img width="300" alt="image" src="https://user-images.githubusercontent.com/88806404/195787105-195f7f10-f82d-4bef-8d71-487a79dfc7a6.png">
<br><br>

### 순서가 없는 목록(*,+,-)

```
* 빨강
    * 녹색
        * 파랑

+ 빨강
    + 녹색
        + 파랑

- 빨강
    - 녹색
        - 파랑
```
<img width="300" height=200 alt="image" src="https://user-images.githubusercontent.com/88806404/195787502-fd904be7-0472-48d2-98d3-ee1621435e7e.png">
<br><br>
혼합하여 사용도 가능합니다.

```
* 1단계
    - 2단계
        + 3단계
            + 4단계
```
<img width="300" height=200 alt="image" src="https://user-images.githubusercontent.com/88806404/201568082-7b0f8a9c-ed6e-4f23-baf3-c65022538bd4.png"><br>

## 3. 코드
4개의 공백 또는 하나의 탭으로 시작하고 들여쓰지 않은 행을 만날때 까지 변환이 계속됩니다.<br>
### 3-1. 들여쓰기

    this is sample code
        this is sample code
<br>

### 3-2. 코드 블럭
코드 블럭은 다음과 같이 2가지 방식으로 사용합니다.
+ \<pre>\<code>{code}\</code>\</pre><br><br>
ex)<br>
    ```
    <pre>
    <code>
    public class Sample {
        public static void main(String[] args) {
            System.out.println("Hello, World");
        }
    }
    </code>
    </pre>
    ```
    적용
    ```
    public class Sample {
        public static void main(String[] args) {
            System.out.println("Hello, World");
        }
    }
    ```
<br>

+ 코드 블럭 (```) 사용
    ```
       ```
        public class Sample {
        public static void main(String[] args) {
            System.out.println("Hello, World");
            }
        }
        ```
    ```
    적용
    ```
    
    public class Sample {
    public static void main(String[] args) {
        System.out.println("Hello, World");
        }
    }
    ```
깃허브에서는 코드블럭코드 (```) 시작점에 사용하는 언어를 선업하여 <b>문법강조(Syntax highlighting)</b>이 가능합니다.
```
    ```java
        public class Sample {
        public static void main(String[] args) {
            System.out.println("Hello, World");
            }
        }
    ```
```
결과
```java
    public class Sample {
    public static void main(String[] args) {
        System.out.println("Hello, World");
        }
    }
```

<br>

## 4. 수평선
아래에 있는 것들은 모두 줄을 만듭니다. 마크다운 문서를 미리보기로 출력할 때 페이지 나누기 용도로 많이 사용합니다.
<br>
```
* * *

***

*****

- - -

------------
```
적용
* * *
***
*****
- - -
-------------

<br>

## 5. 링크
+ 참조링크
