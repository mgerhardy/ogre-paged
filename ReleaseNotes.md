# Release notes for version 1.1.1 #
## Changes to 1.1.0 ##
  * Replacement of passing parameters to functions by value to pass by reference if needed. For example, hard types as Ogre::String, Ogre::Vector3, etc.

  * Replacement of Ogre::Material setting from material name to MaterialPtr (no need to search by name in std::map`s of MaterialManager)
  * Rename data members of classes by m