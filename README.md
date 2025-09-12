vscode 실행
<img width="1145" height="312" alt="image" src="https://github.com/user-attachments/assets/0dbab82e-6fac-4ae0-86fe-73fd072ad1ed" />

# DongYang_Java

#자바 컴파일해서 클래스 파일로 만들기

javac -cp .  Hellowrold.java

#자바 실행

java -cp . Helloworld.java

# * 중요한것 * 
 파일이름 앞글자는 무조건 대문자로 

<img width="298" height="110" alt="image" src="https://github.com/user-attachments/assets/615d7b9b-3969-442b-aae6-963148be92c1" />

변수초기화 문제

package project2;

public class Errorcode{
	public static void main(String[] args) {
		int value;
		
		//연산 결과물 변수 result 의 초기값으로 대입
		int result = value + 10;
		
		System.out.println(result);
	}
}


package project2;

public class Pufectcode{
	public static void main(String[] args) {
		int hour = 3;
		int minute = 5;
		System.out.println(hour + "시간" + minute +"분");
		
		int totalMinute = (hour*60) + minute;
		System.out.println("총"+totalMinute+"분");
	}
}
