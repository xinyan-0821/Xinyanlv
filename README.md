# Xinyanlv
My programming code
import java.util.Scanner;
public  class SumArray{
        public static void main(String[] args) {
            Scanner sc = new Scanner(System.in);
            // 读入起始值和终止值
            System.out.print("Enter the start number");;
            int start = sc.nextInt();
            System.out.print("Enter the end number");;
            int end  = sc.nextInt();
// add each element's value to total 保证前方的start 小于end 否则交换
            if (start > end){
                int temp = start;
                start = end;
                end = temp;;
            }
            int sum = 0;
            for (int i = start; i<=end; i++){
                sum += i;
            }
            System.out.println("从 " + start + " 到 " + end + " 的总和为：" + sum);
            }

        }
