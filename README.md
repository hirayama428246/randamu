# randamu
//数当てゲーム　インポート
import java.util.Scanner;

public class Main {
public static void main(String[] args){
        System.out.println("【数当てゲーム】");
            int ans = new java.util.Random().nextInt(10);//乱数作成
                
                
            
            for(int i = 0;i < 5;i++){
                System.out.println("0～9の数字を入力してください");
                //Scanner ans = new Scanner(System.in);
                //int ans2 = selected.next();
                int num = new Scanner(System.in).nextInt();
                if(ans == num ){
                    System.out.println("アタリ！");
                    break;
                    } else {
                    System.out.println("違います");
                    }
            }
                    
                    System.out.println("ゲームを終了します");
}
}
