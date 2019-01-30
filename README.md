# AndroidXMigrationAndFlavors

Demonstrate AndroidX Migration failure with product flavors.

Studio fails by replacing “androidx.constraintlayout.ConstraintLayout” instead of
“androidx.constraintlayout.widget.ConstraintLayout”. Causes a runtime classnotfound failure,
java.lang.ClassNotFoundException: Didn't find class "androidx.constraintlayout.ConstraintLayout" on path: DexPathList
