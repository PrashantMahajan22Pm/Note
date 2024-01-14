# Note

Angular 17 (2.0)

ANGULAR STRUCTURE 2

  1> e2e folder:-
     e2e stands for "end to end", this is the place where we can write the end-to-end test is an automated test that simulates a real user.


  2> Project Creation:-
                    The Command for project creation " ng new 'PRoject_Name'  ".


 3> Component Creation:-
                     The Command for Component creation is " ng new generate component 'Component_Name'  ".

 4> ParentToChild RelationShip:- 
                         i) (child is a component)child.html Write interpolation statement for accepted from parent.   ii) import Input in component import statement                iii)  and in-class add the  ' @Input ' with a public variable which Bowl with : any type variable. " @Input() public Bowl:any; "

5)  ChildToParent RelationShip:-
                                1) Create a component named a child, go to its child.component.ts file then   ' Output ' import add-in Component import then add EventEmitter import in the separate import statement then create a variable as                                    " @Output() public LaserLight = new EventEmitter();                       "  ' public sendMassage() { this.LaserLight.emit("Hello Parenet");}'
  then go to child.htmlFile.
    This cha[ter is related to the plugIns so when we learn plug Ins then we write Net Things on Parent to Child Communication .



6) InbuiltPipes :-


7) CoustomPipes 24Dec:-


8) Bindings :-
   There are three types of binding 
    i) class binding
    ii)  Style binding 
    iii)
   
10) Toway Communication :-







11) Directives 24Dec:-
    Two types of directives 
    i) Custom directives:-  



12) Template Reference variable :- 
   .hmtl takes  contain  to save into .ts file



12> Tis is a place holder Line
<router-outlet></router-outlet>
           

13>   // Wildcard route / Invalid route
    {path : '**',component:InvalidpageComponent}
  
** It sholud be at the end of the array in Routes array 


Design Types
1> Boost Trap          2> Material design
   |
 Twitter blue print

npm install 

//  C:\Users\HP\OneDrive\Desktop\Angular\MY_Angular\BoostStrapDemo7Jan\node_modules\bootstrap\dist\css\bootstrap.min.css

then copy the bootstrap path 

for go to bootstrap file

then it is put into angular.jason file into double cote  & and change slash direction 


Materail Desing command for 
>ng add @angular/material



any User


[fromGroup]  :-  <!-- It like a structure -->

**   Image  Adding 
   <div>
    <img src="../assets/image/computer.jpg"  alt=" " style="width:150px;height:150px; float: right; padding-right:40px;" > 
</div>


                    
                     

