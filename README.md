# Lesson4_task 10
public static void main(String args[]) {
Scanner scanner = new Scanner(System.in);
   int dayOfWeek = scanner.nextInt();
   switch (dayOfWeek) {
            case 1: 
                    System.out.println("понедельник");
                    break;
            case 2:
                    System.out.println("вторник");
                    break;
            case 3:
                    System.out.println("среда");
                    break;
            case 4: 
                    System.out.println("четверг");
                    break;
            case 5:
                    System.out.println("пятница");
                    break;
            case 6: 
                    System.out.println("суббота");
                    break;
            case 7: 
                    System.out.println("воскресенье");
                    break;
            default: 
                    System.out.println("некорректное число, выберите от 1 до 7");
                    break;
   }
 }  
