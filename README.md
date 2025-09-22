# microwatt-simd
Microwatt extension project adding a SIMD/Vector accelerator for parallel data operations. Provides hardware support for vectorized math, enabling faster performance in AI, DSP, and graphics workloads compared to scalar execution.
---

## Project Proposal

### Objective
To design and implement a SIMD (Single Instruction Multiple Data) accelerator as an extension to the Microwatt processor, enabling efficient vector operations and improving performance for data-parallel workloads.

## Overview
This project proposes extending the Microwatt POWER ISA softcore with a **Vector/SIMD accelerator**.  
The accelerator enables **parallel execution of arithmetic and logic operations** on multiple data elements simultaneously, improving performance for **AI/ML, DSP, and graphics workloads**.

## Motivation
- Modern workloads like AI inference, image/audio processing, and matrix math rely heavily on vector operations.  
- Microwatt currently executes such tasks serially in software → slow.  
- By adding a SIMD unit, we leverage hardware parallelism for **higher throughput and efficiency**.
  
### Scope
- Add vector processing capability to Microwatt.  
- Implement hardware units for SIMD math operations.  
- Optimize workloads in AI, DSP, and graphics domains.  
- Compare performance vs scalar Microwatt execution.

### Deliverables
- VHDL/Verilog implementation of SIMD extension.  
- Simulation and verification testbenches.  
- Integration with Microwatt core.  
- Performance analysis report.

### Expected Outcomes
- Faster parallel data computation.  
- Hardware acceleration for vector workloads.  
- Demonstration on FPGA or simulator.

 ## Future Scope
- Extend with **custom SIMD instructions** for tighter CPU integration.  
- Support more advanced operations (FFT kernels, convolution).  
- Scale to wider vectors (e.g., 128-bit, 256-bit).  
- Potential as a foundation for AI/ML hardware acceleration.  

---

## Repository Structure
- `/src` → Source code for SIMD extension  
- `/tb` → Testbenches  
- `/docs` → Documentation and design reports  
- `/scripts` → Build and simulation scripts  
