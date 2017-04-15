Dieses git soll als Ressourcen Sammlung für den Easter Hegg 2017 WebPentesting Workshop dienen.

1. Needed Components
2. Links zu den einzelnen Topics
3. Lösungen der OWASP BWA

--------------------------------------
1. Needed Components
  Kali Linux
  Diese Linux Distribution stellt alle benötigten Tools die ich während der Demo verwende zur Verfügung.
  Die verwendeten Tools sind auch auf anderen Distributionen installierbar. Wer also etwas anderes nutzen möchte 
  --> DO IT!
  
  Offical Website:
  
  https://www.kali.org/
  
  Image Direct Link:
    
    Kali Linux VMware Image (64bit)
    https://images.offensive-security.com/virtual-images/Kali-Linux-2016.2-vm-amd64.7z
    Kali Linux VMware Image (32bit)
    https://images.offensive-security.com/virtual-images/Kali-Linux-2016.2-vm-i686.7z
    
    Kali Linux Virtual Box Image(64bit)
    https://images.offensive-security.com/virtual-images/Kali-Linux-2016.2-vbox-amd64.ova
    Kali Linux Virtual Box Image(32bit)
    https://images.offensive-security.com/virtual-images/Kali-Linux-2016.2-vbox-i686.ova
    
    Kali Linux Installation Image (64bit)
    http://cdimage.kali.org/kali-2016.2/kali-linux-2016.2-amd64.iso
    
  OWASP Broken Web Applications Project (BWA)
  Diese VM bietet eine große Anzahl von Verwundbaren Webanwendungen. Teile hiervon sind zwar veraltet, sind aber für Vorführungen 
  immer noch verwendbar.
  
  Offical Website:
  
  https://www.owasp.org/index.php/OWASP_Broken_Web_Applications_Project
  
  Image Direct Link:
    
    Release Page:
    https://sourceforge.net/projects/owaspbwa/files/
    
    Used Image:
    https://sourceforge.net/projects/owaspbwa/files/1.2/
 
--------------------------------------------------

2. Links zu den einzelnen Topics

  OWASP TOP 10
  
    2013: 
    
      ENG: https://www.owasp.org/images/f/f8/OWASP_Top_10_-_2013.pdf
      
      DE: https://www.owasp.org/images/4/42/OWASP_Top_10_2013_DE_Version_1_0.pdf
      
    2017:
    
      ENG: https://github.com/OWASP/Top10/raw/master/2017/OWASP%20Top%2010%20-%202017%20RC1-English.pdf
      
----------------------------------------------------

3. Lösungen der OWASP BWA

    Nach der Präsentation werdet ihr Zeit haben selbst ein wenig an den Maschinen zu hacken. Ihr könnt entweder das dort gezeigte 
    selbst einmal ausprobieren oder auch alles hacken was auf den Servern angeboten wird.
    Da ich selbst noch nicht alle Schwachstellen durchgetestet habe (es sind wirklich viele) kann ich euch aus dem Stand nicht sofort       alle Lösungen liefern. Falls ihr eine Lösung gefunden habt, die sonst im Internet schlecht bis gar nicht Dokumentiert ist, könnt ihr     mir diese über keldorb@gmail.com zukommen lassen. Ich werde diese dann aufbereiten und öffentlich zur Verfügung stellen (ein link zu     eurem Blog Post geht natürlich auch).
    
    Folgende Lösungen kann ich euch präsentieren:
    
      WebGoat.net: 
      
        Exploiting SQL Injection
        File Download Path Manipulation
        
      Security Shepherd:
      
        Lessons:
          Broken Session Managment
          Cross Site Requst Forgery
          Cross Site Scripting
          Failure to Restrict URL Access
          Insecure Cryptographic Storage
          Insecure Direct Object References
          Poor Data Valdiation
          Security Misconfiguration
          SQL Injection
          Unvalidated Redirects and Forwards
        Challenges
          Cross Site Scripting 1
          
      OWASP Bricks:
      
        Login Pages 
          Login #1
        Content Pages
          Content Page #1
     
     ...
     ..
     . to be continued
     
     
          
        
