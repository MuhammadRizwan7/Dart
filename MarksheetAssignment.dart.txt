void main() {
   
  print("********Mark Sheet      \n");
  
  print("Name:   M.Rizwan");
  print("Father Name:  M.Mushtaq");
  print("Institute:    Karachi University     ");
  
  
  var maxMarks = 100;
  var mathMarks = 87;
  var techengMarks = 66;
  var datastructureMarks = 75;
  var chemistryMarks = 83;
  var phyMarks = 59;
  var totalMarks = maxMarks*5;
  var securedMarks = mathMarks + techengMarks + datastructureMarks + 
    chemistryMarks + phyMarks ;
  
  var percentage =(securedMarks*100)/totalMarks;
  
  
  print("S.No        subject           Max Marks        Marks Obtained ");
  
  print("1             Math           "+maxMarks.toString()+"                            "+mathMarks.toString());
  
  print("2           Tech Eng         "+maxMarks.toString()+"                            "+techengMarks.toString());
  
  print("3         Data Structure     "+maxMarks.toString()+"                            "+datastructureMarks.toString());
  
  print("4          ChemistryMarks    "+maxMarks.toString()+"                            "+chemistryMarks.toString());  
  
  print("5          Physics Marks     "+maxMarks.toString()+"                            "+phyMarks.toString());                    
  
  print("\n");
  
  
  if(mathMarks>50 && techengMarks>50 && datastructureMarks>50 && chemistryMarks>50 && phyMarks>50)
  {
    print("Congratulation you are Passed");}
  
  if(mathMarks<50)
  {
    print("You are failed in Math");
  }
    
   if(techengMarks<50)
  {
    print("You are failed in Math");
  }
   
    if(datastructureMarks<50)
  {
    print("You are failed in Math");
  }
  
    if(chemistryMarks<50)
  {
    print("You are failed in Math");
  }
    
    if(phyMarks<50)
  {
    print("You are failed in Math");
  }
    
  print("\n");
  print("Total Marks:     "+totalMarks.toString());
  print("Marks Secured:   "+securedMarks.toString());
  
  print("percentage:      "+percentage.toString()+"%");
  
  
  if (percentage>=87)
  {
    print("Grade: A");
  }
  
  else if(percentage>=80 && percentage<87)
  {
    print("Grade: B+");
  }
  
   else if(percentage>=72 && percentage<80)
  {
    print("Grade: B");
  }
  
   else if(percentage>=66 && percentage<72)
  {
    print("Grade: C+");
  }
  
   else if(percentage>=60 && percentage<66)
  {
    print("Grade: C");
  }
  
   else if(percentage>=50 && percentage<60)
  {
    print("Grade: D");
  }
  else if(percentage<50)
  {
    print("Grade: F");
  }  
}

