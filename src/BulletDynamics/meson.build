

headers = [
    '../btBulletDynamicsCommon.h'
]

headers_ConstraintSolver = [
	'ConstraintSolver/btConeTwistConstraint.h',
	'ConstraintSolver/btConstraintSolver.h',
	'ConstraintSolver/btContactConstraint.h',
	'ConstraintSolver/btContactSolverInfo.h',
	'ConstraintSolver/btFixedConstraint.h',
	'ConstraintSolver/btGearConstraint.h',
	'ConstraintSolver/btGeneric6DofConstraint.h',
	'ConstraintSolver/btGeneric6DofSpringConstraint.h',
	'ConstraintSolver/btGeneric6DofSpring2Constraint.h',
	'ConstraintSolver/btHinge2Constraint.h',
	'ConstraintSolver/btHingeConstraint.h',
	'ConstraintSolver/btJacobianEntry.h',
	'ConstraintSolver/btPoint2PointConstraint.h',
	'ConstraintSolver/btSequentialImpulseConstraintSolver.h',
	'ConstraintSolver/btSequentialImpulseConstraintSolverMt.h',
	'ConstraintSolver/btNNCGConstraintSolver.h',
	'ConstraintSolver/btSliderConstraint.h',
	'ConstraintSolver/btSolve2LinearConstraint.h',
	'ConstraintSolver/btSolverBody.h',
	'ConstraintSolver/btSolverConstraint.h',
	'ConstraintSolver/btTypedConstraint.h',
	'ConstraintSolver/btUniversalConstraint.h'
]

headers_Dynamics = [
	'Dynamics/btActionInterface.h',
	'Dynamics/btDiscreteDynamicsWorld.h',
	'Dynamics/btDiscreteDynamicsWorldMt.h',
	'Dynamics/btSimulationIslandManagerMt.h',
	'Dynamics/btDynamicsWorld.h',
	'Dynamics/btSimpleDynamicsWorld.h',
	'Dynamics/btRigidBody.h'
]

headers_Vehicle = [
	'Vehicle/btRaycastVehicle.h',
	'Vehicle/btVehicleRaycaster.h',
	'Vehicle/btWheelInfo.h'
]

headers_Featherstone = [
	'Featherstone/btMultiBody.h',
	'Featherstone/btMultiBodyConstraint.h',
	'Featherstone/btMultiBodyConstraintSolver.h',
	'Featherstone/btMultiBodyDynamicsWorld.h',
	'Featherstone/btMultiBodyFixedConstraint.h',
	'Featherstone/btMultiBodyGearConstraint.h',
	'Featherstone/btMultiBodyJointLimitConstraint.h',
	'Featherstone/btMultiBodyJointMotor.h',
	'Featherstone/btMultiBodyLink.h',
	'Featherstone/btMultiBodyLinkCollider.h',
	'Featherstone/btMultiBodyMLCPConstraintSolver.h',
	'Featherstone/btMultiBodyPoint2Point.h',
	'Featherstone/btMultiBodySliderConstraint.h',
	'Featherstone/btMultiBodySolverConstraint.h'
]

headers_MCLPSolvers = [
	'MLCPSolvers/btDantzigLCP.h',
	'MLCPSolvers/btDantzigSolver.h',
	'MLCPSolvers/btMLCPSolver.h',
	'MLCPSolvers/btMLCPSolverInterface.h',
	'MLCPSolvers/btPATHSolver.h',
	'MLCPSolvers/btSolveProjectedGaussSeidel.h',
	'MLCPSolvers/btLemkeSolver.h',
	'MLCPSolvers/btLemkeAlgorithm.h'
]

headers_Character = [
	'Character/btCharacterControllerInterface.h',
	'Character/btKinematicCharacterController.h'
]

install_headers( headers )
install_headers( headers_ConstraintSolver, subdir : 'BulletDynamics/ConstraintSolver' )
install_headers( headers_Dynamics, subdir : 'BulletDynamics/Dynamics' )
install_headers( headers_Vehicle, subdir : 'BulletDynamics/Vehicle' )
install_headers( headers_Featherstone, subdir : 'BulletDynamics/Featherstone' )
install_headers( headers_MCLPSolvers, subdir : 'BulletDynamics/MLCPSolvers' )
install_headers( headers_Character, subdir : 'BulletDynamics/Character' )

sources = [
	'Character/btKinematicCharacterController.cpp',
	'ConstraintSolver/btConeTwistConstraint.cpp',
	'ConstraintSolver/btContactConstraint.cpp',
	'ConstraintSolver/btFixedConstraint.cpp',
	'ConstraintSolver/btGearConstraint.cpp',
	'ConstraintSolver/btGeneric6DofConstraint.cpp',
	'ConstraintSolver/btGeneric6DofSpringConstraint.cpp',
	'ConstraintSolver/btGeneric6DofSpring2Constraint.cpp',
	'ConstraintSolver/btHinge2Constraint.cpp',
	'ConstraintSolver/btHingeConstraint.cpp',
	'ConstraintSolver/btPoint2PointConstraint.cpp',
	'ConstraintSolver/btSequentialImpulseConstraintSolver.cpp',
	'ConstraintSolver/btSequentialImpulseConstraintSolverMt.cpp',
	'ConstraintSolver/btBatchedConstraints.cpp',
	'ConstraintSolver/btNNCGConstraintSolver.cpp',
	'ConstraintSolver/btSliderConstraint.cpp',
	'ConstraintSolver/btSolve2LinearConstraint.cpp',
	'ConstraintSolver/btTypedConstraint.cpp',
	'ConstraintSolver/btUniversalConstraint.cpp',
	'Dynamics/btDiscreteDynamicsWorld.cpp',
	'Dynamics/btDiscreteDynamicsWorldMt.cpp',
	'Dynamics/btSimulationIslandManagerMt.cpp',
	'Dynamics/btRigidBody.cpp',
	'Dynamics/btSimpleDynamicsWorld.cpp',
#	'Dynamics/Bullet-C-API.cpp',
	'Vehicle/btRaycastVehicle.cpp',
	'Vehicle/btWheelInfo.cpp',
	'Featherstone/btMultiBody.cpp',
	'Featherstone/btMultiBodyConstraint.cpp',
	'Featherstone/btMultiBodyConstraintSolver.cpp',
	'Featherstone/btMultiBodyDynamicsWorld.cpp',
	'Featherstone/btMultiBodyFixedConstraint.cpp',
	'Featherstone/btMultiBodyGearConstraint.cpp',
	'Featherstone/btMultiBodyJointLimitConstraint.cpp',
	'Featherstone/btMultiBodyJointMotor.cpp',
	'Featherstone/btMultiBodyMLCPConstraintSolver.cpp',
	'Featherstone/btMultiBodyPoint2Point.cpp',
	'Featherstone/btMultiBodySliderConstraint.cpp',
	'Featherstone/btMultiBodySphericalJointMotor.cpp',
	'MLCPSolvers/btDantzigLCP.cpp',
	'MLCPSolvers/btMLCPSolver.cpp',
	'MLCPSolvers/btLemkeAlgorithm.cpp'
]

bullet_bd_lib = library( 'BulletDynamics', include_directories : include, sources : sources, link_with : [ bullet_lm_lib, bullet_bc_lib ], install : true )
