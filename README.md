# SlicingWorkbench

A demo project for the fork of OpenFracture.

## Installing

Prior to opening the scene in Unity, the following assets should be placed in `Assets\TestObjects/`:

 - binoculars\_low.fbx
 - charcoal\_grill\_low.fbx
 - chick2.fbx
 - Fish\_Low.obj
 - SHIRE\_01.fbx

Prior to opening the test scene, please navigate to the Packages window, and ensure you import **Demo Assets** from OpenFracture. This will ensure that default materials are assigned correctly.

## Playing

Import any object, and ensure it has a collider attached, along with the MeshRenderer. Then add the `Slice` component, and bind a material to the **Inside Material** property.

Models with no UVs will be sliceable, but the slice face will only be suitable for solid colour materials.
 
