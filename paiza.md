//




//②三角形の内角の和
import java.util.*;


public class Main {
    public static void main(String[] args) {
        // 自分の得意な言語で
        // Let's チャレンジ！！

        Scanner sc = new Scanner(System.in);
        int num1 = sc.nextInt();
        int num2 = sc.nextInt();
        
        int num3 = 180 - (num1 + num2);
        
        System.out.println(num3);
    }
}

//①あなたは単純な運賃計算のプログラムを作成しています。
//
//その運賃計算は以下のルールで行われます。
//
//・初乗り運賃 100 円
//・1 区間ごとに 10 円ずつ加算
//
//ある乗客の乗った区間数 N が与えられるので運賃がいくらかを出力するプログラムを作成してください。
//
//例えば入力例 1の場合
//
//3
//3 区間乗ったので 100 + 3 × 10 という計算となるので、以下のように出力してください。
//130
import java.util.*;


public class Main {
    public static void main(String[] args) {
        // 自分の得意な言語で
        // Let's チャレンジ！！

        Scanner sc = new Scanner(System.in);
        int line = sc.nextInt();
        int sum =100+ (line*10);
        
        System.out.println(sum);
    }
}
