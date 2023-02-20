# web2023
나의 블로그 : https://popidea77.tistory.com/

## HTML
블럭구조와 인라인구조
시멘틱 논리적인 마크업

# JAVASCRIPT
변수, 상수, 배열, 객체
<script>
    // 01. 변수 : 데이터 저장
        
    // 02. 변수 : 데이터 저장 + 데이터 변경
        // var let 차이점 알아두기
        {
            let x = 100;
            let y = 200;
            let z = "javascript"

            x = 300;
            y = 200;
            z = "react";

            // console.log(x);
            // console.log(y);
            // console.log(z);
        }

    // 03. 변수 : 데이터 저장 + 데이터 변경 + 데이터 추가
    {
        let x = 100;
        let y = 200;
        let z = "javascript"

        x += 300; // x = x + 300; 
        y += 400;
        z += "react";

        // console.log(x);
        // console.log(y);
        // console.log(z);
    }

    // 00. 상수 : 데이터 저장 + 데이터 변경(x)
    // 상수는 데이터 저장은 가능하나 변경은 불가능합니다.
    // 상수(const)는 이미 선언한 상수에 대해 중복 선언이 불가능하며
    // 상수의 값을 재지정할 수도 없습니다.

    //변수 ( )
    {
        const a = 10000;
        const b = 20000;

        // 연산자
        // console.log(a + b)
        // console.log(a - b)
        // console.log(a > b)
        // console.log(a * b)
        // console.log(a / b)
        // console.log(a % b)

        let c = 10;
        c = "100"
        c = 1000;
        c +=1000;

        // console.log(c)
        // 검사에서 콘솔 값 확인하기
    }
        // 05. 배열 : 데이터 저장(여러개): 표현방법1
        {
            const arr = new Array();
            arr[0] = 100;
            arr[1] = 200;
            arr[2] = "javascript";

            console.log(arr[0]);
            console.log(arr[1]);
            console.log(arr[2]);
        }

        // 06. 배열 : 데이터 저장(여러개): 표현방법2
        {
            const arr = new Array(100, 200, "javascript");

            // console.log(arr[0]);
            // console.log(arr[1]);
            // console.log(arr[2]);
        }
          // 07. 배열 : 데이터 저장(여러개): 표현방법3
          {
            const arr = [];
            arr[0] = 100;
            arr[1] = 200;
            arr[2] = "javascript";

            // console.log(arr[0]);
            // console.log(arr[1]);
            // console.log(arr[2]);
        }
        // 08. 배열 : 데이터 저장(여러개): 표현방법4
        {
            const arr = [100, 200, "javascript"];

            // console.log(arr[0]);
            // console.log(arr[1]);
            // console.log(arr[2]);
        }

        // 09. 객체 : 데이터 저장 (키와 값) : 표현방법2
        {
            const obj = new Object();
            obj [0] = 100;
            obj [1] = 200;
            obj [2] = "javascript";

            // console.log(obj[0]);
            // console.log(obj[1]);
            // console.log(obj[2]);
        }

        // 10. 객체 : 데이터 저장 (키와 값) : 표현방법2
        {
            const obj = new Object();
            obj.a = 100;
            obj.b = 200;
            obj.c = "javascript";

            // console.log(obj[a]);
            // console.log(obj[b]);
            // console.log(obj[c]);
        }
        // 11. 객체 : 데이터 저장 (키와 값) : 표현방법3
        {
            const obj = {}; 
            obj. a = 100;
            obj. b = 200;
            obj. c = "javascript";

            // console.log(obj[a]);
            // console.log(obj[b]);
            // console.log(obj[c]);
            // 객체 배열에 대한 정의를 알아야 한다. 
            //* 객체 배열 변수에 대한 정확한 정의
        }
        // 12. 객체 : 데이터 저장 (키와 값) : 표현방법3
        {
            const obj = {a:100, b:200, c:"javascript"};

            // console.log(obj[a]);
            // console.log(obj[b]);
            // console.log(obj[c]);
        }
    </script>