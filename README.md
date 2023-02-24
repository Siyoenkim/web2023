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

    
    <script>
        // const x = 100; //숫자, 문자, 블린, 논리형, 심벌, 함수, 객체, null, undefinded 이 들어갈 수 있습니다. => 이것을 자료형이라 칭함. 자바 59페이지 / 검사하기 위해서는 typeof 사용
        // const y = true; 
        // const b = false;

        { 
        
        const X = 100;
        const y = 200;
        const z = "javascript";
        
        console.log(X);
        console.log(y);
        console.log(z);

        }
       
        //출력형식. clg를 가장 많이 씀
        //document.write(X);
        //alert(z) 

        {
            const x = 100, y = 200, z = "javascript"
            console.log(x, y, z)

        //상단과 같지만 한줄 출력 방식이다

        }
        
        {

            let x = 100;
            let y = 200;
            let z = "javascript";

            // let 대신 const 사용 가능 

            x = 1000;
            x -= 1000; //100 - 1000 = -900
            x += 1000; //-900 + 1000 = 100

            console.log(x, y, z)

        }

        {
            const brr = new Array();
            const crr = new Array(200, "react", false);
            const drr = [];
            const err = [300, "arrat", true];
            
            //배열하는 방법은 네가지 / brr,crr은 마음대로 바꿀 수 있음. brr crr 은 구방식 err이 최신 방식
            
            brr[0] = 100;
            brr[1] = "javascript";
            brr[2] = true;
            drr[0] = 100;
            drr[1] = "javascript";
            drr[2] = true;

            console.log(brr[0], brr[1], brr[2]);
            console.log(crr[0], crr[1], crr[2]);
            console.log(drr[0], drr[1], drr[2]);
            console.log(err[0], err[1], err[2]);
        }
            // 배열 끝

            // < 객체 >
        
            // 객체 : 데이터 저장 (키와값) : 표현방법 1
            // 객체를 표현하는 기본적인 방법으로 객체는 배열 방식을 그대로 사용할 수 있다.
            {
                const obj = new Object();

                obj[0] = 100;
                obj[1] = 200;
                obj[2] = "javascript";

                console.log(obj[0]);
                console.log(obj[1]);
                console.log(obj[2]);

            }
            

            // 객체 : 데이터 저장 (키와값) : 표현방법 2
            {
                const obj = new Object();

                obj.a = 100;
                obj.b = 200;
                obj.c = "javascript"

                console.log(obj.a);
                console.log(obj.b);
                console.log(obj.c);
            }

            // 객체 : 데이터 저장 (키와값) : 표현방법 3
            // 많이 쓰는 방식 중 하나로 중간에 데이터를 넣어줄 경우에 사용된다.
            {
                const obj = {}

                obj.a = 100;
                obj.b = 200;
                obj.c = "javascript"

                // a b c 가 키값 숫자 자바가 속성 값

                console.log(obj.a);
                console.log(obj.b);
                console.log(obj.c);

            }
            // 객체 : 데이터 저장 (키와값) : 표현방법 4
            // 가장 자주 쓰고 많이 쓰는 방식으로 한 줄로 입력하는 것이 장점이다.
            {
                const obj = {a:100, b:200, c:"javascript"}
            }
            // 객체 : 데이터 저장 (키와값) : 표현방법 5 : 배열 안에 객체
            // 배열안에 객체가 있는 방식이다. 배열을 먼저 작성 
            // 첫번째 줄이 0 두번째 줄이 1이므로 clg에서 0 0 1로 작성. 
            {
                const obj = [
                    {a:100, b:200},
                    {c:"javascript"}
                ];

                console.log(obj[0].a);
                console.log(obj[0].b);
                console.log(obj[1].c);
            }
            // 객체 : 데이터 저장 (키와값) : 표현방법 6 : 객체 안에 배열로 상단과 반대된다.
            {
                const obj = {
                    a: 100,
                    b: [200, 300],
                    c: {x: 400, y: 500},
                    d: "javascript"
                }

                console.log(obj.a);
                // {}가 객체
                console.log(obj.b[0]);
                // [] 객체 안의 배열
                console.log(obj.b[1]);
                console.log(obj.c.y);
                console.log(obj.c.y);
                console.log(obj.d);
            }
            //b에서 우리가 필요한 건 배열이 아니라 안의 값임 그러므로 .b가 아니라 [0]
 
            // 객체 : 데이터 저장 (키와값) : 표현방법 7
            // 객체 안에 키값에 변수를 저장시킨 것. 객체의 일종  / a 대신에 변수를 넣어준 것이지만 키값이 생략된 것
            {
                const a = 100;
                const b = 200;
                const c = "javascript";

                const obj = {a, b, c};

                console.log(a);
                console.log(b);
                console.log(c);
            }
            // 객체 : 데이터 저장 (키와값) : 표현방법 8
            //변수 안에 함수가 들어갈 수 있다. 함수 : function / 객체 안에는 실행문이 들어갈 수 있다.


            {
                const obj = {
                    a: 100,
                    b: [200, 300],
                    c: "javascript",
                    d: function(){
                        console.log("javascript가 실행되었습니다.");
                    }
                }
            
            
                console.log(obj.a);
                console.log(obj.b[0]);
                console.log(obj.b[1]);
                console.log(obj.b[2]); // 결과 undefiend
                console.log(obj.c);
                console.log(obj.d);//(x)
                obj.d();

            }

            // *변수 : 저장문 : 데이터를 하나 저장 할 수 있음
            // *상수 : 저장문 : 변하지 않는 값
            // *배열 : 저장문 : 두 개 이상 무제한 저장
            // *객체 : 저장문 : 키와 값으로 저장 가능
            // 함수 : 실행문 : 저장된 데이터를 실행을 하기 위해 필요한 것
            
            // 클래스란 함수의 집합체 (잘써야함. 매우 중요)
    </script>