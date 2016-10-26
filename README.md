# OOAD-WEEK10
Sequence Diagram

ข้อที่1
```
@startuml
actor me #red
actor teacher 
teacher -> me :command
me -> homework : do
homework --> homework : if homework is ture than pass/else redo
homework -> teacher : pass
homework -> me : redo
@enduml
```
![](http://www.plantuml.com/plantuml/img/LKz13eCm3Blt5P5sHhltWFXAr6OgWZHJ4iJtAHkmSRDZMtO6SrHVU0wON1IOuA6K3-Q4gP12E47NxuwOX1bh3WstIn6cLNI225d2nRgxDBv-R3JmHGcyO8KtcZrfDe9M_9_lh_xuCTsaVSOtC53DxO4D)

ข้อที่2
```
@startuml
actor me #red
actor Taxidriver 
me -> place  : select
place -> Taxidriver : tell
Taxidriver -> Taxi : drive

@enduml
```
![](http://www.plantuml.com/plantuml/img/JOsx3O0m30LxJs69cWLIe0p10b7oYaZc8ySWniU252dlxaalDajgroQKiXtA6tXIb4vhUchHUaEPlCmBdv8oc0Ct2BBHpnw6QM2320scTo-V88hOYv--)

ข้อที่3
```
@startuml
actor me #red
actor Taxidriver
Taxidriver -> me : tell me about money to pay
me -> money : push to pay Taxidriver
money -> Taxidriver : pay
@enduml
```
![](http://www.plantuml.com/plantuml/img/SoWkIImgAStDuKfCBialKiXDLL0kIas1ya8IAp9JYZBBKeku44m5NJkGCYk5ajIS710hCIc_j4GXDpyljLAX95-X8B6I2oWAKWKMib8eA2tEWCeW6mcH1gf3CjiAhDqXDIy5w2O0)

ข้อที่4
```
@startuml
actor me #red
actor opponent
me -> login :put user and password
login -> game :begin in game
game -> opponent : select your opponent
@enduml
```
![](http://www.plantuml.com/plantuml/img/JOx12iCm34Fl-Gh1plk174P_nMjC6QHsi1t6_dxkji90boS9oui7MSoz5rf33JlZOjn-f6Eei4H9-tf3r-qXg6C6fhE1f66G-rEjbM-OhOsoNUzyOEh0yl4oEm-Ymhdp6dZf_DjPM5e-ymO0)

ข้อที่5
```
@startuml
actor me #red
me -> warmbody
warmbody -> basketball : after warm body you can play
@enduml
```
![](http://www.plantuml.com/plantuml/img/DOn13e0W30JllAA9Pp_WmVYL1Uh50gQK67uladZQpUnaZsfGQqaSWXMbnBGeHpTotUc19bzYTt_ve4Uzs3n4Q2ESnZezcdilZG8otOBk3ivnNBy0)


README.md 
md เป็นภาษา Markdown นิยมใช้ใน wiki ของ github 

ตัวอย่างโค้ด
```
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3
 
```

ผลที่ได้
# Heading ระดับ 1 
## Heading ระดับ 2
### Heading ระดับ 3


## Code ภาษาซี

ตัวอย่างโค้ด
<pre>
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
</pre> 
ผลที่ได้
  ``` c
  #include <stdio.h>
  Main()
  {
     Printf("Hello");
  }
  ```
 
