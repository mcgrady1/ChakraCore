add_library (Chakra.Runtime.Math STATIC
    AsmJsMath.cpp
    JavascriptSSE2MathOperators.cpp
    RuntimeMathPch.cpp
    )

target_include_directories (
    Chakra.Runtime.Math PUBLIC ${CMAKE_CURRENT_SOURCE_DIR})
