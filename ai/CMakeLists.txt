add_library(AI ai.h ai.cpp) # you can expend this anyway you want. Just make sure to create an "AI" target...

add_dependencies(AI GRPC_PROTO) # don't touch this :)