# ListViewUsingArrayAdapter
I learn this from 
http://techlovejump.com/android-arrayadapter-example-listview/
dicoding.com/academies/5
http://android-beginner-lessons.blogspot.co.id/2015/10/android-listactivity.html

##
i look a little different in this code:
###Example 1:
ArrayAdapter arrayAdapter = new ArrayAdapter(this, R.layout.single_item ,eatables); --techlove
Note: have a item.xml

###Example 2:
ArrayAdapter<String> adapter = new ArrayAdapter<String>(MainActivity.this, android.R.layout.simple_list_item_1, 
  android.R.id.text1, footballClubs); --dicoding
  
  Actually this to program have a same function, however app can give listview. 
  But in my opinion from the techlove is more flexibel we can change size padding or anything. 
  Until i found one website (beginner-lesson) that say the example one usually say with ListActivity, 
  which is the different from ListView is just no need layout to make ListView. So, in my assumption 
  this two example not very different function, just one example more flexibel than the other so i put 
  it in same theme apps.
  
  Note: dicoding.com is one from some academy where i learn, however they make student more comfortable 
  for learn. So, i don't say one code is more better. Just want say a little different make a different 
  "title".
  
  Please for someone who read my github to discuss with me if i have a mistake, however programmer must 
  learn from any mistake and improve from that, Thank You :) ..
