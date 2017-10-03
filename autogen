	//Author: Linu Cherian
	//autogenerate string method
	public static String autogen(){
		String genString = "";
		String[] symbols = {"a", "b", "c", "d", "e", "f", "g", "h", "i", "j", "k", "l", "m", "n", "o", "p", "q", "r", "s", "t", "u", "v", "w", "x", "y", "z"};
		int length = 5; //length of the genString

		for(int k=0; k<25; k++){
			Random random = new SecureRandom(); 
			StringBuilder sb = new StringBuilder(length);
			for (int i = 0; i < length; i++) {
				int indexRandom = random.nextInt( symbols.length );
				sb.append( symbols[indexRandom] );
			}
			genString = sb.toString();
		}
		return genString;
	}
