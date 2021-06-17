# This configure Webmin : 
Easy configure :


      sudo nano /etc/apt/sources.list 
      [debhttp://download.webmin.com/download/repository sarge contrib]                                                                                   
      wget http://www.webmin.com/jcameron-key.asc                                                                        
      sudo apt-key add jcameron-key.asc                                                                                 
      sudo apt update                                                                                                    
      sudo apt install webmin -f -y  
      nano -w /etc/webmin/miniserv.conf                                                                                  
      sudo /etc/init.d/webmin restart  
