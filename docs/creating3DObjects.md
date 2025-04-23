# Creating Basic 3D Objects

In this exercise, you will create a _GameObject_ to which you will add some materials and physics.

## Creating GameObjects

Use the Hierarchy window's "create" tab. Click on this and then select 3D Object - Plane. You should get something like below (but note the first time you do this it may state "importing assets", which may take a while).

![A Plane](./images/unityOverviewimage4.png)

This plane is a "GameObject" and should appear as the object "Plane" in your Hierarchy view.

![Hierarchy](./images/unityOverviewimage5.png)

Now use the same method to put a cube (this is another of Unity's basic GameObjects) on the plane, again using the create menu. You should get this:

![Cube](./images/unityOverviewimage6.png)

At this point you should have a white cube embedded in a white plane, not ideal. Both the cube and the plane have the same origin. Select the cube in the Hierarchy menu and you can see its position in the "Transform" component in the Inspector window.

Change the Y position to 2. It should now float above the plane.

![Cube](./images/unityOverviewimage7.png)

### Adding Materials

To add some colour to the cube we need to create a material. In the Project view click the create menu and select "Material". A grey sphere should appear at the bottom of your Inspector view. Towards the top of the Inspector window is a colour chooser (white rectangle) next to the word "Albedo" click on the rectangle and choose a bright red colour (RGB, 255,0,0).

![New Material](./images/unityOverviewimage8.png)

You should also see a red sphere called "New Material" in the assets folder in the project view. Drag this red sphere on to the cube in the Scene view.

![Apply Material](./images/unityOverviewimage9.png)

Save your scene - File - Save.

### Adding Physics

Now we have something to look at we can play with the view controls.

The _MeshRenderer_ makes the Object visible, try unticking the check box.

The _BoxCollider_ deals with checking for collisions with other game objects, but nothing is moving yet so we have no collisions.

The game view should appear, but nothing should happen the cube just floats above the plane. There are no forces acting on your scene so nothing will move. Click on the play button again to exit game view. Add a _Rigidbody_ component to your cube ( add component, physics, rigidbody).

Now push play and the cube will drop under the influence of gravity till it hits the plane. Play around with the following component options:

1. Turn off the BoxCollider on the cube or the MeshCollider on the plane. What do you think will happen?

2. Try tilting the plane (with the colliders on) by setting the plane's  x and z rotation values to 2. The friction in the rigidbody should stop the cube from sliding. What happens if you set the values to 20 rather than 2? Has your plane disappeared? If it has why do you think?

3. Delete the cube and add a sphere in the same position instead. Now the sphere should hit the plane and roll off.

4. Try adding a cube that the sphere will hit to deflect its movement. Note you can change the dimension of the cube to make it easier to hit.

You should have something like this (the objects have been coloured to make them easier to see).

![Apply Material](./images/unityOverviewimage10.png)
