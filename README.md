 [                                 
 [Code: Melik Erdem Koç
 [Discord:Melik Erdem Koç#0538
 [Linkedin:https://www.linkedin.com/in/melik-erdem-ko%C3%A7-5253061a1/
 [:D
 ----------------------------------
 
 
 package com.melikerdemkocmymessage.java;

import java.util.ArrayList;
import java.util.HashMap;
import java.util.HashSet;

public class Main {

     public static void main (String[] args) {

         String[] myStringArray = new String[4];

         int myIntegerArray = 5;

         myStringArray[0]  =  "James";
         myStringArray[1]  =   "Lars";
         myStringArray[2]  =   "Kirk";
         myStringArray[3] = "Michael";

          System.out.println(myStringArray[1]);

         int [] myIntgerArray = new int [4];
         myStringArray[0] = "50";
         myStringArray[1] = "60";
         myStringArray[2] = "70";
         myStringArray[3] = "80";

         System.out.println(myStringArray[1]);


         int age = 20;
                 System.out.println(10*age);
     System.out.println(age/5);
 int x =15;
  int y =11;
 System.out.println(y/x);


 long mylong = 10;
 System.out.println(mylong/5);

 double z = 5.0;
         double a = 11.0;
         System.out.println(a/z);

         float myfloat = 10.0f;
double pi = 3.14;
         int r = 5;


         System.out.println(2*r*pi);

int myInteger = 5;

         System.out.println("myInteger: " + myInteger);
         myInteger = 4;

         System.out.println("myInteger :" + myInteger);
         int [] myNumberArray = {1,2,3,4,5,6,7,8,9};
         System.out.println(myNumberArray[2]);

         //Lits

         ArrayList<String> myMusicians =  new ArrayList<>();
          myMusicians.add("Sandman/LiL");
                  System.out.println(myMusicians.get(0));

         myMusicians.add("NF/my");
         myMusicians.add("JOker");
         myMusicians.add("Lana Del Rey");

         System.out.println(myMusicians.get(0));
         System.out.println(myMusicians.get(1));
         System.out.println(myMusicians.get(2));

         System.out.println(myMusicians.size());

         //Set
         HashSet<String> mySet = new HashSet<String>();

         mySet.add("NF/");
         mySet.add("Sandman");

         System.out.println(mySet.size());

         //HAshMAp

         HashMap<String, String> myHashMap = new HashMap<String , String>();
         myHashMap.put( "name" , "James");
         myHashMap.put("İnstrument" , "Guitar");

         System.out.printf(myHashMap.get("name"));
         System.out.println(myHashMap.get("instrument"));
























     }

}

 
 
 
