
headers = [
	'btAabbUtil2.h',
	'btAlignedAllocator.h',
	'btAlignedObjectArray.h',
	'btConvexHull.h',
	'btConvexHullComputer.h',
	'btDefaultMotionState.h',
	'btGeometryUtil.h',
	'btGrahamScan2dConvexHull.h',
	'btHashMap.h',
	'btIDebugDraw.h',
	'btList.h',
	'btMatrix3x3.h',
	'btImplicitQRSVD.h',
	'btMinMax.h',
	'btMotionState.h',
	'btPolarDecomposition.h',
	'btPoolAllocator.h',
	'btQuadWord.h',
	'btQuaternion.h',
	'btQuickprof.h',
	'btRandom.h',
	'btScalar.h',
	'btSerializer.h',
	'btStackAlloc.h',
	'btThreads.h',
	'btTransform.h',
	'btTransformUtil.h',
	'btVector3.h'
]

headers_TaskScheduler = [
	'TaskScheduler/btThreadSupportInterface.h'
]

install_headers( headers, subdir : 'LinearMath' )
install_headers( headers_TaskScheduler, subdir : 'LinearMath/TaskScheduler' )

sources = [
    'btAlignedAllocator.cpp',
    'btConvexHull.cpp',
    'btConvexHullComputer.cpp',
    'btGeometryUtil.cpp',
    'btPolarDecomposition.cpp',
    'btQuickprof.cpp',
    'btSerializer.cpp',
    'btSerializer64.cpp',
    'btThreads.cpp',
    'btVector3.cpp',
    'TaskScheduler/btTaskScheduler.cpp',
	'TaskScheduler/btThreadSupportPosix.cpp',
	'TaskScheduler/btThreadSupportWin32.cpp'
]

bullet_lm_lib = library( 'LinearMath', include_directories : include, sources : sources, install : true )
