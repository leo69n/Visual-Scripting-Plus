# Bolt-Beginner-Pack

<h2>***Update Version 1.064 ( working ) :</h2>

<p> </p>

<h2>***Update Version 1.063 ( Submited on Mar 28,2022 ) :</h2>
<b>+ Macro-Pin : </b>
<p>   . Fix name : Size -> Scale </p>
<p>   . Shorten custom event of Pin-Start , Pin-StartSmoothPin </p>
<p> </p>

<b>+ Macro-Bound : </b> Added more events
<p>   . Get random a position inside Box Collider 3D ( Move enemy in random positions )	</p>
<p>   . Get random a position inside Box Collider 2D	</p>
<p>   . Get random a position inside Sphere Collider 3D	</p>
<p>   . Get random a position inside Circle Collider 2D	</p>
<p> </p>

<b>+ Macro-Object : </b>
<p>   . Fix variable == value to String ( now give correct result if input is an Int, Float... on comparasion of = )
<p> </p>

<b>+ Macro-Character : </b>Added more events 
<p>   . Character-MoveToPosition : Move a character ( like patrol enemies ) to a giving position in a giving speed </p>
<p>   . Character-OnEnd-MoveToPosition : Trigger when a character arrived the giving position of [Character-MoveToPosition] and stopped moving ( to track a new route and move that character ( like patrol enemies ) again )</p>
<p>   . Character-PlayAnimation : simply call motion name to run that animation. Don't need to add parameters and Exit-time </p>
<p> </p>

<h2>***Update Version 1.062 ( Submited on Mar 27,2022) :</h2>
<b>+ Macro-Pin : </b>
<p>   . Add [ Pin-StartSmoothPin ] : smoothly follow to an object in a giving time ( to move Camera follow Character smoothly ) </p>
<p>   <b>+ Video tutorial of Macro-Pin :</b> Camera follow Player smoothly uploaded on youtube </p>
<p> </p>

<h2>***Update Version 1.061 ( Submited on Mar 26,2022) :</h2>
+ Macro-Bound ( complete ) :  <br />
		. Added Bound in for 3D objects. ( to limit moving 3D Objects not to move out of a area ) [ Bound-BoundInBoxCollider3D ] [ Bound-BoundInBoxSphere3D ] [ Bound-BoundInBoxCapsule3D ]...  <br />
		. Added Bound in for 2D objects. ( to limit moving 2D Objects not to move out of a area ) [ Bound-BoundInBoxCollider2D ] [ Bound-BoundInBoxCircle2D ]...     <br />
+ Macro-Visible : fix name the variable Visilbe-Invisible.  <br />
+ Video Tutorial of Macro-Bound (create Touch-Control ) uploaded on Youtube. <br />
<p> </p>
<h2>***Update Version 1.06 ( Launched on Mar 25,2022 ) : </h2>
+ Macro-Bound (<b>*NEW</b>) : <br />
<span>     </span>. Return closest position if the giving position is out of the collider of Object. ( Example : To make moving touch control on FPS game ).  <br />
<span>     </span>. Please fix : Macro-System(input) into Macro-Bound. It will be fix it in next update.
+ Macro-Visible : <br /> 
<span>     </span>. Be renamed from Macro-Invisible , and added events Visible-isInScreen ( is Object in working visible screen of Camera ).  <br />
<span>     </span>. Fixed name input into object input ( objects with same name but differnt unique ID still work particularly).  <br />
<span>     </span>. Support to check Character (fbx) in screen ( Parent has Macro-Visible and dont have Mesh Render or Skinned Mesh Render,but its child has it. If its child in screen, parent will be in screen, same as not in screen, Object To Invisible , Object to Visible ).  <br />
+ Macro-Character : <br /> 
<span>     </span>. Fixed to work on multi objects now ( Must add Macro-Character into using Object ).  <br />
+ Macro-Pin : <br /> 
<span>     </span>. Fixed to Pin to object but still keep the original distance. Camera follow Player : simply just add Macro-Pin to Main Camera and drag object Player to Pin-Target slot. There will be tutorial soon !   <br />
