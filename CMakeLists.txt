set(LLVM_LINK_COMPONENTS core jit interpreter native)
set(LLVM_REQUIRES_RTTI 1)

add_llvm_example(culeidoscope
  toy.cpp
  )