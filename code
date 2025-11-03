/**教科書第２章の勉強のために作成
*2025/11/01(一日目)
*/
import java.util.Scanner;

public class BMICalculation{
	private double weight;//体重
	private double height;//身長
	/**コンストラクタ
	*@param w 体重
	*@param h 身長
	*/
	public BMICalculation(double w , double h){
		this.weight = w;
		this.height = h;
	}
	//BMIを計算するメソッド
	//return BMIの値
	public double calc(){
		return (weight/(height*height));
		 
	}
	
	public void result(double a){
		if(a<18.5){
			System.out.println("低体重です");
		}else if(a >=25){
			System.out.println("肥満です");
		}else{
			System.out.println("普通です");
		}
	}
	public static void main (String[] args){
		System.out.println("体重を入力してください");
		Scanner sc = new Scanner(System.in);
		double w = sc.nextDouble();
		System.out.println("身長を入力してください");
		double h = sc.nextDouble();
		BMICalculation bmi = new BMICalculation(w,h);
		double retv = bmi.calc();
		System.out.printf("あなたのBMIは%.2fです\n", retv);
		bmi.result(retv);
		
	}
	

}
