set(LLVM_LINK_COMPONENTS
    AllTargetsAsmPrinters
    AllTargetsAsmParsers
    AllTargetsDescs
    AllTargetsInfos
    MC
    MCParser
    Support
)
add_llvm_fuzzer(llvm-mc-assemble-fuzzer llvm-mc-assemble-fuzzer.cpp)
