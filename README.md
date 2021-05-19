# wordpress-brute-force-tool


#    Coder: Cüneyt TANRISEVER                                             
kullanimi=-u url basinda http://  veya https:// koyunuz ve  sonunda / veya/wp-login.php olmasin     
-u http://google.com veya https://google.com/blog gibi  yazabilirsiniz.                   
-urllist burada icinde sadece url http://google.com gibi yukarida                         
yazan kurallara uyularak bir urllistesi olursa saglikli calisir                           
-p sifre listeniz / -p sifre.txt gibi                                                     
-user username yaziniz / -user cuneyt gibi                                                
-userlist birden cok user adina brute yapacaksaniz bunu secin                             
-userlist userler.txt                                                                     
-z zaman araligi sifre denemesini belirtilen sayi kadar sure bekletir                     
kullanim sekilleri                                                                        
 cuneytwpbrute.py -u http://google.com -user cuneyt -p passlist.txt -z 1                             
 cuneytwpbrute.py -u https://google.com -userlist userler.txt -p passlist.txt -z 1                   
 cuneytwpbrute.py -urllist urller.txt -user cuneyt -p passlist.txt -z 1                              
 cuneytwpbrute.py -urllist urller.txt -userlist userler.txt -p passlist.txt -z 1                     
 cuneytwpbrute.py -u http://google.com -user cuneyt -p passlist.txt                                  
 cuneytwpbrute.py -u https://google.com -userlist userler.txt -p passlist.txt                        
 cuneytwpbrute.py -urllist urller.txt -user cuneyt -p passlist.txt                                   
 cuneytwpbrute.py -urllist urller.txt -userlist userler.txt -p passlist.txt                          
