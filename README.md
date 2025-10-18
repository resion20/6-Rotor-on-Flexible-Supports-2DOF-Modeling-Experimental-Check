# 6-Rotor-on-Flexible-Supports-2DOF-Modeling-Experimental-Check
This work modeled a rotor assembly (shaft + three rods) mounted on flexible supports as a two-degree-of-freedom system—one translational and one rotational—to study its small-oscillation dynamics and validate theory against experiment. 


What was done

Free-body diagram & EOM: Derived translational and rotational equations using Newtonian mechanics for small motions; assembled in matrix form. 

Mass & inertia estimation: Computed component masses and moments (disk, plate, shaft, rods) from CAD geometry and material densities; consolidated shaft+rods as a single rotating body. 

Support stiffness: Modeled four vertical rods as cantilever beams; calculated total translational stiffness from bending theory. 

Natural frequencies: Solved the eigenvalue problem, obtaining f₁ ≈ 7.16 Hz and f₂ ≈ 32.59 Hz for the simplified 2DOF model. 

Experimental comparison: Performed vibration tests (shaker + accelerometers) and compared measured modes to theory; discussed discrepancies due to idealizations, material variability, and fixture/sensor effects. 

Results

Theoretical natural frequencies: ~7.16 Hz, 32.59 Hz (2DOF model).

Model validity: Predictions were reasonable given assumptions; differences traced to neglected details (holes/bolts/joints), damping/nonlinearities, and parameter estimation.
