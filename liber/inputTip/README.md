## Welcome to use inputTip!  

It's used to help user select item from a list in which he/she can input keywords.  

Contact me for more information:  

[http://mystist.github.com/][0]  

[0]: http://mystist.github.com/


## Change Log

### 2013-08-27
Add option: `showTipOnClick`.

### 2013-06-03
Add options: `blurHidden`, `clickSelect` and `escHidden`.  
Rewrite the structure of inputTip.
Add event: `option` which use to get/set the options, just like jQueryUI used.  
Add event: `refresh` to refresh your tip after you set some options.  
So, If your dataSourceList is yet to initialized, the tip will show out the loading msg, which can get a better UE.  

Just like:  
//...  
//theList get it's value.  
$("#m_inputTip").inputTip("option", "dataSourceList", theList);  
$("#m_inputTip").inputTip("refresh");  

### 2013-04-23
Set `top: -270px` to the `tipDiv` when it's first initialized.

### 2013-04-08
Add callback function: `tipIsShowing`.  
Add option `scrollTarget` for some complex situation.

### 2013-03-08  
Support display huge datas by using sroll bar, the data will be loading dynamic when srolling to the bottom.  
Add callback function: `clicked` and `tipHasShown`.  
More options can be set.  
Support keyWordsContain mode.  
Add a index column.  

### 2013-02-05  
Add demo.  
Support multi instances in one page.

### 2012-12-05  
Pushed to github.








