# TestFail
import java.io.IOException;
import java.util.Scanner;

public class Main {


        public static void main(String[] args) {
            //while(true) {
                String valueone = null;
                String valuetwo = null;
                String operation = null;
                String valueRim1 = "0";
                String valueRim2 = "0";

                System.out.println("Введите выражение [1 + 2] или [I + II]");
                Scanner scanner = new Scanner(System.in);
                valueone = scanner.next();
                operation = scanner.next();
                valuetwo = scanner.next();


                if (valueone.equals("I") || valueone.equals("II") || valueone.equals("III") || valueone.equals("IV") || valueone.equals("V") || valueone.equals("VI") || valueone.equals("VII") || valueone.equals("VIII") || valueone.equals("IX") || valueone.equals("X")) {
                    int rimNum1 = 0;
                    int rimNum2 = 0;
                    if (valueone.equals("I") || valueone.equals("II") || valueone.equals("III") || valueone.equals("IV") || valueone.equals("V") || valueone.equals("VI") || valueone.equals("VII") || valueone.equals("VIII") || valueone.equals("IX") || valueone.equals("X")) {
                        if (valueone.equals("I")) {
                            rimNum1 = 1;
                        }
                        if (valueone.equals("II")) {
                            rimNum1 = 2;
                        }
                        if (valueone.equals("III")) {
                            rimNum1 = 3;
                        }
                        if (valueone.equals("IV")) {
                            rimNum1 = 4;
                        }
                        if (valueone.equals("V")) {
                            rimNum1 = 5;
                        }
                        if (valueone.equals("VI")) {
                            rimNum1 = 6;
                        }
                        if (valueone.equals("VII")) {
                            rimNum1 = 7;
                        }
                        if (valueone.equals("VIII")) {
                            rimNum1 = 8;
                        }
                        if (valueone.equals("IX")) {
                            rimNum1 = 9;
                        }
                        if (valueone.equals("X")) {
                            rimNum1 = 10;
                        }
                    }
                    if (valuetwo.equals("I") || valuetwo.equals("II") || valuetwo.equals("III") || valuetwo.equals("IV") || valuetwo.equals("V") || valuetwo.equals("VI") || valuetwo.equals("VII") || valuetwo.equals("VIII") || valuetwo.equals("IX") || valuetwo.equals("X")) {
                        if (valuetwo.equals("I")) {
                            rimNum2 = 1;
                        }
                        if (valuetwo.equals("II")) {
                            rimNum2 = 2;
                        }
                        if (valuetwo.equals("III")) {
                            rimNum2 = 3;
                        }
                        if (valuetwo.equals("IV")) {
                            rimNum2 = 4;
                        }
                        if (valuetwo.equals("V")) {
                            rimNum2 = 5;
                        }
                        if (valuetwo.equals("VI")) {
                            rimNum2 = 6;
                        }
                        if (valuetwo.equals("VII")) {
                            rimNum2 = 7;
                        }
                        if (valuetwo.equals("VIII")) {
                            rimNum2 = 8;
                        }
                        if (valuetwo.equals("IX")) {
                            rimNum2 = 9;
                        }
                        if (valuetwo.equals("X")) {
                            rimNum2 = 10;
                        }
                    }
                    if (rimNum1 < 1 || rimNum1 > 10 || rimNum2 < 1 || rimNum2 > 10) {
                        System.out.println("throws Exception");} else
                        {if (operation.equals("+")) {System.out.println(rimNum1 + rimNum2);}
                        if (operation.equals("-")) {System.out.println(rimNum1 - rimNum2);}
                        if (operation.equals("*")) {System.out.println(rimNum1 * rimNum2);}
                        if (operation.equals("/")) {System.out.println(rimNum1 / rimNum2);}}}

                if(valueone.equals("I") || valueone.equals("II") || valueone.equals("III") || valueone.equals("IV") || valueone.equals("V") || valueone.equals("VI") || valueone.equals("VII") || valueone.equals("VIII") || valueone.equals("IX") || valueone.equals("X")) {}
                else
                    {int value1 = Integer.parseInt(valueone);
                    int value2 = Integer.parseInt(valuetwo);
                if (value1 != 0 || value2 != 0)
                {if (value1 < 1 || value1 > 10 || value2 < 1 || value2 > 10) {System.out.println("throws Exception");}
                else
                {if (operation.equals("+")){System.out.println(value1 + value2);}
                        if (operation.equals("-")) {System.out.println(value1 - value2 );}
                        if (operation.equals("*")) {System.out.println(value1 * value2 );}
                        if (operation.equals("/")) {System.out.println(value1 / value2 );}

                }}}
            }}//}
