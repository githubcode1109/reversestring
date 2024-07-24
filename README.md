# reversestring
class Stringreverse {
    public static void main(String[] args) {
        String s="Hello world!";
        String rev=" ";
        int last=s.length()-1;
        for(int i=0;i<s.length();i++){
            rev=rev+s.charAt(last);
            last--;
        }

          System.out.println("after rev of string:"+rev);
       
    }
}
