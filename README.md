# FIR Filter Implementation

This project demonstrates the implementation of a Finite Impulse Response (FIR) filter using a parametric design approach. The FIR filter has been implemented to allow flexibility in input and output bit widths and filter order.

## Key Characteristics of FIR Filters

1. **Finite Impulse Response**  
   - The filter's impulse response settles to zero in a finite amount of time, as it lacks feedback loops.
   
2. **Linear Phase Response**  
   - Preserves the phase relationships of the signal's frequency components, making it ideal for applications like audio processing.
   
3. **Stability**  
   - Inherently stable as the output depends only on current and past input values.
   
4. **Flexibility**  
   - Can approximate almost any frequency response, supporting a wide range of applications.

## Project Explanation

### Implementation
The FIR filter has been implemented using a **block diagram approach**. The design defines input and output bit widths as parameters, enabling customization to meet specific requirements. A **5th-order filter** has been implemented in this project, but the filter order can be modified easily by adjusting parameters.

### Features
- **Parametric Design**: The filter order, bit widths, and other parameters can be customized.
- **IP Core Integration**: The design supports IP generation for reuse in other projects.

### Figures
- **Figure 1**: FIR Filter block diagram  
- **Figure 2**: IP Core visualization, showcasing the adjustable parameters for filter order and bit widths.

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/alialipour98/FIR-Filter.git
