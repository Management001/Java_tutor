# Java_tutor

2022년 07월 05일 java 튜티링 배운 과목들 정리.


자바 버추얼 머신는 가장 느릴 수밖에 없다. 인터프리터 언어이기에 자바는 유독 시간초과가 많이 뜬다. 
자바는 class 안에 main 선언 후 작성 방식 
그러므로 무조건 class 안에 함수가 있어야 한다.
그렇지 않으면 안된다.
메서드. = 함수 개념
public static void main(String[] args){
}

이것이 메인 함수이다.

public = 정적 (마음대로 가져다 사용할 수 있다.)
hello 함수를 만들도 같은 폴더에 main 2 에 hello를 사용하고 싶다면 public으로 선언 되어 있다면 가능하지만 private는 불가능할 있다.


출력하는 방법
// TODO Auto-generated method stub
		System.out.println("Hello world");
		System.out.print("Hello world\n"); // ln의 의미가 \n 과 같다. enter
		

입력받는 방법 
자바에서는 독득한 방식이 많다. 동적할당 new 
다양한 방법중에 한가지...


import java.util.Scanner;

공간할당을 해주어야 한다. 스캔할 데이터를 말이다. 그래서... 

Scanner sc = new Scanner(System.in); // 공간을 할당해준다.
		int score = sc.nextInt();


[과제 1.]

https://www.acmicpc.net/problem/1000


package wonder;

import java.util.Scanner;

public class Helloworld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		Scanner sc = new Scanner(System.in); // 공간을 할당해준다.
		int sc1 = sc.nextInt();
		int sc2 = sc.nextInt();
		
		System.out.println(sc1+sc2);
		
	}

}


		

[테스트 1.]

문자열을 받아보자.


package wonder;

import java.util.Scanner;

public class Helloworld {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		
		
		Scanner str_in = new Scanner(System.in);  //문자열을 받는다.
		String str1 = str_in.nextLine();
		System.out.println(str1);
		
		
	}

}




[과제 2.]

https://www.acmicpc.net/problem/1271





















