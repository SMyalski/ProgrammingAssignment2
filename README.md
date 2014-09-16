### Short description

A set of functions enabling caching inverse for given matrix in order to limit computations

makeCacheMatrix function creates CacheMatrix object it can hold matrix and corresponding inverse matrix

cacheSolve shows previously calculated inverse of given matrix when no cached inverse matrix is present it is calculated and stored it requires CacheMatrix object created by makeCacheMatrix function