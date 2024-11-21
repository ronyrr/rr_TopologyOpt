#   Documentation

The TopologyOPT documentation site. You will find information, mathematical background and features for the three methods implemented:

*   Solid Isotropic Material with Penalisation (SIMP)
*   Bi-directional Evolutionary Structural Optimisation (BESO)
*   Level set method

## Mathematical problem

The mathematical problem is a **minumum compliance** with **volume restriction** for 2D and 3D problems.

## Objective function

The objective function is the compliance. Compliance is a form of energy inversely related to the stiffness of the part. If we want to maximise the stiffness, the problem needs to minimise the compliance.

## Design variables

The design variable is the density of each element of the part.

## Constraints

The physical constraint is the volume of the part. The user defines a volume fraction value target. Additionaly, the user can add geometrical and additive manufacturing restrictions.

### Geometrical restrictions

*   Passive area
*   Minimum size element
*   Maximum size element

### Additive manufacturing restrictions

*   Building direction
*   Anisotropy
*   Multi-material
