# iciba-cmd #

iciba-cmd is a command line tools which used to translate EN to CN or CN to EN and play sound .


## How to setup ##
1.Need Gem nokogiri and colord

  sudo gem install nokogiri <br>
  sudo gem install colored

2.Need mplayer and wget<br>
  In Ubuntu:<br>
  sudo apt-get install mplayer<br>
  sudo apt-get install wget<br>

  In Mac:<br>
  brew install mplayer<br>
  brew install wget<br>

2.In ubuntu need to make iciba executable 
  
  sudo chomd +x iciba

3.copy file iciba to bin directory,such as 'sudo cp iciba /usr/bin/'

4.Usage:

  SHELL$ iciba word    
  SHELL$ iciba "phrase"  
  SHELL$ iciba 爱词霸
