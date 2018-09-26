# 107021153
第一題:攝氏轉華氏溫度

Scanner scn = new Scanner(System.in);
        double C = scn.nextDouble();

        System.out.println(("\r\n")+((C*9/5)+32));

第二題:和,差及成績

Scanner scn = new Scanner(System.in);
        double x = scn.nextDouble();

        double y = scn.nextDouble();

        System.out.println(("\r\n")+("和:")+(x+y));
        System.out.println(("\r\n")+("差:")+(x-y));
        System.out.println(("\r\n")+("積:")+(x*y));

第三題:總分及平均成績

Scanner scn = new Scanner(System.in);
        double x = scn.nextDouble();
        double y = scn.nextDouble();
        double z = scn.nextDouble();
        System.out.println(("\r\n")+(x+y+z));
        System.out.println(("\r\n")+((x+y+z)/3));

第四題:單位換算:身高體重

Scanner scn = new Scanner(System.in);
        double cm = scn.nextDouble();
        double kg = scn.nextDouble();

        System.out.println(("\r\n")+(cm/2.54));
        System.out.println(("\r\n")+(kg/0.454));

第五題:三角形判定
Scanner scn = new Scanner(System.in);
        double a = scn.nextDouble();
        double b = scn.nextDouble();
        double c = scn.nextDouble();
        if (a+b>c && b+c>a && c+a>b && a<=b && b<=c && a<=c){
            System.out.println("True");
        }else {
            System.out.println("Flase");
        }

第六題:閏年

Scanner scn = new Scanner(System.in);

        int a = scn.nextInt();

        if ((a % 4 == 0 && a % 100 != 0) || a % 400 == 0 && (a>0&&a<=3000)){
            System.out.println("True");
        }else {
            System.out.println("Flase");
        }
