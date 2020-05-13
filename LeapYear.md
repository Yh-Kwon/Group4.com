	public static void main(String[] args) {
		
		//윤년은 특정 년도를 4로 나누어 떨어지지만, 100으로 나누어 떨어지지 않음 혹은 400으로 나누어 떨어짐
		Scanner sc = new Scanner(System.in);
		int year = sc.nextInt();
		boolean bool;

		bool = ((year%4 == 0 && year%100 != 0) || (year%400 == 0));
			System.out.println("결과: " + bool);

		
	}

}
