# Bolt-Beginner-Pack

<h2>***Update Version 1.061 (working) :</h2>
+ Macro-Bound :  <br />
		. Added Bound in for 3D objects. ( to limit moving 3D Objects not to move out of a area ) [ Bound-BoundInBoxCollider3D ] [ Bound-BoundInBoxShrere3D ]...  <br />
		. Added Bound in for 2D objects. ( to limit moving 2D Objects not to move out of a area ) [ Bound-BoundInBoxCollider2D ] [ Bound-BoundInBoxShrere2D ]...     <br />
+ Macro-Visible : fix name the variable Visilbe-Invisible.  <br />
+ Video Tutorial of Macro-Bound uploaded on Youtube. <br />
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
