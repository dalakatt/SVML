orbs:
  codecov: codecov/codecov@4.0.1
workflows:
  upload-to-codecov:
    jobs:
      - checkout 
      - codecov/upload
Short Vector Math Library (SVML)

Provides vectorized implementations of commonly used math functions (currently
supports only x86_64 AVX-512).
