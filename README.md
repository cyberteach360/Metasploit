

# 🔥 What is Metasploit ?
![metasploit](https://user-images.githubusercontent.com/79256105/115166827-fa859200-a069-11eb-9187-5d9b1bb25023.jpeg)

Metasploit is a penetration testing framework that makes hacking simple. It's an essential tool for many attackers and defenders .

# 👀 How to use Metasploit?

Start Command :

                msfdb init              --------------------- First things first, we need to initialize the database!( This make database for you )
                                                                       Note : It's for new user of msf and use just one time            
                         
                service postsql start 
                         
                msfconsole -h            ----------------------  How to use msfconsole


### 💥 Modules of Metasploit :
![Screenshot (10)](https://user-images.githubusercontent.com/79256105/115166831-007b7300-a06a-11eb-80a5-cde78525b909.png)

                        Exploit 
                        Auxilary
                        Payload
                        Encoder
                        Post
                        Nop
                        Evasion

#### Exploit:
           
   Most common module utilized of metasploit module  , it  holds all of the exploit code that  we will use for exploitation .
        
#### Payload:
   After select exploit according to target we need payload .Payload  used hand in hand with exploits and it contains the various bits of shellcode that's we send to have executed following exploitation .

#### Encoder:
 Commonly utilized in payload obfuscation . It allows us to modify the 'appearance' of our exploit such that we may avoid signature 
        detection .Simply It is use for bypass antivirus of victim machine .
     
#### Auxilary :
   Scanning and verification machines for exploit .Simply , It is use for information gathering about target machine .
          
      
#### Post :
  One of the most common activities after exploitation is looting and pivoting .
   
#### Nop: 
  Nop module is used with buffer overflow and ROP attacks .  
      
          
        
        
             
             
             
             
             
             
             
             
             
             
             
             
