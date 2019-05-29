# FProjectMath
public double calcStanDev (ArrayList<Integer> data) { 
      int x = 0;
      for (int i = 0; i < data.length(); i++) {
         x += (Math.pow ((i - 80), 2);
      }
      
      double StanDev = (Math.pow ((x / data.length()), 0.5);
      return StanDev;
   }
   
   public double calcMean (ArrayList<Integer> data)  {
      double total = 0;
      for (int i = 0; i < data.length(); i++) {
      total += data[i];  
      }
      return total / data.length();
   }
   
   public double calcT  (ArrayList<Integer> data) {
      double t = ((mean - 80) * Math.pow (data.length(), 0.5)) / StanDev ;
      return t;
   }
