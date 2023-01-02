6.858 spring 2020 Notes
===
---

* Lecture 4 Buffer overflows：
    * Defenses
        * NX non-excute: slack as NX,return to IBC
        
        * Stack canary(測試),oxF，funcation point baf--->github ... 
        
        * Address space layout Random (ASLR): Address leaks, guese the xxxx, website, debug/nondebug mode
        
        * Heap overflows , 
            foo(){
        
            }
            attackers can控制一部分內存,data from the Internet
            
        * done side: 


        * 2. Retrofit bounds checks
            * fat pankers : 
            * Referent obj: table, for every pointer keep track/check find the information, 

        * Bagau bound ideas:
            * 1. Each entry counts 16 bytes, table, 
            * 2. Each entry just holds size
            * 3. Allocate only pawers of 2 
            * 4. Allocate only power of 2 address
            * 5. Error when out of bound >= 1/2 slot size
            * 6. OOB < 1/2 slot size mark pointer OOB

* Lecture 5 Privilege separation
    * Pre reading:
        * key negotiation
    * Intro

    * Plan A avoid bugs
        * Bugsin Web servrces
            *    bo
            *    bugs in SQL escaping
            *    forgetting access checks
            *    handling ".." incorrectly
    * Plan B tolerate bugs    
        * Limits the damage of an attack(Least privilege)
        * Limits access to buggy code
            * Recives attack surface
    * Challanges
        1. waht is the separation play?
        2. how to isolate? 
        3. How to share?
        4. maintain performance
    * 
            













Individual Project            
===
標題：online shopping center

（討論每個phase要做什麼）

1. Requirement 
    
2. Design

3. Develop

4. Build

5. Testing

6. Deploy

7. Operation

8. Disposal


